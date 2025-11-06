<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Isratul Anower Sijan | Student Profile</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Load Lucide Icons for professional icons -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        /* Custom styles to ensure the font looks great */
        html {
            font-family: 'Inter', sans-serif;
        }
        /* Custom scrollbar for aesthetics (now green) */
        body::-webkit-scrollbar {
            width: 8px;
        }
        body::-webkit-scrollbar-thumb {
            background-color: #10b981; /* Emerald Green */
            border-radius: 10px;
        }
        body::-webkit-scrollbar-track {
            background: #1f2937;
        }
    </style>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        // Updated to a Green palette (Emerald 500: #10b981)
                        'primary-green': '#10b981', 
                        'secondary-gray': '#1f2937',
                    }
                }
            }
        }

        // Script to initialize Lucide icons after page load
        document.addEventListener('DOMContentLoaded', () => {
            lucide.createIcons();
        });
    </script>
</head>
<body class="min-h-screen bg-gray-900 text-gray-100 p-4 flex items-center justify-center">

    <!-- Main Profile Card Container -->
    <div class="w-full max-w-lg mx-auto bg-gray-800 p-8 md:p-10 rounded-xl shadow-2xl transition duration-300 hover:shadow-primary-green/50">

        <!-- Header and Personal Info -->
        <header class="text-center mb-8">
            <!-- Profile Avatar Placeholder (now green) -->
            <div class="w-24 h-24 bg-primary-green/20 text-primary-green rounded-full flex items-center justify-center mx-auto mb-4 border-4 border-primary-green/50 text-3xl font-bold">
                IAS
            </div>

            <h1 class="text-4xl font-extrabold tracking-tight text-white mb-1">
                ISRATUL ANOWER SIJAN
            </h1>
            <p class="text-xl font-semibold text-primary-green">
                IAS 
            </p>
        </header>

        <!-- Academic Section -->
        <section class="mb-8 border-t border-b border-gray-700 py-6">
            <h2 class="text-lg font-bold text-gray-300 mb-3 flex items-center">
                <i data-lucide="graduation-cap" class="w-5 h-5 mr-2 text-primary-green"></i>
                Academic Profile
            </h2>
            <ul class="space-y-2 text-gray-300">
                <li class="flex items-center">
                    <span class="font-medium w-1/3 text-gray-400">Institution:</span>
                    <span class="font-semibold text-white">Dhaka College</span>
                </li>
                <li class="flex items-center">
                    <span class="font-medium w-1/3 text-gray-400">Department:</span>
                    HSC Science Department
                </li>
                <li class="flex items-center">
                    <span class="font-medium w-1/3 text-gray-400">SSC Status:</span>
                    Passed in 2025
                </li>
            </ul>
        </section>

        <!-- Contact and Social Links -->
        <section>
            <h2 class="text-lg font-bold text-gray-300 mb-4 flex items-center">
                <i data-lucide="link-2" class="w-5 h-5 mr-2 text-primary-green"></i>
                Connect with Me
            </h2>
            <div class="space-y-4">
                <!-- Email Link - Now clearly displays the address -->
                <a href="mailto:ias32118721@gmail.com"
                   class="flex items-center p-3 rounded-lg bg-gray-700 hover:bg-primary-green hover:text-white transition duration-200 shadow-md">
                    <i data-lucide="mail" class="w-5 h-5 mr-3"></i>
                    <span class="font-medium">Email:</span>
                    <span class="ml-auto font-mono text-sm"></span>
                </a>

                <!-- Instagram Link -->
                <a href="https://www.instagram.com/_n_eo_n__n_o_m_ad_/" target="_blank"
                   class="flex items-center p-3 rounded-lg bg-gray-700 hover:bg-pink-600 hover:text-white transition duration-200 shadow-md">
                    <i data-lucide="instagram" class="w-5 h-5 mr-3"></i>
                    <span class="font-medium">Instagram Profile</span>
                    <i data-lucide="arrow-right" class="w-4 h-4 ml-auto"></i>
                </a>

                <!-- Facebook Link -->
                <a href="https://www.facebook.com/ia.sijan.2025" target="_blank"
                   class="flex items-center p-3 rounded-lg bg-gray-700 hover:bg-blue-600 hover:text-white transition duration-200 shadow-md">
                    <i data-lucide="facebook" class="w-5 h-5 mr-3"></i>
                    <span class="font-medium">Facebook Profile</span>
                    <i data-lucide="arrow-right" class="w-4 h-4 ml-auto"></i>
                </a>
            </div>
        </section>

        <!-- Footer / Closing Statement -->
        <footer class="mt-8 pt-4 border-t border-gray-700 text-center text-sm text-gray-500">
            &copy; 2025 Isratul Anower Sijan. Designed for a professional introduction.
        </footer>

    </div>
</body>
</html>
