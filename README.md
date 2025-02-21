# Multi-LLM Chatbot 🤖

A powerful chatbot interface that integrates multiple Language Learning Models (LLMs) including AI21, OpenAI, Claude, and local models. Built with Streamlit, this application provides a unified interface to interact with different AI models.

![Chatbot Interface](https://i.postimg.cc/fyCpbmFf/1.png)
![Chatbot Interface](https://i.postimg.cc/Bb4RsMhv/2.png)

## 🌟 Features

- **Multiple LLM Support**:
  - AI21 Labs (Jamba 1.5)
  - OpenAI (GPT-4, GPT-3.5)
  - Claude (Opus, Sonnet, Haiku)
  - Local Models (DeepSeek, TinyLlama)

- **User-Friendly Interface**:
  - Clean and intuitive chat interface
  - Easy model switching
  - Conversation history
  - Real-time responses

- **Persistent Storage**:
  - Saves chat histories
  - Maintains API configurations
  - Preserves user preferences

## 🚀 Quick Start

### Prerequisites

```bash
# Python 3.9 or higher required
python --version
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/multi-llm-chatbot.git
cd multi-llm-chatbot
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up environment variables:
```bash
# Create .env file
AI21_API_KEY=your_ai21_key
OPENAI_API_KEY=your_openai_key
CLAUDE_API_KEY=your_claude_key
```

4. Run the application:
```bash
streamlit run app.py
```

## 💻 Usage

1. **Select Model**: Choose your preferred AI model from the dropdown menu
2. **Start Chatting**: Type your message in the chat input
3. **View History**: Access previous conversations from the sidebar
4. **Configure APIs**: Set up API keys in the settings panel

## 🛠️ System Requirements

- **Minimum**:
  - CPU: 2 cores
  - RAM: 8GB
  - Storage: 10GB

- **Recommended**:
  - CPU: 4+ cores
  - RAM: 16GB+
  - Storage: 20GB+
  - GPU: For local models (optional)

## 🔧 Configuration

The application can be configured through various settings:

```python
# Model configurations
MODEL_CONFIGS = {
    "AI21 Labs": {
        "models": ["jamba-1.5-large", "jamba-1.5-mini"],
        "client_type": "ai21",
    },
    "OpenAI": {
        "models": ["gpt-4", "gpt-3.5-turbo"],
        "client_type": "openai",
    },
    # ... other configurations
}
```

## 📁 Project Structure

```
multi-llm-chatbot/
├── app.py              # Main application file
├── requirements.txt    # Python dependencies
├── conversations.json  # Stored conversations
├── .env               # Environment variables
└── README.md          # Documentation
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📋 API Keys Setup

### AI21 Labs
1. Visit [AI21 Labs](https://www.ai21.com/)
2. Sign up and access your API key
3. Add to environment variables

### OpenAI
1. Visit [OpenAI Platform](https://platform.openai.com/)
2. Create an account and generate API key
3. Add to environment variables

### Claude
1. Visit [Anthropic](https://www.anthropic.com/)
2. Sign up for API access
3. Add key to environment variables

## 🔍 Troubleshooting

Common issues and solutions:

1. **API Connection Issues**:
   - Verify API keys
   - Check internet connection
   - Ensure proper environment variables

2. **Memory Issues**:
   - Close unnecessary applications
   - Reduce model size
   - Clear browser cache

3. **Model Loading Errors**:
   - Update dependencies
   - Check system requirements
   - Verify model availability

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- AI21 Labs for their Jamba models
- OpenAI for GPT models
- Anthropic for Claude
- Streamlit for the wonderful framework

## 📞 Support

For support, please:
1. Check existing issues
2. Create a new issue
3. Reach out to contributors

## 🔄 Updates

- Latest version: 1.0.0
- Last updated: February 2024
- Release notes available in [CHANGELOG.md](CHANGELOG.md)

---
Made with ❤️ by [Uzair Abbasi]
