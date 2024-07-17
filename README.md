<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Payton's Deals</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5dc; /* light brown */
            color: #4b3621; /* dark brown */
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        header {
            background-color: #556b2f; /* olive */
            width: 100%;
            padding: 1rem;
            text-align: center;
        }
        header h1 {
            color: #f5deb3; /* pale orange */
            margin: 0;
        }
        main {
            max-width: 800px;
            padding: 1rem;
        }
        section {
            margin-bottom: 2rem;
        }
        h2 {
            color: #d2691e; /* pale dark brown */
        }
        footer {
            background-color: #556b2f;
            width: 100%;
            padding: 1rem;
            text-align: center;
            color: #f5deb3;
        }
        a {
            color: #556b2f;
            text-decoration: none;
        }
        .card {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 1rem;
            margin-bottom: 1rem;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
    </style>
</head>
<body>
    <header>
        <h1>Payton's Deals</h1>
    </header>
    <main>
        <section id="about-me">
            <h2>About Me</h2>
            <p>Hi, I'm Payton and I never pay full price for items I want. I find deals and sales so you don't have to just like me.</p>
        </section>
        <section id="trending-sales">
            <h2>Trending Sales</h2>
            <div class="card">
                <h3>Amazon</h3>
                <p>Check out the latest deals on Amazon. <a href="https://paytonnicolehall.my.canva.site/amazon-storefront" target="_blank">View now</a></p>
            </div>
            <!-- Add more sales as needed -->
        </section>
        <section id="contact-info">
            <h2>Contact Information</h2>
            <p>Email: <a href="mailto:payton@example.com">payton@example.com</a></p>
            <p>Social Media: 
                <a href="https://www.instagram.com/yourprofile" target="_blank">Instagram</a>, 
                <a href="https://www.twitter.com/yourprofile" target="_blank">Twitter</a>
            </p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Payton's Deals. All rights reserved.</p>
    </footer>
</body>
</html>
