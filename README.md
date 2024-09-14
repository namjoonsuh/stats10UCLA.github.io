<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Your Course Title</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Link to external CSS (you can create a separate style.css file) -->
    <link rel="stylesheet" href="style.css">
    <!-- Include Google Fonts or any other fonts you prefer -->
    <link href="https://fonts.googleapis.com/css?family=Roboto:400,700&display=swap" rel="stylesheet">
    <!-- Favicon -->
    <link rel="icon" href="images/favicon.ico" type="image/x-icon">
    <!-- Meta Description for SEO -->
    <meta name="description" content="A brief description of your course for SEO purposes.">
</head>
<body>
    <!-- Header Section -->
    <header id="home">
        <nav>
            <div class="logo">
                <img src="images/logo.png" alt="Course Logo">
                <h1>Your Course Name</h1>
            </div>
            <ul class="nav-links">
                <li><a href="#overview">Overview</a></li>
                <li><a href="#curriculum">Curriculum</a></li>
                <li><a href="#instructor">Instructor</a></li>
                <li><a href="#enrollment">Enrollment</a></li>
                <li><a href="#testimonials">Testimonials</a></li>
                <li><a href="#faq">FAQ</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <!-- Hero Section -->
        <div class="hero">
            <div class="hero-content">
                <h2>Unlock Your Potential with Our Course</h2>
                <p>An engaging tagline that highlights the value of the course.</p>
                <a href="#enrollment" class="btn">Enroll Now</a>
            </div>
            <!-- Hero Image or Video -->
            <div class="hero-media">
                <!-- Use an image -->
                <img src="images/hero-image.jpg" alt="Hero Image">
                <!-- Or embed a video
                <iframe src="your-video-link" frameborder="0" allowfullscreen></iframe>
                -->
            </div>
        </div>
    </header>

    <!-- Course Overview Section -->
    <section id="overview">
        <div class="container">
            <h2>Course Overview</h2>
            <p>A brief but thorough description of what the course covers, learning outcomes, and who it's for.</p>
            <div class="features">
                <div class="feature-item">
                    <i class="icon">⏰</i>
                    <h3>Duration</h3>
                    <p>10 Weeks</p>
                </div>
                <div class="feature-item">
                    <i class="icon">📚</i>
                    <h3>Modules</h3>
                    <p>20 Modules</p>
                </div>
                <div class="feature-item">
                    <i class="icon">💻</i>
                    <h3>Format</h3>
                    <p>Online & Self-paced</p>
                </div>
                <div class="feature-item">
                    <i class="icon">🎓</i>
                    <h3>Certification</h3>
                    <p>Certificate upon completion</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Curriculum Section -->
    <section id="curriculum">
        <div class="container">
            <h2>Curriculum</h2>
            <div class="accordion">
                <!-- Module 1 -->
                <div class="accordion-item">
                    <button class="accordion-button">Module 1: Introduction to the Course</button>
                    <div class="accordion-content">
                        <p>Topics covered, learning objectives, and duration.</p>
                    </div>
                </div>
                <!-- Module 2 -->
                <div class="accordion-item">
                    <button class="accordion-button">Module 2: Advanced Concepts</button>
                    <div class="accordion-content">
                        <p>Topics covered, learning objectives, and duration.</p>
                    </div>
                </div>
                <!-- Add more modules as needed -->
            </div>
        </div>
    </section>

    <!-- Instructor Section -->
    <section id="instructor">
        <div class="container">
            <h2>Meet the Instructor</h2>
            <div class="instructor-profile">
                <img src="images/instructor.jpg" alt="Instructor Photo">
                <div class="instructor-info">
                    <h3>Dr. Jane Doe</h3>
                    <p>A concise biography highlighting qualifications, experience, and achievements.</p>
                    <div class="social-links">
                        <a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
                        <a href="https://twitter.com/yourprofile" target="_blank">Twitter</a>
                        <!-- Add more social links as needed -->
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Enrollment Section -->
    <section id="enrollment">
        <div class="container">
            <h2>Enrollment Details</h2>
            <div class="pricing">
                <!-- Pricing Option 1 -->
                <div class="price-card">
                    <h3>Basic Package</h3>
                    <p class="price">$499</p>
                    <ul>
                        <li>Access to all modules</li>
                        <li>Community Support</li>
                        <li>Certificate of Completion</li>
                    </ul>
                    <a href="#contact" class="btn">Enroll Now</a>
                </div>
                <!-- Pricing Option 2 -->
                <div class="price-card">
                    <h3>Premium Package</h3>
                    <p class="price">$799</p>
                    <ul>
                        <li>Everything in Basic</li>
                        <li>1-on-1 Mentoring</li>
                        <li>Exclusive Webinars</li>
                    </ul>
                    <a href="#contact" class="btn">Enroll Now</a>
                </div>
            </div>
            <!-- Countdown Timer -->
            <div class="countdown">
                <p>Enrollment closes in:</p>
                <div id="countdown-timer">00 Days 00 Hours 00 Minutes 00 Seconds</div>
            </div>
            <!-- FAQ Section -->
            <div id="faq">
                <h3>Frequently Asked Questions</h3>
                <div class="faq-item">
                    <button class="faq-question">What is the refund policy?</button>
                    <div class="faq-answer">
                        <p>Details about refunds.</p>
                    </div>
                </div>
                <!-- Add more FAQs as needed -->
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials">
        <div class="container">
            <h2>What Our Students Say</h2>
            <div class="testimonial-carousel">
                <div class="testimonial-item">
                    <p>"This course changed my life!"</p>
                    <h4>- Student A</h4>
                </div>
                <div class="testimonial-item">
                    <p>"Highly recommend to anyone looking to advance their career."</p>
                    <h4>- Student B</h4>
                </div>
                <!-- Add more testimonials as needed -->
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <h2>Get in Touch</h2>
            <form action="your-form-handler.php" method="post">
                <div class="form-group">
                    <label for="name">Name</label>
                    <input type="text" id="name" name="name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="message">Message</label>
                    <textarea id="message" name="message" rows="5"></textarea>
                </div>
                <button type="submit" class="btn">Send Message</button>
            </form>
            <div class="contact-info">
                <p>Email: <a href="mailto:youremail@example.com">youremail@example.com</a></p>
                <p>Phone: <a href="tel:+1234567890">+1 (234) 567-890</a></p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-social">
                <a href="https://facebook.com/yourpage" target="_blank">Facebook</a>
                <a href="https://twitter.com/yourprofile" target="_blank">Twitter</a>
                <a href="https://instagram.com/yourprofile" target="_blank">Instagram</a>
                <!-- Add more social links as needed -->
            </div>
            <p>&copy; 2024 Your Course Name. All rights reserved.</p>
            <div class="footer-links">
                <a href="privacy-policy.html">Privacy Policy</a>
                <a href="terms-of-service.html">Terms of Service</a>
            </div>
        </div>
    </footer>

    <!-- JavaScript for Interactive Elements -->
    <script src="script.js"></script>
</body>
</html>
