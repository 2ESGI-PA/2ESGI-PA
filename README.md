# 🚀 Business Care 

## 📌 Présentation
**Business Care (BC)** est une société innovante qui propose une solution numérique pour améliorer la santé, le bien-être et la cohésion en milieu professionnel.  

Ce projet, réalisé dans le cadre du **projet annuel 2024-2025 à l’ESGI**, couvre :  
- Une **application web** permettant la gestion des clients, salariés et prestataires  
- Une **application Android** destinée aux salariés pour gérer leurs événements et plannings  
- Une **application Java autonome** générant des rapports graphiques et statistiques  

Ces outils offrent une solution complète et moderne pour améliorer la qualité de vie au travail et faciliter la gestion des prestations proposées par Business Care.  

---

## 🖥️ – Application Web

### 🔹 Fonctionnalités principales

#### 👩‍💼 Côté entreprises clientes
- Gestion des **contrats** et abonnements (paiement en ligne via **Stripe**)  
- Suivi et validation des **devis** en temps réel  
- Gestion de la **facturation automatisée** (génération de factures PDF)  
- Ajout et gestion des **collaborateurs rattachés**  

#### 👨‍💻 Côté salariés
- Accès au **catalogue de services** et réservation (webinars, conférences, RDV médicaux, événements sportifs…)  
- Gestion des **plannings** et historique des activités  
- **Chatbot d’assistance** et possibilité de signalement anonyme  
- Accès à des espaces dédiés :  
  - **Conseils** (santé et bien-être)  
  - **Associations** (engagement solidaire)  
  - **Communautés** (partage et organisation d’événements entre salariés)  
- Tutoriel interactif affiché lors de la première connexion  

#### 🤝 Côté prestataires
- Suivi des prestations effectuées et des **évaluations** laissées par les salariés  
- **Validation du profil** et des habilitations avant mise en service  
- Gestion du **calendrier de disponibilité**  
- Génération et archivage des **factures mensuelles**  

#### 🛠️ Administration (back-office)
- Suivi global de l’activité (sociétés, contrats, salariés, prestataires)  
- Gestion du **catalogue des prestations**  
- Suivi des événements et interventions  
- Gestion financière complète (revenus, charges, paiements)  

---

## 📱  – Services supplémentaires

### 🔹 Application Android
- Accès personnalisé aux **événements** et **plannings** des salariés  
- Possibilité de réserver des activités directement depuis le mobile  
- Notifications en temps réel sur les mises à jour du planning  
- Interface simple et intuitive pour encourager l’usage quotidien  

### 🔹 Application Java autonome
Une application indépendante permettant de générer des **rapports statistiques visuels** pour aider la direction à la prise de décision.  

#### Données traitées :
- Comptes des sociétés clientes (abonnements, devis, factures)  
- Événements (type, fréquence, réservations associées)  
- Prestations (types, coûts, nombre d’événements associés)  

#### Sortie attendue :
Un rapport PDF composé de **3 pages de statistiques** :  
1. **Comptes clients** → diagrammes (camemberts, barres, etc.) + **Top 5 clients fidèles**  
2. **Événements** → répartition par type/fréquence + **Top 5 événements demandés**  
3. **Prestations** → répartition par type/coût/nombre + **Top 5 prestations fréquentes**  


---

## ⚙️ Stack technique

### 🌐 Application Web
- **Frontend** : Angular + TailwindCSS  
- **Backend** : NestJS (API REST)  
- **Base de données** : MySQL  
- **Paiement en ligne** : Stripe  
- **PDF** : pdfbox  

### 📱 Application Mobile
- **Android (Kotlin)**  
- Communication avec l’API backend  
- Notifications en temps réel  

### 📊 Application Java
- **Bibliothèques graphiques** : JavaFX / chartutils
- **Export PDF** :  pdfbox  
- Génération de graphiques et rapports  

---
