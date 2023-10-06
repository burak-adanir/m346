# m346
pekoms.-

1. [KN01](#kn01)
2. [KN02](#kn02)
3. [KN03](#kn03)

7. [KN07](#kn07)


# KN01
### CPU mit weniger Cores than Gast-System
<img src="KN01/m346KN01lessCPU.png" alt="CPU with fewer Cores than Gast-System" width="800">

### CPU mit mehr Cores than Gast-System
<img src="KN01/m346KN01moreCPU.png" alt="CPU with too many Cores as Gast-System" width="800">


Hyper-Threading ermöglicht virtuelle Threads auf physischen CPU Kernen zu erstellen, somit kann man die Nutzung der Kerne effizienter machen. Es erlaubt die gleichzeitige Ausführung von mehreren Aufgaben.

### Weniger RAM als Gast-System
<img src="KN01/m346KN01lessRAM.png" alt="Less RAM than Gast-System" width="800">

### Mehr RAM als Gast-System
<img src="KN01/m346KN01moreRAM.png" alt="More RAM than Gast-System" width="800">

### Gast-System Eigenschaften
<img src="KN01/m346KN01GastProof.png" alt="Gast-System" width="800">

# KN02
## A)a) Lab 4.1 - EC2
### HTML-Seite, inkl. URL
<img src="KN02 IaaS - Virtuelle Server/AWS Kurs/m346KN02-1.png" alt="HTML-Seite, inkl. URL" width="800">

### Liste der EC2-Instanzen
<img src="KN02 IaaS - Virtuelle Server/AWS Kurs/m346KN02-2.png" alt="HTML-Seite, inkl. URL" width="800">

### Details der Web Server-Instanz (öffentliche IP sichtbar)
<img src="KN02 IaaS - Virtuelle Server/AWS Kurs/m346KN02-3.png" alt="HTML-Seite, inkl. URL" width="800">

### Security-Group: Liste der Inbound-Regeln
<img src="KN02 IaaS - Virtuelle Server/AWS Kurs/m346KN02-4.png" alt="HTML-Seite, inkl. URL" width="800">


## A)b) Lab 4.2 - Buckets 
### Liste der Buckets
<img src="KN02 IaaS - Virtuelle Server/Lab 4.2 - Buckets/m346KN02B-01.png" alt="Liste der Buckets" width="800">

### HTML-Seite, inkl. URL.
<img src="KN02 IaaS - Virtuelle Server/Lab 4.2 - Buckets/m346N02B-2.png" alt="Liste der Dateien im Bucket" width="800">

### Liste der Dateien im Bucket
<img src="KN02 IaaS - Virtuelle Server/Lab 4.2 - Buckets/m346KN02B-03.png" alt="HTML-Seite, inkl. URL" width="800">

### Eigenschaften von "Static website hosting"
<img src="KN02 IaaS - Virtuelle Server/Lab 4.2 - Buckets/m346KN02B-04.png" alt="Eigenschaften von Static website hosting" width="800">

## B) Zugriff mit SSH-Key
### ssh-Befehl und das Resultat unter Verwendung des ersten Schlüssels
<img src="KN02 IaaS - Virtuelle Server/Zugriff mit SSH-Key/m346KN02BB01.png.png" alt="Eigenschaften von Static website hosting" width="800">

### ssh-Befehl und das Resultat unter Verwendung des zweiten Schlüssels
<img src="KN02 IaaS - Virtuelle Server/Zugriff mit SSH-Key/m346KN02BB02.png.png" alt="Eigenschaften von Static website hosting" width="800">

### Instanz-Detail mit Key
<img src="KN02 IaaS - Virtuelle Server/Zugriff mit SSH-Key/m346KN02BB03.png.png" alt="Eigenschaften von Static website hosting" width="800">

## C) Installation von Web- und Datenbankserver

### Apache
<img src="KN02 IaaS - Virtuelle Server/Installation von Web- und Datenbankserver/Installation von Web- und DatenbankserverBild1.png" alt="Eigenschaften von Static website hosting" width="800">

### PHP
<img src="KN02 IaaS - Virtuelle Server/Installation von Web- und Datenbankserver/Installation von Web- und DatenbankserverBild2.png" alt="Eigenschaften von Static website hosting" width="800">

### Database-Info
<img src="KN02 IaaS - Virtuelle Server/Installation von Web- und Datenbankserver/Installation von Web- und DatenbankserverBild3.png" alt="Eigenschaften von Static website hosting" width="800">

# KN03
## A) Cloud-init Datei

## B) SSH-Key und Cloud-init
### Ein Screenshot der Details oder Liste der Instanz, welcher den verwendeten Key zeigt.
<img src="KN02 IaaS - Virtuelle Server/AWS Kurs/m346KN02-2.png" alt="HTML-Seite, inkl. URL" width="800">

### Screenshot mit dem ssh-Befehl und des Resultats unter Verwendung des ersten Schlüssels.
<img src="KN02 IaaS - Virtuelle Server/AWS Kurs/m346KN02-2.png" alt="HTML-Seite, inkl. URL" width="800">

### Screenshot mit dem ssh-Befehl und des Resultats unter Verwendung des zweiten Schlüssels.
<img src="KN02 IaaS - Virtuelle Server/AWS Kurs/m346KN02-3.png" alt="HTML-Seite, inkl. URL" width="800">

### Screenshot mit dem Auszug aus dem Cloud-Init-Log.
<img src="KN02 IaaS - Virtuelle Server/AWS Kurs/m346KN02-4.png" alt="HTML-Seite, inkl. URL" width="800">

# KN07
## A) Kostenrechnung erstellen
### 1) Rehosting
### AWS
<img src="KN07\Screenshot 2023-10-02 104140.png" alt="HTML-Seite, inkl. URL" width="800">

Bei AWS habe ich zwei EC2 Instanzen am laufen, eines für die VM, die andere für die Datenbank. Unteranderem auch den Load Balancer und die Back-Up Option gemäss Vorgaben.
Bei der VM Instanz habe ich einen mit 2 Kernen und 2 GB RAM ausgewählt, da dieser mit der Preis-Leistung mir passte. Bei der Datenbank Instanz habe ich den billigsten mit 4 GB RAM genommen. Als Standort habe ich USA-West genommen, da sie am günstigsten war.

### Pro: 
- Die Backups sind im allgemeinen günstiger als bei Azure
- Der Webserver hat ein 5 Gbit Netzwerk
### Contra:
- Teurer Load Balancer

### AZURE
<img src="KN07\Screenshot 2023-10-02 095747.png" alt="HTML-Seite, inkl. URL" width="800">

Bei Azure habe ich immer die billigsten Möglichkeiten ausgewählt da sie eine übersichtlichere Auswahl hatten. Als Standort habe ich ebenfalls USA-West genommen, da sie wieder am günstigsten war. 

### Pro: 
- Load Balancer ist gratis
- Gute UI
### Contra:
- Teurere Instanzen

## 2) Replatforming
### Heroku
<img src="KN07\Screenshot 2023-10-02 105843.png" alt="HTML-Seite, inkl. URL" width="800">

- Standard 2X hat pro Instanz 1GB RAM, ist einbisschen wenig, allerdings ist der Preisunterschied auf die nächste Stufe zu hoch und man hat viel überschüssige Performance.


- Bei der Datenbank wurde 256 GB gewählt da 64 GB nicht gereicht hätte und 256 GB die nächst höhere ist.









