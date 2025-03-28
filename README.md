📁 **Folder Structure:**
- `/` → Root folder.
- `index.html` → Homepage.
- `login.html` → Login page.
- `page1.html` to `page5.html` → Additional pages with different layouts.
- `style.css` → Styling file.
- `script.js` → Optional JS file for interactivity.
- `README.md` → Instructions on how to edit the layout.

---

💡 **Code Files:**

### `index.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Home</title>
</head>
<body>
    <header>
        <nav>
            <a href="index.html">Home</a>
            <a href="page1.html">Page 1</a>
            <a href="page2.html">Page 2</a>
            <a href="login.html">Login</a>
        </nav>
    </header>
    <main>
        <h1>Welcome to the Adjustable Website</h1>
        <p>Edit the layout by modifying the HTML and CSS files.</p>
    </main>
    <footer>
        <p>&copy; 2025 My Website</p>
    </footer>
</body>
</html>
```

---

### `login.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Login</title>
</head>
<body>
    <div class="login-container">
        <form>
            <h2>Login</h2>
            <label for="username">Username</label>
            <input type="text" id="username" name="username" required>
            <label for="password">Password</label>
            <input type="password" id="password" name="password" required>
            <button type="submit">Login</button>
        </form>
    </div>
</body>
</html>
```

---

### `style.css`
```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
header {
    background: #f3a4a4;
    padding: 10px 20px;
}
nav a {
    margin: 0 10px;
    text-decoration: none;
    color: white;
}
.login-container {
    width: 100%;
    max-width: 400px;
    margin: 50px auto;
    background: #fff;
    padding: 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}
```

---

### ✅ **Next Steps:**
- You can now modify the HTML and CSS to adjust the layout.
- Let me know if you want more pages, features, or interactivity!
- 
