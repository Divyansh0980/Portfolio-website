# Portfolio Website

A minimalistic portfolio website showcasing my GitHub projects with smooth animations and modern design.

![Portfolio Preview](https://img.shields.io/badge/status-active-success.svg)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E)

## ✨ Features

- **Minimalistic Design** - Clean grey, white, and black color palette
- **Smooth Animations** - Fade-in effects, parallax scrolling, and 3D card tilts
- **Responsive Layout** - Works perfectly on mobile, tablet, and desktop devices
- **GitHub Integration** - Automatically displays your GitHub repositories
- **Interactive Cards** - Hover effects with 3D transformations
- **Glassmorphism** - Modern frosted glass effect on project cards

## 🚀 Demo

Visit the live site: [Your Portfolio URL]

## 📂 Project Structure

```
Portfolio-website/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── script.js           # JavaScript animations
├── README.md           # Project documentation
├── LICENSE             # MIT License
└── .gitignore          # Git ignore file
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations, gradients, and glassmorphism
- **JavaScript** - Intersection Observer API for scroll animations
- **Git** - Version control

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/Divyansh0980/Portfolio-website.git
```

2. Navigate to the project directory:
```bash
cd Portfolio-website
```

3. Open `index.html` in your browser:
```bash
# On Windows
start index.html

# On macOS
open index.html

# On Linux
xdg-open index.html
```

Or simply double-click the `index.html` file.

## 🎨 Customization

### Update Personal Information

Edit `index.html` to update:
- Your name in the `<h1>` tag
- Your tagline/description
- GitHub and LeetCode usernames in the social links

### Add More Projects

To add more projects, copy a project card section in `index.html`:

```html
<div class="project-card" data-index="3">
    <div class="project-header">
        <h3 class="project-title">Your Project Name</h3>
        <span class="star-count">
            <svg>...</svg>
            0
        </span>
    </div>
    <p class="project-description">Your project description</p>
    <div class="project-footer">
        <span class="language">Language</span>
        <a href="your-repo-url" target="_blank" class="project-link">View Project →</a>
    </div>
</div>
```

### Change Color Scheme

Modify the color variables in `styles.css`:
- Background gradients in `body` selector
- Text colors throughout the stylesheet
- Button colors in `.github-link` and `.leetcode-link`

## 📱 Responsive Design

The website is fully responsive with breakpoints for:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## ⚡ Performance

- Lightweight and fast loading
- Optimized animations using CSS transforms
- Efficient JavaScript with Intersection Observer
- No external dependencies or frameworks

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is [MIT](LICENSE) licensed.

## 👤 Author

**Divyansh**

- GitHub: [@Divyansh0980](https://github.com/Divyansh0980)
- LeetCode: [@Divyansh0980](https://leetcode.com/Divyansh_91)

## ⭐ Show your support

Give a ⭐️ if you like this project!

## 📸 Screenshots

### Desktop View
![Desktop View]()

### Mobile View
![Mobile View]()

---

Made with ❤️ by Divyansh
