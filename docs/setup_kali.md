# 🐉 Setup: Kali Linux

## Ziel

Einrichten einer Kali Linux VM als Angreifer-System.

---

## Download

Kali Linux wurde als fertige VirtualBox-VM heruntergeladen:

https://www.kali.org/get-kali/

→ Bereich: *Virtual Machines*

---

## Import in VirtualBox

1. VirtualBox öffnen
2. Datei → Appliance importieren
3. Kali OVA-Datei auswählen

---

## Einstellungen

Folgende Ressourcen wurden zugewiesen:

* RAM: 4096 MB
* CPU: 2 Kerne

---

## Netzwerk

Adapter 1:

* Modus: Host-Only Adapter

Optional:

* Adapter 2: NAT (für Internetzugang)

---

## Start & Login

Nach dem Start:

* Benutzer: kali
* Passwort: kali

---

## IP-Adresse prüfen

```bash
ip a
```

Beispiel:

```txt
192.168.56.101
```

---

## Ergebnis

Kali Linux läuft erfolgreich und ist im lokalen Netzwerk erreichbar.
