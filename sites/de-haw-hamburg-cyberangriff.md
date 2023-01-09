### Aktueller wichtiger Sicherheitshinweis für Beschäftigte und Studierende der HAW Hamburg  ###

#### [Ändern Sie Ihre Passwörter und nutzen Sie Virenschutzprogramme!](javascript:void(0))  ####

Mit dem Angriff auf die IT-Infrastruktur der HAW Hamburg sind wahrscheinlich auch sensible persönliche Daten abgeflossen. Es gibt außerdem Hinweise darauf, dass den Angreifern nicht nur Passwörter für IT-Systeme der Hochschule bekannt sind, sondern es Ihnen möglicherweise auch geglückt ist, in Einzelfällen Passwörter hochschulferner Accounts wie beispielsweise von Amazon, Ebay etc. auszulesen. Einige wenige Angehörige der Hochschule berichten davon, dass probiert wurde, Zugang zu ihren Accounts auf Portalen oder Kommunikationssystemen im Internet zu erhalten.

Derzeit arbeitet das IT Service Center der HAW Hamburg (ITSC) unter Hochdruck an Möglichkeiten, alle Ihre Systeme zu überprüfen. Darüber hinaus ist es in der derzeitigen Situation sehr wichtig, dass Sie selbst im Zusammenhang mit den eigenen Endgeräten mögliche Sicherheitsrisiken zusätzlich minimieren.

