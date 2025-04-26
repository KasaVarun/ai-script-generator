---

#  AI Script & Storyboard Generator
[![View in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://ai-script-generator.streamlit.app/)

Generate creative **5-page movie scripts** and **cinematic storyboard illustrations** with **voiceover videos**, powered by **OpenAI GPT-4o** and **DALL·E 3**.

Made with ❤️ by **Varun Kasa**.

---

##  About the Project

**Problem:**  
Scriptwriting and visual storyboarding are time-consuming and require professional expertise. Beginners, writers, and indie filmmakers often struggle to rapidly prototype ideas.

**Solution:**  
This app provides an AI-powered solution that takes your input (genres, characters, and premise) and automatically generates:
- A **5-page professional movie script**
- **Storyboard images** (one per page)
- **Voiceover narration** + **video** combining the storyboard and script

All **without coding or design skills**.
[ChatGPT Image Apr 26, 2025, 02_18_29 PM](https://github.com/user-attachments/assets/9aea3492-38b5-4e1b-b414-1f1673a09efc)

---

##  Built With!

- [Streamlit](https://streamlit.io/) — For the frontend web app
- [OpenAI API](https://platform.openai.com/docs) — GPT-4o for scripts, DALL·E 3 for images
- [Pillow](https://python-pillow.org/) — Image handling
- [gTTS](https://pypi.org/project/gTTS/) — Text-to-speech for narration
- [moviepy](https://zulko.github.io/moviepy/) — Storyboard + voiceover video creation
- [Requests](https://requests.readthedocs.io/en/latest/) — HTTP calls

---

##  Installation

```bash
# Clone this repository
git clone https://github.com/your-username/ai-script-generator.git
cd ai-script-generator

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
```

---

##  How to Use

1. Enter your **OpenAI API key**.
2. Choose:
   - **Primary genre** (e.g., Sci-Fi)
   - **Optional secondary genre**
   - **Number of characters** (2-5)
   - **Character names**
   - **Premise**
3. Click **"Generate Script"**.
4. View and download:
   - The **generated script**
   - **Storyboard images**
   - **Narrated video** (if selected)

---

##  Environment Variables

This project requires an OpenAI API Key to work.  
Store it safely using Streamlit Cloud Secrets if deploying.

---

##  Features

- ✍️ Generate creative, structured 5-page movie scripts
- 🖼️ Generate detailed storyboard illustrations
- 🎥 Create narrated videos from script + storyboards
- 📥 Download scripts, images, and videos easily
- 🎨 Multiple genres and character inputs
- 🌍 Fully deployable on **Streamlit Cloud**

---

##  License

This project is licensed under the MIT License — see the LICENSE file for details.

---
