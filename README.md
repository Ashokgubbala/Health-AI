# 🩺 HealthAI: Intelligent Healthcare Assistant
**Project by:** Likitha Puttareddy(TEAM LEAD), Sama Pavithra, Velakaturi Lekhya Sreeya
**Institution:** SVCE College, Tirupati
**Internship:** SmartInternz – Virtual Internship (AI using IBM Granite)
---
## 📌 Project Description
HealthAI is a Streamlit-based intelligent healthcare assistant that helps users with health-related queries.
It includes the following AI-powered modules:
* 💬 AI Health Chat – Ask health-related questions
* 🦠 Disease Prediction – Predict illness based on symptoms
* 💊 Treatment Plans – Get AI-suggested treatments
* 📊 Health Analytics – Visualize health data and ask insights
All modules use the IBM Granite 3.3B model (downloaded locally).
---
## 📽️ Demo Video
This project is demonstrated by:
> I am **Likitha Puttareddy**, and our team includes **Sama Pavithra** and **Velakaturi Lekhya Sreeya**.
> We are from **SVCE College, Tirupati**, completing the **SmartInternz Virtual Internship** using **IBM Granite**.
> In this video, I will explain our HealthAI project and showcase its features.
🎥 **Watch our demo video:**
🔗 [https://youtu.be/cwCj4w5zgPM?si=J06R0qJTyS1aPfW-](https://youtu.be/cwCj4w5zgPM?si=J06R0qJTyS1aPfW-)
---
## 📸 Screenshots
Screenshots are included in the documentation file submitted with this project.
---
## 📁 Folder Structure
HealthAI/
├── app.py
├── shared\_model.py
├── patient\_chat.py
├── disease\_prediction.py
├── treatment\_plans.py
├── health\_analytics.py
├── requirements.txt
├── healthai\_logo.png
├── start\_healthai.bat
├── granite/         ← Place downloaded model files here
└── README.md
---
## 🚀 How to Run This Project
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Likitha456/Health-ai.git
cd Health-ai
```
### 2️⃣ Create Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
venv\Scripts\activate  # On Windows
```
### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 4️⃣ Download Model Files (IBM Granite)
Due to GitHub storage limits, the model files are hosted externally.
📥 Download the Granite model files from Google Drive:
🔗 [Download Model Files (3 Parts)](https://drive.google.com/file/d/1DOIGsywV6mKxiYrYz20Ef1tzYV3B9Lv9/view?usp=drive_link)
> After downloading, extract the files and place them inside the `granite/` folder in this project.
### 5️⃣ Run the App
```bash
streamlit run app.py
```
## 👥 Team Members and Contributions

| Name                         | Role                                                                |
| ---------------------------- | ------------------------------------------------------------------- |
| **Likitha Puttareddy**(LEAD) |Full-stack development, backend integration, chatbot AI, deployment |
| **Sama Pavithra**            | Treatment module logic, design assistance                           |
| **Velakaturi Lekhya Sreeya** | Health analytics design, testing, and dataset preparation           |
---
## 🧪 Features in Detail
### 💬 AI Health Chat
Ask general health queries. Powered by IBM Granite model via local inference.
### 🦠 Disease Prediction
Type symptoms and get likely disease predictions.
### 💊 Treatment Plans
Get simple AI-suggested treatment plans for diagnosed conditions.
### 📊 Health Analytics
Displays graphs for:
* Heart Rate
* Blood Pressure
* Blood Sugar
With AI-based insights via prompt.
---
## 🧠 Tech Stack
* Python
* Streamlit
* Hugging Face Transformers
* IBM Granite 3.3B (offline model)
* Matplotlib & Pandas
---
## 🙏 Acknowledgements
* IBM Granite for open-source models
* SmartInternz for internship support
* SVCE College, Tirupati
---
## 🔐 Notes
* Make sure to allow Google Drive access to the model files before submitting.
* You can rename the `granite/` folder, but update the path in the code too.
---
✨ Built with ❤️ by Likitha, Sama Pavithra & Velakaturi Lekhya Sreeya ✨
---
