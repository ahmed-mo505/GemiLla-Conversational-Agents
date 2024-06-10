# GemiLla-Conversational-Agents

# 💬 GemiLla: Conversational Agents

GemiLla is a Streamlit-based application that allows users to engage in interactive conversations with two AI models: Gemini from Google and LLaMA from Meta. The application supports multiple topics and rounds of conversation, providing a dynamic and engaging user experience.

## ✨ Features

- 🎲 **Multi-Round Conversations**: Choose the number of conversation rounds.
- 📚 **Customizable Topics**: Select from predefined topics or add your custom prompt.
- 📝 **Session History**: View the entire conversation history during the session.
- 💻 **Interactive UI**: User-friendly interface with visual indicators for conversation rounds.

## 📦 Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/ahmed-mo505/GemiLla-Conversational-Agents.git
   cd GemiLla
   ```

2. Create a virtual environment and activate it:

   ```sh
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```

3. Install the required dependencies:

   ```sh
   pip install -r requirements.txt
   ```

## 🔧 Configuration

1. **API Keys**: Replace the placeholders with your actual API keys in the `app.py` file.

   ```python
   LLAMA_API_KEY = "YOUR_LLAMA_API_KEY"
   GEMINI_API_KEY = "YOUR_GEMINI_API_KEY"
   ```

## 🚀 Running the Application

Start the Streamlit application by running:

```sh
streamlit run app.py
```

📖 Usage
1-Select a Topic: Choose a topic from the dropdown menu.
2-Set Rounds: Select the number of conversation rounds.
3-Custom Prompt: (Optional) Add a custom prompt to start the conversation.
4-Start Conversation: Click the "Start Conversation" button to begin.
