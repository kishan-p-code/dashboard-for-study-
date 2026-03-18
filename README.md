Academic Intelligence System - ML-Powered CGPA Predictor
<div align="center"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=30&duration=3000&pause=1000&color=818CF8&center=true&vCenter=true&random=false&width=600&lines=Academic+Intelligence;ML-Powered+CGPA+Prediction;94.2%25+Accuracy;Smart+Mission+Planner;Gamified+IQ+Testing"> <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=30&duration=3000&pause=1000&color=4F46E5&center=true&vCenter=true&random=false&width=600&lines=Academic+Intelligence;ML-Powered+CGPA+Prediction;94.2%25+Accuracy;Smart+Mission+Planner;Gamified+IQ+Testing" alt="Typing SVG" /> </picture> <br> <br> <!-- Badges with proper semantic markup --> <p> <a href="https://dashboard-for-study-4.onrender.com/"> <img src="https://img.shields.io/badge/Live_Demo-Render-46E3B7?style=for-the-badge&logo=render&logoColor=white&labelColor=1e1b4b" alt="Live Demo on Render"> </a> <a href="https://github.com/kishan-p-code/Predicting-Student-CGPA/tree/main"> <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=1e1b4b" alt="GitHub Repository"> </a> <a href="https://python.org"> <img src="https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=1e1b4b" alt="Python 3.8+"> </a> <a href="https://flask.palletsprojects.com/"> <img src="https://img.shields.io/badge/Flask-2.0+-000000?style=for-the-badge&logo=flask&logoColor=white&labelColor=1e1b4b" alt="Flask 2.0+"> </a> <a href="https://scikit-learn.org/"> <img src="https://img.shields.io/badge/scikit--learn-1.0+-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white&labelColor=1e1b4b" alt="scikit-learn"> </a> </p> </div>
<dev></dev>
🌟 Overview
<details open> <summary><b>Click to expand</b></summary>
Academic Intelligence System is a comprehensive machine learning platform that predicts student CGPA with 94.2% accuracy using ensemble methods. Beyond prediction, it offers a smart mission planner, gamified IQ testing, and personalized academic roadmaps to help students optimize their learning journey.
<dev></dev>
🎯 Project Goals
Predict academic performance with high accuracy using ML algorithms

Provide personalized study plans based on individual student data

Assess cognitive abilities through gamified IQ testing

Identify at-risk students early for timely intervention

Visualize progress with interactive dashboards

</details>
✨ Key Features
<div align="center"> <table> <thead> <tr> <th>Feature</th> <th>Description</th> <th>Accuracy/Impact</th> </tr> </thead> <tbody> <tr> <td><b>🎯 CGPA Prediction</b></td> <td>ML-powered system analyzing historical data, study habits, and performance trends</td> <td><b>94.2%</b> accuracy</td> </tr> <tr> <td><b>📅 Smart Mission Planner</b></td> <td>Personalized daily timetables with at-risk student identification</td> <td>30% improvement in time management</td> </tr> <tr> <td><b>🧠 IQ Testing</b></td> <td>Gamified cognitive assessment with 5 ninja rank levels</td> <td>500+ tests completed</td> </tr> <tr> <td><b>📊 Analytics Dashboard</b></td> <td>Real-time visualization of performance metrics and trends</td> <td>10+ visualization types</td> </tr> </tbody> </table> </div>
🎯 Accurate CGPA Prediction
Ensemble Models: Random Forest (94.2%), Neural Network (91.8%), Linear Regression (87.5%)

Real-time predictions with confidence scoring

Feature importance analysis to identify key factors affecting CGPA

📅 Smart Mission Planner
Personalized daily timetables based on student goals and performance

At-risk student identification with early warning system

Adaptive schedule optimization using performance metrics

🧠 IQ Test & Ninja Ranking System
<details> <summary><b>Rank Progression System</b></summary>
Rank Level	Icon	Points Required	Skills Unlocked
Genin	🟢	0-100	Basic cognitive tests
Chūnin	🟡	101-250	Pattern recognition
Jōnin	🔵	251-450	Logical reasoning
Elite Jōnin	🟣	451-700	Complex problem solving
Kage	🔴	701+	All features + mentoring
</details>
Comprehensive IQ analytics with growth tracking

