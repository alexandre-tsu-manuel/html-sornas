Fil rouge : https://openclassrooms.com/fr/courses/1603881-apprenez-a-creer-votre-site-web-avec-html5-et-css3

# Jour 1
## Le code HTML
```html
<!DOCTYPE html>
<html>
    <head>
    	<meta charset="utf-8" />
        <title>Mon arc en ciel</title>
    </head>
    <body>
    	<p>
        	<span class="lettre1">B</span>
        	<span class="lettre2">o</span>
        	<span class="lettre3">n</span>
        	<span class="lettre4">j</span>
        	<span class="lettre5">o</span>
        	<span class="lettre6">u</span>
        	<span class="lettre7">r</span>
                &nbsp;
        	<span class="lettre8">à</span>
                &nbsp;
        	<span class="lettre9">t</span>
        	<span class="lettre10">o</span>
        	<span class="lettre11">u</span>
        	<span class="lettre12">s</span>
        </p>
    </body>
</html>
```

## Le code CSS
```css
.lettre1 { color: red; }
.lettre2 { color: green; }
.lettre3 { color: blue; }
.lettre4 { color: yellow; }
.lettre5 { color: silver; }
.lettre6 { color: orange; }
.lettre7 { color: #584499; }
.lettre8 { color: #808080; }
.lettre9 { color: #CCCCCC; }
.lettre10 { color: #A25F8C; }
.lettre11 { color: rgb(255, 128, 0); }
.lettre12 { color: rgb(112, 45, 68); }
```

# Jour 2
## Différentes techniques de HTML
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8" />
        <title>Ma page de test</title>
    </head>
    <body>
        <!-- Un commentaire -->
        <section> <!-- On découpe le contenu en sections -->
            <p></p> <!-- Un paragraphe -->
            <img src="dossier/monimage.png" alt="Mon image" /> <!-- Insérer une image -->
            <a href="google.com">Lien vers Google</a> <!-- Insérer un lien -->
        </section>
        <section>
            <h1>Titre principal</h1>
            <h2>Sous-titre</h2>
            <h3>Sous-sous-titre</h3>
            <ul> <!-- Liste à puce -->
                <li>Premier élément</li>
                <li>Deuxième élément</li>
            </ul>
        </section>
    </body>
</html>
```

## Exercice du jour
### Votre mission
- 1 : Créez une page HTML.
- 2 : Ajoutez votre nom et votre prénom en titre principal.
- 3 : Ajoutez une photo miniature, sur laquelle on pourra cliquer pour avoir une version agrandie.
- 4 : Ajoutez 3 sections avec un titre secondaire (mon expérience, mes compétences, ma formation). Chaque section contient un paragraphe ou une liste à puce.

### Vérifiez que vous avez bien les éléments suivants :
- [X] La page HTML est un CV.
- [X] Le titre principal est en `<h1>`.
- [X] Une photo miniature cliquable renvoie sur la même photo agrandie.
- [X] 3 sections (mon expérience, mes compétences, ma formation) sont en titre `<h2>`.
- [X] Chaque section contient un paragraphe ou une liste à puce.

# Jour 3
## Différentes techniques de CSS
Soit le code HTML suivant :
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8" />
        <title>Webinaire du 26 novembre 2020</title>
        <link rel="stylesheet" media="all" type="text/css" href="cours-html.css" />
    </head>
    <body>
        <section>
            <img src="youtube-logo.png" alt="Logo Youtube" width="700px" />
            <h1>Webinaire du 26 novembre 2020</h1>
            <p>
                Mon super Live YouTube commencera à 15h. Actualisez la page à ce moment là.
            </p>
        </section>
    </body>
</html>
```

Et le code CSS :
```css
html
{
    background-image: url("bg.png");
}

body
{
    width: 800px;
    margin: auto;
    margin-top: 100px;
    background: linear-gradient(to right, #F0F0F0, white, white, #F0F0F0);
}

section
{
    padding: 50px;
    border: solid 1px silver;
    border-radius: 15px;
    text-align: center;
    color: #404040;
}

h1
{
    font-size: 4em;
}

p
{
    font-size: 2.5em;
}
```

## Exercice du jour
### Votre mission
Étape 1 : Récupérez le fichier HTML que vous aviez créé lors du jour 2.
Étape 2 : Ajoutez-y les effets de style suivants :

- changer la couleur d'un des textes ;
- changer l'alignement d'un des textes ;
- appliquer une image de fond à la page ;
- utiliser une police personnalisée via @font-face ;
- définir la bordure d'un élément ;
- définir l'ombre d'un élément.

