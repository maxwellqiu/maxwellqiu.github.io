---
layout: single
title: "Resume"
permalink: /resume/
author_profile: true
---

<div class="resume-download-bar">
  <a href="/assets/resume.pdf" class="btn btn--primary" download>
    <i class="fas fa-download"></i>&nbsp; Download PDF
  </a>
</div>

<!-- SUMMARY -->
<div class="resume-section">
<h2>Summary</h2>

Machine Learning Engineer and QA Automation Developer with 6+ years of experience across medical AI research, data science, and enterprise test automation. Published researcher in medical image segmentation (U-Net, PyTorch). Skilled at building models that are reproducible and test systems that prove they stay that way. Concordia University B.A. Data Science, 2025.

</div>

<!-- EDUCATION -->
<div class="resume-section">
<h2>Education</h2>

<div class="resume-entry">
  <div class="resume-entry__header">
    <div>
      <div class="resume-entry__title">Bachelor of Arts — Joint Major in Data Science</div>
      <div class="resume-entry__company">Concordia University</div>
    </div>
    <div class="resume-entry__date">Sep 2022 – Aug 2025 · Montreal, QC</div>
  </div>
  <ul>
    <li>Courses: Computer Vision, Neural Networks, Data Structures, Algorithms, AI & ML, Data Science Lab, Big Data Analytics</li>
  </ul>
</div>

</div>

<!-- PUBLICATIONS -->
<div class="resume-section">
<h2>Publications</h2>

<div class="resume-entry">
  <div class="resume-entry__header">
    <div>
      <div class="resume-entry__title">Lightweight U-Net for Breast Ultrasound Image Segmentation</div>
      <div class="resume-entry__company">Concordia University, Dept. of Computer Science and Software Engineering</div>
    </div>
    <div class="resume-entry__date">Aug 2025</div>
  </div>
  <ul>
    <li>Wenyang Qiu, Ethan Hamburg, Yinkun Zhou, Yaser Esmaeili Salehani</li>
  </ul>
</div>

<div class="resume-entry">
  <div class="resume-entry__header">
    <div>
      <div class="resume-entry__title">Prediction of Patient Breast Cancer Probability</div>
      <div class="resume-entry__company">Applied and Computational Engineering 47(1):207–212</div>
    </div>
    <div class="resume-entry__date">Mar 2024</div>
  </div>
  <ul>
    <li>Wenyang Qiu</li>
  </ul>
</div>

</div>

<!-- TECHNICAL SKILLS -->
<div class="resume-section">
<h2>Technical Skills</h2>

<div class="skills-columns">
  <div>
    <h3>Machine Learning & Data Science</h3>
    <div class="skills-grid">
      <span class="skill-badge">PyTorch</span>
      <span class="skill-badge">scikit-learn</span>
      <span class="skill-badge">XGBoost</span>
      <span class="skill-badge">U-Net / Attention U-Net</span>
      <span class="skill-badge">OpenCV</span>
      <span class="skill-badge">Albumentations</span>
      <span class="skill-badge">pandas</span>
      <span class="skill-badge">NumPy</span>
      <span class="skill-badge">Spark</span>
      <span class="skill-badge">Matplotlib</span>
      <span class="skill-badge">Seaborn</span>
      <span class="skill-badge">Flask / FastAPI</span>
    </div>
  </div>
  <div>
    <h3>QA Automation</h3>
    <div class="skills-grid">
      <span class="skill-badge">Appium</span>
      <span class="skill-badge">Selenium</span>
      <span class="skill-badge">Cypress</span>
      <span class="skill-badge">pytest</span>
      <span class="skill-badge">Robot Framework</span>
      <span class="skill-badge">Page Object Model</span>
      <span class="skill-badge">TestRail</span>
      <span class="skill-badge">Postman</span>
      <span class="skill-badge">JMeter</span>
      <span class="skill-badge">REST Assured</span>
      <span class="skill-badge">AWS (EC2, S3, Lambda)</span>
      <span class="skill-badge">Docker · Kubernetes</span>
    </div>
  </div>
</div>

<div style="margin-top: 1rem;">
  <h3 style="font-size:0.9em; text-transform:uppercase; letter-spacing:0.08em; color:var(--text-muted);">Languages</h3>
  <div class="skills-grid">
    <span class="skill-badge">Python</span>
    <span class="skill-badge">Java</span>
    <span class="skill-badge">C#</span>
    <span class="skill-badge">JavaScript</span>
    <span class="skill-badge">C++</span>
    <span class="skill-badge">SQL</span>
    <span class="skill-badge">Bash</span>
    <span class="skill-badge">HTML/CSS</span>
  </div>
</div>

</div>

<!-- EXPERIENCE -->
<div class="resume-section">
<h2>Work Experience</h2>

<div class="resume-entry">
  <div class="resume-entry__header">
    <div>
      <div class="resume-entry__title">Machine Learning Engineer</div>
      <div class="resume-entry__company">Salehanil Lab @ Concordia University</div>
    </div>
    <div class="resume-entry__date">May 2025 – Present · Montreal, QC</div>
  </div>
  <ul>
    <li>Integrated Squeeze-and-Excitation (SE) attention blocks into a lightweight U-Net for medical image segmentation, reducing false positives by 2% and enhancing early breast cancer diagnosis.</li>
    <li>Preprocessed the BUS-BRA dataset (2,000 files) with Python and Albumentations; containerized the ETL pipeline in Docker for reproducible, portable data workflows.</li>
    <li>Trained and evaluated models with controlled hyperparameter tuning and LR scheduling; executed as Kubernetes Jobs with resource requests/limits for parallel, reproducible runs.</li>
    <li>Reduced model complexity to 3.10M parameters and 0.72 GFLOPs, enabling efficient near real-time inference.</li>
    <li>Implemented hybrid loss (BCE + Dice) in PyTorch, improving segmentation accuracy by 15%.</li>
    <li>Achieved <strong>88.88% Dice / 81.26% mIoU</strong>, outperforming U-Net, Attention U-Net, and SSL baselines.</li>
  </ul>
