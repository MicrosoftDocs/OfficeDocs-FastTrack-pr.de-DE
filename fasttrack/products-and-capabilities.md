---
title: Produkte und Funktionen
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/27/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Dieses Thema enthält Details zu den von FastTrack unterstützten Arbeitsauslastungsszenarien und den Erwartungen an die Quellumgebung, die erforderlich sind, bevor wir beginnen können. Basierend auf Ihrem aktuellen Setup arbeiten wir mit Ihnen zusammen, um einen Wartungsplan zu erstellen, mit dem Ihre Quellumgebung die Mindestanforderungen für ein erfolgreiches Onboarding erfüllt.
ms.openlocfilehash: abbc97a7b2d70b0b0111f1cbe96904bbe552e463
ms.sourcegitcommit: cd8426ce64dda56439933576e7da75b1c27f5de1
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 01/27/2021
ms.locfileid: "50016687"
---
# <a name="products-and-capabilities"></a>Produkte und Funktionen

## <a name="services-and-scenarios-supported-by-fasttrack"></a>Von FastTrack unterstützte Dienste und Szenarien

Dieses Thema enthält Details zu den von FastTrack unterstützten Arbeitsauslastungsszenarien und den Erwartungen an die Quellumgebung, die erforderlich sind, bevor wir beginnen können. Basierend auf Ihrem aktuellen Setup arbeiten wir mit Ihnen zusammen, um einen Wartungsplan zu erstellen, mit dem Ihre Quellumgebung die Mindestanforderungen für ein erfolgreiches Onboarding erfüllt.