### Vérifiez que vous avez bien les éléments suivants :
- [X]  Vous avez une page .html et un fichier .css.
- [X]  La couleur d’un des textes est changée.
- [X]  L’alignement d’un des textes est changé.
- [X]  Une image de fond est appliquée à la page.
- [X]  Une police personnalisée est utilisée via @font-face.
- [X]  La bordure d’un élément est définie.
- [X]  L’ombre d’un élément est définie.

## Correction
### HTML
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8" />
        <title>Mon super CV</title>
        <link rel="stylesheet" href="test.css" />
    </head>
    <body>
        <a href="profile-pic.jpg">
            <img src="profilepic.jpeg" alt="Photo d'Alexandre MANUEL" width="200px" />
        </a>
        <h1>Alexandre MANUEL</h1>
        <h3>Ingénieur informatique</h3>
        <header>
        </header>
        <nav>
        </nav>
        <section>
            <h2>Mon expérience</h2>
            <ul>
                <li>Sauvé le monde dans le Marvel Cinematic Universe</li>
                <li>Résolu le réchauffement climatique</li>
                <li>Battu Voldemort en duel</li>
            </ul>
        </section>
        <section>
            <h2>Mes compétences</h2>
            <ul>
                <li>Gourou absolu de HTML</li>
                <li>Niveau maximal de CSS</li>
                <li>Peinture sur chaise déséquilibrée en chanson</li>
            </ul>
        </section>
        <section class="formation">
            <h2>Ma formation</h2>
            <p>
                J'ai suivi au cours de ma vie une formation très particulière, qui me donne un ensemble de compétences très particulier, qui ferait pâlir d'envie Liam Neeson dans Taken.
            </p>
        </section>
        <footer>
        </footer>
    </body>
</html>
```
### CSS
```css
@font-face
{
    font-family: 'Roboto';
    src: url('RobotoMono-Medium.ttf');
}
@font-face
{
    font-family: 'Montserrat';
    src: url('Montserrat-Medium.ttf');
}

html
{
    background-color: #F0F0F0;
}

