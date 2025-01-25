<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Présentation</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
        }
        header {
            background-color: #6c63ff;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #4a47a3;
            padding: 0.5rem;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            padding: 0.5rem 1rem;
            border-radius: 4px;
            transition: background 0.3s;
        }
        nav a:hover {
            background-color: #6c63ff;
        }
        .container {
            max-width: 800px;
            margin: 2rem auto;
            padding: 1rem;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #6c63ff;
        }
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }
        .skill {
            background-color: #e0e7ff;
            color: #333;
            padding: 0.5rem 1rem;
            border-radius: 20px;
        }
        footer {
            text-align: center;
            margin-top: 2rem;
            font-size: 0.9rem;
            color: #555;
        }
        section {
            display: none;
        }
        section.active {
            display: block;
        }
    </style>
    <script>
        function showSection(sectionId) {
            const sections = document.querySelectorAll('section');
            sections.forEach(section => section.classList.remove('active'));
            document.getElementById(sectionId).classList.add('active');
        }
    </script>
</head>
<body>
    <header>
        <h1>Bienvenue sur mon site !</h1>
    </header>
    <nav>
        <a href="#" onclick="showSection('about')">À propos</a>
        <a href="#" onclick="showSection('skills')">Compétences</a>
        <a href="#" onclick="showSection('contact')">Contact</a>
        <a href="#" onclick="showSection('cv')">CV</a>
        <a href="#" onclick="showSection('projects')">Projets</a>
    </nav>
    <div class="container">
        <section id="about" class="active">
            <h2>À propos de moi</h2>
            <p>Bonjour ! Je m'appelle Enzo Borowec. Passionné par les systèmes complexes, électronique embarqué et réseau, je suis actuellement étudiant en 3ème année de BUT GEII.</p>
            <p>J'adore apprendre de nouvelles choses et partager mes connaissances avec les autres. Dans mon temps libre, je me consacre à la lecture de revue spatiale et je pratique également divers sports.</p>
        </section>
        <section id="skills">
            <h2>Compétences</h2>
            <div class="skills">
                <div class="skill">VHDL, C/C++, JAVA, PHYTHON</div>
                <div class="skill">SIEMENS, SCHNEIDER, DISTECH</div>
                <div class="skill">CAO carte électronique</div>
                <div class="skill">MATLAB</div>
                <div class="skill">Pack Offices et VBA</div>
                <div class="skill">Câblage et schéma électrique</div>
                <div class="skill">Gestion de projet (GANTT)</div>
                <div class="skill">Base de données</div>
                <div class="skill">Arduino, Raspberry PI, Linuxe</div>
            </div>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>Vous pouvez me contacter à l'adresse suivante :</p>
            <p><strong>Email :</strong> <a href="mailto:enzoborowec@gmail.com">enzoborowec@gmail.com</a></p>
            <p><strong>Téléphone :</strong> 0768148800</p>
        </section>
        <section id="cv">
            <h2>Mon CV</h2>
            <p>Voici un aperçu de mon parcours professionnel et éducatif :</p>
            <ul>
                <li><strong>2022 - Présent :</strong> IUT de l’Aisne - Soissons</li>
                <li><strong>04/2024 - 06/2024 :</strong> Stage à Dumortier SARL - Charmes</li>
                <li><strong>Avr. 2022 - Jui. 2022 - Août 2022 - Fév 2023 - Jui. 2023 :</strong> Animateur en accueuil de loisir</li>
                <li><strong>2023 :</strong> PSC1</li>
                <li><strong>09/2023 </strong> BAFA</li>
                <li><strong>2019 - 2022 :</strong> Bac technologique STI2D</li>
            </ul>
            <p>Pour télécharger mon CV complet, cliquez ici : <a href="https://mail-attachment.googleusercontent.com/attachment/u/0/?ui=2&ik=bb863d555a&attid=0.1&permmsgid=msg-a:r913908028248021313&th=1945fd5a0a2a9678&view=att&zw&disp=inline&saddbat=ANGjdJ-z8mLV7y6ZH_z-4vb8d9fXm-nYP0InWXYLcBD0ZcSXXlyc6Dp1Ll7AQKju0FWPZQt0wNDEZP5M-ez6DF7ZaIIGKRNCoCtoLxaa3Fk0qeZFOrlFBvhIOKb6qgEVLfKpO1-Cp_MSOxiM0RNna1ydf2iWyNhMChbnZlzxOqd1X67PCVAKYnOzNz9KKaomtmE_CIyF8nEJm2TaD6Gn3XppoU4UvKWwQrmz8vwfJQJsQ05fHfXKDJxDVyMXcoLSKXLrfQLR-XkAQhOoI41KqAMa25Ax2wd8ASWLmZ3x6x_d5zpBhhxDVw7bguGmHGGJCvr_0AYcmeX__EumxSgyaL045qO7Qlyqp3KplY1r_VqiiW-H9wRoiX80DCpMQvOjW4IXkCnFvGM9ow0phyKdosk-H7NIAR4gv2g9mnLkHZGxlI_rqSb44Rvk7U80Ne9rGaOfd2xCj78Qm4xLaRlKi4KFzpTfM0d3aM15OOSsEoa3Aaq9gYH2jvwEP9maJyQdm3a3Ie3eJmaBhveF87UGADAPGQVR-qpwEXw256GOQC8kdpQC-TvQ4HkRb8AYTziLYskYR3INJA9fJXUGcWrtWUel7RJDN8dLSvwoKKfSiyLYx5u4-jatFCNtYv35ItXJA-Zk6mhNcfFXg7j9GoDKrJsuHAhHjeodQH8Q1impKyb9cW2Q6DRuRBCs5CAIwjnpwWfB9w_Tp7xzIzCc5PQRd18cbVL7fmBV_IgoCgbyNYfNp_VOYFY5zEx3mBM5mICAqfqk2szBCCwblWIYb6fDgpI7NYH4xpivnrnb1ia1sV8YThnQvpEJEzupYuJPbNk_axJUDNMRgnN-21fXuwuGfJkdoLxNihg_NWY3biWCFc5MEUwGalyEiwOD4Ek9BILfGC2SqyncO9ffZ4lWLtc4BGbfNAqpTolxK8C62miW0q5xxf29GYu5gsYl-S26iSEhdrAKmCasBFfZ1hzy2i9tgc0aT9rqxuaNqZESdVOgkLg928BlwMrCWNxR1N26Szj5Uv_RcxIn9ND0JowSbe2j" target="_blank">Télécharger le CV</a>.</p>
        </section>
        <section id="projects">
            <h2>Projets</h2>
            <ul>
                <li><a href="link_to_project1.html" target="_blank">Projet 1 : Automatisation industrielle</a></li>
                <li><a href="link_to_project2.html" target="_blank">Projet 2 : Système embarqué</a></li>
                <li><a href="link_to_project3.html" target="_blank">Projet 3 : Gestion de base de données</a></li>
            </ul>
        </section>
    </div>
    <footer>
        <p>© 2025 Borowec. Tous droits réservés.</p>
    </footer>
</body>
</html>
