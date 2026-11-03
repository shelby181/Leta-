Pour toi mon amour 💍❤🫂
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Shelby's Universe ❤️</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background: #090909;
    color: white;
    font-family: Georgia, serif;
    line-height: 1.7;
}

header {
    text-align: center;
    padding: 65px 15px;
    background: linear-gradient(135deg, #17100d, #080808);
    border-bottom: 1px solid #b89555;
}

header h1 {
    color: #d9b66f;
    font-size: 38px;
    margin-bottom: 10px;
}

header p {
    color: #ddd;
}

nav {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 15px;
    padding: 18px 8px;
    background: #111;
    position: sticky;
    top: 0;
    z-index: 10;
}

nav a {
    color: #d9b66f;
    text-decoration: none;
    font-size: 14px;
}

section {
    padding: 45px 20px;
    max-width: 850px;
    margin: auto;
    text-align: center;
}

h2 {
    color: #d9b66f;
    margin-bottom: 20px;
}

.card {
    background: #151515;
    border: 1px solid #45351f;
    border-radius: 14px;
    padding: 22px;
    margin: 15px 0;
}

button {
    background: #c49b50;
    color: #090909;
    border: none;
    border-radius: 25px;
    padding: 12px 22px;
    margin: 10px;
    font-weight: bold;
    cursor: pointer;
}

button:hover {
    background: #f0d18b;
}

input {
    padding: 12px;
    border-radius: 8px;
    border: 1px solid #c49b50;
    background: #222;
    color: white;
    margin: 10px;
    width: 80%;
    max-width: 250px;
}

.timeline {
    border-left: 2px solid #c49b50;
    text-align: left;
    margin: 20px auto;
    max-width: 550px;
    padding-left: 20px;
}

.timeline-item {
    margin-bottom: 25px;
}

.timeline-item strong {
    color: #d9b66f;
}

.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(130px, 1fr));
    gap: 12px;
}

.gallery img {
    width: 100%;
    height: 180px;
    object-fit: cover;
    border-radius: 12px;
    border: 1px solid #c49b50;
}

.hidden {
    display: none;
}

#message, #surprise, #secretResult {
    color: #f0c8d6;
    margin: 20px auto;
    font-size: 18px;
}

footer {
    text-align: center;
    padding: 25px;
    color: #999;
    border-top: 1px solid #45351f;
}
</style>


<body>

<header>
    <h1>Shelby's Universe ❤️</h1>
    <p>Un univers fait de souvenirs, d'amour et de rêves.</p>
    <p>Bienvenue dans notre petit monde.</p>
</header>

<nav>
    <a href="#about">À propos</a>
    <a href="#gallery">Galerie</a>
    <a href="#story">Notre histoire</a>
    <a href="#messages">Messages</a>
    <a href="#surprises">Surprise</a>
</nav>

<section id="about">
    <h2>✨ Bienvenue dans mon univers</h2>
    <div class="card">
        <p>
            Certaines histoires ne sont pas écrites dans les livres.
            Elles se construisent avec des moments, des sourires,
            des souvenirs et des personnes qui deviennent spéciales.
        </p>
        <p>Voici un petit univers qui nous ressemble. ❤️</p>
    </div>
</section>

<section>
    <h2>❤️ Notre compteur</h2>
    <div class="card">
        <p>Depuis le 10 juillet 2026, notre histoire avance...</p>
        <h1 id="counter" style="color:#d9b66f;">Calcul...</h1>
        <p>jours de souvenirs et de complicité.</p>
    </div>
</section>
<section id="souvenirs">
    <h2>❤️ Nos plus beaux souvenirs</h2>

    <div class="card">
        <h3 style="color:#d9b66f;">10 juillet 2026 🥹</h3>
        <p>
            Yon jou ki te pote yon bèl chanjman.
            Yon rankont ki te vin tounen yon bèl istwa.
        </p>
    </div>

    <div class="card">
        <h3 style="color:#d9b66f;">Nos premiers échanges 💌</h3>
        <p>
            Premye mesaj yo, premye konvèsasyon yo,
            ak ti moman ki te fè nou vin pi pwòch.
        </p>
    </div>

    <div class="card">
        <h3 style="color:#d9b66f;">Des moments inoubliables ❤️</h3>
        <p>
            Gen moman ki pa bezwen foto pou yo rete
            grave nan memwa nou.
        </p>
    </div>

    <div class="card">
        <h3 style="color:#d9b66f;">À écrire ensemble ✨</h3>
        <p>
            Pi bèl souvni nou yo poko fini.
            Gen anpil lòt bèl paj ki rete pou nou ekri.
        </p>
    </div>
    
    </div>

    <p style="margin-top:15px;color:#aaa;">
        Les images sont des emplacements temporaires.
        Nous ajouterons vos vraies photos ensuite.
    </p>
   <div class="gallery">
    <img src="IMG-20261011-WA0065.jpg" onclick="agrandir(this)">
    <img src="IMG-20261011-WA0068.jpg" onclick="agrandir(this)">
    <img src="IMG-20261011-WA0071.jpg" onclick="agrandir(this)">
