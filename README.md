<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Portfolio</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f7f7;
            color: #333;
        }

        header {
            background: linear-gradient(to right, #ff7eb3, #ff758c);
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        header p {
            margin: 5px 0 0;
            font-size: 1.2em;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-size: 1.1em;
        }

        section {
            padding: 30px 10%;
            background: white;
            margin-bottom: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #ff758c;
            border-bottom: 2px solid #ff758c;
            display: inline-block;
            padding-bottom: 5px;
        }

        .photos {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            justify-content: center;
        }

        .photos img {
            width: 200px;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
        }

        footer {
            background-color: #ff758c;
            color: white;
            text-align: center;
            padding: 15px;
        }
    </style>
</head>
<body>

<header>
    <h1>Your Name</h1>
    <p>Actor | Model | Producer | Dreamer</p>
    <nav>
        <a href="#about">About Me</a>
        <a href="#resume">Resume</a>
        <a href="#photos">Photos</a>
        <a href="#testimonials">Testimonials</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section id="about">
    <h2>About Me</h2>
    <p>
        Welcome! I'm [Your Name], an actor, model, and producer passionate about storytelling 
        and inspiring others through my work. With a dynamic and eclectic style, I bring energy, creativity, and professionalism to every project.
    </p>
</section>

<section id="resume">
    <h2>Resume & Projects</h2>
    <p><strong>Education:</strong> Currently studying Film with an emphasis on Producing at Utah Valley University.</p>
    <p><strong>Selected Projects:</strong></p>
    <ul>
        <li>Production Assistant - BYU Short Film Production</li>
        <li>Teacher’s Assistant - Scoil Rince Ni Riada (Irish Dance)</li>
        <li>Producer - Upcoming Projects</li>
    </ul>
</section>

<section id="photos">
    <h2>Photos</h2>
    <div class="photos">
        <img src="photo1.jpg" alt="Portfolio Photo 1">
        <img src="photo2.jpg" alt="Portfolio Photo 2">
        <img src="photo3.jpg" alt="Portfolio Photo 3">
        <img src="photo4.jpg" alt="Portfolio Photo 4">
    </div>
</section>

<section id="testimonials">
    <h2>Testimonials</h2>
    <p>"[Your Name] is a joy to work with! Their creativity and professionalism shine through in every project." - [Testimonial Author]</p>
    <p>"One of the most dedicated and talented people I've had the pleasure to collaborate with!" - [Another Testimonial Author]</p>
</section>

<section id="contact">
    <h2>Contact</h2>
    <p><strong>Based in:</strong> [Your Location]</p>
    <p><strong>Email:</strong> <a href="mailto:yourname@example.com">yourname@example.com</a></p>
    <p><strong>Social Media:</strong> <a href="https://instagram.com/yourhandle">Instagram</a></p>
</section>

<footer>
    <p>&copy; 2024 [Your Name]. All Rights Reserved.</p>
</footer>

</body>
</html>
