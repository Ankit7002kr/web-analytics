# web-analytics
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Blog Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Blog</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#posts">Posts</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Latest Post</h2>
        <article>
            <h3>How to Start Web Development</h3>
            <p>Web development is an ever-growing field with lots of opportunities. In this post, we will explore the basics of HTML, CSS, and JavaScript...</p>
            <a href="#">Read more</a>
        </article>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I'm a passionate web developer sharing my knowledge and experiences through this blog. I love building websites and learning new technologies.</p>
    </section>

    <section id="posts">
        <h2>Blog Posts</h2>
        <ul>
            <li><a href="#">Understanding CSS Grid</a></li>
            <li><a href="#">JavaScript ES6 Features</a></li>
            <li><a href="#">Responsive Design Tips</a></li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 My Blog. All rights reserved.</p>
    </footer>
</body>
</html>
