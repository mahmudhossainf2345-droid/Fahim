# Fahim
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mahmud Hossain Fahim | Guitarist & Student</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            color: #333;
            background-color: #f0f2f5;
        }

        /* Navigation */
        nav {
            background: #1a1a1a;
            color: white;
            padding: 1rem;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        /* Hero Section */
        .hero {
            height: 50vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1510915361894-db8b60106cb1?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            padding: 0 20px;
        }

        .hero h1 { font-size: 3rem; margin: 0; text-transform: uppercase; letter-spacing: 2px; }
        .hero p { font-size: 1.2rem; margin-top: 10px; opacity: 0.9; }

        /* Container */
        .container {
            max-width: 800px;
            margin: -50px auto 2rem auto;
            padding: 0 1.5rem;
        }

        .section {
            background: white;
            padding: 2.5rem;
            margin-bottom: 1.5rem;
            border-radius: 12px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
        }

        h2 { color: #2d3436; border-left: 5px solid #0984e3; padding-left: 15px; margin-top: 0; }

        /* Profile Details */
        .details-list { list-style: none; padding: 0; }
        .details-list li { margin-bottom: 12px; font-size: 1.1rem; }
        .details-list strong { color: #0984e3; }

        /* Social/Contact Buttons */
        .btn {
            display: inline-block;
            padding: 12px 25px;
            margin: 10px 5px 0 0;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
            transition: transform 0.2s, background 0.2s;
        }

        .btn-fb { background: #1877F2; color: white; }
        .btn-email { background: #d63031; color: white; }
        .btn:hover { transform: translateY(-3px); opacity: 0.9; }

        footer { text-align: center; padding: 3rem 1rem; color: #636e72; font-size: 0.9rem; }
    </style>
</head>
<body>

    <nav>
        <strong>MAHMUD HOSSAIN FAHIM</strong>
    </nav>

    <header class="hero">
        <h1>I'm Fahim</h1>
        <p>Student • Guitarist • Music Lover</p>
    </header>

    <div class="container">
        <section class="section">
            <h2>About Me</h2>
            <p>Hello! My name is <strong>Mahmud Hossain Fahim</strong>. I am an 18-year-old student with a deep passion for music. When I'm not studying, you'll usually find me with a guitar in my hands exploring new melodies and rhythms.</p>
        </section>

        <section class="section">
            <h2>Quick Info</h2>
            <ul class="details-list">
                <li><strong>Age:</strong> 18 Years</li>
                <li><strong>Education:</strong> Student</li>
                <li><strong>Hobby:</strong> Playing Guitar</li>
                <li><strong>Phone:</strong> 01753417033</li>
            </ul>
        </section>

        <section id="contact" class="section">
            <h2>Connect With Me</h2>
            <p>Feel free to reach out to me for music collaborations or just a friendly chat!</p>
            
            <a href="https://www.facebook.com/share/1DNtq7R4di/" target="_blank" class="btn btn-fb">Facebook Profile</a>
            <a href="mailto:mahmudhossainf2345@gmail.com" class="btn btn-email">Send Email</a>
        </section>
    </div>

    <footer>
        <p>&copy; 2026 Mahmud Hossain Fahim. All rights reserved.</p>
    </footer>

</body>
</html>
