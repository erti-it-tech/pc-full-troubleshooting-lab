# Dépannage complet d’un PC utilisateur — Lab professionnel

Ce projet présente un **cas complet de dépannage d’un poste Windows**, comme dans un environnement professionnel.  
Le but est de démontrer une démarche structurée de technicien support (N1/N2) :

- recueillir l’information utilisateur  
- analyser le système et les performances  
- diagnostiquer les problèmes réseau  
- vérifier les services essentiels (DNS, firewall, pilotes, Office, etc.)  
- appliquer des correctifs précis  
- documenter chaque action  
- valider la résolution

---

# 🎯 Objectif du projet

Créer un **scénario réaliste** de panne utilisateur, le diagnostiquer, puis le résoudre avec une démarche ITIL et des outils professionnels.

Le projet montre la capacité à :

- travailler méthodiquement  
- utiliser PowerShell pour l’analyse  
- analyser un environnement Windows  
- résoudre un incident de A à Z  
- rédiger une documentation claire, utile à un futur employeur  

---

# 📂 Structure du dépôt
````
pc-full-troubleshooting-lab/
│
├── README.md
│
├── 00_scenario.md
├── 01_initial_diagnosis.md
├── 02_system_checks.md
├── 03_network_checks.md
├── 04_office_outlook_checks.md
├── 05_event_logs_analysis.md
├── 06_actions_taken.md
└── 07_resolution_report.md
````

---

# 📘 Contenu des fichiers

### **00_scenario.md**
Description du problème utilisateur comme dans un ticket réel.

### **01_initial_diagnosis.md**
Premières questions, hypothèses, test basique (ping, ipconfig, Task Manager).

### **02_system_checks.md**
Analyse CPU/RAM, services Windows, drivers, disque.

### **03_network_checks.md**
Tests DNS, DHCP, ping passerelle, port 443, résolution de nom.

### **04_office_outlook_checks.md**
Tests Outlook, profil corrompu, connectivité M365, fichiers .OST.

### **05_event_logs_analysis.md**
Analyse du journal d’événements (Application / Système).

### **06_actions_taken.md**
Toutes les actions concrètes prises pour résoudre le problème.

### **07_resolution_report.md**
Rapport final avant/après + validation utilisateur.

---

# 🧰 Outils utilisés

- PowerShell  
- ipconfig /all  
- ping, tracert  
- Test-NetConnection  
- Gestionnaire des tâches  
- Observateur d'événements  
- Services Windows (services.msc)  
- Outlook.exe /safe  
- Nettoyage Windows (temp, cache, etc.)

---

# 👨‍💻 Auteur

Erti — Technicien en informatique

GitHub : https://github.com/erti-it-tech

