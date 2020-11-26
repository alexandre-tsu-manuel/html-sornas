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
