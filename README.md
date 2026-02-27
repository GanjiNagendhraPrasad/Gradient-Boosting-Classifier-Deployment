<h1>Gradient Boosting Classifier Deployment</h1>

<p>
This project demonstrates an <strong>end-to-end Machine Learning deployment</strong> using a 
<strong>Gradient Boosting Classifier</strong> to predict whether a breast tumor is 
<strong>Benign</strong> or <strong>Malignant</strong>.  
The trained model is integrated into a <strong>Flask web application</strong> and deployed online 
for real-time predictions.
</p>

<hr>

<h2>🚀 Live Application</h2>

<p>
You can access the deployed web application here:
</p>

<p>
🔗 <a href="https://gradient-boosting-classifier-deployment.onrender.com/" target="_blank">
https://gradient-boosting-classifier-deployment.onrender.com/
</a>
</p>

<hr>

<h2>📌 Project Objective</h2>

<p>
The main objective of this project is to build a complete machine learning pipeline that includes:
</p>

<ul>
  <li>Training a Gradient Boosting classification model</li>
  <li>Saving the trained model using Pickle</li>
  <li>Building a user-friendly web interface using HTML & CSS</li>
  <li>Deploying the model using Flask for real-time predictions</li>
</ul>

<p>
This project makes machine learning predictions accessible to users without any programming knowledge.
</p>

<hr>

<h2>📊 Dataset Description</h2>

<p>
The model is trained using the <strong>Breast Cancer Wisconsin Dataset</strong>, which contains 
numerical features computed from digitized images of breast mass biopsies.
</p>

<p>
Each data sample consists of <strong>30 numerical features</strong> grouped into:
</p>

<ul>
  <li><strong>Mean Features</strong></li>
  <li><strong>Standard Error Features</strong></li>
  <li><strong>Worst Features</strong></li>
</ul>

<p>
The target variable classifies tumors as:
</p>

<ul>
  <li><strong>Benign (Non-Cancerous)</strong></li>
  <li><strong>Malignant (Cancerous)</strong></li>
</ul>

<hr>

<h2>🤖 Machine Learning Model</h2>

<p>
This project uses a <strong>Gradient Boosting Classifier</strong>, an ensemble learning technique 
that builds multiple decision trees sequentially. Each new tree attempts to correct the errors 
made by the previous trees.
</p>

<p>
Advantages of Gradient Boosting:
</p>

<ul>
  <li>High prediction accuracy</li>
  <li>Handles complex patterns effectively</li>
  <li>Works well with structured numerical data</li>
</ul>

<p>
The trained model is saved as:
</p>

<pre><code>gb.pkl</code></pre>

<hr>

<h2>🛠️ Project Structure</h2>

<pre><code>
Gradient-Boosting-Classifier-Deployment
│
├── app.py               # Flask backend application
├── gb.pkl               # Trained Gradient Boosting model
├── templates/
│   └── index.html       # Frontend user interface
├── requirements.txt     # Project dependencies
└── README.md
</code></pre>

<hr>

<h2>⚙️ How the Application Works</h2>

<h3>Frontend (User Interface)</h3>

<p>
The web interface is built using HTML and CSS. Users enter values for all 30 tumor-related features 
through a structured form and submit the data for prediction.
</p>

<h3>Backend (Flask Application)</h3>

<p>
The Flask backend performs the following steps:
</p>

<ol>
  <li>Receives feature values from the HTML form</li>
  <li>Converts inputs into a NumPy array</li>
  <li>Loads the trained model from <code>gb.pkl</code></li>
  <li>Generates a prediction using the Gradient Boosting model</li>
  <li>Returns the result to the web page</li>
</ol>

<hr>

<h2>🎯 Prediction Output</h2>

<p>
Based on the provided inputs, the application displays one of the following results:
</p>

<ul>
  <li><strong>Benign (Non-Cancerous)</strong></li>
  <li><strong>Malignant (Cancerous)</strong></li>
</ul>

<p>
The prediction result is shown directly on the webpage after submission.
</p>

<hr>

<h2>💻 How to Run Locally</h2>

<pre><code>
git clone https://github.com/GanjiNagendhraPrasad/Gradient-Boosting-Classifier-Deployment.git
cd Gradient-Boosting-Classifier-Deployment
pip install -r requirements.txt
python app.py
</code></pre>

<p>
Then open your browser and go to:
</p>

<pre><code>
http://127.0.0.1:5000/
</code></pre>

<hr>

<h2>🧠 Skills Demonstrated</h2>

<ul>
  <li>Machine Learning with Scikit-learn</li>
  <li>Gradient Boosting Algorithm</li>
  <li>Model Serialization using Pickle</li>
  <li>Flask Web Framework</li>
  <li>HTML & CSS for UI</li>
  <li>Model Deployment on Render</li>
</ul>

<hr>

<h2>🏁 Conclusion</h2>

<p>
This project showcases a complete real-world machine learning workflow — from model training to 
deployment. It highlights how machine learning models can be integrated into web applications 
and made accessible through a simple browser interface.
</p>

<p>
It is an excellent project for demonstrating practical ML deployment skills in interviews 
and professional portfolios.
</p>
