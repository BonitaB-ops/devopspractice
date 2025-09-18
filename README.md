<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Learn to Earn</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f9;
      color: #333;
    }
    header {
      background: #2b6cb0;
      color: white;
      padding: 20px;
      text-align: center;
    }
    section {
      padding: 30px;
      max-width: 600px;
      margin: auto;
    }
    h1, h2 {
      text-align: center;
    }
    form {
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }
    label {
      display: block;
      margin-top: 15px;
      font-weight: bold;
    }
    input, select, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      margin-top: 20px;
      padding: 12px;
      background: #2b6cb0;
      color: white;
      border: none;
      border-radius: 5px;
      width: 100%;
      font-size: 16px;
      cursor: pointer;
    }
    button:hover {
      background: #1a4d80;
    }
  </style>
</head>
<body>

  <header>
    <h1>Learn to Earn</h1>
    <p>Sign up to start your journey of learning and earning today!</p>
  </header>

  <section>
    <h2>Join Us</h2>
    <form action="https://formspree.io/f/your-form-id" method="POST">
      <label for="name">Your Name</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Your Email</label>
      <input type="email" id="email" name="email" required>

      <label for="interest">What do you want to learn?</label>
      <select id="interest" name="interest" required>
        <option value="">-- Select --</option>
        <option value="coding">Coding</option>
        <option value="business">Business</option>
        <option value="design">Design</option>
        <option value="marketing">Marketing</option>
      </select>

      <label for="message">Tell us more</label>
      <textarea id="message" name="message" rows="4"></textarea>

      <button type="submit">Submit</button>
    </form>
  </section>

</body>
</html>
# devopspractice
Learning Repo
