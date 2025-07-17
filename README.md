# 🤖 Gemini Clone

A modern React.js web application that replicates Google's Gemini AI chat interface, powered by Google's Generative AI API.

![Gemini Clone Demo](https://img.shields.io/badge/Demo-Live-brightgreen)
![React](https://img.shields.io/badge/React-18.x-blue)
![Vite](https://img.shields.io/badge/Vite-Latest-purple)
![Google AI](https://img.shields.io/badge/Google%20AI-Gemini%201.5%20Flash-orange)

## ✨ Features

- 💬 **Real-time AI Chat** - Interactive conversation with Google's Gemini AI model
- 🎨 **Modern UI** - Clean, responsive interface mimicking Gemini's design
- ⚡ **Fast Performance** - Built with Vite for optimal development and build speeds
- 🛡️ **Content Safety** - Integrated safety filters for harassment, hate speech, and inappropriate content
- 📱 **Responsive Design** - Works seamlessly across desktop and mobile devices

## 🚀 Quick Start

### Prerequisites

- Node.js 18+ 
- npm or yarn
- Google AI Studio API key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/adityasahu1109/gemini-clone.git
   cd gemini-clone
   ```
   2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure API Key**
   
   Get your API key from [Google AI Studio](https://makersuite.google.com/app/apikey)
   
   Create a `.env` file in the root directory:
   ```env
   VITE_API_KEY=your_google_ai_studio_api_key_here
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   
   Navigate to `http://localhost:5173` (or the port shown in your terminal)

## 🏗️ Project Structure

```
gemini-clone/
├── src/
│   ├── components/
│   │   ├── Main/           # Main chat interface
│   │   └── Sidebar/        # Navigation sidebar
│   ├── config/
│   │   └── gemini.js       # AI configuration & API setup
│   ├── assets/             # Static assets (icons, images)
│   └── App.jsx             # Root component
├── index.html              # HTML template
├── package.json            # Dependencies & scripts
└── vite.config.js          # Vite configuration
```

## 🛠️ Technology Stack

| Technology | Purpose | Version |
|------------|---------|---------|
| **React.js** | Frontend framework | 18.x |
| **Vite** | Build tool & dev server | Latest |
| **Google Generative AI** | AI model integration | Latest |
| **CSS/SCSS** | Styling | - |

## ⚙️ Configuration

The application uses Google's Gemini 1.5 Flash model with the following configuration:

- **Temperature**: 0.9 (creative responses)
- **Max Output Tokens**: 2048
- **Safety Settings**: Medium+ blocking for harmful content
- **Model**: `gemini-1.5-flash`

Configuration details can be found in `src/config/gemini.js`.

## 🔧 Available Scripts

```bash
# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview

# Lint code
npm run lint
```

## 🌐 Deployment

### Build for Production

```bash
npm run build
```

The `dist/` folder will contain the production-ready files that can be deployed to any static hosting service like:

- Vercel
- Netlify  
- GitHub Pages
- Firebase Hosting

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Steps to Contribute

1. **Fork the Repository**
   ```bash
   git fork https://github.com/adityasahu1109/gemini-clone.git
   ```

2. **Create a Feature Branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```

3. **Make Your Changes**
   - Follow the existing code style
   - Add comments for complex logic
   - Test your changes thoroughly

4. **Commit Your Changes**
   ```bash
   git commit -m "Add: Amazing new feature"
   ```

5. **Push to Your Branch**
   ```bash
   git push origin feature/amazing-feature
   ```

6. **Open a Pull Request**

### Code Style Guidelines

- Use functional components with hooks
- Follow React best practices
- Maintain consistent indentation
- Add meaningful variable names
- Include JSDoc comments for functions

## 🐛 Known Issues

- None currently reported

## 🔮 Future Enhancements

- [ ] Dark mode toggle
- [ ] Export chat conversations
- [ ] Voice input support
- [ ] Multiple AI model selection
- [ ] Custom prompt templates
- [ ] Chat search functionality

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://choosealicense.com/licenses/mit/) file for details.

## 🙏 Acknowledgments

- **Google AI Studio** for providing the Generative AI API
- **Google Gemini** for the original design inspiration
- **React Team** for the amazing framework
- **Vite** for the lightning-fast build tool

## 📞 Support

If you encounter any issues or have questions:

1. Check the [Issues](https://github.com/adityasahu1109/gemini-clone/issues) page
2. Create a new issue with detailed information
3. Reach out to the maintainers

---

<div align="center">
  <p>Built with ❤️ by <a href="https://github.com/adityasahu1109">Aditya Sahu</a></p>
  <p>⭐ Star this repository if you found it helpful!</p>
</div>
