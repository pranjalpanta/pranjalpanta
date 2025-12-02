<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pranjal Panta | Networking & Cybersecurity Profile</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom CSS for the Neon Pulse Effect - Retained for the footer */
        @keyframes neon-pulse {
            0% { 
                /* Starting smaller glow */
                text-shadow: 
                    0 0 4px #00FF90, 
                    0 0 8px rgba(0, 255, 144, 0.5);
                opacity: 0.9;
            }
            50% { 
                /* Maximum glow (Breathing out) */
                text-shadow: 
                    0 0 8px #00FF90, 
                    0 0 16px rgba(0, 255, 144, 0.8), 
                    0 0 30px #00FF90; 
                opacity: 1;
            }
            100% { 
                /* Back to smaller glow (Breathing in) */
                text-shadow: 
                    0 0 4px #00FF90, 
                    0 0 8px rgba(0, 255, 144, 0.5); 
                opacity: 0.9;
            }
        }

        .pulsing-text {
            /* Apply the animation: 2 seconds duration, infinite loop, alternates direction */
            animation: neon-pulse 2s infinite alternate; 
        }

        /* Gradient Divider Styling */
        .gradient-divider {
            height: 3px;
            width: 100%;
            background: linear-gradient(90deg, #FF00FF 0%, #00FFFF 25%, #00FF00 50%, #FFFF00 75%, #FF0000 100%);
            border-radius: 3px;
        }

        /* Style for neon bullet points */
        .neon-list li::before {
            content: "•"; /* Use a standard bullet */
            color: #00FF90; /* Neon green color */
            font-size: 1.2em;
            margin-right: 0.5rem;
            display: inline-block;
        }
        
        /* Neon style for headings */
        .neon-heading {
            color: #00FF90;
            text-shadow: 0 0 5px #00FF90, 0 0 10px rgba(0, 255, 144, 0.4);
            border-bottom: 2px solid rgba(0, 255, 144, 0.2);
            padding-bottom: 0.5rem;
        }
    </style>
</head>
<body class="bg-gray-900 flex items-center justify-center min-h-screen p-4 font-['Inter']">

    <!-- Main Profile Container -->
    <div class="w-full max-w-5xl bg-gray-950 rounded-2xl p-6 sm:p-10 shadow-[0_0_50px_rgba(0,255,140,0.1)] border border-[#00FF90] border-opacity-20 text-gray-300 space-y-12">

        <!-- Header and Main Title Section -->
        <div class="text-center space-y-4">
            <!-- Typing SVG Header (Embedded) -->
            <div class="mb-6">
                <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=2500&pause=800&color=00FF41&center=true&vCenter=true&width=800&lines=%F0%9D%97%A3%F0%9D%97%BF%F0%9D%97%BC%F0%9D%97%B3%F0%9D%97%B6%F0%9D%97%BB%F0%9D%97%B2+%F0%9D%97%A5%F0%9D%97%BC%F0%9D%97%B2%F0%9D%97%B2%F0%9D%97%B6%F0%9D%97%B2%F0%9D%97%B3..." alt="Profile Loaded Typing SVG" class="mx-auto w-full max-w-lg">
            </div>

            <!-- Name and Subtitle -->
            <h1 class="text-5xl font-extrabold text-white">
                Hi, I'm <span class="neon-heading p-0 border-none inline-block">Pranjal Panta</span> 👋
            </h1>
            <h2 class="text-2xl font-light text-cyan-400">
                Networking & Cybersecurity Researcher
            </h2>
        </div>

        <!-- Section Divider -->
        <hr class="border-gray-700/50">

        <!-- About/Goal Section -->
        <div class="space-y-4">
            <p class="text-lg">
                💡 **Dedicated to enterprise networking and security engineering**
            </p>
            <p class="text-lg">
                🔧 **Currently learning:** CCNA, ASA Firewall, Routing and Switching
            </p>
            <p class="text-lg">
                🎯 **Goal:** Become a Network Engineer & Security Specialist
            </p>
        </div>

        <!-- Skills & Tools Section -->
        <div class="space-y-6">
            <h3 class="text-3xl font-bold neon-heading">🛠 Skills & Tools</h3>
            <div class="grid md:grid-cols-2 gap-8 text-lg">
                <!-- Networking/Routing/Firewalls Column -->
                <div class="space-y-4 bg-gray-800/50 p-6 rounded-lg border border-gray-700">
                    <h4 class="text-xl font-semibold text-[#00FF90]">Core Disciplines</h4>
                    <ul class="list-none space-y-2 pl-0 neon-list">
                        <li>**Networking:** VLANs, STP, SVI, DHCP, NAT, Port Security</li>
                        <li>**Routing:** RIP, OSPF, EIGRP, BGP, IS-IS</li>
                        <li>**Firewalls:** Cisco ASA, ACLs, VPN</li>
                    </ul>
                </div>
                
                <!-- Cybersecurity/Tools Column -->
                <div class="space-y-4 bg-gray-800/50 p-6 rounded-lg border border-gray-700">
                    <h4 class="text-xl font-semibold text-[#00FF90]">Security & Tools</h4>
                    <ul class="list-none space-y-2 pl-0 neon-list">
                        <li>**Cybersecurity:** Network Forensics, Linux Fundamentals, Operating System, Practical Penstesting, Basic Web Application Security</li>
                        <li>**Tools:** Cisco Packet Tracer, GNS3, Wireshark</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- Featured Projects Section -->
        <div class="space-y-6">
            <h3 class="text-3xl font-bold neon-heading">📂 Featured Projects</h3>
            <ul class="list-none space-y-3 text-lg neon-list pl-0">
                <li>🔹 **Three-Tier Enterprise Network Design**</li>
                <li>🔹 **Cisco ASA Firewall Configuration**</li>
                <li>🔹 **Secure File Tool (Python)**</li>
                <li>🔹 **WEB EMUMERATION TOOL (Python)**</li>
            </ul>
        </div>

        <!-- Connect Section -->
        <div class="space-y-6">
            <h3 class="text-3xl font-bold neon-heading">🌐 Connect With Me</h3>
            <div class="flex flex-wrap justify-center gap-4">
                <a href="https://www.linkedin.com/in/pranjal-p-49ab59293/" target="_blank">
                    <img src="https://img.shields.io/badge/LinkedIn-Pranjal%20Panta-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn Badge" class="rounded">
                </a>
                <a href="mailto:pranjalpantalazarus2@gmail.com" target="_blank">
                    <img src="https://img.shields.io/badge/Email-Contact%20Me-red?style=for-the-badge&logo=gmail" alt="Email Badge" class="rounded">
                </a>
                <a href="https://github.com/pranjalpanta" target="_blank">
                    <img src="https://img.shields.io/badge/GitHub-pranjalpanta-black?style=for-the-badge&logo=github" alt="GitHub Badge" class="rounded">
                </a>
                <a href="https://medium.com/@pranjalpanta2.0" target="_blank">
                    <img src="https://img.shields.io/badge/Medium-Articles%20%26%20Blogs-green?style=for-the-badge&logo=medium" alt="Medium Badge" class="rounded">
                </a>
            </div>
        </div>
        
        <!-- Footer and Pulsing Neon Message (Retaining the original aesthetic) -->
        <div class="flex flex-col items-center pt-8">
            <!-- Top Divider -->
            <div class="gradient-divider mb-6 transform rotate-180"></div>

            <!-- The Pulsing Neon Text -->
            <p class="pulsing-text font-mono font-extrabold text-xl sm:text-2xl" 
               style="color: #00FF90; margin: 0;">
                Thanks for visiting my profile, see you next time!
            </p>

            <!-- Bottom Divider -->
            <div class="gradient-divider mt-6"></div>
        </div>

    </div>

</body>
</html>
        
















---



<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
