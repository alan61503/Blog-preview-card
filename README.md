# 🎨 3D Hover Card Design

This is a solution to the **3D Hover Card Design Challenge**. This project showcases a responsive card with dynamic hover effects, rounded borders, and an elegant 3D shadow transition. It is a great example of modern CSS styling and animation techniques.

## 📋 Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [👩‍💻 Author](#author)
- [🙏 Acknowledgments](#acknowledgments)

---

## 🌟 Overview

### 🏆 The challenge

Users should be able to:

- 🖱️ See a smooth lift effect when hovering over the card.
- 🟡 Experience rounded corners on the card that maintain their shape even during hover transitions.
- 🖤 View a realistic 3D shadow effect emphasizing depth.
- 📱 Interact with a fully responsive design.

### 📸 Screenshot

![alt text](<blog card/blog-preview-card-main/screenshots/1.png>)
![alt text](<blog card/blog-preview-card-main/screenshots/2.png>)
![alt text](<blog card/blog-preview-card-main/screenshots/3.png>)



### 🔗 Links

- 🚀 Solution URL: [click here](https://github.com/alan61503/Blog-preview-card)
- 🌐 Live Site URL: [click here](https://alan61503.github.io/Blog-preview-card/)

---

## 🛠️ My process

### ⚙️ Built with

- 🏗️ Semantic HTML5 markup
- 🎨 CSS custom properties
- ✨ CSS transitions and animations
- 📲 Mobile-first workflow

---

### 📚 What I learned

This project helped me deepen my understanding of CSS transitions and shadows. Here's an example of how I achieved the hover effect:

```css
.card:hover {
  transform: translateY(-15px);
  box-shadow: 
    10px -10px 20px rgba(0, 0, 0, 0.3),
    -10px 10px 20px rgba(0, 0, 0, 0.3),
    0 8px 16px rgba(0, 0, 0, 0.3);
}
```
I also learned how to maintain rounded corners for both inner and outer borders during hover transitions.

## 🔮 Continued development

I plan to:

- 🖼️ Add support for multiple card designs with different shadow effects.
- 📜 Explore JavaScript integrations for dynamic content rendering.
- ♿ Improve accessibility features.

---

## 📖 Useful resources

- 🖤 [MDN Web Docs - CSS box-shadow](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow) - This resource helped me understand shadow layering and offsets.
- 🎨 [CSS Tricks - Hover Effects](https://css-tricks.com/almanac/properties/t/transition/) - A great article on achieving smooth transitions.

---

## 👩‍💻 Author

- 🌐 Website - [Your Name](https://www.your-website.com)
- 🧑‍💻 Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- 🐱 GitHub - [@yourusername](https://github.com/alan61503)

---

## 🙏 Acknowledgments

Thanks to [Frontend Mentor](https://www.frontendmentor.io/) for inspiring this project. Special thanks to tutorials and resources from MDN and CSS-Tricks that helped shape this design. 🙌
