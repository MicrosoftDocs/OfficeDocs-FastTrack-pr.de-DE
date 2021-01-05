## <a name="security-and-compliance"></a>Sicherheit und Compliance

<table>
<thead>
<tr class="header">
<th><strong>Dienst</strong></th>
<th><strong>Details zum kurzbeschreibungs Handbuch</strong></th>
<th><strong>Anforderungen an die Quellumgebung</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Microsoft 365 Defender</strong></td>

<td> <p> Microsoft 365 Defender ist eine vereinheitlichte, vor-und nach Verletzung der Enterprise Defense-Suite, die die Erkennung, Verhinderung, Untersuchung und Antwort über alle Endpunkte, Identitäten, e-Mails und apps hinweg einheitlich koordiniert und einen integrierten Schutz vor anspruchsvollen Angriffen bietet. Wir bieten Remote-Anleitungen für: </p> 
<ul>
<li>  Bietet eine Übersicht über das Microsoft 365 Security Center.  </li>
<li>  Überprüfung produktübergreifender Vorfälle, einschließlich der Fokussierung auf das, was kritisch ist, indem Sie den vollständigen Angriffsbereich, Betroffene Objekte und die zusammengefassten automatischen Behebungsaktionen sicherstellen.  </li>
<li>  Demonstrieren, wie Microsoft 365 Defender die Untersuchung von Objekten, Benutzern, Geräten und Postfächern orchestrieren kann, die möglicherweise durch die automatische Selbstheilung gefährdet wurden. </li>
<li>  Erläuterung und Bereitstellung von Beispielen dafür, wie Kunden proaktiv nach Intrusionsversuchen und Verletzungs Aktivitäten für Ihre e-Mails, Daten, Geräte und Konten in mehreren Datasets suchen können.   </li>
<li> Zeigt Kunden an, wie Sie Ihre Sicherheitsposition ganzheitlich mithilfe von Microsoft Secure Score überprüfen und verbessern können.</li>
</ul>
<p><strong>Das folgende liegt außerhalb des Bereichs</strong></p>
<ul>
<li> Projektmanagement der Problemlösungsaktivitäten des Kunden. </li>
<li> Fortlaufende Verwaltung, Bedrohungs Antwort und Korrektur. </li>
<li> Bereitstellungsanleitungen oder Schulungen unter:
<ul>
<li> Wie Sie die verschiedenen Warnungstypen und überwachten Aktivitäten korrigieren oder interpretieren. </li>
<li> Vorgehensweise zum Untersuchen eines Benutzers, Computers, einer lateralen Bewegungspfad oder Entität. </li>
<li> Benutzerdefinierte Bedrohungs Suche.  </li>
</ul>
</li>
<li> Security Information and Event Management (SIEM) oder API-Integration.</li>
</td>
</tr>
<tr class="even">
<td><strong>Microsoft Cloud App Security</strong></td>
<td>  Microsoft Cloud App Security ist ein Cloud Access Security Broker (CASB), der eine umfassende Sichtbarkeit, eine Kontrolle über Daten Reisen und ausgefeilte Analysen zum Identifizieren und bekämpfen von Cyber-Bedrohungen für alle Microsoft-und Drittanbieter-Cloud-Dienste bereitstellt. Wir bieten Remote-Anleitungen für:
<ul>
<li>  Konfigurieren des Portals, einschließlich:  </li>
<ul>
<li> Importieren von Benutzergruppen.</li>
<li> Verwalten von Administratorzugriff und-Einstellungen.  </li>
<li> Definieren Sie Ihre Bereitstellung, um bestimmte Benutzergruppen auszuwählen, die überwacht oder von der Überwachung ausgeschlossen werden sollen.</li>
<li> Festlegen von IP-Bereichen und-Tags.</li>
<li> Personalisierung der Benutzeroberfläche mit Ihrem Logo und Ihrem benutzerdefinierten Messaging.</li>
</ul>
<li> Einrichten der Cloud-Ermittlung zur Bereitstellung von Shadow IT mithilfe von:</li>
<ul>
<li> Microsoft Defender für Endpunkte.</li>
<li> Zscaler.</li>
<li> iboss.</li>
</ul>
<li> Verbinden von <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-gove">vorgestellten Apps</a> mithilfe von App-Konnektoren</li>
<li> Einrichten des bedingten Zugriffs-App-Steuerelements in den App-Sicherheitsportalen für bedingte Zugriffe und Clouds zum Anwenden von Steuerelementen für die Echtzeitsitzung.</li>
<li> Bereitstellen der Cloud-App-Sicherheit und von Cloud Discovery-Dashboards</li>
<li> Anpassen von App-Risikobewertungen basierend auf den Prioritäten Ihrer Organisation.</li>
<li> Erstellen von App-Tags und Kategorien.</li>
<li> Sanktionierung und nicht Sanktionierung von apps.</li>
<li> Verwenden der Aktivitäts-und Datei Protokolle</li>
<li> Verwalten von OAuth-apps.</li>
<li> Grundlegendes zur Vorfall Korrelation im Microsoft 365 Defender-Portal.</li>
<li> Bereitstellen von Konfigurationsunterstützung <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">für die 20 häufigsten Anwendungsfälle für CASBs</a> (einschließlich der Erstellung oder Aktualisierung von bis zu sechs (6) Richtlinien) mit Ausnahme von: </li>
<ul>
<li> Überwachen der Konfiguration Ihrer Internet-als-Dienstumgebungen (IaaS) (#18).</li>
<li> Überwachen von Benutzeraktivitäten zum Schutz vor Bedrohungen in ihren IaaS-Umgebungen (#19).</li>
</ul>
</ul>
<p><strong>Das folgende liegt außerhalb des Bereichs</strong></p>
<ul>
<li> Projektmanagement der Problemlösungsaktivitäten des Kunden.</li>
<li> Fortlaufende Verwaltung, Bedrohungs Antwort und Korrektur. </li>
<li> Einrichten der Infrastruktur, Installation oder Bereitstellung automatischer Protokoll Uploads für fortlaufende Berichte mithilfe von Docker oder eines Protokoll Sammlers. Weitere Informationen finden Sie unter <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 Use Cases for CASBs</a> .</li>
<li> Erstellen eines Snapshot-Berichts für die Cloud-Suche.</li>
<li> Blockieren der APP-Verwendung mithilfe von Block Skripts.</li>
<li> Verbinden von benutzerdefinierten apps.</li>
<li> Integration mit Drittanbieter-Identitätsanbietern (Providers) und DLP-Anbietern (Data Loss Prevention, Verhinderung von Datenverlust).</li>
<li> Schulungen oder Anleitungen für die erweiterte Suche.</li>
<li> Automatische Untersuchung und Korrektur einschließlich Microsoft Power-Automatisierungs Textbuch.</li>
<li> Security Information and Event Management (SIEM) oder API-Integration (einschließlich Azure Sentinel).</li>
<li> Bereitstellen der Cloud-App-Sicherheit als Machbarkeitsstudie</li>
</ul></td>
</tr>



<tr class="odd">
<td><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></td>
<td>  Microsoft Defender Advanced Threat Protection (ATP) ist eine Plattform, mit deren Hilfe Unternehmensnetzwerke erweiterte Bedrohungen verhindern, erkennen, untersuchen und darauf reagieren können.  
  Wir bieten Remote-Anleitungen für:
<ul>
<li>  Bereitstellen der Technologien zum Sichern der Endpunkte  </li>
<li>  Konfigurieren von Endpunktschutz-und Geräte Einschränkungs Profilen  </li>
<li>  Bewertung der Betriebssystemversion und Geräteverwaltung (einschließlich InTune, Microsoft Endpoint Configuration Manager, Gruppenrichtlinienobjekte (Group Policy Objects, GPOs) und Konfigurationen von Drittanbietern) sowie der Status Ihrer Windows Defender AV-Dienste oder anderer Endpoint Security-Software.  </li>
<li>  Bewerten des Status Ihrer Windows AV-Dienste oder anderer Endpoint Security-Software.  </li>
<li>  Bewerten von Proxys und Firewalls, die den Netzwerkdatenverkehr einschränken.  </li>
<li>  Aktivieren des Microsoft Defender ATP-Diensts durch erläutern der Bereitstellungeines ATP-Agent-Profils mithilfe eines Onboard-Endpunkts.  </li>
<li>  Bereitstellungsanleitungen, Konfigurationsunterstützung und Schulung unter:
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
<li>  Überprüfen von Simulationen und Lernprogrammen (wie Übungsszenarien, gefälschte Schadsoftware und automatisierte Untersuchungen).  </li>
<li>  Übersicht über die Features "Reporting" und "Threat Analytics"  </li>
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
  Windows Server Semi-Annual-Kanal (SAC) Version 1803.  
  </li>
<li>  
  macOS-Versionen 10,13, 10,14 und 10,15.  
  </li>
</ul>
</li>
</ul>
<strong>Hinweis:</strong> Alle Windows Server-Versionen müssen mit der neuesten Version von System Center Configuration Manager 2012 (Versionen 1012 R2, 1511 oder 1602) oder mit dem Microsoft Endpoint Configuration Manager (Version 2002 oder höher) verwaltet werden. 

</li>
</ul>

<strong>Das folgende liegt außerhalb des Bereichs </strong>  
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
  Mobile Geräte (Android und IOS).  
  </li>
</ul></li>
<li>  Server-Onboarding und-Konfiguration:
<ul>
<li>  
  Konfigurieren eines Proxyservers für die Offline Kommunikation.  
  </li>
<li>  
  Konfigurieren von Configuration Manager-Bereitstellungspaketen auf untergeordneten Configuration Manager-Instanzen und-Versionen.  
  </li>
<li>  
  Onboarding-Server im Azure Security Center.  
  </li>
<li>  
  Server, die nicht von Configuration Manager verwaltet werden.  
  </li>
</ul></li>
<li>  macOS-Onboarding und-Konfiguration:
<ul>
<li>  
  Manuelle InTune-basierte Bereitstellung.  
  </li>
<li>  
  JAMF-basierte Bereitstellung.
  </li>
<li>  
  Andere produktbasierte MDM-Bereitstellung (Mobile Device Management).  
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
<li>  Konfiguration oder Schulung Überprüfen der API oder der Sicherheitsinformationen und der Ereignisverwaltung (SIEM)-Verbindungen.  </li>
<li>  Registrierung oder Konfiguration von Microsoft Threat Protection (MTP).  </li>
<li>  Schulungen oder Anleitungen für die erweiterte Suche.  </li>
<li>  Schulungen oder Anleitungen für die Verwendung oder Erstellung von Kusto-Abfragen.</li>
</li>
</ul>
Wenden Sie sich an einen <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft-Partner</a> , um Unterstützung für diese Dienste zu erhalten.  
</ul></td>
<td></td>

<tr class="odd">
<td><strong>Microsoft Defender für Identity </strong></td>
<td>  Microsoft Defender for Identity ist eine Cloud-basierte Sicherheitslösung, die ihre lokalen Active Directory Signale nutzt, um erweiterte Bedrohungen, kompromittierte Identitäten und böswillige Insider Aktionen zu identifizieren, zu erkennen und zu untersuchen, die an Ihre Organisation gerichtet sind. Wir bieten Remote-Anleitungen für:
<ul>
<li>   Erstellen Ihrer Instanz von Defender für Identity. </li>
<li>   Verbinden von Defender für Identität mit Active Directory. </li>
<li>   Bewerten der Bereitschaft Ihrer Umgebung zur Bereitstellung des Defender for Identity Sensors auf Ihren Domänencontrollern, einschließlich:</li>   
<ul> 
<li>  Ausführung des Sizing-Tools für die Planung von Ressourcen Kapazitäten. </li>
<li>  Durchführen des Überwachungstools, um die Kompatibilität Ihrer Domänencontroller mit dem Sensor zu bewerten. </li>
</ul>
<li>  Bereitstellen des Sensors zum Erfassen und Analysieren von Netzwerkdatenverkehr und Windows-Ereignissen direkt von Ihren Domänencontrollern, einschließlich: </li>
<ul> 
<li>  Herunterladen des Sensor Pakets. </li>
<li>  Konfigurieren des Sensors. </li>
<li>  Unbeaufsichtigtes Installieren des Sensors auf dem Domänencontroller. </li>
<li>  Bereitstellen des Sensors in Ihrer Umgebung mit mehreren Gesamtstrukturen. </li>
</ul>
<li>  Integrieren von Defender for Identity mit Microsoft Cloud App Security (Cloud App Security Licensing ist nicht erforderlich). </li>
<li>  Bereitstellen von Bereitstellungsanleitungen, Konfigurationsunterstützung und Schulung für: </li>
<ul>
<li> Optimieren der Umgebung, um "Rauschen" zu reduzieren  </li>
<li>  Grundlegendes zum Beurteilungsbericht für Identitäts Sicherheits Positionen. </li>
<li>  Grundlegendes zum Bewertungsbericht über die Benutzer Ermittlung und-Bewertung. </li>
<li> Grundlegendes zum inaktiven Benutzerbericht.  </li>
<li> Bereitstellen von Korrekturoptionen für ein kompromittiertes Konto.  </li>
</ul>
<li>  Erleichterung der Migration von Advanced Threat Analytics (ATA) zur Defender for Identity. </li>
</ul>
<p><strong>Das folgende liegt außerhalb des Bereichs</strong></p>
<ul>

<li> Projektmanagement der Problemlösungsaktivitäten des Kunden. </li>
<li> Fortlaufende Verwaltung, Bedrohungs Antwort und Korrektur.  </li>
<li> Bereitstellen des Defender für den Identitäts Sensor, einschließlich: </li>
<ul>
<li> Manuelle Kapazitätsplanung. </li>
<li> Bereitstellen des Sensors in einer eigenständigen Kapazität. </li>
<li> Bereitstellen des Sensors mithilfe eines Netzwerkschnittstellenkarten-Teaming-Adapters (NIC) </li>
<li> Bereitstellen des Sensors über ein Drittanbietertool. </li>
<li> Herstellen einer Verbindung mit dem Defender für den Identitäts-clouddienst über eine Webproxy Verbindung </li>
</ul>
<li> Erstellen und Verwalten von honeytokens. </li>
<li> Bereitstellungsanleitungen oder Schulungen unter: </li>
<ul>
<li> Remediation oder Interpretation verschiedener Warnungstypen und überwachten Aktivitäten.  </li>
<li> Untersuchen eines Benutzers, Computers, lateralen Bewegungspfads oder einer Entität. </li>
<li> Bedrohung oder erweiterte Jagd. </li>
<li> Vorfall Antwort. </li>
</ul>
<li> Bereitstellen eines Lernprogramms für Sicherheitswarnungen für Defender for Identity. </li>
<li> Bereitstelleneiner Benachrichtigung, wenn Defender for Identity verdächtige Aktivitäten erkennt, indem Sicherheitswarnungen über einen benannten Sensor an Ihren Syslog-Server gesendet werden.  </li>
<li> Konfigurieren von Defender for Identity zum Ausführen von Abfragen mithilfe des SAMR-Protokolls (Security Account Manager Remote), um lokale Administratoren auf bestimmten Computern zu identifizieren. </li>
<li> Konfigurieren von VPN-Lösungen zum Hinzufügen von Informationen aus der VPN-Verbindung zur Profilseite eines Benutzers.  </li>
<li> Security Information and Event Management (SIEM) oder API-Integration (einschließlich Azure Sentinel). </li>
<li> Bereitstellen von Defender für Identitäts Sensoren als Machbarkeitsstudie</li>
</ul></td>
<td><ul>
<li>  Active Directory bereitgestellt.  </li>
<li>  Die Domänencontroller, auf denen Sie Defender für Identitäts Sensoren installieren möchten, verfügen über eine Internetverbindung mit dem Defender for Identity Cloud Service.  </li>
<ul>
<li> Ihre Firewall und der Proxy müssen für die Kommunikation mit dem Defender for Identity Cloud Service geöffnet sein (*. ATP.Azure.com Port 443 muss geöffnet sein).</li>
</ul>
<li> Domänencontroller mit einer der folgenden Optionen:</li>
<ul>
<li> Windows Server 2008 R2 SP1.</li>
<li> Windows Server 2012.</li>
<li> Windows Server 2012 R2.</li>
<li> Windows Server 2016.</li>
<li> Windows Server 2019 mit KB4487044 (OS Build 17763,316).</li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><strong>Microsoft Information Governance</strong></td>
<td>  Wir bieten Remote-Anleitungen für:
<ul>
<li>  Aufbewahrungsbezeichnungen und Richtlinien.  </li>
<li>  Verwaltung von Unterlagen.  </li>
<li>  Löschungsrichtlinien.  </li>
<li>  Kommunikationscompliance.  </li>
<li>  Insider-Risikomanagement.  </li>
<li>  Advanced eDiscovery.  </li>
</ul>

  <strong>Das folgende liegt außerhalb des Bereichs </strong>  
<ul>
<li> Entwicklung eines Daten Satz Verwaltungsdatei Plans.</li>
<li> Daten-Konnektoren.</li>
<li> Informationsbarrieren.</li>
<li> Privilegierte Zugriffsverwaltung.</li>
<li> Entwicklung der Informationsarchitektur in SharePoint.</li>
<li> Benutzerdefinierte Skripterstellung und Codierung.</li>
</td>
<td>Neben dem <strong>Haupt-Onboarding</strong> -Teil im <a href="#general">allgemeinen</a>gibt es keine minimalen Systemanforderungen.</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Information Protection</strong></td>
<td>  Wir bieten Remote-Anleitungen für:
<ul>
<li>  Datenklassifikation.  </li>
<li>  Typen vertraulicher Informationen.  </li>
<li>  Erstellen von Vertraulichkeitsbezeichnungen.  </li>
<li>  Anwenden von Sensitivitäts Bezeichnungen.  </li>
<li>  Einheitliche Bezeichnungen.  </li>
<li>  Trainierbare Klassifizierungsmerkmale.  </li>
<li>  Erkennen Ihrer Daten über den Inhalts- und Aktivitäten-Explorer.  </li>
<li>  Veröffentlichen von Bezeichnungen mithilfe von Richtlinien (manuell und automatisch).  </li>
<li>  Erstellen von Richtlinien zum Schutz vor Datenverlust (DLP) für Microsoft Teams-Chats und -Kanäle.  </li>
<li>  Erstellen von Endpunkt-DLP-Richtlinien für Windows 10-Geräte.  </li>
</ul>

<strong>Das folgende liegt außerhalb des Bereichs </strong>  
<ul>
<li>Kundenschlüssel.</li>
<li>Entwicklung benutzerdefinierter regulärer Ausdrücke (Regex) für vertrauliche Informationstypen.</li>
<li>Erstellen oder Ändern von Schlüsselwörter Wörterbüchern.</li>
<li>Benutzerdefinierte Skripterstellung und Codierung.</li>
</ul>
<strong>Hinweis:</strong> Weitere Informationen finden Sie unter <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.
<ul>

</td>
<td>Neben dem <strong>Haupt-Onboarding</strong> -Teil im <a href="#general">allgemeinen</a>gibt es keine minimalen Systemanforderungen.</td>
</tr>

<tr class="odd">
<td><strong>Office 365 Advanced Threat Protection (ATP)</strong></td>
<td>  Wir bieten Remote-Anleitungen für:
<ul>
<li>  Aktivieren von sicheren Links, sicheren Anlagen und Antiphishing.  </li>
<li>  Konfigurieren von Automatisierung, Untersuchung und Reaktion.  </li>
<li>  Verwenden des Angriffssimulators.  </li>
<li>  Berichterstellung und Bedrohungsanalyse.  </li>
</ul></td>
<td>Neben dem <strong>Haupt-Onboarding</strong> -Teil im <a href="#general">allgemeinen</a>gibt es keine minimalen Systemanforderungen.</td>
</tr>

</tbody>
</table>


<table>
<thead>
<TABLE  CELLPADDING="2" CELLSPACING="2" WIDTH="100%">
<tr class="header">
<TD width 15%><strong>Dienst</strong></TD>
<TD width 50%><strong>Details zum kurzbeschreibungs Handbuch</strong></TD>
<TD width 25%><strong>Anforderungen an die Quellumgebung</strong></TD>
<TR>
</thead>
<tbody>


</tr>
</tbody>
</table>