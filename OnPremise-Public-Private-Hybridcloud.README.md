# OnPremise, Public-, Private-, Hybridcloud


## OnPremise

### Was bedeutet OnPremise?
Der Begriff "On Premise Software" (oder "On Premises", wie es korrekter wäre) bezieht sich auf die Bereitstellung von Computerprogrammen, die über lokale Computer installiert und betrieben werden.
Er leitet sich vom englischen "on the premises" ab: in den Räumlichkeiten (des Lizenzinhabers).
Das Konzept steht im Gegensatz zur Bereitstellung von Softwarediensten ausserhalb des Unternehmens, im SAAS-Modus oder im Cloud Computing, bei dem die Nutzung des Programms durch den Zugang zu einem Computer (oder einer Hardware-Architektur) aus der Ferne dank einer Internetverbindung erfolgt.

### Vorteile
Obwohl die On-Premise-Lösung die älteste (und am wenigsten "smarte") ist, bietet sie nach wie vor einige strategische Vorteile, die spezifischen Anforderungen gerecht werden:

- Ausschliessliche Kontrolle über Systeme und Daten.
- Interne Verwaltung von sensiblen und wichtigen Daten.
- Flexibilität.
- Engagiertes Unterstützungspersonal.
- Hohe Anfangsinvestitionen, die sich jedoch langfristig amortisieren.


## Public Cloud

### Was bedeutet Public Cloud?
Bei der öffentlichen Cloud handelt es sich um einen Pool virtueller Ressourcen (entwickelt unter Verwendung proprietärer, vom Anbieter verwalteter Hardware), die automatisch bereitgestellt und über eine Selbstbedienungsschnittstelle an mehrere Kunden verteilt werden können.
Dies ist ein direkter Weg, um die Arbeitslast bei unerwarteten Nachfrageschwankungen zu erhöhen.

In der Regel werden moderne öffentliche Clouds nicht als eigenständige Infrastrukturlösungen bereitgestellt, sondern als Kombination verschiedener Umgebungen, die ein höheres Mass an Sicherheit und Leistung, niedrigere Kosten und eine breitere Verfügbarkeit von Infrastruktur, Diensten und Anwendungen bieten.

### Aus welchen Elementen besteht eine Public Cloud?
#### Ressourcenzuweisung
Mieter ausserhalb der Firewall des Anbieters nutzen Cloud-Dienste und virtuelle Ressourcen der Infrastruktur, Plattformen und Software des Anbieters.

#### Nutzungsvereinbarungen
Ressourcen werden nach Bedarf verteilt, aber Umlagemodelle sind kein unverzichtbarer Bestandteil. Einige Kunden, z. B. Forschungsinstitute, die die Massachusetts Open Cloud nutzen, verwenden öffentliche Clouds kostenlos.

#### Verwaltung
Der Anbieter wartet die der Cloud zugrunde liegende Hardware, unterstützt das Netz und verwaltet die Virtualisierungssoftware.

### Wer bietet Public Clouds an?
Es gibt weltweit Tausende von Anbietern.
Die grössten und am weitesten verbreiteten Anbieter sind heute jedoch:
- Alibaba Cloud
- Amazon Web Services (AWS)
- Google Cloud
- IBM Cloud
- Microsoft Azure

