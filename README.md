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
/* Basic Reset */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

/* Body Styling */
body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f4;
  padding: 20px;
}

/* Header Styling */
header {
  text-align: center;
  margin-bottom: 30px;
}

header h1 {
  color: #333;
  margin-bottom: 10px;
}

/* Card Sections */
.card {
  background-color: #fff;
  border: 1px solid #ccc;
  padding: 20px;
  margin-bottom: 20px;
  border-radius: 8px;
}

/* List Styling */
ul {
  list-style-type: disc;
  padding-left: 20px;
}

/* Form Styling */
form {
  display: flex;
  flex-direction: column;
}

label {
  margin-top: 10px;
  margin-bottom: 5px;
}

input {
  padding: 8px;
  border: 1px solid #aaa;
  border-radius: 4px;
}

button {
  margin-top: 15px;
  padding: 10px;
  background-color: #0077cc;
  color: white;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

button:hover {
  background-color: #005fa3;
}

/* Footer Styling */
footer {
  text-align: center;
  margin-top: 40px;
  color: #666;
}
