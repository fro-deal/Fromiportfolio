<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fromi - Fashion Designer</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="nav-container">
            <div class="logo">
                <h2>Fromi</h2>
            </div>
            <ul class="nav-menu">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Me</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Home Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Fromi Fashion Design</h1>
            <p>Creating Unique & Sustainable Clothing Designs</p>
            <button class="cta-button" onclick="scrollToSection('about')">View My Work</button>
        </div>
    </section>

    <!-- About Me Section -->
    <section id="about" class="about">
        <div class="container">
            <h2>About Me</h2>
            <div class="about-content">
                <div class="about-text">
                    <p>Hello! I'm Fromi, a passionate fashion designer specializing in sustainable and innovative clothing designs. With years of experience in the fashion industry, I create pieces that blend style with consciousness.</p>
                    <p>My journey in fashion began with a simple love for fabrics and has evolved into a commitment to eco-friendly design practices.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="skills">
        <div class="container">
            <h2>My Skills</h2>
            <div class="skills-grid">
                <div class="skill-item">
                    <h3>Pattern Making</h3>
                    <p>Creating precise patterns for various garment types</p>
                </div>
                <div class="skill-item">
                    <h3>Textile Design</h3>
                    <p>Designing unique fabrics and prints</p>
                </div>
                <div class="skill-item">
                    <h3>Sustainable Design</h3>
                    <p>Eco-friendly and ethical fashion creation</p>
                </div>
                <div class="skill-item">
                    <h3>Fashion Illustration</h3>
                    <p>Sketching and visualizing design concepts</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Blog Section -->
    <section id="blog" class="blog">
        <div class="container">
            <h2>My Blog</h2>
            <div class="blog-posts">
                <div class="blog-post">
                    <h3>Sustainable Fashion Trends 2024</h3>
                    <p>Exploring the latest eco-friendly materials and techniques in modern fashion design...</p>
                    <button class="read-more">Read More</button>
                </div>
                <div class="blog-post">
                    <h3>The Art of Custom Tailoring</h3>
                    <p>How personalized clothing is making a comeback in the fashion industry...</p>
                    <button class="read-more">Read More</button>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <div class="contact-content">
                <div class="contact-info">
                    <h3>Get In Touch</h3>
                    <div class="contact-item">
                      <strong>Phone:</strong>
                        <span>+251911690742</span>
                    </div>
                    <div class="contact-item">
                        <strong>Email:</strong>
                        <span>yofri@gmail.com</span>
                    </div>
                    <div class="contact-item">
                        <strong>Location:</strong>
                        <span>Ethiopia</span>
                    </div>
                </div>
                <form class="contact-form" id="contactForm">
                    <input type="text" placeholder="Your Name" required>
                    <input type="email" placeholder="Your Email" required>
                    <textarea placeholder="Your Message" rows="5" required></textarea>
                    <button type="submit">Send Message</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <p>&copy; 2024 Fromi Fashion Design. All rights reserved.</p>
        </div>
    </footer>

    <script src="script.js"></script>
<script src="style.css"></script>
</body>
</html>
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

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* Navigation */
.navbar {
    background: #fff;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 1000;
}

.nav-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 1rem 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo h2 {
    color: #e91e63;
    font-size: 1.8rem;
}

.nav-menu {
    display: flex;
    list-style: none;
    gap: 2rem;
}

.nav-menu a {
    text-decoration: none;
    color: #333;
    font-weight: 500;
    transition: color 0.3s;
}

.nav-menu a:hover {
    color: #e91e63;
}

/* Hero Section */
.hero {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
}

.hero-content h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.hero-content p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
}

.cta-button {
    background: #e91e63;
    color: white;
    padding: 12px 30px;
    border: none;
    border-radius: 5px;
    font-size: 1.1rem;
    cursor: pointer;
    transition: background 0.3s;
}

.cta-button:hover {
    background: #c2185b;
}

/* Sections */
section {
    padding: 80px 0;
}

h2 {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 3rem;
    color: #333;
}

/* About Section */
.about {
    background: #f8f9fa;
}

.about-text {
    max-width: 800px;
    margin: 0 auto;
    text-align: center;
}