### What you need is love.. *ehm* *ehm* Linux
[RedHat Video über Linux und Cloud](https://www.youtube.com/watch?v=Ir05ZGX4IT4)


## Private Cloud

### Was bedeutet Private Cloud?
Private Clouds sind Cloud-Umgebungen, die ausschliesslich dem Endnutzer vorbehalten sind und sich in der Regel innerhalb der Firewall des Nutzers befinden. Obwohl private Clouds üblicherweise vor Ort betrieben werden, neigen Unternehmen heute dazu, private Clouds in herstellereigenen Rechenzentren zu implementieren, die sich ausserhalb des Firmengeländes befinden.

Wenn die zugrundeliegende IT-Infrastruktur einem einzigen Kunden vorbehalten ist und der Zugang vollständig isoliert ist, werden alle Clouds privat.

### Wie funktionieren private Clouds?
Private Clouds beruhen auf einigen wenigen Technologien. Um zu verstehen, wie sie funktionieren, ist es jedoch wichtig zu wissen, wie Virtualisierung funktioniert.
Die Virtualisierung ermöglicht es einer privaten Cloud, die von der physischen Hardware bereitgestellten Ressourcen in gemeinsamen Pools zusammenzufassen.
Auf diese Weise muss die Cloud nicht Umgebungen schaffen, indem sie Ressourcen einzeln aus einer Reihe von physischen Systemen virtualisiert, sondern kann durch ein skriptgesteuertes Verfahren alle von einer einzigen Quelle bereitgestellten Ressourcen sammeln.

Durch die Hinzufügung einer Softwareebene für das Ressourcenmanagement können Administratoren die Kontrolle über die Infrastruktur, Plattformen, Anwendungen und Daten behalten, die in der Cloud genutzt werden sollen.
Das bedeutet, dass man in der Lage ist, die Cloud-Nutzung zu überwachen und zu optimieren, Integrationspunkte zu überwachen und Daten zu pflegen oder abzurufen.
Die Cloud wird zur Selbstbedienung, wenn die letzte Automatisierungsebene hinzugefügt wird, die menschliche Eingriffe durch wiederholbare Anweisungen und Prozesse ersetzt oder reduziert. Wenn dies abgeschlossen ist, wird der Satz von Technologien als private Cloud betrachtet.

### Erstellen einer Private Cloud
Die Cloud-Infrastruktur bezieht sich auf die für das Cloud-Computing erforderlichen Komponenten.
Die grundlegenden Elemente einer Cloud-Infrastruktur sind dieselben, unabhängig davon, ob es sich um eine private Cloud, eine öffentliche Cloud oder eine Kombination aus beidem handelt.

Jede Cloud erfordert ein Betriebssystem, z.B. Linux, aber die Cloud-Infrastruktur kann verschiedene Bare-Metal-, Virtualisierungs- oder Container-Software enthalten, die skalierbare Ressourcen abstrahiert, gruppiert und über ein Netzwerk gemeinsam nutzt.

Es ist möglich, eine private Cloud eigenständig aufzubauen, indem nur dedizierte Ressourcen verwendet werden, oder eine fertige Cloud-Infrastruktur wie OpenStack zu nutzen.


## Hybrid Cloud

### Was bedeutet Hybrid Cloud?
Eine hybride Cloud ist eine IT-Architektur, die ein gewisses Mass an Portabilität, Orchestrierung und Verwaltung von Arbeitslasten in zwei oder mehr Umgebungen bietet, die je nach Anforderungen Folgendes umfassen können.

- Mindestens eine Private Cloud und mindestens eine Public Cloud
- Zwei oder mehr Private Clouds
- Zwei oder mehr Public Clouds.
- Eine Bare-Metal- oder virtuelle Umgebung, die mit mindestens einer Public oder Private Cloud verbunden ist.

### Wann ist eine Cloud hybrid?
Jede Hybrid-Cloud muss:

- Mehrere Computer über ein Netzwerk verbinden.
- Konsolidierung der IT-Ressourcen.
- Skalierbar sein und eine schnelle Bereitstellung neuer Ressourcen ermöglichen.
- Ermöglichen Sie die Verschiebung von Workloads zwischen Umgebungen.
- Integrierung ein einziges Verwaltungstool.
- Orchestrierung von Prozessen durch Automatisierung.

### Wie funktioniert eine Hybrid-Cloud?
Öffentliche und private Clouds, die innerhalb einer hybriden Cloud betrieben werden, funktionieren ähnlich wie eigenständige öffentliche oder private Clouds:

- Local Area Network (LAN), Wide Area Network (WAN) oder Virtual Private Network (VPN) und/oder Application Programming Interfaces (APIs), die mehrere Computer verbinden.
- Virtualisierungstechnologien, Container oder Software-Defined Storage abstrahieren Ressourcen und gruppieren sie in Data Lakes.
- Eine Verwaltungssoftware ordnet die Ressourcen den Umgebungen zu, in denen die Anwendungen laufen, und stellt sie dann bei Bedarf mit Hilfe eines Authentifizierungsdienstes bereit.