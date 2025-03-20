<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Eu te amo amor, espero que goste ୨ৎ</title>
    <style>
        body {
            background-color: #ffdde1;
            font-family: 'Poppin ', sans-serif;
            text-align: center;
            padding: 20px;
            overflow: hidden;
        }
        h1 {
            color: #ff4d6d;
            font-size: 2.5em;
        }
        .message {
            background: white;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
            display: inline-block;
            max-width: 500px;
            margin-top: 20px;
        }
        .hearts {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
        }
        .heart {
            position: absolute;
            bottom: 0;
            width: 20px;
            height: 20px;
            background: red;
            clip-path: polygon(50% 0%, 100% 38%, 85% 100%, 50% 75%, 15% 100%, 0% 38%);
            animation: float 5s linear infinite;
        }
        @keyframes float {
            0% { transform: translateY(0) scale(1); opacity: 1; }
            100% { transform: translateY(-100vh) scale(0.5); opacity: 0; }
        }

    </style>
</head>
<body>
    <h1> Pour ma fille 🧸ིྀ </h1>
    <div class="message">

          <p> Hoje faz um ano que escolhemos caminhar juntas, e mesmo depois de tanto tempo, ainda fico impressionada com o quanto estar ao seu lado transforma a minha vida. Não é só sobre o amor que sinto por você – que cresce a cada dia –, mas sobre como você me ensina, me completa e me faz querer ser melhor.
            
          <P>O que vivemos nesse último ano foi muito mais do que momentos felizes. Foi sobre aprender a lidar com as diferenças, encontrar harmonia nos dias difíceis e descobrir que amar também significa estar disposta a crescer, cair e levantar juntas. Cada sorriso seu me lembra por que tudo vale a pena, e cada desafio que enfrentamos me mostra o quão forte somos como um time.
            
        <P>Eu nunca imaginei que o amor pudesse ser tão verdadeiro e, ao mesmo tempo, tão simples. Não preciso de grandes palavras ou gestos para sentir o que temos. Basta um olhar seu, um toque, ou até o silêncio confortável de quando estamos juntas. É nessa simplicidade que encontro tudo o que procuro.
            
        <p>Um ano pode parecer pouco, mas para mim é o suficiente para ter certeza de que você é a minha pessoa. Obrigada por me mostrar que o amor não é só bonito, mas também corajoso, paciente e real. E obrigada por ser você, tão única, tão linda, tão minha.
            
          <p> Que esse seja apenas o primeiro de muitos anos que ainda temos para escrever nossa história. Amo você, hoje e sempre.
            
            Com todo o meu amor,
            Isa 🤍</p>
        <iframe style="border-radius:12px" src="https://open.spotify.com/embed/track/3H3qBumaYj67PT3aMEBvAP?utm_source=generator" width="300" height="80" frameborder="0" allowfullscreen allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"></iframe>
    </div>
    
    <div class="hearts"></div>

    <script>
        function createHeart() {
            const heart = document.createElement("div");
            heart.classList.add("heart");
            heart.style.left = Math.random() * 100 + "vw";
            heart.style.animationDuration = Math.random() * 3 + 2 + "s";
            document.querySelector(".hearts").appendChild(heart);
            setTimeout(() => heart.remove(), 5000);
        }
        setInterval(createHeart, 300);
    
    </script>
</body>
</html>

<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nossas Fotos ❤︎</title>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;700&family=Poppins:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        body {
            background-color: #ffdde1;
            font-family: 'Poppins', sans-serif;
            text-align: center;
            padding: 20px;
        }
        h1 {
            color: #ff4d6d;
            font-size: 2.5em;
            font-family: 'Dancing Script', cursive;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
            margin-top: 20px;
        }
        .gallery img {
            width: 250px;
            height: auto;
            border-radius: 10px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
        }
        .button {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #ff4d6d;
            color: white;
            font-size: 1.2em;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            transition: background 0.3s;
        }
        .button:hover {
            background-color: #e63950;
        }
    </style>
</head>
<body>
    <h1>Nossas Fotos ❤︎</h1>
    <div class="gallery">
        <img src="foto1.jpg" alt="Foto 1">
        <img src="foto2.jpg" alt="Foto 2">
        <img src="foto3.jpg" alt="Foto 3">
        <img src="foto4.jpg" alt="Foto 4">
    </div>
    <br>
    <button class="button" onclick="window.location.href='index.html'">Voltar ❤︎</button>
</body>
</html>
