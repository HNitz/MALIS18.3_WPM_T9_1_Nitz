# Ein Lösch-Tool für persönliche Daten in der Nationale Agentur (NA)

## Einführung
Die Nationale Agentur ist ähnlich dem DAAD zuständig für den Bereich der Auslandsmobilität von Auszubildenden und Berufsbildungspersonal. Sie fördert durch diverse Programme die Internationalierung und Mobilität in  der Berufsbilung. 
In der NA arbeiten verschiedene Fachteams mit mehreren Datenbanken, die vom Team „Finanzen und IT“ zentral verwaltet werden. Dazu gehören eine Datenbank mit E-Akten für das europaweite Programm Erasmus+ mit den Projektakten für jedes einzelne beantragte Mobilitätsvorhaben (Dateien, Prozesse, Verträge, Berichte, Monitoring, Beschwerden), das ständig mit der zentralen Datenbank der EU-Kommission synchronisiert wird, sowie das MySQL-basierte Förderportal Ausbildung Weltweit als Antragsportal für Projektträger. 
Dazu kommen interne Datenbanken: die mit SAP verknüpfte Huel-Anwendung zur Finanzüberwachung, eine interne Gutachter-Datenbank zur Verwaltung und Bewertung von Fördergutachten, ein Aktivitäten-Tool für das interne Berichtswesen und Dokumentation in der NA, ein Reporting-Tool zur Erstellung von Berichten und statistischen Visualisierungen sowie das Extranet. Die NA arbeitet hauptsächlich mit SQL-Servern und Access-Oberflächen. 

## Ziel
Es soll ein internes Tool erstellt werden, mit dem sich die Einhaltung der neuen Datenschutz-Grundverordnung effizient und zeitsparend umsetzen lässt. Derzeit müssen von allen Projektteams Verfahrensbeschreibungen für die Verarbeitung persönlicher Daten erstellt werden, z.B. der Zuwendungsempfänger/-Innen, Teilnehmer/-Innen, Gutachter/-Innen, Dolmetscher/-Innen usw. Die einzelnen Quell-Datenbanken sind zu komplex, nicht alle Mitarbeiter/-Innen sind damit vertraut. Außerdem ist die ständige manuelle Prüfung der zu löschenden Daten mit einem hohen Aufwand verbunden und sehr fehlerbehaftet.  Daher soll ein Lösch-Tracker erstellt werden, der auf die Informationen in  allen Datenbanken zugreift und die Mitarbeiter/-Innen an die fristgemäße Löschung personenbezogener Daten erinnert, wenn die automatisch erkannte Frist für das Projektende und das Ablaufen der Aufbewahrungspflicht eintritt. Dabei gibt es verschiedene Kategorien von Daten. Nicht mehr benötigte Daten (z.B. Geburtsdaten, Reisepass-Nummern,…) müssen unmittelbar nach der Beendung einer Aktivität gelöscht werden. Zahlungsrelevante Daten müssen zum Zweck der Rechnungsprüfung für eine Dauer von 10 Jahren archiviert werden. Darüber hinaus kann die Zustimmung zur  Speicherung inhaltlich relevanter Daten, z.B. Kontaktinformationen und Fachexpertise, bei den betreffenden Personen abgefragt werden, sodass diese Daten zum Zweck zukünftiger Aktivitäten erhalten bleiben. 

## Umsetzung

In Zusammenarbeit mit dem IT-Team der NA besteht eine gute Chance, dass diese Idee auch praktisch umgesetzt wird und kann damit in den allgemeinen Betrieb übernommen werden. Da diese Neuerung gut in Profil passt. Verbesserung