FastTrack bietet Anleitungen, mit deren Hilfe Sie zunächst mit kernfähigen Funktionen (die für alle Microsoft Online Services) und dann mit dem Onboarding der einzelnen berechtigten Dienste unterstützt werden:

  - [Allgemein](#general)
  - [Sicherheit und Compliance](#security-and-compliance)
  - [Office 365](#office-365)
  - [Enterprise Mobility + Security](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [Windows Virtual Desktop](#windows-virtual-desktop)
  - [App Assure](#app-assure)
  - [Microsoft Edge](#microsoft-edge)

> [!NOTE]
> Informationen zu Anforderungen an die Quellumgebung für Office 365 US Government finden Sie unter [Anforderungen an die Quellumgebung für Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations). 
 
## <a name="general"></a>Allgemein

<table>
<thead>
<tr class="header">
<th><strong>Dienst</strong></th>
<th><strong>Details zur FastTrack-Anleitung</strong></th>
<th><strong>Erwartungen an die Quellumgebung</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Haupt-Onboarding</strong></td>
<td>  Wir bieten Remoteanleitungen für das Kern-Onboarding, das die Dienstbereitstellung, mandanten- und identitätsintegration umfasst. Es umfasst außerdem Schritte zur Bereitstellung einer Grundlage für Onboardingdienste wie Exchange Online, SharePoint Online und Microsoft Teams, einschließlich einer Diskussion über <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">Sicherheit, Netzwerkkonnektivität und Compliance.</a>  
  Das Onboarding für einen oder mehrere berechtigte Dienste kann beginnen, sobald das Haupt-Onboarding abgeschlossen ist.
</li>
</ul>  

<strong> Identitätsintegration </strong>

Wir bieten Remoteanleitungen für:
<ul>
<li>Vorbereiten der lokalen Active Directory-Identitäten für die Synchronisierung mit Azure Active Directory (Azure AD), einschließlich der Installation und Konfiguration von Azure AD Connect (Einzel- oder Gesamtstrukturen) und Lizenzierung (einschließlich gruppenbasierter Lizenzierung).</li>
<li>Erstellen von Cloudidentitäten, einschließlich Massenimport und Lizenzierung, einschließlich der Gruppenlizenzierung.</li>
<li>Auswählen und Aktivieren der richtigen Authentifizierungsmethode für Ihre Cloud Journey, Kennworthashsynchronisierung, Pass-Through-Authentifizierung oder Active #A0 (AD FS).</li>
<li>Aktivieren von AD FS für Kunden mit einer einzelnen Active Directory-Gesamtstruktur und Identitäten, die mit dem Azure AD Connect-Tool synchronisiert sind. Dies erfordert Windows Server 2012 R2 Active Directory Federation Services 2.0 oder höher.</li>
<li>Migrieren der Authentifizierung von AD FS zu Azure AD mithilfe der Kennworthashsynchronisierung oder Pass-Through-Authentifizierung.</li>
<li>Migrieren von vorab integrierten Apps (z. B. Azure AD-Katalog-Software-as-a-Service (SaaS)-Apps) von AD FS zu Azure AD für einmaliges Anmelden (Single Sign-On, SSO).</li>
<li>Aktivieren von SaaS-App-Integrationen in SSO aus dem Azure AD-Katalog.</li>
<li>Aktivieren der automatischen Benutzerbereitstellung für vorab integrierte SaaS-Apps, wie in der Lernprogrammliste für die App-Integration <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">aufgeführt</a> (beschränkt auf Azure AD-Katalog-SaaS-Apps und ausgehende Bereitstellung).  </li>
</td>

<td>  <strong>Netzwerkermöglichung </strong>  
  <br>Im Rahmen des FastTrack-Vorteils empfehlen wir Ihnen bewährte Methoden für die Verbindung mit Clouddiensten, um das höchste Leistungsniveau von Microsoft 365 sicherzustellen.  
  
<strong>Active Directory-Gesamtstrukturen</strong> Für diese wird die Ebene der funktionalen Gesamtstruktur auf Windows Server 2003 und mehr festgelegt, mit der folgenden Gesamtstrukturkonfiguration:
<ul>
<li>  Einzelne Active Directory-Gesamtstruktur  </li>
<li>  Eine einzelne Active Directory-Kontogesamtstruktur und Ressourcen-Gesamtstrukturtopologien (Exchange und/oder Lync 2010, Lync 2013 oder Skype for Business)  </li>
<li>  Mehrere Active Directory-Kontogesamtstrukturen und Ressourcen-Gesamtstrukturtopologien (Exchange und/oder Lync 2010, Lync 2013 oder Skype for Business)  </li>
<li>  Mehrere Active Directory-Kontogesamtstrukturen, wobei eine der Gesamtstrukturen eine Gesamtstruktur mit einem zentralen Active Directory-Konto ist, die Exchange und/oder Lync 2010, Lync 2013 oder Skype for Business umfasst.  </li>
<li>  Mehrere Active Directory-Konto-Gesamtstrukturen mit einer jeweils eigenen Exchange-Organisation  </li>
<li>  Aufgaben, die bei Bedarf für die Mandantenkonfiguration und -integration in Azure Active Directory erforderlich sind.   </li>
</ul>
  <strong>Wichtig</strong>  <ul>
<li>  Wenn Lync 2010, Lync 2013 oder Skype for Business in Active Directory mit mehreren Gesamtstrukturen bereitgestellt wird, muss es in derselben Active Directory-Gesamtstruktur wie Exchange bereitgestellt werden.  </li>
<li>  Bei der Implementierung mehrerer Active Directory-Gesamtstrukturen mit mehreren Exchange-Organisationen in einer Exchange-Multihybridkonfiguration werden freigegebene UpN-Namespaces (User Principal Name, Benutzerprinzipalname) zwischen Quell gesamtstrukturen nicht unterstützt. Primäre SMTP-Namespaces zwischen Exchange-Organisationen sollten ebenfalls getrennt werden. Weitere Informationen finden Sie unter <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybridbereitstellungen mit mehreren Active Directory-Gesamtstrukturen</a>.  </li>
<li>  Für alle Konfigurationen mit mehreren Gesamtstrukturen ist die Active Directory Federation Services (AD FS)-Bereitstellung nicht zulässig. Wenden Sie sich <a href="https://go.microsoft.com/fwlink/?linkid=2080150">an einen Microsoft-Partner,</a> um Unterstützung zu erhalten.  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft 365 Apps</strong></td>
<td>  Wir bieten Anleitungen zur Remotebereitstellung für:
<ul>
<li>  Beheben von Problemen bei der Bereitstellung  </li>
<li>  Zuweisen von Endbenutzerlizenzen und gerätebasierten Lizenzen mit Microsoft 365 Admin Center und Windows PowerShell.  </li>
<li>  Installieren von Microsoft 365-Apps aus dem Office 365-Portal mithilfe von Klick-und-Los.  </li>
<li>  Installieren von Office Mobile-Apps (wie Outlook Mobile, Word Mobile, Excel Mobile und PowerPoint Mobile) auf Ihren iOS- oder Android-Geräten.  </li>
<li>  Konfigurieren von Updateeinstellungen mit dem Office 365-Bereitstellungstool  </li>
<li>  Auswahl und Einrichtung einer lokalen oder Cloud-Installation.  </li>
<li>  Erstellung der Konfigurations-XML des Office-Bereitstellungstool mit dem Office-Anpassungstool oder nativem XML zur Konfiguration des Bereitstellungspakets.  </li>
<li>  Bereitstellen mit Microsoft Endpoint Configuration Manager, einschließlich Unterstützung beim Erstellen des Microsoft Endpoint Configuration Manager-Pakets.  
  Wenn Sie außerdem über ein Makro oder Ein-Add-In verfügen, das mit früheren Versionen von Office funktioniert hat und Kompatibilitätsprobleme auftreten, bieten wir Anleitungen zur Behebung des Kompatibilitätsproblems ohne zusätzliche Kosten über das App Assure-Programm. Weitere Informationen <strong>finden Sie im Abschnitt "App Assure"</strong> von Windows <a href="#windows-10">10.</a> </li>
</ul></td>
<td><ul>
<li>  Die Onlineclientsoftware muss auf einer Mindeststufe wie in den Systemanforderungen für <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365</a>und Office definiert sein.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Netzwerkinte health</strong></td>
<td>  Wir bieten Remoteanleitungen zum Abrufen und Interpretieren wichtiger Netzwerkverbindungsdaten aus Ihrer Umgebung, die zeigen, wie die Standorte Ihrer Organisation den Prinzipien der Netzwerkkonnektivität von Microsoft <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">entsprechen.</a> Dies hebt Ihre Netzwerkpunktzahl hervor, die sich direkt auf die Migrationsgeschwindigkeit, die Benutzerfreundlichkeit, die Dienstleistung und die Zuverlässigkeit auswirken.  
  Wir führen Sie auch durch alle Korrekturschritte, die durch diese Daten hervorgehoben werden, um Ihnen zu helfen, Ihre Netzwerkpunktzahl zu verbessern.  </td>
<td><ul>
<li>  Zugriff auf das Microsoft 365 Admin Center.  </li>
<li>  Es sind aktuelle Versionen von Microsoft 365-Apps erforderlich.  </li>
<li>  Ortungsdienste, die nach <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Netzwerkleistungsempfehlungen im Microsoft 365 Admin Center (Vorschau) aktiviert sind.</a>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a>Sicherheit und Compliance

<table>
<thead>
<tr class="header">
<th><strong>Dienst</strong></th>
<th><strong>Details zur FastTrack-Anleitung</strong></th>
<th><strong>Erwartungen an die Quellumgebung</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><strong>Azure Active Directory (Azure AD) und Azure AD Premium</strong></td>
<td>  Wir bieten Remoteanleitungen zum Sichern Ihrer Cloudidentitäten für die folgenden Szenarien.  

 <br/>

<strong>Sichere Foundation-Infrastruktur</strong>  </ul>
<ul>
<li>  Konfigurieren und Aktivieren einer starken Authentifizierung für Ihre Identitäten, einschließlich des Schützens mit Azure Multi-Factor Authentication (MFA) (nur Cloud), der Microsoft Authenticator-App und der kombinierten Registrierung für Azure MFA und Self-Service-Kennwortzurücksetzung (Self-Service Password Reset, SSPR).  </li>
<li>  Für Nicht-Azure AD Premium-Kunden wird eine Anleitung bereitgestellt, um Ihre Identitäten mithilfe von Sicherheitseinstellungen zu schützen.  </li>
<li>  Für Azure AD Premium-Kunden wird eine Anleitung bereitgestellt, um Ihre Identitäten mit bedingten Zugriff zu schützen.  </li>
<li>  Erkennen und Blockieren der Verwendung von schwachen Kennwörtern mit Azure AD Password Protection.  </li>
<li>  Schützen des Remotezugriffs auf lokale Web-Apps mit dem Azure AD-Anwendungsproxy.  </li>
<li>  Aktivieren der risikobasierten Erkennung und Behebung mit Azure Identity Protection.  </li>
<li>  Aktivieren eines angepassten Anmeldebildschirms, einschließlich Logo, Text und Bildern mit benutzerdefiniertem Branding.  </li>
<li>  Sicheres Freigeben von Apps und Diensten für Gastbenutzer mit Azure AD B2B.  </li>
<li>  Verwalten des Zugriffs für Ihre Office 365-Administratoren mithilfe von integrierten Administratorrollen der rollenbasierten Zugriffssteuerung (Role-Based Access Control, RBAC) und Verringern der Anzahl privilegierter Administratorkonten.  </li>
<li>  Konfigurieren der Azure AD-Hybrid-Verknüpfung.  </li>
<li>  Konfigurieren der Azure AD-Verknüpfung.  </li>
</ul>
  
<strong>Überwachen und Melden</strong>  
<ul>
<li>  
  Aktivieren der Remoteüberwachung für AD FS, Azure AD Connect und Domänencontroller mit Azure AD Connect Health.  
  </li>
</ul>
  
<strong>Governance</strong>  
<ul>
<li>  
  Verwalten Ihrer Azure AD-Identität und des Zugriffslebenszyklus im großen Maßstab mit Azure AD-Berechtigungsverwaltung.
  </li>
<li>  
  Verwalten von Azure AD-Gruppenmitgliedschaften, Enterprise-App-Zugriff und Rollenzuweisungen mit Azure AD-Zugriffsüberprüfungen.  
  </li>
<li>  
  Überprüfen der Azure AD-Nutzungsbedingungen.  
  </li>
<li>  
  Verwalten und Steuern des Zugriffs auf privilegierte Administratorkonten mit Azure AD Privileged Identity Management.  
  </li>
</ul>
  
<strong>Automatisierung und Effizienz </strong>  
<ul>
<li>  
  Aktivieren von Azure AD SSPR.  
  </li>
<li>  Zulassen, dass Benutzer ihre eigenen Cloudsicherheits- oder Office 365-Gruppen mit Azure AD Self-Service-Gruppenverwaltung erstellen und verwalten können.  </li>
<li>  Verwalten des delegierten Zugriffs auf Unternehmens-Apps mit delegierter Azure AD-Gruppenverwaltung.  </li>
<li>  Aktivieren dynamischer Azure AD-Gruppen.  </li>
<li>  Organisieren von Apps im Meine Apps-Portal mithilfe von Sammlungen.  </li>
</ul></td>
<td>Das lokale Active Directory und seine Umgebung wurden für Azure AD Premium vorbereitet, einschließlich der Behebung identifizierter Probleme, die die Integration in Azure AD- und Azure AD -Premium-Features verhindern.</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection </strong></td>
<td>  Wir bieten Remoteanleitungen für:
<ul>
<li>  Aktivieren und Konfigurieren Ihres Mandanten.  </li>
<li>  Erstellen und Einrichten von Bezeichnung und Richtlinien.  </li>
<li>  Anwendung von Informationsschutz auf Dokumente.  </li>
<li>  Automatische Klassifizierung und Bezeichnung von Informationen in Office-Anwendungen (wie Word, PowerPoint, Excel und Outlook), die unter Windows ausgeführt werden und den Azure Information Protection Client verwenden.  </li>
<li>  Ermitteln und Beschriften von Dateien im Ruheschutz mithilfe des Azure Information Protection-Scanners.  </li>
<li>  Überwachung von E-Mails während des Versands unter Verwendung von Exchange Online Nachrichtenflussregeln.  </li>
</ul>
Wir bieten auch Anleitungen, wenn Sie Schutz mit Microsoft Azure Rights Management Services (Azure RMS), Office 365-Nachrichtenverschlüsselung (OME) und Verhinderung von Datenverlust (Data Loss Prevention, DLP) anwenden möchten.  </td>
<td>  Zu den verantwortlichen Zuständigkeiten des Kunden gehören:
<ul>
<li>  Eine Liste der zu scannende Speicherorte für Dateifreigaben.  </li>
<li>  Eine genehmigte Klassifizierungstaxonomie. </li>
<li> Grundlegendes zu behördlichen Einschränkungen oder Anforderungen in Bezug auf die Schlüsselverwaltung.  </li>
<li>  Ein Dienstkonto, das für Ihr lokales Active Directory erstellt wurde, das mit Azure AD synchronisiert wurde. </li>
<li>  Bezeichnungen, die für Klassifizierung und Schutz konfiguriert sind. </li>
<li> Alle Voraussetzungen für den Azure Information Protection-Scanner sind erfüllt. Weitere Informationen finden Sie unter "Voraussetzungen für die Installation und Bereitstellung des <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Azure Information Protection-Scanners für einheitliche Bezeichnungen".</a> </li>
<li>  Stellen Sie sicher, dass auf den Benutzergeräten ein unterstütztes Betriebssystem ausgeführt wird und die erforderlichen Komponenten installiert sind. Weitere Informationen finden Sie im Folgenden.</li>
<ul>
<li> <a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Administratorhandbuch: Installieren des Azure Information Protection einheitlichen Bezeichnungsclients für Benutzer</a>   </li>
<li>  <a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">Was ist die Azure Information Protection-App für iOS oder Android?</a>  </li>
</ul>
<li> Installation und Konfiguration des Azure RMS-Connectors und der Server, einschließlich des Active Directory RMS (AD RMS)-Connectors für die Hybridunterstützung.  </li>
<li> Setup und Konfiguration von Bring Your Own Key (BYOK), Double Key Encryption (DKE) (nur Client mit einheitlichen Bezeichnungen) oder Halten eines eigenen Schlüssels (nur klassischer Client), falls Sie eine dieser Optionen für Ihre Bereitstellung benötigen.  </li>
  </ul>
</ul>
  
</td>
</tr>

<tr class="even">
<td><strong>Microsoft 365 Defender</strong></td>

<td> <p> Microsoft 365 Defender ist eine einheitliche Suite vor und nach der Verletzung des Unternehmens, die Erkennung, Verhinderung, Untersuchung und Reaktion über Endpunkte, Identitäten, E-Mails und Apps hinweg koordiniert, um integrierten Schutz vor ausgeklügelten Angriffen zu bieten. Wir bieten Remoteanleitungen für: </p> 
<ul>
<li>  Bereitstellen einer Übersicht über das Microsoft 365 Security Center.  </li>
<li>  Überprüfen von produktübergreifenden Vorfällen, einschließlich der Fokussierung auf wichtige Ereignisse, indem sichergestellt wird, dass der gesamte Angriffsbereich, die ressourcenbelastenden Ressourcen und die automatisierten Abhilfemaßnahmen, die zusammengeteilt sind, sichergestellt werden.  </li>
<li>  Demonstrieren, wie Microsoft 365 Defender die Untersuchung von Ressourcen, Benutzern, Geräten und Postfächern orchestrieren kann, die möglicherweise durch die automatisierte Selbsthilfe gefährdet wurden. </li>
<li>  Erläutern und Bereitstellen von Beispielen dafür, wie Kunden proaktiv nach Angriffsversuchen und Sicherheitsverletzungen abwehren können, die Sich auf Ihre E-Mails, Daten, Geräte und Konten in mehreren Datensätzen ausdähen.   </li>
<li> Zeigen Sie Kunden, wie sie ihren Sicherheitsstand ganzheitlich mithilfe der Microsoft Secure Score überprüfen und verbessern können.</li>
</ul>
<p><strong>Folgendes liegt nicht im Gültigkeitsbereich</strong></p>
<ul>
<li> Projektmanagement der Problemlösungsaktivitäten des Kunden. </li>
<li> Fortlaufende Verwaltung, Bedrohungsreaktion und Problembehebung. </li>
<li> Bereitstellungsleitfas oder Bildungseinrichtungen zu:
<ul>
<li> Wie die verschiedenen Warnungstypen und überwachten Aktivitäten behoben oder interpretiert werden. </li>
<li> Untersuchen eines Benutzers, Computers, lateralen Bewegungspfads oder einer Entität. </li>
<li> Benutzerdefinierte Bedrohungssuche.  </li>
</ul>
</li>
<li> Sicherheitsinformationen und Ereignisverwaltung (SIEM) oder API-Integration.</li>
</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Cloud App Security</strong></td>
<td>  Microsoft Cloud App Security ist ein Cloud Access Security Broker (CASB), der umfassende Transparenz, Kontrolle über den Datenverkehr und komplexe Analysen zur Identifizierung und Bekämpfung von Cyberbedrohungen in allen Ihren Microsoft- und Drittanbieter-Clouddiensten bietet. Wir bieten Remoteanleitungen für:
<ul>
<li>  Konfigurieren des Portals, einschließlich:  </li>
<ul>
<li> Importieren von Benutzergruppen.</li>
<li> Verwalten des Administratorzugriffs und der Einstellungen.  </li>
<li> Legen Sie die Bereitstellung so fest, dass bestimmte Benutzergruppen ausgewählt werden, die überwacht oder von der Überwachung ausgeschlossen werden.</li>
<li> Festlegen von IP-Bereichen und -Tags.</li>
<li> Personalisieren der Endbenutzererfahrung mit Ihrem Logo und benutzerdefiniertem Messaging.</li>
</ul>
<li> Einrichten der Cloudermittlung zur Bereitstellung von Schatten-IT mithilfe von:</li>
<ul>
<li> Microsoft Defender für Endpunkte.</li>
<li> Zscaler.</li>
<li> iboss.</li>
</ul>
<li> Verbinden <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">von empfohlenen Apps</a> mithilfe von App-Connectors.</li>
<li> Einrichten der App-Steuerung für bedingten Zugriff in den Portalen für bedingten Zugriff und Cloud App Security zum Anwenden von Echtzeitsitzungssteuerelementen.</li>
<li> Bereitstellen der Cloud App Security- und Cloud Discovery-Dashboards.</li>
<li> Anpassen von Risikobewertungen für Apps basierend auf den Prioritäten Ihrer Organisation.</li>
<li> Erstellen von App-Tags und -Kategorien.</li>
<li> Sanktionieren und Unanktionieren von Apps.</li>
<li> Verwenden der Aktivitäts- und Dateiprotokolle.</li>
<li> Verwalten von OAuth-Apps.</li>
<li> Grundlegendes zur Vorfallkorrelation im Microsoft 365 Defender-Portal.</li>
<li> Bereitstellung von Konfigurationsunterstützung für die <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> am besten verwendeten Fälle für CASBs (einschließlich der Erstellung oder Aktualisierung von bis zu sechs (6) Richtlinien mit Ausnahme von: </li>
<ul>
<li> Überwachen der Konfiguration Ihrer Internet as a Service (IaaS)-Umgebungen (#18).</li>
<li> Überwachen von Benutzeraktivitäten zum Schutz vor Bedrohungen in Ihren IaaS-Umgebungen (#19).</li>
</ul>
</ul>
<p><strong>Folgendes ist nicht gegenstands-</strong></p>
<ul>
<li> Projektmanagement der Problemlösungsaktivitäten des Kunden.</li>
<li> Fortlaufende Verwaltung, Bedrohungsreaktion und Problembehebung. </li>
<li> Einrichten der Infrastruktur, Installation oder Bereitstellung von automatischen Protokolluploads für kontinuierliche Berichte mithilfe von Docker oder einem Protokollsammler. Weitere Informationen finden Sie unter den 20 am meisten verwendeten Fällen für <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">CASBs.</a></li>
<li> Erstellen eines Cloud Discovery-Snapshotberichts.</li>
<li> Blockieren der Verwendung von Apps mithilfe von Blockskripts.</li>
<li> Verbinden von benutzerdefinierten Apps</li>
<li> Integration mit Identitätsanbietern von Drittanbietern (IsPs) und Anbietern zur Verhinderung von Datenverlust (Data Loss Prevention, DLP).</li>
<li> Schulungen oder Anleitungen für die erweiterte Suche.</li>
<li> Automatisierte Untersuchung und Wartung, einschließlich Microsoft Power Automate-Playbooks.</li>
<li> Sicherheitsinformationen und Ereignisverwaltung (SIEM) oder API-Integration (einschließlich Azure Sentinel).</li>
<li> Bereitstellen der Cloud App Discovery als Konzeptnachweis.</li>
</ul></td>
</tr>



<tr class="even">
<td><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></td>
<td>  Microsoft Defender Advanced Threat Protection (ATP) ist eine Plattform, mit deren Hilfe Unternehmensnetzwerke erweiterte Bedrohungen verhindern, erkennen, untersuchen und darauf reagieren können.  
  Wir bieten Remoteanleitungen für:
<ul>
<li>  Bereitstellen der Technologien zum Sichern Ihrer Endpunkte.  </li>
<li>  Konfigurieren von Endpunktschutz- und Geräteeinschränkungsprofilen.  </li>
<li>  Bewerten der Betriebssystemversion und Geräteverwaltung (einschließlich Intune, Microsoft Endpoint Configuration Manager, Gruppenrichtlinienobjekte (GPOs) und Drittanbieterkonfigurationen sowie des Status Ihrer Windows Defender -AV-Dienste oder anderer Endpunktsicherheitssoftware.  </li>
<li>  Bewerten des Status Ihrer Windows -AV-Dienste oder anderer Endpunktsicherheitssoftware.  </li>
<li>  Bewerten von Proxys und Firewalls, die den Netzwerkdatenverkehr einschränken.  </li>
<li>  Aktivieren des Microsoft Defender ATP-Diensts, indem erläutert wird, wie ein ATP-Agent-Profil mithilfe eines integrierten Endpunkts bereitgestellt wird.  </li>
<li>  Bereitstellungsleitfas, Konfigurationsunterstützung und Bildungseinrichtungen zu:
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
<li>  Überprüfen von Simulationen und Lernprogrammen (z. B. Praxisszenarien, gefälschte Schadsoftware und automatisierte Untersuchungen).  </li>
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
  macOS Version 10.13, 10.14 und 10.15.  
  </li>
</ul>
</li>
</ul>
<strong>Hinweis:</strong> Alle Windows Server-Versionen müssen mit der neuesten Version von System Center Configuration Manager 2012 (Versionen 1012 R2, 1511 oder 1602) oder Microsoft Endpoint Configuration Manager (Version 2002 oder höher) verwaltet werden. 

</li>
</ul>

<strong>Folgendes ist nicht gegenstands- </strong>  
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
<li>  Server-Onboarding und -Konfiguration:
<ul>
<li>  
  Konfigurieren eines Proxyservers für die Offlinekommunikation.  
  </li>
<li>  
  Konfigurieren von Configuration Manager-Bereitstellungspaketen für Konfigurations-Manager-Instanzen und -Versionen auf einer älteren Ebene.  
  </li>
<li>  
  Onboarding von Servern in Azure Security Center.  
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
  Andere produktbasierte Bereitstellung für die mobile Geräteverwaltung (MdM).  
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
<li>  Konfiguration oder Schulung zur Überprüfung von API- oder Sicherheitsinformationen und Ereignisverwaltung (SIEM)-Verbindungen.  </li>
<li>  Registrierung oder Konfiguration von Microsoft Threat Protection (MTP).  </li>
<li>  Schulungen oder Anleitungen für die erweiterte Suche.  </li>
<li>  Schulungen oder Anleitungen zur Verwendung oder Erstellung von Kusto-Abfragen.</li>
</li>
</ul>
Wenden Sie sich <a href="https://go.microsoft.com/fwlink/?linkid=2080150">an einen Microsoft-Partner,</a> um Unterstützung bei diesen Diensten zu erhalten.  
</ul></td>
<td></td>

<tr class="odd">
<td><strong>Microsoft Defender for Identity </strong></td>
<td>  Microsoft Defender for Identity ist eine cloudbasierte Sicherheitslösung, die Ihre lokalen Active Directory-Signale nutzt, um fortgeschrittene Bedrohungen, gefährdete Identitäten und böswillige Insideraktionen zu identifizieren, zu erkennen und zu untersuchen, die gegen Ihre Organisation gerichtet sind. Wir bieten Remoteanleitungen für:
<ul>
<li>   Erstellen Ihrer Instanz von Defender for Identity. </li>
<li>   Herstellen einer Verbindung zwischen Defender for Identity und Active Directory. </li>
<li>   Bewerten der Bereitschaft Ihrer Umgebung zur Bereitstellung des Defender for Identity-Sensors auf Ihren Domänencontrollern, einschließlich:</li>   
<ul> 
<li>  Ausführen des Tools zur Größenanpassung für die Ressourcenkapazitätsplanung. </li>
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
<li> Optimieren der Umgebung, um "Rauschgeräusche" zu reduzieren.  </li>
<li>  Grundlegendes zum Bewertungsbericht zur Identitätssicherheitslage. </li>
<li>  Grundlegendes zum Prioritätsergebnis der Benutzeruntersuchung und des Bewertungsberichts zur Benutzeruntersuchung. </li>
<li> Grundlegendes zum Bericht des inaktiven Benutzers.  </li>
<li> Bereitstellen von Korrekturoptionen für ein gefährdetes Konto.  </li>
</ul>
<li>  Vereinfachen der Migration von Advanced Threat Analytics (ATA) zu Defender for Identity. </li>
</ul>
<p><strong>Folgendes liegt nicht im Gültigkeitsbereich</strong></p>
<ul>

<li> Projektmanagement der Problemlösungsaktivitäten des Kunden. </li>
<li> Fortlaufende Verwaltung, Bedrohungsreaktion und Problembehebung.  </li>
<li> Bereitstellen des Defender for Identity-Sensors, einschließlich: </li>
<ul>
<li> Manuelle Kapazitätsplanung. </li>
<li> Bereitstellen des Sensors in einer eigenständigen Kapazität. </li>
<li> Bereitstellen des Sensors mithilfe eines NIC(Network Interface Card)-Teamadapters. </li>
<li> Bereitstellen des Sensors über ein Drittanbietertool. </li>
<li> Herstellen einer Verbindung mit dem Defender for Identity-Clouddienst über eine Webproxyverbindung. </li>
</ul>
<li> Erstellung und Verwaltung vontokens. </li>
<li> Bereitstellungsleitfas oder Bildungseinrichtungen zu: </li>
<ul>
<li> Behebung oder Interpretation verschiedener Warnungstypen und überwachter Aktivitäten.  </li>
<li> Untersuchen eines Benutzers, Computers, lateralen Bewegungspfads oder einer Entität. </li>
<li> Bedrohung oder erweiterte Suche. </li>
<li> Reaktion auf Vorfälle. </li>
</ul>
<li> Bereitstellen eines Lernprogramms zur Sicherheitswarnungsumgebung für Defender for Identity. </li>
<li> Bereitstellen einer Benachrichtigung, wenn Defender for Identity verdächtige Aktivitäten erkennt, indem Sicherheitswarnungen über einen benannten Sensor an Ihren syslog-Server gesendet werden.  </li>
<li> Konfigurieren von Defender for Identity zum Ausführen von Abfragen mithilfe des Security Account Manager Remote (SAMR)-Protokolls, um lokale Administratoren auf bestimmten Computern zu identifizieren. </li>
<li> Konfigurieren von VPN-Lösungen, um Informationen aus der VPN-Verbindung zur Profilseite eines Benutzers hinzuzufügen.  </li>
<li> Sicherheitsinformationen und Ereignisverwaltung (SIEM) oder API-Integration (einschließlich Azure Sentinel). </li>
<li> Bereitstellen von Defender for Identity-Sensoren als Konzeptnachweis.</li>
</ul></td>
<td><ul>
<li>  Active Directory bereitgestellt.  </li>
<li>  Die Domänencontroller, auf den Sie Defender for Identity-Sensoren installieren möchten, verfügen über eine Internetverbindung zum Defender for Identity-Clouddienst.  </li>
<ul>
<li> Die Firewall und der Proxy müssen für die Kommunikation mit dem Defender for Identity Cloud Service (*.atp.azure.com Port 443 geöffnet sein).</li>
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

  <strong>Folgendes liegt nicht im Gültigkeitsbereich </strong>  
<ul>
<li> Entwicklung eines Datensatzverwaltungsdateiplans.</li>
<li> Datenconnectors.</li>
<li> Informationsbarrieren.</li>
<li> Privileged Access Management.</li>
<li> Entwicklung der Informationsarchitektur in SharePoint.</li>
<li> Benutzerdefinierte Skripterstellung und Codierung.</li>
</td>
<td>Abgesehen vom <strong>Abschnitt "Core-Onboarding"</strong> im <a href="#general">Allgemeinen</a>gibt es keine Mindestsystemanforderungen.</td>
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

<strong>Folgendes ist nicht gegenstands- </strong>  
<ul>
<li>Kundenschlüssel.</li>
<li>Entwicklung von benutzerdefinierten regulären Ausdrücken (RegEx) für Typen vertraulicher Informationen.</li>
<li>Erstellen oder Ändern von Schlüsselwortwörterbüchern.</li>
<li>Benutzerdefiniertes Skripting und Codierung.</li>
</ul>
<strong>Hinweis:</strong> Weitere Informationen finden Sie unter <strong> Azure Information Protection </strong> in Enterprise Mobility + <a href="#enterprise-mobility--security">Security</a>.
<ul>

</td>
<td>Abgesehen vom <strong>Abschnitt "Core-Onboarding"</strong> in <a href="#general">"Allgemein"</a>gibt es keine Mindestsystemanforderungen.</td>
</tr>

</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Wir bieten Remoteanleitungen für die Verwendung von Intune als cloudbasierter Anbieter für die Verwaltung mobiler Geräte (MOBILE Device Management, MDM) und Mobile App Management (MAM) für Ihre Apps und Geräte. Die genauen Schritte hängen von Ihrer Quellumgebung ab und basieren auf dem Mobilgerät und den Anforderungen an die Verwaltung mobiler Apps. Die Schritte können Folgendes umfassen:
<ul>
<li>  Lizenzierung Ihrer Endbenutzer.  </li>
<li>  Konfigurieren von Identitäten, die von Intune verwendet werden sollen, indem Sie entweder Ihr lokales Active Directory oder Cloudidentitäten (Azure AD) nutzen.  </li>
<li>  Hinzufügen von Benutzern zu Ihrem Intune-Abonnement, Definieren von IT-Administratorrollen und Erstellen von Benutzer- und Gerätegruppen.  </li>
<li>  Konfigurieren Ihrer MDM-Autorität, basierend auf Ihren Verwaltungsanforderungen, einschließlich:
<ul>
<li>  Festlegen von Intune als Ihre MDM-Berechtigung, wenn Intune Ihre einzige MDM-Lösung ist.  </li>
</ul></li>
<li>  Bereitstellen von MDM-Anleitungen für Folgendes:
<ul>
<li>  Konfiguration von Testgruppen, die zur Validierung von MDM-Verwaltungsrichtlinien verwendet werden sollen.  </li>
<li>  Konfigurieren von MDM-Verwaltungsrichtlinien und -Diensten wie:
<ul>
<li>  App-Bereitstellung für jede unterstützte Plattform über Weblinks oder Deep-Links.  </li>
<li>  Richtlinien für bedingten Zugriff.  </li>
<li>  Bereitstellung von E-Mail-, Drahtlosnetzwerken und VPN-Profilen, wenn Sie über eine vorhandene Zertifizierungsstelle, ein Drahtlosnetzwerk oder eine vpn-Infrastruktur in Ihrer Organisation verfügen.  </li>
<li>  Herstellen einer Verbindung mit dem Intune Data Warehouse.  </li>
<li>  Integration von Intune mit:
<ul>
<li>  Team Viewer für Remoteunterstützung (ein Team Viewer-Abonnement ist erforderlich).  </li>
<li>  Mobile Threat Defense (MTD)-Partnerlösungen (ein MTD-Abonnement ist erforderlich).  </li>
<li>  Eine Lösung für die Verwaltung von Telekommunikationsausgaben (ein Abonnement für eine Lösung für die Verwaltung von Telekommunikationsausgaben ist erforderlich).  </li>

</ul></li>
<li>  Registrieren von Geräten jeder unterstützten Plattform bei Intune.  </li>
</ul></li>
</ul></li>
<li>  Bereitstellen von Anleitungen zum Schutz von Apps zu:
<ul>
<li>  Konfigurieren von App-Schutzrichtlinien für jede unterstützte Plattform.  </li>
<li>  Konfigurieren von Richtlinien für bedingten Zugriff für verwaltete Apps.  </li>
<li>  Für die entsprechenden Benutzergruppen mit den zuvor erwähnten MAM-Richtlinien.  </li>
<li>  Verwenden von Verwendungsberichten für verwaltete Apps.  </li>
</ul></li>
<li>  Bereitstellen von Migrationsanleitungen von der Legacy-PC-Verwaltung zu Intune MDM.  </li>
</ul>
 
</li>
</ul>
  
<strong>Cloudanfügung</strong>  

  Wir führen Sie durch die ersten Anleitungen für die Cloud-Anfügen vorhandener Configuration Manager-Umgebungen mit Intune. Die genauen Schritte hängen von der Quellumgebung ab. Die Schritte können Folgendes umfassen:  
<ul>
<li>  Lizenzierung Ihrer Endbenutzer.  </li>
<li>  Konfigurieren von Identitäten, die von Intune verwendet werden sollen, durch Nutzung Ihres lokalen Active Directory und von Cloudidentitäten.  </li>
<li>  Hinzufügen von Benutzern zu Ihrem Intune-Abonnement, Definieren von IT-Administratorrollen und Erstellen von Benutzer- und Gerätegruppen.  </li>
<li>  Bereitstellen von Anleitungen zum Einrichten des hybriden Azure AD-Joins.  </li>
<li>  Bereitstellen von Anleitungen zum Einrichten von Azure AD für die automatische MDM-Registrierung.  </li>
<li>  Bereitstellen von Anleitungen zum Einrichten eines Cloud-Management-Gateways, wenn es als Lösung für die gleichzeitige Verwaltung der Remote-internetbasierten Geräteverwaltung verwendet wird.  </li>
<li>  Konfigurieren unterstützter Arbeitsauslastung, die Sie in Intune verschieben möchten.  </li>
<li>  Installieren des Configuration Manager-Clients auf Geräten, die bei Intune registriert sind.  </li>
</ul> 

<strong>Sicheres Bereitstellen von Outlook Mobile für iOS und Android</strong> Wir unterstützen Sie bei der sicheren Bereitstellung von Outlook Mobile für iOS und Android in Ihrer Organisation, um sicherzustellen, dass Ihre Benutzer alle erforderlichen Apps installiert haben.  
  Die Schritte zur sicheren Bereitstellung von Outlook Mobile für iOS und Android mit Intune hängen von Ihrer Quellumgebung ab. Dies kann Folgendes umfassen:
<ul>
<li>  Herunterladen der Outlook für iOS- und Android-, Microsoft Authenticator- und Intune-Unternehmensportal-Apps über den Apple App Store oder Google Play Store.  </li>
<li>  Bereitstellen von Anleitungen zum Einrichten:
<ul>
<li>  Die Outlook für iOS- und Android-, Microsoft Authenticator- und Intune-Unternehmensportal-Apps-Bereitstellung mit Intune.  </li>
<li>  App-Schutzrichtlinien.  </li>
<li>  Richtlinien für bedingten Zugriff.  </li>
<li>  App-Konfigurationsrichtlinien.  </li>
</ul></li>
</ul>  
  </td>
<td>  IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.  
  <strong>Hinweis:</strong>Der FastTrack-Dienstvorteil umfasst keine Unterstützung beim Einrichten oder Konfigurieren von Zertifizierungsstelle, Drahtlosnetzwerken, VPN-Infrastrukturen oder Apple MDM-Pushzertifikaten für Intune.  
 
  <strong>Hinweis</strong>: Der FastTrack-Servicevorteil beinhaltet keine Unterstützung bei der Einrichtung oder Aktualisierung des Configuration Manager-Standortservers oder des Configuration Manager-Clients auf die Mindestanforderungen, die zur Unterstützung der Cloudanfügung erforderlich sind. Wenden Sie sich <a href="https://go.microsoft.com/fwlink/?linkid=2080150">an einen Microsoft-Partner,</a> um Unterstützung zu erhalten.

  <strong>Integration von Intune in Microsoft Defender Advanced Threat Protection (ATP)</strong> 
 
  <strong>Hinweis:</strong>Wir bieten Unterstützung bei der Integration von Intune in Microsoft Defender ATP und der Erstellung von Richtlinien zur Gerätekonformität basierend auf der Risikobewertung von Windows 10. Wir bieten keine Unterstützung beim Kauf, bei der Lizenzierung oder bei der Aktivierung. Wenden Sie sich <a href="https://go.microsoft.com/fwlink/?linkid=2080150">an einen Microsoft-Partner,</a> um Unterstützung zu erhalten.  
  
<strong>Windows Autopilot</strong> 
 
  IT-Administratoren sind für die Registrierung ihrer Geräte in ihrer Organisation verantwortlich, indem sie entweder den Hardware-Anbieter ihre Hardware-IDs in ihrem Namen hochladen lassen oder sie selbst in den Windows-Autopilot-Dienst hochladen.  
  
</td>
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
<td>Abgesehen vom <strong>Abschnitt "Core-Onboarding"</strong> in <a href="#general">"Allgemein"</a>gibt es keine Mindestsystemanforderungen.</td>
</tr>
</tbody>
</table>

## <a name="office-365"></a>Office 365

<<table>
<thead>
<tr class="header">
<th><strong>Dienst</strong></th>
<th><strong>Details zur FastTrack-Anleitung</strong></th>
<th><strong>Erwartungen an die Quellumgebung</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange Online</strong></td>
<td>  Für Exchange Online führen wir Sie durch den Prozess, um Ihre Organisation für die Verwendung von E-Mails zu bereiten. Die genauen Schritte hängen von Ihrer Quellumgebung und Ihren E-Mail-Migrationsplänen ab.  
  Wir bieten Remoteanleitungen für:
<ul>
<li>  Einrichten von Exchange Online Protection (EOP)-Funktionen für alle E-Mail-aktivierten Domänen, die in Office 365 überprüft wurden.  </li>
<li>  Verweisen Ihrer E-Mail-Exchange-Einträge (MX)-Einträge auf Office 365.  </li>
<li>  Einrichten des Office 365 ATP-Features, wenn es Teil Ihres Abonnementdiensts ist. Weitere Informationen finden Sie im <strong>Abschnitt zu Office 365 Advanced Threat Protection</strong> in dieser Tabelle.  </li>
<li>  Einrichten der Verhinderung von Datenverlust (Data Loss Prevention, DLP) für alle E-Mail-aktivierten Domänen, die in Office 365 als Teil Ihres Abonnementdiensts validiert wurden. Dies geschieht, sobald Ihre MX-Einträge auf Office 365 verweisen.</li>
<li>  Einrichten der Office 365-Nachrichtenverschlüsselung (OME) für alle E-Mail-aktivierten Domänen, die in Office 365 als Teil Ihres Abonnementdiensts validiert wurden. Dies geschieht, sobald Ihre MX-Einträge auf Office 365 verweisen.</li>
</ul>
  <strong>Hinweis:</strong> Der Postfachreplikationsdienst versucht, E-Mails mit verwalteten Informationsrechten (Information Rights Managed, IRM) von Ihrem lokalen Postfach in das entsprechende Exchange Online-Postfach zu migrieren. Die Möglichkeit, die geschützten Inhalte nach der Migration zu lesen, hängt von der Kundenzuordnung und dem Kopieren von AD RMS-Vorlagen (Active Directory Rights Managed Services) zum Azure RMS-Dienst (Azure Rights Management) ab.  
<ul>
<li>  Konfigurieren von Firewallports.  </li>
<li>  Einrichten von DNS, einschließlich der erforderlichen AutoErmittlung, des Sender Policy Frameworks (SPF), domainKeys Identified Mail (DKIM), der domänenbasierten Nachrichtenauthentifizierung, der Berichterstellung und Konformität (DMARC) und der MX-Einträge (nach Bedarf).  </li>
<li>  Einrichten des E-Mail-Nachrichtenflusses zwischen Ihrer Quellmessagingumgebung und Exchange Online (bei Bedarf)  </li>
<li>  Durchführen der E-Mail-Migration von Ihrer Quellmessagingumgebung zu Office 365.  </li>
<li>  Konfigurieren von Postfach-Clients (Outlook für Windows, Outlook im Web und Outlook für iOS und Android).  </li>
</ul>
  <strong>Datenmigration</strong>  <br>
Informationen zur Verwendung des FastTrack-Vorteils für die Datenmigration zu Office 365 finden Sie unter <a href="https://docs.microsoft.com/fasttrack/data-migration">Datenmigration</a>.   
<td>  Ihre Quellumgebung muss eine der folgenden Mindeststufen haben:
<ul>
<li>  Einzelne oder mehrere Exchange-Organisationen mit Exchange Server 2003 oder höher.  </li>
<li>  Einzelne IMAP-fähige E-Mail-Umgebung.  </li>
<li>  Eine einzelne G Suite-Umgebung (nur Gmail, Kontakte und Kalender).  </li>
<li>  Informationen zu Multi-Geo-Funktionen finden Sie unter <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo-Funktionen in Exchange Online.</a>  </li>
</ul>
Onlineclientsoftware wie Project für Office 365, Outlook für Windows, Outlook für iOS und Android, OneDrive for Business-Synchronisierungsclient, Power BI Desktop und Skype for Business muss auf einer Mindeststufe wie in den Systemanforderungen für <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office</a>definiert sein.  </td>
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

  <strong>Folgendes ist nicht gegenstands- </strong>  
<ul>
<li> Entwicklung eines Datensatzverwaltungsdateiplans.</li>
<li> Datenconnectors.</li>
<li> Informationsbarrieren.</li>
<li> Privileged Access Management.</li>
<li> Entwicklung der Informationsarchitektur in SharePoint.</li>
<li> Benutzerdefinierte Skripterstellung und Codierung.</li>
</td>
<td>Abgesehen vom <strong>Abschnitt "Core-Onboarding"</strong> im <a href="#general">Allgemeinen</a>gibt es keine Mindestsystemanforderungen.</td>
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

<strong>Folgendes liegt nicht im Gültigkeitsbereich </strong>  
<ul>
<li>Kundenschlüssel.</li>
<li>Entwicklung von benutzerdefinierten regulären Ausdrücken (RegEx) für Typen vertraulicher Informationen.</li>
<li>Erstellen oder Ändern von Schlüsselwortwörterbüchern.</li>
<li>Benutzerdefinierte Skripterstellung und Codierung.</li>
</ul>
<strong>Hinweis:</strong> Weitere Informationen finden Sie unter <strong> Azure Information Protection </strong> in Enterprise Mobility + <a href="#enterprise-mobility--security">Security</a>.
<ul>

</td>
<td>Abgesehen vom <strong>Abschnitt "Core-Onboarding"</strong> im <a href="#general">Allgemeinen</a>gibt es keine Mindestsystemanforderungen.</td>
</tr>
<tr class="even">
<td><strong>Microsoft Teams</strong></td>
<td>  Wir bieten Remoteanleitungen für:
<ul>
<li>  Bestätigen der Mindestanforderungen in Exchange Online, SharePoint Online, Office 365-Gruppen und Azure AD zur Unterstützung von Teams.  </li>
<li>  Konfigurieren von Firewallports.  </li>
<li>  Einrichten von DNS  </li>
<li>  Sicherstellen, dass Teams auf Ihrem Office 365-Mandanten aktiviert ist  </li>
<li>  Aktivieren oder Deaktivieren von Benutzerlizenzen  </li>
<li>  Netzwerkbewertung für Teams:
<ul>
<li>  Überprüfungen hinsichtlich der Ports und Endpunkte  </li>
<li>  Überprüfungen hinsichtlich der Verbindungsqualität  </li>
<li>  Schätzungen hinsichtlich der Bandbreite  </li>
</ul>
<ul>
<li>  Konfigurieren der Teams-App-Richtlinie (Teams-Web-App, Teams-Desktop-App und Teams für iOS- und Android-App).  </li>
</ul>
Gegebenenfalls bieten wir auch Anleitungen für:
<ul>
<li>  Microsoft Teams-Raumgeräte:  </li>
<ul>
<li>  Erstellung von Online-Konten, die für unterstützte Telefonie- und Konferenzraumgeräte benötigt werden, die im <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Katalog der Teams-Geräte</a> aufgeführt sind.  </li>
<li>  Remoteunterstützung bei der dienstseitigen Konfiguration zertifizierter Microsoft Teams Rooms-Geräte.  </li>
<li>  Aktivieren von Audiokonferenzen:  </li>
<li>  Organisationseinrichtung der Standardeinstellungen für Konferenzbrücke  </li>
<li>  Zuweisen der Konferenzbrücke zu lizenzierten Benutzern  </li>
</ul>
<li>  Telefonsystem:
<ul>
<li>  Organisationseinrichtung der Standardeinstellungen für Cloud Voice  </li>
<li>  Leitfaden für Anrufpläne (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">verfügbare Märkte</a>):
<ul>
<li>  Zuweisung von Nummern zu lizenzierten Benutzern  </li>
<li>  Anweisung zum Portieren lokaler Rufnummern über die Benutzeroberfläche bis 999  </li>
<li>  SR-Unterstützung für das Portieren von lokalen Nummern über 999 hinaus  </li>
</ul></li>
<li>  Anleitung für direktes Routing:
<ul>
<li>  Organisationseinrichtungsanleitung für das direkte Routing von vom Partner gehosteten Szenarien oder vom Kunden bereitgestellten Szenarien für bis zu 10 Standorte.  </li>
<li> SBC (Session Border Controller) – Konfigurationsüberprüfung. </li>

<li> Remoteunterstützung bei der Konfiguration von Wähleinstellungen. </li>

<li> Konfiguration der Voiceroute.</li>

<li> Medienumgehung und lokale Medienoptimierung. </li>

</ul></li>
</ul></li>
<li>  Aktivieren von Teams-Liveereignissen  </li>
<li>  Einrichten der Organisation und Integration in Microsoft Stream.  </li>
<li>  Anleitung für den Übergang von Skype for Business zu Teams.  </li>
</ul></td>
<td><ul>
<li>  Identitäten, die in Azure AD für Office 365 aktiviert sind.  </li>
<li>  Aktivierte Benutzer für SharePoint Online.  </li>
<li>  Exchange-Postfächer sind vorhanden (online und lokal in einer Exchange-Hybridkonfiguration).  </li>
<li>  Für Office 365-Gruppen aktiviert.  </li>
</ul>
  <strong>Hinweis:</strong> Wenn Benutzern keine SharePoint #A0 zugewiesen und aktiviert sind, verfügen sie nicht über OneDrive for #A1 in Office 365. Die Dateifreigabe funktioniert weiterhin in Kanälen, aber Benutzer können Dateien in Chats ohne OneDrive for #A0 in Office 365 nicht freigeben. Teams unterstützt SharePoint lokal nicht.  <br>
  <strong>Hinweis:</strong> Der ideale Zustand ist, dass alle Benutzer ihre Postfächer in Exchange Online gespeichert haben. Benutzer mit lokalen Postfächern müssen ihre Identitäten über Azure AD Connect mit dem Office 365-Verzeichnis synchronisieren. Für diese Exchange-Hybrid-Kunden kann der Benutzer keine Connectors hinzufügen oder konfigurieren, wenn das Postfach des Benutzers lokal ist.  
  Die Installationsprogramme für die Windows- und Mac-Desktop-Clients von Microsoft Teams können unter <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> heruntergeladen werden.  </td>
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
<td>Abgesehen vom <strong>Abschnitt "Core-Onboarding"</strong> im <a href="#general">Allgemeinen</a>gibt es keine Mindestsystemanforderungen.</td>
</tr>
<tr class="even">
<td><strong>Outlook für iOS und Android</strong></td>
<td>  Wir bieten Remoteanleitungen für:
<ul>
<li>  Herunterladen von Outlook für iOS und Android über den Apple App Store und Google Play  </li>
<li>  Konfigurieren von Konten und Zugreifen auf das Exchange Online-Postfach  </li>
<li>  Sichern von Outlook Mobile (weitere Informationen finden Sie unter <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Sichern von Outlook für iOS und Android in Exchange Online).</a>  </li>
</ul></td>
<td><ul>
<li>  Identitäten, die in Azure AD für Office 365 aktiviert sind.  </li>
<li>  Exchange Online konfiguriert und Lizenzen zugewiesen.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Power BI</strong></td>
<td>  Wir bieten Remoteanleitungen für:
<ul>
<li>  Zuweisen von Power BI-Lizenzen.  </li>
<li>  Bereitstellen der Power BI Desktop-App.  </li>
</ul></td>
<td>Onlineclientsoftware wie Power BI Desktop muss auf einer Mindeststufe wie in den Systemanforderungen für <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365</a>und Office definiert sein.</td>
</tr>
<tr class="even">
<td><strong>Project Online</strong></td>
<td>  Wir bieten Remoteanleitungen für:
<ul>
<li>  Überprüfen grundlegender SharePoint-Funktionen, auf denen Project Online basiert.  </li>
<li>  Hinzufügen des Project Online-Diensts zu Ihrem Mandanten (einschließlich des Hinzufügens von Abonnements zu Benutzern).  </li>
<li>  Einrichten des Enterprise-Ressourcenpools (ERP)  </li>
<li>  Erstellen Ihres ersten Projekts.  </li>
</ul></td>
<td>Onlineclientsoftware wie Project für Office 365 muss auf einer Mindeststufe wie in den Systemanforderungen für <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365</a>und Office definiert sein.</td>
</tr>
<tr class="odd">
<td><strong>Project Online Professional und Premium</strong></td>
<td>  Wir bieten Remoteanleitungen für:
<ul>
<li>  Beheben von Problemen bei der Bereitstellung  </li>
<li>  Zuweisen von Endbenutzerlizenzen mit Microsoft 365 Admin Center und Windows PowerShell  </li>
<li>  Installieren von Project Online-Desktopclient aus dem Office 365-Portal mithilfe von Klick-und-Los  </li>
<li>  Konfigurieren von Updateeinstellungen mit dem Office 365-Bereitstellungstool  </li>
<li>  Einrichten eines einzelnen lokalen Verteilungsservers für Project Online-Desktopclient, einschließlich Unterstützung beim Erstellen einer configuration.xml-Datei für die Verwendung mit dem Office 365-Bereitstellungstool  </li>
<li>  Herstellen einer Verbindung zwischen Project Online-Desktopclient und Project Online Professional oder Project Online Premium.  </li>
</ul></td>
<td>Onlineclientsoftware wie Project für Office 365 muss auf einer Mindeststufe wie in den Systemanforderungen für <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365</a>und Office definiert sein.</td>
</tr>
<tr class="even">
<td><strong>SharePoint Online und OneDrive for Business</strong></td>
<td>  Wir bieten Remoteanleitungen für:
<ul>
<li>  Einrichten von DNS  </li>
<li>  Konfigurieren von Firewallports.  </li>
<li>  Bereitstellen von Benutzern und Lizenzen.  </li>
<li>Aktivieren der Websiteerstellung für Ihren SharePoint Online-Administrator.</li>
<li>Planen von Websitesammlungen.</li>
<li>Sichern von Inhalten und Verwalten von Berechtigungen.</li>
<li>Konfigurieren von SharePoint Online-Features.</li>
<li>  Konfigurieren von SharePoint-Hybridfeatures, z. B. Hybridsuche, Hybridwebsites, Hybridtaxonomie, Inhaltstypen, Self-Service Site Creation für hybride Sites (nur SharePoint Server 2013), erweitertes App-Startfeld, Hybrid-OneDrive for Business und Extranet-Websites.  </li>
<li>  Ihr Migrationsansatz.  </li>
</ul>
In Abhängigkeit von Ihrer #A0 werden zusätzliche Anleitungen für OneDrive for Business bereitgestellt, beispielsweise:
<ul>
<li>  Identifizieren von Integrationsoptionen und Überprüfen der lokalen und Onlinenetzwerkinfrastruktur und -bandbreite.  </li>
<li>  Installieren von SharePoint Online 2013 SP1 (falls zutreffend), Planen und Implementieren von Synchronisierungs- und Identitätsanforderungen und Identifizieren Ihres OneDrive for Business-Synchronisierungsclients.  </li>
<li>  Planen und Implementieren eines einzelnen Rollouts für alle Benutzer (oder ein phasenweises Rollout).  </li>
<li>  Zuweisen von Lizenzen, Umleiten von Meine Websites und persönlichen Dokumentbibliotheken zu Office 365 (gilt für SharePoint Online 2013), Einrichten von Zielgruppen zur Steuerung des Zugriffs auf OneDrive (gilt für SharePoint Online 2013).  </li>
<li>Umleiten oder Verschieben bekannter Ordner zu OneDrive.</li>
<li>  Bereitstellen der OneDrive for Business-Clientsynchronisierung.  </li>
</ul>
  <strong>Datenmigration</strong>  <br>
Informationen zur Verwendung des FastTrack-Vorteils für die Datenmigration zu Office 365 finden Sie unter <a href="https://docs.microsoft.com/fasttrack/data-migration">Datenmigration</a>.
</ul></td>
<td><br><strong>Für SharePoint Hybrid:</strong>  
<ul>
<li>  Die #A0 umfasst die Konfiguration der Hybridsuche, Websites, Taxonomie, Inhaltstypen, OneDrive for Business, eines erweiterten App-Startfelds, Extranetwebsites und #A1 Site Creation, die von einer lokalen mit einer SharePoint #A2 verbunden sind.  </li>
</ul>
  <strong>Hinweis:</strong> Die Self-Service-Websiteerstellung ist nicht auf lokalen Servern mit SharePoint 2013 verfügbar.  
<ul>
<li>  Um die Hybridbereitstellung von SharePoint zu aktivieren, benötigen Sie eine der folgenden lokalen SharePoint Server-Umgebungen: 2013, 2016 oder 2019.  </li>
</ul>
  <strong>Hinweis:</strong> Das Upgrade von lokalen SharePoint-Umgebungen auf SharePoint Server ist nicht gegenstandsgef?hn. Wenden Sie sich <a href="https://go.microsoft.com/fwlink/?linkid=2080150">an einen Microsoft-Partner,</a> um Unterstützung zu erhalten. Weitere Informationen finden Sie unter <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimale öffentliche Updateebenen für SharePoint-Hybridfeatures.</a><em></em>  <br>
  <strong>Hinweis:</strong> Informationen zu Multi-Geo-Funktionen finden Sie unter <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo-Funktionen in OneDrive und SharePoint Online in Office 365.</a><em></em>  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td><ul>
Wir bieten Remoteanleitungen zum Aktivieren des Yammer Enterprise-Diensts.  
</ul></td>
<td>Die Onlineclientsoftware muss auf einer Mindeststufe wie in den Systemanforderungen für <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365</a>und Office definiert sein.</td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>Enterprise Mobility + Security

<table>
<thead>
<tr class="header">
<th><strong>Dienst</strong></th>
<th><strong>Details zur FastTrack-Anleitung</strong></th>
<th><strong>Erwartungen an die Quellumgebung</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Azure Active Directory (Azure AD) und Azure AD Premium</strong></td>
<td>  Wir bieten Remoteanleitungen zum Sichern Ihrer Cloudidentitäten für die folgenden Szenarien.  

 <br/>

<strong>Sichere Foundation-Infrastruktur</strong>  </ul>
<ul>
<li>  Konfigurieren und Aktivieren einer starken Authentifizierung für Ihre Identitäten, einschließlich des Schützens mit Azure Multi-Factor Authentication (MFA) (nur Cloud), der Microsoft Authenticator-App und der kombinierten Registrierung für Azure MFA und Self-Service-Kennwortzurücksetzung (Self-Service Password Reset, SSPR).  </li>
<li>  Für Nicht-Azure AD Premium-Kunden wird eine Anleitung bereitgestellt, um Ihre Identitäten mithilfe von Sicherheitseinstellungen zu schützen.  </li>
<li>  Für Azure AD Premium-Kunden wird eine Anleitung bereitgestellt, um Ihre Identitäten mit bedingten Zugriff zu schützen.  </li>
<li>  Erkennen und Blockieren der Verwendung von schwachen Kennwörtern mit Azure AD Password Protection.  </li>
<li>  Schützen des Remotezugriffs auf lokale Web-Apps mit dem Azure AD-Anwendungsproxy.  </li>
<li>  Aktivieren der risikobasierten Erkennung und Behebung mit Azure Identity Protection.  </li>
<li>  Aktivieren eines angepassten Anmeldebildschirms, einschließlich Logo, Text und Bildern mit benutzerdefiniertem Branding.  </li>
<li>  Sicheres Freigeben von Apps und Diensten für Gastbenutzer mit Azure AD B2B.  </li>
<li>  Verwalten des Zugriffs für Ihre Office 365-Administratoren mithilfe von integrierten Administratorrollen der rollenbasierten Zugriffssteuerung (Role-Based Access Control, RBAC) und Verringern der Anzahl privilegierter Administratorkonten.  </li>
<li>  Konfigurieren der Azure AD-Hybrid-Verknüpfung.  </li>
<li>  Konfigurieren der Azure AD-Verknüpfung.  </li>
</ul>
  
<strong>Überwachen und Melden</strong>  
<ul>
<li>  
  Aktivieren der Remoteüberwachung für AD FS, Azure AD Connect und Domänencontroller mit Azure AD Connect Health.  
  </li>
</ul>
  
<strong>Governance</strong>  
<ul>
<li>  
  Verwalten Ihrer Azure AD-Identität und ihres Zugriffslebenszyklus im großen Maßstab mit Azure AD-Berechtigungsverwaltung.
  </li>
<li>  
  Verwalten von Azure AD-Gruppenmitgliedschaften, Enterprise-App-Zugriff und Rollenzuweisungen mit Azure AD-Zugriffsüberprüfungen.  
  </li>
<li>  
  Überprüfen der Azure AD-Nutzungsbedingungen.  
  </li>
<li>  
  Verwalten und Steuern des Zugriffs auf privilegierte Administratorkonten mit Azure AD Privileged Identity Management.  
  </li>
</ul>
  
<strong>Automatisierung und Effizienz </strong>  
<ul>
<li>  
  Aktivieren von Azure AD SSPR.  
  </li>
<li>  Zulassen, dass Benutzer ihre eigenen Cloudsicherheits- oder Office 365-Gruppen mit Azure AD Self-Service-Gruppenverwaltung erstellen und verwalten können.  </li>
<li>  Verwalten des delegierten Zugriffs auf Unternehmens-Apps mit delegierter Azure AD-Gruppenverwaltung.  </li>
<li>  Aktivieren dynamischer Azure AD-Gruppen.  </li>
<li>  Organisieren von Apps im Meine Apps-Portal mithilfe von Sammlungen.  </li>
</ul></td>
<td>Das lokale Active Directory und seine Umgebung wurden für Azure AD Premium vorbereitet, einschließlich der Behebung identifizierter Probleme, die die Integration in Azure AD- und Azure AD -Premium-Features verhindern.</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection </strong></td>
<td>  Wir bieten Remoteanleitungen für:
<ul>
<li>  Aktivieren und Konfigurieren Ihres Mandanten.  </li>
<li>  Erstellen und Einrichten von Bezeichnung und Richtlinien.  </li>
<li>  Anwendung von Informationsschutz auf Dokumente.  </li>
<li>  Automatische Klassifizierung und Bezeichnung von Informationen in Office-Anwendungen (wie Word, PowerPoint, Excel und Outlook), die unter Windows ausgeführt werden und den Azure Information Protection Client verwenden.  </li>
<li>  Ermitteln und Beschriften von Dateien im Ruheschutz mithilfe des Azure Information Protection-Scanners.  </li>
<li>  Überwachung von E-Mails während des Versands unter Verwendung von Exchange Online Nachrichtenflussregeln.  </li>
</ul>
Wir bieten auch Anleitungen, wenn Sie Schutz mit Microsoft Azure Rights Management Services (Azure RMS), Office 365-Nachrichtenverschlüsselung (OME) und Verhinderung von Datenverlust (Data Loss Prevention, DLP) anwenden möchten.  </td>
<td>  Zu den verantwortlichen Zuständigkeiten des Kunden gehören:
<ul>
<li>  Eine Liste der zu scannende Speicherorte für Dateifreigaben.  </li>
<li>  Eine genehmigte Klassifizierungstaxonomie. </li>
<li> Grundlegendes zu behördlichen Einschränkungen oder Anforderungen in Bezug auf die Schlüsselverwaltung.  </li>
<li>  Ein Dienstkonto, das für Ihr lokales Active Directory erstellt wurde, das mit Azure AD synchronisiert wurde. </li>
<li>  Bezeichnungen, die für Klassifizierung und Schutz konfiguriert sind. </li>
<li> Alle Voraussetzungen für den Azure Information Protection-Scanner sind erfüllt. Weitere Informationen finden Sie unter "Voraussetzungen für die Installation und Bereitstellung des <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Azure Information Protection-Scanners für einheitliche Bezeichnungen".</a> </li>
<li>  Stellen Sie sicher, dass auf Den Benutzergeräten ein unterstütztes Betriebssystem ausgeführt wird und die erforderlichen Komponenten installiert sind. Weitere Informationen finden Sie im Folgenden.</li>
<ul>
<li> <a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Administratorhandbuch: Installieren des Azure Information Protection einheitlichen Bezeichnungsclients für Benutzer</a>   </li>
<li>  <a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">Was ist die Azure Information Protection-App für iOS oder Android?</a>  </li>
</ul>
<li> Installation und Konfiguration des Azure RMS-Connectors und der Server, einschließlich des Active Directory RMS (AD RMS)-Connectors für die Hybridunterstützung.  </li>
<li> Setup und Konfiguration von Bring Your Own Key (BYOK), Double Key Encryption (DKE) (nur Client mit einheitlichen Bezeichnungen) oder Halten eines eigenen Schlüssels (nur klassischer Client), falls Sie eine dieser Optionen für Ihre Bereitstellung benötigen.  </li>
  </ul>
</ul>
  
</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Wir bieten Remoteanleitungen für die Verwendung von Intune als cloudbasierter Anbieter für die Verwaltung mobiler Geräte (MOBILE Device Management, MDM) und Mobile App Management (MAM) für Ihre Apps und Geräte. Die genauen Schritte hängen von Ihrer Quellumgebung ab und basieren auf dem Mobilgerät und den Anforderungen an die Verwaltung mobiler Apps. Die Schritte können Folgendes umfassen:
<ul>
<li>  Lizenzierung Ihrer Endbenutzer.  </li>
<li>  Konfigurieren von Identitäten, die von Intune verwendet werden sollen, indem Sie entweder Ihr lokales Active Directory oder Cloudidentitäten (Azure AD) nutzen.  </li>
<li>  Hinzufügen von Benutzern zu Ihrem Intune-Abonnement, Definieren von IT-Administratorrollen und Erstellen von Benutzer- und Gerätegruppen.  </li>
<li>  Konfigurieren Ihrer MDM-Autorität, basierend auf Ihren Verwaltungsanforderungen, einschließlich:
<ul>
<li>  Festlegen von Intune als Ihre MDM-Berechtigung, wenn Intune Ihre einzige MDM-Lösung ist.  </li>
</ul></li>
<li>  Bereitstellen von MDM-Anleitungen für Folgendes:
<ul>
<li>  Konfiguration von Testgruppen, die zur Validierung von MDM-Verwaltungsrichtlinien verwendet werden sollen.  </li>
<li>  Konfigurieren von MDM-Verwaltungsrichtlinien und -Diensten wie:
<ul>
<li>  App-Bereitstellung für jede unterstützte Plattform über Weblinks oder Deep-Links.  </li>
<li>  Richtlinien für bedingten Zugriff.  </li>
<li>  Bereitstellung von E-Mail-, Drahtlosnetzwerken und VPN-Profilen, wenn Sie über eine vorhandene Zertifizierungsstelle, ein Drahtlosnetzwerk oder eine vpn-Infrastruktur in Ihrer Organisation verfügen.  </li>
<li>  Herstellen einer Verbindung mit dem Intune Data Warehouse.  </li>
<li>  Integration von Intune mit:
<ul>
<li>  Team Viewer für Remoteunterstützung (ein Team Viewer-Abonnement ist erforderlich).  </li>
<li>  Mobile Threat Defense (MTD)-Partnerlösungen (ein MTD-Abonnement ist erforderlich).  </li>
<li>  Eine Lösung für die Verwaltung von Telekommunikationsausgaben (ein Abonnement für eine Lösung für die Verwaltung von Telekommunikationsausgaben ist erforderlich).  </li>
</ul></li>
<li>  Registrieren von Geräten jeder unterstützten Plattform bei Intune.  </li>
</ul></li>
</ul></li>
<li>  Bereitstellen von Anleitungen zum Schutz von Apps zu:
<ul>
<li>  Konfigurieren von App-Schutzrichtlinien für jede unterstützte Plattform.  </li>
<li>  Konfigurieren von Richtlinien für bedingten Zugriff für verwaltete Apps.  </li>
<li>  Für die entsprechenden Benutzergruppen mit den zuvor erwähnten MAM-Richtlinien.  </li>
<li>  Verwenden von Verwendungsberichten für verwaltete Apps.  </li>
</ul></li>
<li>  Bereitstellen von Migrationsanleitungen von der Legacy-PC-Verwaltung zu Intune MDM.  </li>
</ul>
  
</li>
</ul>
  
<strong>Cloudanfügung</strong>  

  Wir führen Sie durch die ersten Anleitungen für die Cloud-Anfügen vorhandener Configuration Manager-Umgebungen mit Intune. Die genauen Schritte hängen von der Quellumgebung ab. Die Schritte können Folgendes umfassen:  
<ul>
<li>  Lizenzierung Ihrer Endbenutzer.  </li>
<li>  Konfigurieren von Identitäten, die von Intune verwendet werden sollen, durch Nutzung Ihres lokalen Active Directory und von Cloudidentitäten.  </li>
<li>  Hinzufügen von Benutzern zu Ihrem Intune-Abonnement, Definieren von IT-Administratorrollen und Erstellen von Benutzer- und Gerätegruppen.  </li>
<li>  Bereitstellen von Anleitungen zum Einrichten des hybriden Azure AD-Joins.  </li>
<li>  Bereitstellen von Anleitungen zum Einrichten von Azure AD für die automatische MDM-Registrierung.  </li>
<li>  Bereitstellen von Anleitungen zum Einrichten eines Cloud-Management-Gateways, wenn es als Lösung für die gleichzeitige Verwaltung der remote internetbasierten Geräteverwaltung verwendet wird.  </li>
<li>  Konfigurieren unterstützter Arbeitsauslastung, die Sie in Intune verschieben möchten.  </li>
<li>  Installieren des Configuration Manager-Clients auf Geräten, die bei Intune registriert sind.  </li>
</ul> 

<strong>Sicheres Bereitstellen von Outlook Mobile für iOS und Android</strong> Wir unterstützen Sie bei der sicheren Bereitstellung von Outlook Mobile für iOS und Android in Ihrer Organisation, um sicherzustellen, dass Ihre Benutzer alle erforderlichen Apps installiert haben.  
  Die Schritte zur sicheren Bereitstellung von Outlook Mobile für iOS und Android mit Intune hängen von Ihrer Quellumgebung ab. Dies kann Folgendes umfassen:
<ul>
<li>  Herunterladen der Outlook für iOS- und Android-, Microsoft Authenticator- und Intune-Unternehmensportal-Apps über den Apple App Store oder Google Play Store.  </li>
<li>  Bereitstellen von Anleitungen zum Einrichten:
<ul>
<li>  Die Outlook für iOS- und Android-, Microsoft Authenticator- und Intune-Unternehmensportal-Apps-Bereitstellung mit Intune.  </li>
<li>  App-Schutzrichtlinien.  </li>
<li>  Richtlinien für bedingten Zugriff.  </li>
<li>  App-Konfigurationsrichtlinien.  </li>
</ul></li>
</ul>  
  </td>
<td>  IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.  
  <strong>Hinweis:</strong>Der FastTrack-Dienstvorteil umfasst keine Unterstützung beim Einrichten oder Konfigurieren von Zertifizierungsstelle, Drahtlosnetzwerken, VPN-Infrastrukturen oder Apple MDM-Pushzertifikaten für Intune.  
 
  <strong>Hinweis</strong>: Der FastTrack-Servicevorteil beinhaltet keine Unterstützung bei der Einrichtung oder Aktualisierung des Configuration Manager-Standortservers oder des Configuration Manager-Clients auf die Mindestanforderungen, die zur Unterstützung der Cloudanfügung erforderlich sind. Wenden Sie sich <a href="https://go.microsoft.com/fwlink/?linkid=2080150">an einen Microsoft-Partner,</a> um Unterstützung zu erhalten.

  <strong>Integration von Intune in Microsoft Defender Advanced Threat Protection (ATP)</strong> 
 
  <strong>Hinweis:</strong>Wir bieten Unterstützung bei der Integration von Intune in Microsoft Defender ATP und der Erstellung von Richtlinien zur Gerätekonformität basierend auf der Risikobewertung von Windows 10. Wir bieten keine Unterstützung beim Kauf, bei der Lizenzierung oder bei der Aktivierung. Wenden Sie sich <a href="https://go.microsoft.com/fwlink/?linkid=2080150">an einen Microsoft-Partner,</a> um Unterstützung zu erhalten.  
  
<strong>Windows Autopilot</strong> 
 
  IT-Administratoren sind für die Registrierung ihrer Geräte in ihrer Organisation verantwortlich, indem sie entweder den Hardware-Anbieter ihre Hardware-IDs in ihrem Namen hochladen lassen oder sie selbst in den Windows-Autopilot-Dienst hochladen.  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a>Windows 10

<table>
<thead>
<tr class="header">
<th><strong>Dienst</strong></th>
<th><strong>Details zur FastTrack-Anleitung</strong></th>
<th><strong>Erwartungen an die Quellumgebung</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows 10</strong></td>
<td>  Wir bieten Anleitungen für das Upgrade von Windows 7 Professional und Windows 8.1 Professional auf Windows 10 Enterprise.  
  Wir bieten Remoteanleitungen für:
<ul>
<li>  Grundlegendes zu Ihrer Windows 10-Absicht.  </li>
<li>  Bewerten der Quellumgebung und der Anforderungen (stellen Sie sicher, dass Microsoft Endpoint Configuration Manager auf die erforderliche Stufe aktualisiert wurde, um die Windows 10-Bereitstellung zu unterstützen).  </li>
<li>  Bereitstellen von Windows 10 Enterprise- und Microsoft 365-Apps mit Microsoft Endpoint Configuration Manager oder Microsoft 365.  </li>
<li>  Empfehlen von Optionen für die Bewertung Ihrer Windows 10-Apps.  </li>
<li>  Ermöglichen der Verwendung von Desktop Analytics und Anleitungen durch die Erstellung eines Desktop Analytics-Bereitstellungsplans.  </li>
<li>  Bewertung der Kompatibilität von Microsoft 365-Apps durch Nutzung des Office 365-Bereitschaftsdashboards in Configuration Manager oder mit dem eigenständigen Readiness Toolkit für Office sowie Unterstützung bei der Bereitstellung von Microsoft 365-Apps.  </li>
<li>  Erstellen einer Prüfliste für Die Korrekturen, was Sie tun müssen, um Ihre Quellumgebung auf die Mindestanforderungen für eine erfolgreiche Bereitstellung zu bringen.  </li>
<li>  Bereitstellen von Upgradeanleitungen für Ihre vorhandenen Geräte auf Windows 10 Enterprise, wenn diese die erforderlichen Gerätehardwareanforderungen erfüllen.  </li>
<li>  Bereitstellen von Upgradeanleitungen zur Unterstützung ihrer vorhandenen Bereitstellungsbewegung. FastTrack bietet Empfehlungen und Anleitungen für ein direktes Upgrade auf Windows 10. Anleitungen stehen auch für eine Windows-Clean Image-Installation und Windows Autopilot-Bereitstellungsszenarien zur Verfügung.  </li>
<li>  Bereitstellen von Microsoft 365-Apps mithilfe von Configuration Manager als Teil der Windows 10-Bereitstellung.   </li>
<li>  Bereitstellen von Anleitungen, mit deren Hilfe Ihre Organisation mit Windows 10 Enterprise und Microsoft 365-Apps mithilfe Ihrer vorhandenen Configuration Manager-Umgebung oder Microsoft 365 auf dem neuesten Stand bleiben kann.  </li>
</ul>
  <strong>Folgendes liegt nicht im Gültigkeitsbereich </strong>  
<ul>
<li>  Upgrade von Configuration Manager auf den Current Branch.  </li>
<li>  Erstellen von benutzerdefinierten Images für die Bereitstellung von Windows 10.  </li>
<li>  Erstellen und Unterstützen von Bereitstellungsskripts für die Bereitstellung von Windows 10.  </li>
<li>  Konvertieren eines Windows 10-Systems aus BIOS in UEFI (Unified Extensible Firmware Interface).  </li>
<li>  Aktivieren von Windows 10-Sicherheitsfeatures.  </li>
<li>  Konfigurieren der Windows-Bereitstellungsdienste (WDS) für den PXE-Start (Preboot Execution Environment).  </li>
<li>  Verwenden des Microsoft Deployment Toolkit (MDT) zum Erfassen und Bereitstellen von Windows 10-Images.  </li>
<li>  Verwenden des Migrationstools für den Benutzerstatus (USMT).  </li>
</ul>
Wenden Sie sich <a href="https://go.microsoft.com/fwlink/?linkid=2080150">an einen Microsoft-Partner,</a> um Unterstützung bei diesen Diensten zu erhalten.  </td>
<td>  Für ein PC-Upgrades müssen Sie die folgenden Voraussetzungen erfüllen:
<ul>
<li>  Quellbetriebssystem: Windows 7 Enterprise oder Professional, Windows 8.1 Enterprise oder Professional.  </li>
<li>  Geräte: Desktop-, Notizbuch- oder Tablet-Formfaktor.  </li>
<li>  Zielbetriebssystem: Fenster 10 Enterprise.  </li>
</ul>
Für ein Infrastrukturupgrade müssen Sie diese Voraussetzungen erfüllen:
<ul>
<li>  Microsoft Endpoint Configuration Manager.  </li>
<li>  Die Configuration -Manager-Version muss von der Windows 10-Zielversion unterstützt werden. Weitere Informationen finden Sie in der Configuration Manager-Tabelle der unterstützten Versionen unter <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Unterstützung für Windows 10 in Configuration Manager</a>.  </li>
</ul>

<tr class="odd">
<td><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></td>
<td>  Microsoft Defender Advanced Threat Protection (ATP) ist eine Plattform, mit deren Hilfe Unternehmensnetzwerke erweiterte Bedrohungen verhindern, erkennen, untersuchen und darauf reagieren können.  
  Wir bieten Remoteanleitungen für:
<ul>
<li>  Bereitstellen der Technologien zum Sichern Ihrer Endpunkte.  </li>
<li>  Konfigurieren von Endpunktschutz- und Geräteeinschränkungsprofilen.  </li>
<li>  Bewerten der Betriebssystemversion und Geräteverwaltung (einschließlich Intune, Microsoft Endpoint Configuration Manager, Gruppenrichtlinienobjekte (GPOs) und Drittanbieterkonfigurationen sowie des Status Ihrer Windows Defender -AV-Dienste oder anderer Endpunktsicherheitssoftware.  </li>
<li>  Bewerten des Status Ihrer Windows -AV-Dienste oder anderer Endpunktsicherheitssoftware.  </li>
<li>  Bewerten von Proxys und Firewalls, die den Netzwerkdatenverkehr einschränken.  </li>
<li>  Aktivieren des Microsoft Defender ATP-Diensts, indem erläutert wird, wie ein ATP-Agent-Profil mithilfe eines integrierten Endpunkts bereitgestellt wird.  </li>
<li>  Bereitstellungsleitfas, Konfigurationsunterstützung und Bildungseinrichtungen zu:
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
<li> Microsoft Defender ATP (Windows E5- oder Microsoft 365 E5-Lizenzen sind erforderlich).  </li>
<li>  
  Sicherheitsbewertung.  
  </li>
</ul></li>
<li>  Überprüfen von Simulationen und Lernprogrammen (z. B. Praxisszenarien, gefälschte Schadsoftware und automatisierte Untersuchungen).  </li>
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
  macOS Version 10.13, 10.14 und 10.15.  
  </li>
</ul>
</li>
</ul>
<strong>Hinweis:</strong> Alle Windows Server-Versionen müssen mit der neuesten Version von System Center Configuration Manager 2012 (Versionen 1012 R2, 1511 oder 1602) oder Microsoft Endpoint Configuration Manager (Version 2002 oder höher) verwaltet werden. 

</li>
</ul>

<strong>Folgendes liegt nicht im Gültigkeitsbereich </strong>  
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
<li>  Server-Onboarding und -Konfiguration:
<ul>
<li>  
  Konfigurieren eines Proxyservers für die Offlinekommunikation.  
  </li>
<li>  
  Konfigurieren von Configuration Manager-Bereitstellungspaketen für Konfigurations-Manager-Instanzen und -Versionen auf einer älteren Ebene.  
  </li>
<li>  
  Onboarding von Servern in Azure Security Center.  
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
  Andere produktbasierte Bereitstellung der mobilen Geräteverwaltung (MdM).  
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
<li>  Konfiguration oder Schulung zur Überprüfung von API- oder Sicherheitsinformationen und Ereignisverwaltung (SIEM)-Verbindungen.  </li>
<li>  Registrierung oder Konfiguration von Microsoft Threat Protection (MTP).  </li>
<li>  Schulungen oder Anleitungen für die erweiterte Suche.  </li>
<li>  Schulungen oder Anleitungen zur Verwendung oder Erstellung von Kusto-Abfragen.</li>
</li>
</ul>
Wenden Sie sich <a href="https://go.microsoft.com/fwlink/?linkid=2080150">an einen Microsoft-Partner,</a> um Unterstützung bei diesen Diensten zu erhalten.  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a>Windows Virtual Desktop

<table>
<thead>
<tr class="header">
<th><strong>Dienst</strong></th>
<th><strong>Details zur FastTrack-Anleitung</strong></th>
<th><strong>Erwartungen an die Quellumgebung</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows Virtual Desktop</strong></td>
<td><p>Wir bieten Bereitstellungsanleitungen für das Onboarding in Windows Virtual Desktop (einen Desktop- und App-Virtualisierungsdienst). Windows Virtual Desktop nutzt die Windows 10-Erfahrung mit mehreren Sitzungen und ist für Microsoft 365 Apps for Enterprise mit integrierter Sicherheit und Verwaltung für Microsoft 365 optimiert.</p>
<p>Wir bieten Remoteanleitungen für:</p>
<ul>
<li>Bereitstellen Ihrer Windows Virtual Desktop-Umgebung mit Windows 10 Enterprise mit mehreren Sitzungen und Microsoft 365 Apps for Enterprise mithilfe der folgenden Optionen:
<ul>
<li>Azure Marketplace-Image.</li>
<li>Freigegebenes Bild.</li>
<li>Office Deployment Toolkit (ODT).</li>
</ul></li>
<li>Konfigurieren von FSLogix:
<ul>
<li>Bereitstellen des FSLogix Agent mit Profilcontainer.</li>
<li>Bereitstellen des FSLogix Agent mit Office-Container.</li>
<li>Konfigurieren des Ordners "FSLogix" mit Inhaltsausschlüssen.</li>
</ul></li>
<li>Bereitstellen von Microsoft Edge.</li>
<li>Bereitstellen von Microsoft Teams.</li>
<li>Herstellen einer Verbindung mithilfe von Windows Virtual Desktop-Clients.</li>
</ul>

<strong>Folgendes liegt nicht im Gültigkeitsbereich</strong>
<ul>
<li>Projektmanagement der Windows Virtual Desktop-Bereitstellung des Kunden.</li>
<li>Drittanbieter-App-Virtualisierung und -Bereitstellung.</li>
<li>Benutzerdefinierte Bilder.</li>
<li>Migrationen und Szenarien im Zusammenhang mit VMware und Citrix.</li>
<li>Linux-Szenarien.</li>
<li>Konvertierung oder Migration von Benutzerprofilen.</li>
</ul>
Wenden Sie sich <a href="https://go.microsoft.com/fwlink/?linkid=2080150">an einen Microsoft-Partner,</a> um Unterstützung bei diesen Diensten zu erhalten.</td>
<td>Sie sollten bereits über Folgendes verfügen:
<ul>
<li><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Lizenzierungsanforderungen für Windows Virtual Desktop</a>.</li>
<li>Azure-Netzwerke:
<ul>
<li>Erstellen und Subnetzen des virtuellen Netzwerks (VNET).</li>
<li>Firewall- und Netzwerksicherheitsgruppen.</li>
<li>VPN und ExpressRoute.</li>
<li>Routing von der lokalen Bereitstellung zu Azure.</li>
<li>Firewallregeln zum Zulassen der Konnektivität mit Windows Virtual Desktop.
</ul>
Weitere Informationen finden Sie unter <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">"Unterstützte Remotedesktopclients".</a>
</ul>
<ul><li>Allgemeine Einrichtung von Azure AD:
<ul>
<li>Identitätsstrategie <i>(Sie können nur eine der folgenden drei Optionen verwenden):</i>
<ul>
<li>Active Directory mit Azure AD Connect in Azure.</li>
<li>Active Directory mit Azure AD Connect lokal über VPN oder ExpressRoute.</li>
<li>Active Directory Domain Services (AD DS).</li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a>App Assure


<table>
<thead>
<tr class="header">
<th><strong>Dienst</strong></th>
<th><strong>Details zur FastTrack-Anleitung</strong></th>
<th><strong>Erwartungen an die Quellumgebung</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>App Assure</strong></td>
<td>  App Assure ist ein Dienst zum Beheben von Problemen mit der Kompatibilität von Windows 10- und Microsoft 365-Apps-Apps. Wenn Sie den App Assure-Dienst anfordern, arbeiten wir mit Ihnen zusammen, um gültige Probleme mit der App ohne zusätzliche Kosten für Sie mit einem berechtigten Abonnement zu beheben. Wir bieten auch Anleitungen für Kunden, die bei der Bereitstellung von Windows Virtual Desktop und Microsoft Edge Kompatibilitätsprobleme haben und alle angemessenen Anstrengungen unternehmen, um Kompatibilitätsprobleme zu beheben. Wir bieten Unterstützung bei der Problembehebung für Apps, die in den folgenden Microsoft-Produkten bereitgestellt werden:
<ul>
<li>  <strong>Windows 10 </strong> (einschließlich ARM64-Geräten)</li>
<li> <strong>Microsoft 365-Apps</strong>  </li>
<li>  <strong>Microsoft Edge –</strong> Anleitungen zur Bereitstellung finden Sie <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">unter Übersicht über die Microsoft Edge-Kanäle.</a>  </li>
<li>  <strong>Windows Virtual Desktop</strong> - Weitere Informationen finden Sie unter Häufig gestellte Fragen zu <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">Windows Virtual Desktop</a> und Windows <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">10 Enterprise für mehrere Sitzungen.</a>  </li>
</ul>

<strong>Folgendes liegt nicht im Gültigkeitsbereich </strong>  
<ul>
<li>  App-Bestandserfassung und Tests dazu, was unter Windows 10 und Microsoft 365 Apps funktioniert und was nicht. Weitere Hilfestellung zu diesem Vorgang, finden Sie im <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Bereitstellungscenter für Desktop</a>. Wenn Sie an einer detaillierten Upgradebereitschaftsbewertung interessiert sind, füllen Sie das Formular <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Kundenanforderung auf Bewertung der Bereitschaft für den modernen Desktop</a> aus.</li>
<li>  Untersuchen von ISV-Apps von Drittanbietern auf Windows 10-Kompatibilität und Supportanweisungen. Weitere Informationen finden Sie unter <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktopanalysen</a>.</li>
<li>Dienste nur für das App-Packaging. Das Desktop App Assure-Team paketiert jedoch Apps, für die alle Probleme für Windows 10 behoben wurden, um sicherzustellen, dass sie in der Umgebung des Kunden bereitgestellt werden können.</li>
</ul>

<strong>Zu den Verantwortlichkeiten des Kunden gehören u. a.</strong>  
<ul>
<li>  Erstellen eines App-Inventars.</li>
<li>  Überprüfen der Apps unter Windows 10 und Microsoft 365 Apps.</li>
</ul>
<strong>Hinweis:</strong>  Microsoft kann keine Änderungen an Ihrem Quellcode vornehmen. Das Desktop App Assure-Team kann jedoch App-Entwickler beraten, wenn Quellcode für Ihre Apps verfügbar ist. 


  Wenden Sie sich <a href="https://go.microsoft.com/fwlink/?linkid=2080150">an einen Microsoft-Partner,</a> um Unterstützung bei diesen Diensten zu erhalten.  </td>

</td>
<td><strong>Windows 10 und Microsoft 365 Apps</strong>
<ul>
<li>  
  Apps, die unter Windows 7, Windows 8,1, Office 2010 und Office 2013 funktioniert haben, funktionieren ebenfalls unter Windows 10 und Microsoft 365 Apps.  
  </li>
</ul>
<strong>Windows 10 auf ARM</strong>
<ul>
<li>  
Apps, die unter Windows 7, Office 2010 oder höher funktionierten, funktionieren auch auf Windows 10- und Microsoft 365-Apps auf ARM64-Geräten. 
  </li>
</ul>
  <strong>Hinweis:</strong> 
<ul>
<li> Die x64-Emulation (64-Bit) ist als Vorschau für Kunden verfügbar, die am <a href="https://insider.windows.com/">Windows-Insider-Programm teilnehmen.</a>  </li>
<li>  
 Für Nicht-Windows-Insider-Kunden unter Windows 10, Version 2004 (oder höher), wird ARM64 Photoshop mit openCL und <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenGL Compatibility Pack unterstützt.</a> 
  </li>
<li>  
  Kunden im Windows-Insider-Programm können eine Insider-Version des OpenCL- und OpenGL-Kompatibilitätspakets für die Verwendung mit zusätzlichen Apps herunterladen.    
  </li>
</ul>
<strong>Microsoft Edge</strong>
<ul>
<li>  
  Wenn Ihre Web-Apps oder -Websites mit Internet Explorer 11, unterstützten Versionen von Google Chrome oder einer beliebigen Version von Microsoft Edge funktionieren, funktionieren sie auch mit Microsoft Edge.  
  </li>
<li>  
  Da sich das Web ständig weiterentwickelt, sollten Sie diese veröffentlichte Liste bekannter Websitekompatibilitätsänderungen überprüfen, die sich auf <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">Microsoft Edge auswirken.</a>  
  </li>
</ul>
  <strong>Windows Virtual Desktop </strong>  
<ul>
<li>  
  Virtualisierte Apps, die auf dem Windows Server-Remotedesktop-Sitzungshost (RDSH) ausgeführt werden, können als Bestandteil von Windows Virtual Desktop auch unter Windows 10 Enterprise Multi-Session ausgeführt werden.  
  </li>
<li>  
  Apps, die in einer Windows 7- oder Windows 10 Virtual Desktop Infrastructure (VDI)-Umgebung ausgeführt werden, werden auch unter Windows 7 Enterprise und Windows 10 Enterprise als Teil von Windows Virtual Desktop ausgeführt.  
  </li>
<li>  
  Apps, die unter Windows 7 oder Windows 10 auf Kundengeräten ausgeführt werden, können als Bestandteil von Windows Virtual Desktop auch unter Windows 7 Enterprise und Windows 10 Enterprise ausgeführt werden.  
  </li>
</ul>
  <strong>Hinweis:</strong> Zu den Kompatibilitätsausschlüssen und -einschränkungen für Windows 10 Enterprise mit mehreren Sitzungen gehören:
<ul>
<li>  
  Eingeschränkte Umleitung von Hardware.  
  </li>
<li>  
  A/V-intensive Apps können eine eingeschränkte Kapazität zur Folge haben.  
  </li>
<li>  
  16-Bit-Apps werden für den 64-Bit-Windows Virtual Desktop nicht unterstützt.  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a>Microsoft Edge


<table>
<thead>
<tr class="header">
<th><strong>Dienst</strong></th>
<th><strong>Details zur FastTrack-Anleitung</strong></th>
<th><strong>Erwartungen an die Quellumgebung</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Microsoft Edge</strong> (für Windows 10 Enterprise-Kunden)</td>
<td><ul>
<li>  Wir bieten Anleitungen zur Remotebereitstellung und Kompatibilitätsunterstützung für: Bereitstellen von Microsoft Edge unter Windows 10 Enterprise mit Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager oder Intune).  </li>
<li>  Microsoft Edge-Konfiguration (mithilfe von Gruppenrichtlinien oder Intune-App-Konfiguration und App-Richtlinien).  </li>
<li>  Inventarisierung der Liste der Websites, die möglicherweise im Internet Explorer-Modus verwendet werden müssen.  </li>
<li>  Aktivieren des Internet Explorer-Modus mit der vorhandenen Enterprise Site List.  
  Wenn Sie darüber hinaus über eine Web-App oder -Website verfügen, die mit Internet Explorer oder Google Chrome funktioniert und Kompatibilitätsprobleme auftreten, bieten wir Anleitungen, um das Problem ohne zusätzliche Kosten zu beheben. Weitere Informationen finden Sie unter <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">App Assure.</a>  </li>
</ul>

<strong>Folgendes ist nicht gegenstands- </strong>  
<ul>
<li>Projektmanagement der Microsoft Edge-Bereitstellung des Kunden.</li>
<li>  Unterstützung vor Ort.</li>

</td>
<td></td>
</tr>
</tbody>
</table>
