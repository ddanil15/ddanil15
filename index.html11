<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Slime Monster</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap');

        body {
            margin: 0;
            font-family: 'Orbitron', sans-serif;
            background-color: #000; /* czarne tło */
            color: #00ff00; /* zielony tekst */
        }

        header {
            background-color: rgba(0,0,0,0.9);
            padding: 20px;
            text-align: center;
            border-bottom: 2px solid #00ff00;
        }

        header h1 {
            font-size: 3em;
            margin: 0;
            color: #00ff00; /* zielony nagłówek */
        }

        nav {
            margin-top: 10px;
        }

        nav a {
            color: #00ff00; /* zielone linki */
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            font-family: 'Orbitron', sans-serif;
            font-size: 1.2em;
            transition: color 0.3s, transform 0.3s;
        }

        nav a:hover {
            color: #ffffff; /* biały przy hover */
            transform: scale(1.1);
        }

        section {
            padding: 40px 20px;
            max-width: 1200px;
            margin: auto;
        }

        /* Sekcja "O nas" */
        .about {
            text-align: center;
        }

        .about h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
            color: #00ff00;
            border-bottom: 2px solid #00ff00;
            display: inline-block;
            padding-bottom: 10px;
        }

        /* Sekcja z drużyną */
        .team {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .player {
            background-color: rgba(0,0,0,0.8);
            padding: 15px;
            border-radius: 10px;
            width: 200px;
            text-align: center;
            border: 2px solid #00ff00;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .player:hover {
            transform: scale(1.05);
            box-shadow: 0 0 20px #00ff00;
        }

        .player img {
            width: 100%;
            border-radius: 50%;
            margin-bottom: 10px;
            border: 2px solid #00ff00;
        }

        /* Galeria */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .gallery img {
            width: 100%;
            border-radius: 10px;
            cursor: pointer;
            border: 2px solid #00ff00;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .gallery img:hover {
            transform: scale(1.05);
            box-shadow: 0 0 20px #00ff00;
        }

        /* Modal */
        .modal {
            display: none;
            position: fixed;
            z-index: 999;
            padding-top: 60px;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            overflow: auto;
            background-color: rgba(0,0,0,0.9);
        }

        .modal-content {
            margin: auto;
            display: block;
            max-width: 80%;
            border: 4px solid #00ff00;
            border-radius: 10px;
        }

        .close {
            position: absolute;
            top: 20px;
            right: 35px;
            color: #00ff00;
            font-size: 40px;
            font-weight: bold;
            cursor: pointer;
            transition: color 0.3s, transform 0.3s;
        }

        .close:hover {
            color: #ffffff;
            transform: scale(1.2);
        }

        /* Kontakt i Steam */
        .contact, .steam {
            background-color: rgba(0,0,0,0.8);
            padding: 20px;
            border-radius: 10px;
            border: 2px solid #00ff00;
            margin-top: 20px;
        }

        .contact h2, .steam h2 {
            color: #00ff00;
            margin-bottom: 15px;
            text-align: center;
            border-bottom: 2px solid #00ff00;
            display: inline-block;
            padding-bottom: 10px;
        }

        form {
            display: flex;
            flex-direction: column;
            max-width: 500px;
            margin: auto;
        }

        input, textarea {
            padding: 10px;
            margin-bottom: 15px;
            border: none;
            border-radius: 5px;
            background-color: #222;
            color: #00ff00;
        }

        button {
            padding: 12px;
            background-color: #00ff00;
            color: #000;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
            transition: background-color 0.3s;
        }

        button:hover {
            background-color: #00cc00;
        }

        /* Stopka */
        footer {
            background-color: rgba(0,0,0,0.9);
            text-align: center;
            padding: 20px;
            margin-top: 40px;
            border-top: 2px solid #00ff00;
            font-size: 1em;
        }

        /* Responsive */
        @media(max-width: 768px){
            header h1 {
                font-size: 2em;
            }
            .team {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Slime Monster - Drużyna Counter-Strike 2</h1>
    <nav>
        <a href="#about">O Nas</a>
        <a href="#team">Zespół</a>
        <a href="#gallery">Galeria</a>
        <a href="#videos">Nagrania</a>
        <a href="#contact">Kontakt</a>
        <a href="#steam">Steam</a>
    </nav>
</header>

<section id="about" class="about">
    <h2>O nas</h2>
    <p>Jesteśmy drużyną Counter-Strike 2 o nazwie Slime Monster. Składa się z 6 utalentowanych graczy, którzy rywalizują na najwyższym poziomie. Dołącz do nas, oglądaj nasze nagrania i kontaktuj się z nami!</p>
</section>

<section id="team">
    <h2 style="text-align:center; margin-bottom:20px; color:#00ff00;">Nasz Zespół</h2>
    <div class="team">
        <div class="player">
            <img src="https://via.placeholder.com/200x200.png?text=Gracz+1" alt="Gracz 1"/>
            <h3>Gracz 1</h3>
            <p>Role: Inżynier</p>
        </div>
        <div class="player">
            <img src="https://via.placeholder.com/200x200.png?text=Gracz+2" alt="Gracz 2"/>
            <h3>Gracz 2</h3>
            <p>Role: Snajper</p>
        </div>
        <div class="player">
            <img src="https://via.placeholder.com/200x200.png?text=Gracz+3" alt="Gracz 3"/>
            <h3>Gracz 3</h3>
            <p>Role: Rusher</p>
        </div>
        <div class="player">
            <img src="https://via.placeholder.com/200x200.png?text=Gracz+4" alt="Gracz 4"/>
            <h3>Gracz 4</h3>
            <p>Role: Support</p>
        </div>
        <div class="player">
            <img src="https://via.placeholder.com/200x200.png?text=Gracz+5" alt="Gracz 5"/>
            <h3>Gracz 5</h3>
            <p>Role: AWM</p>
        </div>
        <div class="player">
            <img src="https://via.placeholder.com/200x200.png?text=Gracz+6" alt="Gracz 6"/>
            <h3>Gracz 6</h3>
            <p>Role: Entry Fragger</p>
        </div>
    </div>
</section>

<section id="gallery">
    <h2 style="text-align:center; margin-bottom:20px; color:#00ff00;">Galeria</h2>
    <div class="gallery">
        <img src="https://via.placeholder.com/400x300.png?text=Zdjęcie+1" alt="Zdjęcie 1" onclick="openModal('img', 'https://via.placeholder.com/800x600.png?text=Zdjęcie+1')"/>
        <img src="https://via.placeholder.com/400x300.png?text=Zdjęcie+2" alt="Zdjęcie 2" onclick="openModal('img', 'https://via.placeholder.com/800x600.png?text=Zdjęcie+2')"/>
        <img src="https://via.placeholder.com/400x300.png?text=Zdjęcie+3" alt="Zdjęcie 3" onclick="openModal('img', 'https://via.placeholder.com/800x600.png?text=Zdjęcie+3')"/>
        <img src="https://via.placeholder.com/400x300.png?text=Zdjęcie+4" alt="Zdjęcie 4" onclick="openModal('img', 'https://via.placeholder.com/800x600.png?text=Zdjęcie+4')"/>
    </div>
</section>

<section id="videos">
    <h2 style="text-align:center; margin-bottom:20px; color:#00ff00;">Nagrania</h2>
    <div style="text-align:center;">
        <button onclick="openModal('video', 'https://www.youtube.com/embed/dQw4w9WgXcQ')">Oglądaj Nasze Nagranie 1</button>
        <button onclick="openModal('video', 'https://www.youtube.com/embed/3JZ_D3ELwOQ')">Oglądaj Nasze Nagranie 2</button>
    </div>
</section>

<section id="contact">
    <h2 style="text-align:center; margin-bottom:20px; color:#00ff00;">Kontakt</h2>
    <div class="contact">
        <form id="contactForm" onsubmit="return validateForm()">
            <input type="text" id="name" placeholder="Twoje imię" required />
            <input type="email" id="email" placeholder="Twój email" required />
            <textarea id="message" rows="4" placeholder="Twoja wiadomość" required></textarea>
            <button type="submit">Wyślij</button>
        </form>
        <p id="formStatus" style="margin-top:15px; text-align:center; font-weight:bold;"></p>
    </div>
</section>

<section id="steam">
    <h2 style="text-align:center; margin-bottom:20px; color:#00ff00;">Steam</h2>
    <p style="text-align:center;">
        Nasz profil Steam: <a href="https://steamcommunity.com/profiles/76561199094370719/" target="_blank" style="color:#00ff00;">tutaj</a>
    </p>
</section>

<!-- Modal -->
<div id="modal" class="modal">
    <span class="close" onclick="closeModal()">&times;</span>
    <div id="modalContent" style="text-align:center; margin-top:50px;">
        <!-- dynamic content -->
    </div>
</div>

<footer>
    &copy; 2023 Slime Monster - Counter-Strike 2 Team
</footer>

<script>
    function openModal(type, src) {
        const modal = document.getElementById('modal');
        const contentDiv = document.getElementById('modalContent');
        contentDiv.innerHTML = '';

        if (type === 'img') {
            const img = document.createElement('img');
            img.src = src;
            img.className = 'modal-content';
            contentDiv.appendChild(img);
        } else if (type === 'video') {
            const iframe = document.createElement('iframe');
            iframe.src = src;
            iframe.width = '800';
            iframe.height = '450';
            iframe.frameBorder = '0';
            iframe.allow = 'accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture';
            iframe.allowFullscreen = true;
            iframe.className = 'modal-content';
            contentDiv.appendChild(iframe);
        }

        document.getElementById('modal').style.display = 'block';
    }

    function closeModal() {
        document.getElementById('modal').style.display = 'none';
    }

    window.onclick = function(event) {
        const modal = document.getElementById('modal');
        if (event.target === modal) {
            closeModal();
        }
    }

    // Formularz kontaktowy
    function validateForm() {
        const name = document.getElementById('name').value.trim();
        const email = document.getElementById('email').value.trim();
        const message = document.getElementById('message').value.trim();
        const status = document.getElementById('formStatus');

        if (!name || !email || !message) {
            status.innerText = 'Proszę uzupełnić wszystkie pola.';
            status.style.color = '#ff0000';
            return false;
        }

        // Tu można dodać obsługę wysyłki, np. przez API lub email
        status.innerText = 'Dziękujemy za wiadomość! Skontaktujemy się z Tobą.';
        status.style.color = '#00ff00';

        // Reset formularza po wysłaniu
        document.getElementById('contactForm').reset();

        return false; // zapobiega odświeżeniu strony
    }
</script>

</body>
</html>
