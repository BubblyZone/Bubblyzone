<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>BubblyZone | Printing Services</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #007BFF;
      color: white;
      padding: 1rem 2rem;
      text-align: center;
    }
    nav {
      background: #0056b3;
      padding: 0.5rem 2rem;
      display: flex;
      justify-content: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      padding: 2rem;
    }
    .services, .contact {
      background: #e6f0ff;
      margin: 1rem 0;
      border-radius: 10px;
      padding: 1rem;
    }
    footer {
      background: #003f7f;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
    form input, form textarea {
      width: 100%;
      padding: 0.5rem;
      margin: 0.5rem 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    form button {
      background: #007BFF;
      color: white;
      border: none;
      padding: 0.7rem 1.5rem;
      border-radius: 5px;
      cursor: pointer;
    }
    form button:hover {
      background: #0056b3;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to BubblyZone</h1>
    <p>Your trusted printing service partner</p>
  </header>
  <nav>
    <a href="#about">About Us</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Us</h2>
    <p>BubblyZone is a professional printing service offering a wide range of solutions to meet your business and personal printing needs. We are committed to quality, reliability, and customer satisfaction.</p>
  </section>

  <section id="services" class="services">
    <h2>Our Services</h2>
    <ul>
      <li>Business Cards</li>
      <li>Posters & Flyers</li>
      <li>Brochures</li>
      <li>Custom T-Shirts</li>
      <li>Large Format Printing</li>
      <li>Stickers & Labels</li>
    </ul>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="5" placeholder="Your Message"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 BubblyZone. All rights reserved.</p>
  </footer>
</body>
</html>
