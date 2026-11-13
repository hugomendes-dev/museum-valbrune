# Muséum de Valbrune : site vitrine

Projet de formation : intégration HTML5 / Bootstrap d'un site vitrine à partir de maquettes.

## Auteur·rice

- Nom et prénom : Mendes Farias Hugo    
- Formation (DWWM / CDA) : DWWM
- Dates du projet : du 9 au 20 novembre 2026 

## Palier atteint

- [ ] Palier 1 : Socle
- [ ] Palier 2 : Standard
- [ ] Palier 3 : Avancé

## Dépôt GitHub

- Adresse du dépôt : https://github.com/hugomendes-dev/museum-valbrune
- Version de Bootstrap utilisée (relevée sur getbootstrap.com le jour du lancement) : 5.3.8

## Tags du vendredi

|     Tag     |   Date   |   État du projet à cette date   |
|-------------|----------|---------------------------------|
| semaine-1   |13/11/2026| Toutes les étapes palier 1 fait |
| semaine-2   |          |                                 |
| semaine-3   |          |                                 |

## Lancer le projet


1. Ouvrir le dossier museum-valbrune dans VS Code.
2. Installer l'extension Live Server si elle n'est pas déjà installée.
3. Ouvrir un fichier .html, puis cliquer sur « Go Live » en bas à droite de VS Code.

## Lien de mise en ligne (palier 3)

## Questions posées au client et réponses obtenues

Question posées le 09/11/2026 :

R2 :  La signature de la direction figure sur l'organigramme, mais celui-ci n'est fourni nulle part. J'aurais donc besoin de connaître le nom et la fonction de cette personne. Pouvez-vous me les communiquer ? 
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

## Sources consultées

- Documentation officielle Bootstrap 5.3 : https://getbootstrap.com/docs/5.3/
- MDN Web Docs : https://developer.mozilla.org/fr/
- Documents du projet : sujet, dossier technique, contenus à intégrer, maquettes, charte graphique.
- Réponses du client aux questions ci-dessus.

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

En dehors de ces cas, l'IA n'a produit ni le code ni les textes du site : les textes viennent des documents fournis et des réponses du client. Je sais expliquer tout ce que je rends.