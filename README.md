<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Site com Cartões</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #0b2341;
            color: white;
        }

        header {
            padding: 30px;
            text-align: center;
            background-color: #081b33;
        }

        nav {
            padding: 15px;
            text-align: center;
            background-color: #102f55;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }

        main {
            padding: 40px;
        }

        .cartoes {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .cartao {
            background-color: white;
            color: black;
            padding: 20px;
            border-radius: 8px;
            min-height: 160px;
        }

        footer {
            margin-top: 40px;
            padding: 20px;
            text-align: center;
            background-color: #081b33;
        }

        /* Quando a tela ficar menor, organiza em 2 colunas */
        @media (max-width: 850px) {
            .cartoes {
                grid-template-columns: repeat(2, 1fr);
            }
        }
        #cartao1 {
          background:#00F4F4;
          color:#7C0000;
        }
         #cartao2 {
          background:#1D006B;
          color:#FB31D9;
        }
         #cartao3 {
          background:#04FF00;
          color:#8D5200;
        }
         #cartao4 {
          background:#FFE08C;
          color:#FF0000;
        }
         #cartao5 {
          background:#F2F200;
          color:#0800FF;
        }
        #cartao6 {
          background:#960099;
          color:#00FFEE;
        }
        #cartao7 {
          background:#FF2A00;
          color:#FF9500;
        }
        #cartao8 {
          background:#4E00CC;
          color:#91FF00;
        }
    </style>
</head>

<body>

    <header>
        <h1>Frases de Famosos!</h1>
        <p>Segua abaixo algumas frases de famosos</p>
    </header>

    <nav>
        <a href="#">Início</a>
        <a href="#">Sobre</a>
        <a href="#">Contato</a>
    </nav>

    <main>
        <div class="cartoes">

            <div class="cartao" id="cartao1">
                <h2>Albert Einstein</h2>
                <p>
                    "A imaginação é mais importante que o conhecimento." 8.21
                </p>
            </div>

            <div class="cartao" id="cartao2">
                <h2>Steve Jobs</h2>
                <p>
                    "Se você realmente olhar de perto, a maioria dos sucessos da noite para o dia demorou muito." 5.17
                </p>
            </div>

            <div class="cartao" id="cartao3">
                <h2>Oprah Winfrey</h2>
                <p>
                    "O que eu sei de verdade é: sua jornada começa com a decisão de se levantar, sair e viver plenamente." 4.58
                </p>
            </div>

            <div class="cartao" id="cartao4">
                <h2>Ayrton Senna</h2>
                <p>
                    "Vencer sem riscos é triunfar sem glória." 3.10
                </p>
            </div>

            <div class="cartao" id="cartao5">
                <h2>Renato Russo</h2>
                <p>
                    "Nunca deixe de ser você, mesmo que ser você desagrade a alguém." 7.12
                </p>
            </div>

            <div class="cartao" id="cartao6">
                <h2>Carlos Drummond de Andrade </h2>
                <p>
                    "O mundo é grande e cabe nesta janela sobre o mar.
O mar é grande e cabe na cama e no colchão de amar.
O amor é grande e cabe no breve espaço de beijar."
6
                </p>
            </div>

            <div class="cartao" id="cartao7">
                <h2>Fernando Pessoa</h2>
                <p>
                    ⁠"A vida é um hospital
Onde quase tudo falta.
Por isso ninguém se cura
E morrer é que é ter alta. 1.71
                </p>
            </div>

            <div class="cartao" id="cartao8">
                <h2>Machado de Assis </h2>
                <p>
                    "⁠Lutar. Podes escachá-los ou não; o essencial é que lutes. Vida é luta. Vida sem luta é um mar morto no centro do organismo universal." 7.52
            </div>

        </div>
    </main>

    <footer>
        <p>© 2026 - Meu Site</p>
    </footer>

</body>
</html>

