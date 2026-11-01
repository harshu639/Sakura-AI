# Sakura-AI

A web-based AI chatbot built with HTML, CSS, and JavaScript, powered by the **Google Gemini API**.

Type a message, and Sakura-AI sends it to Gemini and shows the AI-generated reply in a clean chat interface.


## Features

- Simple chat interface for talking to an AI model
- Sends user messages to the Google Gemini API and displays the response
- Loading animation while the AI is generating a reply
- Lightweight: plain HTML, CSS, and JavaScript, with no frameworks or build step

## Tech Stack

| Part | Technology |
|---|---|
| Structure | HTML |
| Styling | CSS |
| Logic | JavaScript |
| AI model | Google Gemini API |

## Project Structure

```
Sakura-AI/
├── index.html     # Page layout and chat interface
├── style.css      # Styling
├── script.js      # Chat logic and Gemini API calls
├── logo.png       # Logo
├── user.png       # User avatar
├── img.svg        # Icon
├── submit.svg     # Send button icon
├── loading.webp   # Loading animation
└── README.md
```

## How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/harshu639/Sakura-AI.git
   cd Sakura-AI
   ```

2. **Get a Gemini API key** for free from [Google AI Studio](https://aistudio.google.com/apikey).

3. **Add your API key** in `script.js` where the API key variable is defined.

   > **Important:** never upload your real API key to GitHub. Add it only on your own computer, and do not commit it.

4. **Open the app.** Double-click `index.html` to open it in your browser, or use the Live Server extension in VS Code.

5. Type a message and press send.

## What I Learned

- Calling an AI model through an API from JavaScript
- Sending requests, handling responses, and showing results in the interface
- Building a responsive chat interface with HTML and CSS
- Keeping API keys safe in a project

## Future Improvements

- Remember the conversation so the AI can answer follow-up questions
- Keep the API key on a small backend server instead of in the browser
- Add a dark mode and a "clear chat" button
- Deploy a live demo with GitHub Pages

## Author

**Harshit Yadav**
B.Tech CSE (AI/ML), COER University

- GitHub: [harshu639](https://github.com/harshu639)
- LinkedIn: [harshit-yadav-](https://www.linkedin.com/in/harshit-yadav-/)
- Email: harshy6396@gmail.com