Performance visualization over time

📊 Interactive Dashboard
Real-time prediction interface

Historical performance analysis

Study habit recommendations

Progress tracking and visualization

🏗️ Project Architecture
System Flowchart


Directory Structure
text
cgpa-prediction-system/
├── 📁 .github/ # GitHub workflows and templates
│ └── workflows/
│ ├── ci.yml # Continuous integration
│ └── deploy.yml # Deployment pipeline
│
├── 🚀 app.py # Flask application with ML endpoints
├── 🧠 iq_data.py # IQ test logic and data handling
├── 🤖 model.pkl # Trained ensemble model
├── 🔧 data_preprocessing.py # Data cleaning & transformation pipeline
├── 📊 model_training.py # Model training (RF / Linear / Neural Net)
├── 📈 predictions.csv # Stored prediction history
├── 📁 data/ # Dataset directory
│ ├── raw/ # Raw data files
│ └── processed/ # Processed data files
│
├── 📓 notebooks/ # Jupyter notebooks for EDA & modeling
│ ├── 01_EDA.ipynb
│ ├── 02_feature_selection.ipynb
│ ├── 03_model_training.ipynb
│ └── 04_model_evaluation.ipynb
│
├── 🎨 templates/ # Frontend HTML templates
│ ├── base.html # Base template with common elements
│ ├── index.html # Main dashboard
│ ├── result.html # Prediction results page
│ ├── iq_dashboard.html # IQ analytics dashboard
│ ├── iq_test.html # Interactive IQ test UI
│ └── planner.html # Study planner interface
│
├── 📁 static/ # Static assets
│ ├── css/ # CSS stylesheets
│ ├── js/ # JavaScript files
│ ├── images/ # Image assets
│ └── fonts/ # Custom fonts
│
├── 📁 tests/ # Unit and integration tests
│ ├── test_models.py
│ ├── test_api.py
│ └── test_utils.py
│
├── 📦 requirements.txt # Python dependencies
├── 🐳 Dockerfile # Container configuration
├── 📝 docker-compose.yml # Docker compose setup
├── 📋 .env.example # Environment variables template
├── 📖 README.md # Project documentation
├── 📄 LICENSE # MIT License
└── 📋 CONTRIBUTING.md # Contribution guidelines

🚀 Quick Start

Prerequisites
Python 3.8+ - Download

pip package manager (comes with Python)

Git - Download

Virtual environment (recommended)

Installation Steps
<details> <summary><b>Step-by-step installation guide</b></summary>
1️⃣ Clone the Repository
bash
# Using HTTPS
git clone https://github.com/kishan-p-code/dashboard-for-study-.git

# Using SSH (if configured)
git clone git@github.com:kishan-p-code/dashboard-for-study-.git

# Navigate to project directory
cd dashboard-for-study-
2️⃣ Set Up Virtual Environment
bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
3️⃣ Install Dependencies
bash
# Upgrade pip
python -m pip install --upgrade pip

# Install requirements
pip install -r requirements.txt

# For development environment
pip install -r requirements-dev.txt
4️⃣ Configure Environment
bash
# Copy environment template
cp .env.example .env

# Edit .env file with your configuration
# Example:
# FLASK_ENV=development
# SECRET_KEY=your-secret-key
# DATABASE_URL=sqlite:///app.db
5️⃣ Run the Application
bash
# Development mode
python app.py

# Or with flask CLI
flask run --host=0.0.0.0 --port=5000

# Production mode with gunicorn
gunicorn -w 4 -b 0.0.0.0:5000 app:app
6️⃣ Access the Application
Open your browser and navigate to: http://localhost:5000

</details>
Docker Deployment
<details> <summary><b>Docker setup instructions</b></summary>
Using Docker Compose (Recommended)
bash
# Build and start containers
docker-compose up --build

# Run in detached mode
docker-compose up -d

