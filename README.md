# Simple AI Chat

A clean, responsive web-based chat interface that supports multiple AI providers including Google Gemini and OpenAI GPT models. Also includes an AI Quiz Generator for creating and taking interactive quizzes.

## Features

### Chat Interface (index.html)
- **Multiple AI Providers**: Support for Google Gemini and OpenAI GPT models
- **Clean UI**: LINE-style chat interface with customizable user and AI nicknames
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Persistent Settings**: All configurations are saved locally in your browser
- **Custom Icons**: Support for custom user and AI avatar images
- **Conversation History**: Maintains chat history for context-aware responses

### AI Quiz Generator (quiz.html)
- **Interactive Quiz Generation**: AI-powered quiz creation on any topic
- **Multiple Choice Questions**: 4-option multiple choice format
- **Real-time Feedback**: Immediate scoring and correct answer display
- **Customizable Topics**: Generate quizzes on any subject or theme
- **Progress Tracking**: Visual progress indicator during quiz taking
- **Responsive Design**: Optimized for both desktop and mobile use

## Supported Models

### Google Gemini
- Gemini 2.5 Flash Lite
- Gemini 2.5 Flash

### OpenAI GPT
- GPT-4o mini
- GPT-5 Mini

## Setup

1. Clone or download this repository
2. Place your custom avatar images:
   - `userIcon.png` for user avatar
   - `aiIcon.png` for AI avatar
3. Open the desired application in your web browser:
   - `index.html` for the chat interface
   - `quiz.html` for the quiz generator
4. Click the settings gear icon (⚙️) in the header to configure:
   - AI Provider (Gemini or OpenAI)
   - API Key
   - Model selection
   - Additional settings (system prompt, nicknames for chat interface)

## API Keys

You'll need to obtain API keys from the respective providers:

- **Google Gemini**: Get your API key from [Google AI Studio](https://makersuite.google.com/app/apikey)
- **OpenAI**: Get your API key from [OpenAI Platform](https://platform.openai.com/api-keys)

## Usage

### Chat Interface (index.html)
1. Configure your settings by clicking the gear icon
2. Enter your API key for your chosen provider
3. Customize nicknames, system prompt, and other preferences
4. Start chatting! Type your message and press Enter or click the send button

### Quiz Generator (quiz.html)
1. Configure your AI provider and API key
2. Enter a quiz title and theme/topic
3. Set the number of questions (1-20)
4. Click "クイズを生成" to generate the quiz
5. Answer the multiple-choice questions and receive instant feedback
6. View your final score and create new quizzes

## File Structure

```
simple-ai-chat/
├── index.html          # Chat interface application
├── quiz.html           # Quiz generator application
├── style.css           # Main styling and responsive design
├── quiz.css            # Quiz-specific styling
├── userIcon.png        # User avatar image
├── aiIcon.png          # AI avatar image
├── LICENSE             # MIT License
└── README.md           # This file
```

## Browser Compatibility

- Chrome/Chromium 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## Privacy

- All settings and conversations are stored locally in your browser
- No data is sent to any servers except the AI provider APIs
- API keys are stored securely in localStorage

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## Support

If you encounter any issues or have questions, please create an issue in the repository.