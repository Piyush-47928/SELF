🤖** Friday A.I – Voice Assistant in Python**

Friday A.I is a Python-based voice assistant that can listen to your voice commands, respond using speech, open websites, tell the current time, perform Google searches, and even capture photos using your webcam.

This project is ideal for beginners in Python, AI, and voice-based applications, especially students working on mini-projects or learning automation.

✨** Features**

  🎤 Voice input using microphone
  
  🔊 Text-to-speech response (Windows SAPI)
  
  🌐 Open websites via voice commands
  
  🔍 Search queries using voice
  
  ⏰ Tell current system time
  
  📷 Capture photos using webcam
  
  🧠 Simple command-processing logic
  
🛠️ **Technologies & Libraries Used**
  
  Python 3
  
  win32com.client – Text-to-Speech (Windows only)
  
  speech_recognition – Speech to text
  
  pygame & pygame.camera – Webcam access
  
  webbrowser – Open websites
  
  datetime – Time handling
  
  os – System commands

📁 **Project Structure**
Friday-AI/
│
├── friday.py          # Main Python script
├── README.md          # Project documentation
└── requirements.txt   # Required libraries (recommended)

⚙️** Installation & Setup**
  1️⃣ Clone the Repository
  git clone https://github.com/your-username/Friday-AI.git
  cd Friday-AI
  
  2️⃣ Install Required Libraries
  pip install pywin32 SpeechRecognition pygame pyaudio
  

⚠️** Note:**

  This project works only on Windows because it uses SAPI.SpVoice.
  
  Make sure your microphone and webcam are working properly.
  
  For pyaudio, you may need a precompiled wheel on Windows.

▶️ **How to Run**
  python friday.py
  
  Once started, Friday A.I will:
  
  Greet you
  
  Ask for your name
  
  Listen continuously for voice commands

🗣️ **Supported Voice Commands**
  **Command	Action**
    "What's the time"	Speaks current time
    "Open the site google"	Opens google.com
    "Please search machine learning"	Searches query
    "Take a photo"	Captures webcam image
    "Goodbye"	Ends interaction
    
  **📸 Webcam Feature**
    Uses your default camera
    Saves image with the name you speak
    Resolution: 640 × 480

  **🚧 Known Limitations**

    Windows-only (due to win32com)
    No error handling for background noise
    Camera filename bug needs minor fix
    Limited command vocabulary

**🔮 Future Improvements**

    Add ChatGPT / OpenAI API integration 
    Improve natural language understanding
    Add GUI using Tkinter or PyQt
    Cross-platform support
    Command history & logging
    
👨‍💻** Author**
  Piyush Sharma
  B.Tech Student | Robotics | AI | Embedded Systems
