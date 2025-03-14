# profile-card-html-css
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Card</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f4f4f4;
            margin: 0;
        }
        .card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
            text-align: center;
            width: 300px;
            transition: transform 0.3s;
        }
        .card:hover {
            transform: scale(1.05);
        }
        .profile-pic {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
        }
        .social-icons a {
            margin: 10px;
            text-decoration: none;
            font-size: 20px;
        }
    </style>
</head>
<body>
    <div class="card">
        <img src="profile.jpg" alt="Profile Picture" class="profile-pic">
        <h2>John Doe</h2>
        <h4>Web Developer</h4>
        <p>Passionate about creating interactive and user-friendly web applications.</p>
        <div class="social-icons">
            <a href="#">🔵</a>
            <a href="#">🐦</a>
            <a href="#">📸</a>
        </div>
    </div>
</body>
</html>
