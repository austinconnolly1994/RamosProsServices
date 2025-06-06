<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ramos Professional Services</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #2e5a2e;
            color: white;
            text-align: center;
            padding: 2rem;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        header p {
            margin: 0.5rem 0;
            font-size: 1.2rem;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }
        .services, .contact {
            background: white;
            padding: 2rem;
            margin: 1rem 0;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .services h2, .contact h2 {
            color: #2e5a2e;
        }
        .contact a {
            color: #2e5a2e;
            text-decoration: none;
        }
        .contact a:hover {
            text-decoration: underline;
        }
        form {
            display: flex;
            flex-direction: column;
            max-width: 500px;
            margin-top: 1rem;
        }
        form label {
            margin: 0.5rem 0 0.2rem;
            color: #2e5a2e;
        }
        form input, form textarea {
            padding: 0.5rem;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1rem;
        }
        form textarea {
            resize: vertical;
            min-height: 100px;
        }
        form button {
            background-color: #2e5a2e;
            color: white;
            padding: 0.8rem;
            border: none;
            border-radius: 5px;
            font-size: 1.1rem;
            cursor: pointer;
            margin-top: 1rem;
        }
        form button:hover {
            background-color: #1e3a1e;
        }
        footer {
            background-color: #2e5a2e;
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        html {
            scroll-behavior: smooth;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ramos Professional Services</h1>
        <p>Tree Removal • Trimming • Shrub Trimming</p>
        <p>Est. 2014</p>
    </header>

    <div class="container">
        <section class="services">
            <h2>Our Services</h2>
            <p>We specialize in professional tree care services in Stephenville, TX. Whether you need tree removal, trimming, or shrub maintenance, we've got you covered with over a decade of experience.</p>
        </section>

        <section class="contact" id="contact">
            <h2>Contact Us</h2>
            <p><strong>Chris Ramos</strong></p>
            <p>Phone: <a href="tel:2544599549">254-459-9549</a></p>
            <p>Email: <a href="mailto:ramospro2014@gmail.com">ramospro2014@gmail.com</a></p>
            <p>Address: Stephenville, TX 76401</p>
            <h3>Request a Quote</h3>
            <form id="contact-form" action="https://formspree.io/f/xrbkeznb" method="POST">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="_replyto" required>
                <label for="phone">Phone:</label>
                <input type="tel" id="phone" name="phone">
                <label for="message">Service Needed:</label>
                <textarea id="message" name="message" required></textarea>
                <input type="hidden" name="_subject" value="Free Quote Request">
                <input type="hidden" name="_to" value="austinconnolly103@gmail.com">
                <button type="submit">Submit Quote Request</button>
            </form>
        </section>
    </div>

    <footer>
        <p>© <script>document.write(new Date().getFullYear())</script> Ramos Professional Services. All rights reserved.</p>
    </footer>
</body>
</html>
