# IRON MAN AI
![image alt](https://github.com/Mr-Nilarnab/IRON-MAN-AI/blob/main/Screenshot%202025-11-05%20083050.png?raw=true)

Creator= Mr-Nilarnab

## Overview
**IRON MAN AI** is a web-based, voice-controlled personal assistant inspired by Iron Man's AI system. It can perform a variety of tasks such as opening websites, fetching information from Wikipedia, and responding with natural speech. Jarvis provides a startup sequence, greeting messages, and real-time voice command processing to make user interactions smooth and intuitive.

---

## Features

### **1. Voice Command Control**
- Uses the **Web Speech API** (`SpeechRecognition`) for recognizing spoken commands.
- Supports multiple pre-defined commands like:
  - "Open Google"
  - "Open YouTube"
  - "Open ChatGPT"
  - "Open GitHub", "Open Facebook", "Open Instagram", "Open LinkedIn"
  - "Open Stack Overflow", "Open Reddit", "Open Amazon", "Open Spotify", "Open Maps"
- Automatically opens the corresponding website when a recognized command is spoken.
- Continuous listening mode can be enabled for seamless interaction.

### **2. Wikipedia Search Integration**
- Performs **voice-activated Wikipedia searches**.
- Fetches summaries of the queried topic using **Wikipedia's REST API**.
- Handles ambiguous queries gracefully by providing multiple results or opening the main Wikipedia search page.
- Displays results in a readable format on the webpage.
- Reads out the result using text-to-speech.

### **3. Startup Sequence**
- Provides a realistic AI initialization sequence, including:
  - System checks
  - Core processor calibration
  - Network connectivity verification
- Greets the user based on the time of day (Good Morning/Afternoon/Evening)
- Announces the current system time
- Confirms that Jarvis is online and ready for commands.

### **4. Speech Output**
- Uses **Text-to-Speech (TTS)** to read messages aloud.
- Provides audio feedback for commands, greetings, search results, and error messages.

### **5. Error Handling**
- Gracefully handles cases when:
  - A command is unrecognized
  - Wikipedia search fails or no results are found
  - The system encounters fetch errors
 
### **6. Wikipedia Search Integration**

Voice-Activated Search: Users can ask Jarvis to search Wikipedia by speaking commands like:

“Search Wikipedia for Iron Man”

“Search Wikipedia for Artificial Intelligence”

Summary Retrieval: Jarvis fetches concise article summaries from Wikipedia’s REST API and reads them aloud, displaying the result on-screen.

Handles Ambiguity: If a topic has multiple meanings, Jarvis notifies the user and can open the main Wikipedia page for further exploration.

Why Wikipedia?

Comprehensive Knowledge Base: Wikipedia has millions of articles across countless topics.

Free and Open Access: Allows easy integration without licensing restrictions.

Structured API: Provides summaries and links that are perfect for voice-based assistants.

Lightweight Summaries for TTS: Short summaries make spoken responses fast and clear.

---

## Technology Stack
- **Frontend:** HTML, CSS, JavaScript
- **APIs Used:**
  - [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API) for voice recognition
  - [Wikipedia REST API](https://en.wikipedia.org/api/rest_v1/) for fetching page summaries
- **Hosting:** Can be hosted on any static server or locally

---

## Usage
1. Open the webpage in a modern browser (Chrome, Edge, or Firefox).  
2. Allow microphone access when prompted.  
3. Wait for the startup sequence and greeting.  
4. Speak one of the supported commands, for example:
   - “Open YouTube”
   - “Search Wikipedia for Iron Man”
5. Jarvis will respond with both speech and visible output on the screen.  
6. Commands are continuously listened for unless stopped manually.

---

## Creator
**Developer:** [NILARNAB]  
**Inspired by:** Iron Man’s AI assistant, J.A.R.V.I.S.  
**Date:** [5/11/25]

---

## Future Improvements
- Add **customizable voice commands**.
- Support **more search engines and services**.
- Implement **conversation-style interactions** with memory context.
- Add **GUI for managing commands and favorite sites**.
- Include **multi-language support** for speech recognition and TTS.

---

## License
This project is open-source and available under the **MIT License**. Feel free to modify and distribute.

---

## Example Commands
| Command | Action |
|---------|--------|
| Open Google | Opens Google in a new tab |
| Open YouTube | Opens YouTube in a new tab |
| Search Wikipedia for *topic* | Fetches summary of topic from Wikipedia |
| Open ChatGPT | Opens ChatGPT in a new tab |

---

## Screenshots
*Include screenshots of the AI assistant webpage, startup messages, and Wikipedia search results here if desired.*

---

## Contact
- LINK=  "https://github.com/Mr-Nilarnab?tab=overview&from=2025-11-01&to=2025-11-05"
- GitHub: [Mr-Nilarnab]  
