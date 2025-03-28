# kangra-institute
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kangra Institute of Academy - Premier Coaching for NDA, NEET, JEE</title>
    <style>
        /* Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            line-height: 1.6;
            color: #333;
            background-color: #f9f9f9;
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }
        
        a {
            text-decoration: none;
            color: #2c3e50;
            transition: all 0.3s ease;
        }
        
        a:hover {
            color: #e74c3c;
        }
        
        .btn {
            display: inline-block;
            padding: 10px 20px;
            background-color: #e74c3c;
            color: white;
            border-radius: 5px;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
        }
        
        .btn:hover {
            background-color: #c0392b;
            color: white;
            transform: translateY(-2px);
        }
        
        section {
            padding: 60px 0;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 40px;
            position: relative;
        }
        
        .section-title h2 {
            font-size: 36px;
            color: #2c3e50;
            margin-bottom: 15px;
        }
        
        .section-title::after {
            content: '';
            display: block;
            width: 80px;
            height: 4px;
            background-color: #e74c3c;
            margin: 0 auto;
        }
        
        /* Header Styles */
        header {
            background-color: white;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }
        
        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
        }
        
        .logo {
            display: flex;
            align-items: center;
        }
        
        .logo img {
            height: 50px;
            margin-right: 10px;
        }
        
        .logo h1 {
            font-size: 24px;
            color: #2c3e50;
        }
        
        .logo span {
            color: #e74c3c;
        }
        
        nav ul {
            display: flex;
            list-style: none;
        }
        
        nav ul li {
            margin-left: 30px;
        }
        
        nav ul li a {
            font-weight: 600;
            font-size: 16px;
        }
        
        .mobile-menu {
            display: none;
            font-size: 24px;
            cursor: pointer;
        }
        
        /* Home Section */
        .home {
            background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('https://images.unsplash.com/photo-1523050854058-8df90110c9f1');
            background-size: cover;
            background-position: center;
            height: 100vh;
            display: flex;
            align-items: center;
            text-align: center;
            color: white;
            margin-top: 80px;
        }
        
        .home-content {
            max-width: 800px;
            margin: 0 auto;
        }
        
        .home h1 {
            font-size: 48px;
            margin-bottom: 20px;
        }
        
        .home p {
            font-size: 20px;
            margin-bottom: 30px;
        }
        
        /* About Section */
        .about {
            background-color: white;
        }
        
        .about-content {
            display: flex;
            align-items: center;
            gap: 40px;
        }
        
        .about-img {
            flex: 1;
            border-radius: 10px;
            overflow: hidden;
        }
        
        .about-img img {
            width: 100%;
            height: auto;
            display: block;
        }
        
        .about-text {
            flex: 1;
        }
        
        .about-text h3 {
            font-size: 28px;
            margin-bottom: 20px;
            color: #2c3e50;
        }
        
        .about-text p {
            margin-bottom: 15px;
        }
        
        /* Courses Section */
       .container {
            width: 80%;
            margin: auto;
            padding: 50px 0;
        }
        h3 {
            font-size: 2em;
            color: red;
            margin-bottom: 20px;
        }
        .courses {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .course-card {
            background: white;
            padding: 20px;
            width: 250px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s;
        }
        .course-card:hover {
            transform: scale(1.05);
        }
        .course-card h3 {
            margin-bottom: 10px;
            color: #007bff;
        }
        /* Facilities Section */
        .facilities {
            background-color: white;
        }
        
        .facilities-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 30px;
        }
        
        .facility-card {
            text-align: center;
            padding: 30px 20px;
            border-radius: 10px;
            background-color: #f9f9f9;
            transition: all 0.3s ease;
        }
        
        .facility-card:hover {
            background-color: #e74c3c;
            color: white;
            transform: translateY(-5px);
        }
        
        .facility-card:hover i, .facility-card:hover h3, .facility-card:hover p {
            color: white;
        }
        
        .facility-card i {
            font-size: 40px;
            color: #e74c3c;
            margin-bottom: 20px;
        }
        
        .facility-card h3 {
            font-size: 20px;
            margin-bottom: 15px;
            color: #2c3e50;
        }
        
        .facility-card p {
            color: #666;
        }
        
        /* Testimonials Section */
        .testimonials {
            background-color: #f1f5f9;
        }
        
        .testimonial-slider {
            max-width: 800px;
            margin: 0 auto;
        }
        
        .testimonial {
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            text-align: center;
            margin: 0 15px;
        }
        
        .testimonial img {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            object-fit: cover;
            margin: 0 auto 20px;
            border: 3px solid #e74c3c;
        }
        
        .testimonial p {
            font-style: italic;
            margin-bottom: 20px;
            color: #555;
        }
        
        .testimonial h4 {
            color: #2c3e50;
            margin-bottom: 5px;
        }
        
        .testimonial span {
            color: #e74c3c;
            font-size: 14px;
        }
        
        /* Admission Section */
        .admission {
            background-color: white;
        }
        
        .admission-container {
            display: flex;
            gap: 40px;
        }
        
        .admission-process {
            flex: 1;
        }
        
        .admission-process h3 {
            font-size: 28px;
            margin-bottom: 20px;
            color: #2c3e50;
        }
        
        .process-steps {
            margin-bottom: 30px;
        }
        
        .process-step {
            display: flex;
            margin-bottom: 20px;
        }
        
        .step-number {
            width: 40px;
            height: 40px;
            background-color: #e74c3c;
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            margin-right: 15px;
            flex-shrink: 0;
        }
        
        .step-content h4 {
            font-size: 18px;
            margin-bottom: 5px;
            color: #2c3e50;
        }
        
        .admission-form {
            flex: 1;
            background-color: #f9f9f9;
            padding: 30px;
            border-radius: 10px;
        }
        
        .admission-form h3 {
            font-size: 24px;
            margin-bottom: 20px;
            color: #2c3e50;
            text-align: center;
        }
        
        .form-group {
            margin-bottom: 20px;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: 600;
            color: #555;
        }
        
        .form-group input, .form-group select, .form-group textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 16px;
        }
        
        .form-group textarea {
            height: 100px;
        }
        
        /* Contact Section */
        .contact {
            background-color: #f1f5f9;
        }
        
        .contact-container {
            display: flex;
            gap: 40px;
        }
        
        .contact-info {
            flex: 1;
        }
        
        .contact-info h3 {
            font-size: 28px;
            margin-bottom: 20px;
            color: #2c3e50;
        }
        
        .info-item {
            display: flex;
            margin-bottom: 20px;
        }
        
        .info-item i {
            width: 40px;
            height: 40px;
            background-color: #e74c3c;
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 18px;
            margin-right: 15px;
            flex-shrink: 0;
        }
        
        .info-content h4 {
            font-size: 18px;
            margin-bottom: 5px;
            color: #2c3e50;
        }
        
        .contact-map {
            flex: 1;
            height: 400px;
            border-radius: 10px;
            overflow: hidden;
        }
        
        .contact-map iframe {
            width: 100%;
            height: 100%;
            border: none;
        }
        
        /* Footer */
        footer {
            background-color: #2c3e50;
            color: white;
            padding: 60px 0 20px;
        }
        
        .footer-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-bottom: 40px;
        }
        
        .footer-col h3 {
            font-size: 20px;
            margin-bottom: 20px;
            position: relative;
            padding-bottom: 10px;
        }
        
        .footer-col h3::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            width: 50px;
            height: 2px;
            background-color: #e74c3c;
        }
        
        .footer-col p {
            margin-bottom: 15px;
            color: #bbb;
        }
        
        .footer-links li {
            margin-bottom: 10px;
            list-style: none;
        }
        
        .footer-links a {
            color: #bbb;
            transition: all 0.3s ease;
        }
        
        .footer-links a:hover {
            color: #e74c3c;
            padding-left: 5px;
        }
        
        .social-links {
            display: flex;
            gap: 15px;
        }
        
        .social-links a {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 40px;
            height: 40px;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            color: white;
            transition: all 0.3s ease;
        }
        
        .social-links a:hover {
            background-color: #e74c3c;
            transform: translateY(-3px);
        }
        
        .footer-bottom {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: #bbb;
            font-size: 14px;
        }
        
        /* Responsive Styles */
        @media (max-width: 992px) {
            .about-content, .admission-container, .contact-container {
                flex-direction: column;
            }
            
            .about-img, .about-text, .admission-process, .admission-form, .contact-info, .contact-map {
                width: 100%;
            }
            
            .home h1 {
                font-size: 36px;
            }
            
            .home p {
                font-size: 18px;
            }
        }
        
        @media (max-width: 768px) {
            nav ul {
                display: none;
                position: absolute;
                top: 80px;
                left: 0;
                width: 100%;
                background-color: white;
                flex-direction: column;
                padding: 20px 0;
                box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
            }
            
            nav ul.show {
                display: flex;
            }
            
            nav ul li {
                margin: 0;
                padding: 10px 20px;
            }
            
            .mobile-menu {
                display: block;
            }
            
            .section-title h2 {
                font-size: 30px;
            }
        }
        
        @media (max-width: 576px) {
            .home h1 {
                font-size: 28px;
            }
            
            .home p {
                font-size: 16px;
            }
            
            .btn {
                padding: 8px 16px;
                font-size: 14px;
            }
            
            section {
                padding: 40px 0;
            }
.social-media {
            margin-top: 40px;
        }
        .social-media a {
            margin: 0 10px;
            color: #007bff;
            font-size: 24px;
            text-decoration: none;
            transition: color 0.3s;
        }
        .social-media a:hover {
            color: #0056b3;
        }
        }

    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container header-container">
            <div class="logo"> 
                <img src="logo.png"style="width:150px;height:100px;">
                <h1>Kangra <span>Institute</span></h1><br><br>
