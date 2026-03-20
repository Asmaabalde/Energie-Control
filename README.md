# 🔌 Energie-Control — Outil de gestion d’interventions (Projet PHP)

Projet réalisé dans le cadre du cours **Développement Web PHP** (Université Paris Cité).  
Durée : **15/01/2024 → 22/03/2024**

Ce projet consistait à développer un outil complet de gestion d’interventions pour une société fictive, **AccordEnergie**, en utilisant PHP, MySQL et le moteur de templates **Twig**.

---

## 🎯 Objectifs pédagogiques

- Découvrir l’environnement PHP et les bonnes pratiques backend  
- Concevoir un **MCD** et un schéma de base de données  
- Réaliser un **diagramme de Gantt**  
- Implémenter un système d’authentification  
- Manipuler une base MySQL (CRUD complet)  
- Structurer une application PHP avec des **classes** pour la rendre modulable  
- Utiliser **Twig** pour séparer logique et affichage  

---

## 🧠 Compétences acquises

- Connexion à une base MySQL  
- Gestion des rôles utilisateurs  
- Création de CRUD complets  
- Architecture MVC simplifiée  
- Utilisation de Twig pour les vues  
- Gestion d’interventions, statuts, urgences, commentaires  
- Tri dynamique des tableaux (A→Z / Z→A)  

---

## 🏗️ Fonctionnalités principales

### 🔐 Authentification & rôles
4 types d’utilisateurs :
- **Admin** : accès complet, gestion des listes (CRUD)  
- **Standardiste** : création/modification/annulation d’interventions  
- **Intervenant** : suivi des interventions assignées  
- **Client** : suivi de ses interventions + commentaires  

### 🛠️ Gestion des interventions
- Création d’une intervention  
- Attribution à un ou plusieurs intervenants  
- Statut de suivi  
- Degré d’urgence  
- Commentaires  
- Historique des interventions  

### 📊 Tri dynamique
Les tableaux peuvent être triés en cliquant sur les en-têtes (A→Z puis Z→A).

---

## 🗂️ Technologies utilisées

- **PHP 8+**  
- **MySQL**  
- **Twig**  
- **HTML/CSS**  
- **Architecture MVC simplifiée**

---

## 📦 Installation

```bash
git clone https://github.com/Asmaabalde/Energie-Control.git
cd Energie-Control
composer install
