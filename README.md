# TP : Utilisation des Variables Bootstrap

## Objectif
L'objectif de ce TP est de vous familiariser avec l'utilisation des variables Bootstrap pour personnaliser les styles de vos composants web et créer de nouvelles classes basées sur Bootstrap.

## Exercice

### **Étape 1 : Configuration du Projet**

1. Créez un nouveau projet avec une structure comprenant les dossiers `scss`, `css`, et un fichier `index.html`.
2. Installez Bootstrap en SCSS via npm et configurez la compilation SCSS en CSS.
3. Dans votre fichier `style.scss`, importez Bootstrap et ses variables.

### **Étape 2 : Personnalisation des Couleurs**

1. Modifiez les couleurs de base dans `style.scss`, en personnalisant notamment les variables `$primary`, `$secondary`, `$success`, et `$danger`.
2. Testez les modifications en créant des boutons dans `index.html`.

### **Étape 3 : Ajuster les Spacings**

1. Redéfinissez la variable `$spacer` et ajustez les espacements dans la carte `$spacers`.
2. Créez une section dans `index.html` pour observer les effets des espacements modifiés.

### **Étape 4 : Redéfinir les Typographies**

1. Changez la police par défaut en "Roboto" et ajustez les tailles de texte (`$font-size-base`, `$h1-font-size`, `$h2-font-size`).
2. Testez les nouvelles typographies dans `index.html` en utilisant différents titres et paragraphes.

### **Étape 5 : Utilisation des Mixins Bootstrap**

1. Utilisez les mixins Bootstrap pour créer des styles réactifs, par exemple pour un conteneur personnalisé (`custom-container`).
2. Testez l'affichage réactif en appliquant la classe à une `div` dans `index.html`.

### **Étape 6 : Personnalisation des Boutons**

1. Créez une nouvelle classe de boutons personnalisés en utilisant les variables et mixins de Bootstrap.
2. Testez ce bouton personnalisé dans `index.html`.

### **Étape 7 : Création d'une Classe Card Personnalisée**

1. Créez une nouvelle classe `card-custom` basée sur la classe `card` de Bootstrap.
2. Personnalisez la bordure, la couleur d'arrière-plan, le padding, et l'ombre de la carte.
3. Ajoutez des variables pour contrôler ces éléments et assurez-vous que la carte est réactive en utilisant des mixins Bootstrap.
4. Intégrez cette nouvelle carte dans `index.html` avec un titre, une image, du texte et un bouton, pour tester la mise en page et le style de la carte.
