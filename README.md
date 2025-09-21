# 2ESGI-PA
Projet annuel 2eme année ESGI 
# 🚀 Business Care 

## 📌 Présentation
**Business Care (BC)** est une solution destinée à améliorer la santé, le bien-être et la cohésion en milieu professionnel.  
Ce projet a été développé dans le cadre du **projet annuel 2024-2025 à l’ESGI** et comprend :  

- Une **application web** pour la gestion des clients, salariés et prestataires  
- Un **backoffice d’administration** centralisant les données  
- Des **services supplémentaires** (application Android, application Java de reporting, intégration NFC…)  
- Une **infrastructure réseau et système sécurisée** (multi-sites, VPN, firewall, supervision)  

---

## 🖥️ Fonctionnalités principales

### 🔹 Entreprises clientes
- Gestion des contrats et abonnements (paiement en ligne via **Stripe**)  
- Devis en temps réel & facturation automatisée (**PDF**)  
- Gestion des collaborateurs  

### 🔹 Salariés
- Réservation d’événements et services (webinars, conférences, RDV médicaux, sport, etc.)  
- Chatbot d’assistance & signalement anonyme  
- Espaces : **Conseils**, **Associations**, **Communautés**  
- Notifications push (**OneSignal**)  
- Tutoriel interactif à la première connexion  

### 🔹 Prestataires
- Gestion des prestations, disponibilités et interventions  
- Évaluations et suivi qualité  
- Facturation automatique et archivage mensuel  

### 🔹 Administration
- Gestion centralisée des sociétés, contrats, salariés, prestataires  
- Suivi des événements et du catalogue de prestations  
- Gestion financière  

---

## ⚙️ Stack technique

### 🌐 Application Web
- **Frontend** : Angular + TailwindCSS  
- **Backend** : Node.js / NestJS (API REST)  
- **Base de données** : MySQL / PostgreSQL  
- **Paiement en ligne** : Stripe  
- **Notifications push** : OneSignal  
- **PDF** : pdfmake / jsPDF  

### 📊 Services supplémentaires
- Application **Java** autonome pour reporting et génération de graphiques PDF  
- Application **Android** (accès salarié aux événements et plannings)  
- Carte **NFC** pour l’accès aux locaux  

### 🖧 Infrastructure
- Virtualisation : VMware / Proxmox / GNS3  
- Réseau multi-sites interconnectés par **VPN IPsec GRE**  
- Firewall & sécurité : **OPNSense**  
- Supervision : **Zabbix / Nagios**, **GLPI**  
- Sauvegardes automatiques (**TrueNAS / Veeam**)  

---

## 📂 Organisation du dépôt