.about-text p {
    font-size: 1.1rem;
    margin-bottom: 1rem;
    line-height: 1.8;
}

/* Skills Section */
.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
    margin-top: 2rem;
}

.skill-item {
    background: white;
    padding: 2rem;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    text-align: center;
    transition: transform 0.3s;
}

.skill-item:hover {
    transform: translateY(-5px);
}

.skill-item h3 {
    color: #e91e63;
    margin-bottom: 1rem;
}

/* Blog Section */
.blog {
    background: #f8f9fa;
}

.blog-posts {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
}

.blog-post {
    background: white;
    padding: 2rem;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

.blog-post h3 {
    color: #333;
    margin-bottom: 1rem;
}

.read-more {
    background: #667eea;
    color: white;
    padding: 8px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    margin-top: 1rem;
}

/* Contact Section */
.contact-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 3rem;
    margin-top: 2rem;
}

.contact-info h3 {
    margin-bottom: 1.5rem;
    color: #333;
}

.contact-item {
    margin-bottom: 1rem;
    padding: 1rem;
    background: #f8f9fa;
    border-radius: 5px;
}

.contact-form {
    display: flex;
    flex-direction: column;
    gap: 1rem;
}

.contact-form input,
.contact-form textarea {
    padding: 12px;
    border: 1px solid #ddd;
    border-radius: 5px;
    font-size: 1rem;
}

.contact-form button {
    background: #e91e63;
    color: white;
    padding: 12px;
    border: none;
    border-radius: 5px;
    font-size: 1.1rem;
    cursor: pointer;
    transition: background 0.3s;
}

.contact-form button:hover {
    background: #c2185b;
}

/* Footer */
.footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 2rem 0;
}

/* Responsive Design */
@media (max-width: 768px) {
    .nav-menu {
        flex-direction: column;
        gap: 1rem;
    }
    
    .hero-content h1 {
        font-size: 2rem;
    }
    
    .contact-content {
        grid-template-columns: 1fr;
    }
    
    .skills-grid {
        grid-template-columns: 1fr;
    }

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


function scrollToSection(sectionId) {
    const section = document.getElementById(sectionId);
    if (section) {
        section.scrollIntoView({
            behavior: 'smooth',
            block: 'start'
        });
    }
}

.getElementById('contactForm').addEventListener('submit', function(e) {
    e.preventDefault();
    
    
    const formData = new FormData(this);
    const name = this.querySelector('input[type="text"]').value;
    const email = this.querySelector('input[type="email"]').value;
    const message = this.querySelector('textarea').value;
    
    
     we'll just show an alert and reset the form
    alert(Thank you ${name}! Your message has been sent. I'll get back to you soon at ${email});
    this.reset();
});


window.addEventListener('scroll', function() {
    const navbar = document.querySelector('.navbar');
    if (window.scrollY > 100) {
        navbar.style.background = 'rgba(255, 255, 255, 0.95)';
        navbar.style.backdropFilter = 'blur(10px)';
    } else {
        navbar.style.background = '#fff';
        navbar.style.backdropFilter = 'none';
    }
});

.querySelectorAll('.read-more').forEach(button => {
    button.addEventListener('click', function() {
        const post = this.closest('.blog-post');
        const title = post.querySelector('h3').textContent;
        alert(Reading more about: ${title}\n\nThis would open a full blog post page in a complete website.);
    });
});

.addEventListener('load', function() {
    document.body.style.opacity = '0';
    document.body.style.transition = 'opacity 0.5s ease-in';
    
    setTimeout(() => {
        document.body.style.opacity = '1';
    }, 100);
});


const observerOptions = {
    threshold: 0.1,
    rootMargin: '0px 0px -50px 0px'
};

const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            entry.target.style.opacity = '1';
            entry.target.style.transform = 'translateY(0)';
        }
    });
}, observerOptions);


document.querySelectorAll('.skill-item').forEach(item => {
    item.style.opacity = '0';
    item.style.transform = 'translateY(20px)';
    item.style.transition = 'opacity 0.5s ease, transform 0.5s ease';
    observer.observe(item);
});}
