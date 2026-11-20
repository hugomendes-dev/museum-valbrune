# Muséum de Valbrune : site vitrine

Projet de formation : intégration HTML5 / Bootstrap d'un site vitrine à partir de maquettes.

## Auteur·rice

- Nom et prénom : Mendes Farias Hugo    
- Formation (DWWM / CDA) : DWWM
- Dates du projet : du 9 au 20 novembre 2026 

## Palier atteint

- [X] Palier 1 : Socle
- [X] Palier 2 : Standard
- [ ] Palier 3 : Avancé

## Dépôt GitHub

- Adresse du dépôt : https://github.com/hugomendes-dev/museum-valbrune
- Version de Bootstrap utilisée (relevée sur getbootstrap.com le jour du lancement) : 5.3.8

## Tags du vendredi

|     Tag     |   Date   |   État du projet à cette date   |
|-------------|----------|---------------------------------|
| semaine-1   |13/11/2026| Toutes les étapes palier 1 faites |
| semaine-2   |20/11/2026| Toutes les étapes du palier 2 faites |                              
| semaine-3   |          |                                 |

## Lancer le projet


1. Ouvrir le dossier museum-valbrune dans VS Code.
2. Installer l'extension Live Server si elle n'est pas déjà installée.
3. Ouvrir un fichier .html, puis cliquer sur « Go Live » en bas à droite de VS Code.

## Lien de mise en ligne (palier 3)

## Questions posées au client et réponses obtenues

Questions posées le 09/11/2026 :

R2 : La signature de la direction figure sur l'organigramme, mais celui-ci n'est fourni nulle part. J'aurais donc besoin de connaître le nom et la fonction de cette personne. Pouvez-vous me les communiquer ? 
- Direction du Muséum 

R3 : Concernant le tarif Famille, la « règle habituelle » n'est écrite nulle part. Pouvez-vous me préciser ce que vous considérez comme une famille ?
Combien d'adultes et d'enfants sont inclus dans ce tarif ? 
- 2 adultes et 3 jeunes

Jusqu'à quel âge un enfant peut-il bénéficier de ce tarif ? 
- 12 à 17 ans

Quel prix souhaitez-vous afficher ? 
- 20 € 

R5 : Je n'ai pas eu connaissance du message que vous avez communiqué oralement lors du lancement du projet. Quel texte souhaitez-vous afficher dans le bandeau d'information ? 
- Nocturne gratuite chaque jeudi premier du mois, jusqu'à 21h

R6 : Pour le plan d'accès, j'ai bien le fichier plan-acces.webp. Est-ce que ce fichier suffit ou souhaitez-vous autre chose, comme une carte interactive ?
- Le plan plan-acces.webp suffit

R7 : Pour les réseaux sociaux, quand vous dites « mettez les liens là où nous ne sommes pas encore », qu'est-ce que vous voulez dire exactement ? Est-ce un endroit sur le site qui n'a pas encore été créé ou des réseaux sociaux sur lesquels le Muséum n'a pas encore de compte ? Quelle adresse souhaitez-vous que je mette dans le lien ?
- Le Muséum n'a pas encore de compte : réseaux sociaux affichés en texte, sans lien

R8 : Quelle année souhaitez-vous retenir pour la mise en ligne ?
- 2026

Lien « Agenda » dans la navigation : La page Agenda sera ajoutée plus tard au site. En attendant, que souhaitez-vous faire du lien « Agenda » ?
- Affiché en texte, mais sans lien

## Difficultés rencontrées et solutions trouvées

- Live Server ajoutait "-->" dans la page html : un commentaire du kit contenait </body>, ce qui perturbait le script injecté par Live Server. Solution : modifier ce commentaire.

- Modifications CSS invisibles dans le navigateur : j'oubliais d'enregistrer style.css. Solution : activer l'enregistrement automatique (Auto Save) dans VS Code.

- Pages non conformes à la maquette : j'avais d'abord suivi uniquement les légendes, et il manquait des titres et des pictogrammes. 
Solution : comparer chaque page avec l'image de la maquette, les légendes, les contenus et la charte avant de valider.

- Sections collées à l'intérieur de la section précédente : certaines balises fermantes étaient mal placées. Solution : déplacer les balises fermantes au bon endroit et replier les sections dans VS Code avant de coller du code.

- Liens du sommaire bleus au lieu d'être verts : Bootstrap appliquait sa couleur par défaut aux liens. Solution : modifier les variables CSS de Bootstrap pour utiliser les couleurs du site.

- Titres cachés sous le header fixe après un clic sur un lien du sommaire : le défilement ne tenait pas compte de la hauteur du header. Solution : ajouter scroll-padding-top sur html.

- Croix de fermeture du bandeau d'information mal alignée : le positionnement appliqué par Bootstrap ne respectait pas l'alignement de la grille. Solution : utiliser un container avec Flexbox et retirer la classe alert-dismissible.

- Images des cartes étirées en hauteur : les images ne conservaient pas leurs proportions. Solution : ajouter la classe img-fluid pour adapter automatiquement leur hauteur à leur largeur.

## Sources consultées

- Documentation officielle Bootstrap 5.3 : https://getbootstrap.com/docs/5.3/
- MDN Web Docs : https://developer.mozilla.org/fr/
- Documents du projet : sujet, dossier technique, contenus à intégrer, maquettes, charte graphique.
- Réponses du client aux questions ci-dessus.
- W3C : https://validator.w3.org/
- WAVE : https://wave.webaim.org/

