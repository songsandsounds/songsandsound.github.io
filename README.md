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
