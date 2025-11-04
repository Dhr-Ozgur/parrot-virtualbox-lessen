# Parrot VirtualBox Lessenserie

Welkom bij de **Parrot VirtualBox Lessenserie** — een stap-voor-stap handleiding om een veilige pentest-laboratoriumomgeving te bouwen met **Parrot OS** in **VirtualBox**.

Deze lessen zijn bedoeld voor studenten **HBO Informatica / Information Security**, en iedereen die wil leren hoe je een ethisch hacking-lab professioneel en verantwoord opzet.

---

## 🎯 Doel van de serie
Na het voltooien van deze 5 lessen kun je:
- Zelf een veilige virtuele pentestomgeving bouwen;
- VirtualBox-netwerken correct configureren (zonder risico voor echte netwerken);
- Basis pentest-tools gebruiken zoals `nmap`, `nikto`, `burp`, `gobuster`;
- Scanresultaten verwerken en rapporteren in een CMDB-achtige structuur.

---

## 📚 Overzicht van de lessen

| Les | Onderwerp | Wat je leert |
|-----|------------|--------------|
| **Les 1** | VirtualBox basisprincipes | Interface, snapshots, netwerkmodi, veilige architectuur (Host-only + NAT). |
| **Les 2** | Host-only netwerk en IP-plan | Host Network Manager gebruiken, IP’s plannen en isolatie begrijpen. |
| **Les 3** | Statische IP’s instellen | IP-adressen configureren in Parrot en Metasploitable. |
| **Les 4** | Basis netwerkscans | Nmap, Nikto en Gobuster gebruiken in een gecontroleerde omgeving. |
| **Les 5** | Rapportage & CMDB | Scanresultaten omzetten naar rapport of database (JSON/CSV). |

---

## 🧱 Projectstructuur
Elke les krijgt een eigen repository:

parrot-virtualbox-lessen/
└── les-1-virtualbox/
└── les-2-hostonly/
└── les-3-static-ip/
└── les-4-scans/
└── les-5-cmdb/


Zo blijft elke stap overzichtelijk en kun je makkelijk terugkijken naar eerdere onderdelen.

---

## ⚙️ GitHub Workflow

```bash
# Voorbeeld bij een nieuwe les
mkdir les-1-virtualbox
cd les-1-virtualbox
git init
git add README.md
git commit -m "Les 1: VirtualBox basisprincipes"
git branch -M main
git remote add origin https://github.com/Dhr-Ozgur/parrot-virtualbox-lessen
git push -u origin main
💡 Benodigdheden

VirtualBox (versie 7 of hoger)

Parrot OS (Security Edition aanbevolen)

8 GB RAM of meer

Basiskennis van Linux & netwerken

Enthousiasme 😎
📜 Licentie

MIT License – vrij te gebruiken voor studie en niet-commerciële projecten.
