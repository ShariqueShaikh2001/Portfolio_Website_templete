# Portfolio Website Template (Single HTML File)

A clean, responsive portfolio template built in one `index.html` file using Tailwind CSS (CDN) and Font Awesome (CDN).  
Anyone can download it, edit the text/images/links, and use it for their own portfolio.

---

## What’s Inside
- `index.html` (all sections in one file)
  - Navigation with dark mode toggle
  - Hero (intro)
  - About
  - Skills
  - Projects
  - Experience (timeline)
  - Education
  - Contact (form UI only; no backend)
  - Footer
  - Smooth scroll + back-to-top button

---

## How to Use (Super Simple)
1. **Download** this repository (Code → Download ZIP) or **Clone** it.
2. Open `index.html` by **double-clicking** it (it opens in your browser).
3. To edit, open `index.html` in any text editor (VS Code, Notepad, etc.) and replace the placeholder content.

> To put it online later, upload this file to **any web host** (or your own server). No special setup is required.

---

## Quick Edits in `index.html`
Search and replace the following:

### 1) Identity
- **Name**  
  - Find: `Your Name`
- **Role/Headline**  
  - Find: `Web Developer | Designer | Creative Professional`

### 2) Contact
- **Email**  
  - Find: `your.email@example.com`
- **Phone**  
  - Find: `(123) 456-7890`
- **Location**  
  - Find: `San Francisco, CA`

### 3) Social Links
In **Contact → Follow Me** and **Footer**, change `href="#"` to your real links:
- GitHub → `https://github.com/YOUR_USERNAME`
- LinkedIn → `https://linkedin.com/in/YOUR_HANDLE`
- Twitter/X → `https://twitter.com/YOUR_HANDLE`
- Instagram → `https://instagram.com/YOUR_HANDLE`

### 4) Projects
- Replace project **titles**, **descriptions**, **tech tags**, and the two buttons:
  - **Live Demo** → your project URL
  - **Code** → your GitHub repo
- Replace the sample **images** (Unsplash URLs) with your own images/links.

### 5) Profile Image
- In the **About** section, replace the `img src` URL with your photo (or an image in your repo).

### 6) Branding & Footer
- Navbar/brand text: replace `Portfolio`
- Footer text: replace `© 2023 Your Name. All rights reserved.`

### 7) Accent Color (optional)
At the top, in the Tailwind config inside the `<script>` tag:
```js
colors: {
  primary: {
    DEFAULT: '#3B82F6', // change this if you want
    dark: '#2563EB'
  }
}