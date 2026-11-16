# Maroc·Patrimoine

## Démarrer le site

1. Installez les dépendances avec `npm install`.
2. Créez `.env` à partir de `.env.example`.
3. Ajoutez votre clé OpenAI dans `.env` : `OPENAI_API_KEY=...`.
4. Lancez `npm start`, puis ouvrez <http://localhost:3000>.

La clé reste côté serveur et ne doit jamais être ajoutée à `index.html` ni partagée publiquement. Le modèle peut être modifié avec `OPENAI_MODEL`. Les requêtes de chat sont limitées pour éviter les abus.