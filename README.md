# Site-de-jogo/PAGINA-PRINCIPAL
Projeto com finalidade de treinar o html, css e JS


<!DOCTYPE html>
<html lang="PT-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VALHALLA</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="title">
            <h1>PREPARE-SE PARA A BATALHA</h1>
            <img class="img" src="pixil-frame-0.png" alt="Ícone do Valhalla">
        </div>
    </header>
    
    <main>
        <article class="presentation">
            <p>É um servidor alternativo de Tibia focado em PvP, sua honra só vem através do sangue inimigo! Construa seu legado usando os corpos de seus rivais como tijolos. E que ao longo dessa sua grande jornada, Odin esteja contigo!</p>
        </article>
        
        <img class="gif" src="https://i.redd.it/hy29wm3203jb1.gif" alt="imagem de tibia">
    
        <div id="main-content">  </div>

        <nav>
         
            <div class="container">
                <a href="#" class="buttonum"> LOGIN </a>
                <a href="#" class="sub-button"> CREATE ACCOUNT </a>
                <a href="#" class="button" > DOWNLOAD </a>
            </div>


            <ul class="side_menu">
                <li>
                    <a href="javascript:void(0)" class="menu-link">NEWS</a>
                    <ul class="submenu submenu_acc">
                        <li><a href="#" class="last-news" data-page="last-news">Last News</a></li>
                        <li><a href="#" class="events" data-page="events">Events</a></li>
                    </ul>
                </li>
                
                <li>
                    <a href="javascript:void(0)" class="menu-link">COMMUNITY</a>
                    <ul class="submenu submenu_download">
                        <li><a href="#" class="highscores" data-page="highscores">Highscores</a></li>
                        <li><a href="#" class="characters" data-page="cadastro">Characters</a></li>
                    </ul>
                </li>
                
                <li>
                    <a href="javascript:void(0)" class="menu-link">SUPPORT</a>
                    <ul class="submenu submenu_forum">
                        <li><a href="#staff" class="staff" data-page="staff">Staff</a></li>
                        <li><a href="#rules" class="rules" data-page="rules">Rules</a></li>
                    </ul>
                </li>
                
                <li>
                    <a href="javascript:void(0)" class="menu-link" data-page="about">ABOUT</a>
                </li>
            </ul>
        </nav>
    
        <section class="notes">
            <h2>NOTÍCIAS</h2>
            <p>Fique por dentro das atualizações do servidor!</p>
        </section>
    </main>

    <footer>
        <p>&copy; VALHALLA - DIREITOS RESERVADOS.</p>
    </footer>

    <script src="accScript.js"></script>
    <script src="jsOt.js"></script>

</body>
</html>
