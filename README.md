# Parrot VM Lab - VirtualBox lessenserie

Dit repository beschrijft een meer-delige lessenserie (5 lessen) om een veilige en reproduceerbare pentest-labomgeving op te zetten met Parrot OS in VirtualBox.  
Elke les krijgt zijn eigen repository of map: `les-1-virtualbox`, `les-2-hostonly`, `les-3-static-ip`, `les-4-scans`, `les-5-cmdb-report`.

## Doelgroep
Studenten Information Security, stagiairs en iedereen die veilig een labo wil opzetten om pentest-tools te leren gebruiken zonder risico voor productie- of openbare netwerken.

## Overzicht van de 5 lessen
- **Les 1 — VirtualBox basis & best practices**  
  Intro VirtualBox, snapshots, Guest Additions, netwerkmodi en veilige architectuur (Host-only + NAT).
- **Les 2 — Host-only netwerk aanmaken & IP-plan**  
  Host Network Manager, vboxnet0 configuratie, waarom DHCP uit/aan en voorbeeld IP-plan.
- **Les 3 — Statische IP toewijzen in Parrot & target VMs**  
  `nmcli`, `ip` en `ifconfig` voorbeelden, persistente configuratie en controle.
- **Les 4 — Basis scans en outputs**  
  `nmap`, `nikto`, `gobuster` commando's, nmap XML export en veilige testregels.
- **Les 5 — Rapportage & CMDB integratie**  
  Kort rapportformat, velden voor CMDB, nmap-xml -> JSON script en voorbeeld CSV/JSON export.

## GitHub structuur en workflow (aanbevolen)
Voor elke les maak je een aparte repo of map. Een aanbevolen layout per les:


**Commit & push workflow (kort):**
```bash
git init
git add .
git commit -m "Les X: korte omschrijving"
git remote add origin https://github.com/<jouw>/les-X-naam.git
git branch -M main
git push -u origin main