</div>

<div class="resume-entry">
  <div class="resume-entry__header">
    <div>
      <div class="resume-entry__title">Data Scientist</div>
      <div class="resume-entry__company">Vogelsberger Lab @ MIT</div>
    </div>
    <div class="resume-entry__date">Jul 2023 – Sep 2023 · Remote</div>
  </div>
  <ul>
    <li>Built insight-driven visualizations for a 100,000-population WHO breast cancer dataset using Matplotlib and Seaborn, highlighting trend shifts and outliers for stakeholders.</li>
    <li>Applied scikit-learn across 5 datasets (SVR, polynomial regression, shallow NN) to benchmark forecasting baselines with cross-validated results.</li>
    <li>Pioneered A/B testing frameworks using SciPy to identify user drop-off factors, increasing user engagement by 12%.</li>
    <li>Architected a lightweight data lake (raw/curated/feature zones) with partitioned Parquet, schema/version control, and quality checks.</li>
    <li>Packaged models as internal Flask/FastAPI services for rapid data science product deployment.</li>
  </ul>
</div>

<div class="resume-entry">
  <div class="resume-entry__header">
    <div>
      <div class="resume-entry__title">Software Developer / Automation Developer</div>
      <div class="resume-entry__company">Unity Technologies</div>
    </div>
    <div class="resume-entry__date">May 2022 – May 2025 · Montreal, QC</div>
  </div>
  <ul>
    <li>Developed predictive risk models in Python (feature signals from logs/defects) to flag high-risk features pre-release, achieving a <strong>42% reduction in critical bugs</strong>.</li>
    <li>Engineered scalable data extraction pipelines (pandas/NumPy) to parse Unity test logs and store in MySQL, enabling risk-based validation and test prioritization.</li>
    <li>Automated Unity Editor cross-platform testing on Windows/macOS/Linux using C# with GameDriver.</li>
    <li>Implemented Page Object pattern in C#/Python, improving code reusability by 60% and reducing deployment cycle times by 45%.</li>
    <li>Built Python batch validators with MLP and XGBoost to classify AI behaviors (pathfinding, NPC), reducing low-quality submissions by 56%.</li>
    <li>Integrated TestRail and Jenkins into CI/CD; generated dynamic HTML dashboards and pushed real-time updates via Slack webhooks.</li>
  </ul>
</div>

<div class="resume-entry">
  <div class="resume-entry__header">
    <div>
      <div class="resume-entry__title">Senior QA Developer</div>
      <div class="resume-entry__company">Autodesk</div>
    </div>
    <div class="resume-entry__date">Feb 2021 – Apr 2022 · Montreal, QC</div>
  </div>
  <ul>
    <li>Automated end-to-end testing pipelines in JavaScript using Cypress with TestRail integration, enabling CI-integrated QA workflows with full audit trails.</li>
    <li>Leveraged TestRail analytics to identify defect hotspots and prioritize test coverage, contributing to improved release stability.</li>
    <li>Delivered internal training on JavaScript Cypress scripting and data-driven testing strategies.</li>
    <li>Worked with DevOps engineers to refine CI/CD pipelines and export QA metrics into product dashboards.</li>
  </ul>
</div>

<div class="resume-entry">
  <div class="resume-entry__header">
    <div>
      <div class="resume-entry__title">QA Automation Developer — Mobile Team</div>
      <div class="resume-entry__company">TrackTik</div>
    </div>
    <div class="resume-entry__date">Oct 2019 – Feb 2021 · Montreal, QC</div>
  </div>
  <ul>
    <li>Engineered cross-platform mobile UI automation pipelines using Appium (Java) and UIAutomatorViewer, integrating structured data logging into CI/CD (Travis CI/Jenkins).</li>
    <li>Conducted API validation with Postman, verifying JSON response accuracy and backend reliability metrics.</li>
    <li>Designed scalable test frameworks in Java using PageObject patterns, improving test coverage and fault isolation across mobile platforms.</li>
  </ul>
</div>

<div class="resume-entry">
  <div class="resume-entry__header">
    <div>
      <div class="resume-entry__title">QA Developer</div>
      <div class="resume-entry__company">MavTek</div>
    </div>
    <div class="resume-entry__date">Oct 2018 – Oct 2019 · Montreal, QC</div>
  </div>
  <ul>
    <li>Designed and automated validation frameworks for AWS services (EC2, DynamoDB, S3, Lambda) using Robot Framework (Python) and Cypress (JavaScript).</li>
    <li>Simulated local S3 environments with LocalStack and Moto to enhance testing accuracy and reduce dependency on live cloud resources.</li>
    <li>Validated zero-downtime deployment strategies for AWS Lambda, ensuring 99.99% uptime for critical services.</li>
  </ul>
</div>

<div class="resume-entry">
  <div class="resume-entry__header">
    <div>
      <div class="resume-entry__title">Software QA Engineer — Contractor</div>
      <div class="resume-entry__company">Nuance</div>
    </div>
    <div class="resume-entry__date">Nov 2017 – Oct 2018 · Montreal, QC</div>
  </div>
  <ul>
    <li>Automated speech/NLU test suites for in-car voice systems (BMW, Audi, Harman, PATEO_2B), validating Mandarin and English utterances across multiple audio platforms.</li>
    <li>Improved test throughput by 15% with Robot Framework in Python.</li>
    <li>Created methods to increase real test coverage by 30%; integrated automated reports and trend dashboards in Jenkins.</li>
  </ul>
</div>

</div>
