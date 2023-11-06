# m346
pekoms.-

1. [KN01](#kn01)
2. [KN02](#kn02)
3. [KN03](#kn03)
4. [KN04](#kn04)
5. [KN05](#kn05)
6. [KN06](#kn06)
7. [KN07](#kn07)
8. [KN08](#kn08)
9. [KN09](#kn09)

# KN01
### CPU mit weniger Cores than Gast-System
<img src="KN01/m346KN01lessCPU.png" alt="CPU with fewer Cores than Gast-System" width="800">

### CPU mit mehr Cores than Gast-System
<img src="KN01/m346KN01moreCPU.png" alt="CPU with too many Cores as Gast-System" width="800">


Hyper-Threading ermöglicht virtuelle Threads auf physischen CPU Kernen zu erstellen, somit kann man die Nutzung der Kerne effizienter machen. Es erlaubt die gleichzeitige Ausführung von mehreren Aufgaben.

### Weniger RAM als Gast-System
<img src="KN01/m346KN01lessRAM.png" alt="Less RAM than Gast-System" width="300">

### Mehr RAM als Gast-System
<img src="KN01/m346KN01moreRAM.png" alt="More RAM than Gast-System" width="300">

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
### Ein Screenshot der Details oder Liste der Instanz + "Key pair assigned at launch".
<img src="KN03 Cloud-init und AWS\D\Screenshot 2023-10-23 085055.png" alt="HTML-Seite, inkl. URL" width="800">

### Screenshot mit dem ssh-Befehl und des Resultats unter Verwendung des ersten Schlüssels.
<img src="KN03 Cloud-init und AWS\B\Key1.png" alt="HTML-Seite, inkl. URL" width="800">

### Screenshot mit dem ssh-Befehl und des Resultats unter Verwendung des zweiten Schlüssels.
<img src="KN03 Cloud-init und AWS\B\Key2.png" alt="HTML-Seite, inkl. URL" width="800">

### Screenshot mit dem Auszug aus dem Cloud-Init-Log.
<img src="KN03 Cloud-init und AWS\B\AuszugCloudInit.png" alt="HTML-Seite, inkl. URL" width="800">

## C) Template
[Yamls](https://github.com/burak-adanir/m346/tree/main/KN03%20Cloud-init%20und%20AWS/yamls)

## D) Auftrennung von Web- und Datenbankserver
### Beweisführung DB Server
<img src="KN03 Cloud-init und AWS\D\Screenshot 2023-10-23 105959.png" alt="HTML-Seite, inkl. URL" width="800">
<img src="KN03 Cloud-init und AWS\D\telnet.png" alt="HTML-Seite, inkl. URL" width="800">

### Beweisführung Web Server
<img src="KN03 Cloud-init und AWS\D\indexhtmkn03.png" alt="HTML-Seite, inkl. URL" width="800">
<img src="KN03 Cloud-init und AWS\D\infophpkn3d.png" alt="HTML-Seite, inkl. URL" width="800">
<img src="KN03 Cloud-init und AWS\D\screenshot db.png" alt="HTML-Seite, inkl. URL" width="800">
<img src="KN03 Cloud-init und AWS\D\IMG_1347.jpg" alt="HTML-Seite, inkl. URL" width="800">

# KN04
## A) Bild erstellen und auf S3 hosten
### Screenshot der S3-Objekte im Bucket
<img src="KN04\KN04A1.png" alt="HTML-Seite, inkl. URL" width="800">

### Screenshot des Bildes im Browser (mit sichtbarer URL)
<img src="KN04\KN04A2.png" alt="HTML-Seite, inkl. URL" width="800">

## B) Web-Server mit PHP-Seite hinzufügen
### Screenshot der Seite image.php (mit sichtbarer URL)
<img src="KN04\KN04B1.png" alt="HTML-Seite, inkl. URL" width="800">
https://github.com/burak-adanir/m346/blob/main/KN04/cloud-init.yaml

## C) Elastic Block Storage (EBS) hinzufügen.
### Screenshots der Liste der EBS (2 Volumen) der Instanz
<img src="KN04\KN04C1.png" alt="HTML-Seite, inkl. URL" width="800">

## D) Speichereigenschaften erkennen
### Kategorisierung
| Name           | Typ  | Persistenz |
|----------------|------|------------|
| EBS Root       | Hot  | Nein       |
| EBS 2nd volume | Hot  | Ja         |
| S3             | Warm | Ja         |

EBS Root: Wird oft fürs Betriebssystem und Systemdateien verwendet. Darauf ist ein schneller Zugriff erfolderlich, weswegen ich es als "Hot" kategorisiert. Sie muss aber nicht unbedingt persistent sein, da es die Dateien nach dem herunterfahren der Instanz löscht.

EBS 2nd Volume: Dient oft als zusätzlicher Speicher für Daten, die häufiger geändert und aktualisiert werden. Man braucht einen schneller Zugriff und die Datenintegrität muss auch erhalten bleiben, deswegen "Hot" und "Ja" für Persistenz.

S3: Wird  für die Speicherung von Backups, Archiven und anderen Daten verwendet, die nicht häufig geändert werden. Zugriff darauf kann auch langsamer sein -> "Warm", aber die Persistenz ist wichtig, damit die Daten bei einem Ausfall noch vorhanden sind.

# KN05
## A) Diagramm erstellen
### Diagramm als Bild
<img src="KN05\KN05Diagram.png" alt="HTML-Seite, inkl. URL" width="800">

## B) Subnetz und private IP wählen 
### Screenshot der Subnetzen, die die Namen zeigen
<img src="KN05\KN05B.png" alt="HTML-Seite, inkl. URL" width="800">

### Zwei definierte IPs für Web- und DB-Server/Instanz
172.31.16.228, 172.31.21.248
## C) Objekte und Instanzen erstellen
### Screenshot der Liste der Sicherheitsgruppe mit sprechenden Namen/Feldern
<img src="KN05\KN05Infor.png" alt="HTML-Seite, inkl. URL" width="800">

### Screenshot der Inbound-Regel für die DB-Sicherheitsgruppe.
<img src="KN05\KN05CDBRUles.png" alt="HTML-Seite, inkl. URL" width="800">

### Screenshot der Liste der Elastic IPs mit sprechenden Namen.
<img src="KN05\KN05Elastic.png" alt="HTML-Seite, inkl. URL" width="800">

### Zeigen Sie, dass Sie nun alle drei Seiten aufrufen können (index.html, info.php und db.php)
<img src="KN05\Screenshot 2023-11-06 111330.png" alt="HTML-Seite, inkl. URL" width="800">
<img src="KN05\inforKN05.png" alt="HTML-Seite, inkl. URL" width="800">
<img src="KN05\image.png" alt="HTML-Seite, inkl. URL" width="800">

### Screenshot der Liste der Instanzen, wenn beide Instanzen gestoppt sind.
<img src="KN05\Stopp.png" alt="HTML-Seite, inkl. URL" width="800">
<img src="KN05\stopp2.png" alt="HTML-Seite, inkl. URL" width="800">

### Screenshot der Details beider Instanzen, so dass die Subnet ID sichtbar ist.
<img src="KN05\summary1.png" alt="HTML-Seite, inkl. URL" width="800">
<img src="KN05\summary2.png" alt="HTML-Seite, inkl. URL" width="800">

### Cloud Init
](https://github.com/burak-adanir/m346/blob/main/KN07/cloud-init.yaml)
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

## 3) Repurchasing
### Zoho CRM 
<img src="KN07\Screenshot 2023-10-06 224545.png" alt="HTML-Seite, inkl. URL" width="800">

- Bei der Professional Subscription hat man die meisten Grundlegenden Funktionen, die Enterprise Version würde ich bei der Grösse des Unternehmens nicht nehmen, sie wäre auch viel teurer.
  
### SalesForce
<img src="KN07\Screenshot 2023-10-02 110638.png" alt="HTML-Seite, inkl. URL" width="800">

- Hier habe ich Starter Version genommen, der Preisunterschied zum nächsten ist erheblich, dies macht auch bei der Grösse des Teams viel mehr Sinn für mich.

## B) Interpretation der Resultate
### Wie stark unterscheiden sich die Angebote?
Die Angebote sind bei allen recht ähnlich, ausser dass man bei Replatforming und Repurchasing nicht eine Präzisere Auswahl zur Verfügung hat. 

### Welches ist das billigste?
Rehosting, bei beiden Anbietern (Azure und AWS) kostet es fast gleich.

### Wieso ist eines davon viel teurer? Ist es aber wirklich teurer?
Ich denke Repurchasing und Replatforming sind teurer, da sie mehr Funktionen haben und auch härteren use-case haben.




