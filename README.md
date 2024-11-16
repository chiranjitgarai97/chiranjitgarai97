<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Chiranjit Garai - Festival Enthusiast</title>
<!-- Font Awesome CDN for Icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Pacifico&display=swap" rel="stylesheet">
<style>
    body {
        font-family: 'Roboto', sans-serif;
        background: url('https://source.unsplash.com/1600x900/?festival,celebration') no-repeat center center/cover;
        margin: 0;
        padding: 0;
        color: #333;
        background-attachment: fixed;
    }
    nav {
        position: sticky;
        top: 0;
        background-color: #ff7e5f;
        padding: 10px;
        text-align: center;
        z-index: 1000;
    }
    nav a {
        color: #fff;
        text-decoration: none;
        margin: 0 15px;
        font-weight: bold;
        transition: color 0.3s;
    }
    nav a:hover {
        color: #feb47b;
    }
    .container {
        max-width: 800px;
        margin: 20px auto;
        padding: 20px;
        background-color: rgba(255, 255, 255, 0.8);
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        border-radius: 10px;
        animation: fadeIn 2s;
    }
    .profile-header {
        text-align: center;
        padding: 20px;
        background: linear-gradient(135deg, #ff7e5f, #feb47b);
        color: #fff;
        border-radius: 10px 10px 0 0;
        font-family: 'Pacifico', cursive;
    }
    .profile-header h1 {
        margin: 0;
        font-size: 2.5em;
    }
    .content h2 {
        color: #ff7e5f;
    }
    .scroll-top {
        position: fixed;
        bottom: 20px;
        right: 20px;
        background-color: #ff7e5f;
        color: #fff;
        border: none;
        padding: 10px 15px;
        border-radius: 50%;
        cursor: pointer;
        display: none;
        font-size: 20px;
    }
    .scroll-top:hover {
        background-color: #feb47b;
    }
    .social-media, .contact {
        text-align: center;
        padding: 20px;
    }
    .social-media a, .contact a {
        text-decoration: none;
        color: #ffffff;
        margin: 0 10px;
        padding: 10px;
        border-radius: 50%;
        display: inline-block;
        font-size: 20px;
    }
    .facebook { background-color: #3b5998; }
    .twitter { background-color: #1da1f2; }
    .instagram { background-color: #e4405f; }
    .linkedin { background-color: #0077b5; }
    .youtube { background-color: #ff0000; }
    .whatsapp { background-color: #25d366; }
    .gmail { background-color: #d14836; }
    footer {
        text-align: center;
        padding: 20px;
        background-color: #333;
        color: #fff;
    }
    @keyframes fadeIn {
        from {opacity: 0;}
        to {opacity: 1;}
    }
</style>
</head>
<body>
    <nav>
        <a href="#about">About</a>
        <a href="#interests">Interests</a>
        <a href="#connect">Connect</a>
    </nav>

    <div class="container" id="about">
        <div class="profile-header">
            <h1>Chiranjit Garai</h1>
            <p>Festival Enthusiast & Mela Explorer</p>
        </div>
        <div class="content">
            <h2>About Me</h2>
            <p>Hello! I'm Chiranjit Garai, a passionate festival person who loves exploring different melas and festival shows. Whether it's a traditional fair, a cultural festival, or a vibrant celebration, I enjoy the atmosphere, the people, and the unique experiences each event offers.</p>
                 <button onclick="myDialog.showModal()">More</button>
            <dialog id="myDialog">
                <h4>Director Chiranjit Garai reflects on his journey at the Creative Minds of Tomorrow event at the International Film Festival of India. He describes it as a pivotal moment in his career and an opportunity to connect with fellow creators.</h4>
                <button onclick="myDialog.close()">OK</button>
            </dialog>
        </div>
    </div>

    <div class="container" id="interests">
        <h2>Interests</h2>
              <ul>
                <li>Visiting local and regional melas</li>
                <li>Exploring cultural festivals and fairs</li>
                <li>Enjoying music, dance, and live performances</li>
                <li>Tasting traditional foods and treats at events</li>
            </ul>
    </div>

    <div class="container" id="connect">
        <h2>Connect with Me</h2>
        <div class="social-media">
             <a href="https://www.facebook.com/profile.php?id=61559930538001&mibextid=ZbWKwL" class="facebook" target="_blank"><i class="fab fa-facebook-f"></i></a>
                <a href="https://www.twitter.com" class="twitter" target="_blank"><i class="fab fa-twitter"></i></a>
                <a href="https://www.instagram.com/chiranjit.official.g/profilecard/?igsh=MTJpcXlxaDNrdjl3Mg==" class="instagram" target="_blank"><i class="fab fa-instagram"></i></a>
                <a href="https://www.linkedin.com" class="linkedin" target="_blank"><i class="fab fa-linkedin-in"></i></a>
                <a href="https://youtube.com/@chiranjitgarai-k5z?si=Zu-3zM1nXYjhRfE4" class="youtube" target="_blank"><i class="fab fa-youtube"></i></a>
            </div>
            <div class="contact">
                <a href="https://whatsapp.com/channel/0029Vajj949AO7ROYmbnSu1z" class="whatsapp" target="_blank"><i class="fab fa-whatsapp"></i></a>
                <a href="chiranjit973214@gmail.com" class="gmail" target="_blank"><i class="fas fa-envelope"></i></a>
            </div>
        </div>
    </div>

    <button class="scroll-top" onclick="scrollToTop()"><i class="fas fa-chevron-up"></i></button>

    <footer>
        <p>© 2024 Chiranjit Garai - Thanks for views</p>
    </footer>

    <script>
        window.onscroll = function() {
            const scrollButton = document.querySelector('.scroll-top');
            if (document.documentElement.scrollTop > 100) {
                scrollButton.style.display = "block";
            } else {
                scrollButton.style.display = "none";
            }
        };

        function scrollToTop() {
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }
    </script>
</body>
</html>
