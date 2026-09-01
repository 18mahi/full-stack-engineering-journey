
# 📸 CSS Sidebar Menu

A simple and interactive sidebar menu created using **HTML and CSS**.

## ✨ Features

- ☰ Hamburger menu
- ❌ Close button
- 📱 Sidebar navigation
- 🖼️ Full-screen background image
- 🎨 Transparent sidebar design
- 🖱️ Hover effects
- ✨ Smooth CSS transitions
- 📱 Social media icons
- 🚫 No JavaScript required

## 🛠️ Technologies Used

- HTML5
- CSS3
- Font Awesome
- Google Fonts (Poppins)

## 📂 Project Structure

```text
CSS-Sidebar-Menu/
│
├── index1.html
├── style.css
├── photo2.jpg
└── README.md

## 📋 Menu Items
* 🖼️ Gallery
* 🔗 Shortcuts
* 🎞️ Exhibits
* 📅 Events
* 🛍️ Store
* 📞 Contact
* 💬 Feedback

## ⚙️ How It Works

The sidebar is opened and closed using a hidden HTML checkbox, so JavaScript is not required.

```html
<input type="checkbox" id="check">
```

The hamburger button is connected to the checkbox using a label:

```html
<label for="check">
    <i class="fa-solid fa-bars"></i>
</label>
```

CSS is then used to display the sidebar when the checkbox is checked:

```css
#check:checked ~ .sidebar_menu {
    left: 0;
}
```

## 🎨 Design

The project uses a camera image as a full-screen background with a transparent sidebar and shadow effects.

```css
.main_box {
    background: url("photo2.jpg");
    background-size: cover;
    height: 100vh;
}
```

## 🚀 How to Run

1. Clone the repository.
2. Open the project folder.
3. Make sure `index1.html`, `style.css`, and `photo2.jpg` are in the same folder.
4. Open `index1.html` in your browser.

## 📚 What I Learned

* HTML structure
* CSS positioning
* Fixed positioning
* CSS transitions
* Hover effects
* CSS sibling selectors
* Checkbox-based CSS interaction
* Background images
* Box shadows
* Transparent backgrounds
* Font Awesome icons
* Google Fonts
* Sidebar UI design

## 🔮 Future Improvements

* Make the design fully responsive
* Add active navigation states
* Add functional navigation links
* Improve accessibility
* Add more animations
* Add JavaScript for advanced interactions

## 👩‍💻 Author

**Mahi Jindal**

⭐ If you like this project, consider giving the repository a star!

```
```
