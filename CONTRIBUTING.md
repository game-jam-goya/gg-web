# 🤝 Contributing to Game Jam GOYA

First off, thank you for considering contributing to Game Jam GOYA! It's people like you that make this encyclopedia so valuable for game developers worldwide.

## 📋 Table of Contents
- [How Can I Contribute?](#how-can-i-contribute)
- [Adding New Tools](#adding-new-tools)
- [Adding Code Snippets](#adding-code-snippets)
- [Adding Assets](#adding-assets)
- [Adding Learning Resources](#adding-learning-resources)
- [Adding Problems & Solutions](#adding-problems--solutions)
- [Style Guidelines](#style-guidelines)
- [Testing](#testing)

---

## 🎯 How Can I Contribute?

There are many ways you can contribute:

1. **Add new resources**: Tools, assets, tutorials, etc.
2. **Improve existing content**: Better descriptions, updated links
3. **Add code snippets**: Share your useful GDScript code
4. **Report issues**: Found a broken link? Let us know!
5. **Suggest features**: Have ideas for improvements?
6. **Translate content**: Help make it accessible to more developers
7. **Fix bugs**: Found something not working? Submit a fix!

---

## 🛠️ Adding New Tools

To add a new tool to the Tools section:

1. Open `index.html`
2. Find the `toolsData` array in the JavaScript section
3. Add your tool following this format:

```javascript
{ 
    name: "Tool Name", 
    description: "Brief description of what it does", 
    category: "coding", // Options: coding, debug, project, art, sound, ai, version
    link: "https://tool-website.com/", 
    icon: "fa-icon-name" // Font Awesome icon (without 'fas' prefix)
}
```

**Example:**
```javascript
{ 
    name: "New Game Engine", 
    description: "Amazing 2D game engine for rapid development", 
    category: "coding", 
    link: "https://newengine.com/", 
    icon: "fa-gamepad"
}
```

---

## 💻 Adding Code Snippets

To add a new GDScript code snippet:

1. Open `index.html`
2. Find the `gdscriptData` array
3. Add your code following this format:

```javascript
{
    title: "Feature Name",
    description: "Brief description of what the code does",
    category: "movement", // Options: movement, ai, inventory, physics, ui, save, camera
    code: `extends Node2D

func your_function():
    # Your code here
    pass`
}
```

**Important:**
- Test your code in Godot before submitting
- Use Godot 4.x syntax
- Include comments for clarity
- Keep it simple and focused on one feature

---

## 🎨 Adding Assets

To add new asset resources:

1. Open `index.html`
2. Find the `assetsData` array
3. Add your resource following this format:

```javascript
{ 
    name: "Asset Name", 
    description: "What kind of assets are available", 
    category: "characters", // Options: characters, ui, sfx, music, sprites, models, tilesets, vfx
    link: "https://asset-site.com/", 
    icon: "fa-icon-name"
}
```

---

## 📚 Adding Learning Resources

To add tutorials, courses, or documentation:

1. Open `index.html`
2. Find the `learningData` array
3. Add your resource:

```javascript
{ 
    name: "Resource Name", 
    description: "What you can learn from this", 
    category: "youtube", // Options: youtube, docs, courses, discord, opensource
    link: "https://resource-link.com/", 
    icon: "fa-youtube"
}
```

---

## 🐛 Adding Problems & Solutions

Help others by sharing solutions to common problems:

1. Open `index.html`
2. Find the `problemsData` array
3. Add your problem/solution:

```javascript
{
    title: "Problem Title",
    problem: "وصف المشكلة بالعربية", // Arabic description
    cause: "Why this problem happens",
    solution: "1. Step one\n2. Step two\n3. Step three",
    code: `# Optional code solution
extends Node2D
# Solution code here` // Leave empty string if no code needed
}
```

---

## 🎨 Style Guidelines

### Code Style
- Use clear, descriptive names
- Add comments for complex logic
- Keep functions focused and small
- Follow GDScript best practices

### Content Style
- Be concise but informative
- Use proper grammar and spelling
- Keep descriptions under 100 characters when possible
- Include both English and Arabic where appropriate

### Link Guidelines
- Always link to official sources when possible
- Verify links work before submitting
- Prefer direct download/resource pages over homepages
- Include HTTPS links only

---

## ✅ Testing

Before submitting your contribution:

1. **Test locally**: Open `index.html` in a browser
2. **Check functionality**: 
   - Search works with your new content
   - Filters work correctly
   - Links are clickable and correct
   - No JavaScript errors in console
3. **Test responsiveness**: Check on mobile view
4. **Verify content**: 
   - Descriptions are accurate
   - Code compiles (for snippets)
   - Links are active

---

## 📝 Submission Process

### For Small Changes (1-5 items):
1. Fork the repository
2. Make your changes to `index.html`
3. Test thoroughly
4. Create a pull request with:
   - Clear title
   - List of what you added/changed
   - Why it's valuable

### For Large Changes (6+ items):
1. Open an issue first to discuss
2. Get feedback from maintainers
3. Make changes after approval
4. Submit pull request

---

## 🌍 Translation Contributions

Want to help translate?

**Currently needed:**
- More Arabic translations for technical terms
- Additional language support

**How to help:**
1. Identify content needing translation
2. Ensure accuracy and proper context
3. Maintain technical terminology appropriately
4. Submit via pull request

---

## 🎖️ Recognition

All contributors will be:
- Listed in the contributors section (if added)
- Acknowledged in release notes
- Appreciated by the community! 🙏

---

## ❓ Questions?

- Open an issue for questions
- Tag with "question" label
- We'll respond as soon as possible

---

## 🚫 What NOT to Include

Please don't add:
- Pirated or illegal content
- Broken or spam links
- Untested code
- Offensive or inappropriate content
- Commercial promotions without value
- Duplicate resources already listed

---

## 📜 Code of Conduct

- Be respectful and inclusive
- Help others learn
- Accept constructive criticism
- Focus on what's best for the community

---

Thank you for contributing to Game Jam GOYA! Together, we're helping developers worldwide create amazing games in 48 hours! 🎮🚀

**Happy Contributing!**
