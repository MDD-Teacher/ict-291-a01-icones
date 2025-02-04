# Exercice 1 : Intégrer des icônes sur un site web

## Objectifs
Les icônes sont très souvent utilisées sur un site web. Nous allons voir comment les intégrer de **trois manières différentes** :
- **Fichiers SVG**
- **Font Awesome**
- **Icônes de Bootstrap**

**Remarque :**  
Font Awesome propose une version payante avec de nombreux icônes, mais attention à la vitesse de chargement de votre page, un critère important pour les moteurs de recherche.

Il y a moins d’icônes disponibles avec Bootstrap, mais cela peut être une alternative intéressante. Il existe également d’autres librairies d’icônes sur le web ainsi que la possibilité d’afficher des icônes en **SVG**.

On peut aussi créer ses propres icônes au format **SVG**, ce qui permet d'agrandir une image sans perte de qualité (grâce au format vectoriel). Vous pouvez les créer avec **Illustrator** ou tout autre logiciel vectoriel, puis les sauvegarder en **SVG**.

Cet exercice demande de **faire quelques recherches**. Il y a des ressources disponibles sur Internet, donc n’hésitez pas à poser des questions à votre moteur de recherche préféré.

---

## 1️⃣ Affichage avec un fichier **SVG**
- Utiliser la structure de site proposée dans le répertoire **svg**.
- Afficher l’image **main.svg** du répertoire `img` à l’aide de la balise `<img>`.
- Modifier la taille du texte et de l’image pour qu’elle s’affiche de cette manière :

> 📌 **Exemple d'affichage attendu :**
>
> ![Exemple d'affichage SVG](chemin/vers/image-exemple.png)

On peut aussi afficher les fichiers **SVG** avec la balise `<svg>`. Cela permet d’intégrer directement le contenu du fichier dans l’HTML.

### 🔹 Étapes à suivre :
1. Ouvrir le fichier `main.svg` dans un éditeur de code.
2. Copier le contenu du fichier entre les balises `<svg>`.
3. Insérer ce contenu directement dans votre fichier HTML.
4. Vérifier si l’affichage est identique à la première version.

### 📚 Quelques ressources utiles :
- [SVG Repo - Icônes Open Source](https://www.svgrepo.com)
- [MDN - Comparaison des balises `<img>` et `<svg>`](https://developer.mozilla.org/fr/docs/Learn/HTML/Multimedia_and_embedding/Adding_vector_graphics_to_the_Web)

---

## 2️⃣ Affichage avec **Font Awesome**
1. Créer une structure de site basique pour tester l’affichage des icônes **Font Awesome**.
2. Télécharger et installer **Font Awesome** sur votre site web en suivant ce lien :  
   🔗 [Font Awesome - Site officiel](https://fontawesome.com)
3. Rechercher une icône **"terre"** à l’aide de ce lien :  
   🔗 [Icônes gratuites Font Awesome](https://fontawesome.com/v5.15/icons?d=gallery&p=1&m=free)  
   (**Note :** la recherche est limitée aux icônes gratuites.)
4. Afficher l’icône de la terre sur votre site avec la balise `<i>`.
5. Modifier l’apparence de cette icône pour qu’elle ressemble à ceci (**taille : 2rem**) :

> 📌 **Exemple d'affichage attendu :**
>
> 🌍 *(Icône Font Awesome de la Terre agrandie à 2rem)*

---

## 3️⃣ Affichage avec **Bootstrap Icons**
1. Créer une nouvelle structure de site basique.
2. Télécharger et installer **Bootstrap Icons** en suivant ce lien :  
   🔗 [Bootstrap Icons](https://icons.getbootstrap.com)
3. Afficher l’icône de la **montre** avec la balise `<i>`.
4. Modifier l’apparence de cette icône pour qu’elle ressemble à ceci (**taille : 4rem**) :

> 📌 **Exemple d'affichage attendu :**
>
> ⌚ *(Icône Bootstrap agrandie à 4rem)*
