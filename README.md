# Portofolio1
The is portofolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }

        header {
            background-color: #007ACC;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }

        h1 {
            margin: 0;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
        }

        .project {
            margin: 20px 0;
            padding: 10px;
            border: 1px solid #ddd;
        }
    </style>
</head>
<body>
    <header>
        <h1>My Software Developer Portfolio</h1>
    </header>
    <div class="container">
        <h2>About Me</h2>
        <p>
            I am a passionate software developer with a love for coding. I have experience in web development, mobile app development, and more.
        </p>

        <h2>My Projects</h2>
        <div class="project">
            <h3>Project 1: Awesome Website</h3>
            <p>A description of the first project.</p>
        </div>
        <div class="project">
            <h3>Project 2: Cool Mobile App</h3>
            <p>A description of the second project.</p>
        </div>

        <h2>Contact Me</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name"><br><br>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email"><br><br>

            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="4" cols="50"></textarea><br><br>

            <input type="submit" value="Submit">
        </form>
    </div>

    <script>
        // JavaScript code can go here for interactivity
        // For example, you can validate the form data or add dynamic behavior.
    </script>
</body>
</html>
