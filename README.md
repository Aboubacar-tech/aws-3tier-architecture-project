# AWS 3-Tier Architecture Project

## 📌 Description
Ce projet démontre la mise en place d'une architecture 3-tier sur AWS, une architecture couramment utilisée dans les applications web modernes.

## 🏗️ Architecture
L’architecture est composée de 3 couches :

- **Presentation Layer (Web Server)** : EC2 dans un subnet public
- **Application Layer (App Server)** : EC2 dans un subnet privé
- **Database Layer (RDS)** : Base de données dans un subnet privé

## ⚙️ Services utilisés
- AWS VPC
- Subnets (Public & Private)
- Internet Gateway
- NAT Gateway
- EC2 (Bastion Host, Web Server, App Server)
- RDS (MariaDB)
- Security Groups

## 🔐 Sécurité
- Accès SSH via Bastion Host uniquement
- Base de données accessible seulement depuis App Server
- Subnets privés isolés

## 🚀 Étapes principales
1. Création du VPC et des subnets
2. Configuration des route tables
3. Mise en place des Security Groups
4. Déploiement des instances EC2
5. Installation des serveurs (Web & App)
6. Création de la base de données RDS
7. Tests de connectivité

## 🧪 Tests réalisés
- Connexion SSH via Bastion Host
- Ping entre serveurs
- Connexion à la base de données depuis App Server

## 📸 Architecture
Voir fichier `architecture.png`

## 🎯 Objectif
Comprendre comment sécuriser et structurer une application scalable dans le cloud AWS. 
