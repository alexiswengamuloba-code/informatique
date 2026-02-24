<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PLATEFORME EXAMEN - IG</title>
    <style>
        :root { 
            --blue: #0044ff; --green: #27ae60; --red: #e74c3c; 
            --yellow: #ffeb3b; --orange: #ff8c00; --soft-bg: #fdf5e6; /* Couleur Veuve (OldLace) */
        }
        
        body { 
            font-family: 'Segoe UI', Arial, sans-serif; 
            background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%); 
            min-height: 100vh; margin: 0; padding: 10px; 
            display: flex; flex-direction: column; align-items: center;
        }

        .container { 
            width: 100%; max-width: 600px; background: white; 
            padding: 15px; border-radius: 15px; box-shadow: 0 10px 30px rgba(0,0,0,0.4); 
            box-sizing: border-box; position: relative;
        }

        /* LOGO MAISON RETOUR */
        #nav-logo {
            display: none; width: 40px; height: 40px; cursor: pointer;
            position: absolute; top: 20px; left: 15px;
            background: #f0f0f0; border-radius: 8px; padding: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2); z-index: 100;
        }
        
        .case-jaune {
            background-color: var(--yellow); border: 3px solid #000;
            padding: 15px; text-align: center; margin-bottom: 20px;
            border-radius: 8px; box-shadow: 4px 4px 0px #000;
        }
        .case-jaune h1 { margin: 0; font-size: 1.4rem; color: #000; text-transform: uppercase; font-weight: 900; }

        /* STYLE BULLETIN COMMUN */
        .bulletin-paper { border: 4px double #222; padding: 15px; background: #fff; border-radius: 5px; position: relative; }
        .b-header-top { display: flex; justify-content: space-between; align-items: center; border-bottom: 2px solid #000; padding-bottom: 10px; margin-bottom: 15px; }
        .header-side { width: 75px; text-align: center; }
        .header-side img { width: 65px; height: 65px; border: 1px solid #000; object-fit: cover; border-radius: 5px; }
        .header-center { text-align: center; flex: 1; font-weight: bold; font-size: 0.75rem; padding: 0 5px; }

        .details { text-align: left; background: #f0f0f0; padding: 10px; border-radius: 5px; margin: 10px 0; font-size: 0.9rem; border: 1px solid #ddd; }
        
        /* BOX STATISTIQUES RÉUSSITE/ÉCHEC */
        .stats-box { 
            display: flex; justify-content: space-around; 
            margin: 10px 0; padding: 8px; 
            background: #fff; border: 1px solid #ddd; 
            border-radius: 5px; font-size: 0.9rem; font-weight: bold;
        }
        .stat-r { color: var(--green); }
        .stat-e { color: var(--red); }

        .msg-chef { font-style: italic; padding: 12px; background: #fffbe6; border: 1px solid #ffe58f; margin: 10px 0; font-size: 1rem; text-align: center; }
        .signature-box { border: 2px solid var(--blue); padding: 10px; color: var(--blue); font-weight: bold; width: 180px; margin: 10px auto; text-align: center; }
        .score-final { font-size: 3.5rem; font-weight: 900; color: var(--blue); text-align: center; margin-top: 10px; }

        /* BOUTONS ACTIONS */
        .bulletin-footer-btns { display: flex; justify-content: flex-end; align-items: center; gap: 15px; margin-top: 20px; }
        .btn-ok { padding: 10px 25px; background: var(--green); color: white; border: none; border-radius: 5px; font-weight: bold; cursor: pointer; }
        .btn-icon-msg { background: none; border: none; cursor: pointer; display: none; }
        .btn-icon-msg img { width: 45px; height: 45px; }

        /* STYLES EXAMEN */
        .q-card { background: #f9f9f9; padding: 15px; margin: 10px 0; border-left: 5px solid var(--blue); border-radius: 8px; }
        .opt { display: block; padding: 10px; margin: 5px 0; border: 1px solid #ddd; border-radius: 6px; cursor: pointer; background: #fff; }
        .correct { background: var(--green) !important; color: white; }
        .wrong { background: var(--red) !important; color: white; }
        .locked .opt { cursor: default; }

        input[type="text"], input[type="file"] { width: 100%; padding: 12px; margin: 8px 0; border: 1px solid #ccc; border-radius: 5px; box-sizing: border-box; }
        .btn-primary { width: 100%; padding: 15px; background: var(--blue); color: white; border: none; border-radius: 8px; font-weight: bold; cursor: pointer; }
    </style>
</head>
<body>

<div class="container">
    <img id="nav-logo" src="image/sms.png" onclick="allerAuChoix()" alt="Accueil">

    <div class="case-jaune">
        <h1>Informatique de Gestion</h1>
    </div>

    <div id="step-1">
        <h2 style="text-align:center;">INSCRIPTION ÉTUDIANT</h2>
        <input type="file" id="photo-input" accept="image/*">
        <input type="text" id="mat-input" placeholder="Matricule">
        <input type="text" id="nom-input" placeholder="Nom complet">
        <button class="btn-primary" onclick="validerInscription()">S'INSCRIRE</button>
        <h6></h6>
    </div>

    <div id="step-2" style="display:none; text-align:center;">
        <img src="image/c.jpg" style="width:100px; border:3px solid var(--blue); border-radius:50%;">
        <h2>Chef Alexis</h2>
        <p>Sélectionnez votre module :</p>
        <button class="btn-primary" style="background:#34495e; margin:5px 0;" onclick="demarrerExamen('POO')">Programmation Orientée Objet</button>
        <button class="btn-primary" style="background:#34495e; margin:8px 0;" onclick="demarrerExamen('RESEAU')">Architecture Réseaux</button>
        <button class="btn-primary" style="background:#34495e; margin:8px 0;" onclick="demarrerExamen('ALGO')">Algorithmique</button>
        <button class="btn-primary" style="background:#34495e; margin:8px 0;" onclick="demarrerExamen('PRATIQUE')">Pratique de l'Informatique</button>
    </div>

    <div id="step-3" style="display:none;">
        <div id="quiz-container"></div>
        <div id="wait-msg" style="display:none; text-align:center; padding:15px; font-weight:bold; color: var(--blue);">Analyse des résultats (3s)...</div>
        <button id="res-btn" class="btn-primary" style="display:none;" onclick="genererBulletin()">VOIR MON BULLETIN</button>
    </div>

    <div id="bulletin-zone" style="display:none;">
        <div id="bulletin-content">
            <div class="bulletin-paper" id="main-paper">
                <div id="b-header-to-copy" class="b-header-top">
                    <div class="header-side"><img src="image/c.jpg"><span>Chef Alexis</span></div>
                    <div class="header-center">RÉPUBLIQUE DÉMOCRATIQUE DU CONGO<br>
                    MINISTÈRE DE L'ENSEIGNEMENT<br><strong>BULLETIN DE L'EXAMEN</strong><br><span id="session-tag" style="color:var(--red);">Session 1</span></div>
                    <div class="header-side"><img id="bul-img" src=""><span>Étudiant</span></div>
                </div>
                <div class="details">
                    <strong>MATRICULE :</strong> <span id="bul-mat"></span><br>
                    <strong>NOM :</strong> <span id="bul-nom"></span><br>
                    <strong>MODULE :</strong> <span id="bul-mod"></span>
                </div>
                <div class="stats-box">
                    <span class="stat-r">Réussies : <span id="bul-reussies">0</span></span>
                    <span class="stat-e">Échouées : <span id="bul-echouees">0</span></span>
                </div>
                <div id="bul-msg" class="msg-chef"></div>
                <div class="signature-box" id="bul-sig">Alexis Chef<br>Informatique de Gestion</div>
                <div class="score-final" id="bul-percent"></div>
            </div>
        </div>

        <div class="bulletin-footer-btns">
            <button class="btn-ok" id="btn-recommencer" onclick="recommencerSession2()">OK</button>
            <button class="btn-icon-msg" id="btn-rattrapage" onclick="afficherRattrapage()">
                <img src="image/ame.png">
            </button>
        </div>
        <button class="btn-primary" style="margin-top:20px; background:#333;" onclick="window.location.reload()">RELOGUER</button>
    </div>
</div>

<script>
    let etudiant = { nom: "", mat: "", photo: "" };
    let score = 0, count = 0, totalQuestions = 0;
    let moduleActuel = "";
    let scoresSessions = []; 
    let sessionActuelle = 1;

    const banquesQuestions = {
        'POO': [
            { q: "La POO est basée sur :", opts: ["Fonctions", "Objets", "Tableaux", "Fichiers"], cur: 1 },
            { q: "Un objet est :", opts: ["Une classe", "Une méthode", "Une instance d’une classe", "Une variable"], cur: 2 },
            { q: "Le principe qui cache les détails internes est :", opts: ["Héritage", "Encapsulation", "Polymorphisme", "Compilation"], cur: 1 },
            { q: "Une classe sert à :", opts: ["Créer des objets", "Stocker des fichiers", "Compiler un programme", "Exécuter le code"], cur: 0 },
            { q: "L’héritage permet :", opts: ["Copier un programme", "Réutiliser le code", "Supprimer une classe", "Bloquer l’accès"], cur: 1 },
            { q: "Polymorphisme signifie :", opts: ["Plusieurs formes d’une méthode", "Une seule forme", "Une erreur", "Une variable"], cur: 0 },
            { q: "Une méthode est :", opts: ["Une action d’un objet", "Un attribut", "Une classe", "Un fichier"], cur: 0 },
            { q: "Attribut =", opts: ["Comportement", "Propriété de l’objet", "Classe", "Fonction système"], cur: 1 },
            { q: "Le constructeur sert à :", opts: ["Détruire l’objet", "Initialiser l’objet", "Compiler", "Tester"], cur: 1 },
            { q: "En Java, une classe commence par :", opts: ["function", "class", "def", "object"], cur: 1 },
            { q: "private signifie :", opts: ["Accessible partout", "Accessible dans la classe seulement", "Public", "Global"], cur: 1 },
            { q: "public signifie :", opts: ["Caché", "Accessible partout", "Privé", "Interdit"], cur: 1 },
            { q: "protected est :", opts: ["Public", "Privé", "Accessible à la classe et héritiers", "Interdit"], cur: 2 },
            { q: "Une interface contient :", opts: ["Des attributs", "Des méthodes abstraites", "Des objets", "Des fichiers"], cur: 1 },
            { q: "Abstraction sert à :", opts: ["Simplifier le code", "Le compliquer", "Supprimer les classes", "Bloquer l’accès"], cur: 0 },
            { q: "new sert à :", opts: ["Supprimer", "Créer un objet", "Tester", "Compiler"], cur: 1 },
            { q: "Une classe mère est aussi appelée :", opts: ["Sous-classe", "Super-classe", "Objet", "Méthode"], cur: 1 },
            { q: "extends sert à :", opts: ["Hériter", "Compiler", "Supprimer", "Tester"], cur: 0 },
            { q: "Un objet possède :", opts: ["Attributs et méthodes", "Seulement des méthodes", "Seulement des variables", "Rien"], cur: 0 },
            { q: "La POO améliore :", opts: ["Désordre", "Organisation du code", "Bugs", "Erreurs"], cur: 1 }
        ],
        'RESEAU': [
            { q: "Un réseau informatique est :", opts: ["Un ordinateur", "Un ensemble d’ordinateurs connectés", "Un logiciel", "Un fichier"], cur: 1 },
            { q: "LAN signifie :", opts: ["Large Area Network", "Local Area Network", "Long Access Network", "Linked Area Network"], cur: 1 },
            { q: "WAN signifie :", opts: ["Wide Area Network", "Web Access Network", "Wireless Area Network", "World Area Network"], cur: 0 },
            { q: "Internet est :", opts: ["Un LAN", "Un WAN", "Un logiciel", "Un serveur"], cur: 1 },
            { q: "Adresse IP sert à :", opts: ["Identifier une machine", "Installer un logiciel", "Supprimer un fichier", "Protéger un virus"], cur: 0 },
            { q: "IPv4 contient :", opts: ["16 bits", "32 bits", "64 bits", "128 bits"], cur: 1 },
            { q: "IPv6 contient :", opts: ["32 bits", "64 bits", "128 bits", "256 bits"], cur: 2 },
            { q: "Un routeur sert à :", opts: ["Relier des réseaux", "Créer des fichiers", "Stocker des données", "Imprimer"], cur: 0 },
            { q: "Un switch fonctionne sur :", opts: ["Couche réseau", "Couche liaison de données", "Couche application", "Couche transport"], cur: 1 },
            { q: "Le modèle OSI a :", opts: ["5 couches", "6 couches", "7 couches", "8 couches"], cur: 2 },
            { q: "HTTP est :", opts: ["Protocole web", "Adresse IP", "Routeur", "Switch"], cur: 0 },
            { q: "FTP sert à :", opts: ["Transférer des fichiers", "Naviguer", "Sécuriser", "Imprimer"], cur: 0 },
            { q: "DNS sert à :", opts: ["Traduire nom → IP", "Sécuriser", "Stocker", "Supprimer"], cur: 0 },
            { q: "Le câble RJ45 est :", opts: ["Fibre", "Ethernet", "Coaxial", "USB"], cur: 1 },
            { q: "Wi-Fi est :", opts: ["Filaire", "Sans fil", "Câble", "Fibre"], cur: 1 },
            { q: "Bluetooth est :", opts: ["Réseau longue distance", "Réseau courte distance", "WAN", "LAN étendu"], cur: 1 },
            { q: "Pare-feu sert à :", opts: ["Protéger le réseau", "Créer un virus", "Accélérer l’ordi", "Installer Windows"], cur: 0 },
            { q: "Serveur est :", opts: ["Client", "Fournisseur de services", "Câble", "Routeur"], cur: 1 },
            { q: "Client est :", opts: ["Celui qui demande un service", "Serveur", "Routeur", "Switch"], cur: 0 },
            { q: "Réseau en étoile utilise :", opts: ["Un hub central", "Plusieurs hubs", "Aucun centre", "Internet"], cur: 0 }
        ],
        'ALGO': [
            { q: "Un algorithme est :", opts: ["Un langage", "Une suite d’instructions", "Un logiciel", "Un ordinateur"], cur: 1 },
            { q: "Début et Fin servent à :", opts: ["Décorer", "Délimiter l’algorithme", "Compiler", "Supprimer"], cur: 1 },
            { q: "Une variable sert à :", opts: ["Stocker une valeur", "Exécuter", "Imprimer", "Supprimer"], cur: 0 },
            { q: "Si…Alors est :", opts: ["Une boucle", "Une condition", "Une variable", "Un tableau"], cur: 1 },
            { q: "TantQue est :", opts: ["Condition", "Boucle", "Variable", "Constante"], cur: 1 },
            { q: "Pour est :", opts: ["Condition", "Boucle", "Variable", "Tableau"], cur: 1 },
            { q: "Lire sert à :", opts: ["Afficher", "Entrer une donnée", "Supprimer", "Calculer"], cur: 1 },
            { q: "Écrire sert à :", opts: ["Entrer", "Afficher", "Calculer", "Supprimer"], cur: 1 },
            { q: "Variable entière est :", opts: ["Texte", "Nombre sans virgule", "Décimal", "Booléen"], cur: 1 },
            { q: "Variable réelle est :", opts: ["Texte", "Entier", "Décimal", "Logique"], cur: 2 },
            { q: "Booléen a :", opts: ["3 valeurs", "2 valeurs (Vrai/Faux)", "Plusieurs", "Aucune"], cur: 1 },
            { q: "Tableau est :", opts: ["Variable simple", "Ensemble de variables", "Condition", "Boucle"], cur: 1 },
            { q: "Indice commence souvent à :", opts: ["1", "0", "2", "5"], cur: 1 },
            { q: "FinSi termine :", opts: ["Boucle", "Condition", "Algorithme", "Variable"], cur: 1 },
            { q: "FinPour termine :", opts: ["Condition", "Boucle Pour", "Algorithme", "Variable"], cur: 1 },
            { q: "FinTantQue termine :", opts: ["Condition", "Boucle TantQue", "Variable", "Tableau"], cur: 1 },
            { q: "Algorithme sert à :", opts: ["Programmer correctement", "Jouer", "Naviguer", "Supprimer"], cur: 0 },
            { q: "Ordre logique est :", opts: ["Important", "Facultatif", "Inutile", "Aléatoire"], cur: 0 },
            { q: "Un test logique retourne :", opts: ["Nombre", "Texte", "Vrai ou Faux", "Image"], cur: 2 },
            { q: "Algorithme est indépendant de :", opts: ["Langage de programmation", "Logique", "Données", "Instructions"], cur: 0 }
        ],
        'PRATIQUE': [
            { q: "Un ordinateur sert à :", opts: ["Calculer et traiter l’information", "Dormir", "Marcher", "Parler"], cur: 0 },
            { q: "CPU signifie :", opts: ["Central Processing Unit", "Computer Power Unit", "Control Program Unit", "Central Program User"], cur: 0 },
            { q: "RAM est :", opts: ["Mémoire temporaire", "Mémoire permanente", "Disque dur", "Clavier"], cur: 0 },
            { q: "Disque dur sert à :", opts: ["Stocker durablement", "Calculer", "Afficher", "Imprimer"], cur: 0 },
            { q: "Clavier est :", opts: ["Sortie", "Entrée", "Stockage", "Réseau"], cur: 1 },
            { q: "Souris est :", opts: ["Entrée", "Sortie", "Stockage", "Réseau"], cur: 0 },
            { q: "Écran est :", opts: ["Entrée", "Sortie", "Stockage", "Réseau"], cur: 1 },
            { q: "Imprimante est :", opts: ["Entrée", "Sortie", "Stockage", "Réseau"], cur: 1 },
            { q: "Windows est :", opts: ["Matériel", "Système d’exploitation", "Antivirus", "Navigateur"], cur: 1 },
            { q: "Linux est :", opts: ["Virus", "OS", "Navigateur", "Pilote"], cur: 1 },
            { q: "Word sert à :", opts: ["Tableur", "Traitement de texte", "Présentation", "Base de données"], cur: 1 },
            { q: "Excel sert à :", opts: ["Texte", "Calculs et tableaux", "Images", "Vidéos"], cur: 1 },
            { q: "PowerPoint sert à :", opts: ["Calculer", "Présenter", "Programmer", "Naviguer"], cur: 1 },
            { q: "Navigateur web sert à :", opts: ["Installer Windows", "Aller sur Internet", "Programmer", "Supprimer"], cur: 1 },
            { q: "Chrome est :", opts: ["OS", "Navigateur", "Antivirus", "Langage"], cur: 1 },
            { q: "Dossier sert à :", opts: ["Classer les fichiers", "Calculer", "Naviguer", "Programmer"], cur: 0 },
            { q: "Copier permet de :", opts: ["Déplacer", "Dupliquer", "Supprimer", "Renommer"], cur: 1 },
            { q: "Supprimer efface :", opts: ["Définitivement", "Le fichier", "Le système", "Internet"], cur: 1 },
            { q: "Antivirus sert à :", opts: ["Créer virus", "Protéger l’ordinateur", "Programmer", "Naviguer"], cur: 1 },
            { q: "Informatique est :", opts: ["Science du traitement automatique de l’information", "Jeu", "Machine", "Internet"], cur: 0 }
        ]
    };

    function validerInscription() {
        etudiant.nom = document.getElementById('nom-input').value;
        etudiant.mat = document.getElementById('mat-input').value;
        const file = document.getElementById('photo-input').files[0];
        if(!etudiant.nom || !etudiant.mat) return alert("Champs obligatoires !");
        
        if(file) {
            const reader = new FileReader();
            reader.onload = (e) => { etudiant.photo = e.target.result; allerAuChoix(); };
            reader.readAsDataURL(file);
        } else {
            etudiant.photo = "https://via.placeholder.com/70";
            allerAuChoix();
        }
    }

    function allerAuChoix() {
        document.getElementById('step-1').style.display = 'none';
        document.getElementById('step-3').style.display = 'none';
        document.getElementById('bulletin-zone').style.display = 'none';
        document.getElementById('step-2').style.display = 'block';
        document.getElementById('nav-logo').style.display = 'block';
    }

    function demarrerExamen(code) {
        score = 0; count = 0;
        moduleActuel = code;
        let questions = [...banquesQuestions[code]];
        totalQuestions = questions.length;

        if(sessionActuelle === 2) {
            let q1 = questions.shift(); 
            questions.splice(1, 0, q1); 
        }

        document.getElementById('step-2').style.display = 'none';
        document.getElementById('step-3').style.display = 'block';
        document.getElementById('res-btn').style.display = 'none';
        document.getElementById('nav-logo').style.display = 'none';
        
        const container = document.getElementById('quiz-container');
        container.innerHTML = `<h2 style="text-align:center;">${code} (Session ${sessionActuelle})</h2>`;
        
        questions.forEach((qObj, index) => {
            let div = document.createElement('div');
            div.className = "q-card";
            let optionsHtml = qObj.opts.map((opt, i) => 
                `<span class="opt" onclick="check(this, ${i === qObj.cur})">${String.fromCharCode(65 + i)}. ${opt}</span>`
            ).join('');
            div.innerHTML = `<p><strong>${index + 1}. ${qObj.q}</strong></p>${optionsHtml}`;
            container.appendChild(div);
        });
    }

    function check(el, isCorrect) {
        if(el.parentElement.classList.contains('locked')) return;
        if(isCorrect) { el.classList.add('correct'); score++; } else { el.classList.add('wrong'); }
        el.parentElement.classList.add('locked');
        count++;
        
        if(count === totalQuestions) {
            document.getElementById('wait-msg').style.display = 'block';
            setTimeout(() => {
                document.getElementById('wait-msg').style.display = 'none';
                document.getElementById('res-btn').style.display = 'block';
            }, 3000);
        }
    }

    function genererBulletin() {
        document.getElementById('step-3').style.display = 'none';
        document.getElementById('bulletin-zone').style.display = 'block';
        document.getElementById('nav-logo').style.display = 'block';

        let pc = Math.round((score / totalQuestions) * 100);
        document.getElementById('bul-mat').innerText = etudiant.mat;
        document.getElementById('bul-nom').innerText = etudiant.nom;
        document.getElementById('bul-mod').innerText = moduleActuel;
        document.getElementById('bul-percent').innerText = pc + "%";
        document.getElementById('bul-img').src = etudiant.photo;
        document.getElementById('session-tag').innerText = "Session " + sessionActuelle;
        
        // Stats
        document.getElementById('bul-reussies').innerText = score;
        document.getElementById('bul-echouees').innerText = totalQuestions - score;
        document.getElementById('bul-msg').innerText = pc < 50 ? "Ce que tu fais pour le moment est très faible, l'exament est en dessous de la moyenne. Mais un jour, tu pourras continuer à étudier l'informatique et tu réussiras.": "Félicitations ! Tu as réussi avec une mention satisfaisante. Continue tes efforts pour viser l'excellence.";
    }

    function recommencerSession2() {
        scoresSessions.push(Math.round((score / totalQuestions) * 100));
        sessionActuelle = 2;
        allerAuChoix();
        document.getElementById('btn-recommencer').style.display = 'none';
        document.getElementById('btn-rattrapage').style.display = 'block';
    }

    function afficherRattrapage() {
        let pcS2 = Math.round((score / totalQuestions) * 100);
        if(scoresSessions.length === 1) scoresSessions.push(pcS2);

        let moyenne = Math.round((scoresSessions[0] + scoresSessions[1]) / 2);
        let zone = document.getElementById('bulletin-content');
        let headerHtml = document.getElementById('b-header-to-copy').innerHTML;
        
        let messageFinal = moyenne < 50 ? "Tu repasses encore l’examen, mais tu es vraiment nul." : "Tu t’es bien travail jusqu’à la deuxième session, félicitations.";
        let colorFinal = moyenne < 50 ? "#0044ff" : "green";

        zone.innerHTML = `
            <div class="bulletin-paper" style="border-color: var(--orange); background-color: var(--soft-bg);">
                <div class="b-header-top">${headerHtml}</div>
                <h3 style="text-align:center; color: var(--orange); text-decoration: underline;">BULLETIN DE RATTRAPAGE</h3>
                <div class="details" style="background: #fff; border-color: var(--orange);">
                    <strong>Examen Session 1 :</strong> ${scoresSessions[0]}%<br>
                    <strong>Examen Session 2 :</strong> ${scoresSessions[1]}%<br>
                    <hr style="border: 0.5px dashed var(--orange)">
                    <strong>MOYENNE :</strong> (${scoresSessions[0]} + ${scoresSessions[1]}) ÷ 2 = <strong>${moyenne}%</strong>
                </div>
                <div class="stats-box" style="border-color: var(--orange);">
                    <span>Dernier Essai : </span>
                    <span class="stat-r">R: ${score}</span>
                    <span class="stat-e">E: ${totalQuestions - score}</span>
                </div>
                <div class="score-final" style="color: var(--orange)">${moyenne}%</div>
                <div style="color:${colorFinal}; font-weight:bold; text-align:center; font-style:italic; margin-top:15px; border-top: 1px solid rgba(0,0,0,0.1); padding-top:10px;">
                    "${messageFinal}"
                </div>
                <div class="signature-box" style="margin-top:20px; border-color: var(--orange); color: var(--orange);">Alexis Chef<br>Informatique de Gestion</div>
            </div>
        `;
        
        zone.querySelector('#session-tag').innerText = "Rattrapage";
        zone.querySelector('#session-tag').style.color = "var(--orange)";
        document.getElementById('btn-rattrapage').style.display = 'none';
    }
</script>

</body>
</html>