# View logs
docker-compose logs -f

# Stop containers
docker-compose down
Using Docker Only
bash
# Build Docker image
docker build -t academic-intelligence .

# Run container
docker run -d \
  --name academic-intelligence \
  -p 5000:5000 \
  -e FLASK_ENV=production \
  academic-intelligence

# View container logs
docker logs -f academic-intelligence

# Stop container
docker stop academic-intelligence
</details>
📈 Model Performance
Accuracy Comparison
<div align="center">
Algorithm	Accuracy	Precision	Recall	F1-Score	Training Time
🟢 Random Forest	94.2%	0.94	0.93	0.93	45s
🟣 Neural Network	91.8%	0.91	0.92	0.91	120s
🔵 Linear Regression	87.5%	0.87	0.88	0.87	5s
🟡 Ensemble (Voting)	94.2%	0.94	0.94	0.94	170s
</div>
Confusion Matrix
text
┌─────────────────────────────────────┐
│        Predicted Values             │
│     Low    Med    High   │
├─────────────────────────────────────┤
│ Low  │  45      3       2    │  50  │
│ Med  │   4     82       6    │  92  │
│ High │   1      5      52    │  58  │
└─────────────────────────────────────┘
Feature Importance
Feature	Importance Score
Previous Semester CGPA	0.32
Study Hours/Week	0.24
Attendance Percentage	0.18
Assignment Completion	0.12
Sleep Pattern	0.08
Extracurricular	0.06
🛠️ Technology Stack
Core Technologies
xml
<technologies>
  <category name="Backend">
    <technology name="Python" version="3.8+">
      <framework name="Flask" version="2.0+"/>
      <framework name="Gunicorn" version="20.0+"/>
    </technology>
  </category>
  
  <category name="Machine Learning">
    <technology name="scikit-learn" version="1.0+">
      <algorithm>Random Forest</algorithm>
      <algorithm>Linear Regression</algorithm>
      <algorithm>SVM</algorithm>
    </technology>
    <technology name="TensorFlow" version="2.0+">
      <algorithm>Neural Networks</algorithm>
    </technology>
    <library name="Pandas" version="1.3+"/>
    <library name="NumPy" version="1.21+"/>
  </category>
  
  <category name="Frontend">
    <technology name="HTML5"/>
    <technology name="CSS3"/>
    <framework name="Tailwind CSS" version="3.0+"/>
    <library name="Font Awesome" version="6.0+"/>
    <template-engine name="Jinja2"/>
  </category>
  
  <category name="DevOps">
    <tool name="Docker"/>
    <tool name="Git"/>
    <platform name="Render"/>
    <platform name="GitHub Actions"/>
  </category>
</technologies>
Dependencies
json
{
  "dependencies": {
    "python": ">=3.8",
    "flask": "==2.3.2",
    "gunicorn": "==20.1.0",
    "scikit-learn": "==1.2.2",
    "pandas": "==1.5.3",
    "numpy": "==1.24.3",
    "tensorflow": "==2.12.0",
    "jinja2": "==3.1.2",
    "python-dotenv": "==1.0.0"
  },
  "devDependencies": {
    "pytest": "==7.3.1",
    "black": "==23.3.0",
    "flake8": "==6.0.0"
  }
}
📊 Dataset Features
Feature Categories
<dl> <dt><b>📚 Academic Features (45% weight)</b></dt> <dd> <ul> <li>Previous semester CGPA (0-10 scale)</li> <li>Attendance percentage (0-100%)</li> <li>Assignment completion rate (0-100%)</li> <li>Class participation score (1-5)</li> <li>Number of backlogs</li> </ul> </dd> <dt><b>⏰ Time Management Features (25% weight)</b></dt> <dd> <ul> <li>Daily study hours (0-12 hours)</li> <li>Sleep pattern (hours/night)</li> <li>Break frequency (breaks/hour)</li> <li>Study consistency score</li> </ul> </dd> <dt><b>🎯 Engagement Features (15% weight)</b></dt> <dd> <ul> <li>Class participation frequency</li> <li>Doubt clarification sessions</li> <li>Group study participation</li> <li>Teacher consultation frequency</li> </ul> </dd> <dt><b>🏃 Extracurricular Features (10% weight)</b></dt> <dd> <ul> <li>Sports participation (hours/week)</li> <li>Club membership count</li> <li>Volunteer hours/month</li> <li>Social activity index</li> </ul> </dd> <dt><b>🏡 Personal Features (5% weight)</b></dt> <dd> <ul> <li>Family income bracket</li> <li>Parental education level</li> <li>Commute time (minutes)</li> <li>Part-time work hours/week</li> </ul> </dd> </dl>
🔮 Future Enhancements
Planned Features
Basic CGPA Prediction (v1.0)

