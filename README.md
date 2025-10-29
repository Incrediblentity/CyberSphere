🛡 CyberSphere — The All-in-One Digital Trust Platform

HackThrone Project by Team CodeBlooded

🚀 Overview:

In today’s digital world, millions fall victim daily to phishing scams, fake news, and deepfake media.

Traditional tools only solve one part of the problem — some detect malware, others verify news — but there’s no unified platform that helps users verify online content easily and transparently.

CyberSphere bridges that gap.

It’s an AI-powered, explainable platform that allows users to:

Scan websites for phishing or scams 🕵‍♂

Verify headlines for fake or misleading content 📰

(Optionally) Detect deepfake images/videos 🎭

Learn about online safety and cyber hygiene 🔐

💡 Problem Statement:

Online deception — from scam websites and phishing links to fake news and deepfakes — has become rampant.

Users lack a single, easy-to-use verification tool that provides:

A trust score for any link, headline, or media

Human-readable explanations behind each verdict

Educational insights for better cyber awareness

This leads to financial frauds, misinformation spread, and reduced trust in digital spaces.

🌟 Opportunities:

🧩 All-in-One Verification: Website, News, and Media checks in one platform.

🧠 Explainable AI: Clear, human-readable reasoning for all predictions.

📈 Scalable Design: Expandable to browser extensions and mobile apps.

🎓 Educational Impact: Promotes digital literacy and cyber hygiene.

⚙ Methods & Approach:

Multi-Modal Detection
Website Scanner:

Uses SSL validation, domain age, and blacklists.

Employs a lightweight ML phishing model.

Returns a Trust Score and reasoning.

News & Headline Checker:

NLP model using TF-IDF + Logistic Regression

Classifies as Real, Misleading, or Fake.

Deepfake Detector (Optional): Uses pre-trained AI models to analyze manipulated media.

Explainable AI
Combines deterministic rules with AI predictions to generate transparent, human-understandable explanations for every result.

Architecture
Frontend: React / Next.js

Backend: Flask / Node.js

Data Sources: PhishTank, Kaggle Fake News datasets, public threat intel

UI Tabs:

• Website Scanner

• News Checker

• Deepfake Detector

• Safety Insights

🔄 Process Flow:

User Input: URL, headline, or media file

Backend Processing: Sends input to relevant module (phishing, news, or media)

Detection Engine: Runs AI + heuristic analysis

Explainable Output:

Verdict (Safe / Risky / Fake / Real)

Reasons for decision

Educational insights and suggested next steps

🧩 Tech Stack:

Layer Technology

Frontend React / Next.js

Backend Flask / Node.js

AI Models TF-IDF, Logistic Regression, Heuristic Rules

Database SQLite / MongoDB

Datasets PhishTank, Kaggle Fake News Dataset

Optional Media Analysis Pre-trained Deepfake Detection Models

📊 Output Example:

Input Type Example Input Result Explanation

Website URL http://banklogin-secure.xyz ⚠ Suspicious Domain age < 30 days, SSL invalid, appears on blacklist

News Headline “NASA confirms aliens landed on Earth” ❌ Fake TF-IDF model similarity with known fake dataset

Image Manipulated celebrity video 🎭 Deepfake Detected Facial artifact mismatch and frame inconsistency

🧠 Learning Impact:

Educates users about scam patterns, fake news spotting, and cyber hygiene.

Encourages safe browsing habits and awareness of digital deception.

👥 Team CodeBlooded:

• Manan Singhal

• Viransh Jain

• Aagam Shah

• Smit Kamatnurkar

🏁 Future Scope:

🌐 Browser extension and mobile app versions

🗞 Real-time misinformation tracking

🧩 Integration with enterprise verification systems

🎓 Educational modules for schools and journalists

🏆 Hackathon: HackThrone

Built with ❤ by Team CodeBlooded to make the digital world safer, smarter, and more trustworthy.
