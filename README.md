
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
        <div class="container">
            <!-- Profile Picture -->
            <img src="profile.jpg" alt="Baron Offei-Darko" class="profile-pic">
            
            <h1>BARON OFFEI-DARKO</h1>
            <h2 class="subtitle">Data Scientist</h2>
            <div class="contact-info">
                <a href="https://www.linkedin.com/in/baron-offei-darko-077b1b171/" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a>
                <a href="mailto:baronoffeid@gmail.com"><i class="fas fa-envelope"></i> baronoffeid@gmail.com</a>
                <span><i class="fas fa-map-marker-alt"></i> Canterbury</span>
                <span><i class="fas fa-phone"></i> +44 7459144832</span>
            </div>
        </div>
    </header>

    <main class="container">
        <!-- Education Section -->
        <section id="education">
            <h2 class="section-title"><i class="fas fa-graduation-cap"></i> Education & Qualifications</h2>
            
            <div class="card">
                <div class="card-header">
                    <h3>University of Kent</h3>
                    <span class="date">Sept 2025 - Present</span>
                </div>
                <p class="degree">MSc Data Science</p>
                <p class="grade">Projected: <strong>DISTINCTION</strong></p>
            </div>

            <div class="card">
                <div class="card-header">
                    <h3>Anglia Ruskin University (Cambridge)</h3>
                </div>
                <p class="degree">BEng. Computer Science (Hons)</p>
                <p class="grade">Grade: <strong>UPPER SECOND CLASS</strong></p>
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills">
            <h2 class="section-title"><i class="fas fa-code"></i> Technical Skills</h2>
            <div class="card">
                <div class="skill-category">
                    <h3>Proficient</h3>
                    <div class="tags">
                        <span>Python</span><span>SQL</span><span>Tableau</span><span>NumPy</span><span>Matplotlib</span>
                        <span>R</span><span>Deep Learning</span><span>Active Directory</span><span>CRM</span>
                        <span>Microsoft Office Suite (Word, Excel, PowerPoint, Outlook, Access)</span>
                    </div>
                </div>
                <div class="skill-category mt-2">
                    <h3>Familiar</h3>
                    <div class="tags">
                        <span>Machine Learning</span><span>LLM</span><span>Pandas</span><span>AWS</span><span>Microsoft Azure</span>
                        <span>Node.js</span><span>Java</span><span>C</span><span>HTML</span><span>Power BI</span>
                        <span>MATLAB</span><span>Microsoft Windows Server</span><span>PowerShell</span><span>IT Systems</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects">
            <h2 class="section-title"><i class="fas fa-project-diagram"></i>Projects</h2>
            
            <div class="card project-card">
                <h3>Deep Learning Image Classification (QuickDraw dataset)</h3>
                <ul>
                    <li>Developed an end-to-end computer vision pipeline to classify 15 complex categories from a 112,500-image dataset.</li>
                    <li>Achieved 92.26% accuracy by implementing a custom VGG-style CNN, utilising targeted dropout layers and early stopping callbacks to eliminate overfitting.</li>
                    <li>Engineered efficient data pipelines using stratified sampling and optimised hyperparameter tuning (batch size, dropout rates and architecture) to ensure rapid, stable convergence.</li>
                </ul>
            </div>

            <div class="card project-card">
                <h3>Facial Recognition in MATLAB</h3>
                <ul>
                    <li>Developed a facial recognition system in MATLAB using the AlexNet neural network, training the convolutional neural network on images of five pro footballers for identity classification.</li>
                    <li>Achieved about 95% model accuracy in correctly identifying individuals, demonstrating strong model performance and effective dataset preparation.</li>
                    <li>Applied deep learning techniques for image classification, including transfer learning, data processing and model evaluation, to optimise recognition accuracy.</li>
                </ul>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2026 Baron Offei-Darko. Hosted on <a href="https://baron017.github.io" style="color: var(--accent-color);">baron017.github.io</a></p>
        </div>
    </footer>
</body>
</html>