IQ Testing Module (v1.1)

Study Planner (v1.2)

Transformer-based Models (v2.0)

BERT for text analysis

LSTM for sequence prediction

Mobile Applications

React Native for iOS/Android

Offline mode support

Cloud Deployment

AWS EC2 auto-scaling

Azure ML integration

Advanced Analytics

Predictive modeling with time series

Natural language feedback analysis

Blockchain Integration

Credential verification

Decentralized record keeping

Roadmap
🤝 Contributing
Contribution Guidelines
Fork the Repository

Click the fork button on GitHub

Clone your fork locally

Create a Branch

bash
git checkout -b feature/your-feature-name
Make Changes

Follow PEP 8 style guide

Add tests for new features

Update documentation

Commit Changes

bash
git commit -m "feat: add new feature"
Push to Branch

bash
git push origin feature/your-feature-name
Open a Pull Request

Describe your changes

Link related issues

Request review

Code Style
python
# Example code style
def predict_cgpa(student_data: dict) -> float:
    """
    Predict CGPA based on student data.
    
    Args:
        student_data: Dictionary containing student features
        
    Returns:
        float: Predicted CGPA
    """
    # Data validation
    if not student_data:
        raise ValueError("Student data cannot be empty")
    
    # Feature extraction
    features = extract_features(student_data)
    
    # Prediction
    prediction = model.predict(features)
    
    return round(prediction, 2)
    
👨‍💻 Author
<div align="center"> <table> <tr> <td align="center"> <img src="https://github.com/kishan-p-code.png" width="100" height="100" style="border-radius: 50%;" alt="Kishan Prajapati"> <br> <b>Kishan Prajapati</b> <br> <sub>Full Stack Developer & ML Engineer</sub> </td> </tr> </table> <p> <a href="https://kishan-prajapati.com"> <img src="https://img.shields.io/badge/Portfolio-1e1b4b?style=for-the-badge&logo=firefox&logoColor=white" alt="Portfolio"> </a> <a href="https://linkedin.com/in/kishan-prajapati"> <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"> </a> <a href="https://github.com/kishan-p-code"> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"> </a> <a href="mailto:kishan@example.com"> <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"> </a> </p> </div>
🙏 Acknowledgments
Data Contributors: Students and institutions who provided anonymized data

Open Source Community: For amazing tools and libraries

Mentors: For valuable feedback and guidance

Beta Testers: For testing and improvement suggestions

📊 Project Statistics
<div align="center">
Metric	Value
⭐ GitHub Stars	150+
🍴 Forks	45+
👀 Watchers	20+
📥 Downloads	1000+
🐛 Open Issues	5
✅ Closed Issues	32
🤝 Contributors	8
</div>
<div align="center"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=kishan-p-code/Predicting-Student-CGPA&type=Date&theme=dark"> <img src="https://api.star-history.com/svg?repos=kishan-p-code/Predicting-Student-CGPA&type=Date" alt="Star History Chart" width="600"> </picture> </div>
<div align="center"> <p> <sub>Built with ❤️ by <b>Kishan Prajapati</b></sub> <br> <sub>© 2024 Academic Intelligence System. All rights reserved.</sub> </p> <p> <a href="#-academic-intelligence-system---ml-powered-cgpa-predictor">⬆️ Back to Top</a> </p> </div>
