# HTML Learning Notes

## HTML Fundamentals Covered

### Document Structure

Learned the basic structure of an HTML page:

* `<!DOCTYPE html>`
* `<html>`
* `<head>`
* `<body>`
* Meta tags
* Title tag

---

### Text Elements

Practiced:

* Headings (`h1 → h6`)
* Paragraph (`p`)
* Line break (`br`)
* Horizontal line (`hr`)
* Bold (`b`, `strong`)
* Italic (`i`, `em`)

Key Learning:

* Only one main `h1` should generally exist per page
* Heading tags are different from the semantic `<header>` tag

---

### Lists

Practiced:

* Ordered List (`ol`)
* Unordered List (`ul`)
* List Items (`li`)
* Nested Lists

Key Learning:

Nested lists should be written inside list items.

Example:

```html
<ul>
   <li>Frontend
      <ul>
         <li>HTML</li>
         <li>CSS</li>
      </ul>
   </li>
</ul>
```

---

### Links and Media

Practiced:

* Anchor tag (`a`)
* Image tag (`img`)
* Relative paths
* Absolute paths
* `mailto:`
* `tel:`

Key Learning:

Always use the `alt` attribute for images.

---

### Tables

Practiced:

* `table`
* `tr`
* `th`
* `td`
* `caption`
* `thead`
* `tbody`

Key Learning:

`caption` improves accessibility and provides table description.

---

### Forms

Practiced:

* `form`
* `input`
* `label`
* `textarea`
* `select`
* `option`
* Radio buttons
* Checkboxes
* `button`
* `fieldset`
* `legend`

Key Learning:

Connect labels with inputs using `for` and `id`.

Example:

```html
<label for="email">Email</label>
<input type="email" id="email">
```

---

### Semantic HTML

Practiced:

* `header`
* `nav`
* `main`
* `section`
* `article`
* `aside`
* `footer`

Key Learning:

Semantic HTML improves:

* Code readability
* Accessibility
* SEO
* Structure

---

### Accessibility Basics

Practiced:

* `aria-label`
* `aria-labelledby`

Key Learning:

Accessibility attributes help screen readers understand page content.

Example:

```html
<button aria-label="Archive Task">
Archive
</button>
```

---

## Mini Projects Built

✔ Personal Learning Dashboard
Built a structured dashboard layout using semantic HTML sections, navigation, lists and accessibility elements.


✔ Personal Portfolio Structure
Designed a portfolio page containing profile information, education, skills and contact sections.


---

## Important Lessons Learned

* Write clean indentation
* Use semantic tags whenever possible
* Properly nest elements
* Connect labels with form inputs
* Use accessibility attributes
* Keep HTML structure organized and readable

---

Current Status: HTML Fundamentals Completed → Moving to CSS 🚀
