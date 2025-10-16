<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles/main.css">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Bungee&family=Orbitron:wght@400..900&family=Roboto+Mono:ital,wght@0,100..700;1,100..700&display=swap" rel="stylesheet">
    <link rel="icon" type="image/png" href="img/hed.jpg">
    <title>João Pedro - FullStack Developer</title>
</head>
<body>
    <!-- Navigation  -->
    <nav class="navbar" data-aos="fade-down">
        <div class="nav-container">
            <div class="nav-logo">
                <span class="logo-text">&lt;/jp&gt;</span>
               </div>
            <div class="nav-menu">
                <a href="#home" class="nav-link">Home</a>
                <a href="#about" class="nav-link">Sobre</a>
                <a href="#skills" class="nav-link">Skills</a>
                <a href="#contact" class="nav-link">Contato</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-container">
            <div class="hero-content" data-aos="fade-right">
                <div class="hero-text">
                    <h1 class="hero-title">
                        <span class="greeting">Olá, eu sou</span>
                        <span class="name">João Pedro</span>
                        <span class="role">FullStack Developer | Pentester</span>
                    </h1>
                    <p class="hero-description">
                        Transformando ideias em código. Especializado em desenvolvimento web moderno 
                        e apaixonado por tecnologia desde 2012.
                    </p>
                    <div class="hero-buttons">
                        <a href="#about" class="btn btn-primary">Conheça-me</a>
                        <a href="#contact" class="btn btn-secondary">Vamos conversar</a>
                    </div>
                </div>
            </div>
            <div class="hero-visual" data-aos="fade-left">
                <div class="profile-container">
                    <div class="profile-image">
                        <img src="img/icon.jpeg" alt="João Pedro" class="profile-img">
                        <div class="profile-overlay"></div>
                    </div>
                    <div class="floating-elements">
                        <div class="code-snippet">
                            <div class="terminal-header">
                                <span class="terminal-dot red"></span>
                                <span class="terminal-dot yellow"></span>
                                <span class="terminal-dot green"></span>
                            </div>
                            <div class="terminal-content">
                                <p class="code-line"><span class="prompt">$</span> whoami</p>
                                <p class="code-line"><span class="output">joao-pedro-dev</span></p>
                                <p class="code-line"><span class="prompt">$</span> cat skills.txt</p>
                                <p class="code-line"><span class="output">FullStack | Backend | Security</span></p>
                            </div>
                </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="scroll-indicator" data-aos="fade-up">
            <div class="scroll-arrow"></div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <div class="section-header" data-aos="fade-up">
                <h2 class="section-title">Sobre Mim</h2>
                <p class="section-subtitle">Conheça um pouco da minha jornada</p>
            </div>
            
            <div class="about-content">
                <div class="about-text" data-aos="fade-right">
                    <div class="about-card">
                        <h3>Minha História</h3>
                        <p>
                            Me chamo João Pedro, moro em uma cidade pequena no interior de São Paulo. 
                            Sou apaixonado por tecnologia desde criança, mas comecei a estudar programação 
                            em 2023 quando comprei meu primeiro computador.
                        </p>
                        <p>
                            Desde então, tenho me dedicado intensamente ao desenvolvimento web, 
                            focando especialmente em backend e segurança. Atualmente estou estudando 
                            para me tornar um pentester profissional.
                        </p>
                    </div>
                    
                    <div class="about-stats">
                        <div class="stat-item" data-aos="zoom-in" data-aos-delay="100">
                            <div class="stat-number">18</div>
                            <div class="stat-label">Anos</div>
                </div>
                        <div class="stat-item" data-aos="zoom-in" data-aos-delay="200">
                            <div class="stat-number">2+</div>
                            <div class="stat-label">Anos de Estudo</div>
                </div>
                        <div class="stat-item" data-aos="zoom-in" data-aos-delay="300">
                            <div class="stat-number">∞</div>
                            <div class="stat-label">Paixão por Código</div>
                </div>
                </div>
                </div>

                <div class="about-quote" data-aos="fade-left">
                    <div class="quote-card">
                        <div class="quote-text">
                            <p>"O que é a Matrix? Controle. A Matrix é um mundo de sonhos gerado por computador..."</p>
                            <p>"É o mundo que foi colocado diante dos seus olhos para lhe cegar da verdade."</p>
                        </div>
                        <div class="quote-author">- Morpheus</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="skills">
        <div class="container">
            <div class="section-header" data-aos="fade-up">
                <h2 class="section-title">Skills & Tecnologias</h2>
                <p class="section-subtitle">Minhas especialidades técnicas</p>
            </div>
            
            <div class="skills-grid">
                <div class="skill-category" data-aos="fade-up" data-aos-delay="100">
                    <h3 class="category-title">Frontend</h3>
                    <div class="skill-items">
                        <div class="skill-item">
                            <span class="skill-name">HTML5</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="90%"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span class="skill-name">CSS3</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="85%"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span class="skill-name">JavaScript</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="40%"></div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="skill-category" data-aos="fade-up" data-aos-delay="200">
                    <h3 class="category-title">Backend</h3>
                    <div class="skill-items">
                        <div class="skill-item">
                            <span class="skill-name">Python</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="85%"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span class="skill-name">C#</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="75%"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span class="skill-name">Node.js</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="35%"></div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="skill-category" data-aos="fade-up" data-aos-delay="300">
                    <h3 class="category-title">Ferramentas</h3>
                    <div class="skill-items">
                        <div class="skill-item">
                            <span class="skill-name">Git</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="90%"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span class="skill-name">GitHub</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="85%"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span class="skill-name">Linux</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="80%"></div>
                            </div>
                        </div>
                </div>
                </div>
                
                <div class="skill-category" data-aos="fade-up" data-aos-delay="400">
                    <h3 class="category-title">Idiomas</h3>
                    <div class="skill-items">
                        <div class="skill-item">
                            <span class="skill-name">Português</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="100%"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span class="skill-name">Inglês</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="75%"></div>
                            </div>
                        </div>
                        <div class="skill-item">
                            <span class="skill-name">Francês</span>
                            <div class="skill-bar">
                                <div class="skill-progress" data-width="40%"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <div class="section-header" data-aos="fade-up">
                <h2 class="section-title">Vamos Conversar?</h2>
                <p class="section-subtitle">Estou sempre aberto a novas oportunidades e projetos</p>
            </div>
            
            <div class="contact-content">
                <div class="contact-info" data-aos="fade-right">
                    <div class="contact-card">
                        <h3>Entre em Contato</h3>
                        <p>Pronto para transformar suas ideias em realidade digital.</p>
                        
                        <div class="contact-methods">
                            <a href="https://github.com/defaultxx00" class="contact-method" target="_blank">
                                <div class="contact-icon">📱</div>
                                <div class="contact-details">
                                    <span class="contact-label">GitHub</span>
                                    <span class="contact-value">@defaultxx00</span>
                                </div>
                            </a>
                            
                            <a href="https://www.linkedin.com/in/joao-pedro-70b08b318/" class="contact-method" target="_blank">
                                <div class="contact-icon">💼</div>
                                <div class="contact-details">
                                    <span class="contact-label">LinkedIn</span>
                                    <span class="contact-value">João Pedro</span>
                                </div>
                            </a>
                            
                            <div class="contact-method">
                                <div class="contact-icon">📧</div>
                                <div class="contact-details">
                                    <span class="contact-label">Instagram</span>
                                    <span class="contact-value">@jao_pedro.f</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="contact-terminal" data-aos="fade-left">
                    <div class="terminal-window">
                        <div class="terminal-header">
                            <span class="terminal-dot red"></span>
                            <span class="terminal-dot yellow"></span>
                            <span class="terminal-dot green"></span>
                            <span class="terminal-title">terminal</span>
                        </div>
                        <div class="terminal-content">
                            <p class="code-line"><span class="prompt">$</span> echo "Hello World!"</p>
                            <p class="code-line"><span class="output">Hello World!</span></p>
                            <p class="code-line"><span class="prompt">$</span> <span class="cursor">_</span></p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <p>&copy; 2024 João Pedro. Feito com ❤️ e muito ☕</p>
                <p class="footer-quote">"O código é poesia em movimento"</p>
            </div>
        </div>
    </footer>

    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script src="scripts/main.js"></script>
<script>
        AOS.init({
            duration: 1000,
            once: true
        });
</script>
</body>
</html>
