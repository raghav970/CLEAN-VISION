<div align="center">

# 🌿 EcoWatch
### AI-Driven Garbage Detection & LiFE Practices Monitoring Dashboard

[![GitHub license](https://img.shields.io/github/license/dopTrashTrackers/website)](https://github.com/dopTrashTrackers/website/blob/master/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/dopTrashTrackers/website)](https://github.com/dopTrashTrackers/website/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/dopTrashTrackers/website)](https://github.com/dopTrashTrackers/website/issues)
[![GitHub forks](https://img.shields.io/github/forks/dopTrashTrackers/website)](https://github.com/dopTrashTrackers/website/network)

[Live Demo](https://clean-vision.vercel.app) • [Report Bug](https://github.com/dopTrashTrackers/website/issues) • [Request Feature](https://github.com/dopTrashTrackers/website/issues)

![EcoWatch Dashboard](https://raw.githubusercontent.com/dopTrashTrackers/website/main/docs/dashboard.png)

</div>

## 📋 Table of Contents
- [✨ Introduction](#-introduction)
- [🎯 Problem Statement](#-problem-statement)
- [💡 Proposed Solution](#-proposed-solution)
- [🚀 Features](#-features)
- [⚙️ Technologies Used](#️-technologies-used)
- [🔄 Workflow](#-workflow)
- [📥 Installation](#-installation)
- [🖥️ Usage](#️-usage)
- [🛠️ Challenges and Mitigation](#️-challenges-and-mitigation)
- [🌟 Potential Impact](#-potential-impact)
- [👥 Team Members](#-team-members)
- [🔗 Links](#-links)

## ✨ Introduction
EcoWatch is an innovative AI-powered dashboard designed to revolutionize cleanliness monitoring and LiFE (Lifestyle for Environment) practices near post offices. By leveraging existing CCTV infrastructure and cutting-edge AI models, we provide real-time analytics and alerts for efficient waste management.

## 🎯 Problem Statement
In today's urban landscape, maintaining cleanliness in public spaces, especially near post offices, presents a significant challenge. Our mission is to implement a cost-effective, device-less solution that harnesses AI technology to detect waste and promote sustainable practices.

## 💡 Proposed Solution
Our solution integrates state-of-the-art technologies:
- YOLO v5 for precise garbage detection
- UNet/Transformer models for enhanced low-light visibility
- Real-time CCTV footage processing via OpenCV
- Smart alert system for threshold-based notifications
- Interactive dashboard powered by React.js and Vue.js

## 🚀 Features
| Feature | Description |
|---------|-------------|
| 🎯 Real-Time Detection | YOLO v5-powered garbage detection with precise bounding boxes |
| 🌙 Low-Light Enhancement | Advanced image processing using UNet/Transformer/MIRNet |
| ⚡ Smart Alerts | Automated email/SMS notifications for threshold breaches |
| 📊 Interactive Dashboard | Rich visualization of trends and compliance metrics |
| 🤖 AI Chatbot | Intelligent query resolution and e-waste awareness |

## ⚙️ Technologies Used
mermaid
graph LR
    A[AI Models] --> B[YOLO v5/v8]
    A --> C[UNet]
    A --> D[Transformer]
    E[Frameworks] --> F[FastAPI]
    E --> G[React.js]
    E --> H[Vue.js]
    I[Deployment] --> J[AWS]
    I --> K[Kubernetes]
    I --> L[Firebase]


## 🔄 Workflow
1. 📹 *Video Capture*: CCTV footage collection
2. 🔄 *Frame Processing*: OpenCV-powered frame extraction
3. 🎯 *Detection*: YOLO v5 trash detection
4. 📊 *Analysis*: Coverage calculation & threshold monitoring
5. ⚡ *Alerts*: Real-time notification system
6. 👁️ *Monitoring*: Continuous surveillance

## 📥 Installation
bash
# Clone the repository
git clone https://github.com/dopTrashTrackers/website.git

# Navigate to project directory
cd website

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py


## 🖥️ Usage
1. Open http://localhost:5000 in your browser
2. Access real-time monitoring dashboard
3. Interact with AI chatbot for assistance

## 🛠️ Challenges and Mitigation
| Challenge | Solution |
|-----------|----------|
| 💰 Budget Constraints | Leverage existing infrastructure |
| 🔒 Privacy Concerns | Robust data anonymization |
| 🎯 Detection Accuracy | Self-learning model optimization |

## 🌟 Potential Impact

### 🤝 Social Impact
- Enhanced public safety
- Real-time threat detection
- Community engagement

### 💹 Economic Benefits
- Reduced labor costs
- Improved efficiency
- Automated monitoring

### 🌍 Environmental Impact
- Optimized resource management
- Reduced energy consumption
- Sustainable practices

## 👥 Team Members
<div align="center">

| Member | Institution |
|--------|-------------|
| Harshit Bahety | IIIT BGP |
| Abhinav Gupta | IIIT BGP |
| Ujjwal Shah | IIIT BGP |
| Arbab Arshad | IIIT BGP |

</div>

## 🔗 Links
- 📂 [GitHub Repository](https://github.com/dopTrashTrackers/website)
- 🌐 [Live Demo](https://clean-vision.vercel.app)

---

<div align="center">

### 🌟 Star us on GitHub — it helps!

[Report Bug](https://github.com/dopTrashTrackers/website/issues) • [Request Feature](https://github.com/dopTrashTrackers/website/issues)

</div>
