# Simple AI Chat

A clean, responsive web-based chat interface that supports multiple AI providers including Google Gemini and OpenAI GPT models.

## Features

- **Multiple AI Providers**: Support for Google Gemini and OpenAI GPT models
- **Clean UI**: LINE-style chat interface with customizable user and AI nicknames
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Persistent Settings**: All configurations are saved locally in your browser
- **Custom Icons**: Support for custom user and AI avatar images
- **Conversation History**: Maintains chat history for context-aware responses

## Supported Models

### Google Gemini
- Gemini 2.5 Flash Lite (default)
- Gemini 2.5 Flash
- Gemini Pro
- Gemini 1.5 Pro

### OpenAI GPT
- GPT-3.5 Turbo
- GPT-4
- GPT-4 Turbo
- GPT-4o

## Setup

1. Clone or download this repository
2. Place your custom avatar images:
   - `userIcon.png` for user avatar
   - `aiIcon.png` for AI avatar
3. Open `index.html` in your web browser
4. Click the settings gear icon (⚙️) in the header to configure:
   - AI Provider (Gemini or OpenAI)
   - API Key
   - Model selection
   - System prompt
   - Temperature setting
   - User and AI nicknames

## API Keys

You'll need to obtain API keys from the respective providers:

- **Google Gemini**: Get your API key from [Google AI Studio](https://makersuite.google.com/app/apikey)
- **OpenAI**: Get your API key from [OpenAI Platform](https://platform.openai.com/api-keys)

## Usage

1. Configure your settings by clicking the gear icon
2. Enter your API key for your chosen provider
3. Customize nicknames and other preferences
4. Start chatting! Type your message and press Enter or click the send button

## File Structure

```
simple-ai-chat/
├── index.html          # Main application file
├── style.css           # Styling and responsive design
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