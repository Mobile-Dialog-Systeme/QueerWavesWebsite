<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Podcast Übersicht - Queer Waves Corpus</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f5f5f5;
            color: #333;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0,0,0,0.1);
        }
        
        h1 {
            color: #2c3e50;
            text-align: center;
            margin-bottom: 30px;
            border-bottom: 3px solid #3498db;
            padding-bottom: 10px;
        }
        
        .summary {
            background: #ecf0f1;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 30px;
            text-align: center;
        }
        
        .summary h2 {
            margin: 0 0 10px 0;
            color: #2c3e50;
        }
        
        .stats {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 20px;
        }
        
        .stat-item {
            text-align: center;
        }
        
        .stat-number {
            font-size: 2em;
            font-weight: bold;
            color: #3498db;
        }
        
        .podcast-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
            gap: 25px;
            margin-top: 30px;
        }
        
        .podcast-card {
            border: 1px solid #ddd;
            border-radius: 12px;
            padding: 20px;
            background: white;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            transition: transform 0.2s, box-shadow 0.2s;
        }
        
        .podcast-card:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 12px rgba(0,0,0,0.15);
        }
        
        .podcast-card.error {
            border-color: #e74c3c;
            background: #fdf2f2;
        }
        
        .podcast-header {
            display: flex;
            align-items: flex-start;
            gap: 15px;
            margin-bottom: 15px;
        }
        
        .podcast-image {
            width: 80px;
            height: 80px;
            border-radius: 8px;
            object-fit: cover;
            border: 2px solid #ddd;
        }
        
        .podcast-image.placeholder {
            background: #95a5a6;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-weight: bold;
            font-size: 12px;
        }
        
        .podcast-title {
            flex: 1;
        }
        
        .podcast-title h3 {
            margin: 0 0 5px 0;
            color: #2c3e50;
            font-size: 1.3em;
        }
        
        .podcast-author {
            color: #7f8c8d;
            font-size: 0.9em;
            margin: 0;
        }
        
        .podcast-description {
            color: #555;
            margin-bottom: 15px;
            line-height: 1.5;
        }
        
        .podcast-stats {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 10px;
            font-size: 0.9em;
        }
        
        .stat-row {
            display: flex;
            justify-content: space-between;
            padding: 5px 0;
            border-bottom: 1px solid #ecf0f1;
        }
        
        .stat-label {
            font-weight: bold;
            color: #7f8c8d;
        }
        
        .stat-value {
            color: #2c3e50;
        }
        
        .error-message {
            color: #e74c3c;
            font-style: italic;
            text-align: center;
            padding: 10px;
        }
        
        .footer {
            text-align: center;
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid #ddd;
            color: #7f8c8d;
        }
        
        @media (max-width: 768px) {
            .container {
                padding: 15px;
            }
            
            .podcast-grid {
                grid-template-columns: 1fr;
            }
            
            .stats {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🎙️ Queer Waves Podcast Corpus - Übersicht</h1>
        
        <div class="summary">
            <h2>Zusammenfassung</h2>
            <div class="stats">
                <div class="stat-item">
                    <div class="stat-number">12</div>
                    <div>Podcasts</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">1064</div>
                    <div>Gesamt-Episoden</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">12</div>
                    <div>Erfolgreich geladen</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">0</div>
                    <div>Fehler</div>
                </div>
            </div>
        </div>
        
        <div class="podcast-grid">

            <div class="podcast-card ">
                <div class="podcast-header">
                    <img src="podcast_images/Bootycall.jpg" alt="030-Bootycall: Der etwas andere Berlin-Dating-Podcast" class="podcast-image">
                    <div class="podcast-title">
                        <h3>030-Bootycall: Der etwas andere Berlin-Dating-Podcast</h3>
                        <p class="podcast-author">030 Bootycall</p>
                    </div>
                </div>
                
                <div class="podcast-description">
                    Willkommen in Berlin, der Hauptstadt der Singles. In diesem Berlin-Podcast geht es ordentlich zur Sache. Gastgeber Caramel Mafia hat in jeder Folge ein spannendes Date und Ihr seid live dabei. Ganz egal ob Horrordate, Sexpanne oder vorgetäuschter Orgasmus von Männern - hier wird kein Blatt vor de...
                </div>
                
                
                
                <div class="podcast-stats">
                    <div class="stat-row">
                        <span class="stat-label">Episoden:</span>
                        <span class="stat-value">41</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Kategorie:</span>
                        <span class="stat-value">Unbekannt</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Start:</span>
                        <span class="stat-value">25.04.2019</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Ende:</span>
                        <span class="stat-value">26.03.2025</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Sprache:</span>
                        <span class="stat-value">de</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Base Name:</span>
                        <span class="stat-value">Bootycall</span>
                    </div>
                </div>
            </div>

            <div class="podcast-card ">
                <div class="podcast-header">
                    <img src="podcast_images/Auf-eine-Tüte.jpg" alt="Auf eine Tüte" class="podcast-image">
                    <div class="podcast-title">
                        <h3>Auf eine Tüte</h3>
                        <p class="podcast-author">Hengameh</p>
                    </div>
                </div>
                
                <div class="podcast-description">
                    Let's talk about bags, baby! In diesem Potcast heißt es: Abhängen mit der High Society. Jede Folge trifft Hengameh eine beeindruckende Person aus Popkultur und Politik auf eine Tüte. Den Inhalt dieser Tüte bringen die Gäste mit, schließlich packen sie aus ihrem Innersten aus. Welchen Emotional Ba...
                </div>
                
                
                
                <div class="podcast-stats">
                    <div class="stat-row">
                        <span class="stat-label">Episoden:</span>
                        <span class="stat-value">61</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Kategorie:</span>
                        <span class="stat-value">Unbekannt</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Start:</span>
                        <span class="stat-value">18.04.2020</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Ende:</span>
                        <span class="stat-value">28.11.2021</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Sprache:</span>
                        <span class="stat-value">de</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Base Name:</span>
                        <span class="stat-value">Auf eine Tüte</span>
                    </div>
                </div>
            </div>

            <div class="podcast-card ">
                <div class="podcast-header">
                    <img src="podcast_images/BBQ-Der-Black-Brown-Queere-Podcast.jpg" alt="BBQ – Der Black Brown Queere Podcast von COSMO" class="podcast-image">
                    <div class="podcast-title">
                        <h3>BBQ – Der Black Brown Queere Podcast von COSMO</h3>
                        <p class="podcast-author">COSMO</p>
                    </div>
                </div>
                
                <div class="podcast-description">
                    Black! Brown! Queer! Mehr BIPoC und queere Perspektiven im öffentlichen Diskurs: Alle zwei Wochen besprechen die Hosts Zuher Jazmati und Dominik Djialeu Themen, die sie oder die Welt gerade bewegen.
                </div>
                
                
                
                <div class="podcast-stats">
                    <div class="stat-row">
                        <span class="stat-label">Episoden:</span>
                        <span class="stat-value">66</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Kategorie:</span>
                        <span class="stat-value">Society & Culture</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Start:</span>
                        <span class="stat-value">06.09.2022</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Ende:</span>
                        <span class="stat-value">05.12.2024</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Sprache:</span>
                        <span class="stat-value">de</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Base Name:</span>
                        <span class="stat-value">BBQ – Der Black Brown Queere Podcast</span>
                    </div>
                </div>
            </div>

            <div class="podcast-card ">
                <div class="podcast-header">
                    <img src="podcast_images/Böttinger-Wohnung-17.jpg" alt="Böttinger. Wohnung 17" class="podcast-image">
                    <div class="podcast-title">
                        <h3>Böttinger. Wohnung 17</h3>
                        <p class="podcast-author">WDR 2</p>
                    </div>
                </div>
                
                <div class="podcast-description">
                    Inwieweit bestimmt unser Geschlecht unsere Identität und unseren Lebensweg? Das möchte ich herausfinden. Ich bin Bettina Böttinger. Ich bin selbst queer und kämpfe für die gesellschaftliche Akzeptanz verschiedener Lebensentwürfe. In diesem Podcast lade ich Menschen zu mir nach Hause ein. Ich möch...
                </div>
                
                
                
                <div class="podcast-stats">
                    <div class="stat-row">
                        <span class="stat-label">Episoden:</span>
                        <span class="stat-value">55</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Kategorie:</span>
                        <span class="stat-value">Society & Culture</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Start:</span>
                        <span class="stat-value">27.04.2021</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Ende:</span>
                        <span class="stat-value">29.12.2022</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Sprache:</span>
                        <span class="stat-value">de</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Base Name:</span>
                        <span class="stat-value">Böttinger Wohnung 17</span>
                    </div>
                </div>
            </div>

            <div class="podcast-card ">
                <div class="podcast-header">
                    <img src="podcast_images/Hotel-Matze.jpg" alt="Hotel Matze" class="podcast-image">
                    <div class="podcast-title">
                        <h3>Hotel Matze</h3>
                        <p class="podcast-author">Matze Hielscher & Mit Vergnügen</p>
                    </div>
                </div>
                
                <div class="podcast-description">
                    Das ist kein richtiges Hotel, sondern ein Interview-Podcast von Matze Hielscher. Hier treffe ich mich seit 2016 mit Menschen, die mich interessieren und versuche herauszufinden, wie die so ticken.
                </div>
                
                
                
                <div class="podcast-stats">
                    <div class="stat-row">
                        <span class="stat-label">Episoden:</span>
                        <span class="stat-value">466</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Kategorie:</span>
                        <span class="stat-value">Unbekannt</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Start:</span>
                        <span class="stat-value">26.10.2016</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Ende:</span>
                        <span class="stat-value">09.07.2025</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Sprache:</span>
                        <span class="stat-value">de</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Base Name:</span>
                        <span class="stat-value">Hotel Matze</span>
                    </div>
                </div>
            </div>

            <div class="podcast-card ">
                <div class="podcast-header">
                    <img src="podcast_images/Out-and-About.jpg" alt="Out and About" class="podcast-image">
                    <div class="podcast-title">
                        <h3>Out and About</h3>
                        <p class="podcast-author">Aljosha Muttardi & Studio Bummens</p>
                    </div>
                </div>
                
                <div class="podcast-description">
                    Was bedeutet Coming-out im Jahr 2023? Braucht es das überhaupt noch? Und wie sah das früher aus? Das und viele weitere Fragen rund um die Lebensrealitäten queerer Menschen diskutiert Host Aljosha Muttardi mit seinen Gäst*innen im neuen Format "Out and About". Die queere Community ist divers, so w...
                </div>
                
                
                
                <div class="podcast-stats">
                    <div class="stat-row">
                        <span class="stat-label">Episoden:</span>
                        <span class="stat-value">12</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Kategorie:</span>
                        <span class="stat-value">Unbekannt</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Start:</span>
                        <span class="stat-value">01.03.2023</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Ende:</span>
                        <span class="stat-value">18.01.2024</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Sprache:</span>
                        <span class="stat-value">de</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Base Name:</span>
                        <span class="stat-value">Out-and-About</span>
                    </div>
                </div>
            </div>

            <div class="podcast-card ">
                <div class="podcast-header">
                    <img src="podcast_images/Queer-as-Berlin.jpg" alt="Out and About" class="podcast-image">
                    <div class="podcast-title">
                        <h3>Out and About</h3>
                        <p class="podcast-author">Aljosha Muttardi & Studio Bummens</p>
                    </div>
                </div>
                
                <div class="podcast-description">
                    Was bedeutet Coming-out im Jahr 2023? Braucht es das überhaupt noch? Und wie sah das früher aus? Das und viele weitere Fragen rund um die Lebensrealitäten queerer Menschen diskutiert Host Aljosha Muttardi mit seinen Gäst*innen im neuen Format "Out and About". Die queere Community ist divers, so w...
                </div>
                
                
                
                <div class="podcast-stats">
                    <div class="stat-row">
                        <span class="stat-label">Episoden:</span>
                        <span class="stat-value">12</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Kategorie:</span>
                        <span class="stat-value">Unbekannt</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Start:</span>
                        <span class="stat-value">01.03.2023</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Ende:</span>
                        <span class="stat-value">18.01.2024</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Sprache:</span>
                        <span class="stat-value">de</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Base Name:</span>
                        <span class="stat-value">Queer as Berlin</span>
                    </div>
                </div>
            </div>

            <div class="podcast-card ">
                <div class="podcast-header">
                    <img src="podcast_images/Sputnik-Pride.jpg" alt="Queer As Berlin" class="podcast-image">
                    <div class="podcast-title">
                        <h3>Queer As Berlin</h3>
                        <p class="podcast-author">© Michael Meyer - PODCAST EINS</p>
                    </div>
                </div>
                
                <div class="podcast-description">
                    Zur Show“Queer as Berlin” ist der Diversity Podcast aus der Hauptstadt, der interessante Gäste und Themen präsentiert. (Sub-) Kultur,&nbsp;Politik, Unterhaltung, Musik, Wirtschaft, Gesellschaft – alles aus der Diversity Perspektive kann hier Thema sein. In Deutschland leben ca. 8-10 Millionen sch...
                </div>
                
                
                
                <div class="podcast-stats">
                    <div class="stat-row">
                        <span class="stat-label">Episoden:</span>
                        <span class="stat-value">68</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Kategorie:</span>
                        <span class="stat-value">Unbekannt</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Start:</span>
                        <span class="stat-value">01.08.2019</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Ende:</span>
                        <span class="stat-value">24.05.2024</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Sprache:</span>
                        <span class="stat-value">de</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Base Name:</span>
                        <span class="stat-value">Sputnik Pride</span>
                    </div>
                </div>
            </div>

            <div class="podcast-card ">
                <div class="podcast-header">
                    <img src="podcast_images/Queerkram.jpg" alt="QUEERKRAM" class="podcast-image">
                    <div class="podcast-title">
                        <h3>QUEERKRAM</h3>
                        <p class="podcast-author">Johannes Kram präsentiert von queer.de</p>
                    </div>
                </div>
                
                <div class="podcast-description">
                    Hier gibt es rund einstündige Gespräche, die der Autor Johannes Kram mit Gästen führt, die meist aus der LGBTI-Community kommen, also offen lesbisch, schwul, bi-, intersexuell oder trans sind. Unter dem Motto „Wir sind alle anders, wir sind alle gleich“ möchte Kram dazu beitragen, völlig untersch...
                </div>
                
                
                
                <div class="podcast-stats">
                    <div class="stat-row">
                        <span class="stat-label">Episoden:</span>
                        <span class="stat-value">43</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Kategorie:</span>
                        <span class="stat-value">Unbekannt</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Start:</span>
                        <span class="stat-value">28.02.2020</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Ende:</span>
                        <span class="stat-value">02.11.2024</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Sprache:</span>
                        <span class="stat-value">de</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Base Name:</span>
                        <span class="stat-value">Queerkram</span>
                    </div>
                </div>
            </div>

            <div class="podcast-card ">
                <div class="podcast-header">
                    <img src="podcast_images/Reden-ist-Gold.jpg" alt="Reden ist Gold" class="podcast-image">
                    <div class="podcast-title">
                        <h3>Reden ist Gold</h3>
                        <p class="podcast-author">Rick und Chris</p>
                    </div>
                </div>
                
                <div class="podcast-description">
                    Zwei Freunde, ein Mikrofon (ehrlich gesagt sind es zwei Mikrofone),...und jede Menge Themen, die bewegen – Von mentaler Gesundheit über Fitness und Technik bis zu den Herausforderungen des Alltags. Hier erwarten euch ehrliche Gespräche, spontane Wetten und wöchentliche Challenges, die wir mit ein...
                </div>
                
                
                
                <div class="podcast-stats">
                    <div class="stat-row">
                        <span class="stat-label">Episoden:</span>
                        <span class="stat-value">18</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Kategorie:</span>
                        <span class="stat-value">Unbekannt</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Start:</span>
                        <span class="stat-value">27.10.2024</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Ende:</span>
                        <span class="stat-value">08.06.2025</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Sprache:</span>
                        <span class="stat-value">de-de</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Base Name:</span>
                        <span class="stat-value">Reden ist Gold</span>
                    </div>
                </div>
            </div>

            <div class="podcast-card ">
                <div class="podcast-header">
                    <img src="podcast_images/Somewhere-Over-The-Hay-Bale.jpg" alt="Somewhere Over The Hay Bale" class="podcast-image">
                    <div class="podcast-title">
                        <h3>Somewhere Over The Hay Bale</h3>
                        <p class="podcast-author">Fabian</p>
                    </div>
                </div>
                
                <div class="podcast-description">
                    Jenseits des Heuballens: Der erste deutschsprachige Interviewpodcast über queeres Leben auf dem Land. 40 Folgen aus 4 Jahren. Danke. Als schwuler Junge in einem (ostdeutschen) Dorf groß zu werden war nicht immer ganz so easy für mich. Homosexualität und queeres Leben kannte ich fast nur aus dem F...
                </div>
                
                
                
                <div class="podcast-stats">
                    <div class="stat-row">
                        <span class="stat-label">Episoden:</span>
                        <span class="stat-value">43</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Kategorie:</span>
                        <span class="stat-value">Unbekannt</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Start:</span>
                        <span class="stat-value">10.03.2020</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Ende:</span>
                        <span class="stat-value">15.03.2024</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Sprache:</span>
                        <span class="stat-value">de</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Base Name:</span>
                        <span class="stat-value">Somewhere Over The Hay Bale</span>
                    </div>
                </div>
            </div>

            <div class="podcast-card ">
                <div class="podcast-header">
                    <img src="podcast_images/Willkommen-im-Club.jpg" alt="Willkommen im Club - der queere Podcast von PULS" class="podcast-image">
                    <div class="podcast-title">
                        <h3>Willkommen im Club - der queere Podcast von PULS</h3>
                        <p class="podcast-author">Bayerischer Rundfunk</p>
                    </div>
                </div>
                
                <div class="podcast-description">
                    Willkommen im Club der LGBTIQA*-Community! Aber wer ist das eigentlich und wieso braucht sie so viele Buchstaben im Titel? Welche Klischees ärgern Lesben, Schwule, Bisexuelle, trans* und andere queere Menschen so richtig? Was beschäftigt sie gerade? Gemeinsam mit euch entdecken Sophia und Dimi, d...
                </div>
                
                
                
                <div class="podcast-stats">
                    <div class="stat-row">
                        <span class="stat-label">Episoden:</span>
                        <span class="stat-value">179</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Kategorie:</span>
                        <span class="stat-value">Society & Culture</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Start:</span>
                        <span class="stat-value">04.05.2020</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Ende:</span>
                        <span class="stat-value">09.07.2025</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Sprache:</span>
                        <span class="stat-value">de-DE</span>
                    </div>
                    <div class="stat-row">
                        <span class="stat-label">Base Name:</span>
                        <span class="stat-value">Willkommen im Club</span>
                    </div>
                </div>
            </div>

        </div>
        
        <div class="footer">
            <p>Generiert am 11.07.2025 um 22:40 Uhr | Queer Waves Corpus</p>
        </div>
    </div>
</body>
</html>
