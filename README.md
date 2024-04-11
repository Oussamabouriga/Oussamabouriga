<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohamed Oussama Bouriga's Profile</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        .container {
            max-width: 800px;
            margin: auto;
            overflow: hidden;
            padding: 0 20px;
        }

        h1, h3 {
            text-align: center;
            line-height: 1.5;
        }

        .profile-stats img, .skills img {
            transition: transform 0.2s;
        }

        .profile-stats img:hover, .skills img:hover {
            transform: scale(1.1);
        }

        .skills, .social-links {
            display: flex;
            justify-content: center;
            list-style: none;
            padding: 0;
        }

        .skills li, .social-links li {
            margin: 10px;
        }

        .social-links a {
            display: inline-block;
            height: 40px;
            width: 40px;
            overflow: hidden;
        }

        .social-links img, .skills img {
            max-width: 100%;
            height: auto;
            display: block;
        }

        .footer {
            text-align: center;
            padding: 20px;
            color: #777;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Hi 👋, I'm Mohamed Oussama Bouriga</h1>
    <h3>A passionate Mobile Developer from Tunisia</h3>

    <div class="profile-stats">
        <img src="https://komarev.com/ghpvc/?username=oussamabouriga&label=Profile%20views&color=0e75b6&style=flat" alt="profile views">
    </div>

    <p>🔭 I’m currently working on <strong>Soullift</strong></p>
    <p>📫 How to reach me: <strong>oussamabouriga3@gmail.com</strong></p>

    <h3>Connect with me:</h3>
    <ul class="social-links">
        <li>
            <a href="https://linkedin.com/in/oussama bouriga" target="_blank">
                <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn">
            </a>
        </li>
        <!-- Add more social links as needed -->
    </ul>

    <h3>Languages and Tools:</h3>
    <ul class="skills">
        <!-- Replace 'YourSkillIcon.svg' with your actual skill icons -->
        <li><img src="YourSkillIcon.svg" alt="Skill Name" title="Skill Name"></li>
        <!-- Add more skills as needed -->
    </ul>

    <div class="footer">
        <p>Thank you for visiting my profile!</p>
    </div>
</div>

</body>
</html>
