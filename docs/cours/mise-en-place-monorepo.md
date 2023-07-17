# S08 - oKanban - Mise en place

L'idée de cette aprem => regrouper le front et le backend dans un seul dépôt Github. 

De manière générale, les serveurs frontend et backend sont séparés. (2 serveurs)

Ici, on va regrouper le front et le back sur le même serveur, tout en conservant notre API et nos fichiers 'statiques'

Partons de notre application backend et on va rappatrier le front dedans

Idée : le backend doit "servir" statiquement les ressources frontend. 
- `app.use(express.static)` d'un dossier => `dist` ie, le dossier qui comporte le front compilé !

Répartition du code dans le dépôt : 
- le code backend est dans `app`
  - point d'entrée : `./index.js`
- le code frontend est dans `assets`
  - point d'entrée : `./index.html`

