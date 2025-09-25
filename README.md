# Texasrigsroots
Website 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Texas Rigs Roots - Helical Pier Manufacturing & Installation</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
        }
        
        .header {
            background: linear-gradient(135deg, #1a472a, #2d5a3d);
            color: white;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        
        .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-size: 1.8rem;
            font-weight: bold;
            color: #f4f4f4;
        }
        
        .nav-links {
            display: flex;
            list-style: none;
            gap: 2rem;
        }
        
        .nav-links a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }
        
        .nav-links a:hover {
            color: #87ceeb;
        }
        
        .hero {
            background: linear-gradient(rgba(26, 71, 42, 0.8), rgba(45, 90, 61, 0.8)), 
                        url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 600"><rect fill="%23654321" width="1200" height="600"/><circle fill="%238B7355" cx="300" cy="150" r="50"/><circle fill="%238B7355" cx="900" cy="400" r="40"/><rect fill="%232F4F2F" x="0" y="500" width="1200" height="100"/></svg>');
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            background-size: cover;
            background-position: center;
        }
        
        .hero-content h1 {
            font-size: 3.5rem;
            margin-bottom: 1rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }
        
        .hero-content p {
            font-size: 1.3rem;
            margin-bottom: 2rem;
            max-width: 600px;
        }
        
        .cta-button {
            background: #ff6b35;
            color: white;
            padding: 15px 30px;
            border: none;
            border-radius: 5px;
            font-size: 1.1rem;
            cursor: pointer;
            text-decoration: none;
            display: inline-block;
            transition: background 0.3s;
            font-weight: bold;
        }
        
        .cta-button:hover {
            background: #e55a2b;
            transform: translateY(-2px);
        }
        
        .section {
            padding: 80px 0;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        .section-title {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 3rem;
            color: #1a472a;
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 3rem;
        }
        
        .service-card {
            background: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            text-align: center;
            transition: transform 0.3s;
        }
        
        .service-card:hover {
            transform: translateY(-5px);
        }
        
        .service-icon {
            width: 80px;
            height: 80px;
            background: #1a472a;
            border-radius: 50%;
            margin: 0 auto 1rem;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 2rem;
        }
        
        .about-section {
            background: #f8f9fa;
        }
        
        .about-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 3rem;
            align-items: center;
        }
        
        .about-text h3 {
            color: #1a472a;
            font-size: 1.5rem;
            margin-bottom: 1rem;
        }
        
        .stats {
            background: #1a472a;
            color: white;
            text-align: center;
        }
        
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
        }
        
        .stat-item h3 {
            font-size: 3rem;
            margin-bottom: 0.5rem;
            color: #87ceeb;
        }
        
        .contact-section {
            background: #f8f9fa;
        }
        
        .contact-info {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            text-align: center;
        }
        
        .contact-card {
            background: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }
        
        .contact-card h3 {
            color: #1a472a;
            margin-bottom: 1rem;
        }
        
        .footer {
            background: #1a472a;
            color: white;
            text-align: center;
            padding: 2rem 0;
        }
        
        @media (max-width: 768px) {
            .hero-content h1 {
                font-size: 2.5rem;
            }
            
            .nav-links {
                display: none;
            }
            
            .about-content {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header class="header">
        <div class="nav-container">
            <div class="logo">Texas Rigs Roots</div>
            <nav>
                <ul class="nav-links">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Texas Rigs Roots</h1>
            <p>Professional Helical Pier Manufacturing & Installation Services Throughout Texas</p>
            <a href="#contact" class="cta-button">Get Free Quote</a>
        </div>
    </section>

    <section id="services" class="section">
        <div class="container">
            <h2 class="section-title">Our Helical Pier Services</h2>
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon">🏭</div>
                    <h3>Custom Manufacturing</h3>
                    <p>We manufacture high-quality helical piers tailored to your specific foundation needs. Our piers are engineered for maximum strength and longevity.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">⚙️</div>
                    <h3>Professional Installation</h3>
                    <p>Expert installation by certified technicians using state-of-the-art equipment. We ensure proper torque and depth for optimal foundation support.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">🏠</div>
                    <h3>Foundation Repair</h3>
                    <p>Comprehensive foundation stabilization and repair services using helical pier systems. Perfect for settling foundations and structural support.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">📋</div>
                    <h3>Engineering Support</h3>
                    <p>Complete engineering analysis and load calculations to ensure your helical pier system meets all structural requirements and building codes.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="section stats">
        <div class="container">
            <h2 class="section-title" style="color: white;">Why Choose Texas Rigs Roots</h2>
            <div class="stats-grid">
                <div class="stat-item">
                    <h3>500+</h3>
                    <p>Projects Completed</p>
                </div>
                <div class="stat-item">
                    <h3>15+</h3>
                    <p>Years Experience</p>
                </div>
                <div class="stat-item">
                    <h3>100%</h3>
                    <p>Customer Satisfaction</p>
                </div>
                <div class="stat-item">
                    <h3>24/7</h3>
                    <p>Emergency Service</p>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="section about-section">
        <div class="container">
            <h2 class="section-title">About Texas Rigs Roots</h2>
            <div class="about-content">
                <div class="about-text">
                    <h3>Helical Pier Specialists</h3>
                    <p>Texas Rigs Roots is your trusted partner for helical pier manufacturing and installation across Texas. We specialize in providing robust foundation solutions that stand the test of time.</p>
                    
                    <h3>Our Expertise</h3>
                    <p>Our team combines decades of experience with cutting-edge technology to deliver helical pier systems that exceed industry standards. From residential foundations to commercial projects, we have the expertise to handle any challenge.</p>
                    
                    <h3>Quality Guarantee</h3>
                    <p>Every helical pier we manufacture and install comes with our comprehensive warranty. We stand behind our work and are committed to your complete satisfaction.</p>
                </div>
                <div class="about-image">
                    <div style="background: #1a472a; height: 300px; border-radius: 10px; display: flex; align-items: center; justify-content: center; color: white; font-size: 1.2rem;">
                        Professional Helical Pier Installation
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="section contact-section">
        <div class="container">
            <h2 class="section-title">Contact Texas Rigs Roots</h2>
            <div class="contact-info">
                <div class="contact-card">
                    <h3>📞 Phone</h3>
                    <p>Call us for immediate assistance</p>
                    <p><strong>(555) 123-4567</strong></p>
                </div>
                <div class="contact-card">
                    <h3>✉️ Email</h3>
                    <p>Send us your project details</p>
                    <p><strong>info@texasrigsroots.com</strong></p>
                </div>
                <div class="contact-card">
                    <h3>📍 Service Area</h3>
                    <p>Serving all of Texas</p>
                    <p><strong>Statewide Coverage</strong></p>
                </div>
            </div>
        </div>
    </section>

    <footer class="footer">
        <div class="container">
            <p>&copy; 2025 Texas Rigs Roots. All rights reserved. Professional Helical Pier Manufacturing & Installation.</p>
        </div>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Header background change on scroll
        window.addEventListener('scroll', function() {
            const header = document.querySelector('.header');
            if (window.scrollY > 100) {
                header.style.background = 'rgba(26, 71, 42, 0.95)';
            } else {
                header.style.background = 'linear-gradient(135deg, #1a472a, #2d5a3d)';
            }
        });
    </script>
</body>
</html>
