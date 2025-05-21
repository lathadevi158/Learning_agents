# 🎬 Conversational Movie Recommendation Chatbot

This project is a **conversational chatbot application** built using `LangChain`, `Azure OpenAI`, and `ipywidgets`. The chatbot learns user preferences over time based on past conversations and suggests movies tailored to genres discussed by the user.

---

## 📌 Features

- 💬 **Conversational Interface** via `ipywidgets`
- 🧠 **Memory-Powered Context**: Remembers past conversation history
- 🎯 **Genre Detection** from user messages (e.g., Sci-Fi, Horror, Drama, etc.)
- 🎥 **Movie Recommendations** based on preferred genres
- ☁️ **Powered by Azure OpenAI** for reliable, high-quality responses

---

## 🚀 How It Works

1. The user interacts with the chatbot through a text input UI.
2. Each message is stored and analyzed for genre-related keywords.
3. Over time, the chatbot "learns" user preferences.
4. If a user asks for a movie recommendation, the chatbot suggests titles aligned with learned preferences.

---

## 🧰 Technologies Used

- **LangChain** for prompt chaining and memory
- **Azure OpenAI (ChatGPT)** as the LLM backend
- **ipywidgets** for building interactive UI in Jupyter Notebooks
- **Python** for logic and glue code

---

## 📁 Folder Structure

📦movie-recommendation-chatbot/
├── app.ipynb # Main Jupyter Notebook UI
├── global_config.json # API and Azure deployment credentials
├── requirements.txt # Python dependencies
└── README.md # Project documentation



---



🧑‍💻 Author
Marpally Latha Devi
Prompt Engineer | Generative AI Enthusiast | Python Developer

🪪 License
This project is licensed under the MIT License.