</div>

<div id="visionneuse" onclick="fermer()">
    <span>×</span>
    <img id="photoGrande">
</div>

<section id="story">
    <h2>📖 Notre chronologie</h2>

    <div class="timeline">

        <div class="timeline-item">
            <strong>6 juillet 2026</strong>
            <p>Le départ de Port-au-Prince.</p>
        </div>

        <div class="timeline-item">
            <strong>7 juillet 2026</strong>
            <p>L'arrivée en province.</p>
        </div>

        <div class="timeline-item">
            <strong>10 juillet 2026 ❤️</strong>
            <p>Un moment particulier qui a marqué le début de notre histoire.</p>
        </div>

        <div class="timeline-item">
            <strong>À suivre...</strong>
            <p>Parce que notre histoire continue de s'écrire.</p>
        </div>

    </div>
</section>

<section id="messages">
    <h2>💌 Un message pour toi</h2>

    <div class="card">
        <p id="message">Clique pour découvrir un message...</p>
        <button onclick="newMessage()">Découvrir un message ❤️</button>
    </div>
</section>

<section id="surprises">
    <h2>🎁 Une petite surprise</h2>

    <div class="card">
        <p>Il y a parfois des choses qu'on ne découvre qu'en ouvrant...</p>
        <button onclick="showSurprise()">Ouvrir ma surprise 🎁</button>
        <p id="surprise"></p>
    </div>
</section>

<section>
    <h2>🔐 Un petit espace secret</h2>

    <div class="card">
        <p>Entre le code pour découvrir un message spécial.</p>

        <input type="password" id="secretCode" placeholder="Code secret">

        <br>

        <button onclick="checkCode()">Déverrouiller ❤️</button>

        <p id="secretResult"></p>
    </div>
</section>

<footer>
    <p>Créé avec ❤️ par Shelby.</p>
    <p>Une histoire, des souvenirs, un univers.</p>
</footer>

<script>

// Compteur de jours
const startDate = new Date(2026, 6, 10);
const today = new Date();

const difference = today - startDate;
const days = Math.floor(difference / (1000 * 60 * 60 * 24));

document.getElementById("counter").textContent =
    days >= 0 ? days + " jours" : "Bientôt ❤️";


// Messages aléatoires
const messages = [
    "Même les journées ordinaires deviennent spéciales avec toi. ❤️",
    "Tu es une belle partie de mes souvenirs préférés.",
    "Il y a des personnes qu'on rencontre et qu'on n'oublie jamais.",
    "Mon bonheur possède parfois ton sourire. 🥹",
    "Je veux continuer à construire de beaux souvenirs avec toi.",
    "Notre histoire mérite encore beaucoup de belles pages. 💍"
];

function newMessage() {
    const random = Math.floor(Math.random() * messages.length);
    document.getElementById("message").textContent = messages[random];
}


// Boîte surprise
function showSurprise() {
    document.getElementById("surprise").textContent =
        "Surprise ! ❤️ Peu importe les kilomètres, certains liens gardent toute leur beauté. Tu es une personne précieuse.";
}


// Code secret
function checkCode() {
    const code = document.getElementById("secretCode").value;

    if (code === "1007") {
        document.getElementById("secretResult").textContent =
            "Tu as trouvé ! ❤️ Tu occupes une place spéciale dans cet univers.T'es l'unique, ma paix, ma douceur, tu représentes tout pour toi. N'oublie pas que tu es spéciale et tu as beaucoup de valeur à mes yeux, l'amour, la joie, la paix que tu m'apportes, je prêtes cette phrase que tu aimes prononcé je me sens, je me sens 🕺🕺🤗. I LOVE YOU madan maryem ❤💍.";
    } else {
        document.getElementById("secretResult").textContent =
            "Ce n'est pas le bon code. Essaie encore !";
    }
}

</script>

</body>
Nèg dous ou a 🤗
