# Site-De-Stessy
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pour Stessy</title>
    <style>
        /* Styles globaux */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }

        /* En-tête avec titre et image principale */
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 80px 20px;
        }
        header h1 {
            font-size: 3.5rem;
            font-weight: bold;
            margin: 0;
            text-transform: uppercase;
            letter-spacing: 2px;
            text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.3);
        }
        .hero-image {
            width: 100%;
            max-height: 400px;
            object-fit: cover;
            margin-top: 20px;
            border-radius: 12px;
        }

        /* Section de contenu avec texte et images */
        .content {
            padding: 40px 20px;
            text-align: center;
        }
        .content p {
            font-size: 1.2rem;
            color: #333;
            line-height: 1.6;
            margin-bottom: 40px;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }

        /* Galerie d'images */
        .image-gallery {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 40px;
        }
        .image-gallery img {
            width: 32%;
            height: auto;
            border-radius: 12px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .image-gallery img:hover {
            transform: scale(1.05);
            box-shadow: 0 12px 30px rgba(0, 0, 0, 0.2);
        }
    </style>
</head>
<body>

    <header>
         <a href="2.html"><h1>Découvrez Notre Univers</h1>
        <img src="https://cdn.discordapp.com/attachments/833730362277625906/1333449090448490596/Capture_decran_2025-01-26_020954.png?ex=6798eebd&is=67979d3d&hm=8592eceb0bc5704a8bb029374a2b21b83a2dc50d80bc458c441ba046b2193b86&" alt="Image principale" class="hero-image">
    </header>

    <div class="content">
        <P>Ma chère amie,</P>
        <p>Je voulais prendre un moment pour te dire combien je suis reconnaissante d’avoir croisé ton chemin. Depuis notre rencontre, tout semble plus lumineux et plus léger, comme si le destin nous avait réunies pour une raison bien particulière. Ton sourire, ta bienveillance et ton authenticité m’inspirent chaque jour. Je suis tellement heureuse que nos vies se soient croisées, et je me sens chanceuse d’avoir une amie comme toi à mes côtés.</p>
        <p>Merci pour ta présence, ton écoute et toutes ces petites choses que tu fais, parfois sans même t’en rendre compte, qui rendent tout plus beau autour de toi. J’ai hâte de vivre encore plein de moments avec toi et de continuer à écrire ensemble cette belle histoire de notre amitié.</p>
        <P>Avec toute ma tendresse et mon amitié,</P>

        <div class="image-gallery">
            <img src="https://media.discordapp.net/attachments/833730362277625906/1333231905323094046/Capture_decran_2025-01-26_033537.png?ex=6798cd38&is=67977bb8&hm=ad67e475d1b0385b1d17285d0896747237840f6ab834f2962f465e66dae46eb9&=&format=webp&quality=lossless" alt="Image 1">
            <img src="https://cdn.discordapp.com/attachments/833730362277625906/1333230170290655262/Capture_decran_2025-01-26_004305.png?ex=6798cb9a&is=67977a1a&hm=9fc75b2da3db9d16d56ba04a35f0e95d1af74df7c720cc3ed27fb13334c9a23d&" alt="Image 2">
            <img src="https://cdn.discordapp.com/attachments/833730362277625906/1333449901245206529/Capture_decran_2025-01-26_005131.png?ex=6798ef7e&is=67979dfe&hm=838715bd9c04b426f34198fcde522662bb2f5d008f0a436e22720e1476029398&" alt="Image 3">
        </div>
    </div>

</body>
</html>
