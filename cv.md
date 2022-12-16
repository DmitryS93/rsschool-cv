<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>CV</title>
</head>
<body class="body">
    <header class="header">
        <nav>
            <ul class="menu_box">
                <li class="menu_block">
                    <a href="#education">Education</a>
                </li>
                <li class="menu_block">
                    <a href="#experience">Experience</a>
                </li>
                <li class="menu_block">
                    <a href="#additionalinfo">Additional info</a>
                </li>
                <li class="menu_block">
                    <a href="#code">Code</a>
                </li>
                <li class="menu_block">
                    <a href="#contacts">Contacts</a>
                </li>
            </ul>
        </nav>
    </header>
    <main class="main">
        <section id="profile">
            <img class="photo" src="assets/Photo.jpg" alt="My photo">
            <h1 class="nameandsurname">Dmitry Syropiatov</h1>
        </section>
        <div class="content">
            <section class="section" id="contacts">
                <h2>Contacts</h2>
                <p>phone number: +7-981-781-XX-XX</p>
                <p>e-mail: d.siropyatov@mail.ru</p>
            </section>
            <section class="section" id="education">
                <h2>Education</h2>
                <ul>
                    <li>Peter the Great St. Petersburg Polytechnic University, Saint Petersburg, Magister of Electrotechnics</li>
                    <li>FCE certificate, Cambridge assessment, B2 English level</li>
                </ul>
            </section>
            <section class="section" id="experience">
                <h2>Experience</h2>
                <ul>
                    <li>7 years experience in the engineering and quality management</li>
                    <li>No any experience in the programming</li>
                </ul>
            </section>
            <section class="section" id="additionalinfo">
                <h2>Additional info</h2>
                <p>I am a quality engineer in the atomic industry.</p>
                <p>I wish to expand my horizons and receive new knowledge and experience.</p>
                <p>I don't have some specific skills or experience in the programming area, but I can easily adapt to changing conditions in a short time frame.</p>
                <p>I like and able to manage complex and varied tasks.</p>
            </section>
            <section class="section"  id="code">
                <h2>Code</h2>
                <h3>Example of Code</h3>
                <pre>
                    <code>
"function greetings(){<br>   let name = "DmitryS93";<br>   return 'My name is: ${name}';"
                    </code>
                </pre>
            </section>
        </div>
    </main>
    <footer class="footer">
        <a class="footer_link" href="https://github.com/DmitryS93">My GIT HUB</a>
        <div>2022</div>
        <div>
            <a class="footer_link" id="rsschoollink" href="https://rs.school/js/">RS School</a>
            <img  src="assets/RS.jpg" class="label" alt="RS School logo">
        </div>
    </footer>
</body>
</html>
