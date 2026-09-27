AgriSafe AI — SIH Demo
Smart AI-Enabled Rapid Feed and Silage Quality Testing System for Dairy Farmers
📌 Project Overview

AgriSafe AI is a web-based prototype designed to help dairy farmers rapidly assess the quality and safety of cattle feed and silage using AI-assisted analysis.

The system provides:

Feed and silage sample testing
AI-based quality assessment
Moisture and nutritional parameter display
Mould/fungal risk detection
Quality scoring
Farmer recommendations
Silage condition monitoring
Test history and reports
Farmer/FPO management
🚀 Demo Features
1. Dashboard

Displays:

Total feed tests
Healthy samples
Alerts detected
Average test time
AI analysis results
Farmer advisory
Silage monitoring
Quality trends
Recent tests
2. New Test

Farmers can:

Upload a feed/silage image
Select sample type
Start an AI analysis
View the simulated quality result
3. Test History

Contains demo records including:

Date and time
Sample type
Quality score
Moisture
Risk level
Test status
4. Silage Monitor

Displays demo sensor values:

pH
Moisture
Temperature
Humidity
Fermentation status
5. Farmer Advisory

Provides recommendations such as:

Safe to Feed
Storage guidance
Retesting guidance
Nutrition suggestions
6. Farmers / FPO

Displays sample farmer and FPO records for demonstration.

7. Reports

Provides:

Total tests
Safe samples
Alerts
Average quality score
Average analysis time
Demo report download
8. Knowledge Center

Provides basic guidance regarding:

Feed quality
Silage
Storage
AI-based screening
9. Settings

Includes basic:

Notification settings
Auto-save option
Language selection
🛠️ Technology Used
Frontend
HTML5
CSS3
JavaScript
Responsive UI
Planned Backend
Python
FastAPI
REST API
AI/ML
PyTorch
Scikit-learn
NumPy
Pandas
Planned Database
PostgreSQL / MongoDB
Future Integration
Moisture sensor
Temperature sensor
pH sensor
Cloud infrastructure
AI/ML model API
📂 Project Structure
AgriSafe-AI/
│
├── agrisafe_ai_SIH_full_demo.html
├── demo_feed_sample.png
├── demo_silage_sample.png
└── README.md

The current prototype is contained primarily in:

agrisafe_ai_SIH_full_demo.html

HTML, CSS and JavaScript are integrated into the same file for easy SIH demonstration and deployment.

▶️ How to Run
Method 1 — Directly in Browser
Download the project.
Extract the ZIP file.
Open:
agrisafe_ai_SIH_full_demo.html
It will open directly in Chrome, Edge or another modern browser.
Method 2 — VS Code

Open the project folder in VS Code and use Live Server.

Right-click:

agrisafe_ai_SIH_full_demo.html

and select:

Open with Live Server
🤖 Demo AI Workflow
Feed/Silage Image
       ↓
Image Upload
       ↓
AI Analysis
       ↓
Quality Assessment
       ↓
Quality Score
       ↓
Risk Detection
       ↓
Farmer Advisory

Example demo output:

Quality Score: 82/100
Moisture: 12.5%
Crude Protein: 16.2%
Fungal Risk: Low
Status: Safe to Feed
⚠️ Important Demo Note

This version is a frontend prototype for SIH demonstration.

The following are currently simulated:

AI predictions
Sensor readings
Database records
Quality scores
Risk classification

They can later be connected to the actual FastAPI + ML + database + IoT sensor backend.

Demo values should not be treated as actual laboratory test results or veterinary advice.