<div style="background-color:#e0f7fa; padding:20px; border-radius:15px; border: 2px solid #00acc1;">
<h1 style="color:#006064; text-align:center;">📝 Prac 2: Supervised Machine Learning</h1>
<p style="color:#004d40; font-size:16px;">
This repository demonstrates various <b>supervised machine learning models</b> using multiple datasets.  
We cover both <b>classification</b> and <b>regression</b> tasks with detailed explanations, visualizations, and professional styling.
</p>
</div>

---

<div style="background-color:#f1f8e9; padding:15px; border-radius:10px; border: 2px solid #8bc34a;">
<h2 style="color:#33691e;">📂 Datasets Used</h2>
<ul style="color:#4e342e; font-size:15px;">
<li><b>Iris.csv</b> – Features: Sepal/Petal Length & Width; Target: Species (Classification)</li>
<li><b>HeadBrain.csv</b> – Features: Head Size; Target: Brain Weight (Regression)</li>
<li><b>Bank.csv</b> – Features: Client demographics & campaign info; Target: Term deposit subscription (Classification)</li>
<li><b>Diabetes.csv</b> – Features: Medical measurements; Target: Diabetes outcome (Classification)</li>
<li><b>Adult.csv</b> – Features: Demographics and occupation; Target: Income <=50K / >50K (Classification)</li>
<li><b>50_Startups.csv</b> – (Optional for regression tasks)</li>
<li><b>AirPassengers.csv</b> – (Optional for time series exploration)</li>
</ul>
</div>

---

<div style="background-color:#fff3e0; padding:15px; border-radius:10px; border: 2px solid #ff9800;">
<h2 style="color:#e65100;">💻 Models Implemented</h2>
<ul style="color:#4e342e; font-size:15px;">
<li>Decision Tree (Iris dataset)</li>
<li>Random Forest (Iris dataset)</li>
<li>Linear Regression (Head-Brain dataset)</li>
<li>Logistic Regression (Bank dataset)</li>
<li>K-Nearest Neighbors (Diabetes dataset)</li>
<li>Naïve Bayes (Adult dataset)</li>
</ul>
</div>

---

<div style="background-color:#fce4ec; padding:15px; border-radius:10px; border: 2px solid #e91e63;">
<h2 style="color:#880e4f;">📊 Overall Performance</h2>
<ul style="color:#4e342e; font-size:15px;">
<li>Decision Tree: 100% Accuracy (Iris)</li>
<li>Random Forest: 100% Accuracy (Iris)</li>
<li>Linear Regression: R² ≈ 0.63 (Head-Brain)</li>
<li>Logistic Regression: Accuracy ≈ 0.90 (Bank)</li>
<li>KNN: Accuracy ≈ 0.70 (Diabetes)</li>
<li>Naïve Bayes: Accuracy ≈ 0.80 (Adult)</li>
</ul>
<p style="color:#4e342e;">*Note: Always consider train/test split or cross-validation for realistic evaluation.*</p>
</div>

---

<div style="background-color:#ede7f6; padding:15px; border-radius:10px; border: 2px solid #673ab7;">
<h2 style="color:#4527a0;">🔑 Key Insights</h2>
<ul style="color:#4e342e; font-size:15px;">
<li>Decision Tree and Random Forest perform perfectly on small, well-separated datasets.</li>
<li>Linear Regression demonstrates strong correlation between features and target.</li>
<li>Logistic Regression and KNN show how feature scaling and model choice affect performance.</li>
<li>Naïve Bayes handles categorical variables efficiently for classification tasks.</li>
<li>Preprocessing, visualization, and evaluation metrics are crucial for all supervised ML tasks.</li>
</ul>
</div>

---

<div style="background-color:#fff9c4; padding:15px; border-radius:10px; border: 2px solid #fbc02d;">
<h2 style="color:#f57f17;">⚙️ How to Run</h2>
<ul style="color:#4e342e; font-size:15px;">
<li>Clone the repository: <code>git clone &lt;repo_url&gt;</code></li>
<li>Install dependencies: <code>pip install -r requirements.txt</code></li>
<li>Open <code>Prac2_Supervised_ML.ipynb</code> in Jupyter Notebook or VS Code.</li>
<li>Run all cells sequentially to reproduce the results and visualizations.</li>
</ul>
</div>

---

<div style="background-color:#c8e6c9; padding:15px; border-radius:10px; border: 2px solid #2e7d32;">
<h2 style="color:#1b5e20;">📌 Notes</h2>
<ul style="color:#4e342e; font-size:15px;">
<li>All code is written in Python using <b>scikit-learn</b>, <b>pandas</b>, <b>matplotlib</b>, and <b>seaborn</b>.</li>
<li>Data visualizations help understand feature-target relationships.</li>
<li>Ensure datasets are in the same folder as the notebook for smooth execution.</li>
</ul>
</div>