## Déclaration d'usage d'outils d'IA

J'ai utilisé Claude (Anthropic) pendant tout le projet, comme tuteur :

- la lecture et la compréhension des documents du projet
- relecture de mes questions au client 
- explications des notions (grille Bootstrap, accessibilité, Git) sous forme d'indices quand je bloquais 
- QCM pour vérifier ma compréhension 
- vérification de mon code page par page, avec la liste des erreurs à corriger 
- préparation d'une fiche de révision 
- mise en forme de ce README à partir de mes notes

Lors du jour 2, Claude m'a donné pas mal de code pour le bandeau d'information et le bandeau principal. Je me suis rendu compte que ça allait un peu trop loin par rapport aux consignes du projet, et je lui ai fait remarquer. Après ça, on a repris avec une méthode basée sur des indices pour que je puisse faire le code moi-même et comprendre ce que je faisais. Une fois, après plusieurs essais de ma part, il m'a quand même montré une structure HTML pour m'aider à avancer. Je suis capable d'expliquer ce code comme le reste du site.

Lors du jour 5, Claude m'a aussi donné directement les lignes de code corrigées pour régler des erreurs de copier-coller dans les attributs class des pictogrammes, notamment sur les pages Infos pratiques et Accueil. C'était de la correction de mon propre code, mais les lignes m'ont quand même été fournies par l'IA et je les ai recopiées.

Lors des jours 6 à 9, Claude m'a d'abord donné directement certaines variables et propriétés CSS que je ne connaissais pas, notamment --bs-link-color, --bs-btn-focus-shadow-rgb et scroll-padding-top. Nous avons ensuite repris certains points avec une méthode basée sur des indices pour que je comprenne leur fonctionnement et leur utilité. Pour certaines corrections, il m'a également fourni directement des exemples de lignes de code, notamment l'ajout de la classe img-fluid sur les images. J'ai intégré ces modifications dans mon projet et je suis capable d'expliquer leur rôle.

J'ai également utilisé Claude pour vérifier une partie de la checklist directement sur mes fichiers.

En dehors de ces cas, l'IA n'a produit ni le code ni les textes du site : les textes viennent des documents fournis et des réponses du client. Je sais expliquer tout ce que je rends.

## Checklist de recette

| # | Point de contrôle | OK ? | Commentaire |
|---|---|---|---|
| 1 | Toutes les pages du palier visé existent et sont reliées par la navigation. | X | Les 6 pages sont créées : Accueil, Le Muséum, Expositions, Infos pratiques, Contact et Mentions légales. |
| 2 | En-tête et pied de page identiques sur toutes les pages. | X | Même en-tête sur les 6 pages, avec uniquement le lien actif qui change. Les pieds de page sont identiques. |
| 3 | Affichage correct à 375, 768 et 1280 px, sans barre de défilement horizontale. | X | Tests réalisés à 375, 768 et 1280 px. Correction des images des cartes avec la classe img-fluid pour conserver leurs proportions. |
| 4 | Menu replié fonctionnel sous 992 px. | X | Menu burger testé à 768 px, il s'ouvre correctement. |
| 5 | Validateur W3C : 0 erreur sur chaque page. | X | 0 erreur sur les 6 pages. |
| 6 | Un seul h1 par page, hiérarchie des titres respectée. | X | Exactement un h1 sur chacune des 6 pages. Hiérarchie des titres vérifiée. |
| 7 | Couleurs et polices conformes à la planche. | X | Couleurs de la charte et polices Fraunces et Atkinson Hyperlegible intégrées dans le CSS. |
| 8 | Boutons principaux et liens aux bonnes couleurs, y compris au survol. | X | Couleurs personnalisées dans le CSS pour respecter la charte graphique. |
| 9 | Textes intégrés tels que fournis. | X | Textes repris du document Contenus, sans modification. |
| 10 | Chaque image a un attribut alt adapté, ainsi que width et height. | X | Toutes les images ont un attribut alt, width et height adaptés. |
| 11 | Navigation au clavier possible, focus visible, lien d'évitement présent. | X | Navigation au clavier possible, focus visible et lien d'évitement présent. |
| 12 | Chaque champ de formulaire a un label relié. | X | Tous les champs de Contact et de la lettre d'information ont un label relié avec for et id. |
| 13 | Tableaux avec th et scope. | X | Tous les th des deux tableaux ont un attribut scope (col ou row). |
| 14 | Aucune ressource inutile chargée ; aucun attribut style dans le HTML. | X | Bootstrap CSS est utilisé pour la mise en page, les cartes et les boutons. Bootstrap JS est utilisé pour le menu burger, le bandeau d'information et l'accordéon de la FAQ. Aucun attribut style présent dans les 6 pages HTML. |
| 15 | Remarques du client (sujet § 5.5) toutes traitées, questions notées dans le README. | X | Les 9 remarques du client (R1 à R9) ont été traitées. Les questions et les réponses sont notées dans le README. |
| 16 | Commits réguliers poussés sur GitHub ; tags semaine-1 et semaine-2 présents (git ls-remote --tags origin). | X | Tag semaine-1 présent depuis le 13/11. Tag semaine-2 présent depuis le 20/11. |
| 17 | README complet. | X | Complet. |