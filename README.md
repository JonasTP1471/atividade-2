body {
    background: url("https://www.transparenttextures.com/patterns/stardust.png"),
                linear-gradient(to bottom, #000033, #330066);
    color: #00ffea;
    font-family: "Comic Sans MS", cursive;
    margin: 20px;
    text-align: center;
}

/* TÍTULOS */
h1 {
    font-size: 50px;
    color: yellow;
    text-shadow: 4px 4px #ff00ff;
    background: linear-gradient(to right, red, orange, yellow);
    padding: 15px;
    border: 5px dashed cyan;
    animation: piscar 1s infinite alternate;
}

h2 {
    color: #ff00ff;
    background-color: black;
    border: 3px groove cyan;
    padding: 10px;
    margin-top: 30px;
    text-transform: uppercase;
}

h3 {
    color: white;
    background-color: rgba(0,0,0,0.7);
    padding: 15px;
    border-left: 5px solid lime;
    border-right: 5px solid lime;
}

/* LISTAS */
li {
    list-style: none;
    margin: 10px;
    font-size: 22px;
    color: #00ff00;
    text-shadow: 2px 2px black;
}

/* LINKS */
a {
    color: yellow;
    font-weight: bold;
    text-decoration: none;
    background-color: red;
    padding: 5px 10px;
    border: 3px outset white;
}

a:hover {
    background-color: cyan;
    color: black;
    border: 3px inset white;
}

/* TABELA */
table {
    margin: auto;
    width: 80%;
    border-collapse: collapse;
    background-color: black;
    color: white;
    box-shadow: 0 0 20px cyan;
}

th {
    background-color: purple;
    color: yellow;
    padding: 15px;
    border: 3px solid cyan;
}

td {
    padding: 12px;
    border: 2px solid white;
}

/* IMAGENS */
img {
    width: 600px;
    border: 8px ridge hotpink;
    margin: 20px;
    box-shadow: 0 0 20px yellow;
    transition: transform 0.3s;
}

img:hover {
    transform: scale(1.05) rotate(-1deg);
}

/* ANIMAÇÃO ANOS 90 */
@keyframes piscar {
    from {
        color: yellow;
        text-shadow: 0 0 10px red;
    }

    to {
        color: cyan;
        text-shadow: 0 0 20px magenta;
    }
}

/* EFEITO DE MARQUEE ANTIGO */
marquee {
    color: lime;
    font-size: 24px;
    font-weight: bold;
}

/* RODAPÉ */
footer {
    margin-top: 50px;
    padding: 20px;
    background: black;
    color: white;
    border-top: 5px double cyan;
}
