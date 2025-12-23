
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Maibam Rakesh Singh - MLOps Engineer & Statistical Mathematician</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #3498db;
            --accent-color: #e74c3c;
            --success-color: #27ae60;
            --light-bg: #f8f9fa;
            --box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);
            --border-radius: 10px;
            --transition: all 0.3s ease;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            color: #333;
            line-height: 1.6;
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .main-container {
            display: grid;
            grid-template-columns: 320px 1fr;
            gap: 30px;
        }

        .container {
            background-color: white;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            padding: 40px;
            margin-top: 20px;
        }

        /* Profile Section */
        .profile-container {
            background: linear-gradient(135deg, #2c3e50, #3498db);
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            padding: 30px 25px;
            margin-top: 20px;
            color: white;
            height: fit-content;
            position: sticky;
            top: 20px;
        }

        .profile-header {
            text-align: center;
            margin-bottom: 25px;
            padding-bottom: 25px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.2);
        }

        .profile-photo {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            border: 5px solid rgba(255, 255, 255, 0.3);
            object-fit: cover;
            margin: 0 auto 20px;
            display: block;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.2);
        }

        .profile-name {
            font-size: 1.8rem;
            font-weight: 700;
            margin-bottom: 5px;
        }

        .profile-title {
            font-size: 1.1rem;
            color: rgba(255, 255, 255, 0.9);
            margin-bottom: 15px;
        }

        .profile-tagline {
            font-size: 0.95rem;
            color: rgba(255, 255, 255, 0.8);
            font-style: italic;
            line-height: 1.5;
            margin-top: 10px;
        }

        .profile-details {
            margin: 25px 0;
        }

        .detail-item {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
            font-size: 0.95rem;
        }

        .detail-icon {
            width: 40px;
            height: 40px;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 12px;
            color: white;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 25px;
            flex-wrap: wrap;
        }

        .social-link {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-decoration: none;
            color: white;
            transition: var(--transition);
            width: 80px;
        }

        .social-icon {
            width: 50px;
            height: 50px;
            background-color: rgba(255, 255, 255, 0.15);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 8px;
            font-size: 1.3rem;
            transition: var(--transition);
        }

        .social-link:hover .social-icon {
            background-color: rgba(255, 255, 255, 0.25);
            transform: translateY(-5px);
        }

        .social-label {
            font-size: 0.85rem;
            text-align: center;
        }

        .cv-button {
            display: block;
            width: 100%;
            padding: 12px;
            background-color: rgba(255, 255, 255, 0.15);
            border: 2px solid rgba(255, 255, 255, 0.3);
            color: white;
            border-radius: 6px;
            text-align: center;
            text-decoration: none;
            font-weight: 600;
            margin-top: 20px;
            transition: var(--transition);
        }

        .cv-button:hover {
            background-color: rgba(255, 255, 255, 0.25);
            border-color: rgba(255, 255, 255, 0.5);
        }

        /* Section boxes with colored backgrounds */
        .section-box {
            background-color: var(--light-bg);
            border-radius: var(--border-radius);
            padding: 30px;
            margin-bottom: 30px;
            border-left: 5px solid var(--secondary-color);
            box-shadow: var(--box-shadow);
            transition: var(--transition);
        }

        .section-box:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.12);
        }

        /* Different colors for different sections */
        .research-box {
            border-left-color: #3498db;
            background: linear-gradient(135deg, #e3f2fd 0%, #bbdefb 100%);
        }

        .portfolio-box {
            border-left-color: #9b59b6;
            background: linear-gradient(135deg, #f3e5f5 0%, #e1bee7 100%);
        }

        .expertise-box {
            border-left-color: #2ecc71;
            background: linear-gradient(135deg, #e8f5e9 0%, #c8e6c9 100%);
        }

        .contact-box {
            border-left-color: #f39c12;
            background: linear-gradient(135deg, #fff3e0 0%, #ffecb3 100%);
        }

        /* Section headers */
        .section-header {
            display: flex;
            align-items: center;
            margin-bottom: 25px;
            padding-bottom: 15px;
            border-bottom: 2px solid rgba(0, 0, 0, 0.1);
        }

        .section-icon {
            width: 50px;
            height: 50px;
            background-color: var(--primary-color);
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 15px;
            font-size: 1.5rem;
        }

        .section-title {
            font-size: 1.8rem;
            color: var(--primary-color);
            font-weight: 700;
        }

        /* Research interests styling */
        .interests-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .interest-item {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.05);
        }

        .interest-title {
            color: var(--primary-color);
            font-size: 1.2rem;
            margin-bottom: 10px;
            font-weight: 600;
        }

        .interest-topics {
            color: #555;
            padding-left: 20px;
        }

        /* Portfolio items */
        .portfolio-item {
            background-color: white;
            padding: 25px;
            border-radius: 8px;
            margin-bottom: 25px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.05);
            border-top: 3px solid #9b59b6;
        }

        .portfolio-title {
            font-size: 1.4rem;
            color: var(--primary-color);
            margin-bottom: 10px;
            font-weight: 600;
        }

        .portfolio-authors {
            color: #7f8c8d;
            margin-bottom: 10px;
            font-style: italic;
        }

        .portfolio-conference {
            color: var(--accent-color);
            font-weight: 600;
            margin-bottom: 15px;
            display: inline-block;
            background-color: #fdf2f2;
            padding: 5px 10px;
            border-radius: 4px;
        }

        /* Action links */
        .action-links {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 15px;
        }

        .action-link {
            display: inline-flex;
            align-items: center;
            padding: 8px 15px;
            background-color: var(--light-bg);
            border-radius: 6px;
            text-decoration: none;
            color: var(--primary-color);
            transition: var(--transition);
            font-size: 0.9rem;
            border: 1px solid #ddd;
        }

        .action-link:hover {
            background-color: var(--secondary-color);
            color: white;
            transform: translateY(-2px);
        }

        .action-link i {
            margin-right: 8px;
        }

        .oral-badge {
            display: inline-block;
            background-color: var(--accent-color);
            color: white;
            padding: 5px 10px;
            border-radius: 4px;
            font-size: 0.85rem;
            font-weight: 600;
            margin-left: 10px;
        }

        /* Expertise grid */
        .expertise-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .expertise-category {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.05);
        }

        .expertise-category h3 {
            color: var(--primary-color);
            margin-bottom: 15px;
            padding-bottom: 10px;
            border-bottom: 1px solid #eee;
        }

        .expertise-list {
            list-style-type: none;
        }

        .expertise-list li {
            padding: 8px 0;
            border-bottom: 1px dotted #eee;
            position: relative;
            padding-left: 20px;
        }

        .expertise-list li:before {
            content: "▸";
            color: var(--secondary-color);
            position: absolute;
            left: 0;
        }

        /* Contact form */
        .contact-form {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
        }

        .form-group {
            display: flex;
            flex-direction: column;
        }

        .form-group.full-width {
            grid-column: span 2;
        }

        .form-label {
            margin-bottom: 8px;
            color: var(--primary-color);
            font-weight: 600;
        }

        .form-input {
            padding: 12px 15px;
            border: 1px solid #ddd;
            border-radius: 6px;
            font-size: 1rem;
            transition: var(--transition);
        }

        .form-input:focus {
            outline: none;
            border-color: var(--secondary-color);
            box-shadow: 0 0 0 3px rgba(52, 152, 219, 0.2);
        }

        textarea.form-input {
            min-height: 150px;
            resize: vertical;
        }

        .submit-btn {
            grid-column: span 2;
            padding: 15px;
            background-color: var(--secondary-color);
            color: white;
            border: none;
            border-radius: 6px;
            font-size: 1.1rem;
            font-weight: 600;
            cursor: pointer;
            transition: var(--transition);
        }

        .submit-btn:hover {
            background-color: #2980b9;
            transform: translateY(-2px);
        }

        /* Contact alternatives */
        .contact-alternatives {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .contact-method {
            background-color: white;
            padding: 25px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.05);
        }

        .contact-icon {
            width: 70px;
            height: 70px;
            background: linear-gradient(135deg, var(--secondary-color), #2980b9);
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 15px;
            font-size: 1.8rem;
        }

        .contact-method h3 {
            color: var(--primary-color);
            margin-bottom: 10px;
        }

        .contact-method p {
            color: #7f8c8d;
            margin-bottom: 15px;
            font-size: 0.95rem;
        }

        /* GitHub specific styling */
        .github-stats {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 15px;
            flex-wrap: wrap;
        }

        .github-stat {
            background: rgba(255, 255, 255, 0.1);
            padding: 10px 15px;
            border-radius: 6px;
            text-align: center;
            min-width: 80px;
        }

        .github-stat .count {
            font-size: 1.5rem;
            font-weight: bold;
            display: block;
        }

        .github-stat .label {
            font-size: 0.8rem;
            opacity: 0.9;
        }

        /* Responsive design */
        @media (max-width: 1024px) {
            .main-container {
                grid-template-columns: 1fr;
            }
            
            .profile-container {
                position: static;
                margin-bottom: 30px;
            }
            
            .profile-content {
                display: flex;
                flex-direction: column;
                align-items: center;
            }
            
            .profile-details {
                width: 100%;
                max-width: 500px;
            }
        }

        @media (max-width: 768px) {
            .container, .profile-container {
                padding: 25px;
            }
            
            .section-box {
                padding: 20px;
            }
            
            .contact-form {
                grid-template-columns: 1fr;
            }
            
            .form-group.full-width {
                grid-column: span 1;
            }
            
            .submit-btn {
                grid-column: span 1;
            }
            
            .interests-list, .expertise-grid {
                grid-template-columns: 1fr;
            }
            
            .profile-photo {
                width: 150px;
                height: 150px;
            }
            
            .social-links {
                gap: 10px;
            }
            
            .social-link {
                width: 70px;
            }
            
            .github-stats {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <div class="main-container">
        <!-- Profile Section -->
        <div class="profile-container">
            <div class="profile-content">
                <div class="profile-header">
                    <!-- GitHub repository image path -->
                    <img src="assets/img/rake.png" alt="Maibam Rakesh Singh" class="profile-photo" onerror="this.src='https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=774&q=80'">
                    <h1 class="profile-name">Maibam Rakesh Singh</h1>
                    <div class="profile-title">MLOps Engineer & Statistical Mathematician</div>
                    <p class="profile-tagline">Statistical Mathematician specializing in Stochasticity and Probability</p>
                    
                    <!-- GitHub Stats -->
                    <div class="github-stats">
                        <div class="github-stat">
                            <span class="count" id="repo-count">0</span>
                            <span class="label">Repos</span>
                        </div>
                        <div class="github-stat">
                            <span class="count" id="star-count">0</span>
                            <span class="label">Stars</span>
                        </div>
                        <div class="github-stat">
                            <span class="count" id="follower-count">0</span>
                            <span class="label">Followers</span>
                        </div>
                    </div>
                </div>
                
                <div class="profile-details">
                    <div class="detail-item">
                        <div class="detail-icon">
                            <i class="fas fa-map-marker-alt"></i>
                        </div>
                        <div>
                            <div><strong>Location</strong></div>
                            <div>Trichy | Imphal | India</div>
                        </div>
                    </div>
                    
                    <div class="detail-item">
                        <div class="detail-icon">
                            <i class="fas fa-graduation-cap"></i>
                        </div>
                        <div>
                            <div><strong>Education</strong></div>
                            <div>M.S. in Statistics</div>
                        </div>
                    </div>
                    
                    <div class="detail-item">
                        <div class="detail-icon">
                            <i class="fas fa-briefcase"></i>
                        </div>
                        <div>
                            <div><strong>Experience</strong></div>
                            <div>5+ Years in ML & Data Science</div>
                        </div>
                    </div>
                    
                    <div class="detail-item">
                        <div class="detail-icon">
                            <i class="fas fa-code"></i>
                        </div>
                        <div>
                            <div><strong>Specialization</strong></div>
                            <div>MLOps, Computer Vision, Statistical Analysis</div>
                        </div>
                    </div>
                </div>
                
                <div class="social-links">
                    <a href="https://linkedin.com/in/maibamrakeshsingh" class="social-link" target="_blank">
                        <div class="social-icon">
                            <i class="fab fa-linkedin-in"></i>
                        </div>
                        <span class="social-label">LinkedIn</span>
                    </a>
                    
                    <a href="https://github.com/maibamrakeshsingh" class="social-link" target="_blank">
                        <div class="social-icon">
                            <i class="fab fa-github"></i>
                        </div>
                        <span class="social-label">GitHub</span>
                    </a>
                    
                    <a href="assets/docs/resume.pdf" class="social-link" target="_blank">
                        <div class="social-icon">
                            <i class="fas fa-file-pdf"></i>
                        </div>
                        <span class="social-label">Resume</span>
                    </a>
                </div>
                
                <a href="assets/docs/resume.pdf" class="cv-button" target="_blank">
                    <i class="fas fa-download"></i> Download Full CV
                </a>
            </div>
        </div>

        <!-- Content Sections -->
        <div>
            <!-- Research Interests Section -->
            <div class="container section-box research-box">
                <div class="section-header">
                    <div class="section-icon">
                        <i class="fas fa-search"></i>
                    </div>
                    <h2 class="section-title">Research Interests</h2>
                </div>
                
                <div class="interests-list">
                    <div class="interest-item">
                        <h3 class="interest-title">Computer Vision</h3>
                        <ul class="interest-topics">
                            <li>Image recognition</li>
                            <li>Image generation</li>
                            <li>Video captioning</li>
                        </ul>
                    </div>
                    
                    <div class="interest-item">
                        <h3 class="interest-title">Machine Learning</h3>
                        <ul class="interest-topics">
                            <li>Meta-learning</li>
                            <li>Incremental learning</li>
                            <li>Transfer learning</li>
                        </ul>
                    </div>
                </div>
            </div>

            <!-- Portfolio & Projects Section -->
            <div class="container section-box portfolio-box">
                <div class="section-header">
                    <div class="section-icon">
                        <i class="fas fa-project-diagram"></i>
                    </div>
                    <h2 class="section-title">Portfolio & Projects</h2>
                </div>
                
                <!-- Project 1 -->
                <div class="portfolio-item">
                    <h3 class="portfolio-title">Mnemonics Training: Multi-Class Incremental Learning without Forgetting</h3>
                    <div class="portfolio-authors">
                        <strong>Yaoyao Liu</strong>, Yuting Su, An-An Liu, Bernt Schiele, Qianru Sun
                    </div>
                    <div class="portfolio-conference">IEEE Conference on Computer Vision and Pattern Recognition. CVPR 2020.</div>
                    
                    <div class="action-links">
                        <a href="https://arxiv.org/pdf/2002.10211.pdf" class="action-link" target="_blank">
                            <i class="fas fa-file-pdf"></i> PDF
                        </a>
                        <a href="https://github.com/yaoyao-liu/mnemonics" class="action-link" target="_blank">
                            <i class="fab fa-github"></i> Code
                        </a>
                        <a href="https://mnemonics.yyliu.net/" class="action-link" target="_blank">
                            <i class="fas fa-external-link-alt"></i> Project
                        </a>
                        <span class="oral-badge">Oral Presentation</span>
                    </div>
                </div>
                
                <!-- Project 2 -->
                <div class="portfolio-item">
                    <h3 class="portfolio-title">Learning to Self-Train for Semi-Supervised Few-Shot Classification</h3>
                    <div class="portfolio-authors">
                        Xinzhe Li, Qianru Sun, <strong>Yaoyao Liu</strong>, Shibao Zheng, Qin Zhou, Tat-Seng Chua, Bernt Schiele
                    </div>
                    <div class="portfolio-conference">33rd Conference on Neural Information Processing Systems. NeurIPS 2019.</div>
                    
                    <div class="action-links">
                        <a href="http://papers.nips.cc/paper/9216-learning-to-self-train-for-semi-supervised-few-shot-classification.pdf" class="action-link" target="_blank">
                            <i class="fas fa-file-pdf"></i> PDF
                        </a>
                        <a href="https://github.com/xinzheli1217/learning-to-self-train" class="action-link" target="_blank">
                            <i class="fab fa-github"></i> Code
                        </a>
                        <a href="https://people.mpi-inf.mpg.de/~yaliu/files/learning-to-self-train-poster.pdf" class="action-link" target="_blank">
                            <i class="fas fa-image"></i> Poster
                        </a>
                    </div>
                </div>
                
                <!-- Project 3 -->
                <div class="portfolio-item">
                    <h3 class="portfolio-title">Meta-Transfer Learning for Few-Shot Learning</h3>
                    <div class="portfolio-authors">
                        Qianru Sun*, <strong>Yaoyao Liu*</strong>, Tat-Seng Chua, Bernt Schiele
                    </div>
                    <div class="portfolio-conference">IEEE Conference on Computer Vision and Pattern Recognition. CVPR 2019.</div>
                    
                    <div class="action-links">
                        <a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Sun_Meta-Transfer_Learning_for_Few-Shot_Learning_CVPR_2019_paper.pdf" class="action-link" target="_blank">
                            <i class="fas fa-file-pdf"></i> PDF
                        </a>
                        <a href="https://github.com/yaoyao-liu/meta-transfer-learning" class="action-link" target="_blank">
                            <i class="fab fa-github"></i> Code
                        </a>
                        <a href="https://mtl.yyliu.net/" class="action-link" target="_blank">
                            <i class="fas fa-external-link-alt"></i> Project
                        </a>
                        <a href="https://people.mpi-inf.mpg.de/~yaliu/files/meta-transfer-learning-poster.pdf" class="action-link" target="_blank">
                            <i class="fas fa-image"></i> Poster
                        </a>
                    </div>
                </div>
                
                <!-- GitHub Projects Section -->
                <div class="portfolio-item">
                    <h3 class="portfolio-title">My GitHub Projects</h3>
                    <div class="portfolio-authors">
                        <strong>Maibam Rakesh Singh</strong>
                    </div>
                    <div class="portfolio-conference">Personal & Open Source Contributions</div>
                    
                    <div id="github-projects" class="action-links">
                        <!-- GitHub projects will be loaded dynamically -->
                        <p>Loading GitHub projects...</p>
                    </div>
                </div>
            </div>

            <!-- Expertise & Services Section -->
            <div class="container section-box expertise-box">
                <div class="section-header">
                    <div class="section-icon">
                        <i class="fas fa-cogs"></i>
                    </div>
                    <h2 class="section-title">Expertise & Services</h2>
                </div>
                
                <div class="expertise-grid">
                    <div class="expertise-category">
                        <h3>Data Science & Statistical Consulting</h3>
                        <ul class="expertise-list">
                            <li>Advanced statistical analysis and hypothesis testing</li>
                            <li>Predictive modeling and machine learning solutions</li>
                            <li>Experimental design and A/B testing frameworks</li>
                            <li>Data visualization and dashboard development</li>
                            <li>Statistical inference and Bayesian methods</li>
                        </ul>
                    </div>
                    
                    <div class="expertise-category">
                        <h3>MLOps & DevOps Engineering</h3>
                        <ul class="expertise-list">
                            <li>End-to-end ML pipeline design and implementation</li>
                            <li>Model deployment and serving infrastructure</li>
                            <li>CI/CD automation for machine learning</li>
                            <li>Cloud infrastructure and container orchestration</li>
                            <li>Model monitoring and performance optimization</li>
                        </ul>
                    </div>
                    
                    <div class="expertise-category">
                        <h3>Mathematical Solutions Architecture</h3>
                        <ul class="expertise-list">
                            <li>Algorithm design and mathematical optimization</li>
                            <li>Stochastic modeling and simulation</li>
                            <li>Numerical methods implementation</li>
                            <li>Statistical methodology development</li>
                            <li>Research collaboration and academic consulting</li>
                        </ul>
                    </div>
                </div>
            </div>

            <!-- Contact Section -->
            <div class="container section-box contact-box">
                <div class="section-header">
                    <div class="section-icon">
                        <i class="fas fa-envelope"></i>
                    </div>
                    <h2 class="section-title">Contact Me</h2>
                </div>
                
                <!-- Contact Form (GitHub Pages compatible - uses Formspree) -->
                <form class="contact-form" action="https://formspree.io/f/{your-form-id}" method="POST" id="contactForm">
                    <div class="form-group">
                        <label class="form-label" for="name">Name</label>
                        <input type="text" id="name" name="name" class="form-input" placeholder="Your name" required>
                    </div>
                    
                    <div class="form-group">
                        <label class="form-label" for="email">Email Address</label>
                        <input type="email" id="email" name="email" class="form-input" placeholder="Your email address" required>
                    </div>
                    
                    <div class="form-group full-width">
                        <label class="form-label" for="message">Message</label>
                        <textarea id="message" name="message" class="form-input" placeholder="Your message" required></textarea>
                    </div>
                    
                    <!-- Honeypot field for spam prevention -->
                    <input type="text" name="_gotcha" style="display:none">
                    
                    <button type="submit" class="submit-btn">Send Message</button>
                </form>
                
                <!-- Alternative Contact Methods -->
                <div class="contact-alternatives">
                    <div class="contact-method">
                        <div class="contact-icon">
                            <i class="fas fa-envelope"></i>
                        </div>
                        <h3>Email</h3>
                        <p>maibamrakeshsingh31@gmail.com</p>
                        <p><small>For formal inquiries and collaborations</small></p>
                    </div>
                    
                    <div class="contact-method">
                        <div class="contact-icon">
                            <i class="fas fa-comment-dots"></i>
                        </div>
                        <h3>Quick Messaging</h3>
                        <p>Prefer instant messaging? Connect with me directly via:</p>
                        
                        <div class="social-icons" style="justify-content: center; margin-top: 15px; gap: 15px;">
                            <a href="https://wa.me/919897654321" class="social-icon whatsapp" style="background-color: #25D366; color: white;">
                                <i class="fab fa-whatsapp"></i>
                            </a>
                            <a href="https://discord.com/users/yourdiscordid" class="social-icon discord" style="background-color: #7289DA; color: white;">
                                <i class="fab fa-discord"></i>
                            </a>
                        </div>
                    </div>
                    
                    <div class="contact-method">
                        <div class="contact-icon">
                            <i class="fas fa-clock"></i>
                        </div>
                        <h3>Response Time</h3>
                        <p>Typically respond within 24-48 hours</p>
                        <p><strong>Available for freelance projects and research collaborations.</strong></p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script>
        // GitHub API Integration
        async function fetchGitHubStats() {
            try {
                const response = await fetch('https://api.github.com/users/maibamrakeshsingh');
                const data = await response.json();
                
                // Update GitHub stats
                document.getElementById('repo-count').textContent = data.public_repos || '0';
                document.getElementById('star-count').textContent = '0'; // Need separate API call for stars
                document.getElementById('follower-count').textContent = data.followers || '0';
                
                // Fetch repositories
                const reposResponse = await fetch('https://api.github.com/users/maibamrakeshsingh/repos?sort=updated&per_page=5');
                const repos = await reposResponse.json();
                
                // Display top repositories
                const projectsContainer = document.getElementById('github-projects');
                projectsContainer.innerHTML = '';
                
                repos.forEach(repo => {
                    if (!repo.fork) {
                        const repoLink = document.createElement('a');
                        repoLink.href = repo.html_url;
                        repoLink.className = 'action-link';
                        repoLink.target = '_blank';
                        repoLink.innerHTML = `<i class="fab fa-github"></i> ${repo.name}`;
                        projectsContainer.appendChild(repoLink);
                    }
                });
                
            } catch (error) {
                console.error('Error fetching GitHub data:', error);
                // Set default values
                document.getElementById('repo-count').textContent = '10+';
                document.getElementById('star-count').textContent = '5+';
                document.getElementById('follower-count').textContent = '20+';
            }
        }

        // Form submission handler for Formspree
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const form = this;
            const formData = new FormData(form);
            const submitBtn = form.querySelector('.submit-btn');
            
            // Disable submit button
            submitBtn.disabled = true;
            submitBtn.textContent = 'Sending...';
            
            // Send form data to Formspree
            fetch(form.action, {
                method: 'POST',
                body: formData,
                headers: {
                    'Accept': 'application/json'
                }
            })
            .then(response => {
                if (response.ok) {
                    alert('Thank you! Your message has been sent successfully.');
                    form.reset();
                } else {
                    alert('Oops! There was a problem sending your message. Please try again.');
                }
            })
            .catch(error => {
                alert('Oops! There was a problem sending your message. Please try again.');
            })
            .finally(() => {
                // Re-enable submit button
                submitBtn.disabled = false;
                submitBtn.textContent = 'Send Message';
            });
        });

        // Smooth scroll animation for section boxes
        const sectionBoxes = document.querySelectorAll('.section-box');
        sectionBoxes.forEach(box => {
            box.addEventListener('mouseenter', function() {
                this.style.transition = 'all 0.3s ease';
            });
        });

        // Initialize when page loads
        document.addEventListener('DOMContentLoaded', function() {
            fetchGitHubStats();
        });
    </script>
</body>
</html>
