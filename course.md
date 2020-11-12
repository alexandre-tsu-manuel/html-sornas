# Exercice de la dernière fois :
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

# Différentes techniques de HTML
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

# Exercice du jour
## Votre mission
- 1 : Créez une page HTML.
- 2 : Ajoutez votre nom et votre prénom en titre principal.
- 3 : Ajoutez une photo miniature, sur laquelle on pourra cliquer pour avoir une version agrandie.
- 4 : Ajoutez 3 sections avec un titre secondaire (mon expérience, mes compétences, ma formation). Chaque section contient un paragraphe ou une liste à puce.

## Vérifiez que vous avez bien les éléments suivants :
- [X] La page HTML est un CV.
- [X] Le titre principal est en `<h1>`.
- [X] Une photo miniature cliquable renvoie sur la même photo agrandie.
- [X] 3 sections (mon expérience, mes compétences, ma formation) sont en titre `<h2>`.
- [X] Chaque section contient un paragraphe ou une liste à puce.
