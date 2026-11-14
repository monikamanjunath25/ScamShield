🛡️ ScamShield

AI-Powered Financial Scam Detection & Awareness Platform

<p align="center">Detect. Protect. Stay Aware.

Arthaton 2026 | AI for Finance

Team Duo Logic

</p>---

👥 Team Details

Detail| Information
Team Name| Duo Logic
Team Member 1| Monika M
Team Member 2| Nuthan Gowda L
Project Name| ScamShield
Hackathon| Arthaton 2026
Theme| AI for Finance
Project Domain| Financial Security & Fraud Detection

---

🌟 1. Project Overview

ScamShield is an AI-powered financial scam detection and awareness platform developed to help people identify suspicious financial messages and recognise potential digital payment fraud.

With the rapid growth of digital banking, UPI transactions, SMS communication and online payments, fraudulent messages have become increasingly difficult for ordinary users to identify.

ScamShield aims to address this challenge through intelligent message analysis, multilingual warning support, suspicious UPI request detection and a user-friendly fraud awareness dashboard.

Our goal is to make digital financial communication safer, simpler and more accessible.

🚨 2. Problem Statement

Digital financial services have made payments faster and more convenient. However, they have also created opportunities for fraudulent messages and misleading payment requests.

Users may encounter:

- Fake bank account blocking notifications.
- Fraudulent cashback and reward messages.
- Fake refund and payment confirmation messages.
- Suspicious UPI collect requests.
- Messages asking users to share OTPs or UPI PINs.
- Urgent messages containing suspicious links.

Many people struggle to distinguish genuine financial communication from fraudulent messages.

The challenge: How can we help users recognise potential financial scams before they make unsafe decisions?

💡 3. Proposed Solution

ScamShield provides a simple platform that analyses suspicious financial messages and highlights potential fraud indicators.

It combines a machine-learning-based text analysis pipeline with rule-based fraud detection and awareness features.

The application is designed to:

1. Analyse suspicious financial messages.
2. Identify potential scam-related patterns.
3. Provide understandable risk assessments.
4. Support multilingual warning messages.
5. Highlight suspicious UPI-related requests.
6. Improve user awareness through visual analytics and safety guidance.

✨ 4. Key Features

4.1 AI-Based Scam Message Detection

- Analyses user-entered SMS and financial messages.
- Uses a Scikit-learn-based machine-learning text analysis pipeline.
- Identifies potential scam indicators.
- Displays the analysis through a simple Gradio interface.
- Helps users recognise suspicious communication.

4.2 Multilingual Scam Warning Support

Designed to support five languages:

- 🇬🇧 English
- 🇮🇳 Kannada
- 🇮🇳 Hindi
- 🇮🇳 Telugu
- 🇮🇳 Tamil

Includes translated warning messages to make scam awareness more accessible to users from different language backgrounds.

4.3 Voice-Based Input Prototype

- Provides browser-based speech recognition.
- Allows users to enter messages through speech when microphone permission is enabled.
- Converts speech into text using browser speech recognition capabilities.

Note: Voice input is an experimental prototype. Its connection to the main scam-detection workflow must be verified before treating it as a fully integrated feature.

4.4 Fake UPI Collect Request Detection

A rule-based detection module designed to identify suspicious payment-related messages.

It checks for indicators such as:

- Unexpected payment approval requests.
- Requests for OTPs or UPI PINs.
- Suspicious links.
- Fake cashback and refund claims.
- Urgent or threatening payment instructions.

The module generates a risk assessment based on the indicators identified and provides safety recommendations.

4.5 Fraud Awareness Dashboard

A visual dashboard designed to improve financial fraud awareness.

It includes:

- Total analysed-message statistics.
- High-risk message counts.
- Suspicious message counts.
- Low-risk message counts.
- Visual risk-category representation.
- Analysis history during the active session.
- Cyber-safety awareness tips.

Note: The UPI detection and dashboard modules are available in the project notebook. Their integration into the main web interface is subject to the current implementation.

---

🔄 5. How ScamShield Works

The overall workflow:

1. User Input: The user enters a suspicious financial message.
2. Message Processing: The application receives and processes the message.
3. Detection: The relevant machine-learning or rule-based detection module analyses suspicious indicators.
4. Risk Assessment: The system generates a result based on its analysis.
5. Safety Guidance: The user receives relevant fraud-awareness recommendations.

