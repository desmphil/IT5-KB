# Points à réviser avant publication ou utilisation par un chatbot

Cette liste est ajoutée par la migration. Elle ne fait pas partie des procédures originales.

- **Ensemble de la base** : le propriétaire indique que certaines sections ne sont pas terminées. Des blocs Google Sites vides ont été omis; ils peuvent être de simples espacements, pas nécessairement des instructions manquantes. Chaque article reste marqué `imported-needs-review`.
- **Accueil** : le bouton « IMPRIMANTE » pointe vers la page du tourniquet dans le site source. Cette destination a été conservée dans `articles/home.md`; la table des matières du README pointe vers le véritable article d’imprimante.
- **Musique** : des instructions sont explicitement réservées à l’administration, notamment la reconnexion des comptes Spotify. Séparer l’assistance utilisateur de l’administration.
- **Google TV** : vérifier et réserver les manipulations de développement, de débogage et de configuration aux personnes autorisées.
- **Tourniquets et portes** : faire approuver les étapes mécaniques, d’accès au matériel et les redémarrages avant de les présenter à un utilisateur. Maintenir la distinction entre modèles de tourniquets.
- **Caméra** : valider les consignes de réinitialisation du navigateur et leurs effets avant utilisation automatique.
- **Imprimante / scan vers courriel** : le texte source propose un autre domaine de destination et évoque la Loi 25. Faire réviser cette consigne; ne pas automatiser l’envoi de documents vers des adresses personnelles ou non autorisées.
- **Imprimante** : le texte fait référence à un CHAT sur la page d’accueil. Vérifier et actualiser ce parcours d’assistance.
- **Captures d’écran** : inspecter les images avant de rendre un dépôt public (noms, adresses, identifiants, paramètres ou autres renseignements internes).
- **Liens externes** : les destinations ont été conservées, mais leur disponibilité et leur comportement n’ont pas tous été testés. Aucune installation, connexion, demande de support ou autre action externe n’a été exécutée.
- **Mise en page** : les colonnes et éléments visuels Google Sites deviennent une séquence linéaire en Markdown. Valider l’association entre chaque image et son instruction avant publication.

## Étape suivante proposée

Réviser d’abord les articles importés. Ensuite, créer des parcours de dépannage distincts (par exemple en JSON ou YAML) avec des questions courtes, des choix Oui / Non / Je ne sais pas, et une sortie vers le support. Aucun parcours ni diagnostic nouveau n’a été inventé dans cet import.
