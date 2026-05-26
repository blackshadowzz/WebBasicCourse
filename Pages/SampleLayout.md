# Preview

<style>
  .preview-wrapper {
    margin: 0;
    font-family: Arial, sans-serif;
    display: flex;
    flex-direction: column;
    min-height: 80vh;
    border: 1px solid #ddd;
    border-radius: 4px;
    overflow: hidden;
  }

  .preview-wrapper header {
    background-color: #333;
    color: white;
    padding: 1rem;
    text-align: center;
  }

  .preview-wrapper nav {
    background-color: #444;
    padding: 0.5rem;
    text-align: center;
  }

  .preview-wrapper nav a {
    color: white;
    margin: 0 1rem;
    text-decoration: none;
  }

  .preview-wrapper nav a:hover {
    text-decoration: underline;
  }

  .preview-wrapper .preview-container {
    display: flex;
    flex: 1;
  }

  .preview-wrapper aside {
    background-color: #f4f4f4;
    padding: 1rem;
    width: 250px;
    color: #333;
  }

  .preview-wrapper main {
    flex: 1;
    padding: 2rem;
    background-color: #fff;
    color: #333;
  }

  .preview-wrapper footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem;
    margin-top: auto;
  }
</style>

<div class="preview-wrapper">
  <header>
    <h1>Welcome to My Website</h1>
  </header>

  <nav>
    <a href="Index.html">Home</a>
    <a href="contacts/about.html">About</a>
    <a href="contacts/contact.html">Contact</a>
  </nav>

  <div class="preview-container">
    <aside>
      <h2>Sidebar</h2>
      <ul>
        <li><a href="#">Link 1</a></li>
        <li><a href="#">Link 2</a></li>
        <li><a href="#">Link 3</a></li>
      </ul>
    </aside>

    <main>
      <h2>Main Content Area</h2>
      <p>
        This is the main content of the website. It takes up the remaining
        space on the right side of the sidebar.
      </p>
      <p>Using CSS Flexbox makes it very easy to create this structure.</p>
    </main>
    <aside>
      <h2>Additional Sidebar or Advertisement</h2>
      <p>This is an additional sidebar on the right side.</p>
    </aside>

  </div>

  <footer>
    <p>&copy; 2026 My Website. All rights reserved.</p>
  </footer>
</div>

---

# Code

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Sample Layout</title>
    <link rel="stylesheet" href="publics/css/style.css" />
    <style>
      body {
        margin: 0;
        font-family: Arial, sans-serif;
        display: flex;
        flex-direction: column;
        min-height: 100vh;
      }

      header {
        background-color: #333;
        color: white;
        padding: 1rem;
        text-align: center;
      }

      nav {
        background-color: #444;
        padding: 0.5rem;
        text-align: center;
      }

      nav a {
        color: white;
        margin: 0 1rem;
        text-decoration: none;
      }

      nav a:hover {
        text-decoration: underline;
      }

      .container {
        display: flex;
        flex: 1;
      }

      aside {
        background-color: #f4f4f4;
        padding: 1rem;
        width: 250px;
      }

      main {
        flex: 1;
        padding: 2rem;
        background-color: #fff;
      }

      footer {
        background-color: #333;
        color: white;
        text-align: center;
        padding: 1rem;
        margin-top: auto;
      }
    </style>
  </head>
  <body>
    <header>
      <h1>Welcome to My Website</h1>
    </header>

    <nav>
      <a href="Index.html">Home</a>
      <a href="contacts/about.html">About</a>
      <a href="contacts/contact.html">Contact</a>
    </nav>

    <div class="container">
      <aside>
        <h2>Sidebar</h2>
        <ul>
          <li><a href="#">Link 1</a></li>
          <li><a href="#">Link 2</a></li>
          <li><a href="#">Link 3</a></li>
        </ul>
      </aside>

      <main>
        <h2>Main Content Area</h2>
        <p>
          This is the main content of the website. It takes up the remaining
          space on the right side of the sidebar.
        </p>
        <p>Using CSS Flexbox makes it very easy to create this structure.</p>
      </main>
      <aside>
        <h2>Additional Sidebar or Advertisement</h2>
        <p>This is an additional sidebar on the right side.</p>
      </aside>
    </div>

    <footer>
      <p>&copy; 2026 My Website. All rights reserved.</p>
    </footer>
  </body>
</html>
```
