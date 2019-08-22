# Page 404
---

Exercices sur les pages d'erreurs

Création d'une page 404...

### Partie HTML
<details>
<summary>Fichier HTML</summary>
```markdown
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="index.css" />
    <title>Page_404</title>
</head>
<body>
    <header>
            <div id="engrenage">
                    <img class="un" src="images/engrenage01.png" alt="engrenage">
                    <img class="deux" src="images/engrenage02.png" alt="engrenage">
                    <img class="trois" src="images/engrenage03.png" alt="engrenage">
                </div>
        
    </header>
    <section>
            <div id="texte">Sorry, Page not Found</br></div>
    </section>
    <footer>
        
            <a href="https://github.com/christophedejaiffe" target="_blank" rel="" class="button">Back</a>
    </footer>
</body>
</html>
```
</details>


### Partie CSS
<details>
<summary>Fichier CSS</summary>
```markdown
/*Fonts de la page*/

@font-face {
    font-family: 'atomic_ageregular';
    src: url('Fonts/atomicage-regular-webfont.eot');
    src: url('Fonts/atomicage-regular-webfont.eot?#iefix') format('embedded-opentype'),
         url('Fonts/atomicage-regular-webfont.woff2') format('woff2'),
         url('Fonts/atomicage-regular-webfont.woff') format('woff'),
         url('Fonts/atomicage-regular-webfont.ttf') format('truetype'),
         url('Fonts/atomicage-regular-webfont.svg#atomic_ageregular') format('svg');
    font-weight: normal;
    font-style: normal;

}

body, html
{
    height: 100%;
}


header
{
    width: 90%;
    height: 100%;
    margin: 0 auto;
}

#engrenage
{
    position: relative;
    width: 50%;
    height: 80%;
    margin: auto;

}

@-webkit-keyframes rotate-center 
{
        0% {
          -webkit-transform: rotate(0);
                  transform: rotate(0);
            }
        100% {
          -webkit-transform: rotate(360deg);
                  transform: rotate(360deg);
            }
}

 @keyframes rotate-center 
{
        0% {
          -webkit-transform: rotate(0);
                  transform: rotate(0);
            }
        100% {
          -webkit-transform: rotate(360deg);
                  transform: rotate(360deg);
            }
}
      

#texte
    {
    
        font-family: 'atomic_ageregular',Arial, Helvetica, sans-serif;
        font-size: 2em;
        text-align: center;


    }

footer
{
    margin-top: 12%;
    text-align: center;
}

.button {
    text-align: center;
    background-color: black;
    display: inline-block;
    padding: 10px 30px 10px 30px;
    text-decoration: none;
    color: white;
    border-radius: 20px;
}

.button:hover {
    background-color: red;
}


.un
{
       position: absolute;
       top: 10%;
       left: 20%;
       width: 40%;
       height: auto;
 
        -webkit-animation: rotate-center 8s linear infinite both;
                animation: rotate-center 8s linear infinite both;
}

.deux
{
        position: absolute;
        top: 57%;
        left: 30%;
        width: 30%;
        height: auto;
        -webkit-animation: rotate-center 5s linear infinite both;
                animation: rotate-center 5s linear infinite both;
}

.trois
{
       position: absolute;
       top: 43%;
       left: 55%;
       width: 20%;
       height: auto;
        -webkit-animation: rotate-center 4s linear infinite reverse both;
                animation: rotate-center 4s linear infinite reverse both;
}

section
{
    margin: -10%;
}
```
</details>

