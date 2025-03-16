# ThreatSensor

## 🔍 Overview
**ThreatSensor** is an AI-powered violence detection system designed to enhance public safety by identifying and responding to potential threats in real-time. The system is designed to be deployed in public areas such as parks, schools, hospitals, and transportation hubs, where ensuring safety is critical. By leveraging advanced machine learning and computer vision techniques, ThreatSensor provides real-time monitoring and automated alerts for violent incidents, helping authorities take swift action.

## 🌍 Why Society Needs ThreatSensor
Violence in public spaces is a growing concern worldwide. Schools, hospitals, and other public venues are meant to be safe havens, yet incidents of violence continue to rise. 
- **Preventative Security:** By detecting violent behavior early, authorities can intervene before situations escalate.
- **Public Safety Enhancement:** Reduces risks for vulnerable populations such as children, patients, and commuters.
- **Rapid Emergency Response:** Automatic alerts to law enforcement and security personnel can save lives by reducing response time.
- **Smart Cities & AI Integration:** Modernizing public safety infrastructure with AI-driven surveillance aligns with smart city initiatives worldwide.
- **Privacy-Preserving Technology:** Designed with ethical considerations, focusing on behavior detection rather than personal identification.

## 🛠 Features
- **Real-time Threat Detection** – AI-powered computer vision detects violent behavior instantly.
- **Automated Alerts** – Sends notifications to law enforcement/security teams for quick intervention.
- **Multi-Environment Compatibility** – Works in parks, schools, hospitals, malls, and public transport stations.
- **Scalable & Customizable** – Can be tailored to different security needs and risk levels.
- **Privacy-Focused AI** – No facial recognition, only behavior analysis to ensure ethical deployment.

## 🚀 Installation
### Prerequisites
- [Miniconda or Anaconda](https://docs.conda.io/en/latest/miniconda.html)
- Git installed on your system

### Setup
```bash
# Clone the repository
git clone https://github.com/yourusername/ThreatSensor.git
cd ThreatSensor

# Create the Conda environment
conda env create -f environment.yaml

# Activate the environment
conda activate threatsensor

# Run the notebook
cd src/
```

[src/training_yolov8.ipynb] is for the data training based on pre-trained model (fine-tuning).
[src/camera.ipynb] is to kickstart the camera live detection using fine-tuned model.

## 📌 Usage
1. **Deploy ThreatSensor on a security camera feed.**
2. **Define the area of interest** (e.g., school, hospital, public park).
3. **Monitor the dashboard** for real-time detection and alerts.
4. **Customize response mechanisms** such as sending alerts via SMS, email, or API integrations.

## 🏛 Deployment Options
- **On-Premise:** Securely process video feeds within a private network.
- **Cloud-Based:** Deploy on AWS, Azure, or Google Cloud for scalable monitoring.
- **Edge AI:** Run on embedded devices (e.g., NVIDIA Jetson, Raspberry Pi) for low-latency processing.

## 🤝 Contributing
We welcome contributions from developers and security experts to improve ThreatSensor.
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes and push to the branch.
4. Submit a pull request.

## 📜 License
Distributed under the MIT License. See `LICENSE` for more details.

## 📧 Contact
For inquiries, support, or collaboration:
- **GitHub:** [Albert0011](https://github.com/Albert0011) [jdaduica](https://github.com/jdaduica) [waiming](https://github.com/waiming)

---
**ThreatSensor: Empowering Safer Communities Through AI-Powered Threat Detection.**
