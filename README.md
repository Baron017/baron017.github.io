
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Baron Offei-Darko | Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <!-- Font Awesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <header>
        <div class="container header-content">
            <div class="profile-section">
                <!-- Make sure your image is named profile.jpg -->
                <img src="profile.jpg" alt="Baron Offei-Darko" class="profile-pic">
                <div class="title-section">
                    <h1>BARON OFFEI-DARKO</h1>
                    <h2 class="subtitle">Data Scientist</h2>
                </div>
            </div>
            <div class="contact-info">
                <a href="https://www.linkedin.com/in/baron-offei-darko-077b1b171/" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a>
                <a href="mailto:baronoffeid@gmail.com"><i class="fas fa-envelope"></i> baronoffeid@gmail.com</a>
                <span><i class="fas fa-map-marker-alt"></i> England</span>
                <span><i class="fas fa-phone"></i> +44 7459144832</span>
            </div>
        </div>
    </header>

    <main class="container">
        <!-- Education Section -->
        <section id="education">
            <h2 class="section-title">Education & Qualifications</h2>
            
            <div class="card">
                <div class="card-header">
                    <h3>University of Kent</h3>
                    <span class="date">Sept 2025 - Present</span>
                </div>
                <p class="degree">MSc Data Science</p>
            </div>

            <div class="card">
                <div class="card-header">
                    <h3>Anglia Ruskin University (Cambridge)</h3>
                </div>
                <p class="degree">BEng. Computer Science (Hons)</p>
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills">
            <h2 class="section-title">Technical Skills</h2>
            <div class="card">
                <div class="skill-category">
                    <h3>Proficient</h3>
                    <div class="tags">
                        <span>Python</span><span>SQL</span><span>Tableau</span><span>NumPy</span><span>Matplotlib</span>
                        <span>R</span><span>Deep Learning</span><span>CRM</span><span>Pandas</span>
                    </div>
                </div>
                <div class="skill-category mt-2">
                    <h3>Familiar</h3>
                    <div class="tags">
                        <span>Machine Learning</span><span>LLM</span><span>AWS</span><span>Microsoft Azure</span>
                        <span>Node.js</span><span>Java</span><span>C</span><span>HTML</span><span>Power BI</span>
                        <span>MATLAB</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects">
            <h2 class="section-title">Projects</h2>
            
            <div class="card project-card">
                <h3>
                    <a href="https://github.com/Baron017/image-classification" target="_blank" class="project-link">
                        Deep Learning Image Classification (QuickDraw dataset) <i class="fas fa-external-link-alt link-icon"></i>
                    </a>
                </h3>
                <ul>
                    <li>Developed an end-to-end computer vision pipeline to classify 15 complex categories from a 112,500-image dataset.</li>
                    <li>Achieved 92.26% accuracy by implementing a custom VGG-style CNN, utilising targeted dropout layers and early stopping callbacks to eliminate overfitting.</li>
                    <li>Engineered efficient data pipelines using stratified sampling and optimised hyperparameter tuning (batch size, dropout rates and architecture) to ensure rapid, stable convergence.</li>
                </ul>
            </div>

            <div class="card project-card">
                <h3>
                    <a href="https://github.com/Baron017/document-Classifier-" target="_blank" class="project-link">
                        Using an LLM as a Document Classifier in Python <i class="fas fa-external-link-alt link-icon"></i>
                    </a>
                </h3>
                <ul>
                    <li>Engineered an automated data ingestion pipeline using Python and REST APIs to extract medical preprint abstracts from medRxiv, utilising Pandas to resolve a severe class imbalance by filtering for high-density to ensure statistical validity.</li>
                    <li>Fine-tuned a domain-specific LLM (BioMedBERT) for multi-class sequence classification using PyTorch and the Hugging Face ecosystem, managing sub-word tokenisation and tensor padding to preserve complex clinical syntax.</li>
                    <li>Designed a custom evaluation framework using Scikit-learn to optimise for the Macro F1-score, successfully diagnosing early-stage model overfitting by analysing divergent training and validation loss curves to inform future hyperparameter tuning.</li>
                </ul>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2026 Baron Offei-Darko. Hosted on <a href="https://baron017.github.io" class="footer-link">baron017.github.io</a></p>
        </div>
    </footer>
</body>
</html>

