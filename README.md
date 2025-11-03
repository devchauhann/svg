# 🎨 SVG Icon Showcase

<div align="center">

![SVG Icon Showcase Banner](https://via.placeholder.com/800x200/667eea/ffffff?text=SVG+Icon+Showcase)

**A modern, responsive web application for browsing, customizing, and managing SVG icons**

[![Live Demo](https://img.shields.io/badge/Live-Demo-blue?style=for-the-badge)](https://devchauhann.github.io/svg/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/devchauhann/svg-icon-showcase?style=for-the-badge)](https://github.com/devchauhann/svg-icon-showcase/stargazers)

</div>

## ✨ Features

### 🎯 **Core Functionality**
- **🔍 Smart Search**: Real-time icon search with instant filtering
- **📂 Category Browsing**: Organized icons by categories (Interface, Business, Media, Arrows, Development, Social, General, Health)
- **🎨 Live Customization**: Real-time color and size adjustments
- **📋 One-Click Copy**: Instant SVG code copying to clipboard
- **❤️ Favorites System**: Save and manage your favorite icons with persistent storage

### 📱 **Mobile-First Design**
- **📱 Responsive Layout**: Seamless experience across all devices
- **🍔 Mobile Menu**: Feature-rich mobile navigation with smooth animations
- **👆 Touch-Friendly**: Optimized for touch interactions
- **🌙 Theme Support**: Beautiful light and dark mode themes

### 🚀 **Advanced Features**
- **⚡ Performance Optimized**: Lazy loading and efficient rendering
- **🎭 Modal Preview**: Detailed icon preview with live editing
- **💾 Local Storage**: Persistent favorites and preferences
- **🎨 Theme Switching**: Smooth light/dark mode transitions
- **📊 Live Statistics**: Real-time icon count and category information

## 🖼️ Screenshots

<div align="center">

### Desktop View
![Desktop Screenshot]<img src="modals/desktopview.jpg" alt="Mobile Menu" width="900"/>

### Mobile View & Features
<div style="display: flex; gap: 20px; justify-content: center;">
<img src="modals/mobileview.jpg" alt="Mobile View" width="250"/>
<img src="modals/menu.jpg" alt="Mobile Menu" width="250"/>
</div>

</div>

## 🚀 Quick Start

### 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/devchauhann/svg-icon-showcase.git
   cd svg-icon-showcase
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your preferred browser
   open index.html
   # OR serve with a local server
   python -m http.server 8000
   ```

3. **That's it!** 🎉 No build process required - it's a pure HTML/CSS/JS application.

### 🔧 Configuration

The application uses a `data.json` file to load icons. You can customize it by:

```json
{
  "icons": [
    {
      "name": "your-icon-name",
      "category": "interface",
      "svg": "<svg>...</svg>"
    }
  ]
}
```

## 🛠️ Technology Stack

<div align="center">

| Technology | Usage | Description |
|------------|-------|-------------|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) | Structure | Semantic markup and accessibility |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) | Styling | Modern CSS with custom properties and Grid/Flexbox |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) | Functionality | Vanilla JS for performance and simplicity |
| ![JSON](https://img.shields.io/badge/JSON-000000?style=flat&logo=json&logoColor=white) | Data | Icon database and configuration |

</div>

## 📱 User Interface

### 🎨 **Icon Cards**
- **Heart Button**: Add/remove from favorites (top-right corner)
- **Copy Button**: Instantly copy SVG code
- **Favorite Action**: Quick favorite toggle
- **Click to Preview**: Open detailed modal view

### 🔍 **Search & Filter**
- **Real-time Search**: Type to filter icons instantly
- **Category Tabs**: Browse by icon categories
- **Smart Filtering**: Combined search and category filtering

### 📲 **Mobile Menu**
- **Categories**: Quick access to all icon categories
- **My Favorites**: View and manage saved icons
- **Tools**: Download pack, theme switching
- **About**: Project information and links

## 🎯 Key Features Breakdown

### ❤️ **Favorites System**
```javascript
// Persistent favorites with localStorage
- Add/remove icons from favorites
- View favorites in dedicated section
- Sync across all UI elements
- Persistent storage between sessions
```

### 📋 **Copy Functionality**
```javascript
// One-click SVG copying
- Direct SVG code copying
- Visual feedback with animations
- Fallback error handling
- Success/failure notifications
```

### 🎨 **Customization**
```javascript
// Live icon customization
- Real-time color changes
- Size adjustment slider
- Preview before copying
- Theme-aware defaults
```

## 🌐 Browser Support

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 60+ | ✅ Fully Supported |
| Firefox | 55+ | ✅ Fully Supported |
| Safari | 12+ | ✅ Fully Supported |
| Edge | 79+ | ✅ Fully Supported |
| Mobile | iOS 12+, Android 7+ | ✅ Fully Supported |

## 📈 Performance

- **⚡ Fast Loading**: Optimized assets and lazy loading
- **📱 Mobile Optimized**: Touch-friendly interactions
- **💾 Efficient Storage**: Smart localStorage usage
- **🔄 Smooth Animations**: 60fps CSS animations

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **🍴 Fork the repository**
2. **🌿 Create a feature branch** (`git checkout -b feature/AmazingFeature`)
3. **💻 Make your changes**
4. **✅ Commit your changes** (`git commit -m 'Add some AmazingFeature'`)
5. **📤 Push to the branch** (`git push origin feature/AmazingFeature`)
6. **🔄 Open a Pull Request**

### 🐛 Bug Reports
Found a bug? Please open an issue with:
- Clear description of the issue
- Steps to reproduce
- Expected vs actual behavior
- Screenshots if applicable

### 💡 Feature Requests
Have an idea? We'd love to hear it! Open an issue with:
- Detailed description of the feature
- Use cases and benefits
- Mockups or examples if available

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software...
```

## 👨‍💻 Developer

<div align="center">

<img src="https://github.com/devchauhann.png" alt="Dev Chauhan" width="100" style="border-radius: 50%;">

**Dev Chauhan**

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/devchauhann)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/devchauhann3)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/devchauhann3)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://chauhann.dev)

*Passionate Full-Stack Developer creating beautiful and functional web experiences*

</div>

## 🙏 Acknowledgments

- **Icons**: Curated collection of high-quality SVG icons
- **Design Inspiration**: Modern web design trends and best practices
- **Community**: Thanks to all contributors and users for feedback and support

## 📞 Support

Need help? Here are your options:

- 📧 **Email**: [dev.chauhan@example.com](mailto:devgurjar9897@gmail.com)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/devchauhann/svg-icon-showcase/discussions)
- 🐛 **Issues**: [GitHub Issues](https://github.com/devchauhann/svg-icon-showcase/issues)
- 📱 **Social**: Follow [@devchauhann](https://twitter.com/devchauhann3) for updates

---

<div align="center">

**⭐ Star this repository if you found it helpful!**

Made with ❤️ by [Dev Chauhan](https://github.com/devchauhann)

</div>
