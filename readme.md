# Découverte du Markdown
Les niveaux de titre sont définis par des # (1 à 6)


## 1. Quelques styles de texte

**Note :** Pour revenir à la ligne il faut utiliser la balise `<br>`<br>
Appuyer sur `entrée` ne suffit pas <br>
Sauter une ligne crée un nouveau paragraphe.


### 1.1. Ecrire en italique
Pour écrire en italique on entoure les mots ou les expressions par le symbole * ou _ <br>
Par exemple dans cette phrase, *il y'a de l'italique* <br>
Ici également on trouve un mot en _italique_

### 1.2. Ecrire en gras
Pour écrire en gras, on utilise le symbole ** ou __ <br>
Dans cette phrase il y'a un mot en **gras**, on peut aussi faire du gras __comme ceci__ 

### 1.3. Texte barré
Mince j'ai fait une erreur, le chat est ~~rouge~~ vert !

### 1.4. Définir une citation
Le journaliste de France 2 :
> Aujourd'hui il fait vraiment chaud !


## 2. Structures de texte

### 2.1. Listes
#### a. Liste à puces
- Fraises
- Pête feuilletée
- sucre
- amandes effilées

#### b. Liste numérotée
1. Préparer la pâte
2. Couper les fraises
3. disposer les fraises sur la pâte
4. saupoudre de sucre et d'amandes effilées

### 2.2. Code
Un petit morceau de code `<img src="chat.jpg" alt="un chat mignon">` dans un texte.

Un gros bloc de code quelquonque :
```
body {
    color: red;
    font-size: 1.2em;
}
```

Un gros bloc de code identifié (ici css) :
```css
body {
    color: red;
    font-size: 1.2em;
}
```

### 2.3. Liens
Les liens sont interpretés automatiquement comme tels :
https://dillinger.io/

Il est possible de personnaliser le texte d'affichage du lien :
[Dillinger](https://dillinger.io/)

### 2.4. Image
![Licorne](https://is3-ssl.mzstatic.com/image/thumb/Purple112/v4/3d/9e/66/3d9e66b3-d1a9-db75-8685-49cfd022ef9e/AppIcon-0-0-1x_U007emarketing-0-0-0-7-0-0-sRGB-0-0-0-GLES2_U002c0-512MB-85-220-0-0.png/256x256bb.jpg)

### 2.5. Tableaux
Fromage | Lait | Origine
--- | --- | ---
Comté | vache | Jura
Beaufort | vache | Savoie
Roquefort | Brebis | Aveyron
Camembert | vache | Normandie

### 2.6. Séparateur horizontal
---

### 2.7. CheckBox
Cases à cocher, super pratique !<br>
- [ ] J'ai tout compris au Markdown

Check list :
- [x] Sortir le chien
- [ ] Eplucher les patates
- [ ] Réviser les cours

### 2.8. Bonus
Emojis : 
:joy:
:wave:
:rocket:

### 2.9. Echapper un caractère
Je veux entourer un mot avec deux étoiles sans que ce mot soit en italique : \*Etoile\*. Il suffit de placer un antislash =>  \" \ \" avant le caractère que l'on ne souhaite pas interprété.