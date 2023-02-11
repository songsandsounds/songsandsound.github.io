<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>My Product</title>
  </head>
  <body>
    <header>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#products">Products</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <section id="about">
        <h2>About</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam malesuada orci vel bibendum dictum. Nam ac massa efficitur, placerat orci vel, gravida tellus. In hac habitasse platea dictumst. Donec malesuada libero vel risus vestibulum, vel facilisis velit pharetra.</p>
      </section>
      <section id="products">
        <h2>Products</h2>
        <ul>
          <li>
            <h3>Product 1</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam malesuada orci vel bibendum dictum. Nam ac massa efficitur, placerat orci vel, gravida tellus. In hac habitasse platea dictumst. Donec malesuada libero vel risus vestibulum, vel facilisis velit pharetra.</p>
            <button>Buy</button>
          </li>
          <li>
            <h3>Product 2</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam malesuada orci vel bibendum dictum. Nam ac massa efficitur, placerat orci vel, gravida tellus. In hac habitasse platea dictumst. Donec malesuada libero vel risus vestibulum, vel facilisis velit pharetra.</p>
            <button>Buy</button>
          </li>
        </ul>
      </section>
      <section id="contact">
        <h2>Contact</h2>
        <form action="#">
          <label for="name">Name:</label>
          <input type="text" id="name" name="name">
          <label for="email">Email:</label>
          <input type="email" id="email" name="email">
          <label for="message">Message:</label>
          <textarea id="message" name="message"></textarea>
          <input type="submit" value="Submit">
        </form>
      </section>
    </main>
    <footer>
      <p>Copyright &copy; My Product</p>
    </footer>
  </body>
</html>
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>My Product</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        background-color: #f2f2f2;
      }
      header {
        background-color: #333;
        color: #fff;
        padding: 20px;
        text-align: center;
      }
      header nav ul {
        list-style: none;
        margin: 0;
        padding: 0;
        display: flex;
        justify-content: center;
      }
      header nav ul li {
        margin: 0 10px;
      }
      header nav ul li a {
        color: #fff;
        text-decoration: none;
      }
      main {
        max-width: 800px;
        margin: 0 auto;
        padding: 20px;
      }
      section {
        margin-bottom: 20px;
        background-color: #fff;
        padding: 20px;
        box-shadow: 0 0 10px #ccc;
      }
      section h2 {
        margin-top: 0;
      }
      section button {
        background-color: #333;
        color: #fff;
        padding: 10px 20px;
        border: none;
        border-radius: 5px;
        cursor: pointer;
      }
      footer {
        background-color: #333;
        color: #fff;
        padding: 20px;
        text-align: center;
      }
    </style>
  </head>
  <body>
    <header>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#products">Products</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <section id="about">
        <h2>About</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam malesuada orci vel bibendum dictum. Nam ac massa efficitur, placerat orci vel, gravida tellus. In hac habitasse platea dictumst. Donec malesuada libero vel risus vestibulum, vel facilisis velit pharetra.</p>
      </section>
      <section id="products">
        <h2>Products</h2>
        <ul>
          <li>
            <h3>Product 1</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam malesuada orci vel bibendum dictum. Nam ac massa efficitur, placerat orci vel, gravida tellus. In hac habitasse platea dictumst. Donec malesuada libero vel risus vestibulum, vel facilisis velit pharetra.</p>
            <button>
<li>
  <img src="product1.jpg" alt="Product 1">
  <h3>Product 1</h3>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam malesuada orci vel bibendum dictum. Nam ac massa efficitur, placerat orci vel, gravida tellus. In hac habitasse platea dictumst. Donec malesuada libero vel risus vestibulum, vel facilisis velit pharetra.</p>
  <button>Buy now</button>
</li>
<form action="sendemail.php" method="post">
  <input type="text" name="name" placeholder="Name">
  <input type="email" name="email" placeholder="Email">
  <textarea name="message" placeholder="Message"></textarea>
  <button type="submit">Send</button>
</form>
