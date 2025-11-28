# Vérifications système

## 1. Uptime
(Get-CimInstance Win32_OperatingSystem).LastBootUpTime


→ 10 jours → redémarrage recommandé

## 2. Espace disque
Get-PSDrive C

→ 8 Go libres → insuffisant

## 3. RAM / CPU
Checks via Task Manager :
- CPU entre 70 % et 100 %
- RAM 80 %

## 4. Services critiques
- Windows Update : Running
- OneDrive : Stopped
- Windows Search : Running

## Hypothèses
- Cache saturé
- Temp Windows plein
- Disque presque plein → ralentissements
