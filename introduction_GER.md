[English version of this page](https://github.com/FLMRobert/open-source-compliance/blob/main/introduction_EN.md)

# Open Source Software Grundlagen

## OSS Einleitung

Open Source Software (OSS) wird  häufig auf nur zwei Eigenschaften reduziert:
- Software, deren Quelltext verfügbar ist
- Software, die kostenlos erhältlich ist

### OSS Freiheiten

Tatsächlich ist Open Source Software durch vier Freiheiten charakterisiert:
- der **Quelltext** der Software ist verfügbar / die Software kann **analysiert** werden
- die Software darf **beliebig kopiert, verbreitet und genutzt** werden
- die Software darf **verändert** werden
- **veränderte Software** darf **weitergegeben** werden

### OSS Definition

Die genaue Bedeutung des Begriffs Open Source Software wird unterschiedlich definiert. Die wichtigsten Definitionen sind hier zu finden: 

- Definition bei Wikipedia: https://de.wikipedia.org/wiki/Open_Source
- Definition der Open Source Initiative: https://opensource.org/docs/osd- 
- Definition der Free Software Foundation: https://www.fsf.org/about/what-is-free-software


### Kostenlos versus Frei

Der Aspekt "kostenlos" ist in der klassischen Definition von Open Source nicht enthalten, da Open Source Software nicht zwinged kostenlos sein muss.
Der Begriff "FLOSS" (Free/Libre Open Source Software) verdeutlicht dies dadurch, indem er betont, dass "Free" im Sinne von "Freiheit" zu interpretieren ist. 

## Urheberrecht und Nutzungsrecht

Die vier Freiheiten, die Open Source Software dem Nutzer einräumt, sind keine Selbstverständlichkeiten.

Software zählt nach dem Deutschen Urheberrecht zu den geschützten Werken (wie z.B. auch schriftstellerische Texte, Musik oder Filme). Auch im Rest der Welt existieren Copyright-Gesetze, die dem Deutschen Urheberrecht entsprechen. In der "Berner Übereinkunft" haben insgesamt 170 Staaten den Schutz von kreativen Werken anerkannt.

Nach dem Urheberrecht liegen alle Rechte an der Software zunächst nur beim Autor der Software. Will der Autor der Software anderen Personen ein Nutzungsrecht einräumen, so muss er die Software unter eine Lizenz stellen.

## OSS Lizenzen

Open Source Lizenzen sind Dokumente, die dem Nutzer von Open Source Software bestimmte Rechte einräumen. Die Lizenzen enthalten jedoch auch Pflichten. Nur wer die Pflichten der Lizenz erfüllt, kann auch die eingeräumten Nutzungsrechte beanspruchen.

Viele Lizenz-Pflichten sind leicht erfüllbar. Beispiele dafür sind:
- Nennung des Autors (Attribution)
- Beilegen des Lizenztexts
- Beibehalten von Copyright-Hinweisen

Manche Lizenz-Pflichten sind mit mehr Aufwand verbunden, oder haben weitreichende Konsequenzen für den Nutzer der Open Source Software. Ein Beispiel ist die sogenannte Copyleft-Bedingung.

### OSS Lizenz-Typen

Es gibt hunderte von unterschiedlichen Open Source Lizenzen, von denen jedoch nur einige Dutzend Lizenzen stärker verbreitet sind. 

Man unterscheidet grob zwischen drei Gruppen von Lizenzen
- Copyleft Lizenzen
- Weak Copyleft Lizenzen
- Permissive Lizenzen

## Copyleft Lizenzen

Copyleft Lizenzen enthalten eine Copyleft-Bedingung. Die Bedinung besagt, dass abgeleitete Werke unter die gleiche Lizenz wie das ursprüngliche Werk gestellt werden müssen. In manchen Fällen kann das bedeuten, dass eigener Quellcode offengelegt werden muss, wenn er mit  Quellcode unter einer Open Source Copyleft-Lizenz kombiniert wird.

Weak Copyleft Lizenzen enthalten ebenfalls eine Copyleft-Bedingung, wobei die Definition des abgeleiteten Werks stärker eingeschränkt ist.

## Permissive Lizenzen

Permissive Lizenzen enthalten keine Copyleft-Bedingung.

Um die Unterschiede zwischen verschiedenen Lizenzen herauszufinden, müssen die Lizenztexte verglichen werden. Auf dieser Website bekommt man einen schnellen Überblick über die Rechten und Pflichten verschiedener Open Source Lizenzen: https://tldrlegal.com/

## OSS Compliance

Bei Verletzung von OSS Lizenz-Pflichten erlischt das Nutzungsrecht, daher ist die Einhaltung der Pflichten wichtig. Werden alle Pflichten einer OSS Lizenz eingehalten, so spricht man von Open Source Compliance.

Open Source Compliance ist insbesondere bei Nutzung von OSS in kommerziellen Softwareprodukten wichtig, da andernfalls großer finanzieller Schaden enstehen kann (z.B. durch Lizenzverletzungs-Klagen, oder weil ein Produkt wegen Lizenzverletzungen vom Markt genommen werden muss).

Die Herstellung von Open Source Compliance ist eine anspruchsvolle Aufgabe. Das trifft insbesondere auf komplexe Softwareprojekte zu in denen viele Open Source Komponenten miteinander kombiniert werden, oder Open Source Software modifiziert wird. Häufig ist juristisches Wissen erforderlich, um z.B. Lizenzkonflikte aufzulösen oder Copyleft-Effekte in abgeleiteten Werken korrekt zu bewerten.

## Open Source Management (OSM)

Damit die Herstellung von Open Source Compliance nicht dem Zufall überlassen wird, etablieren immer mehr Softwareunternehmen Open Source Management (OSM) Prozesse. Das Durchlaufen der OSM-Prozesse wird als Open Source Clearing bezeichnet.

Mit formalisierten OSM-Prozessen und Tools kann das Clearing von OSS Komponenten erheblich erleichtert werden. Noch gibt es keine standardisierte Vorgehensweise für diesen Clearing Prozess, jedoch sind derzeit algemein akzeptierte Standards für Open Source Management im Entstehen.

### Open Source Management Tools
Beispiele für gängige Open Source Tools sind 
- Online Informationsquellen zur Recherche
- Tools für die Überprüfung von Komponenten auf Abhängigkeiten zu Open Source Komponenten
- Tools für die Überprüfung von Quellcode auf enthaltene Open Source Komponenten (sogenannte Open Source Scanner)
- Tools für die Erstellung von Open Source Stücklisten (Bill of Material)


## Open Source Grundlagen für Entwickler

- Wichtige Informationen zu OpenSource Komponenten als Grundlage für BoM, fulfillment package
- Einschätzung von Lizenzen (Klassifizierung, Freiheiten, Pflichten, Kompatibilität, Architektur (linking))
- Informationsquellen (GitHub & Co, Lizenzen, Lizenztexte, Lizenznamen, Archive Org)

## Open Source Management im Unternehmen

OpenSource Management in Unternehmen
- Open Source Strategie
- OSM Prozesse (OpenChain)
- OSS Tools (component scanning, snippet scanning)
- Informationsquellen (Lizenzen, Lizenztexte, Lizenznamen)
