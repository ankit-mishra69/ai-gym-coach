# 🏋️ AI Gym Coach
### Your Personal AI-Powered Fitness Trainer

**Train Smarter. Move Better. Get Stronger.**

AI Gym Coach is an intelligent fitness coaching application designed to make workouts smarter, safer, and more effective using Artificial Intelligence, Computer Vision, and Voice-Based Interaction.

The goal is to bring the experience of a personal gym trainer directly to your screen — helping users understand their exercise performance, improve workout form, and receive intelligent coaching feedback.

---

## ✨ Key Features

- **🤖 AI-Powered Coaching:** Intelligent fitness assistance and personalized workout guidance.
- **📹 Exercise Form Analysis:** Designed to analyze exercise movements and identify potential form issues.
- **🏋️ Squat Analysis:** Evaluates squat-related metrics, including depth status and back angle.
- **🎙️ Voice-Based Coaching:** Voice interaction with Language Models (LLM) and Text-to-Speech (TTS).
- **⚡ Real-Time Feedback:** Coaching feedback designed to help users improve their exercise technique.
- **💡 Smart Recommendations:** Exercise-related suggestions to support better workout performance.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Core Programming |
| Streamlit | Interactive Web Application |
| Computer Vision | Exercise Movement Analysis |
| Machine Learning | Intelligent Fitness Analysis |
| LLM | AI-Based Coaching |
| Text-to-Speech | Voice Feedback |
| Git & GitHub | Version Control |

## 🏗️ Project Architecture

The project is organized into different modules to keep the application modular, maintainable, and scalable.

```text
AI-GYM-COACH/
│
├── Main App/
│   ├── services/
│   │   └── coaching/
│   │       └── voice_pipeline.py
│   │
│   └── ...
│
├── requirements.txt
├── .gitignore
└── README.md
```

*Additional modules and directories are organized according to the project implementation.*

## ⚙️ Getting Started

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/ankit-mishra69/ai-gym-coach.git
```

### 2. Navigate to the Project

```bash
cd ai-gym-coach
```

### 3. Create a Virtual Environment

```bash
python -m venv .venv
```

### 4. Activate Virtual Environment

**Windows:**

```powershell
.venv\Scripts\activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the Application

```bash
streamlit run "Main App/app.py"
```

*Update the application entry-point path if your main Streamlit file is located elsewhere.*

## 🎯 Project Vision

The vision behind AI Gym Coach is to combine Artificial Intelligence with fitness technology to make personalized fitness coaching more accessible.

Instead of relying only on traditional workout instructions, the application aims to provide intelligent feedback based on exercise performance and help users develop better workout habits.

## 🚀 Future Enhancements

- Support for multiple exercises.
- Advanced body posture and movement tracking.
- Personalized workout plans.
- Fitness progress tracking and analytics.
- Improved AI-powered conversational coaching.
- Nutrition and fitness recommendations.

## 👨‍💻 Developer

**Ankit Mishra**

AI / Machine Learning Enthusiast

GitHub: [@ankit-mishra69](https://github.com/ankit-mishra69)

---

### ⭐ Support

If you find this project interesting, consider giving it a ⭐ on GitHub.

**Built with ❤️, Python, and Artificial Intelligence.**

*Making Fitness Smarter, One Rep at a Time.*
