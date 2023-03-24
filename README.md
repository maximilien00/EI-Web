# EI-Web

# Bootstrap 4

### Site officiel de la documentation : https://getbootstrap.com/docs/4.6/getting-started/introduction/ 

### Génération automatique de la base de code html avec les imports de Bootstrap de la version 4 grace à l'extension :
```html
b4-$
```
Nom de l'extension Visual Studio Code : "Bootstrap 4, Font awesome 4, Font Awesome 5 Free & Pro snippets » + « Bootstrap v4 Snippets"

### Bootstrap custom progress bars : https://getbootstrap.com/docs/4.0/components/progress/

Exemple : https://minuteurpersorpojetculturel.000webhostapp.com/Bootstrap%20Barre%20de%20Chargement/test.html

### Génération de grille pour bootstrap : http://www.net-developer.nl/en/bootstrap-grid-generator.html

### Icônes :
- https://icons.getbootstrap.com/
- https://fonts.google.com/icons
- https://fontawesome.com/docs

---

### Site pour la reconnaissance par image de structure bootstrap :
- https://www.bing.com/
- https://images.google.com/

---

# jQuerry

## Documentation jQuerry : https://api.jquery.com/

## Import jQuerry (sinon cela ne fonctionnera pas)
```html
<script
        src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js">
</script>
```

## Le code jQuerry doit être écrit dans la fonction suivante (qui se trouve dans un fichier .js ou dans le code html entre des balises <script></script>)

```javascript
$(function() {
    // votre code
});
```

## Exemple d'utilisation de jQuerry :

1.
```javascript
$(function() {
    console.log( "ready!" ); // exemple de code JavaScript
});
```

2.
```javascript
$(function() {
    $("#progress-bar").attr("aria-valuenow","0"); // Modification de l'attribut "aria-valueno"w qui à une classe "progress-bar" avec la valeur 0.
    $("#progress-bar").attr("aria-valuenow","50"); // Modification de l'attribut "aria-valueno"w qui à une classe "progress-bar" avec la valeur 50.
    $("#progress-bar").attr("aria-valuenow","100"); // Modification de l'attribut "aria-valueno"w qui à une classe "progress-bar" avec la valeur 100.
});
```

### Exemple pour modifier la valeur d'un attribut : https://www.w3schools.com/jquery/html_attr.asp

---

# Génération Image avec dimensions : http://via.placeholder.com/
Exemple : http://via.placeholder.com/400x450/3F51B5/fff

---

# ChatGPT
https://chat.openai.com/chat

Exemple de 1er échange avant toutes questions : "Tu es un assistant pour un développeur web qui est spécialisé dans le HTML, CSS, jQuerry, et Bootstrap Version 4 dans le but de produire un site web"

---

# Exemples

### Site d'Alexis
https://pengdoof.tk/aled/

### Travel Agency
https://minuteurpersorpojetculturel.000webhostapp.com/TP%201%20:%20Travel%20Agency/

### TP 1 Bootstrap
https://minuteurpersorpojetculturel.000webhostapp.com/TP%202%20:%20Bootstrap%204/HTML/index.html

### TP 2 jQuerry
https://minuteurpersorpojetculturel.000webhostapp.com/TP%203%20:%20Validation%20de%20Formulaire%20en%20JS/index.html
