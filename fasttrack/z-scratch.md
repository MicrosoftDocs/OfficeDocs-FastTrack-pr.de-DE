---
title: Sicherheit und Compliance
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 7/01/2020
audience: ITPro
ms.topic: overview
ms.service: O365-seccomp
localization_priority: None
ms.collection: FastTrack
description: FastTrack-Anleitungsdetails für Microsoft-Dienste.
ms.openlocfilehash: 000a81c51729deba8d3f5c4d88a0baa918dcd048
ms.sourcegitcommit: 5d40d060bbcf4b266a0d6f3e4bbc151f94288b00
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/25/2021
ms.locfileid: "51996238"
---
# <a name="security-and-compliance"></a>Sicherheit und Compliance

<table>
<thead>
<tr class="header">
<th><strong>Dienst</strong></th>
<th><strong>FastTrack-Anleitungsdetails</strong></th>
<th><strong>Anforderungen an die Quellumgebung</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Microsoft 365 Defender</strong></td>

<td> <p> Microsoft 365 Defender ist eine einheitliche Vor- und Nachverletzungssuite für die Unternehmensverteidigung, die Erkennung, Verhinderung, Untersuchung und Reaktion auf Endpunkte, Identitäten, E-Mails und Apps nativ koordiniert, um integrierten Schutz vor komplexen Angriffen zu bieten. Wir bieten Remoteanleitungen für: </p> 
<ul>
<li>  Bereitstellen einer Übersicht über das Microsoft 365 Security Center.  </li>
<li>  Überprüfen produktübergreifender Vorfälle, einschließlich der Fokussierung auf das Entscheidende, indem sichergestellt wird, dass der gesamte Angriffsbereich, die ressourcenbelastenden Ressourcen und die automatisierten Abhilfemaßnahmen, die zusammengeteilt sind, sichergestellt werden.  </li>
<li>  Demonstrieren, wie Microsoft 365 Defender die Untersuchung von Ressourcen, Benutzern, Geräten und Postfächern orchestrieren kann, die möglicherweise durch automatisierte Selbstheilung gefährdet wurden. </li>
<li>  Erläutern und Bereitstellen von Beispielen dafür, wie Kunden proaktiv nach Angriffsversuchen und Verletzungsaktivitäten abwehren können, die Sich auf Ihre E-Mails, Daten, Geräte und Konten in mehreren Datensätzen ausdingen.   </li>
<li> Zeigen Sie Kunden, wie sie ihre Sicherheitslage ganzheitlich mithilfe von Microsoft Secure Score überprüfen und verbessern können.</li>
</ul>
<p><strong>Die folgenden Bereiche sind nicht mehr</strong></p>
<ul>
<li> Projektmanagement der Problemlösungsaktivitäten des Kunden. </li>
<li> Laufende Verwaltung, Bedrohungsreaktion und Behebung. </li>
<li> Bereitstellungsanleitungen oder Bildungseinrichtungen zu:
<ul>
<li> Wie Die verschiedenen Warnungstypen und überwachten Aktivitäten behoben oder interpretiert werden. </li>
<li> Untersuchen eines Benutzers, Computers, lateralen Bewegungspfads oder einer Entität. </li>
<li> Benutzerdefinierte Bedrohungssuche.  </li>
</ul>
</li>
<li> Sicherheitsinformationen und Ereignisverwaltung (SIEM) oder API-Integration.</li>
</td>
</tr>
<tr class="even">
<td><strong>Microsoft Cloud App Security</strong></td>
<td>  Microsoft Cloud App Security ist ein Cloud Access Security Broker (CASB), der umfassende Sichtbarkeit, Kontrolle über Datenreise und ausgefeilte Analysen bietet, um Cyberbedrohungen in allen Ihren Microsoft- und Drittanbieter-Clouddiensten zu identifizieren und zu bekämpfen. Wir bieten Remoteanleitungen für:
<ul>
<li>  Konfigurieren des Portals, einschließlich:  </li>
<ul>
<li> Importieren von Benutzergruppen.</li>
<li> Verwalten des Administratorzugriffs und der Einstellungen.  </li>
<li> Legen Sie die Bereitstellung so fest, dass bestimmte Benutzergruppen ausgewählt werden, die überwacht oder von der Überwachung ausgeschlossen werden.</li>
<li> Festlegen von IP-Bereichen und -Tags.</li>
<li> Personalisierung der Endbenutzererfahrung mit Ihrem Logo und benutzerdefiniertem Messaging.</li>
</ul>
<li> Einrichten der Clouderkennung für die Bereitstellung von Schatten-IT mithilfe von:</li>
<ul>
<li> Microsoft Defender für Endpunkte.</li>
<li> Zscaler.</li>
<li> iboss.</li>
</ul>
<li> Verbinden <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-gove">von empfohlenen Apps</a> mithilfe von App-Connectors.</li>
<li> Einrichten der App-Steuerung für bedingten Zugriff in den Portalen bedingter Zugriff und Cloud App-Sicherheit, um Sitzungssteuerelemente in Echtzeit anzuwenden.</li>
<li> Bereitstellen der Cloud App Security- und Cloud Discovery-Dashboards.</li>
<li> Anpassen der App-Risikoergebnisse basierend auf den Prioritäten Ihrer Organisation.</li>
<li> Erstellen von App-Tags und -Kategorien.</li>
<li> Sanktions- und Nichtfunktionierungs-Apps.</li>
<li> Verwenden der Aktivitäts- und Dateiprotokolle.</li>
<li> Verwalten von OAuth-Apps.</li>
<li> Grundlegendes zur Korrelation zwischen Vorfällen im Microsoft 365 Defender-Portal.</li>
<li> Bereitstellung von Konfigurationsunterstützung bei den <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> am meisten verwendeten Fällen für CASBs (einschließlich der Erstellung oder Aktualisierung von bis zu sechs (6) Richtlinien) mit Ausnahme von: </li>
<ul>
<li> Überwachen der Konfiguration Ihres Internet as a Service (IaaS)-Umgebungen (#18).</li>
<li> Überwachen von Benutzeraktivitäten zum Schutz vor Bedrohungen in Ihren IaaS-Umgebungen (#19).</li>
</ul>
</ul>
<p><strong>Die folgenden Bereiche sind nicht mehr</strong></p>
<ul>
<li> Projektmanagement der Problemlösungsaktivitäten des Kunden.</li>
<li> Laufende Verwaltung, Bedrohungsreaktion und Behebung. </li>
<li> Einrichten der Infrastruktur, Installation oder Bereitstellung von automatischen Protokolluploads für kontinuierliche Berichte mithilfe von Docker oder einem Protokollsammler. Weitere <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Informationen finden Sie unter Top 20 use cases for CASBs.</a></li>
<li> Erstellen eines Cloud Discovery-Snapshotberichts.</li>
<li> Blockieren der App-Verwendung mithilfe von Blockskripts.</li>
<li> Verbinden benutzerdefinierter Apps.</li>
<li> Integration in Drittanbieter von Identitätsanbietern (IsPs) und Verhinderung von Datenverlust (Data Loss Prevention, DLP).</li>
<li> Schulungen oder Anleitungen für die erweiterte Suche.</li>
<li> Automatisierte Untersuchung und Korrektur, einschließlich Microsoft Power Automate-Playbooks.</li>
<li> Sicherheitsinformationen und Ereignisverwaltung (SIEM) oder API-Integration (einschließlich Azure Sentinel).</li>
<li> Bereitstellen von Cloud App Security als Konzeptbeweis.</li>
</ul></td>
</tr>



<tr class="odd">
<td><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></td>
<td>  Microsoft Defender Advanced Threat Protection (ATP) ist eine Plattform, mit deren Hilfe Unternehmensnetzwerke erweiterte Bedrohungen verhindern, erkennen, untersuchen und darauf reagieren können.  
  Wir bieten Remoteanleitungen für:
<ul>
<li>  Bereitstellen der Technologien zum Sichern Ihrer Endpunkte.  </li>
<li>  Konfigurieren von Endpunktschutz- und Geräteeinschränkungsprofilen.  </li>
<li>  Bewerten der Betriebssystemversion und Geräteverwaltung (einschließlich Intune, Microsoft Endpoint Configuration Manager, Gruppenrichtlinienobjekte (GPOs) und Konfigurationen von Drittanbietern sowie des Status Ihrer Windows Defender-AV-Dienste oder anderer Endpunktsicherheitssoftware.  </li>
<li>  Bewerten des Status Ihrer Windows AV-Dienste oder anderer Endpunktsicherheitssoftware.  </li>
<li>  Bewerten von Proxys und Firewalls, die den Netzwerkdatenverkehr einschränken.  </li>
<li>  Aktivieren des Microsoft Defender ATP-Diensts durch Erläuterung der Bereitstellung eines ATP-Agentprofils mithilfe eines onboard-Endpunkts.  </li>
<li>  Bereitstellungsanleitungen, Konfigurationsunterstützung und Bildungseinrichtungen zu:
<ul>
<li>  
  Bedrohungs- und Sicherheitsrisikoverwaltung.  
  </li>
<li>  
  Verringerung der Angriffsfläche.  
  </li>
<li>  
  Schutz der nächsten Generation.  
  </li>
<li>  
  Erkennung und Reaktion am Endpunkt.  
  </li>
<li>  
  Automatische Untersuchung und Reaktion.  
  </li>
<li>  
  Sicherheitsbewertung.  
  </li>
</ul></li>
<li>  Überprüfen von Simulationen und Lernprogrammen (z. B. Übungsszenarien, gefälschte Schadsoftware und automatisierte Untersuchungen).  </li>
<li>  Übersicht über Berichterstellungs- und Bedrohungsanalysefeatures.  </li>
<li>  Integration von Office 365 ATP in Microsoft Defender ATP.  </li>
<li>  Ausführen von exemplarischen Vorgehensweisen im Microsoft Defender Security Center-Portal.  </li>
<li>  Die folgenden Betriebssysteme:
<ul>
<li>  
  Windows 10.  
  </li>
<li>  
  Windows Server 2016.  
  </li>
<li>  
  Windows Server 2019.  
  </li>
<li>  
  Windows Server 2019 Core Edition.  
  </li>
<li>  
  Windows Server Semi-Annual Channel (SAC) Version 1803.  
  </li>
<li>  
  macOS-Versionen 10.13, 10.14 und 10.15.  
  </li>
</ul>
</li>
</ul>
<strong>Hinweis:</strong> Alle Windows Server-Versionen müssen über die neueste Version von System Center Configuration Manager 2012 (Versionen 1012 R2, 1511 oder 1602) oder Microsoft Endpoint Configuration Manager (Version 2002 oder höher) verwaltet werden. 

</li>
</ul>

<strong>Die folgenden Bereiche sind nicht mehr </strong>  
<ul>
<li>  Projektmanagement der Problemlösungsaktivitäten des Kunden.  </li>
<li>  Unterstützung vor Ort.  </li>
<li>  Fortlaufende Verwaltung und Bedrohungsreaktion.  </li>
<li>  Onboarding oder Konfiguration für die folgenden Microsoft Defender ATP-Agenten:
<ul>
<li>  
  Windows Server 2008.  
  </li>
<li>  
  Windows Server 2012.  
  </li>
<li>  
  Linux.  
  </li>
<li>  
  Mobile Geräte (Android und iOS).  
  </li>
</ul></li>
<li>  Server-Onboarding und -konfiguration:
<ul>
<li>  
  Konfigurieren eines Proxyservers für die Offlinekommunikation.  
  </li>
<li>  
  Konfigurieren von Configuration Manager-Bereitstellungspaketen für Configuration Manager-Instanzen und -Versionen auf ebener ebener Ebene.  
  </li>
<li>  
  Onboarding von Servern im Azure Security Center.  
  </li>
<li>  
  Server, die nicht vom Configuration Manager verwaltet werden.  
  </li>
</ul></li>
<li>  macOS-Onboarding und -Konfiguration:
<ul>
<li>  
  Manuelle Intune-basierte Bereitstellung.  
  </li>
<li>  
  JAMF-basierte Bereitstellung.
  </li>
<li>  
  Andere produktbasierte Bereitstellung für die Mobile Device Management (MDM).  
  </li>
<li>  
  Manuelle Bereitstellung.  
  </li>
</ul></li>
<li>  Konfiguration der folgenden Funktionen zur Verringerung der Angriffsfläche:
<ul>
<li>  
  Hardwarebasierte Isolation.  
  </li>
<li>  
  App-Steuerelement.  
  </li>
<li>  
  Exploit-Schutz.  
  </li>
<li>  
  Netzwerkfirewall.  
  </li>
</ul></li>
<li>  Registrierung oder Konfiguration von Microsoft-Bedrohungsexperten.  </li>
<li>  Konfiguration oder Schulung zur Überprüfung von API- oder Sicherheitsinformationen und Ereignisverwaltungsverbindungen (EVENT Management, SIEM).  </li>
<li>  Registrierung oder Konfiguration von Microsoft Threat Protection (MTP).  </li>
<li>  Schulungen oder Anleitungen für die erweiterte Suche.  </li>
<li>  Schulungen oder Anleitungen zur Verwendung oder Erstellung von Kusto-Abfragen.</li>
</li>
</ul>
Wenden Sie sich <a href="https://go.microsoft.com/fwlink/?linkid=2080150">an einen Microsoft-Partner,</a> um Unterstützung für diese Dienste zu erhalten.  
</ul></td>
<td></td>

<tr class="odd">
<td><strong>Microsoft Defender for Identity </strong></td>
<td>  Microsoft Defender for Identity ist eine cloudbasierte Sicherheitslösung, die Ihre lokalen Active Directory-Signale nutzt, um komplexe Bedrohungen, kompromittierte Identitäten und bösartige, gegen Ihre Organisation gerichtete Insideraktionen zu identifizieren, zu erkennen und zu untersuchen. Wir bieten Remoteanleitungen für:
<ul>
<li>   Erstellen Ihrer Instanz von Defender for Identity. </li>
<li>   Verbinden von Defender for Identity mit Active Directory. </li>
<li>   Bewerten der Bereitschaft Ihrer Umgebung zur Bereitstellung des Defender for Identity-Sensors auf Ihren Domänencontrollern, einschließlich:</li>   
<ul> 
<li>  Ausführen des Größenanpassungstools für die Ressourcenkapazitätsplanung. </li>
<li>  Ausführen des Überwachungstools, um die Kompatibilität Ihrer Domänencontroller mit dem Sensor zu bewerten. </li>
</ul>
<li>  Bereitstellen des Sensors zum Erfassen und Analysieren von Netzwerkdatenverkehr und Windows-Ereignissen direkt von Ihren Domänencontrollern, einschließlich: </li>
<ul> 
<li>  Herunterladen des Sensorpakets. </li>
<li>  Konfigurieren des Sensors. </li>
<li>  Automatisches Installieren des Sensors auf dem Domänencontroller. </li>
<li>  Bereitstellen des Sensors in Ihrer Umgebung mit mehreren Gesamtstrukturen. </li>
</ul>
<li>  Integrieren von Defender for Identity in Microsoft Cloud App Security (Cloud App Security-Lizenzierung ist nicht erforderlich). </li>
<li>  Bereitstellen von Bereitstellungsanleitungen, Konfigurationsunterstützung und Bildungseinrichtungen zu: </li>
<ul>
<li> Optimieren der Umgebung, um "Rauschen" zu reduzieren.  </li>
<li>  Grundlegendes zum Bericht zur Bewertung der Identitätssicherheitslage. </li>
<li>  Grundlegendes zum Bewertungsergebnis für die Priorität der Benutzeruntersuchung und zum Bewertungsbericht der Benutzeruntersuchung. </li>
<li> Grundlegendes zum bericht des inaktiven Benutzers.  </li>
<li> Bereitstellen von Korrekturoptionen für ein gefährdetes Konto.  </li>
</ul>
<li>  Vereinfachen der Migration von Advanced Threat Analytics (ATA) zu Defender for Identity. </li>
</ul>
<p><strong>Die folgenden Bereiche sind nicht mehr</strong></p>
<ul>

<li> Projektmanagement der Problemlösungsaktivitäten des Kunden. </li>
<li> Laufende Verwaltung, Bedrohungsreaktion und Behebung.  </li>
<li> Bereitstellen des Defender for Identity-Sensors, einschließlich: </li>
<ul>
<li> Manuelle Kapazitätsplanung. </li>
<li> Bereitstellen des Sensors in eigenständiger Kapazität. </li>
<li> Bereitstellen des Sensors mithilfe eines Netzwerkschnittstellenkartenadapters (Network Interface Card, NIC). </li>
<li> Bereitstellen des Sensors über ein Drittanbietertool. </li>
<li> Herstellen einer Verbindung mit dem Defender for Identity-Clouddienst über eine Webproxyverbindung. </li>
</ul>
<li> Erstellung und Verwaltung von "honeytokens". </li>
<li> Bereitstellungsanleitungen oder Bildungseinrichtungen zu: </li>
<ul>
<li> Behebung oder Interpretation verschiedener Warnungstypen und überwachter Aktivitäten.  </li>
<li> Untersuchen eines Benutzers, Computers, lateralen Bewegungspfads oder einer Entität. </li>
<li> Bedrohung oder erweiterte Suche. </li>
<li> Reaktion auf Vorfälle. </li>
</ul>
<li> Bereitstellen eines Lernprogramms für Sicherheitswarnungen für Defender for Identity. </li>
<li> Bereitstellen einer Benachrichtigung, wenn Defender for Identity verdächtige Aktivitäten erkennt, indem Sicherheitswarnungen über einen benannten Sensor an Ihren syslog-Server gesendet werden.  </li>
<li> Konfigurieren von Defender for Identity zum Ausführen von Abfragen mithilfe des Security Account Manager Remote (SAMR)-Protokolls, um lokale Administratoren auf bestimmten Computern zu identifizieren. </li>
<li> Konfigurieren von VPN-Lösungen zum Hinzufügen von Informationen aus der VPN-Verbindung zur Profilseite eines Benutzers.  </li>
<li> Sicherheitsinformationen und Ereignisverwaltung (SIEM) oder API-Integration (einschließlich Azure Sentinel). </li>
<li> Bereitstellen von Defender for Identity-Sensoren als Konzeptbeweis.</li>
</ul></td>
<td><ul>
<li>  Active Directory bereitgestellt.  </li>
<li>  Die Domänencontroller, auf die Sie Defender for Identity-Sensoren installieren möchten, verfügen über eine Internetverbindung zum Defender for Identity-Clouddienst.  </li>
<ul>
<li> Die Firewall und der Proxy müssen für die Kommunikation mit dem Defender for Identity-Clouddienst geöffnet sein (*.atp.azure.com Port 443 muss geöffnet sein).</li>
</ul>
<li> Domänencontroller, die auf einem der folgenden Controller ausgeführt werden:</li>
<ul>
<li> Windows Server 2008 R2 SP1.</li>
<li> Windows Server 2012.</li>
<li> Windows Server 2012 R2.</li>
<li> Windows Server 2016.</li>
<li> Windows Server 2019 mit KB4487044 (Betriebssystem build 17763.316).</li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><strong>Microsoft Information Governance</strong></td>
<td>  Wir bieten Remoteanleitungen für:
<ul>
<li>  Aufbewahrungsbezeichnungen und Richtlinien.  </li>
<li>  Verwaltung von Unterlagen.  </li>
<li>  Löschungsrichtlinien.  </li>
<li>  Kommunikationscompliance.  </li>
<li>  Insider-Risikomanagement.  </li>
<li>  Advanced eDiscovery.  </li>
</ul>

  <strong>Die folgenden Bereiche sind nicht mehr </strong>  
<ul>
<li> Entwicklung eines Datensatzverwaltungsdateiplans.</li>
<li> Datenconnectors.</li>
<li> Informationsbarrieren.</li>
<li> Privilegierte Zugriffsverwaltung.</li>
<li> Entwicklung der Informationsarchitektur in SharePoint.</li>
<li> Benutzerdefinierte Skripts und Codierung.</li>
</td>
<td>Abgesehen vom <strong>Abschnitt Core-Onboarding</strong> im <a href="products-and-capabilities.md#general">Allgemeinen</a>gibt es keine Mindestsystemanforderungen.</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Information Protection</strong></td>
<td>  Wir bieten Remoteanleitungen für:
<ul>
<li>  Datenklassifikation.  </li>
<li>  Typen vertraulicher Informationen.  </li>
<li>  Erstellen von Vertraulichkeitsbezeichnungen.  </li>
<li>  Anwenden von Vertraulichkeitsbezeichnungen.  </li>
<li>  Einheitliche Bezeichnungen.  </li>
<li>  Trainierbare Klassifizierungsmerkmale.  </li>
<li>  Erkennen Ihrer Daten über den Inhalts- und Aktivitäten-Explorer.  </li>
<li>  Veröffentlichen von Bezeichnungen mithilfe von Richtlinien (manuell und automatisch).  </li>
<li>  Erstellen von Richtlinien zum Schutz vor Datenverlust (DLP) für Microsoft Teams-Chats und -Kanäle.  </li>
<li>  Erstellen von Endpunkt-DLP-Richtlinien für Windows 10-Geräte.  </li>
</ul>

<strong>Die folgenden Bereiche sind nicht mehr </strong>  
<ul>
<li>Kundenschlüssel.</li>
<li>Entwicklung von benutzerdefinierten regulären Ausdrücken (RegEx) für Typen vertraulicher Informationen.</li>
<li>Erstellen oder Ändern von Schlüsselwortwörterbüchern.</li>
<li>Benutzerdefinierte Skripts und Codierung.</li>
</ul>
<strong>Hinweis:</strong> Weitere Informationen finden Sie unter <strong>Azure Information Protection</strong> in Enterprise Mobility + <a href="products-and-capabilities.md#enterprise-mobility--security">Security</a>.
<ul>

</td>
<td>Abgesehen vom <strong>Abschnitt Core-Onboarding</strong> im <a href="products-and-capabilities.md#general">Allgemeinen</a>gibt es keine Mindestsystemanforderungen.</td>
</tr>

<tr class="odd">
<td><strong>Office 365 Advanced Threat Protection (ATP)</strong></td>
<td>  Wir bieten Remoteanleitungen für:
<ul>
<li>  Aktivieren von sicheren Links, sicheren Anlagen und Antiphishing.  </li>
<li>  Konfigurieren von Automatisierung, Untersuchung und Reaktion.  </li>
<li>  Verwenden des Angriffssimulators.  </li>
<li>  Berichterstellung und Bedrohungsanalyse.  </li>
</ul></td>
<td>Abgesehen vom <strong>Abschnitt Core-Onboarding</strong> im <a href="products-and-capabilities.md#general">Allgemeinen</a>gibt es keine Mindestsystemanforderungen.</td>
</tr>


<tr class="odd">
<td><strong>Ermittlung & Antwort</strong></td>
<td>  

<strong>Advanced eDiscovery</strong>
  
<ul>
<li>  Aktivieren von sicheren Links, sicheren Anlagen und Antiphishing.  </li>
<li>  Konfigurieren von Automatisierung, Untersuchung und Reaktion.  </li>
<li>  Verwenden des Angriffssimulators.  </li>
<li>  Berichterstellung und Bedrohungsanalyse.  </li>
</ul>

<strong>Erweiterte Überwachung</strong> (nur in E5 unterstützt)

Wir bieten Remoteanleitungen für: 
<ul>
<li> Aktivieren der erweiterten Überwachung.</li>
<li> Ausführen einer Benutzeroberfläche für das Such-Überwachungsprotokoll und grundlegende PowerShell-Überwachungsbefehle.</li>
</ul>

<strong> Compliance-Manager</strong>

Wir bieten Remoteanleitungen für:  

<ul> <li>Überprüfen von Rollentypen.  </li>
<li> Hinzufügen und Konfigurieren von Bewertungen.</li>
<li> Bewerten der Compliance durch Implementieren von Verbesserungsmaßnahmen und Bestimmen, wie sich dies auf Ihre Compliance-Bewertung aus wirkt.</li>
<li> Überprüfen der integrierten Steuerelementzuordnung und Bewertung von Steuerelementen.</li>
<li> Generieren eines Berichts innerhalb einer Bewertung.</li>
</ul>

<strong>Die folgenden Bereiche sind nicht mehr </strong> 
<ul>
<li> Benutzerdefinierte Skripts oder Codierungen.</li>
<li> eDiscovery-API. </li>
<li> Datenconnectors. </li>
<li> Compliancegrenzen und Sicherheitsfilter.</li>
<li> Datenuntersuchungen.</li>
<li> Anfragen von Datensubjekten.</li>
<li> Entwurfs-, Architekten- und Drittanbieterdokumentüberprüfung.</li>
<li> Einhaltung der branchen- und regionalen Vorschriften und Anforderungen.</li>
<li> Praktische Implementierung empfohlener Verbesserungsmaßnahmen für Bewertungen im Compliance Manager.</li>
</ul>
</td>
<td>Abgesehen vom <strong>Abschnitt Core-Onboarding</strong> im <a href="products-and-capabilities.md#general">Allgemeinen</a>gibt es keine Mindestsystemanforderungen.</td>
</tr>
<tr class="odd">
<td><strong>Insider Threat Management</strong></td>

<td>  Wir bieten Remoteanleitungen für:
<ul>
<li> Erstellen von Richtlinien und Überprüfen von Einstellungen.</li>
<li> Zugreifen auf Berichte und Warnungen.</li>
<li> Erstellen von Fällen.</li>
<li> Erstellen von Benachrichtigungsvorlagen.</li>
<li> Anleitungen zum Erstellen des Personalconnector.</li>
</ul>

<strong> Kommunikationskonformität </strong> 

Wir bieten Remoteanleitungen für: 
<ul>
<li> Erstellen von Richtlinien und Überprüfen von Einstellungen.</li>
<li> Zugreifen auf Berichte und Warnungen.</li>
<li> Erstellen von Benachrichtigungsvorlagen.</li>
</ul>

<strong> Compliance-Manager</strong>

Wir bieten Remoteanleitungen für:  

<ul> <li>Überprüfen von Rollentypen.  </li>
<li> Hinzufügen und Konfigurieren von Bewertungen.</li>
<li> Bewerten der Compliance durch Implementieren von Verbesserungsmaßnahmen und Bestimmen, wie sich dies auf Ihre Compliance-Bewertung aus wirkt.</li>
<li> Überprüfen der integrierten Steuerelementzuordnung und Bewertung von Steuerelementen.</li>
<li> Generieren eines Berichts innerhalb einer Bewertung.</li>
</ul>

<strong>Die folgenden Bereiche sind nicht mehr </strong> 
<ul>
<li> Erstellen und Verwalten von Power Automate-Flüssen.</li>
<li> Datenconnectors (über den HR-Connector hinaus). </li>
<li> Konfigurationen für benutzerdefinierte reguläre Ausdrücke (RegEx).</li>
<li> Entwurfs-, Architekten- und Drittanbieterdokumentüberprüfung.</li>
<li> Informationsbarrieren.</li>
<li> Privilegierte Zugriffsverwaltung.</li>
<li> Einhaltung der branchen- und regionalen Vorschriften und Anforderungen.</li>
<li> Praktische Implementierung empfohlener Verbesserungsmaßnahmen für Bewertungen im Compliance Manager.</li>
</ul></td>
<td>Abgesehen vom <strong>Abschnitt Core-Onboarding</strong> im <a href="products-and-capabilities.md#general">Allgemeinen</a>gibt es keine Mindestsystemanforderungen.</td>
</tr>


</tbody>
</table>












</tbody>
</table>


<table>
<thead>
<TABLE  CELLPADDING="2" CELLSPACING="2" WIDTH="100%">
<tr class="header">
<TD width 15%><strong>Dienst</strong></TD>
<TD width 50%><strong>FastTrack-Anleitungsdetails</strong></TD>
<TD width 25%><strong>Erwartungen an die Quellumgebung</strong></TD>
<TR>
</thead>
<tbody>


</tr>
</tbody>
</table>