<<<<<<< Updated upstream
# socket-application
=======
# 💬 ChatRoom - Modern Socket.IO Chat Application

A beautiful, real-time chat application built with Socket.IO, Express, and modern web technologies.

## ✨ Features

- **Real-time messaging** - Instant message delivery using WebSockets
- **Advanced AI Chat Bot** - Intelligent AI assistant with multiple AI service integrations 🤖
- **Modern UI/UX** - Beautiful gradient design with smooth animations
- **User management** - Join with custom usernames
- **Typing indicators** - See when others are typing (including AI)
- **Online user count** - Track how many users are connected
- **Connection status** - Visual indicator of connection state
- **Responsive design** - Works on desktop and mobile devices
- **Message timestamps** - See when messages were sent
- **Auto-scrolling** - Automatically scroll to latest messages
- **Emoji support** - Send emojis in your messages
- **AI Commands** - Special commands to interact with the AI bot
- **Smart AI responses** - Context-aware AI with OpenAI, Gemini, and Hugging Face support
- **Conversation memory** - AI remembers context within conversations
- **Fallback system** - Multiple AI services with automatic fallback

## 🚀 Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn package manager

### Installation

1. Clone or download this repository
2. Navigate to the project directory:
   ```bash
   cd socket-application
   ```

3. Install dependencies:
   ```bash
   npm install
   ```


### Running the Application

1. **Development mode** (with auto-restart):
   ```bash
   npm run dev
   ```

2. **Production mode**:
   ```bash
   npm start
   ```

3. Open your browser and go to `http://localhost:3000`

4. Enter your name and start chatting with other users and the AI bot!

## 🎯 How to Use

1. **Join the Chat**: Enter your name when prompted
2. **Send Messages**: Type your message and press Enter or click Send
3. **Chat with AI Bot**: The AI will automatically respond to questions and mentions
4. **Use AI Commands**:
   - `/ai [question]` - Ask the AI directly
   - `@ai [question]` - Mention the AI
   - `/help` - Show available commands
   - `/time` - Get current time
   - `/date` - Get current date
   - Ask for a "joke" - Get a random joke
5. **See Typing Indicators**: Watch when others (and AI) are typing
6. **Monitor Connection**: Check the connection status in the top-right
7. **View Online Users**: See how many users are currently online

## 🛠️ Technical Details

### Built With

- **Backend**: Node.js + Express.js
- **Real-time Communication**: Socket.IO
- **Frontend**: Vanilla JavaScript + Modern CSS
- **Styling**: Custom CSS with gradients and animations
- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Inter)

### Project Structure

```
socket-application/
├── index.html          # Main chat interface
├── index.js           # Express server with Socket.IO
├── package.json       # Project dependencies and scripts
├── README.md          # Documentation
├── .gitignore         # Git ignore rules
└── public/           # Static assets (if any)
```

### Socket Events

- `join` - User joins the chat with username
- `chat message` - Send/receive chat messages
- `typing` / `stop typing` - Typing indicators
- `user joined` / `user left` - User connection events
- `online users` - Update online user count

## 🎨 Customization

### Changing Colors

Edit the CSS custom properties in `index.html`:

```css
:root {
  --primary-gradient: linear-gradient(135deg, #4f46e5, #7c3aed);
  --background-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

### Adding Features

The application is built with extensibility in mind. You can easily add:

- Message history persistence
- Private messaging
- File/image sharing
- User avatars
- Chat rooms/channels
- Message reactions
- User authentication

## 📱 Mobile Support

The application is fully responsive and works great on:
- Desktop browsers
- Tablets
- Mobile phones

## 🔧 Configuration

### Environment Variables

- `PORT` - Server port (default: 3000)
- `OPENAI_API_KEY` - Optional: OpenAI API key for advanced AI responses

### AI Configuration

The chat includes an advanced AI bot with multiple service integrations:

#### **AI Capabilities:**
- **Context-aware conversations** - Remembers chat history
- **Multiple AI services** - OpenAI GPT, Google Gemini, Hugging Face
- **Automatic fallback** - If one service fails, tries others
- **Smart response logic** - Responds to questions, mentions, commands
- **Local responses** - Works without any API keys

#### **Supported AI Services:**

1. **OpenAI GPT-3.5/4** (Recommended)
   - Get API key: [OpenAI Platform](https://platform.openai.com/api-keys)
   - Set: `OPENAI_API_KEY=your_key_here`

2. **Google Gemini** (Free tier available)
   - Get API key: [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Set: `GEMINI_API_KEY=your_key_here`

3. **Hugging Face** (Free)
   - Get API key: [Hugging Face Tokens](https://huggingface.co/settings/tokens)
   - Set: `HUGGINGFACE_API_KEY=your_key_here`

#### **Setup Instructions:**
1. Copy `.env.example` to `.env`
2. Add your API keys (optional - app works without them)
3. Restart the server
4. The AI will automatically use the best available service

#### **AI Features:**
- **Conversation memory** - Tracks last 10 messages per user
- **Context cleanup** - Automatically cleans old conversations
- **Error handling** - Graceful fallback on API failures
- **Smart categorization** - Recognizes tech, business, science topics
- **Command system** - Special commands for specific functions

### Server Configuration

Edit `index.js` to customize:
- CORS settings
- Rate limiting
- Message validation
- User limits

## 🤝 Contributing

Feel free to contribute to this project by:
1. Adding new features
2. Improving the UI/UX
3. Fixing bugs
4. Adding documentation

## 📄 License

This project is licensed under the ISC License.

## 🎉 Enjoy Chatting!

Start the server and invite your friends to chat in real-time! 🚀
>>>>>>> Stashed changes
# socket-application-main-main
# socket-application-main-main
# socket-application-main-main
