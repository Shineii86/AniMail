<div align="center">
  
  # [AniMail](https://github.com/AniPulse)
  *Anime-Themed Email Generator*

AniMail is a sleek, anime-themed email generator that creates unique email addresses with premium domains. Featuring vibrant colors, glassmorphism design, and smooth animations, it offers both random and custom email generation with password creation capabilities.

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge&logo=google-chrome)](https://your-demo-link.com)
![Last Commit](https://img.shields.io/github/last-commit/Shineii86/AniMail?style=for-the-badge)
![Repo Size](https://img.shields.io/github/repo-size/Shineii86/AniMail?style=for-the-badge) [![GitHub Stars](https://img.shields.io/github/stars/Shineii86/AniMail?style=for-the-badge)](https://github.com/Shineii86/AniMail/stargazers) [![GitHub Forks](https://img.shields.io/github/forks/Shineii86/AniMail?style=for-the-badge)](https://github.com/Shineii86/AniMail/fork)

</div>

## ✨ Features

- 🌓 Dark/Light mode toggle with smooth transitions
- 🎨 Premium anime-themed color schemes
- ✨ Glassmorphism UI design
- ⚡️ Random email generator with anime-themed domains
- 🔧 Custom email generator with domain selection
- 🔑 Secure password generation
- 📋 Copy to clipboard functionality
- 📱 Fully responsive design
- 🚀 Animations powered by anime.js

## 🚀 Live Demo

Experience AniMail live:  
[![Live Demo Button](https://img.shields.io/badge/Experience_AniMail-Live_Demo-9cf?style=for-the-badge&logo=vercel)](https://your-demo-link.com)

## 🛠️ Technologies Used

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Anime.js](https://img.shields.io/badge/Anime.js-2C2D72?style=flat&logo=anime.js&logoColor=white)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-528DD7?style=flat&logo=font-awesome&logoColor=white)
![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=flat&logo=google-fonts&logoColor=white)

## 🎨 Customization Guide

### 1. Color Schemes 🖌️
Modify the CSS variables in the `:root` section:

```css
:root {
  /* Light Theme Colors */
  --light-primary: #ff6b6b;
  --light-secondary: #4ecdc4;
  --light-accent: #ff9a76;
  
  /* Dark Theme Colors */
  --dark-primary: #ff79c6;
  --dark-secondary: #bd93f9;
  --dark-accent: #ffb86c;
}
```

### 2. Domains 🌐
Add or modify domains in the HTML select elements:

```html
<select id="randomDomain">
  <option value="@quinx.com">@quinx.com</option>
  <option value="@sakura.jp">@sakura.jp</option>
  <!-- Add more domains here -->
</select>
```

### 3. Anime Names/Words 📛
Expand the random name generator by adding to these arrays:

```javascript
const animeNames = ['sakura', 'naruto', 'goku' /* Add more names */];
const animeWords = ['kawaii', 'kitsune', 'senpai' /* Add more words */];
```

### 4. Animations 🎬
Customize animations using anime.js:

```javascript
anime({
  targets: '.card',
  translateY: [50, 0],
  opacity: [0, 1],
  duration: 1200,
  delay: anime.stagger(200),
  easing: 'easeOutExpo'
});
```

### 5. Footer Information ℹ️
Update the footer content in the HTML:

```html
<footer>
  <div class="footer-content">
    <!-- Update social links, legal pages, and copyright -->
    <a href="https://github.com/yourusername" target="_blank">GitHub</a>
    <p>&copy; 2023 Your Name. All rights reserved.</p>
  </div>
</footer>
```

## 🖥️ Installation

1. Clone the repository:
```bash
git clone https://github.com/Shineii86/AniMail.git
```

2. Navigate to the project directory:
```bash
cd AniMail
```

3. Open `index.html` in your browser:
```bash
# For Windows:
start index.html

# For macOS:
open index.html

# For Linux:
xdg-open index.html
```

## 🌟 Features in Detail

| Feature | Description | Emoji |
|---------|-------------|-------|
| **Random Generator** | Creates anime-themed emails with secure passwords | 🎲 |
| **Custom Generator** | Build your own email with custom domains | 🛠️ |
| **Theme Toggle** | Switch between light and dark modes | 🌓 |
| **Glassmorphism UI** | Modern frosted glass design elements | ✨ |
| **Copy Functionality** | One-click copy for emails and passwords | 📋 |
| **Responsive Design** | Works perfectly on all device sizes | 📱 |

## 🧩 Project Structure

```
animail/
├── index.html          # Main HTML file
├── README.md           # Project documentation
├── LICENSE             # License file
├── assets/             # Optional assets folder
│   ├── css/            # CSS files
│   ├── js/             # JavaScript files
│   └── img/            # Image assets
```

## 🤝 Contributing

Contributions are welcome! Follow these steps:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## 🎉 Acknowledgements

- [Anime.js](https://animejs.com/) for amazing animations
- [Font Awesome](https://fontawesome.com/) for beautiful icons
- [Google Fonts](https://fonts.google.com/) for Noto Sans font
- [Shields.io](https://shields.io/) for badges

---
## 🪪 License

This project is licensed under the [MIT License](LICENSE).
Feel free to use, remix, and share it with proper credits.

---

## 👤 Credits

> Project created by [**Shinei Nouzen**](https://github.com/Shineii86)
> Built with ❤️ passion for Anime and Open Source.

---

## 📬 Support

* Issues: [GitHub Issues](https://github.com/Shineii86/AniMail/issues)

---

## 💕 Loved My Work?

🚨 [Follow me on GitHub](https://github.com/Shineii86/Shineii86)

⭐ [Give a star to this project](https://github.com/Shineii86/AniMail)

<a href="https://github.com/Shineii86/AniMail">
<img src="https://github.com/Shineii86/AniPay/blob/main/Source/Banner6.png" alt="Banner">
</a>

---

## ☎️ Contact

<div align="center">

*For inquiries or collaborations*

[![Telegram Badge](https://img.shields.io/badge/-Telegram-2CA5E0?style=flat\&logo=Telegram\&logoColor=white)](https://telegram.me/Shineii86 "Contact on Telegram")
[![Instagram Badge](https://img.shields.io/badge/-Instagram-C13584?style=flat\&logo=Instagram\&logoColor=white)](https://instagram.com/ikx7.a "Follow on Instagram")
[![Pinterest Badge](https://img.shields.io/badge/-Pinterest-E60023?style=flat\&logo=Pinterest\&logoColor=white)](https://pinterest.com/ikx7a "Follow on Pinterest")
[![Gmail Badge](https://img.shields.io/badge/-Gmail-D14836?style=flat\&logo=Gmail\&logoColor=white)](mailto:ikx7a@hotmail.com "Send an Email")

<sup><b>Copyright © 2025 <a href="https://telegram.me/Shineii86">Shinei Nouzen</a>.
All Rights Reserved</b></sup>

</div>
