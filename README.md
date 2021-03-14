# Comment créer mon cosmétique ?
Pour créer votre cosmétique vous devez vous rendre dans votre `%appdata% `puis dans `botson` et pour finir dans `cosmetics-install`, Créez un fichier `style.css` est voilà votre fichier est créer.
```
└── AppData
    └── Roaming
        └── botson
            └── cosmetics-install
                └── style.css
```
# Que faut-il mettre dans style.css ?
Dans votre fichier css vous devez mettre un root puis les variables qui vous serons donner si dessus pour pouvoir changer la taille, les couleurs, les padding, ect...
Exemple :
```css
:root {
  /* Body */
  --body-bg-color: #FFFFFF;

  /* Title */
  --title-color: black;

  /* List Bots */
  --list-bg-color: ;
  --list-bg-img: url('https://user.oc-static.com/files/6001_7000/6410.jpg');
  --list-bg-repeat: repeat;
  --list-bg-size: cover;
}
```
