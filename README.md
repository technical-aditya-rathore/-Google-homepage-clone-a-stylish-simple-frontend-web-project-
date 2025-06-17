# Google-homepage-clone-a-stylish-simple-frontend-web-project
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

 Google homepage clone — a stylish, simple frontend web project using HTML + CSS (and optionally JavaScript for animation or form behaviour).


---

## 🌐 Project Title: **Google Homepage Clone**

### 🔧 Tools/Tech:

* HTML5
* CSS3 (Flexbox/Grid)
* Optional: JavaScript for animations or search field behavior

---

## ✅ Features:

* Google logo (use placeholder or real image)
* Search bar
* Two buttons: `Google Search` and `I'm Feeling Lucky`
* Footer with links
* Responsive layout (desktop & mobile)

---

## 📁 File Structure:

```
google-clone/
│
├── index.html
├── style.css
└── images/
    └── google-logo.png
```

---

## 🔤 `index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Google Clone</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <img src="images/google-logo.png" alt="Google Logo" class="logo" />
    
    <div class="search-box">
      <input type="text" placeholder="Search Google or type a URL" />
    </div>
    
    <div class="buttons">
      <button>Google Search</button>
      <button>I'm Feeling Lucky</button>
    </div>
  </div>

  <footer>
    <div class="footer-links">
      <a href="#">About</a>
      <a href="#">Advertising</a>
      <a href="#">Business</a>
      <a href="#">Privacy</a>
      <a href="#">Settings</a>
    </div>
  </footer>
</body>
</html>
```

---

## 🎨 `style.css`

```css
body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
  background-color: #f8f9fa;
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: center;
  align-items: center;
}

.container {
  text-align: center;
  margin-top: -80px;
}

.logo {
  width: 270px;
  margin-bottom: 30px;
}

.search-box input {
  width: 550px;
  padding: 12px 20px;
  border: 1px solid #dcdcdc;
  border-radius: 24px;
  outline: none;
  font-size: 16px;
  box-shadow: 0 1px 6px rgba(32, 33, 36, 0.28);
}

.buttons {
  margin-top: 25px;
}

button {
  margin: 6px;
  padding: 10px 20px;
  border: none;
  background-color: #f8f9fa;
  border: 1px solid #f8f9fa;
  border-radius: 4px;
  cursor: pointer;
  font-size: 14px;
}

button:hover {
  border: 1px solid #dadce0;
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.1);
}

footer {
  position: absolute;
  bottom: 0;
  width: 100%;
  padding: 16px 0;
  background: #f2f2f2;
  text-align: center;
}

.footer-links a {
  margin: 0 12px;
  text-decoration: none;
  color: #5f6368;
  font-size: 14px;
}

.footer-links a:hover {
  text-decoration: underline;
}
```

---

## 🖼️ Google Logo:

* Save a PNG logo as `google-logo.png` inside a folder named `images/`
* Or use online URL:

```html
<img src="https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png">
```

---

## ✅ Enhancements (Optional):

* Add **dark mode** toggle with JavaScript
* Add **voice input** icon (microphone symbol)
* Add **keyboard shortcuts** (press Enter to simulate search)
* Animate buttons with hover effects

---

Project made by 🥇
Aditya Kumar Jha 
follow for more=====================+++++++++++++++++++++++++++++++