System Workflow

       USER
         |
         v
   Message Input
         |
         v
   Text Processing
         |
         v
  Scam Detection System
         |
    +----+----+
    |         |
    v         v
 Machine    Rule-Based
 Learning   UPI Detection
    |         |
    +----+----+
         |
         v
    Risk Assessment
         |
         v
   Result & Warnings
         |
         v
  Fraud Awareness

---

🛠️ 6. Technology Stack

Technology| Application
Python| Core development
Scikit-learn| Machine-learning text processing and classification
Gradio| Interactive web interface
Regular Expressions| Rule-based fraud indicator detection
Matplotlib| Dashboard visualisation
Google Colab| Development and execution environment
HTML / JavaScript| Browser-based voice-input prototype
Web Speech API| Speech recognition where supported by the browser

---

🧠 7. AI and Detection Approach

ScamShield uses two complementary detection approaches:

A. Machine-Learning-Based Analysis

The original scam-message detection module uses a Scikit-learn text-processing and classification pipeline to analyse message content and identify potential scam patterns.

B. Rule-Based Fraud Analysis

The fake UPI detection module checks for predefined suspicious indicators using text-matching rules and generates a risk score.

Combining these approaches provides different ways to identify potentially suspicious financial communication.

The system does not claim perfect detection accuracy. Its results depend on the model, rules and input message.

---

💻 8. How to Run the Project

Recommended Environment: Google Colab

Requirements:

- Google account.
- Internet connection.
- ScamShield GitHub repository.
- Supported web browser.

Execution Steps:

1. Open the ScamShield GitHub repository.
2. Open the project Jupyter Notebook (".ipynb").
3. Open the notebook using Google Colab.
4. Follow the dependency and setup instructions included in the notebook.
5. Execute the notebook cells in their correct order.
6. Run the application launch cell.
7. Open the generated Gradio public URL.
8. Enter a message and test the detection interface.

Clone the Repository

git clone https://github.com/monikamanjunath25/ScamShield.git

Open the downloaded project and follow the notebook's setup instructions to execute the application.

---

🎯 9. Expected Impact

ScamShield aims to create a positive impact by:

- Improving awareness of digital financial scams.
- Helping users recognise suspicious financial messages.
- Encouraging safer UPI payment practices.
- Promoting multilingual financial awareness.
- Making scam detection more accessible.
- Encouraging responsible digital payment behaviour.

🚀 10. Future Enhancements

We aim to improve ScamShield through:

- More advanced multilingual scam detection.
- Complete voice-to-detection integration.
- Enhanced fake UPI collect request analysis.
- Persistent fraud-awareness analytics.
- Expanded and diverse scam-message testing datasets.
- Improved detection of emerging financial scam patterns.
- A more comprehensive real-time fraud awareness experience.

⚠️ 11. Limitations and Responsible Use

ScamShield is an educational scam-awareness and detection assistance platform.

- Its predictions are not guarantees that a message is fraudulent or safe.
- A low-risk result does not guarantee that a message is genuine.
- Rule-based detection may not recognise every type of fraud.
- Voice input requires browser and microphone support and permission.
- Dashboard history is maintained during the active notebook session.
- Users should independently verify unexpected payment requests through official bank or payment-provider channels.

Safety Reminder: Never share your OTP, UPI PIN, banking password or confidential financial information with anyone.

---

🔗 12. Project Links

GitHub Repository

https://github.com/monikamanjunath25/ScamShield

Project Demonstration Video
https://drive.google.com/file/d/1ERwRJfx7ysiMHKFRQCmgxQk1_y-xJwlL/view?usp=drivesdk

---

🙏 13. Acknowledgements

We acknowledge the developers and communities behind the open-source technologies used in this project, including Python, Scikit-learn, Gradio and Matplotlib.

AI-assisted development tools were used during development. The project implementation, testing and final integration were carried out by Team Duo Logic.

---

🏆 14. About Arthaton 2026

Arthaton 2026 – AI for Finance

ScamShield is our contribution towards making digital financial experiences safer through accessible technology, intelligent analysis and fraud awareness.

Built by Team Duo Logic

Monika | Nuthan Gowda

🛡️ ScamShield – Detect. Protect. Stay Aware.
