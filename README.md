```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>THIS IS AN HTML</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            min-height: 100vh;

            background-image:
                linear-gradient(rgba(0, 0, 0, 0.25),
                                rgba(0, 0, 0, 0.45)),
                url("https://wallpapers.com/images/hd/minecraft-landscape-of-white-mountains-v6bt1fa328lul9fg.jpg");

            background-repeat: no-repeat;
            background-attachment: fixed;
            background-size: cover;
            background-position: center;

            font-family: Arial, sans-serif;
            color: white;
        }

        /* Top bar */
        header {
            background: rgba(0, 0, 0, 0.65);
            padding: 20px 40px;

            display: flex;
            justify-content: space-between;
            align-items: center;

            border-bottom: 2px solid rgba(255, 255, 255, 0.2);
            backdrop-filter: blur(5px);
        }

        .logo {
            font-size: 25px;
            font-weight: bold;
            color: #55ff55;

            text-shadow: 3px 3px #000;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 25px;
            font-weight: bold;

            transition: 0.2s;
        }

        nav a:hover {
            color: #55ff55;
        }

        /* Main content */
        main {
            max-width: 900px;
            margin: 100px auto;
            padding: 20px;
        }

        .welcome {
            text-align: center;
            background: rgba(0, 0, 0, 0.55);

            padding: 45px;
            border-radius: 15px;

            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);

            backdrop-filter: blur(5px);
        }

        h1 {
            font-size: 55px;
            margin-top: 0;
            margin-bottom: 15px;

            color: #ffffff;
            text-shadow: 4px 4px #000;
        }

        .subtitle {
            font-size: 20px;
            color: #dddddd;
        }

        /* Cards */
        .cards {
            display: flex;
            gap: 20px;
            margin-top: 25px;
            flex-wrap: wrap;
        }

        .card {
            flex: 1;
            min-width: 250px;

            background: rgba(0, 0, 0, 0.65);
            padding: 25px;

            border-radius: 12px;

            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);

            transition: 0.25s;
        }

        .card:hover {
            transform: translateY(-5px);
            background: rgba(0, 0, 0, 0.75);
        }

        .apple {
            color: #ff4444;
            font-size: 22px;
            font-weight: bold;
        }

        .dogs {
            color: #ffffff;
            font-size: 18px;
        }

        /* Button */
        .button {
            display: inline-block;

            margin-top: 15px;
            padding: 12px 25px;

            background: #55aa55;
            color: white;

            text-decoration: none;
            font-weight: bold;

            border-radius: 6px;

            box-shadow: 0 4px 0 #336633;

            transition: 0.15s;
        }

        .button:hover {
            background: #66cc66;
            transform: translateY(-2px);
            box-shadow: 0 6px 0 #336633;
        }

        .button:active {
            transform: translateY(2px);
            box-shadow: 0 2px 0 #336633;
        }

        footer {
            text-align: center;
            margin-top: 30px;
            padding: 20px;

            color: #dddddd;
            font-size: 14px;
        }
    </style>
</head>

<body>

    <header>
        <div class="logo">⛏ MINECRAFT WORLD</div>

        <nav>
            <a href="https://www.msn.com/en-ph/news/other/ateneo-de-zamboanga-shooting-2-students-dead/ar-AA2aptbJ?ocid=BingNewsSerp"
            target="_blank">News</a> 
            <a href="https://maasincity.gov.ph/index.php/12-maasin-news/50-2022-07-05-07-06-05"
             target="_blank">Home</a>
            <a href="file:///D:/ICT-A%2011%20DANIEL%20LARSEN/BIO-DATA_LARSEN-3-DANIEL.pdf"
             target="_blank">About</a>
            <a href="https://www.typing.com/student/games"
             target="_blank">Games</a>
        </nav>
    </header>

    <main>

        <section class="welcome">
            <h1>Welcome</h1>

            <p class="subtitle">
                Welcome to my Minecraft-themed website!
            </p>

            <div class="cards">

                <div class="card">
                    <p class="apple">
                        🍎 This is an apple
                    </p>

                    <p class="dogs">
                        An apple a day keeps the dogs away.
                    </p>
                </div>

                <div class="card">
                    <p>
                        🎮 Ready to play?
                    </p>

                    <p>
                        Check out my typing trainer?!
                    </p>

                    <a
                        class="button"
                        href="file:///D:/typing-trainer-v3%20.html"
                        target="_blank">
                        Open Typing Trainer
                    </a>
                </div>

            </div>
        </section>

        <footer>
            Made with HTML & CSS ⛏️
        </footer>

    </main>

</body>
</html>
```