body
{
    width: 800px;
    margin: auto;
    margin-top: 100px;
    background: linear-gradient(to right, #F0F0F0, white, white, #F0F0F0);
    border: solid 1px silver;
    border-radius: 15px;
    box-shadow: 6px 6px 10px silver;
    font-family: 'Roboto';
    color: #707070;
}

section
{
    padding: 10px 20px;
    color: #404040;
    width: 80%;
    margin: auto;
    margin-top: 15px;
    margin-bottom: 15px;
}

h1, h2, h3
{
    text-align: center;
    font-family: 'Montserrat';
}
h1
{
    font-size: 3em;
    color: #202080;
}
h2 { color: #404040; }
h3 { color: #1010C0; }

img
{
    border-radius: 50%;
    text-align: left;
    margin-left: -40px;
    margin-top: -40px;
    float: left;
    box-shadow: 3px 3px 5px silver;
}
```

# Jour 4
## Différentes techniques de CSS
Soit le code HTML suivant :
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8" />
        <link rel="stylesheet" media="all" type="text/css" href="cours-html.css" />
    </head>
    <body>
        <header>
            <!-- En-tête -->
        </header>
        <nav>
            <!-- Menu -->
        </nav>
        <section>
            <!-- Contenu central -->
        </section>
        <footer>
            <!-- Pied de page -->
        </footer>
    </body>
</html>
```

Et le code CSS :
```css
nav
{
    height: 500px;
    width: 10%;
    margin-right: 2%;
    display: inline-block;
    background-color: blue;
}

section
{
    height: 500px;
    width: 85%;
    display: inline-block;
    background-color: red;
}
```

## Exercice du jour
### Votre mission
Pour le moment, vos pages sont assez verticales… Mais il est possible de travailler le sens de lecture et de profiter de la puissance de la mise en page en CSS.

Vous allez devoir structurer votre CV comme ceci :
* à gauche, un liseré, qui sera défini en valeur absolue (en pixels) ;
* à droite, le contenu de votre CV, qui contiendra à l'intérieur, de gauche à droite, les sections suivantes :
	* Mon expérience,
	* Mes compétences,
	* Ma formation.

La mise en page, à l'exception du liseré, doit être en valeur relative (pourcentage). Le contenu doit occuper tout l'espace en largeur, quelle que soit la largeur de la fenêtre.

Vous devrez utiliser des balises sémantiques pour réaliser votre mise en page.

### Vérifiez que vous avez bien les éléments suivants :
- [X] Un liseré est présent à gauche, en valeur absolue.
- [X] 3 blocs sont alignés de gauche à droite, avec une mise en page en valeur relative (pourcentage).
- [X] Des balises sémantiques sont utilisées.

## Correction
### HTML
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8" />
        <title>Mon super CV</title>
        <link rel="stylesheet" href="test.css" />
    </head>
    <body>
        <a href="profilepic.jpeg">
            <img src="profilepic.jpeg" alt="Photo d'Alexandre MANUEL" width="200px" />
        </a>
        <header>
            <h1>Alexandre MANUEL</h1>
            <h3>Ingénieur informatique</h3>
        </header>
        <section>
            <h2>Mon expérience</h2>
            <ul>
                <li>Sauvé le monde dans le Marvel Cinematic Universe</li>
                <li>Résolu le réchauffement climatique</li>
                <li>Battu Voldemort en duel</li>
            </ul>
        </section>
        <section>
            <h2>Mes compétences</h2>
            <ul>
                <li>Gourou absolu de HTML</li>
                <li>Niveau maximal de CSS</li>
                <li>Peinture sur chaise déséquilibrée en chanson</li>
            </ul>
        </section>
        <section>
            <h2>Ma formation</h2>
            <p>
                J'ai suivi au cours de ma vie une formation très particulière, qui me donne un ensemble de compétences très particulier, qui ferait pâlir d'envie Liam Neeson dans Taken.
            </p>
        </section>
        <footer>
            <a href="mailto:alexandre.th.manuel@gmail.com">alexandre.th.manuel@gmail.com</a> - 06 37 64 59 80
        </footer>
    </body>
</html>
```
### CSS
```css
@font-face
{
	font-family: 'Roboto';
	src: url('RobotoMono-Medium.ttf');
}
@font-face
{
	font-family: 'Montserrat';
	src: url('Montserrat-Medium.ttf');
}

html
{
	background-color: #F0F0F0;
}

body
{
    width: 1000px;
    margin: auto;
    margin-top: 50px;
    background: linear-gradient(to right, #F0F0F0, white, white, #F0F0F0);
    border: solid 1px silver;
    border-radius: 15px;
    box-shadow: 6px 6px 10px silver;
    font-family: 'Roboto';
	color: #707070;
}

header
{
	margin-left: 200px;
}

section:first-of-type
{
	clear: both;
}

section
{
    padding: 10px 20px;
    color: #404040;
    width: calc(33% - 40px);
    margin: auto;
    margin-top: 15px;
    margin-bottom: 15px;
    float: left;
}

footer
{
	margin: 10px;
	text-align: center;
}

a
{
    text-decoration: none;
    color: #404040;
}

h1, h2, h3
{
    font-family: 'Montserrat';
}
h1
{
    font-size: 3em;
    color: #1010A8;
}
h2
{
    color: #202080;
    text-align: center;
}
h3 { color: #404040; }

img
{
	border-radius: 50%;
	text-align: left;
	margin-left: -30px;
	margin-top: -30px;
	float: left;
    box-shadow: 3px 3px 5px silver;
}
```

# Jour 5
## Le Javascript
Soit le code HTML suivant :
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8" />
        <link rel="stylesheet" media="all" type="text/css" href="cours-html.css" />
    </head>
    <body>
        <section>
	    <p id="content">Ceci est un texte</p>
            <button onclick="button1()"></button>
            <button onclick="button2()"></button>
            <button onclick="button3()"></button>
        </section>
        <script
            src="https://code.jquery.com/jquery-3.5.1.min.js"
            integrity="sha256-9/aliU8dGd2tb6OSsuzixeV4y/faTqgFtohetphbbj0="
            crossorigin="anonymous"></script>
        <script src="cours-html.js"></script>
    </body>
</html>
```

Et le code Javascript :
```javascript
function button1()
{
    $('#content').text('ceci est un autre texte');
}

function button2()
{
    $('#content').css('color', 'red');
}

function button3()
{
    $('#content').toggle();
}
```

## Exercice du jour
### Votre mission
Vous allez devoir créer des sections dans votre CV.
Ajoutez un menu, contenant les boutons suivants :
    * Mon expérience,
    * Mes compétences,
    * Ma formation.

Par défaut, les sections "mes compétences" et "ma formation" doivent être cachées. Elles devront apparaître lors de l'appui sur le bouton correspondant.

### Vérifiez que vous avez bien les éléments suivants :
- [X] Un menu avec trois boutons
- [X] Un espace pour afficher la section en cours
- [X] Trois sections affichables
