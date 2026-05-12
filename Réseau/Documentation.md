# 🌐 Réseau

## 🎯 Objectif
Configurer DHCP et DNS pour un environnement entreprise.

---

## 📡 DHCP

### Configuration :
- Scope : 192.168.1.40 → 192.168.1.230
- Exclusion : 192.168.1.80 → 192.168.1.85
- Réservation : 192.168.1.200 (client)

![DHCP Scope](./Captures/DHCP/Capture%20d’écran%20(541).png)  

![DHCP Scope](./Captures/DHCP/Capture%20d’écran%20(542).png)  

![DHCP Scope](./Captures/DHCP/Capture%20d’écran%20(543).png)

![DHCP Scope](./Captures/DHCP/Capture%20d’écran%20(544).png)  

![DHCP Scope](./Captures/DHCP/Capture%20d’écran%20(545).png)  

![DHCP Scope](./Captures/DHCP/Capture%20d’écran%20(547).png) 

![DHCP Scope](./Captures/DHCP/Capture%20d’écran%20(548).png)  

![DHCP Scope](./Captures/DHCP/Capture%20d’écran%20(549).png)  

---

## 🌍 DNS

### Load Balancing :
- www.rev.local → 2 IP :
  - 192.168.1.8
  - 192.168.1.9

[ dns configuration ](./Captures/DNS/Capture%20d’écran%20(549).png)

---

## 🧠 Résultat

- Attribution IP automatique
- Haute disponibilité DNS & Configuration DHCP
