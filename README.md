UMARIS – Prototype de wireframes (basse fidélité)

Prototype cliquable de la future plateforme de gestion des demandes clients d'UMARIS. Il sert aux tests utilisateurs : il permet de valider les parcours avant de passer à la maquette haute fidélité.

Voir le prototype : https://IDENTIFIANT.github.io/umaris-prototype/ (remplacez IDENTIFIANT par votre identifiant GitHub)

Ce sont des wireframes basse fidélité. Ils montrent la structure des écrans et l'enchaînement des parcours, pas le design final. Les textes entre crochets, comme [N°], [Prénom] ou [durée à définir], sont des exemples ou des règles qui restent à définir.

Contexte

Aujourd'hui, les demandes des clients d'UMARIS arrivent par plusieurs canaux : mail, téléphone, formulaires. Il en résulte des pertes d'information, aucune visibilité sur l'avancement et des difficultés à prioriser. La plateforme doit centraliser les demandes, permettre leur suivi, les prioriser, automatiser les notifications et piloter l'activité.

Deux personas guident la conception :

Bernard, client, sur smartphone : il veut faire une demande vite et savoir où elle en est sans avoir à appeler.
Claire, chargée de relation client, sur ordinateur : elle veut une vue unique des demandes, triées par priorité.
Utiliser le prototype
La barre noire en haut mène directement au début de chaque parcours.
Les boutons et les liens des écrans font passer d'un écran à l'autre, comme dans l'application.
Les encadrés en pointillés « Variantes du flow » n'existeront pas dans l'application. Ils servent seulement à ouvrir les écrans d'erreur pendant les tests.
Le prototype fonctionne dans n'importe quel navigateur, sur ordinateur comme sur smartphone, sans compte ni installation.
Parcours couverts

Les parcours couvrent les 6 user stories « Must have » du MVP.

Parcours	Utilisateur	Stories	Écrans
UF1 · Se connecter (lien envoyé par mail, sans mot de passe)	Bernard	M1	5
UF2 · Soumettre une demande	Bernard	M2, M6	5
UF3 · Suivre sa demande	Bernard	M6	2
UF4 · Retrouver ou saisir une demande	Claire	M3	2
UF5 · Qualifier et prioriser	Claire	M5	3
UF6 · Traiter une demande	Claire	M4, M6	5

Au total : 22 écrans. Chaque écran correspond à un rectangle « écran » des user flows.

Cas d'erreur et cas limites représentés
UF1 : adresse inconnue, lien expiré
UF2 : champ obligatoire manquant, échec de l'envoi
UF6 : clôture refusée sans responsable, fiche modifiée par un collègue pendant la saisie
Tests utilisateurs
5 testeurs, en visio de 30 minutes, en test modéré : le testeur pense à voix haute.
Chaque testeur suit les parcours qui correspondent à son profil, Bernard ou Claire.
Les observations sont notées dans une grille de relevé, avec les réussites, les points de blocage et leur gravité.
Contenu du dépôt
Fichier	Rôle
index.html	Le prototype complet, en un seul fichier autonome
README.md	Ce document
Mettre à jour le prototype
Renommez la nouvelle version en index.html.
Cliquez sur Add file, puis sur Upload files, déposez le fichier, puis cliquez sur Commit changes.
Le lien ne change pas. La mise à jour est en ligne après quelques minutes.
Points encore à définir
La durée de validité du lien de connexion
La liste des types de demande et des niveaux de priorité
Les champs obligatoires et la longueur maximale de la description
Le contact affiché en cas d'adresse inconnue
La règle à appliquer quand deux personnes modifient la même demande en même temps
Hors périmètre de cette version

Ces sujets ne sont pas couverts par la version actuelle : les fonctions IA, l'application mobile native, l'intégration à l'ERP et la transmission des demandes au bureau d'études. Cette dernière est prévue pour une phase 2.
