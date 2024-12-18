# Système de Suivi de Commandes - Frontend

## Description
Cette application frontend permet aux utilisateurs de suivre des commandes, de modifier leur statut et de recevoir des notifications en temps réel. Développée avec Vue.js, elle offre une interface utilisateur réactive et conviviale.

## Fonctionnalités
- **Affichage de la Liste des Commandes** : Visualisez toutes les commandes avec leurs détails (ID, produit, client, statut, date).
- **Pagination et Filtrage** : Filtrez les commandes par statut ou date pour une navigation facile.
- **Détails de la Commande** : Cliquez sur une commande pour voir ses détails, y compris l'historique et les informations sur le client.
- **Modification du Statut** : Changez le statut des commandes (En attente, Expédiée, Livrée, Annulée) avec mise à jour instantanée de l'affichage.
- **Notifications** : Recevez des alertes visuelles lors des changements de statut (fonctionnalité optionnelle utilisant Kafka).

## Technologies Utilisées
- Vue.js
- Vue Router
- Axios
- Bootstrap/Vuetify (au choix pour le design)

## Installation
1. Clonez le dépôt :
   ```bash
   git clone https://github.com/votre-utilisateur/suivi-commandes-frontend.git
   cd suivi-commandes-frontend
   
2. Installez les dépendances :
   ```bash
   npm install
   
3. Lancez l'application :
   ```bash
   npm run serve

4. Accédez à l'application à l'adresse http://localhost:8080.

Les contributions sont les bienvenues ! Veuillez soumettre une pull request avec des commentaires sur les modifications.

@BiKadri
