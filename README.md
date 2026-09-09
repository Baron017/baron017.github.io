<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Baron Offei-Darko | Data Scientist</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>

    <div class="layout-wrapper">
        <!-- LEFT COLUMN: Sidebar -->
        <aside class="sidebar">
            <h1 class="sidebar-name">Baron Offei-Darko</h1>
            
            <img src="profile.jpg" alt="Baron Offei-Darko" class="profile-pic">
            
            <p class="sidebar-desc">Data Science & Engineering Portfolio</p>
            
            <div class="sidebar-contact">
                <a href="https://www.linkedin.com/in/baron-offei-darko-077b1b171/" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a>
                <a href="mailto:baronoffeid@gmail.com"><i class="fas fa-envelope"></i> baronoffeid@gmail.com</a>
                <span><i class="fas fa-map-marker-alt"></i> England</span>
                <span><i class="fas fa-phone"></i> +44 7459144832</span>
            </div>

            <!-- CV Link Button -->
            <div class="cv-section">
                <a href="BaronCV_OD_prof.pdf" target="_blank" class="cv-btn">
                    <i class="fas fa-file-pdf"></i> BaronCV_OD_prof.pdf
                </a>
            </div>
        </aside>

        <!-- RIGHT COLUMN: Main Content -->
        <main class="main-content">
            
            <h1 class="main-title">Data Scientist</h1>
            
            <p class="skills-summary">
                <strong>Technical Skills:</strong> Python, SQL, Deep Learning, Machine Learning, LLMs, Tableau, NumPy, Matplotlib, Pandas, AWS, Microsoft Azure, Node.js, Java, C, HTML, Power BI, MATLAB
            </p>

            <section class="content-section">
                <h2>Education</h2>
                <ul class="education-list">
                    <li>
                        <span class="degree">MSc, Data Science</span>
                        <span class="uni">University of Kent <em>(Sept 2025 - Present)</em></span>
                    </li>
                    <li>
                        <span class="degree">BEng, Computer Science (Hons)</span>
                        <span class="uni">Anglia Ruskin University (Cambridge)</span>
                    </li>
                </ul>
            </section>

            <section class="content-section">
                <h2>Portfolio Projects</h2>
                
                <div class="project-grid">
                    <!-- Project 1: Image Classification -->
                    <div class="project-card-new">
                        <a href="https://github.com/Baron017/image-classification" target="_blank">
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
            </section>

        </main>
    </div>

    <footer>
        <p>&copy; 2026 Baron Offei-Darko. Hosted on <a href="https://baron017.github.io">baron017.github.io</a></p>
    </footer>

</body>
</html>
