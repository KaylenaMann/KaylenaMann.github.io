
<style>
  .dropdown-checkbox { display: none; }
  .dropdown-label { cursor: pointer; font-weight: 600; display: inline-block; margin: 0.35rem 0; }
  .dropdown-label::after { content: " ▾"; }
  .dropdown-checkbox:checked + .dropdown-label::after { content: " ▴"; }
  .project-details { display: none; margin-top: 0.35rem; font-size: 0.95rem; }
  .dropdown-checkbox:checked + .dropdown-label + .project-details { display: block; }
</style>

<p>
  <a href="https://github.com/KaylenaMann/Final_Project">
    <strong>Massachusetts Schools Early Warning System</strong>
  </a>
</p>

<img
  width="936"
  height="322"
  alt="Logistic regression diagnostics plot for early warning model"
  src="https://github.com/user-attachments/assets/e2ce5581-6cae-4ee0-81c3-340338388325"
/>

<input type="checkbox" id="proj-ews" class="dropdown-checkbox">
<label for="proj-ews" class="dropdown-label">Project details</label>

<div class="project-details">
  <!-- your description paragraphs here -->
</div>

<style>
/* Simple dropdown/accordion styling */
.project-card {
  margin-bottom: 1.75rem;
}

.project-card img {
  max-width: 100%;
  height: auto;
  margin: 0.5rem 0 0.25rem;
}

/* Hide the checkbox – we just use it for CSS toggling */
.dropdown-checkbox {
  display: none;
}

/* Clickable label that acts like the dropdown header */
.dropdown-label {
  display: inline-block;
  cursor: pointer;
  font-weight: 600;
  margin: 0.35rem 0 0.5rem;
}

.dropdown-label::after {
  content: " ▾";
  font-weight: normal;
}

/* When checked, flip the arrow */
.dropdown-checkbox:checked + .dropdown-label::after {
  content: " ▴";
}

/* Details are hidden by default */
.project-details {
  display: none;
  margin-top: 0.35rem;
  font-size: 0.95rem;
}

/* Show details when checkbox is checked */
.dropdown-checkbox:checked + .dropdown-label + .project-details {
  display: block;
}
</style>

<div class="project-card">
  <p>
    <a href="https://github.com/KaylenaMann/Final_Project">
      <strong>Massachusetts Schools Early Warning System</strong>
    </a>
  </p>

  <img
    width="936"
    height="322"
    alt="Logistic regression diagnostics plot for early warning model"
    src="https://github.com/user-attachments/assets/e2ce5581-6cae-4ee0-81c3-340338388325"
  />

  <input type="checkbox" id="proj-ews" class="dropdown-checkbox">
  <label for="proj-ews" class="dropdown-label">Project details</label>

  <div class="project-details">
    <p>
      Early-warning prediction model for Massachusetts schools, identifying schools
      at risk of falling into the bottom quartile of math proficiency.
    </p>
    <p>
      This project serves as an early-warning system, identifying at-risk schools based
      on yearly tracked data. The features are repeated annually, making it useful for
      policymakers to flag schools a full year in advance—before new test scores are
      released—and for individual schools to understand their relative risk level.
    </p>
    <p>
      The main analysis and modeling pipeline is organized into four scripts, where I
      compare regular logistic regression, ridge logistic regression, K-Nearest Neighbors
      (KNN), and a Random Forest model.
    </p>
    <p><strong>Skills:</strong> Python · scikit-learn · pandas · model evaluation</p>
    <p>
      <a href="https://github.com/KaylenaMann/Final_Project">🔗 View on GitHub</a>
    </p>
  </div>
</div>

---

<div class="project-card">
  <p>
    <a href="https://github.com/KaylenaMann/HW2">
      <strong>Logistic Regression / KNN Stroke Risk Prediction</strong>
    </a>
  </p>

  <img
    width="511"
    height="386"
    alt="ROC curve for stroke risk prediction"
    src="https://github.com/user-attachments/assets/38655b46-d54d-4a4a-8a80-f4bcd30457aa"
  />

  <input type="checkbox" id="proj-stroke" class="dropdown-checkbox">
  <label for="proj-stroke" class="dropdown-label">Project details</label>

  <div class="project-details">
    <p>
      Developed a binary classification model to predict stroke risk based on
      patient characteristics.
    </p>
    <p>
      Compared <strong>Logistic Regression</strong>, <strong>K-Nearest Neighbors (KNN)</strong>,
      and <strong>Ridge Regression</strong>, evaluating model performance with
      <strong>F1-score</strong>, <strong>ROC–AUC</strong>, and
      <strong>precision–recall</strong> metrics.
    </p>
    <p><strong>Skills:</strong> Python · scikit-learn · pandas · model evaluation</p>
    <p>
      <a href="https://github.com/KaylenaMann/HW2">🔗 View on GitHub</a>
    </p>
  </div>
</div>

---

### Psychometrics Projects

<div class="project-card">
  <p>
    <a href="https://github.com/KaylenaMann/3pl-Lab-Project">
      <strong>3PL Psychometrics Project</strong>
    </a>
  </p>

  <img
    width="543"
    height="397"
    alt="Item Response Theory 3PL model plots"
    src="https://github.com/user-attachments/assets/077b0cdf-ab5b-4edd-be4e-414ef1fed659"
  />

  <input type="checkbox" id="proj-3pl" class="dropdown-checkbox">
  <label for="proj-3pl" class="dropdown-label">Project details</label>

  <div class="project-details">
    <p><strong>Item Response Theory Psychometrics Analysis</strong></p>
    <p>
      Implemented a three-parameter logistic (3PL) Item Response Theory model to
      evaluate test quality and item characteristics across 500 examinees.
      Analyzed item difficulty, discrimination, and guessing parameters, and used
      priors to stabilize estimates.
    </p>
    <p>
      Evaluated model fit indices, classical item statistics, and person-fit
      diagnostics to identify problematic items and unusual response patterns.
    </p>
    <p>
      <strong>Skills:</strong> R · mirt · Item Response Theory · Psychometrics ·
      Statistical Modeling
    </p>
    <p>
      <a href="https://github.com/KaylenaMann/3pl-Lab-Project">🔗 View on GitHub</a>
    </p>
  </div>
</div>

---

[Project 3 Title](http://example.com/)  
<img src="images/dummy_thumbnail.jpg?raw=true" alt="Project 3 thumbnail" />

---

### Category Name 2

- [Project 1 Title](http://example.com/)
- [Project 2 Title](http://example.com/)
- [Project 3 Title](http://example.com/)
- [Project 4 Title](http://example.com/)
- [Project 5 Title](http://example.com/)

---

<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