<h5>"Empowering Minds, Enriching Futures!"</h5>
            </div>
            <nav>
                <ul id="nav-menu">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#courses">Courses</a></li>
                    <li><a href="#facilities">Facilities</a></li>
                    <li><a href="#admission">Admission</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
                <div class="mobile-menu" id="mobile-menu">
                    <i class="fas fa-bars"></i>
                </div>
            </nav>
        </div>
    </header>

    <!-- Home Section -->
    <section class="home" id="home">
        <div class="container home-content">
            <h1>Unlock Your Potential with Kangra Institute</h1>
            <p>Premier coaching for NDA, NEET, JEE and other competitive exams with a proven track record of success</p>
            <a href="#admission" class="btn">Apply Now</a>
        </div>
    </section>

    <!-- About Section -->
    <section class="about" id="about">
        <div class="container">
            <div class="section-title">
                <h3>About Kangra Institute</h3>
                <p>Transforming dreams into reality since 2010</p>
<h2>Our Vision</h2><p>To be a premier institution of excellence, fostering innovation, knowledge, and leadership to empower individuals for a brighter future.</p>
<h2>Our Mission</h2><p><ul><li>To provide high-quality education and skill-based training that nurtures intellectual growth and professional excellence.</li>
<li>
To instill ethical values, social responsibility, and leadership qualities in students.</li>
<li>To cultivate an environment of innovation, research, and continuous learning.
</li></ul></p>
            </div>
            <div class="about-content">
                <div class="about-img">
                    <img src="https://images.unsplash.com/photo-1523050854058-8df90110c9f1" alt="Kangra Institute Campus">
                </div>
                <div class="about-text">
    <h3>Why Choose Kangra Institute?</h3>
  <p>Kangra Institute of Academy is a premier coaching institute dedicated to helping students achieve their dreams of cracking competitive exams like NDA, NEET, JEE, and more. With over a decade of experience, we've developed a proven methodology that combines academic excellence with personalized attention.</p>
  <p>Our team of expert faculty members, comprehensive study materials, and state-of-the-art facilities create the perfect environment for academic success. We believe in nurturing not just academic skills but also the overall personality development of our students.</p>
  <p>At Kangra, we don't just teach subjects - we build futures. Our alumni network includes hundreds of successful candidates who have secured positions in prestigious institutions across the country.</p>
      <a href="#courses" class="btn">Explore Courses</a>
                </div>
            </div>
        </div>
    </section>

 <div class="container">
        <h3>Our Courses</h3>
        <div class="courses">
            <div class="course-card">
                <h3>NEET</h3>
                <p>Comprehensive coaching for medical entrance exams.</p>
            </div>
            <div class="course-card">
                <h3>JEE</h3>
                <p>Expert guidance for engineering aspirants.</p>
            </div>
            <div class="course-card">
                <h3>NDA</h3>
                <p>Prepare for National Defence Academy with top mentors.</p>
            </div>
            <div class="course-card">
                <h3>SSC CGL/CHSL</h3>
                <p>Master SSC exams with our structured courses.</p>
            </div>
            <div class="course-card">
                <h3>Banking Exams</h3>
                <p>Crack IBPS, SBI, RBI exams with confidence.</p>
            </div>
        </div>
    </div>
    <!-- Facilities Section -->
    <section class="facilities" id="facilities">
        <div class="container">
            <div class="section-title">
                <h2>Our Facilities</h2>
                <p>Creating the perfect learning environment</p>
            </div>
            <div class="facilities-grid">
                <!-- Facility 1 -->
                <div class="facility-card">
                    <i class="fas fa-chalkboard-teacher"></i>
                    <h3>Expert Faculty</h3>
                    <p>Learn from IIT/NIT graduates and retired defense personnel with years of teaching experience.</p>
                </div>
                
                <!-- Facility 2 -->
                <div class="facility-card">
                    <i class="fas fa-book"></i>
                    <h3>Study Material</h3>
                    <p>Comprehensive, regularly updated study material designed by our expert faculty.</p>
                </div>
                
                <!-- Facility 3 -->
                <div class="facility-card">
                    <i class="fas fa-laptop"></i>
                    <h3>Digital Classroom</h3>
                    <p>Smart classrooms with audio-visual aids for enhanced learning experience.</p>
                </div>
                
                <!-- Facility 4 -->
                <div class="facility-card">
                    <i class="fas fa-flask"></i>
                    <h3>Laboratories</h3>
                    <p>Well-equipped Physics, Chemistry and Biology labs for practical learning.</p>
                </div>
                
                <!-- Facility 5 -->
                <div class="facility-card">
                    <i class="fas fa-book-open"></i>
                    <h3>Library</h3>
                    <p>Extensive collection of reference books, competitive exam materials and journals.</p>
                </div>
                
                <!-- Facility 6 -->
                <div class="facility-card">
                    <i class="fas fa-chart-line"></i>
                    <h3>Test Series</h3>
                    <p>Regular mock tests with detailed performance analysis and improvement plans.</p>
                </div>
                
                <!-- Facility 7 -->
                <div class="facility-card">
                    <i class="fas fa-dumbbell"></i>
                    <h3>Physical Training</h3>
                    <p>For NDA aspirants, we provide specialized physical training and SSB guidance.</p>
                </div>
                
                <!-- Facility 8 -->
                <div class="facility-card">
                    <i class="fas fa-home"></i>
                    <h3>Hostel Facility</h3>
                    <p>Safe and comfortable hostel accommodation for outstation students.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials">
        <div class="container">
            <div class="section-title">
                <h2>Success Stories</h2>
                <p>What our students say about us</p>
            </div>
            <div class="testimonial-slider">
                <!-- Testimonial 1 -->
                <div class="testimonial">
                    <img src="https://randomuser.me/api/portraits/men/32.jpg" alt="Rahul Sharma">
                    <p>"Kangra Institute's NDA coaching helped me secure AIR 24 in NDA exam. The faculty's personalized attention and regular mock tests were instrumental in my success."</p>
                    <h4>Rahul Sharma</h4>
                    <span>NDA 2022 Topper</span>
                </div>
                
                <!-- Testimonial 2 -->
                <div class="testimonial">
                    <img src="https://randomuser.me/api/portraits/women/44.jpg" alt="Priya Patel">
                    <p>"The NEET program at Kangra gave me the confidence and knowledge to score 680/720. The doubt-clearing sessions were particularly helpful."</p>
                    <h4>Priya Patel</h4>
                    <span>NEET 2023 Qualified</span>
                </div>
                
                <!-- Testimonial 3 -->
                <div class="testimonial">
                    <img src="https://randomuser.me/api/portraits/men/75.jpg" alt="Amit Kumar">
                    <p>"Thanks to Kangra's JEE coaching, I cracked JEE Advanced with AIR 1500. The faculty's problem-solving approach changed my perspective towards Physics."</p>
                    <h4>Amit Kumar</h4>
                    <span>IIT Delhi 2023</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Admission Section -->
    <section class="admission" id="admission">
        <div class="container">
            <div class="section-title">
                <h2>Admission Process</h2>
                <p>Begin your journey to success</p>
            </div>
            <div class="admission-container">
                <div class="admission-process">
                    <h3>How to Join Kangra Institute</h3>
                    <div class="process-steps">
                        <!-- Step 1 -->
                        <div class="process-step">
                            <div class="step-number">1</div>
                            <div class="step-content">
                                <h4>Choose Your Course</h4>
                                <p>Select from our range of courses that match your career aspirations.</p>
                            </div>
                        </div>
                        
                        <!-- Step 2 -->
                        <div class="process-step">
                            <div class="step-number">2</div>
                            <div class="step-content">
                                <h4>Fill Application Form</h4>
                                <p>Complete the online or offline application form with your details.</p>
                            </div>
                        </div>
                        
                        <!-- Step 3 -->
                        <div class="process-step">
                            <div class="step-number">3</div>
                            <div class="step-content">
                                <h4>Appear for Entrance Test</h4>
                                <p>Take our scholarship test to assess your current level (for some courses).</p>
                            </div>
                        </div>
                        
                        <!-- Step 4 -->
                        <div class="process-step">
                            <div class="step-number">4</div>
                            <div class="step-content">
                                <h4>Complete Admission</h4>
                                <p>Submit required documents and pay fees to confirm your seat.</p>
                            </div>
                        </div>
                    </div>
                    
                    <h3 style="margin-top: 40px;">Documents Required</h3>
                    <ul style="list-style-type: none;">
                        <li><i class="fas fa-check" style="color: #e74c3c; margin-right: 10px;"></i> 10th Marksheet (Photocopy)</li>
                        <li><i class="fas fa-check" style="color: #e74c3c; margin-right: 10px;"></i> 12th Marksheet (Photocopy) if applicable</li>
                        <li><i class="fas fa-check" style="color: #e74c3c; margin-right: 10px;"></i> Aadhar Card (Photocopy)</li>
                        <li><i class="fas fa-check" style="color: #e74c3c; margin-right: 10px;"></i> 4 Passport Size Photographs</li>
                        <li><i class="fas fa-check" style="color: #e74c3c; margin-right: 10px;"></i> Transfer Certificate (For hostel students)</li>
                    </ul>
                </div>
                
                <div class="admission-form">
                    <h3>Admission Form</h3>
                    <form id="admissionForm">
                        <div class="form-group">
                            <label for="fullname">Full Name*</label>
                            <input type="text" id="fullname" name="fullname" required>
                        </div>
                        
                        <div class="form-group">
                            <label for="email">Email*</label>
                            <input type="email" id="email" name="email" required>
                        </div>
                        
                        <div class="form-group">
                            <label for="phone">Phone Number*</label>
                            <input type="tel" id="phone" name="phone" required>
                        </div>
                        
                        <div class="form-group">
                            <label for="course">Select Course*</label>
                            <select id="course" name="course" required>
                                <option value="">-- Select Course --</option>
                                <option value="NDA Foundation Course">NDA Foundation Course</option>
                                <option value="NEET Intensive Program">NEET Intensive Program</option>
                                <option value="JEE Advanced Coaching">JEE Advanced Coaching</option>
                                <option value="CBSE Board Preparation">CBSE Board Preparation</option>
                                <option value="SSC CGL/CHSL">SSC CGL/CHSL</option>
                                <option value="Banking Exams (PO/Clerk)">Banking Exams (PO/Clerk)</option>
                            </select>
                        </div>
                        
                        <div class="form-group">
                            <label for="qualification">Highest Qualification*</label>
                            <select id="qualification" name="qualification" required>
                                <option value="">-- Select Qualification --</option>
                                <option value="10th Pass">10th Pass</option>
                                <option value="12th Pass">12th Pass</option>
                                <option value="Graduate">Graduate</option>
                                <option value="Post Graduate">Post Graduate</option>
                            </select>
                        </div>
                        
                        <div class="form-group">
                            <label for="message">Any Questions?</label>
                            <textarea id="message" name="message"></textarea>
                        </div>
                        
                        <button type="submit" class="btn" style="width: 100%;">Submit Application</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <div class="container">
            <div class="section-title">
                <h2>Contact Us</h2>
                <p>We'd love to hear from you</p>
 <div class="social-media">
            <h2>Follow Us</h2>
            <a href="#" target="_blank"><i class="fab fa-facebook"></i></a>
            <a href="#" target="_blank"><i class="fab fa-instagram"></i></a>
            <a href="#" target="_blank"><i class="fab fa-twitter"></i></a>
            <a href="#" target="_blank"><i class="fab fa-youtube"></i></a>
        </div>
            </div>
            <div class="contact-container">
                <div class="contact-info">
                    <h3>Get in Touch</h3>
                    
                    <div class="info-item">
                        <i class="fas fa-map-marker-alt"></i>
                        <div class="info-content">
                            <h4>Address</h4>

  <p>123 Education Street, Kangra City, Himachal Pradesh 176208
</body>
</html>
