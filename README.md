# 🎓 SIYA - STUDY INTEGRATED YOUTH ASSISTANT 🤖

**SIYA AI** is your friendly *study buddy*, designed to make learning easier and more accessible, especially for students with dyslexia. With features like a smart chatbot, real-time web search, and dyslexic-friendly fonts, SIYA is here to help you stay focused and organized! 📚✨

## 🌟 Features

- **Chatbot** 🤖: Ask questions and get quick answers via text or voice.
- **Real-time Search** 🔍: Find up-to-date information instantly.
- **Automation** ⚙️: Control apps and websites with voice commands.
- **Focus Mode** 🎯: Block distractions for better concentration.
- **Alarm Setting** ⏰: Set reminders for important tasks with sound alerts.
- **Image Generation** 🖼️: Create images from text prompts.
- **Dyslexic-Friendly Fonts** 📖: Switch to easier-to-read fonts.
- **Multilingual Support** 🌐: Chat in English, Hindi, and more!

## 🚀 Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/Aryaan-Dev/SIYA-AI.git
   cd SIYA-AI
   ```

2. **Install dependencies**\
   Ensure you have Python 3.6 or later installed. Then run:

   ```bash
   pip install -r requirements.txt
   ```

3. **Set up your .env file**\
   Create a `.env` file in the root folder and add your API keys:

   ```
   CohereAPIKey=your_cohere_api_key
   Username=your_username
   Assistantname=SIYA
   GroqAPIKey=your_groq_api_key
   InputLanguage=en,hi
   AssistantVoice=en-IE-EmilyNeural
   HuggingFaceAPIKey=your_huggingface_api_key
   ```

   *Need keys? Sign up at Cohere, Groq, and Hugging Face.*

**Note**: SIYA AI uses Chrome for speech recognition. Ensure Google Chrome is installed.

## 🎮 How to Use It

Launch SIYA AI with:

```bash
python main.py
```

A GUI window will appear where you can:

- **Talk or Type**: Click the mic button for voice input or type your question.
- **Stay Focused**: Say “Focus mode for 20 minutes” to block distractions.
- **Get Creative**: Try “Generate an image of a sunset.”
- **Switch Fonts**: Check the box for dyslexic-friendly text.

**Examples:**

- “Open Notepad”
- “Set an alarm for 3 PM to finish homework”
- “What’s the capital of France?”

**Feature Details:**

- **Focus Mode**: Say "Focus mode for \[duration\]" to block distracting websites. Check your focus history with "Show focus graph."
- **Alarms**: Say "Set an alarm for \[time\] to \[message\]" for a sound reminder.
- **Image Generation**: Say "Generate an image of \[description\]" to create visuals.

## 🛠️ Requirements

- **Python 3.6+**
- **Internet connection** for speech recognition, text-to-speech, and API features.
- **Google Chrome** for speech recognition via Selenium.
- Packages listed in `requirements.txt`:
  - python-dotenv
  - groq
  - appOpener
  - pywhatkit
  - bs4
  - pillow
  - rich
  - requests
  - keyboard
  - cohere
  - googlesearch-python
  - selenium
  - mtranslate
  - pygame
  - edge-tts
  - PyQt5
  - webdriver-manager
  - pyttsx3
  - matplotlib

## 🤝 Join the Fun

Love SIYA AI? Help us improve it! Fork the repo, add your ideas, and submit a pull request. Check the issues page for tasks to tackle!

## 👥 CODED BY :

- B P ARYAAN [Aryaan-Dev]

---

**Made with ❤️ for students everywhere.** SIYA AI is evolving! Have suggestions or spot bugs? Open an issue on GitHub.
