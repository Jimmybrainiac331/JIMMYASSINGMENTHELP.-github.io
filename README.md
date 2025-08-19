<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jimmy Assignment Help Services | Academic Excellence Guaranteed</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #2c3e50;
            --secondary: #3498db;
            --accent: #e74c3c;
            --light: #ecf0f1;
            --dark: #2c3e50;
            --success: #27ae60;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f9f9f9;
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }
        
        /* Header Styles */
        header {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-size: 1.8rem;
            font-weight: 700;
            display: flex;
            align-items: center;
        }
        
        .logo i {
            margin-right: 10px;
            color: var(--accent);
        }
        
        nav ul {
            display: flex;
            list-style: none;
        }
        
        nav ul li {
            margin-left: 25px;
        }
        
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }
        
        nav ul li a:hover {
            color: var(--accent);
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(44, 62, 80, 0.8), rgba(44, 62, 80, 0.8)), url('https://images.unsplash.com/photo-1501504905252-473c47e087f8?ixlib=rb-4.0.3&auto=format&fit=crop&w=1500&q=80');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 100px 0;
            text-align: center;
        }
        
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
        
        .hero p {
            font-size: 1.2rem;
            max-width: 800px;
            margin: 0 auto 30px;
        }
        
        .cta-button {
            display: inline-block;
            background-color: var(--accent);
            color: white;
            padding: 15px 30px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            font-size: 1.1rem;
            transition: all 0.3s;
            box-shadow: 0 4px 15px rgba(231, 76, 60, 0.4);
        }
        
        .cta-button:hover {
            background-color: #c0392b;
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(231, 76, 60, 0.6);
        }
        
        /* Services Section */
        .services {
            padding: 80px 0;
            background-color: white;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 50px;
            color: var(--primary);
        }
        
        .section-title h2 {
            font-size: 2.5rem;
            margin-bottom: 15px;
        }
        
        .section-title p {
            color: #777;
            max-width: 700px;
            margin: 0 auto;
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .service-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        
        .service-card:hover {
            transform: translateY(-10px);
        }
        
        .service-icon {
            background: linear-gradient(135deg, var(--secondary) 0%, var(--primary) 100%);
            height: 120px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2.5rem;
            color: white;
        }
        
        .service-content {
            padding: 25px;
        }
        
        .service-content h3 {
            font-size: 1.5rem;
            margin-bottom: 15px;
            color: var(--primary);
        }
        
        .service-content ul {
            list-style: none;
            margin-top: 15px;
        }
        
        .service-content ul li {
            padding: 8px 0;
            border-bottom: 1px solid #eee;
        }
        
        .service-content ul li:last-child {
            border-bottom: none;
        }
        
        .service-content ul li i {
            color: var(--success);
            margin-right: 10px;
        }
        
        /* Subjects Section */
        .subjects {
            padding: 80px 0;
            background: linear-gradient(135deg, #f6f9fc 0%, #e9f2fa 100%);
        }
        
        .subjects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        
        .subject-card {
            background: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            text-align: center;
            transition: all 0.3s;
        }
        
        .subject-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.1);
        }
        
        .subject-card i {
            font-size: 2.5rem;
            color: var(--secondary);
            margin-bottom: 20px;
        }
        
        .subject-card h3 {
            color: var(--primary);
            margin-bottom: 15px;
        }
        
        /* Testimonials */
        .testimonials {
            padding: 80px 0;
            background-color: white;
        }
        
        .testimonial-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .testimonial-card {
            background: var(--light);
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            position: relative;
        }
        
        .testimonial-card i {
            position: absolute;
            top: 20px;
            right: 20px;
            font-size: 2rem;
            color: rgba(0, 0, 0, 0.05);
        }
        
        .testimonial-text {
            font-style: italic;
            margin-bottom: 20px;
            color: #555;
        }
        
        .testimonial-author {
            display: flex;
            align-items: center;
        }
        
        .author-avatar {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background-color: var(--secondary);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-weight: bold;
            margin-right: 15px;
        }
        
        .author-details h4 {
            color: var(--primary);
            margin-bottom: 5px;
        }
        
        .author-details p {
            color: #777;
            font-size: 0.9rem;
        }
        
        /* Performance Section */
        .performance {
            padding: 80px 0;
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
            text-align: center;
        }
        
        .performance h2 {
            font-size: 2.5rem;
            margin-bottom: 30px;
        }
        
        .performance-score {
            font-size: 5rem;
            font-weight: 800;
            color: var(--accent);
            text-shadow: 3px 3px 0 rgba(0, 0, 0, 0.2);
            margin: 30px 0;
        }
        
        .performance-desc {
            max-width: 800px;
            margin: 0 auto;
            font-size: 1.2rem;
        }
        
        /* Chat Demo */
        .chat-demo {
            padding: 80px 0;
            background-color: white;
        }
        
        .chat-container {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            border-radius: 10px;
            box-shadow: 0 5px 30px rgba(0, 0, 0, 0.1);
            overflow: hidden;
        }
        
        .chat-header {
            background: var(--primary);
            color: white;
            padding: 20px;
            display: flex;
            align-items: center;
        }
        
        .chat-avatar {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: var(--secondary);
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 15px;
            font-weight: bold;
        }
        
        .chat-messages {
            padding: 20px;
            height: 300px;
            overflow-y: auto;
            background: #f5f5f5;
        }
        
        .message {
            margin-bottom: 15px;
            display: flex;
        }
        
        .message.received {
            flex-direction: row;
        }
        
        .message.sent {
            flex-direction: row-reverse;
        }
        
        .message-bubble {
            max-width: 70%;
            padding: 12px 18px;
            border-radius: 18px;
            margin: 0 10px;
        }
        
        .received .message-bubble {
            background: white;
            border-top-left-radius: 4px;
        }
        
        .sent .message-bubble {
            background: var(--secondary);
            color: white;
            border-top-right-radius: 4px;
        }
        
        .message-time {
            font-size: 0.7rem;
            color: #999;
            margin-top: 5px;
            text-align: right;
        }
        
        .chat-input {
            display: flex;
            padding: 15px;
            border-top: 1px solid #eee;
        }
        
        .chat-input input {
            flex: 1;
            padding: 12px;
            border: 1px solid #ddd;
            border-radius: 30px;
            margin-right: 10px;
        }
        
        .chat-input button {
            background: var(--primary);
            color: white;
            border: none;
            width: 45px;
            height: 45px;
            border-radius: 50%;
            cursor: pointer;
        }
        
        /* Contact Section */
        .contact {
            padding: 80px 0;
            background: linear-gradient(135deg, #f6f9fc 0%, #e9f2fa 100%);
        }
        
        .contact-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 40px;
        }
        
        .contact-info {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        }
        
        .contact-info h3 {
            color: var(--primary);
            margin-bottom: 20px;
            font-size: 1.5rem;
        }
        
        .contact-detail {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
        }
        
        .contact-detail i {
            width: 50px;
            height: 50px;
            background: var(--light);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--secondary);
            font-size: 1.2rem;
            margin-right: 15px;
        }
        
        .contact-detail a {
            color: var(--dark);
            text-decoration: none;
            transition: color 0.3s;
        }
        
        .contact-detail a:hover {
            color: var(--secondary);
        }
        
        /* Footer */
        footer {
            background: var(--dark);
            color: white;
            padding: 50px 0 20px;
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-bottom: 30px;
        }
        
        .footer-section h3 {
            font-size: 1.2rem;
            margin-bottom: 20px;
            position: relative;
            padding-bottom: 10px;
        }
        
        .footer-section h3::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 50px;
            height: 2px;
            background: var(--accent);
        }
        
        .footer-links {
            list-style: none;
        }
        
        .footer-links li {
            margin-bottom: 10px;
        }
        
        .footer-links a {
            color: #bbb;
            text-decoration: none;
            transition: color 0.3s;
        }
        
        .footer-links a:hover {
            color: var(--accent);
        }
        
        .footer-bottom {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            font-size: 0.9rem;
            color: #bbb;
        }
        
        /* Responsive Design */
        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                text-align: center;
            }
            
            nav ul {
                margin-top: 20px;
                justify-content: center;
            }
            
            nav ul li {
                margin: 0 10px;
            }
            
            .hero h1 {
                font-size: 2.2rem;
            }
            
            .hero p {
                font-size: 1rem;
            }
            
            .performance-score {
                font-size: 3.5rem;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container header-content">
            <div class="logo">
                <i class="fas fa-graduation-cap"></i>
                Jimmy Assignment Help
            </div>
            <nav>
                <ul>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#subjects">Subjects</a></li>
                    <li><a href="#testimonials">Testimonials</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h1>Excel in Your Studies with Professional Assignment Help</h1>
            <p>Get top-quality assistance from subject matter experts and achieve academic success with our guaranteed A+ grades and on-time delivery.</p>
            <a href="#contact" class="cta-button">Get Help Now</a>
        </div>
    </section>

    <!-- Services Section -->
    <section class="services" id="services">
        <div class="container">
            <div class="section-title">
                <h2>Our Assignment Help Services</h2>
                <p>We provide comprehensive academic assistance across all subjects and levels</p>
            </div>
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-file-alt"></i>
                    </div>
                    <div class="service-content">
                        <h3>Writing Services</h3>
                        <ul>
                            <li><i class="fas fa-check-circle"></i> Thesis & Dissertation</li>
                            <li><i class="fas fa-check-circle"></i> Research Papers</li>
                            <li><i class="fas fa-check-circle"></i> Proposals</li>
                            <li><i class="fas fa-check-circle"></i> Literature Reviews</li>
                            <li><i class="fas fa-check-circle"></i> Reflective Writing</li>
                            <li><i class="fas fa-check-circle"></i> Research Summary</li>
                        </ul>
                    </div>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-laptop-code"></i>
                    </div>
                    <div class="service-content">
                        <h3>Technical Assistance</h3>
                        <ul>
                            <li><i class="fas fa-check-circle"></i> Online Exams & Coursework</li>
                            <li><i class="fas fa-check-circle"></i> Programming Assignments</li>
                            <li><i class="fas fa-check-circle"></i> Engineering Projects</li>
                            <li><i class="fas fa-check-circle"></i> Data Analysis</li>
                            <li><i class="fas fa-check-circle"></i> Web Development</li>
                            <li><i class="fas fa-check-circle"></i> Technical Reports</li>
                        </ul>
                    </div>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-chart-line"></i>
                    </div>
                    <div class="service-content">
                        <h3>Business & Finance</h3>
                        <ul>
                            <li><i class="fas fa-check-circle"></i> Case Studies</li>
                            <li><i class="fas fa-check-circle"></i> Financial Analysis</li>
                            <li><i class="fas fa-check-circle"></i> Business Plans</li>
                            <li><i class="fas fa-check-circle"></i> Market Research</li>
                            <li><i class="fas fa-check-circle"></i> Accounting Help</li>
                            <li><i class="fas fa-check-circle"></i> Economics Papers</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Subjects Section -->
    <section class="subjects" id="subjects">
        <div class="container">
            <div class="section-title">
                <h2>Our Core Subjects</h2>
                <p>Expert assistance across all major academic disciplines</p>
            </div>
            <div class="subjects-grid">
                <div class="subject-card">
                    <i class="fas fa-chart-pie"></i>
                    <h3>Economics & Marketing</h3>
                    <p>Micro/macro economics, market analysis, consumer behavior studies</p>
                </div>
                
                <div class="subject-card">
                    <i class="fas fa-coins"></i>
                    <h3>Finance & Accounting</h3>
                    <p>Financial reporting, investment analysis, managerial accounting</p>
                </div>
                
                <div class="subject-card">
                    <i class="fas fa-truck-loading"></i>
                    <h3>Supply Chain</h3>
                    <p>Logistics, operations management, inventory control</p>
                </div>
                
                <div class="subject-card">
                    <i class="fas fa-gavel"></i>
                    <h3>Law</h3>
                    <p>Legal studies, case analysis, contract law, international law</p>
                </div>
                
                <div class="subject-card">
                    <i class="fas fa-cogs"></i>
                    <h3>Engineering (All)</h3>
                    <p>Mechanical, electrical, civil, chemical, and more</p>
                </div>
                
                <div class="subject-card">
                    <i class="fas fa-code"></i>
                    <h3>Programming</h3>
                    <p>C++, JavaScript, SQL, Android apps, Web development, AI/ML</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials" id="testimonials">
        <div class="container">
            <div class="section-title">
                <h2>Student Testimonials</h2>
                <p>See how Jimmy Assignment Help has transformed academic performance</p>
            </div>
            <div class="testimonial-grid">
                <div class="testimonial-card">
                    <i class="fas fa-quote-right"></i>
                    <p class="testimonial-text">I was struggling with my economics dissertation until I found Jimmy Assignment Help. Their expert not only helped me structure my paper but also provided incredible insights that impressed my professor. I got an A!</p>
                    <div class="testimonial-author">
                        <div class="author-avatar">S</div>
                        <div class="author-details">
                            <h4>Sarah Johnson</h4>
                            <p>Economics Major</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card">
                    <i class="fas fa-quote-right"></i>
                    <p class="testimonial-text">The programming assistance I received was exceptional. My Android application project was completed with clean, well-documented code that exceeded expectations. Will definitely use again!</p>
                    <div class="testimonial-author">
                        <div class="author-avatar">M</div>
                        <div class="author-details">
                            <h4>Michael Chen</h4>
                            <p>Computer Science Student</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card">
                    <i class="fas fa-quote-right"></i>
                    <p class="testimonial-text">As an international student, I sometimes struggle with academic writing. Jimmy Help Services transformed my rough ideas into a polished research paper that earned me my first A+ in Law school.</p>
                    <div class="testimonial-author">
                        <div class="author-avatar">A</div>
                        <div class="author-details">
                            <h4>Amanda Rodriguez</h4>
                            <p>Law Student</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Performance Section -->
    <section class="performance">
        <div class="container">
            <h2>Our Performance Record</h2>
            <div class="performance-score">89%</div>
            <p class="performance-desc">Our students achieve an average grade of 89% across all assignments, with guaranteed quality, on-time delivery, and 100% original content written from scratch by subject matter experts.</p>
        </div>
    </section>

    <!-- Chat Demo -->
    <section class="chat-demo">
        <div class="container">
            <div class="section-title">
                <h2>See Our Service in Action</h2>
                <p>Example conversation showing how we help students excel</p>
            </div>
            <div class="chat-container">
                <div class="chat-header">
                    <div class="chat-avatar">J</div>
                    <div class="chat-info">
                        <h3>Jimmy Assignment Help</h3>
                        <p>Typically replies within minutes</p>
                    </div>
                </div>
                <div class="chat-messages">
                    <div class="message received">
                        <div class="message-bubble">
                            <p>Hi! I need help with my finance assignment on portfolio optimization. It's due in 4 days.</p>
                            <div class="message-time">10:05 AM</div>
                        </div>
                    </div>
                    <div class="message sent">
                        <div class="message-bubble">
                            <p>Hello! We can definitely help with that. Our finance experts have extensive experience with portfolio optimization models. Can you share the assignment details?</p>
                            <div class="message-time">10:06 AM</div>
                        </div>
                    </div>
                    <div class="message received">
                        <div class="message-bubble">
                            <p>It's a 2000-word analysis with Excel modeling. The case study is about balancing risk and return for a retirement portfolio.</p>
                            <div class="message-time">10:08 AM</div>
                        </div>
                    </div>
                    <div class="message sent">
                        <div class="message-bubble">
                            <p>Perfect! We have several finance specialists who excel at such assignments. We can deliver a comprehensive analysis with Excel models, explanations, and proper referencing.</p>
                            <div class="message-time">10:09 AM</div>
                        </div>
                    </div>
                    <div class="message received">
                        <div class="message-bubble">
                            <p>That sounds great! What's your guarantee?</p>
                            <div class="message-time">10:10 AM</div>
                        </div>
                    </div>
                    <div class="message sent">
                        <div class="message-bubble">
                            <p>We guarantee:
                                <br>✅ A-grade quality (or free revision)
                                <br>✅ On-time delivery
                                <br>✅ 0% plagiarism with report
                                <br>✅ Complete confidentiality</p>
                            <div class="message-time">10:11 AM</div>
                        </div>
                    </div>
                    <div class="message received">
                        <div class="message-bubble">
                            <p>Amazing! Let's proceed. I just sent the files via WhatsApp.</p>
                            <div class="message-time">10:12 AM</div>
                        </div>
                    </div>
                </div>
                <div class="chat-input">
                    <input type="text" placeholder="Type a message...">
                    <button><i class="fas fa-paper-plane"></i></button>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <div class="container">
            <div class="section-title">
                <h2>Contact Us</h2>
                <p>Reach out for instant assignment help and consultation</p>
            </div>
            <div class="contact-grid">
                <div class="contact-info">
                    <h3>Get In Touch</h3>
                    <div class="contact-detail">
                        <i class="fab fa-whatsapp"></i>
                        <div>
                            <h4>WhatsApp</h4>
                            <a href="https://wa.me/qr/4PKBWS2XMM4VF1" target="_blank">Direct Message</a>
                        </div>
                    </div>
                    <div class="contact-detail">
                        <i class="fas fa-users"></i>
                        <div>
                            <h4>WhatsApp Group</h4>
                            <a href="https://chat.whatsapp.com/K4pGzREL0Io5XN9v5McvbQ" target="_blank">Join Support Group</a>
                        </div>
                    </div>
                    <div class="contact-detail">
                        <i class="fas fa-clock"></i>
                        <div>
                            <h4>Availability</h4>
                            <p>24/7 Service</p>
                        </div>
                    </div>
                    <div class="contact-detail">
                        <i class="fas fa-star"></i>
                        <div>
                            <h4>Quality Guarantee</h4>
                            <p>First Class Quality Assured</p>
                        </div>
                    </div>
                </div>
                
                <div class="contact-info">
                    <h3>Why Choose Us</h3>
                    <ul class="footer-links">
                        <li><i class="fas fa-check"></i> Excellent grades guaranteed</li>
                        <li><i class="fas fa-check"></i> On-time delivery</li>
                        <li><i class="fas fa-check"></i> 0% AI - Human experts only</li>
                        <li><i class="fas fa-check"></i> 24/7 customer support</li>
                        <li><i class="fas fa-check"></i> Subject matter experts</li>
                        <li><i class="fas fa-check"></i> Plagiarism-free work</li>
                        <li><i class="fas fa-check"></i> Money-back guarantee</li>
                        <li><i class="fas fa-check"></i> Complete confidentiality</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>Jimmy Assignment Help</h3>
                    <p>Providing top-quality academic assistance since 2015. We help students achieve their educational goals with expert guidance and support.</p>
                </div>
                
                <div class="footer-section">
                    <h3>Quick Links</h3>
                    <ul class="footer-links">
                        <li><a href="#services">Our Services</a></li>
                        <li><a href="#subjects">Core Subjects</a></li>
                        <li><a href="#testimonials">Testimonials</a></li>
                        <li><a href="#contact">Contact Us</a></li>
                    </ul>
                </div>
                
                <div class="footer-section">
                    <h3>Contact Info</h3>
                    <ul class="footer-links">
                        <li><a href="https://wa.me/qr/4PKBWS2XMM4VF1" target="_blank"><i class="fab fa-whatsapp"></i> WhatsApp Direct</a></li>
                        <li><a href="https://chat.whatsapp.com/K4pGzREL0Io5XN9v5McvbQ" target="_blank"><i class="fas fa-users"></i> WhatsApp Group</a></li>
                        <li><i class="fas fa-clock"></i> Available 24/7</li>
                    </ul>
                </div>
            </div>
            
            <div class="footer-bottom">
                <p>&copy; 2023 Jimmy Assignment Help Services. All rights reserved.</p>
            </div>
        </div>
    </footer>
</body>
</html>
