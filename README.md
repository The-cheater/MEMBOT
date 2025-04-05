## Test The Bot -- https://shorturl.at/SgI6m
# Memora AI - Memory Assistant Chatbot![Screenshot 2025-04-05 144036](https://github.com/user-attachments/assets/95bff187-acec-4da5-b74c-e9cd5087b71f)
![Screenshot 2025-04-05 144028](https://github.com/user-attachments/assets/40a3b53d-d715-4179-9231-0bd30d9205be)


Memora is an AI-powered chatbot designed to help users remember important information, events, and tasks through natural conversations and intelligent reminders.

## Features

- 🧠 **Contextual Memory**: Remembers previous conversations and context
- ⏰ **Smart Reminders**: Proactively reminds you of important events
- 📚 **Learning Assistant**: Helps with study and information retention
- 🔄 **Continuous Learning**: Improves with more interactions
- 💬 **Natural Conversations**: Chat like you would with a human

## How It Works

1. **Tell Memora anything** you want to remember
2. **Ask naturally** when you need to recall information
3. **Get reminders** about important events
4. **Review periodically** to strengthen memory

## Configuration

Customize these elements in the code:

```javascript
Chatbot.init({
    chatflowid: "YOUR_FLOWISE_CHATFLOW_ID",
    apiHost: "YOUR_FLOWISE_API_HOST",
    theme: {
        // Customize colors, icons, and behavior here
    }
});
```

## Technical Stack

- Frontend: HTML5, CSS3, JavaScript
- Chat Framework: [Flowise](https://flowiseai.com)
- Hosting: Static file hosting (Netlify/Vercel/GitHub Pages)

## Troubleshooting

**Issue**: Chatbot not loading  
**Solution**: Verify your Flowise credentials and API endpoint

**Issue**: Icons not displaying  
**Solution**: 
- Check SVG file paths
- Ensure files are in `/assest/` directory
- Use absolute URLs if needed

**Issue**: Mobile responsiveness  
**Solution**: Test with different screen sizes in developer tools

## Roadmap

- [ ] Add user accounts
- [ ] Implement calendar integration
- [ ] Add voice input/output
- [ ] Develop mobile app version



### Key Sections Explained:

1. **Features**: Highlights the chatbot's capabilities with emoji icons
2. **How It Works**: Simple 4-step user flow
3. **Setup**: Clear instructions for both users and developers
4. **Configuration**: Shows where to input Flowise credentials
5. **Troubleshooting**: Common issues and solutions
6. **Roadmap**: Future development plans

To use this README:
1. Save as `README.md` in your project root
2. Replace placeholder URLs and information with your actual details
3. Add screenshots if available (update the logo URL)
4. Customize the roadmap and contact information

Would you like me to add any specific technical details or modify any sections?