**Für Rückfragen zu den hier beschriebenen Hinweisen wurde ein E-Mail-Postfach eingerichtet: [security (at) haw (dot) hamburg](#)**

**Beachten Sie folgendes:**

**1. Verändern Sie bitte Ihre Passwörter**

Alle Ihre Passwörter für Systeme an der HAW Hamburg werden neu erzeugt. Diese wird das ITSC baldmöglichst verteilen. Wir empfehlen Ihnen darüber hinaus jedoch dringend, auch Ihre Passwörter auf anderen Systemen zu verändern. Denken Sie dabei nicht nur an das „zentrale“ Passwort für die zentralen IT-Dienste wie die HAW-Cloud oder MS Teams, sondern auch an alle anderen Systeme, insbesondere die dezentral betriebenen IT-Dienste mit einer separaten Passwortverwaltung.

Bitte ändern Sie unbedingt auch andere Passwörter auf Systemen, die nicht zur HAW Hamburg gehören, um die Gefahr eines möglichen Missbrauchs zu verringern oder ganz auszuschließen. Der Hintergrund: Wir können derzeit nicht ausschließen, dass die Angreifer auch sogenannte Keyboard-Logger installierten und damit in der Lage sind, an den Geräten eingegebene Passwörter aufzuzeichnen und später zu missbrauchen.

Wir beobachten kontinuierlich alle Entwicklungen und werden hierbei auch rund um die Uhr von den Ermittlungsbehörden und Computer-Notfallteams unterstützt. Wenn sich die Gefahrenbeurteilung ändert, werden wir diesen Abschnitt anpassen und Sie unverzüglich informieren.

**2. Installieren Sie sich ein gängiges Viren-Prüfprogramm**

Diese Alarme durch gängige Viren-Prüfprogramme weisen direkt auf die konkrete Angreifergruppe. Natürlich können Sie auch ganz andere Sicherheitsprobleme finden, die damit nichts zu tun haben – aber dennoch behoben werden müssen.

Wenn Sie einen Windows-Rechner benutzen, ist das Microsoft-Defender-Antivirus-Programm eine gute Wahl. Es ist auf den Computern der Hochschule standardmäßig installiert. Dieses Antivirus-Programm ist außerdem gut dokumentiert:

[Microsoft Defender Antivirus](https://learn.microsoft.com/de-de/microsoft-365/security/defender-endpoint/microsoft-defender-antivirus-windows?view=o365-worldwide)

MS Defender Antivirus erkennt eine „Zeppelin“ genannte Variante der eingesetzten Malware unter diesen Namen:

* [Ransom:Win32/VSocCrypt](https://www.microsoft.com/en-us/wdsi/threats/malware-encyclopedia-description?Name=Ransom:Win32/VSocCrypt.PA!MTB&threatId=-2147138765)
* [Trojan:PowerShell/VSocCrypt](https://www.microsoft.com/en-us/wdsi/threats/malware-encyclopedia-description?Name=Trojan:PowerShell/VSocCrypt.PA!MTB&threatId=-2147136227)
* [Ransom:Linux/ViceSociety](https://www.microsoft.com/en-us/wdsi/threats/malware-encyclopedia-description?Name=Ransom:Linux/ViceSociety.D!MTB&threatId=-2147136262)

Andere Angriffswerkzeuge, die in diesem Zusammenhang eingesetzt werden, werden erkannt als:

* [Behavior:Win32/Ransomware!Quantum.A](https://www.microsoft.com/en-us/wdsi/threats/malware-encyclopedia-description?Name=Behavior:Win32/Ransomware!Quantum.A&threatId=-2147147947)
* [Behavior:Win32/Quantum.AA](https://www.microsoft.com/en-us/wdsi/threats/malware-encyclopedia-description?Name=Behavior:Win32/Quantum.AA&threatId=-2147147852)
* [Ransom:Win32/Zeppelin](https://www.microsoft.com/en-us/wdsi/threats/malware-encyclopedia-description?Name=Ransom:Win32/Zeppelin&threatId=-2147188430)
* [Ransom:Win32/Blackcat](https://www.microsoft.com/en-us/wdsi/threats/malware-encyclopedia-description?Name=Ransom:Win32/Blackcat&threatId=-2147158032)

Außerdem gibt es Angriffswerkzeuge („SystemBC“ und „PortStarter“ genannt), die unter diesen Namen auftauchen:

* [Behavior:Win32/SystemBC](https://www.microsoft.com/en-us/wdsi/threats/malware-encyclopedia-description?Name=Behavior:Win32/SystemBC.A!nri&threatId=-2147149800)
* [Trojan:Win32/SystemBC](https://www.microsoft.com/en-us/wdsi/threats/malware-encyclopedia-description?Name=Trojan:Win32/SystemBC.SA!sms&threatId=-2147150468)
* [Backdoor:Win64/PortStarter](https://www.microsoft.com/en-us/wdsi/threats/malware-encyclopedia-description?Name=Backdoor:Win64/PortStarter&threatId=-2147137231)

Bevor die Angreifer daran gehen, Systeme zu verschlüsseln, benötigen sie einen direkten Zugriff. Da dieser nicht erreichbar ist, werden Benutzer:innen angegriffen, damit dann von innen weitere Angriffe gestartet werden können. Die hierbei eingesetzten Angriffswerkzeuge sind nicht unbedingt für eine bestimmte Angreifergruppe spezifisch, aber auf jeden Fall relevant:

* Behavior:Win32/OfficeInjectingProc.A
* Behavior:Win32/PsexecRemote.E
* Behavior:Win32/SuspRemoteCopy.B
* Behavior:Win32/PSCodeInjector.A
* Behavior:Win32/REnamedPowerShell.A

**Weiterführende Hinweise finden Sie hier:**

<https://www.microsoft.com/en-us/security/blog/2022/10/25/dev-0832-vice-society-opportunistic-ransomware-campaigns-impacting-us-education-sector/>

Die technische Informations- und Kommunikationsinfrastruktur der HAW Hamburg ist angegriffen worden. Dies wurde am 29. Dezember 2022 festgestellt. Aufgrund dieses Angriffs und um weiteren Schaden zu vermeiden, wurde die gesamte Kommunikationsinfrastruktur vorsorglich stillgelegt. Dies hat drastische Einschränkungen bei kritischen IT-Services zur Folge. Die Einschränkungen betreffen die gesamte Hochschule und alle ihre Bereiche. Da die Schadensfeststellung noch immer läuft, kann zurzeit keine belastbare Prognose abgegeben werden, wann welche IT-Services wieder verfügbar sein werden.

Diese Situation ist für alle – Studierende, Professor\*innen, wissenschaftliche Mitarbeiter\*innen und Beschäftigte – sehr belastend und mit großen Unsicherheiten verbunden. Insbesondere unseren Studierenden wollen wir auf dieser Seite laufend mitteilen, wann und wie sie wieder auf ihre Unterlagen für die Prüfungsvorbereitung zugreifen können, wie sich Fristen verschieben und wie Lehrveranstaltungen stattfinden können. Da außerdem die Bewerbungsphase für unsere Studieninteressierten läuft, ist es uns wichtig, auch hier schnell Lösungen zu finden.

Parallel zur Analyse und Auswertung des Vorfalls werden konkret die folgenden Dienste mit höchster Priorität wiederhergestellt:

* Zentrales Identitätsmanagementsystem
* MS Teams als zentrales Kommunikationsmedium
* Elektronische Schließsysteme

Die HAW Hamburg hat einen Krisenstab einberufen und einen IT-Dienstleister eingebunden, der bei der forensischen Aufklärung und der Wiederinbetriebnahme der verschiedenen Dienste unterstützt.

Auf diesen FAQ-Seiten berichten wir über aktuelle Entwicklungen und Fortschritte. Wir bemühen uns auf allen Ebenen um kurzfristige Lösungen, müssen aber aufgrund der hohen Komplexität und gebotenen Sorgfaltspflicht auch um Ihr Verständnis bitten, falls bestimmte Sachverhalte nicht sofort geklärt werden können. Wir bitten alle Angehörigen der Hochschule dringend darum, sich regelmäßig auf dieser FAQ-Seite zu informieren, da die Auskünfte laufend aktualisiert werden.

###  Ansprechpersonen und Kontaktdaten  ###

Bitte beachten Sie, dass derzeit **keine Kommunikation via E-Mail an @haw-hamburg.de** möglich ist und zudem die **Erreichbarkeit per Telefon eingeschränkt** ist (Stand 6. Januar). Sie finden untenstehend alternative Kontaktmöglichkeiten. Diese Liste wird fortlaufend ergänzt.

#### [Zentrale Studienberatung](javascript:void(0))  ####

Die Zentrale Studienberatung (ZSB) ist derzeit per E-Mail erreichbar unter: [haw\_zsb (at) gmx (dot) de](#)

Die telefonische Sprechzeit findet montags und dienstags von 9-10 Uhr und donnerstags von 16-17 Uhr statt (0151.72818022). Eine psychologische Sprechzeit für Studierende wird aktuell montags, dienstags und donnerstags von 9-12 Uhr angeboten (0151.72817883). Falls die Kollegin im Gespräch ist, ruft sie Sie zurück. Die persönliche Sprechzeit vor Ort findet weiterhin montags und dienstags von 11-13 Uhr und donnerstags von 14-16 Uhr im Studierendenzentrum in der Stiftstr. 69 statt.

#### [International Office](javascript:void(0))  ####

[HAW\_IO-incomings (at) gmx (dot) de](#)

[HAW\_IO-outgoings (at) gmx (dot) de](#)

#### [Fakultät Technik und Informatik (Kontakt für Studierende) (Stand: 06.01.)](javascript:void(0))  ####

**Department Maschinenbau und Produktion** (Prof. Dr. Enno Stöver/Prof. Dr. Friedrich Ohlendorf):

* Schwarzes Brett auf: <https://padlet.com/departmentmp/info>
* Mailkontakt über [department-mp (at) haw-hamburg (dot) eu](#)
* Sprechstunde: montags bis freitags von 11-12 Uhr, Berliner Tor 21, Raum 129

**Department Informations- und Elektrotechnik**

* Aktuelle Informationen des Departments: [https://www.haw-hamburg.de/ti-ie](/hochschule/technik-und-informatik/departments/informations-und-elektrotechnik/)
* Mailkontakt über [DL-IE (at) HAW-Hamburg (dot) eu](#)

**Department Informatik**

* [Aktuelle Informationen und Kontakte](https://www.haw-hamburg.de/detail/news/news/show/informationen-aus-dem-department-informatik-zum-angriff-auf-die-it/)

#### [Fakultät Life Sciences (Kontakt für Studierende und Beschäftigte) (Stand: 06.01.)](javascript:void(0))  ####

**Fakultätsservicebüro Life Sciences (LS):**
 Katharina Ress: +49 40 428 75 6407
 Inga Minet: +49 160 3714 219
 Anna Hartwig: +49 40 428 75 6408
 Peer Minet: +40 160 7838909

Die Fakultät hat einen Krisenstab um Dr. Helga Andree (Dekanin) eingerichtet, dem weiterhin Prof. Dr. Boris Tolg (Prodekan LS), Prof. Dr. Martin Holle (Prodekan LS), Sabine Witting (Verwaltungsleiterin), Prof. Dr. Petra Margaritoff und Prof. Dr. Volker Skwarek angehören. Der Krisenstab kann hier erreicht werden: [Krisenstab-ls.haw (at) web (dot) de](#)

#### [Fakultät Design, Medien und Information (Kontakt für Studierende und Beschäftigte) (Stand: 06.01.)](javascript:void(0))  ####

**Fakultätsservicebüro Design, Medien und Information (DMI):**
 Sabrina Breuer: +49 40 428 75 3623

 Die Fakultät hat einen Krisenstab DMI um Prof. Dorothea Wenzel (Dekanin) eingerichtet, dem weiterhin angehören Prof. Dr. Frederike Masemann (Prodekanin Lehre Department Information), Prof. Dr. Andreas Plaß (Prodekan Lehre Department Medientechnik), Prof. Dr. Markus Oberthür (Prodekan Lehre Department Design), Prof. Dr. Tessa Taefi (Prodekanin Internationales) Prof. Ulrike Schempp (Prodekanin QM und Berufungen), Prof. Dr. Hannah Früh (Prodekanin Forschung), Sabine Wittkuhn (Verwaltungsleiterin). Der Krisenstab kann hier erreicht werden: [wenzelro (at) web (dot) de](#); Telefon: +49 171499665.

#### [Fakultät Wirtschaft und Soziales (Kontakt für Studierende und Beschäftigte) (Stand: 06.01.)](javascript:void(0))  ####

**Dekanat**
 Dekanatsleitung: [dekanat-ws (at) posteo (dot) de](#)
 Studium und Lehre: [studiumlehre-ws (at) posteo (dot) de](#)
 Forschung: [forschung-ws (at) posteo (dot) de](#)
 Digitalisierung: [digitalisierung-ws@posteo.de](#)

**Verwaltung**
 Verwaltungsleitung: [verwaltungsleitung-ws (at) posteo (dot) de](#), +49 40 42875-7020

**Fakultätsservicebüros** **(FSB)**
 Semestermanager: [winkler-budwasch (at) posteo (dot) de](#), +49 176 42862929
 FSB Wirtschaft: fsb-wirtschaft@posteo.de (ab 9.1., ca. 14 Uhr erreichbar), +49 176 42862928
 FSB Soziale Arbeit und Pflege und Management: fsb-alex@posteo.de (ab 9.1., ca. ab 14 Uhr erreichbar) , +49 176 42862930; +49 176 42858969
 FSB Public Management: fsb-puma@posteo.de (ab 9.1., ca. ab 14 Uhr erreichbar), +49 176 42862931

Personal: personal-ws@posteo.de (ab 9.1., ca. ab 14 Uhr erreichbar)
 Öffentlichkeitsarbeit: [oeffentlichkeitsarbeit-ws (at) posteo (dot) de](#), +49 40 42875-7159
 Lehrbeauftrage: lehrbeauftragte-ws@posteo.de (ab 9.1., ca. ab 14 Uhr erreichbar)
 Tutorien: tutorien-ws@posteo.de (ab 9.1., ca. ab 14 Uhr erreichbar)
 Internationales: internationales-ws@posteo.de (ab 9.1., ca. ab 14 Uhr erreichbar)
 Finanzen: finanzen-ws@posteo.de (ab 9.1., ca. ab 14 Uhr erreichbar)
 Poststelle: poststelle-ws@posteo.de (ab 9.1., ca. ab 14 Uhr erreichbar)

**Departments**
 Departmentleitung Public Management (PuMa): [departmentleitung (at) puma-hamburg (dot) de](#)
 Departmentleitung Soziale Arbeit: [departmentleitung\_sozialearbeit\_hawhamburg (at) posteo (dot) de](#), weitere Informationen finden Sie [hier](https://www.haw-hamburg.de/detail/news/news/show/zum-angriff-auf-die-it-infrastruktur/).
 Departmentleitung Wirtschaft: Der Telegrammkanal "HAWDepartmentWirtschaft" des Departments kann abonniert werden, um regelmäßig aktuelle Informationen des Departments Wirtschaft zu erhalten
 Department Pflege und Management: Sie erreichen Angehörige des Departments auf dem Postweg. Die Adresse lautet:
 Department Pflege & Management
 \<Name\>
 Alexanderstr. 1
 20099 Hamburg

Gegebenenfalls sind die Beschäftigten auch unter den im Beschäftigtenportal hinterlegten Telefonnummern zu erreichen.

#### [Presse und Kommunikation (Kontakt für Website- und Social Media-Fragen sowie für Pressevertreter\*innen) (Stand: 06.01.)](javascript:void(0))  ####

Ansprechpartner\*innen der Stabsstelle Presse und Kommunikation sind auf der [Website der HAW Hamburg](/hochschule/hochschuleinheiten/presse-und-kommunikation/unser-team/) hinterlegt, die Team-Mitglieder sind zudem via Teams erreichbar.

### Fragen und Antworten zum Cyberangriff ###

#### [(Update 06.01.2023, 18 Uhr) Kann ich WLAN in der Hochschule nutzen?](javascript:void(0))  ####

Das WLAN ist wieder verfügbar, jedoch fehlt noch eine Anbindung an das Identity Management System. Dessen Daten sind zwar komplett vorhanden, aber die benötigten Systeme müssen aufgrund der Gefahrenlage neu aufgesetzt werden.

Damit ein Lehrbetrieb möglich ist, wird der geschützte Zugang ab 9. Januar trotzdem bereits möglich gemacht. Hierzu wird es entsprechende QR-Codes geben, die im einfachsten Falle mit dem Mobiltelefon gescannt werden können.

Genauere Informationen erfolgen in der kommenden Woche!

#### [(Update 06.01.2023, 14 Uhr) Ich benötige einen Nachweis der Immatrikulation. Was kann ich tun?](javascript:void(0))  ####

Zum jetzigen Zeitpunkt können wir Ihnen leider nur einen Nachweis ausstellen, dass wir keine Immatrikulationsbescheinigungen ausstellen können. Diese können Sie zu den Öffnungszeiten der Infothek im Studierendensekretariat (Stiftstr. 69, 1. Stock) abholen.

* Montag 10-13 Uhr
* Dienstag 10-13 und 14-15 Uhr
* Mittwoch 10-11 und 12-13 Uhr
* Donnerstag 10-13 Uhr
* Freitag 10-12 Uhr

#### [(Update 06.01.2023, 14 Uhr) Kann ich mich für das Sommersemester 2023 zurückmelden?](javascript:void(0))  ####

Ja. Bitte überweisen Sie den Semesterbeitrag (345,00 Euro) bis zum 15. Februar 2023. [Die Bankdaten und den Verwendungszweck finden Sie hier](/studium/studienorganisation/#c5555) im Abschnitt Rückmeldung.

Wir können Ihnen leider noch nicht sagen, wann genau die Bestätigung über die Rückmeldung erfolgen wird, da neben dem Zugriff auf myhaw auch das Erfassen der Zahlungen wieder möglich sein muss. Es wird an einer Lösung gearbeitet.

#### [(Update 06.01.2023, 13:30 Uhr) Ich benötige eine Exmatrikulationsbescheinigung. Was kann ich tun?](javascript:void(0))  ####

Bitte stellen Sie formlos einen Antrag auf Exmatrikulation. Der Antrag muss Ihren Vor- und Zunamen, Ihre Matrikelnummer und das Datum, zu dem Sie exmatrikuliert werden möchten, enthalten. Wir würden uns freuen, wenn Sie uns zudem noch den Grund der Exmatrikulation nennen würden. Den Antrag können Sie entweder per Post (Studierendensekretariat, Stiftstraße 69, 20099 Hamburg) an uns schicken, in den Briefkasten des Studierendensekretariats in der Stiftstr. 69 einwerfen oder zu den Öffnungszeiten der Infothek vorbeibringen. Sie erhalten dann eine Bestätigung, dass die Exmatrikulation beantragt wurde und dem Hinweis, dass eine Exmatrikulation zurzeit technisch nicht möglich ist. Wenn Sie den Exmatrikulationsantrag persönlich in der Öffnungszeit abgeben, können Sie die Bestätigung der Exmatrikulation direkt mitnehmen, ansonsten schicken wir diese per Post an Sie.

#### [(Update 06.01.2023, 16 Uhr) Kann ich meinen Studierendenausweis an einem der Validierungsautomaten validieren?](javascript:void(0))  ####

Nein, das ist derzeit nicht möglich. Im schlimmsten Fall wird ein noch gültiger Studierendenausweis sein Gültigkeitsdatum verlieren. Daher sollte der Validierungsautomat aktuell nicht genutzt werden.

#### [(Update 06.01.2023, 9:30 Uhr) Was bedeutet die Situation für den weiteren Lehr- und Prüfungsbetrieb an der HAW Hamburg?](javascript:void(0))  ####

Oberstes Ziel der HAW Hamburg ist es, dass die Studierenden unter den derzeitigen äußerst schwierigen Bedingungen ihr Studium wie geplant fortführen können. **Der Lehr- und Prüfungsbetrieb soll daher ohne Aufschub fortgesetzt werden. Alle mündlichen und schriftlichen Prüfungen sollen in der Regel wie geplant stattfinden**. Falls in Ausnahmefällen für die Prüfung relevante technische Anlagen in Folge des Cyberangriffs nicht funktionieren, wird eine gesonderte Information aus dem jeweiligen Department oder Fakultätsservicebüro heraus erfolgen.

Grundsätzlich ermutigt die HAW Hamburg alle Studierenden, an ihren schriftlichen oder mündlichen Prüfungsterminen teilzunehmen, um mögliche Aufschübe und Verdichtungen im Folgesemester zu vermeiden. **Die Lehrenden der HAW Hamburg wie auch die Hochschulverwaltung werden sie nach Kräften dabei unterstützen, ihre Prüfungen erfolgreich zu absolvieren.**

**Für die Fakultät TI** haben die Prüfungsausschussvorsitzenden einstimmig beschlossen, dass es keine zusätzliche Prüfungsphase geben soll, da diese das Sommersemester 2023 verkürzen würde. Stattdessen wurde eine Fehlversuchsregelung beschlossen. Das bedeutet: Für Studierende, die an der Prüfung teilnehmen und diese nicht bestehen, zählt dies nicht als Fehlversuch. Dasselbe gilt bei Nicht-Teilnahme nach Anmeldung. Diese Regelung gilt **nur für die Fakultät TI** und bezieht sich ausschließlich auf die mündlichen und schriftlichen Prüfungen des Wintersemesters 2022/2023.

[Zum Beschluss der TI-Prüfungsausschussvorsitzenden vom 05.01.2023](/fileadmin/PK/BeschlussDerPAVsTIvom5.1.2023.pdf)

 In den weiteren Fakultäten und Departments laufen derzeit Gespräche über mögliche kulante und gangbare Regelungen im Sinne der Studierenden in den weiteren Studiengängen. Die jeweiligen Prüfungsausschüsse in den Departments werden hierzu in den nächsten Tagen die erforderlichen Entscheidungen treffen. Diese werden auf der Website bekannt gegeben. Auch wird an dieser Stelle darauf hingewiesen, sofern die Bekanntgabe durch einen schriftlichen Aushang an der Fakultät erfolgt.

#### [(Update 05.01.2023, 19 Uhr) Wie melde ich mich zur Prüfung an oder ab?](javascript:void(0))  ####

Es ist derzeit nicht möglich, sich über den bekannten Weg an- oder abzumelden. Das Erscheinen zur Prüfung selbst wird daher als Anmeldung gewertet und die Prüfungsteilnahme vor Ort von den Prüfenden notiert. Eine gesonderte Abmeldung ist nicht nötig. Auf den Webseiten der Departments finden sich weitere Informationen zu den Terminen und Räumlichkeiten der jeweiligen Prüfungen.

#### [(Update 05.01.2023, 19 Uhr) Verschieben sich die Fristen für die Abgabe von Hausarbeiten und Abschlussarbeiten?](javascript:void(0))  ####

Die Fristen für die Abgabe von Hausarbeiten und Abschlussarbeiten (BA- und MA-Thesen) verschieben sich zunächst um drei Wochen, da dringend benötigte Lernmaterialien und Informationen zur anstehenden Prüfungsphase aktuell nicht zur Verfügung stehen (Hinweis: Für den hochschulübergreifenden Studiengang Wirtschaftsingenieurwesen gilt diese Regelung nicht, da das UHH-Netz von dem Cyberangriff nicht betroffen ist). Die Fristverlängerung betrifft nicht die Klausuren oder andere schriftliche sowie mündliche Prüfungsleistungen – mit Ausnahme der Hausarbeit. Weitere Details werden durch den Prüfungsausschuss entschieden und von dort aus mitgeteilt.

#### [(Update 05.01.2023, 19 Uhr) Wie sieht es mit Lehrveranstaltungen aus?](javascript:void(0))  ####

Die in Präsenz geplanten Lehrveranstaltungen starten ab dem 9. Januar. Aktuell wird daran gearbeitet, auch den Zugang zu den Räumen, die mit einem Kartenschließsystem funktionieren, zu gewährleisten. **Wir empfehlen allen Studierenden dringend, an den Präsenzveranstaltungen ab dem 9. Januar teilzunehmen, um mit ihren Lehrenden mögliche noch offene Fragen im direkten Austausch klären zu können.**

#### [(Update 06.01.2023) Wird die Anmeldefrist (6. Januar) für ein Auslandssemester in den USA, Vietnam und Hong Kong verlängert?](javascript:void(0))  ####

Ja, die Frist wird vorerst auf den 13. Januar 2023 verlängert. Das Portal Mobility Online ist weiterhin erreichbar. Bitte melden Sie sich mit einer privaten E-Mail Adresse an, um die Zugangsdaten zu erhalten.

Das [International Office](/international/ansprechpersonen/international-office/) hat Zugriff auf Mobility Online und kann Ihre vollständigen Bewerbungen herunterladen. Wenn Ihre Unterlagen nicht vollständig sind und Sie fehlende Unterlagen nicht hochladen können, weil Sie mit Ihrer E-Mail Adresse der HAW Hamburg angemeldet sind, bitten wir Sie, in die Sprechstunde Ihrer [Student Exchange Coordinatorin](/international/ansprechpersonen/student-exchange-coordinators/) zu gehen. Sie wird Ihr Profil im Mobility Online löschen, Sie können sich dann mit einer persönlichen E-Mail-Adresse erneut anmelden und Ihre Dokumente hochladen.
 Wenn Sie Ihre Leistungsnachweise (Transcript) noch nicht vorliegen haben, werden wir klären, wie Ihre Noten für die Bewerbung berücksichtigt werden können. Weitere Informationen folgen.

#### [(Update 05.01.2023) Finden die Termine zur System-Reakkreditierung statt?](javascript:void(0))  ####

Im System-Reakkreditierungsverfahren der HAW Hamburg finden die Begehungen vor Ort am 11./12. Januar (Probebegehung) und 18./19. Januar 2023 (Begehung vor Ort) wie geplant statt.

Bitte wenden Sie sich bei Fragen zu diesem Thema und noch ausstehenden Zusagen telefonisch an Dorian Seeliger (-9248) oder Christine Wollmann (-9021).

Alle Bachelor- und Masterstudiengänge müssen in Deutschland akkreditiert, d.h. von unabhängigen Agenturen unter Einbeziehung von Gutachtergruppen geprüft und für gut befunden werden. Das jetzt anstehende Verfahren der System-Reakkreditierung überprüft, ob das an der HAW Hamburg bestehende Qualitätsmanagementsystem den gesetzlichen Anforderungen entspricht.

#### [(Update 06.01.2023) Sind die Bibliotheken geöffnet?](javascript:void(0))  ####

Die Fachbibliotheken des HIBS sind [zu den auf den Webseiten angegebenen Zeiten](/hochschule/hochschuleinheiten/bibliotheken-hibs/) geöffnet. Sie können dort arbeiten und die Printmedien vor Ort nutzen. Entleihungen sind derzeit leider nicht möglich. Zudem können Sie Medien zwar zurückbringen, die korrekte Rückbuchung ist aber nicht möglich, Gebühren entstehen Ihnen dadurch nicht.

Der [HAW-Katalog](https://katalog.haw-hamburg.de) funktioniert weiterhin. Der Zugriff auf Open Access E-Medien ist möglich, auflizenzierte Medien erst, sobald das HAW Hamburg WLAN wieder freigeschaltet wird.

 Sie können mit Studierendenausweisen bzw. Mitarbeiter\*innen-Hochschulausweisen der HAW Hamburg kostenlosen Zugang zu allen Hamburger Hochschulbibliotheken (z.B. SUB, TUHH, etc.) bekommen, um dort Printmedien zu entleihen. Die Recherche ist im [Hamburg Katalog](https://beluga.sub.uni-hamburg.de/vufind/) möglich.

#### [Was ist bei dem Cyberangriff passiert?](javascript:void(0))  ####

Nach derzeitigem Kenntnisstand haben sich die Angreifer ausgehend von dezentralen IT-Systemen über das Netzwerk manuell bis in die zentralen IT- und Sicherheitskomponenten der HAW Hamburg vorgearbeitet. Über diesen Angriffspfad haben sie auch administrative Rechte auf den zentralen Storage-Systemen erlangt und damit die zentrale Datenhaltung kompromittiert. Mit den erlangten administrativen Rechten wurde abschließend die Verschlüsselung diverser virtualisierter Plattformen und das Löschen gespeicherter Backups gestartet.

Wir müssen davon ausgehen, dass unter den abgeflossenen Informationen auch personenbeziehbare Daten sind. Die HAW Hamburg hat beim Landeskriminalamt, Abteilung Cyber-Kriminalität, Anzeige erstattet. Außerdem wurde der Vorfall dem Hamburger Beauftragten für Datenschutz und Informationsfreiheit (HmbBfDI) gemäß Art. 33 DSGVO sowie dem CERTnord gemeldet und [die Betroffenen im Sinne des Gesetzes](/fileadmin/PK/PDF/Infos_Art._34_DS-GVO_final.pdf) informiert.

#### [Wann werden die IT-Services wieder verfügbar sein?](javascript:void(0))  ####

Nach den aktuell zur Verfügung stehenden Informationen werden in dieser Woche bis zum 08.01.2023 noch keine digitalen Zugangsmöglichkeiten zum EMIL-Raum, zu Outlook, myHAW oder MS Teams mit Neuanmeldung möglich sein. Wer noch Zugriff auf Teams-Räume hat, sollte sich bitte nicht von dieser Anwendung abmelden, denn eine Neuanmeldung ist nicht möglich.

Über diese Seiten werden wir nach der abgeschlossenen Schadensfeststellung die gesicherte Verfügbarkeit einzelner IT-Services kommunizieren. Wir werden hier aufzeigen, an welchen IT-Services mit welcher Priorität gearbeitet wird und wann mit deren Wiederherstellung zu rechnen ist. Für die Nutzung der wiederhergestellten IT-Services werden die bisherigen E-Mail-Adressen und HAW-Kennungen weiterhin verwendet werden. Allerdings wird das Setzen eines neuen Passworts erforderlich sein. Über die Vorgehensweise und die von Ihnen benötigte Unterstützung werden wir Sie an dieser Stelle informieren, sobald wir das zentrale Identitätsmanagementsystem wieder in Betrieb genommen haben.

#### [Sollten Beschäftigte ihren Rechner / Laptop einschalten und benutzen?](javascript:void(0))  ####

Wir gehen davon aus, dass alle durch die HAW Hamburg selbst administrierten Rechner / Laptops vor einer weiteren Nutzung auf Anzeichen einer Kompromittierung getestet werden müssen. Wir werden anhand der Erkenntnisse an einer Handreichung arbeiten, die es ermöglichen soll, die Gefährdung ihres Rechners / Laptops einzuschätzen.

#### [Wie ist die Arbeitssituation in der Hochschule?](javascript:void(0))  ####

Aktuell können Verwaltungsmitarbeiter\*innen vor Ort nur die Büroarbeiten erledigen, für die sie kein Internet benötigen. Die Lehrenden werden gebeten, ab dem 9.1.2023 soweit möglich Präsenzlehre oder Sprechstunden anzubieten.

#### [Wann und wie sind Bewerbungen zum Sommersemester 2023 wieder möglich?](javascript:void(0))  ####

Die aktuelle Bewerbungsphase für das Sommersemester 2023 geht offiziell noch bis zum 15. Januar. Da allerdings auch die onlinegestützten Prozesse zur Bewerbung an der HAW Hamburg betroffen sind, arbeiten wir unter Hochdruck an Alternativlösungen. Aktuell prüfen wir, ob wir Fristverlängerungen für Bewerbungen möglich machen können.

####  Hinweise  ####

[Information nach Art. 34 DSGVO zum Sicherheitsvorfall an der HAW Hamburg](/fileadmin/PK/PDF/Infos_Art._34_DS-GVO_final.pdf)

[Web-Team](#) / Letzte Änderung 09.01.2023
