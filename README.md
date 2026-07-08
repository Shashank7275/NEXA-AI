# 🤖 Nexa AI - Personal AI Assistant

Welcome to **Nexa AI** 🚀

Nexa AI is a futuristic personal AI assistant inspired by modern AI systems. It can understand voice commands, perform tasks, automate workflows, and interact with your computer in a smart way.

---

# 📋 Prerequisites

Before starting, make sure you have:

* Python **3.11+** (Recommended: Python 3.12)
* Git
* Internet Connection
* Microphone Enabled
* Speakers/Headphones

---

# 🚀 Step 1: Clone the Repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd Nexa-AI
```

---

# 🐍 Step 2: Create a Virtual Environment (Recommended)

### Windows

```bash
python -m venv .venv
```

Activate the virtual environment

```bash
.venv\Scripts\activate
```

### macOS / Linux

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Agar activation successful ho gaya hai to terminal ke beginning me **(.venv)** dikhne lagega.

---

# 📦 Step 3: Install Required Packages

Run the following command:

```bash
pip install -r requirements.txt
```

Ye command project ke saare required Python packages automatically install kar dega.

---

# 🔑 Step 4: Configure API Keys

Project folder ke andar ek **.env** file create karein.

Example:

```text
LIVEKIT_URL=
LIVEKIT_API_KEY=
LIVEKIT_API_SECRET=

GOOGLE_API_KEY=

GOOGLE_SEARCH_API_KEY=
SEARCH_ENGINE_ID=

OPENWEATHER_API_KEY=

OPENAI_API_KEY=
# Add other API keys if required
```

⚠️ **Important**

* Apni real API keys hi use karein.
* `.env` file ko GitHub par upload mat karein.
* Kisi ke saath API keys share na karein.

---

# ▶️ Step 5: Run Nexa AI

Sab kuch setup hone ke baad terminal me ye command run karein:

```bash
python agent.py console
```

Agar setup sahi hai to Nexa AI initialize ho jayega aur voice commands ke liye ready hoga.

---

# 📝 Customize Your Name

Agar aap chahte hain ki Nexa AI aapko naam se greet kare, to project ke **Prompt/System Prompt** section me apna naam add kar sakte hain.

Example:

```
User Name: Prateek
```

Uske baad Nexa AI aapse is tarah baat karega:

> "Hello Prateek Sir 👋"

Ya aap apni preference ke according greeting bhi customize kar sakte hain.

---

# 📁 Project Structure

```text
Nexa-AI/
│
├── agent.py
├── requirements.txt
├── .env
├── prompts/
├── modules/
├── utils/
├── assets/
└── README.md
```

---

# 💡 Tips

* Always activate the virtual environment before running the project.
* Check that all API keys are valid.
* Make sure your microphone permissions are enabled.
* Keep Python packages updated.
* If you face any errors, verify that all dependencies are installed correctly.

---

# ▶️ Quick Start

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>

cd Nexa-AI

python -m venv .venv

.venv\Scripts\activate

pip install -r requirements.txt

python agent.py console
```

---

# ❤️ Support

If you like this project:

⭐ Star this repository

🍴 Fork the project

🐞 Report bugs

💡 Suggest new features

---

# 📜 License

This project is intended for learning and personal development purposes.

---

## 🚀 Enjoy Building with Nexa AI!

**Welcome to the future of AI assistants.**

 
