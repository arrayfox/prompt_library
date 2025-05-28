# 🚀 AI Prompt Library

A modern, searchable prompt library built for GitHub Pages. Perfect for organizing and sharing your AI prompts with powerful search and filtering capabilities.

## ✨ Features

- **Real-time Search** - Search across titles, descriptions, content, and tags
- **Smart Filtering** - Filter by category, tags, or both
- **Easy Organization** - Sort by date or alphabetically
- **One-Click Copy** - Copy prompts to clipboard instantly
- **Responsive Design** - Works perfectly on desktop and mobile
- **Daily Updates** - Simple JSON file editing for hassle-free updates

## 🚀 Quick Start

### 1. GitHub Pages Setup
1. Fork or download this repository
2. Enable GitHub Pages in repository settings
3. Your site will be live at: `https://yourusername.github.io/repository-name`

### 2. Local Development
```bash
# Clone repository
git clone https://github.com/yourusername/ai-prompt-library.git
cd ai-prompt-library

# Open with VS Code and install Live Server extension
# Right-click index.html → "Open with Live Server"
```

## 📝 Adding Prompts

Edit the `prompts.json` file to add your prompts:

```json
{
  "title": "Your Prompt Title",
  "category": "Writing",
  "description": "Brief description of what this prompt does",
  "content": "The actual prompt text with [PLACEHOLDERS] for user input",
  "tags": ["creative", "writing", "storytelling"],
  "date": "2024-05-28"
}
```

### Daily Update Workflow
1. Open `prompts.json` in your favorite editor
2. Add new prompt objects to the array
3. Save and commit changes
4. Push to GitHub - your site updates automatically!

## 📁 File Structure
```
ai-prompt-library/
├── index.html          # Main website file
├── prompts.json        # Your prompt data
└── README.md          # This file
```

## 🎨 Customization

### Change Colors
Edit the CSS gradient variables in `index.html`:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Update Branding
Modify the header section:
```html
<h1>🚀 Your Library Name</h1>
<p>Your custom description</p>
```

## 💡 Tips

- **Consistent Dating**: Use YYYY-MM-DD format for proper sorting
- **Good Tags**: Use 3-5 relevant, searchable keywords per prompt
- **Placeholders**: Use [BRACKETS] for user-replaceable parts
- **JSON Validation**: Use VS Code or jsonlint.com to check syntax

## 🔧 Local Development Notes

- **CORS Issues**: Use VS Code Live Server extension for local testing
- **Fallback Mode**: Opens directly in browser with sample data if needed
- **JSON Loading**: External JSON files work perfectly on GitHub Pages

## 📱 Browser Support

Works on all modern browsers including:
- Chrome, Firefox, Safari, Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

1. Fork the repository
2. Add your prompts to `prompts.json`
3. Submit a pull request

## 📄 License

MIT License - feel free to use this template for your own prompt libraries!

---

**Happy Prompting!** 🎯