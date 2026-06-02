# Form Styling Using HTML & CSS

## Project Overview

This project is a simple **Form Styling Project** created using **HTML5** and **CSS3**. It demonstrates how to build and style a registration form with a clean layout, modern UI elements, and hover effects.

The project is designed for practicing **HTML form elements** and **CSS styling techniques**.

---

## Features

✅ Clean and simple UI design
✅ Centered form container
✅ Styled labels and placeholders
✅ Rounded borders (`border-radius`)
✅ Button hover effect
✅ Responsive alignment using `margin: auto`
✅ Custom textarea styling

---

## Technologies Used

* **HTML5**
* **CSS3**

---

## Project Structure

```plaintext id="w1v2h9"
Form-Styling-Project/
│── index.html
│── style.css
│── README.md
```

---

## Form Components

The form contains the following fields:

### Input Fields

* Full Name
* Email Address
* Password
* Phone Number

### Selection Fields

* Gender Dropdown
* Skills Checkbox
* Gender Radio Buttons

### Text Area

* Message Box

### Button

* Submit Button with Hover Effect

---

## CSS Styling Applied

### Form Container Styling

* Fixed width (`400px`)
* Center alignment using `margin: auto`
* Padding for spacing
* Rounded corners
* Light background color
* Border styling

### Typography Styling

* Centered heading
* Text shadow effect
* Bold labels

### Input & Textarea Styling

* Placeholder customization
* Border radius for smooth corners
* Padding for better spacing

### Button Styling

* Full-width button
* Hover background effect
* Cursor pointer for interaction

---

## CSS Code Used

```css id="t1styt"
.form-container{
    width: 400px;
    margin: 10px auto;
    padding: 20px;
    border: 1px solid #070000;
    border-radius: 5px;
    background-color: #f3d5d5fe;
}

.form-group{
    margin-bottom: 10px;
}

h2{
    text-align: center;
    color: #070000;
    text-shadow: 1px 1px 2px #070000;
}

label{
    display:inline-block;
    margin-bottom: 5px;
    color: #070000;
    font-weight: bold;
}

textarea{
    width: 70%;
    padding: 10px;
    border: 1px solid #070000;
    border-radius: 5px;
}

input::placeholder,
textarea::placeholder{
    color: #070000;
    text-shadow: 1px 1px 2px #070000;
}

button{
    display: block;
    width: 100%;
    padding: 10px;
    background-color: #f3d5d5fe;
    color: #a51414;
    border: 1px solid #070000;
    border-radius: 5px;
    cursor: pointer;
}

button:hover{
    background-color: #000000;
}
```

---

## How to Run the Project

1. Download or clone this repository.
2. Open the project folder.
3. Open `index.html` in any browser.

---

## Learning Outcomes

By completing this project, you will learn:

* HTML Form Creation
* CSS Selectors
* Styling Form Components
* Placeholder Customization
* Hover Effects
* Box Model Concepts
* UI Improvement Basics

---

## Future Improvements

* Add responsive design using media queries
* Add form validation
* Improve accessibility
* Add animations and transitions
* Enhance UI design

---

## Author

Created for practicing **HTML Form Styling using CSS**.
