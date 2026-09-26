# ☀️🌙 Premium Theme Switch UI

<p align="center">

  <img src="assets/preview.png" alt="Premium Day and Night Theme Switch UI">

</p>

<h3 align="center">
  A modern interactive Day/Night theme switch built with HTML, CSS and JavaScript.
</h3>

<p align="center">

<a href="#-features">Features</a> • <a href="#-demo">Demo</a> • <a href="#-technologies">Technologies</a> • <a href="#-installation">Installation</a> • <a href="#-author">Author</a>

</p>

---

## ✨ Overview

**Premium Theme Switch UI** is a modern frontend UI experiment that transforms a simple light/dark mode toggle into a complete interactive experience.

Instead of using a basic checkbox or switch, this project creates a visual transition between:

☀️ **Day Mode**

and

🌙 **Night Mode**

The interface includes animated environmental changes, a premium switch component, responsive layouts and an interactive developer-style code preview.

The project was created as part of my frontend development journey to practice creating polished UI interactions using vanilla web technologies.

---

## 🚀 Features

* ☀️ Interactive Day Mode
* 🌙 Interactive Night Mode
* 🌅 Animated Sun transition
* 🌙 Animated Moon transition
* ✨ Subtle night-sky effects
* 🎨 Smooth theme transitions
* 💫 Micro-interactions
* 🖱️ Hover and click animations
* 💾 Theme persistence using `localStorage`
* 🖥️ Developer-style code preview
* 📱 Fully responsive design
* ⌨️ Keyboard accessibility
* ♿ Accessible theme control
* ⚡ Lightweight vanilla JavaScript
* 🎯 No unnecessary frameworks
* 🌐 Works directly in the browser

---

## 🎨 Preview

### ☀️ Day Mode

<p align="center">
  <img src="assets/screenshots/day-mode.png" alt="Day Mode preview">
</p>

---

### 🌙 Night Mode

<p align="center">
  <img src="assets/screenshots/night-mode.png" alt="Night Mode preview">
</p>

---

## 🧠 What I Practiced

This project helped me practice several important frontend concepts:

### HTML

* Semantic structure
* Form controls
* Accessibility attributes
* Component organization

### CSS

* CSS variables
* Responsive design
* Transitions
* Keyframe animations
* Gradients
* Shadows
* Glass-style surfaces
* Hover states
* Focus states
* Responsive layouts

### JavaScript

* DOM manipulation
* Event listeners
* Theme state management
* `localStorage`
* System theme detection
* Dynamic UI updates
* Accessibility interactions

---

## 🛠️ Technologies

| Technology    | Purpose              |
| ------------- | -------------------- |
| HTML5         | Structure            |
| CSS3          | Styling & animations |
| JavaScript    | Theme functionality  |
| LocalStorage  | Theme persistence    |
| CSS Variables | Theme management     |

---

## 📂 Project Structure

```text
premium-theme-switch-ui/
│
├── index.html
├── README.md
├── LICENSE
├── .gitignore
│
└── assets/
    ├── preview.png
    └── screenshots/
        ├── day-mode.png
        └── night-mode.png
```

---

## ⚙️ How It Works

The theme system uses a theme state that controls the visual appearance of the interface.

Example concept:

```javascript
document.documentElement.setAttribute(
    "data-theme",
    theme
);
```

The selected theme can then be stored in the browser:

```javascript
localStorage.setItem("theme", theme);
```

When the page loads, the saved theme is restored automatically.

---

## 💾 Theme Persistence

If the user selects:

```text
🌙 Night Mode
```

the preference is saved locally.

When the user returns to the page, the selected theme can be restored without requiring them to toggle it again.

---

## 📱 Responsive Design

The UI is designed to work across:

* Mobile phones
* Tablets
* Laptops
* Desktop monitors
* Large screens

Special attention is given to:

* Touch-friendly controls
* Code preview scrolling
* Text readability
* Layout spacing
* Preventing horizontal page overflow

---

## ♿ Accessibility

The theme switch is designed with accessibility in mind.

The interface supports:

* Keyboard interaction
* Focus states
* Descriptive ARIA labeling
* Touch-friendly controls
* Reduced-motion preferences

---

## ⚡ Performance

The project intentionally uses lightweight web technologies.

No large frontend framework is required.

The animations primarily rely on:

```text
CSS transitions
CSS transforms
CSS keyframes
Opacity
```

This keeps the interaction smooth while avoiding unnecessary JavaScript work.

---

## 🎯 Future Improvements

Possible future upgrades:

* [ ] More theme variations
* [ ] Custom theme creator
* [ ] Animated weather environments
* [ ] Theme transition sound effects
* [ ] More code-preview interactions
* [ ] Theme export/import
* [ ] Additional accessibility improvements
* [ ] Component customization panel

---

## 🌐 Live Demo

**Live Demo:** Add your deployed project URL here.

Example:

```text
https://your-project-url.com
```

---

## 📸 Screenshots

The repository includes screenshots showing both Day Mode and Night Mode.

These screenshots demonstrate the visual transformation and responsive UI design.

---

## 🤝 Contributing

Contributions, suggestions and improvements are welcome.

If you find a bug or have an idea for improving the UI:

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Commit your changes
5. Open a Pull Request

---

## 📄 License

This project is available under the MIT License.

See the `LICENSE` file for more information.

---

## 👨‍💻 Author

### Code With Vishesh

**Vishesh Jaiswal**

Frontend Developer | JavaScript | React.js | Full-Stack Development

I'm learning by building real-world projects and experimenting with modern web technologies.

### Connect With Me

* GitHub: https://github.com/Code-With-Vishesh
* LinkedIn: https://www.linkedin.com/in/codewithvishesh/
* Instagram: https://www.instagram.com/code_with_vishesh/
* YouTube: https://www.youtube.com/@VisheshJayaswal

---

<p align="center">

### ☀️ Build. 🌙 Experiment. 💻 Learn. 🚀 Repeat.

**Made with ❤️ by Code With Vishesh**

</p>
