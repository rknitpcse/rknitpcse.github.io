<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Er. Rakesh Kumar - Personal Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc; /* slate-50 */
            color: #475569; /* slate-600 */
        }
        .hero-bg {
            background-color: #f1f5f9; /* slate-100 */
        }
        .section-title {
            color: #0f172a; /* slate-900 */
        }
        .nav-link {
            transition: color 0.3s ease;
        }
        .nav-link:hover {
            color: #4338ca; /* indigo-700 */
        }
        .timeline-item::before {
            content: '';
            position: absolute;
            width: 1rem;
            height: 1rem;
            border-radius: 50%;
            left: -2.5rem;
            top: 0.35rem;
            background-color: #4f46e5; /* indigo-600 */
            border: 4px solid #e0e7ff; /* indigo-100 */
        }
        .card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);
        }
        .section-icon {
            color: #4f46e5;
        }
    </style>
</head>
<body class="antialiased">

    <!-- Header & Navigation -->
    <header id="header" class="fixed top-0 left-0 right-0 z-50 bg-white/90 backdrop-blur-sm shadow-md transition-all duration-300">
        <div class="container mx-auto px-6 py-4">
            <div class="flex items-center justify-between">
                <a href="#" class="text-2xl font-extrabold text-slate-900">Er. RAKESH KUMAR</a>
                <nav class="hidden lg:flex items-center space-x-6">
                    <a href="#about" class="nav-link text-slate-700 font-medium">About</a>
                    <a href="#experience" class="nav-link text-slate-700 font-medium">Experience</a>
                    <a href="#education" class="nav-link text-slate-700 font-medium">Education</a>
                    <a href="#achievements" class="nav-link text-slate-700 font-medium">Achievements</a>
                    <a href="#contact" class="nav-link text-slate-700 font-medium">Contact</a>
                </nav>
                <button id="mobile-menu-button" class="lg:hidden text-slate-800">
                    <i class="fas fa-bars text-2xl"></i>
                </button>
            </div>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden lg:hidden">
            <a href="#about" class="block py-2 px-6 text-sm text-slate-700 hover:bg-slate-100">About</a>
            <a href="#experience" class="block py-2 px-6 text-sm text-slate-700 hover:bg-slate-100">Experience</a>
            <a href="#education" class="block py-2 px-6 text-sm text-slate-700 hover:bg-slate-100">Education</a>
            <a href="#achievements" class="block py-2 px-6 text-sm text-slate-700 hover:bg-slate-100">Achievements</a>
            <a href="#certifications" class="block py-2 px-6 text-sm text-slate-700 hover:bg-slate-100">Certifications</a>
            <a href="#research" class="block py-2 px-6 text-sm text-slate-700 hover:bg-slate-100">Interests</a>
            <a href="#extra-curriculars" class="block py-2 px-6 text-sm text-slate-700 hover:bg-slate-100">Extra Curriculars</a>
            <a href="#contact" class="block py-2 px-6 text-sm text-slate-700 hover:bg-slate-100">Contact</a>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section id="home" class="hero-bg pt-32 pb-20 md:pt-48 md:pb-32">
            <div class="container mx-auto px-6">
                <div class="flex flex-col md:flex-row items-center">
                    <div class="md:w-3/5 text-center md:text-left mb-10 md:mb-0">
                        <h1 class="text-4xl md:text-6xl font-extrabold text-slate-900 leading-tight mb-4">Er. RAKESH KUMAR</h1>
                        <p class="text-xl text-slate-700 mb-6">A <strong class="text-indigo-600">Cloud Computing</strong> enthusiast.</p>
                        <p class="text-lg text-slate-600 mb-8">Currently working as a <strong class="font-semibold">Lead Founding Engineer</strong> at <a href="https://oculon.ai/" target="_blank" class="text-indigo-600 hover:underline">Oculon.ai</a>.</p>
                        <a href="#contact" class="bg-indigo-600 text-white font-bold py-3 px-8 rounded-full hover:bg-indigo-700 transition-all duration-300 inline-block">Contact Me</a>
                    </div>
                    <div class="md:w-2/5 flex justify-center">
                        <div class="w-64 h-64 md:w-80 md:h-80 rounded-full overflow-hidden shadow-2xl border-8 border-white bg-indigo-200 flex items-center justify-center">
                             <img src="https://placehold.co/400x400/e0e7ff/4338ca?text=RK" alt="Er. Rakesh Kumar" class="w-full h-full object-cover">
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- About / Personal Section -->
        <section id="about" class="py-20">
            <div class="container mx-auto px-6">
                 <div class="text-center mb-12">
                    <i class="fas fa-user-circle fa-3x section-icon mb-4"></i>
                    <h2 class="section-title text-3xl font-bold">Personal Details</h2>
                </div>
                <div class="max-w-4xl mx-auto bg-white p-8 rounded-xl shadow-md">
                    <ul class="space-y-4 text-slate-700">
                        <li><strong>Parents:</strong> Mr. Ramashish Prasad (Business-Man) and Mrs. Sharada Devi (Home-Maker)</li>
                        <li><strong>Siblings:</strong> 3 Sisters and 1 Brother {Sr. Auditor at <a href="https://cgda.nic.in/" target="_blank" class="text-indigo-600 hover:underline">CGDA Patna</a>}</li>
                        <li><strong>Birth Place:</strong> <a href="https://en.wikipedia.org/wiki/Hisua" target="_blank" class="text-indigo-600 hover:underline">Hisua, Bihar, India</a></li>
                        <li><strong>Date of Birth:</strong> 1st February 1996</li>
                    </ul>
                </div>
            </div>
        </section>
        
        <!-- Industry Experience Section -->
        <section id="experience" class="py-20 bg-slate-100">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <i class="fas fa-briefcase fa-3x section-icon mb-4"></i>
                    <h2 class="section-title text-3xl font-bold">Industry Experience</h2>
                </div>
                <div class="relative max-w-3xl mx-auto">
                    <div class="absolute left-0 top-0 bottom-0 w-0.5 bg-slate-300 ml-2"></div>
                    <!-- Experience Items -->
                    <div class="mb-10 pl-12 relative timeline-item">
                        <h3 class="text-xl font-bold text-slate-800">Lead Founding Engineer</h3>
                        <p class="text-indigo-600 font-medium mb-1"><a href="https://oculon.ai/" target="_blank" class="hover:underline">Oculon.ai</a>, United States - Remote | NOV 2024 - Present</p>
                    </div>
                     <div class="mb-10 pl-12 relative timeline-item">
                        <h3 class="text-xl font-bold text-slate-800">Member of Technical Staff (MTS)</h3>
                        <p class="text-indigo-600 font-medium mb-1"><a href="https://en.wikipedia.org/wiki/Salesforce" target="_blank" class="hover:underline">Salesforce</a>, Hyderabad | DEC 2023 - OCT 2024</p>
                    </div>
                    <div class="mb-10 pl-12 relative timeline-item">
                        <h3 class="text-xl font-bold text-slate-800">Applications Developer 2</h3>
                        <p class="text-indigo-600 font-medium mb-1"><a href="https://en.wikipedia.org/wiki/Oracle_Corporation" target="_blank" class="hover:underline">Oracle Cloud HCM</a>, Hyderabad | MAY 2022 - DEC 2023</p>
                    </div>
                    <div class="mb-10 pl-12 relative timeline-item">
                        <h3 class="text-xl font-bold text-slate-800">Software Development Engineer II</h3>
                        <p class="text-indigo-600 font-medium mb-1"><a href="https://www.progress.com/" target="_blank" class="hover:underline">Progress Software</a>, Hyderabad | JAN 2022 - MAY 2022</p>
                    </div>
                    <div class="mb-10 pl-12 relative timeline-item">
                        <h3 class="text-xl font-bold text-slate-800">Software Development Engineer I</h3>
                        <p class="text-indigo-600 font-medium mb-1"><a href="https://www.progress.com/" target="_blank" class="hover:underline">Progress Software</a>, Hyderabad | JUN 2020 - DEC 2021</p>
                    </div>
                     <div class="mb-10 pl-12 relative timeline-item">
                        <h3 class="text-xl font-bold text-slate-800">Software Development Engineer Intern</h3>
                        <p class="text-indigo-600 font-medium mb-1"><a href="https://www.progress.com/" target="_blank" class="hover:underline">Progress Software</a>, Hyderabad | JAN 2020 - MAY 2020</p>
                    </div>
                    <div class="mb-10 pl-12 relative timeline-item">
                        <h3 class="text-xl font-bold text-slate-800">Managed Network Expert</h3>
                        <p class="text-indigo-600 font-medium mb-1"><a href="https://www.chegg.com/" target="_blank" class="hover:underline">Chegg</a> | SEPT 2020 - MAY 2021</p>
                    </div>
                    <div class="pl-12 relative timeline-item">
                        <h3 class="text-xl font-bold text-slate-800">Research Assistant</h3>
                        <p class="text-indigo-600 font-medium mb-1"><a href="http://www.idrbt.ac.in" target="_blank" class="hover:underline">IDRBT, Hyderabad (Research Wing of RBI)</a> | JULY 2019 - AUG 2020</p>
                        <p class="text-sm text-slate-600 mt-1">Project: Security Health Monitoring and Attestation of Virtual Machines using TPM 2.0 in Cloud Computing.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Education Section -->
        <section id="education" class="py-20">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <i class="fas fa-graduation-cap fa-3x section-icon mb-4"></i>
                    <h2 class="section-title text-3xl font-bold">Education</h2>
                </div>
                <div class="grid md:grid-cols-2 gap-8 max-w-5xl mx-auto">
                    <div class="card bg-white p-6 rounded-lg shadow-md">
                        <h3 class="font-bold text-lg text-slate-800">M.Tech in Computer Science</h3>
                        <p class="text-indigo-600 font-medium"><a href="https://uohyd.ac.in" target="_blank" class="hover:underline">University of Hyderabad</a> (2018-2020)</p>
                        <p class="text-sm text-slate-500">An Institute of Eminence (IoE)</p>
                    </div>
                    <div class="card bg-white p-6 rounded-lg shadow-md">
                        <h3 class="font-bold text-lg text-slate-800">B.Tech in Computer Science and Engineering</h3>
                        <p class="text-indigo-600 font-medium"><a href="http://www.nitp.ac.in/php/home.php" target="_blank" class="hover:underline">National Institute of Technology Patna</a> (2014-2018)</p>
                        <p class="text-sm text-slate-500">An Institute of National Importance</p>
                    </div>
                    <div class="card bg-white p-6 rounded-lg shadow-md">
                        <h3 class="font-bold text-lg text-slate-800">ISc. (10+2)th in PCM</h3>
                        <p class="text-indigo-600 font-medium"><a href="http://www.nardiganjcollege.com/" target="_blank" class="hover:underline">Nardiganj College Nardiganj</a> (2011-2013)</p>
                    </div>
                    <div class="card bg-white p-6 rounded-lg shadow-md">
                        <h3 class="font-bold text-lg text-slate-800">Matric (10th) & Basic Education</h3>
                        <p class="text-indigo-600 font-medium">High School Hisua & Middle School Hisua</p>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Achievements Section -->
        <section id="achievements" class="py-20 bg-slate-100">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                     <i class="fas fa-trophy fa-3x section-icon mb-4"></i>
                    <h2 class="section-title text-3xl font-bold">Offers & Exams Qualified</h2>
                </div>
                <div class="max-w-4xl mx-auto bg-white p-8 rounded-xl shadow-md">
                    <ul class="space-y-3 text-slate-700 list-disc list-inside">
                        <li><strong>Secured SDE-2 Offers (DEC 2023):</strong> Qualcomm, AMD, MakeMyTrip, Microsoft, Salesforce.</li>
                        <li><strong>Secured SDE-2 Offer (2022):</strong> Oracle Cloud HCM.</li>
                        <li><strong>Secured SDE-1 Offer (2020):</strong> Progress Data Direct.</li>
                        <li><strong>Cleared NIELIT NIC Exam (2020):</strong> For Scientific/Technical Assistant-A and Scientist-C roles.</li>
                        <li>Qualified <strong class="text-slate-800">UGC-NET CS (DEC 2019)</strong> with <strong class="text-slate-800">97.3 Percentile</strong> for Assistant Professor & JRF.</li>
                        <li>Qualified <strong class="text-slate-800">GATE Computer Science 2018</strong>.</li>
                        <li>Qualified <strong class="text-slate-800">JEE-Mains 2014</strong>.</li>
                        <li>Cleared <strong class="text-slate-800">UPSC NDA & NA Written Exam 2013</strong> (SSB Conference out).</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Certifications -->
        <section id="certifications" class="py-20">
            <div class="container mx-auto px-6">
                 <div class="text-center mb-12">
                    <i class="fas fa-certificate fa-3x section-icon mb-4"></i>
                    <h2 class="section-title text-3xl font-bold">Certifications</h2>
                </div>
                <div class="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">
                    <div class="card text-center bg-white p-6 rounded-lg shadow-md">
                        <h3 class="font-bold text-lg mb-2 text-slate-800">Applied CS with Android</h3>
                        <p class="text-slate-500 mb-4">Google Android</p>
                        <a href="https://drive.google.com/open?id=0B7XXZv3OfgOyYzJhdy1VZnFIMnc" target="_blank" class="font-bold text-indigo-600 hover:underline">View Certificate &rarr;</a>
                    </div>
                    <div class="card text-center bg-white p-6 rounded-lg shadow-md">
                        <h3 class="font-bold text-lg mb-2 text-slate-800">Core Java with Android</h3>
                        <p class="text-slate-500 mb-4">Hewlett Packard Enterprises</p>
                        <a href="https://drive.google.com/open?id=1Voe04ipSCLJZaiCAIif6tbQP1PuiK6Sv" target="_blank" class="font-bold text-indigo-600 hover:underline">View Certificate &rarr;</a>
                    </div>
                    <div class="card text-center bg-white p-6 rounded-lg shadow-md">
                        <h3 class="font-bold text-lg mb-2 text-slate-800">SAFe 5 Practitioner</h3>
                        <p class="text-slate-500 mb-4">Scaled Agile Framework</p>
                        <a href="https://www.scaledagileframework.com/" target="_blank" class="font-bold text-indigo-600 hover:underline">Learn More &rarr;</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Research Interests & Extra Curriculars -->
        <section id="research" class="py-20 bg-slate-100">
            <div class="container mx-auto px-6">
                <div class="grid lg:grid-cols-2 gap-16">
                    <!-- Research Interests -->
                    <div>
                        <div class="text-center mb-12">
                            <i class="fas fa-flask fa-3x section-icon mb-4"></i>
                            <h2 class="section-title text-3xl font-bold">Research Interests</h2>
                        </div>
                        <div class="flex flex-wrap justify-center gap-3">
                            <span class="bg-indigo-100 text-indigo-800 text-base font-medium px-4 py-2 rounded-full">Cloud Computing</span>
                            <span class="bg-indigo-100 text-indigo-800 text-base font-medium px-4 py-2 rounded-full">Distributed Computing</span>
                            <span class="bg-indigo-100 text-indigo-800 text-base font-medium px-4 py-2 rounded-full">Parallel Computing</span>
                            <span class="bg-indigo-100 text-indigo-800 text-base font-medium px-4 py-2 rounded-full">Data Structures & Algorithms</span>
                            <span class="bg-indigo-100 text-indigo-800 text-base font-medium px-4 py-2 rounded-full">Artificial Intelligence</span>
                            <span class="bg-indigo-100 text-indigo-800 text-base font-medium px-4 py-2 rounded-full">Machine Learning</span>
                            <span class="bg-indigo-100 text-indigo-800 text-base font-medium px-4 py-2 rounded-full">Software Engineering</span>
                        </div>
                    </div>

                    <!-- Extra Curriculars -->
                    <div id="extra-curriculars">
                        <div class="text-center mb-12">
                            <i class="fas fa-star fa-3x section-icon mb-4"></i>
                            <h2 class="section-title text-3xl font-bold">Extra Curriculars</h2>
                        </div>
                        <div class="max-w-md mx-auto bg-white p-8 rounded-xl shadow-md">
                           <ul class="space-y-3 text-slate-700 list-disc list-inside">
                                <li>Volunteer of <a href="https://www.artofliving.org/in-en" target="_blank" class="text-indigo-600 hover:underline">Art of Living</a>.</li>
                                <li>Awareness and Survey Manager at <a href="http://huhcindia.org/" target="_blank" class="text-indigo-600 hover:underline">Help Us To Help The Child</a>.</li>
                                <li>Cadet of National Cadet Corps (NCC – Army Wing).</li>
                                <li>Captain of Panther Cricket Team at IVSIT Mathura.</li>
                           </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-20">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <i class="fas fa-paper-plane fa-3x section-icon mb-4"></i>
                    <h2 class="section-title text-3xl font-bold">Contact</h2>
                </div>
                <div class="text-center max-w-xl mx-auto">
                    <p class="text-lg mb-6">Feel free to reach out. I'm always open to discussing new projects, creative ideas, or opportunities to be part of an ambitious vision.</p>
                    <div class="bg-white p-6 rounded-lg shadow-md inline-block">
                        <div class="flex items-center justify-center space-x-3">
                            <i class="fas fa-envelope text-indigo-600 text-xl"></i>
                            <a href="mailto:rknitpcse@gmail.com" class="text-slate-800 font-medium text-lg hover:text-indigo-600">rknitpcse[at]gmail[dot]com</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-slate-800 text-slate-400 py-8">
        <div class="container mx-auto px-6 text-center">
            <p>&copy; 2024 Er. Rakesh Kumar. All Rights Reserved.</p>
            <p class="text-sm mt-2">Designed with <i class="fas fa-heart text-red-500"></i> and coded with passion.</p>
        </div>
    </footer>

    <script>
        // Mobile Menu Toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Close mobile menu when a link is clicked
        document.querySelectorAll('#mobile-menu a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });

        // Header shadow on scroll
        const header = document.getElementById('header');
        window.addEventListener('scroll', () => {
            if (window.scrollY > 50) {
                header.classList.add('shadow-lg');
            } else {
                header.classList.remove('shadow-lg');
            }
        });
    </script>
</body>
</html>
