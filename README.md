# Projet-AD
Projet AD


# 🏢 REV ENTERPRISE LAB — Help Desk Project

---

## 📋 Description

Ce projet simule un environnement d’entreprise complet basé sur **Active Directory**.

Objectif : démontrer des compétences réelles de technicien Help Desk / Support TI :

- Gestion des utilisateurs et groupes
- Administration Active Directory
- Configuration GPO
- Support poste client
- Gestion réseau (DHCP, DNS)
- Sécurité et restrictions utilisateurs

---

## 🎯 Environnement

| Élément        | Valeur            |
|---------------|------------------|
| Domaine       | rev.local        |
| Serveur       | PDC              |
| IP Serveur    | 192.168.1.X      |
| Client        | HRPC01           |
| OS            | Windows Server / Windows 10 |

---

## 🗂️ Documentation

### 🔵 Active Directory
➡️ [Voir la documentation](./Active%20Directory/documentation.md)

- Structure OU
- Création des utilisateurs
- Groupes de sécurité

---

### 🟣 GPO (Group Policy)
➡️ [Voir la documentation](./GPO/Documentation.md)

- Restrictions utilisateurs
- Désactivation CMD / Control Panel
- Blocage stockage externe

---

### 🌐 Réseau
➡️ [Voir la documentation](./Réseau/Documentation.md)

- DHCP (scope + exclusions)
- DNS (load balancing)

---

### 📁 File Server
➡️ [Voir la documentation](./Serveur-de-fichiers/Documentation.md)

- Dossiers partagés
- Map drive (Public / HR)
- Quotas disque

---

### 💻 Client Machine
➡️ [Voir la documentation](./Machine-cliente/Documentation.md)

- Jointure domaine
- Ajout admin local

---

### 🔐 Sécurité
➡️ [Voir la documentation](./Sécurité/Documentation.md)

- Password policy
- Account lockout
- Restrictions exécutables

---

### 📸 Screenshots
➡️ [Voir les captures](./07-Screenshots/)

Preuves visuelles du lab :

- Active Directory
- GPO
- DHCP / DNS
- Partages réseau
- Poste client

---

## ⚙️ Fonctionnalités implémentées

✔ Domaine Active Directory (rev.local)  
✔ OU par département (HR, Sales, IT)  
✔ Utilisateurs + groupes  
✔ Machine Windows 10 join au domaine  
✔ IT-Group ajouté admin local  
✔ GPO restrictions utilisateurs  
✔ Blocage CMD / Control Panel  
✔ Blocage stockage externe (except IT)  
✔ Politique mot de passe sécurisée  
✔ Lockout après tentatives échées  
✔ DHCP configuré + réservation IP  
✔ DNS load balancing  
✔ Drive réseau (Public + HR)  
✔ Quota disque 2GB  
✔ Restrictions fichiers exécutables  

---

## 🔥 Cas réel Help Desk

Ce lab simule des tâches quotidiennes :

- Reset password
- Gestion accès utilisateur
- Troubleshooting GPO
- Problèmes de login domaine
- Accès refusé aux dossiers
- Map drive manquant
- DHCP / IP issues

---

## 🚀 Objectif

Projet conçu pour :

- CV technicien informatique
- Portfolio GitHub
- Entrevue Help Desk

---

## 👤 Auteur

Technicien informatique orienté support et systèmes  
Passionné par les environnements entreprise (AD, GPO, réseau)
