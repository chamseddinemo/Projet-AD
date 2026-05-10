# 🌐 Réseau

## 🎯 Objectif
Configurer DHCP et DNS pour un environnement entreprise.

---

## 📡 DHCP

### Configuration :
- Scope : 192.168.1.40 → 192.168.1.230
- Exclusion : 192.168.1.80 → 85
- Réservation : 192.168.1.200 (client)

![DHCP Scope](../Captures d'écran/reseau/dhcp-scope.png)

---

## 🌍 DNS

### Load Balancing :
- www.rev.local → 2 IP :
  - 192.168.1.8
  - 192.168.1.9

![DNS](../Captures d'écran/reseau/dns.png)

---

## 🧠 Résultat

- Attribution IP automatique
- Haute disponibilité DNS
