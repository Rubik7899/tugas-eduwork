<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Professional Profile</title>
    <style>
        /* Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        section {
            margin-bottom: 40px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            padding: 30px;
        }
        
        /* Section 1 - Navigation Menu */
        .nav-section {
            background-color: #2c3e50;
            color: white;
        }
        
        .nav-menu {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
        }
        
        .nav-logo {
            font-size: 24px;
            font-weight: bold;
        }
        
        .nav-links {
            display: flex;
            gap: 20px;
        }
        
        .nav-links a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }
        
        .nav-links a:hover {
            color: #3498db;
        }
        
        /* Section 2 - Title Left, Image Right */
        .hero-section {
            display: flex;
            align-items: center;
            gap: 40px;
            overflow: hidden;
        }
        
        .hero-content {
            flex: 1;
        }
        
        .hero-title {
            font-size: 2.5rem;
            margin-bottom: 20px;
            color: #2c3e50;
        }
        
        .hero-subtitle {
            font-size: 1.2rem;
            margin-bottom: 20px;
            color: #7f8c8d;
        }
        
        .hero-image {
            flex: 1;
        }
        
        .hero-image img {
            width: 100%;
            border-radius: 8px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        
        .hero-image img:hover {
            transform: scale(1.02);
        }
        
        /* Section 3 - Biodata in 6 Boxes */
        .biodata-section {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }
        
        .bio-box {
            padding: 20px;
            background-color: #f8f9fa;
            border-radius: 8px;
            transition: all 0.3s;
        }
        
        .bio-box:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .bio-title {
            font-size: 1.2rem;
            margin-bottom: 10px;
            color: #3498db;
        }
        
        /* Section 4 - Portfolio */
        .portfolio-section table {
            width: 100%;
            border-collapse: collapse;
        }
        
        .portfolio-section th, 
        .portfolio-section td {
            padding: 12px 15px;
            text-align: left;
            border-bottom: 1px solid #ddd;
        }
        
        .portfolio-section th {
            background-color: #2c3e50;
            color: white;
        }
        
        .portfolio-section tr:hover {
            background-color: #f5f5f5;
        }
        
        /* Responsive Styles */
        @media (max-width: 768px) {
            .hero-section {
                flex-direction: column;
            }
            
            .biodata-section {
                grid-template-columns: repeat(2, 1fr);
            }
            
            .nav-menu {
                flex-direction: column;
                gap: 15px;
            }
        }
        
        @media (max-width: 480px) {
            .biodata-section {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Section 1 - Navigation Menu -->
        <section class="nav-section">
            <div class="nav-menu">
                <div class="nav-logo">Muhammad Farhan</div>
                <div class="nav-links">
                    <a href="#home">Home</a>
                    <a href="#biodata">Biodata</a>
                    <a href="#portfolio">Portfolio</a>
                    <a href="#contact">Contact</a>
                </div>
            </div>
        </section>
        
        <!-- Section 2 - Title Left, Image Right -->
        <section class="hero-section" id="home">
            <div class="hero-content">
                <h1 class="hero-title">Muhammad Farhan</h1>
                <p class="hero-subtitle">Full Stack Developer & IT Specialist</p>
                <p>Passionate about building innovative solutions with expertise in both front-end and back-end technologies.</p>
            </div>
            <div class="hero-image">
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/ec73b21d-084e-40ba-bf9c-f312c6df2525.png" alt="Professional portrait of Muhammad Farhan" />
            </div>
        </section>
        
        <!-- Section 3 - Biodata with 6 Boxes -->
        <section class="biodata-section" id="biodata">
            <div class="bio-box">
                <h3 class="bio-title">Personal Information</h3>
                <p><strong>Name:</strong> Muhammad Farhan</p>
                <p><strong>Date of Birth:</strong> Januari 22, 2003</p>
                <p><strong>Nationality:</strong> Indonesian</p>
            </div>
            
            <div class="bio-box">
                <h3 class="bio-title">Education</h3>
                <p><strong>Degree:</strong> Informatic Engineering</p>
                <p><strong>University:</strong> Universitas Bina Sarana Informatika</p>
                <p><strong>Year:</strong> 2022</p>
            </div>
            
            <div class="bio-box">
                <h3 class="bio-title">Skills</h3>
                <p>HTML5, CSS3, JavaScript, PHP</p>
                <p>C++, Laravel, MySQL</p>
                <p>Cloud Computing</p>
            </div>
            
            <div class="bio-box">
                <h3 class="bio-title">Experience</h3>
                <p><strong>Position:</strong> Front end Developer</p>
                <p><strong>Company:</strong> PT Ali baba indonesia TBK</p>
                <p><strong>Years:</strong> 4</p>
            </div>
            
            <div class="bio-box">
                <h3 class="bio-title">Languages</h3>
                <p>English (Advanced)</p>
                <p>Indonesian (Native)</p>
                <p>Arabic (Basic)</p>
            </div>
            
            <div class="bio-box">
                <h3 class="bio-title">Contact</h3>
                <p><strong>Email:</strong> mhmdfrhnpriyo@gmail.com</p>
                <p><strong>Phone:</strong> +62 85215788925</p>
                <p><strong>Location:</strong> Bekasi, Indonesia</p>
            </div>
        </section>
        
        <!-- Section 4 - Portfolio -->
        <section class="portfolio-section" id="portfolio">
            <h2 style="margin-bottom: 20px; color: #2c3e50;">Portfolio</h2>
            <table>
                <thead>
                    <tr>
                        <th>Project</th>
                        <th>Description</th>
                        <th>Year</th>
                        <th>Technologies</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>School Management System</td>
                        <td>Comprehensive platform for educational institutions</td>
                        <td>2023</td>
                        <td>Laravel, MySQL</td>
                    </tr>
                    <tr>
                        <td>E-Learning Portal</td>
                        <td>Interactive online learning platform</td>
                        <td>2022</td>
                        <td>React, Node.js</td>
                    </tr>
                    <tr>
                        <td>Inventory Management</td>
                        <td>Retail stock tracking system</td>
                        <td>2021</td>
                        <td>PHP, MySQL</td>
                    </tr>
                    <tr>
                        <td>Company Profile Website</td>
                        <td>Responsive corporate website</td>
                        <td>2020</td>
                        <td>HTML, CSS, JavaScript</td>
                    </tr>
                </tbody>
            </table>
        </section>
    </div>
    
    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
        
        // Animation for bio boxes on scroll
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = 1;
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        }, { threshold: 0.1 });
        
        document.querySelectorAll('.bio-box').forEach(box => {
            box.style.opacity = 0;
            box.style.transform = 'translateY(20px)';
            box.style.transition = 'all 0.5s ease-out';
            observer.observe(box);
        });
    </script>
</body>
</html>

