# Diagnostic initial

## Questions posées
- Depuis quand le problème apparaît ?  
- Est-ce que d’autres collègues ont le même problème ?  
- Le PC a-t-il été redémarré récemment ?  
- Le problème touche-t-il uniquement Outlook ou tout le PC ?  

## Observations rapides
- PC lent → suspicion RAM/CPU saturé
- Outlook bloque → profil corrompu possible
- OneDrive gris → erreur de connexion M365
- Pas de redémarrage récent → accumulation de cache/temp

## Tests rapides

### 1. Vérification réseau
ping google.com
ping 8.8.8.8

### 2. Informations IP
ipconfig /all

### 3. Gestionnaire des tâches
- CPU : 90 %
- RAM : 80 %
- `SearchUI.exe` et `Teams.exe` consomment beaucoup

Conclusion :  
→ problème système + réseau + M365 probable.
