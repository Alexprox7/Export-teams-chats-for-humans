# 📱 Teams Messages to Text Converter

> 🌐 **[Try it live here!](https://alexprox7.github.io/Export-teams-chats-for-humans/)**

A simple, privacy-focused web tool to convert Microsoft Teams chat exports (`messages.json`) into readable text format. No servers, no data upload - everything runs directly in your browser!

## ✨ Features

- 🔒 **100% Client-side** - Your data never leaves your browser
- 🎯 **Drag & Drop Interface** - Simply drag your `messages.json` file
- 📱 **Responsive Design** - Works on desktop, tablet, and mobile
- 🌍 **Multi-language Support** - Automatically detects your browser language
- ⚡ **Instant Processing** - Fast conversion with progress feedback
- 💾 **Direct Download** - Get your converted `chat_estratta.txt` file immediately
- 🎨 **Modern UI** - Clean, intuitive interface with smooth animations

## 🚀 How to Use

1. **Export your Teams chat**
   - Go to [Microsoft Teams privacy settings](https://privacy.teams.live.com/ui/en/dataexport)
   - Ask for a copy of tour messages (no media)
   - wait
   - Download the tar archive
   - extract the conversations messages.json

2. **Convert the file**
   - Open the [converter tool](https://alexprox7.github.io/Export-teams-chats-for-humans/)
   - Drag and drop your `messages.json` file onto the upload area
   - Or click to browse and select the file

3. **Download the result**
   - Wait for processing to complete
   - Click the download button to get your `chat_estratta.txt` file

## 📄 Output Format

The converted file organizes your messages chronologically with this format:

```
=== Conversazione: [Topic Name] ([Conversation ID]) ===
[2024-01-15 14:30] John Doe: Hello everyone!
[2024-01-15 14:32] Jane Smith: Hi John, how are you?
[2024-01-15 14:35] John Doe: I'm doing great, thanks for asking!

=== Conversazione: [Another Topic] ([Another ID]) ===
[2024-01-16 09:15] Alice: Good morning team!
...
```

## 🌍 Supported Languages

The interface automatically adapts to your browser's language:
- 🇮🇹 **Italian** (Italiano)
- 🇺🇸 **English**
- 🇪🇸 **Spanish** (Español)
- 🇫🇷 **French** (Français)
- 🇩🇪 **German** (Deutsch)

## 🛠️ Technical Details

- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)
- **No Dependencies**: Runs without external libraries
- **File Processing**: Client-side JSON parsing and HTML content extraction
- **Browser Support**: All modern browsers (Chrome, Firefox, Safari, Edge)

## 🔒 Privacy & Security

- ✅ **No data transmission** - Files are processed locally
- ✅ **No server storage** - Nothing is saved or logged
- ✅ **No cookies or tracking** - Complete privacy
- ✅ **Open source** - You can review all the code

## 📝 License

This project is licensed under the MIT License
</p>
