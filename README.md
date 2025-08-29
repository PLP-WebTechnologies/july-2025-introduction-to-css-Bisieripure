<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Box Model Showcase</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>Welcome to My Styled Page</h1>
    <p>This page demonstrates CSS selectors, the box model, and clean layout styling.</p>
  </header>

  <main>
    <section class="card">
      <h2>About This Page</h2>
      <p>This section uses padding, margin, and borders to illustrate the box model.</p>
    </section>

    <section class="card">
      <h2>Features</h2>
      <ul>
        <li>External CSS with class and element selectors</li>
        <li>Consistent spacing and sizing</li>
        <li>Semantic HTML structure</li>
      </ul>
    </section>

    <section class="card">
      <h2>Contact</h2>
      <form>
        <label for="name">Name:</label>
        <input type="text" id="name" placeholder="Your name" required />

        <label for="email">Email:</label>
        <input type="email" id="email" placeholder="you@example.com" required />

        <button type="submit">Submit</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Styled Page Demo</p>
  </footer>
</body>
</html>
