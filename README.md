# 📊 Social Media Dashboard with Theme Toggle

A beautifully crafted social media dashboard that visualizes metrics across multiple platforms — complete with a sleek light/dark theme toggle. This is a pure **HTML + CSS** UI project with a focus on responsive layout, clean aesthetics, and modern design trends.

## 🚀 Live Demo
![127 0 0 1_5500_index html](https://github.com/yarlinlynn/Social-Media-Dashboard/assets/140059481/2f2727bc-9b83-4667-b21a-3eca22bb9eff)

<br/>

## 🧠 Concept

This project was inspired by modern analytics dashboards used in tools like Buffer, Hootsuite, and native social media insights panels. The main goal was to create a visually appealing, responsive, and theme-adaptive interface **without any JavaScript**.

## ✨ Key Features

- 🎨 **Light/Dark Theme Toggle** – fully styled switch using pure CSS
- 📱 **Responsive Design** – scales elegantly across mobile, tablet, and desktop
- 📈 **Metrics Cards** – daily and overall engagement statistics for multiple platforms (Facebook, Twitter, Instagram, YouTube)
- 💡 **Accessible UI** – strong color contrast and readable fonts
- 🧼 **Clean and Minimalist Layout** – focus on user metrics without clutter

<br/>

## 🛠 Tech Stack

- **HTML5** – semantic, structured markup
- **CSS3** – Flexbox, CSS variables, transitions, and custom toggle styling
- ❌ **No JavaScript** – everything handled through CSS interactions

<br/>

## 📂 File Structure
```
Social-Media-Dashboard/
├── index.html # Main dashboard structure
├── style.css # All styling including themes and layout
└── README.md # Project documentation
```

## 🧪 How the Theme Toggle Works

The theme toggle is implemented using a checkbox input styled as a switch. When toggled, the `:checked` state triggers a global theme change by switching CSS variables — no JS needed!

```css
:root {
  --bg-color: hsl(0, 0%, 100%);
  --text-color: hsl(230, 17%, 14%);
}

body.dark-mode {
  --bg-color: hsl(230, 17%, 14%);
  --text-color: hsl(0, 0%, 100%);
}
```
> The body element’s class is toggled using a checkbox :checked selector via CSS.


## 📈 Metrics Displayed
Followers, Likes, and Views per platform

Up/down arrows showing change since previous day

Visual indicators for growth or decline

Each platform’s signature color and icon is used for quick recognition
