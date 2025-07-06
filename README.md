# TP Capture Luigi's Mansion

## Présentation

Ce projet est une recréation du système de capture de luigi's mansion sur Unreal Engine 5 en blueprint.

Le projet est basé sur une caméra top down vue du dessus.

L'objectif du joueur est de capturer le fantôme.

Pour cela il doit d'abord stun le fantôme avec le flash de sa lampe torche lorsque celui-ci est dans sa zone.
Puis lancer la capture une fois stun.

Le joueur a un délai de 3 secondes pour lancer la capture sinon le fantôme s'enfuira.

Une fois en mode capture le joueur ne peut que tourner sur lui-même.
Pour capturer le fantôme la jauge de capture doit être pleine.
Pour la remplir le joueur doit faire face au fantôme et le joystick droit ou la souris doit aller à l'opposé de cette direction.

Une foi rempli le fantôme est capturé.

Si la jauge de capture reste à 0 pendant 5 secondes alors la capture prend fin et le fantôme s'enfuit.


Version d'Unreal minimale : 5.4.4

## Commande

Ce projet peut être utilisé au clavier/souris mais il est recommandé d'utiliser une manette.

### Commande manette :

**Mode déplacement**

Déplacement : Joystick gauche
Mouvement lampe torche : Joystick droit dans la direction où regarde le joueur
Flash : X / carré
Lancer la capture : B / rond

**Mode capture**

Tourner le joueur : Joystick gauche
Capturer le fantôme : Joystick droit dans la direction opposé où regarde le joueur

### Commande clavier/souris :

**Mode déplacement**

Déplacement : ZQSD
Mouvement lampe torche : Souris dans la direction où regarde le joueur
Flash : E
Lancer la capture : R

**Mode capture**

Tourner le joueur : ZQSD
Capturer le fantôme : Souris dans la direction opposé où regarde le joueur
