À partir du projet fourni, créez un formulaire d'inscription dans la zone dédiée
(marquée par un commentaire).
Le formulaire doit comprendre :
Un fieldset avec le titre "Inscription au club de jeux vidéo"
Un champ pour le nom avec un label associé.
Un champ pour le prénom avec un label associé.
Un champ pour l'âge (de préférence un champ numérique) avec un label
associé.
Un champ pour l'adresse e-mail avec un label associé.
Un menu déroulant pour choisir le type de jeu préféré avec un label
associé.
Deux cases à cocher pour sélectionner les consoles possédées, chacune
avec un label associé
PlayStation
XboxNintendo Switch
PC
Un bouton pour soumettre l'inscription.
Un bouton pour réinitialiser le formulaire.
Un lien pour revenir à la page d'accueil.
Accessibilité :
Chaque champ doit avoir un id correspondant à son label pour améliorer
l'accessibilité.
Utiliser des attributs aria-label si nécessaire pour les éléments non textuels.

Ajoutez, sur chaque champ, les contraintes suivantes :
Nom : obligatoire, uniquement des caractères alphabétiques. Ajoutez un
message d'erreur visible si non respecté.
Prénom : obligatoire, uniquement des caractères alphabétiques. Affichez
un message d'erreur si non respecté.
Âge : obligatoire, doit être un nombre entre 10 et 100. Utilisez des attributs
de validation HTML pour cela.
Adresse e-mail : obligatoire, doit respecter le format d'une adresse e-mail
valide. Ajoutez une indication visuelle pour les erreurs.
Type de jeu : obligatoire, une sélection doit être faite, avec un message
d'erreur si aucune sélection n'est faite.
Assurez-vous que les messages d'erreur sont visibles pour les utilisateurs de
lecteurs d'écran.
Ajoutez des descriptions (via aria-describedby) pour chaque champ pour
clarifier les erreurs ou les instructions.
