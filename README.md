<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Baron Offei-Darko | Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <!-- Top Navigation -->
    <nav class="top-nav">
        <a href="#" class="active">HOME</a>
        <a href="#about">ABOUT</a>
        <a href="#projects">PORTFOLIO</a>
        <a href="#skills">SKILLS</a>
    </nav>

    <!-- Hero Section -->
    <section class="hero bg-light">
        <div class="container hero-content">
            <div class="hero-text">
                <h1>Baron Offei-Darko</h1>
                <h2 class="subtitle">DATA SCIENTIST</h2>
                <p>I'm currently an MSc Data Science student with experience using Python, SQL, and Deep Learning to solve complex classification problems. You can view my personal portfolio below.</p>
                
                <a href="#projects" class="btn">VIEW PORTFOLIO</a>

                <div class="contact-links">
                    <a href="https://www.linkedin.com/in/baron-offei-darko-077b1b171/" target="_blank" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
                    <a href="mailto:baronoffeid@gmail.com" title="Email"><i class="fas fa-envelope"></i></a>
                </div>
            </div>
            <div class="hero-image">
                <!-- Your profile picture -->
                <img src="profile.jpg" alt="Baron Offei-Darko">
            </div>
        </div>
    </section>

    <!-- About / Education Section -->
    <section id="about" class="container section-padding">
        <h2 class="section-heading">ABOUT ME</h2>
        <div class="about-grid">
            <div class="about-text">
                <p>I am a Data Scientist based in England, specialising in computer vision and natural language processing. I leverage advanced deep learning models to extract insights and build robust automated pipelines.</p>
                <br>
                <p><strong>Location:</strong> England<br>
                   <strong>Phone:</strong> +44 7459144832<br>
                   <strong>Email:</strong> baronoffeid@gmail.com</p>
            </div>
            <div class="education-info">
                <h3>Education</h3>
                <p><strong>MSc Data Science</strong><br>University of Kent (Sept 2025 - Present)</p>
                <p><strong>BEng. Computer Science (Hons)</strong><br>Anglia Ruskin University (Cambridge)</p>
            </div>
        </div>
    </section>

    <!-- Projects Section (Visual Layout) -->
    <section id="projects" class="bg-light section-padding">
        <div class="container">
            <h2 class="section-heading">PORTFOLIO</h2>
            
            <div class="project-grid">
                <!-- Project 1: Image Classification -->
                <div class="project-card-new">
                    <a href="https://github.com/Baron017/image-classification" target="_blank">
                        <!-- References your uploaded accuracy graph -->
                        <img src="model accuracy graph.png" alt="Model Accuracy Graph" class="project-image">
                    </a>
                    <div class="project-info">
                        <h3>
                            <a href="https://github.com/Baron017/image-classification" target="_blank">
                                Deep Learning Image Classification
                            </a>
                        </h3>
                        <p>Developed an end-to-end computer vision pipeline to classify 112,500 images across 15 categories. Achieved 92.26% accuracy using a custom VGG-style CNN with optimized hyperparameter tuning and targeted dropout to eliminate overfitting.</p>
                    </div>
                </div>

                <!-- Project 2: LLM Classifier -->
                <div class="project-card-new">
                    <a href="https://github.com/Baron017/document-Classifier-" target="_blank">
                        <!-- References your uploaded baseline confusion matrix -->
                        <img src="baseline_confusion_matrix.png" alt="Baseline Confusion Matrix" class="project-image">
                    </a>
                    <div class="project-info">
                        <h3>
                            <a href="https://github.com/Baron017/document-Classifier-" target="_blank">
                                LLM Document Classifier
                            </a>
                        </h3>
                        <p>Built an automated data ingestion pipeline to extract medical preprint abstracts and fine-tuned a domain-specific LLM (BioMedBERT) for multi-class sequence classification. Designed a custom evaluation framework using Scikit-learn to optimize the Macro F1-score and diagnose model overfitting.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="container section-padding">
        <h2 class="section-heading">SKILLS</h2>
        <div class="skills-grid">
            <div>
                <h3 class="skills-title">Proficient</h3>
                <div class="tags">
                    <span>Python</span><span>SQL</span><span>Tableau</span><span>NumPy</span>
                    <span>Matplotlib</span><span>R</span><span>Deep Learning</span><span>CRM</span><span>Pandas</span>
                </div>
            </div>
            <div>
                <h3 class="skills-title">Familiar</h3>
                <div class="tags">
                    <span>Machine Learning</span><span>LLM</span><span>AWS</span><span>Microsoft Azure</span>
                    <span>Node.js</span><span>Java</span><span>C</span><span>HTML</span><span>Power BI</span><span>MATLAB</span>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2026 Baron Offei-Darko. Hosted on <a href="https://baron017.github.io">baron017.github.io</a></p>
        </div>
    </footer>
</body>
</html>
