# 🧠 Fitness Chatbot

An interactive **Node.js-based chatbot** designed to assist users with fitness-related queries using pattern-matching and intent recognition. The bot achieves over **95% dataset accuracy** and offers a smooth conversational experience.

## 🚀 Features

- 🤖 Natural text input with intent recognition
- 🔍 Regex-based pattern matching
- 🧘 Responds to common fitness questions (diet, workouts, BMI, etc.)
- ⚡ Fast response with Express.js
- 🖥️ Simple and responsive UI for seamless user interaction

---

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js
- **Frontend:** HTML, CSS, JavaScript (optional for interaction)
- **Regex Patterns:** For user intent mapping
- **Dataset:** Custom JSON file with questions/answers (can be expanded)

---

## 📁 Project Structure
fitness-chatbot/ │ ├── server.js # Express server setup ├── intents.json # Dataset for questions and responses ├── public/ │ ├── index.html # Frontend interface │ └── style.css # Styling for UI └── README.md # Project documentation

yaml
Copy code

---

## ⚙️ How to Run Locally

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/fitness-chatbot.git
cd fitness-chatbot
Install dependencies:

bash
Copy code
npm install
Run the app:

bash
Copy code
node server.js
Open in browser:

Visit: http://localhost:3000

🧠 Sample User Inputs
User Input	Bot Response
"What should I eat after gym?"	"Post-workout meals should include..."
"Tell me a good workout"	"Here's a great home workout routine."
"What’s my BMI?"	"Please enter your weight and height."
📚 Learnings
Regex pattern recognition for chatbot intent classification.

Backend routing and response handling using Express.js.

Real-time interaction simulation without using heavy ML models.

📌 Future Improvements
Integrate NLP library like compromise or Dialogflow.

Add user profile support for personalized responses.

Deploy on platforms like Render or Vercel.

📧 Contact
For any suggestions or collaboration, feel free to connect:

📧 Email: vidushi.jain0903@gmail.com

🌐 LinkedIn: Your LinkedIn


