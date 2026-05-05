# 🎯 Setup: Metasploitable2

## Ziel

Einrichten eines absichtlich verwundbaren Zielsystems.

---

## Download

Metasploitable2 wurde heruntergeladen von:

https://sourceforge.net/projects/metasploitable/

---

## VM Erstellung

In VirtualBox:

1. Neue VM erstellen
2. Typ: Linux
3. Version: Ubuntu (32-bit)

---

## Ressourcen

* RAM: 1024 MB

---

## Festplatte

* Bestehende virtuelle Festplatte verwenden
* Datei: Metasploitable.vmdk

---

## Netzwerk

Adapter 1:

* Modus: Host-Only Adapter

---

## Start & Login

Nach dem Start:

* Benutzer: msfadmin
* Passwort: msfadmin

---

## IP-Adresse prüfen

```bash
ifconfig
```

Beispiel:

```txt
192.168.56.102
```

---

## Ergebnis

Metasploitable2 läuft erfolgreich und ist im Netzwerk erreichbar.
