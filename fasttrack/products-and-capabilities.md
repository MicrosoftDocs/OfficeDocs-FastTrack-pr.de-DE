---
title: Produkte und Funktionen
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 6/16/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Dieses Thema enthält Details zu den Workloadszenarien, die von FastTrack unterstützt werden, und zu den Erwartungen an die Quellumgebung, die erforderlich sind, bevor wir beginnen können. Basierend auf Ihrem aktuellen Setup arbeiten wir mit Ihnen zusammen, um einen Korrekturplan zu erstellen, mit dem Ihre Quellumgebung den Mindestanforderungen für ein erfolgreiches Onboarding entspricht.
ms.openlocfilehash: 0d5272079471b7dafe40e45f6c72189f1dad4c12
ms.sourcegitcommit: cff44abb4212a768ccdcfd00226793d4dc3b02d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/17/2021
ms.locfileid: "52994868"
---
# <a name="products-and-capabilities"></a>Produkte und Funktionen

## <a name="services-and-scenarios-supported-by-fasttrack"></a>Von FastTrack unterstützte Dienste und Szenarien 

Dieses Thema enthält Details zu den Workloadszenarien, die von FastTrack unterstützt werden, und zu den Erwartungen an die Quellumgebung, die erforderlich sind, bevor wir beginnen können. Basierend auf Ihrem aktuellen Setup arbeiten wir mit Ihnen zusammen, um einen Korrekturplan zu erstellen, mit dem Ihre Quellumgebung den Mindestanforderungen für ein erfolgreiches Onboarding entspricht.

FastTrack bietet Anleitungen, die Ihnen zunächst bei den Kernfunktionen (allgemein für alle Microsoft Online Services) und dann beim Onboarding der einzelnen berechtigten Dienste helfen:

  - [Allgemein](#general)
  - [Sicherheit und Compliance](#security-and-compliance)
  - [Office 365](#office-365)
  - [Enterprise Mobility + Security](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [Windows Virtual Desktop](#windows-virtual-desktop)
  - [App Assure](#app-assure)
  - [Microsoft Edge](#microsoft-edge)

> [!NOTE]
> Informationen zu Anforderungen an die Quellumgebung für Office 365 US Government finden Sie unter [Anforderungen an die Quellumgebung für Office 365 US Government](/us-gov-appendix-source-environment-expectations). 
 
## <a name="general"></a>Allgemein

<table>
<thead>
<tr class="header">
<th><strong>Dienst</strong></th>
<th><strong>FastTrack Anleitungsdetails</strong></th>
<th><strong>Erwartungen an die Quellumgebung</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Haupt-Onboarding</strong></td>
<td>  Wir bieten Remote-Anleitungen für das Onboarding von Kernen, die dienstbereitstellung, Mandanten- und Identitätsintegration umfassen. Es enthält auch Schritte zur Bereitstellung einer Grundlage für Onboarding-Dienste wie Exchange Online, SharePoint Online und Microsoft Teams, einschließlich einer <a href="/office365/enterprise/office-365-network-connectivity-principles">Diskussion über Sicherheit, Netzwerkkonnektivität und Compliance.</a>   

Das Onboarding für einen oder mehrere berechtigte Dienste kann beginnen, sobald das Haupt-Onboarding abgeschlossen ist.
</li>
</ul>  

<strong> Identitätsintegration </strong>

Wir bieten Remoteanleitungen für:
<ul>
<li>Vorbereiten lokaler Active Directory-Identitäten für die Synchronisierung mit Azure Active Directory (Azure AD), einschließlich der Installation und Konfiguration von Azure AD-Verbinden (einzelne oder mehrere Gesamtstrukturen) und Lizenzierung (einschließlich gruppenbasierter Lizenzierung).</li>
<li>Erstellen von Cloudidentitäten einschließlich Massenimport und Lizenzierung, einschließlich gruppenbasierter Lizenzierung.</li>
<li>Auswählen und Aktivieren der richtigen Authentifizierungsmethode für Ihre Cloud-Reise, Kennworthashsynchronisierung, Pass-Through-Authentifizierung oder Active Directory-Verbunddienste (AD FS).</li>
<li> Auswählen und Aktivieren einer bequemeren Authentifizierung für Ihre Benutzer mit kennwortloser Authentifizierung (Fast Identity Online (FIDO)2 oder Microsoft Authenticator App).</li>
<li>Aktivieren von AD FS für Kunden mit einer einzigen Active Directory-Gesamtstruktur und Identitäten, die mit dem Azure AD Verbinden-Tool synchronisiert sind. Dies erfordert Windows Server 2012 R2 Active Directory-Verbunddienste 2.0 oder höher.</li>
<li>Migrieren der Authentifizierung von AD FS zu Azure AD mithilfe der Kennworthashsynchronisierung oder Pass-Through-Authentifizierung.</li>
<li>Migrieren von vorintegrierten Apps (z. B. SaaS-Apps (Azure AD Gallery Software-as-a-Service) von AD FS zu Azure AD für einmaliges Anmelden (Single Sign-On, SSO).</li>
<li>Aktivieren von SaaS-App-Integrationen mit SSO aus dem Azure AD-Katalog.</li>
<li>Aktivieren der automatischen Benutzerbereitstellung für vorintegrierte SaaS-Apps, wie in der <a href="/azure/active-directory/saas-apps/tutorial-list">Lernprogrammliste zur App-Integration </a> aufgeführt (beschränkt auf SaaS-Apps des Azure AD-Katalogs und nur ausgehende Bereitstellung).  </li>

</td>

<td>  <strong>Netzwerk-Aktivierung </strong>  
  <br>Im Rahmen des FastTrack Vorteils empfehlen wir Ihnen, bewährte Methoden für die Verbindung mit Clouddiensten zu verwenden, um die höchste Leistung von Microsoft 365 sicherzustellen.  
  
<strong>Active Directory-Gesamtstrukturen</strong> Diese haben die Funktionalgesamtstrukturebene auf Windows Server 2003 und die folgende Gesamtstrukturkonfiguration festgelegt:
<ul>
<li>  Einzelne Active Directory-Gesamtstruktur  </li>
<li>  Eine einzelne Active Directory-Kontogesamtstruktur und Ressourcen-Gesamtstrukturtopologien (Exchange und/oder Lync 2010, Lync 2013 oder Skype for Business)  </li>
<li>  Mehrere Active Directory-Kontogesamtstrukturen und Ressourcen-Gesamtstrukturtopologien (Exchange und/oder Lync 2010, Lync 2013 oder Skype for Business)  </li>
<li>  Mehrere Active Directory-Kontogesamtstrukturen, wobei eine der Gesamtstrukturen eine Gesamtstruktur mit einem zentralen Active Directory-Konto ist, die Exchange und/oder Lync 2010, Lync 2013 oder Skype for Business umfasst.  </li>
<li>  Mehrere Active Directory-Konto-Gesamtstrukturen mit einer jeweils eigenen Exchange-Organisation  </li>
<li>  Aufgaben, die bei Bedarf für die Mandantenkonfiguration und -integration in Azure Active Directory erforderlich sind.   </li>
</ul>
  <strong>Wichtig</strong>  <ul>
<li>  Wenn Lync 2010, Lync 2013 oder Skype for Business in Active Directory-Szenarien mit mehreren Gesamtstrukturen bereitgestellt wird, muss es in derselben Active Directory-Gesamtstruktur wie Exchange bereitgestellt werden.  </li>
<li>  Beim Implementieren mehrerer Active Directory-Gesamtstrukturen mit mehreren Exchange Organisationen in einer Exchange Multihybridkonfiguration werden freigegebene UPN-Namespaces (User Principal Name) zwischen Quellgesamtstrukturen nicht unterstützt. Primäre SMTP-Namespaces zwischen Exchange-Organisationen sollten ebenfalls getrennt werden. Weitere Informationen finden Sie unter <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybridbereitstellungen mit mehreren Active Directory-Gesamtstrukturen</a>.  </li>
<li>  Für alle Konfigurationen mit mehreren Gesamtstrukturen liegt die Ad FS-Bereitstellung (Active Directory Federation Services) außerhalb des Bereichs. Wenden Sie sich an einen <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft-Partner,</a> um Hilfe zu erhalten.  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft 365 Apps</strong></td>
<td>  Wir bieten Anleitungen für die Remotebereitstellung für:
<ul>
<li>  Beheben von Problemen bei der Bereitstellung  </li>
<li>  Zuweisen von Endbenutzerlizenzen und gerätebasierten Lizenzen mit Microsoft 365 Admin Center und Windows PowerShell.  </li>
<li>  Installieren von Microsoft 365-Apps aus dem Office 365-Portal mithilfe von Klick-und-Los.  </li>
<li>  Installieren von Office Mobile-Apps (wie Outlook Mobile, Word Mobile, Excel Mobile und PowerPoint Mobile) auf Ihren iOS- oder Android-Geräten.  </li>
<li>  Konfigurieren von Updateeinstellungen mit dem Office 365-Bereitstellungstool  </li>
<li>  Auswahl und Einrichtung einer lokalen oder Cloud-Installation.  </li>
<li>  Erstellung der Konfigurations-XML des Office-Bereitstellungstool mit dem Office-Anpassungstool oder nativem XML zur Konfiguration des Bereitstellungspakets.  </li>
<li>  Bereitstellen mit Microsoft Endpoint Configuration Manager, einschließlich Unterstützung beim Erstellen des Microsoft Endpoint Configuration Manager-Pakets.  
  Wenn Sie über ein Makro oder Add-In verfügen, das mit früheren Versionen von Office funktioniert hat und Kompatibilitätsprobleme auftreten, bieten wir außerdem Anleitungen zur Behebung des Kompatibilitätsproblems ohne zusätzliche Kosten über das App Assure-Programm. Weitere Informationen finden Sie im <strong>App Assure-Teil</strong> von <a href="#windows-10">Windows 10.</a> </li>
</ul></td>
<td><ul>
<li>  Die Onlineclientsoftware muss mindestens so sein, wie sie in den <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Systemanforderungen für Microsoft 365 und Office</a>definiert ist.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Netzwerkintegrität</strong></td>
<td>  Wir bieten Remoteanleitungen zum Abrufen und Interpretieren wichtiger Netzwerkkonnektivitätsdaten aus Ihrer Umgebung, die zeigen, wie ausgerichtet die Standorte Ihrer Organisation an den <a href="/office365/enterprise/office-365-network-connectivity-principles">Prinzipien der Netzwerkkonnektivität von</a>Microsoft sind. Dadurch wird Ihre Netzwerkbewertung hervorgehoben, die sich direkt auf die Migrationsgeschwindigkeit, die Benutzererfahrung, die Dienstleistung und die Zuverlässigkeit auswirkt.  
  Wir führen Sie auch durch alle Korrekturschritte, die durch diese Daten hervorgehoben werden, um Ihre Netzwerkbewertung zu verbessern.  </td>
<td><ul>
<li>  Microsoft 365 Admin Zentrer Zugriff.  </li>
<li>  Es sind aktuelle Versionen von Microsoft 365-Apps erforderlich.  </li>
<li>  Standortdienste, die gemäß <a href="/Office365/Enterprise/office-365-network-mac-perf-overview">den Empfehlungen zur Netzwerkleistung im Microsoft 365 Admin Center (Vorschau)</a>aktiviert sind.  </li>
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
<th><strong>FastTrack Anleitungsdetails</strong></th>
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
<li>  Konfigurieren und Aktivieren einer starken Authentifizierung für Ihre Identitäten, einschließlich des Schutzes mit Azure Multi-Factor Authentication (MFA) (nur Cloud), der Microsoft Authenticator-App und der kombinierten Registrierung für Azure MFA und Self-Service Password Reset (SSPR).  </li>
<li> Bereitstellen von FIDO2 oder Microsoft Authenticator App. </li>
<li>  Nicht Azure AD Premium Kunden erhalten Anleitungen zum Sichern Ihrer Identitäten mithilfe von Sicherheitsstandards.  </li>
<li>  Azure AD Premium-Kunden erhalten Anleitungen zum Sichern Ihrer Identitäten mit bedingtem Zugriff.  </li>
<li>  Erkennen und Blockieren der Verwendung schwacher Kennwörter mit Azure AD Password Protection.  </li>
<li>  Sichern des Remotezugriffs auf lokale Web-Apps mit dem Azure AD-Anwendungsproxy.  </li>
<li>  Aktivieren der risikobasierten Erkennung und Behebung mit Azure Identity Protection.  </li>
<li>  Aktivieren eines benutzerdefinierten Anmeldebildschirms, einschließlich Logo, Text und Bildern mit benutzerdefiniertem Branding.  </li>
<li>  Sicheres Teilen von Apps und Diensten mit Gastbenutzern mit Azure AD B2B.  </li>
<li>  Verwalten des Zugriffs für Ihre Office 365 Administratoren mithilfe von rollenbasierten Zugriffssteuerungsrollen (Role-Based Access Control, RBAC) integrierten Administratorrollen und zur Reduzierung der Anzahl privilegierter Administratorkonten.  </li>
<li>  Konfigurieren der Hybrid-Azure AD-Verknüpfung.  </li>
<li>  Konfigurieren der Azure AD-Verknüpfung.  </li>
</ul>
  
<strong>Überwachen und Melden</strong>  
<ul>
<li>  
  Aktivieren der Remoteüberwachung für AD FS, Azure AD Verbinden und Domänencontroller mit Azure AD Verbinden Health.  
  </li>
</ul>
  
<strong>Governance</strong>  
<ul>
<li>  
  Verwalten Ihres Azure AD-Identitäts- und Zugriffslebenszyklus im großen Maßstab mit Azure AD-Berechtigungsverwaltung.
  </li>
<li>  
  Verwalten von Azure AD-Gruppenmitgliedschaften, Zugriff auf Unternehmens-Apps und Rollenzuweisungen mit Azure AD-Zugriffsüberprüfungen.  
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
<li>  Ermöglicht Benutzern das Erstellen und Verwalten eigener Cloudsicherheits- oder Office 365-Gruppen mit azure AD Self-Service-Gruppenverwaltung.  </li>
<li>  Verwalten des delegierten Zugriffs auf Unternehmens-Apps mit delegierter Azure AD-Gruppenverwaltung.  </li>
<li>  Aktivieren dynamischer Azure AD-Gruppen.  </li>
<li>  Organisieren von Apps im Portal "Meine Apps" mithilfe von Sammlungen.  </li>
</ul></td>
<td>Das lokale Active Directory und seine Umgebung wurden für Azure AD Premium vorbereitet, einschließlich der Behebung identifizierter Probleme, die die Integration in Azure AD und Azure AD Premium Features verhindern.</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection </strong></td>
<td>  Weitere Informationen zu Azure Information Protection finden Sie <strong>Microsoft Information Protection</strong> weiter unten in dieser Tabelle.

  </td>
<td>  
  <tr class="odd">
<td><strong>Ermitteln & Antworten</strong></td>
<td>  

<strong>Erweiterte eDiscovery</strong>
  
Wir bieten Remoteanleitungen für: 
<ul>
<li>  Erstellen eines neuen Falls.   </li>
<li>  Verwahrer in die Sperre versetzen.  </li>
<li>  Durchführen von Suchvorgängen. </li>
<li>  Hinzufügen von Suchergebnissen zu einem Prüfdateisatz. </li>
<li>  Ausführen von Analysen in einem Prüfdateisatz.  </li>
<li>  Überprüfen und Markieren von Dokumenten.  </li>
<li>  Exportieren von Daten aus dem Prüfdateisatz. </li>
<li>  Importieren von Nicht-Office 365-Daten. </li>
</ul>

<strong>Erweiterte Überwachung</strong> (wird nur in E5 unterstützt)

Wir bieten Remoteanleitungen für:  
<ul>
<li> Aktivieren der erweiterten Überwachung.</li>
<li> Durchführen einer Benutzeroberfläche für das Suchüberwachungsprotokoll und grundlegender PowerShell-Überwachungsbefehle.</li>
</ul>

<strong> Compliance-Manager</strong>

Wir bieten Remoteanleitungen für:  

<ul> <li>Überprüfen von Rollentypen.  </li>
<li> Hinzufügen und Konfigurieren von Bewertungen.</li>
<li> Bewertung der Compliance durch Implementierung von Verbesserungsmaßnahmen und Bestimmen, wie sich dies auf Ihre Compliancebewertung auswirkt.</li>
<li> Überprüfen der integrierten Steuerelementzuordnung und -bewertung von Steuerelementen.</li>
<li> Generieren eines Berichts innerhalb einer Bewertung.</li>
</ul>

<strong>Folgendes liegt außerhalb des Gültigkeitsbereichs </strong> 
<ul>
<li> Benutzerdefinierte Skripterstellung oder Codierung.</li>
<li> eDiscovery-API. </li>
<li> Datenkonnektoren. </li>
<li> Compliancegrenzen und Sicherheitsfilter.</li>
<li> Datenuntersuchungen.</li>
<li> Anträge betroffener Personen.</li>
<li> Entwurfs-, Architektur- und Drittanbieterdokumentüberprüfung.</li>
<li> Einhaltung von Branchen- und regionalen Vorschriften und Anforderungen.</li>
<li> Praktische Implementierung empfohlener Verbesserungsmaßnahmen für Bewertungen im Compliance-Manager.</li>
</ul>
</td>
<td>Abgesehen vom <strong>Core-Onboarding-Teil</strong> im <a href="#general">Allgemeinen</a>gibt es keine Mindestsystemanforderungen.</td>
</tr>

<tr class="odd">
<td><strong>Insider-Risikomanagement</strong></td>

<td>  Wir bieten Remoteanleitungen für:
<ul>
<li> Erstellen von Richtlinien und Überprüfen von Einstellungen.</li>
<li> Zugreifen auf Berichte und Warnungen.</li>
<li> Erstellen von Fällen.</li>
<li> Erstellen von Benachrichtigungsvorlagen.</li>
<li> Anleitung zum Erstellen des Hr-Connectors (Personalwesen).</li>
</ul>

<strong> Kommunikationscompliance </strong> 

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
<li> Bewertung der Compliance durch Implementierung von Verbesserungsmaßnahmen und Bestimmen, wie sich dies auf Ihre Compliancebewertung auswirkt.</li>
<li> Überprüfen der integrierten Steuerelementzuordnung und -bewertung von Steuerelementen.</li>
<li> Generieren eines Berichts innerhalb einer Bewertung.</li>
</ul>

<strong>Folgendes liegt außerhalb des Gültigkeitsbereichs </strong> 
<ul>
<li> Erstellen und Verwalten von Power Automate Flüssen.</li>
<li> Datenconnectors (über den HR-Connector hinaus). </li>
<li> Benutzerdefinierte RegEx-Konfigurationen (Regulärer Ausdruck).</li>
<li> Entwurfs-, Architektur- und Drittanbieterdokumentüberprüfung.</li>
<li> Informationsbarrieren.</li>
<li> Privileged Access Management.</li>
<li> Einhaltung von Branchen- und regionalen Vorschriften und Anforderungen.</li>
<li> Praktische Implementierung empfohlener Verbesserungsmaßnahmen für Bewertungen im Compliance-Manager.</li>
</ul></td>
<td>Abgesehen vom <strong>Core-Onboarding-Teil</strong> im <a href="#general">Allgemeinen</a>gibt es keine Mindestsystemanforderungen.</td>
</tr>
</td>
</tr>

<tr class="even">
<td><strong>Microsoft 365 Defender</strong></td>

<td> <p> Microsoft 365 Defender ist eine einheitliche Verteidigungssuite vor und nach einem Angriff, die Erkennung, Verhinderung, Untersuchung und Reaktion auf Endpunkte, Identitäten, E-Mails und Apps nativ koordiniert, um integrierten Schutz vor komplexen Angriffen zu bieten. Wir bieten Remoteanleitungen für: </p> 
<ul>
<li>  Bereitstellen einer Übersicht über das Microsoft 365 Security Center.  </li>
<li>  Überprüfung produktübergreifender Vorfälle, einschließlich der Aufmerksamkeit auf das, was wichtig ist, indem der vollständige Angriffsbereich, betroffene Ressourcen und automatisierte Abhilfemaßnahmen, die gruppiert sind, sichergestellt werden.  </li>
<li>  Demonstrieren, wie Microsoft 365 Defender die Untersuchung von Objekten, Benutzern, Geräten und Postfächern orchestrieren kann, die durch automatische Selbstkorrektur kompromittiert worden sein könnten. </li>
<li>  Erläutern und Bereitstellen von Beispielen dafür, wie Kunden proaktiv nach Angriffsversuchen und Aktivitäten suchen können, die sich auf Ihre E-Mails, Daten, Geräte und Konten in mehreren Datensätzen auswirken.   </li>
<li> Zeigen Sie Kunden, wie sie ihren Sicherheitsstatus mithilfe der Microsoft-Sicherheitsbewertung in einem ganzheitlichen Ansatz überprüfen und verbessern können.</li>
</ul>
<p><strong>Folgendes liegt außerhalb des Gültigkeitsbereichs</strong></p>
<ul>
<li> Projektmanagement der Problemlösungsaktivitäten des Kunden. </li>
<li> Fortlaufendes Management, Reaktion auf Bedrohungen und Behebung. </li>
<li> Bereitstellungsleitfaden oder Schulung zu:
<ul>
<li> So korrigieren oder interpretieren Sie die verschiedenen Warnungstypen und überwachten Aktivitäten. </li>
<li> Untersuchen eines Benutzers, Computers, lateralen Bewegungspfads oder einer Entität. </li>
<li> Benutzerdefinierte Bedrohungssuche.  </li>
</ul>
</li>
<li> Unterstützung <a href=" /fasttrack/us-gov-appendix-overview">von GCC-High oder GCC-DoD (Office 365 US Government).</a></li>
<li> Sicherheitsinformations- und Ereignisverwaltung (Security Information and Event Management, SIEM) oder API-Integration.</li>
</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Cloud App Security</strong></td>
<td>  Microsoft Cloud App Security ist ein Cloud Access Security Broker (CASB), der umfassende Sichtbarkeit, Kontrolle über Datenverläufe und komplexe Analysen bietet, um Cyberbedrohungen in allen Ihren Microsoft- und Clouddiensten von Drittanbietern zu erkennen und zu bekämpfen. Wir bieten Remoteanleitungen für:
<ul>
<li>  Konfigurieren des Portals, einschließlich:  </li>
<ul>
<li> Importieren von Benutzergruppen.</li>
<li> Verwalten des Administratorzugriffs und der Einstellungen.  </li>
<li> Bereichsdefinition ihrer Bereitstellung, um bestimmte Benutzergruppen auszuwählen, die überwacht oder von der Überwachung ausgeschlossen werden sollen.</li>
<li> Einrichten von IP-Bereichen und Tags.</li>
<li> Personalisieren der Endbenutzerumgebung mit Ihrem Logo und benutzerdefiniertem Messaging.</li>
</ul>
<li> Integration von Erstanbieterdiensten, einschließlich:
<ul>
<li> Microsoft Defender für Endpunkt.</li>
<li> Microsoft Defender for Identity.</li>
<li> Azure AD Identity Protection.</li>
<li> Azure Information Protection.</li>
</ul>
<li> Einrichten der Cloudermittlung mithilfe von:</li>
<ul>
<li> Microsoft Defender für Endpunkte.</li>
<li> Zscaler.</li>
<li> iboss.</li>
</ul>
<li> Erstellen von App-Tags und -Kategorien.</li>
<li> Anpassen von App-Risikobewertungen basierend auf den Prioritäten Ihrer Organisation.</li>
<li> Sanktionierung und Nichtanordnung von Apps.</li>
<li> Überprüfen der Dashboards für Cloud App Security und Cloud Discovery.</li>
<li> Verbinden <a href="/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps"> von empfohlenen Apps</a> mit App-Connectors.</li>
<li> Schützen von Apps mit app-Steuerung für bedingten Zugriff im bedingten Zugriff innerhalb von Azure AD und Cloud App Security-Portalen.</li>
<li> Bereitstellen der App-Steuerung für bedingten Zugriff für ausgewählte Apps.</li>
<li> Verwenden der Aktivitäts- und Dateiprotokolle.</li>
<li> Verwalten von OAuth-Apps.</li>
<li> Überprüfen und Konfigurieren von Richtlinienvorlagen.</li>
<li> Bereitstellen von Konfigurationsunterstützung bei den <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20 wichtigsten Anwendungsfällen für CASBs</a> (einschließlich der Erstellung oder Aktualisierung von bis zu sechs (6) Richtlinien) außer: </li>
<ul>
<li> Überwachen der Konfiguration Ihrer IaaS-Umgebungen (Internet as a Service) (#18).</li>
<li> Überwachen von Benutzeraktivitäten zum Schutz vor Bedrohungen in Ihren IaaS-Umgebungen (#19).</li>
</ul>
<li> Grundlegendes zur Vorfallkorrelation im Microsoft 365 Defender-Portal.</li>
</ul>
<p><strong>Folgendes liegt außerhalb des Gültigkeitsbereichs</strong></p>
<ul>
<li> Projektmanagement der Problemlösungsaktivitäten des Kunden.</li>
<li> Fortlaufendes Management, Reaktion auf Bedrohungen und Behebung. </li>
<li> Diskussionen, in denen Cloud App Security mit anderen CASB-Angeboten verglichen wird.</li>
<li> Konfigurieren von Cloud App Security, um bestimmte Compliance- oder behördliche Anforderungen zu erfüllen.</li>
<li> Bereitstellen des Diensts in einer Nicht-Test-Produktionsumgebung.</li>
<li> Bereitstellen von Cloud App Discovery als Machbarkeitsstudie.</li>
<li> Unterstützung <a href=" /fasttrack/us-gov-appendix-overview">von GCC-High oder GCC-DoD (Office 365 US Government).</a></li>
<li> Einrichten der Infrastruktur, Installation oder Bereitstellung von automatischen Protokolluploads für fortlaufende Berichte mit Docker oder einem Protokollsammler. </li>
<li> Erstellen eines Cloud Discovery-Momentaufnahmeberichts.</li>
<li> Blockieren der App-Nutzung mithilfe von Blockskripts.</li>
<li> Verbinden von benutzerdefinierten Apps.</li>
<li> Onboarding und Bereitstellen der App-Steuerung für bedingten Zugriff für Apps, die keine Features enthalten.</li>
<li> Integration in Identitätsanbieter von Drittanbietern (IsPs) und DLP-Anbietern (Data Loss Prevention, Verhinderung von Datenverlust).</li>
<li> Schulungen oder Anleitungen für die erweiterte Suche.</li>
<li> Automatisierte Untersuchung und Behebung, einschließlich Microsoft Power Automate-Playbooks.</li>
<li> SIEM-Integration (Security Information and Event Management) oder API-Integration (einschließlich Azure Sentinel).</li>

</ul></td>
</tr>



<tr class="even">
<td><strong>Microsoft Defender für Endpunkt</strong></td>
<td>  Microsoft Defender für Endpunkt ist eine Plattform, die Unternehmensnetzwerke dabei unterstützt, fortgeschrittene Bedrohungen zu verhindern, zu erkennen, zu untersuchen und darauf zu reagieren.  
  Wir bieten Remoteanleitungen für:
<ul>
<li>  Bereitstellen der Technologien zum Sichern Ihrer Endpunkte.  </li>
<li>  Konfigurieren von Endpunktschutz- und Geräteeinschränkungsprofilen.  </li>
<li>  Bewerten der Betriebssystemversion und Geräteverwaltung (einschließlich Intune, Microsoft Endpoint Configuration Manager, Gruppenrichtlinienobjekte (GPOs) und Drittanbieterkonfigurationen) sowie des Status Ihrer Windows Defender AV-Dienste oder anderer Endpunktsicherheitssoftware.  </li>
<li>  Bewerten des Status Ihrer Windows AV-Dienste oder anderer Endpunktsicherheitssoftware.  </li>
<li>  Bewerten von Proxys und Firewalls, die den Netzwerkdatenverkehr einschränken.  </li>
<li>  Aktivieren des Microsoft Defender für Endpunkt-Diensts durch Erläutern der Bereitstellung eines Defender für Endpunkt-Agent-Profils mithilfe eines integrierten Endpunkts.  </li>
<li>  Bereitstellungsleitfaden, Konfigurationsunterstützung und Schulung zu:
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
  Sicherheitsbewertung für Geräte.  
  </li>
<li> Microsoft Defender SmartScreen-Konfiguration mit Microsoft Endpoint Manager.</li>

</ul></li>
<li>  Überprüfen von Simulationen und Lernprogrammen (z. B. Praxisszenarien, gefälschte Schadsoftware und automatisierte Untersuchungen).  </li>
<li>  Übersicht über Berichterstellungs- und Bedrohungsanalysefeatures.  </li>
<li>  Integrieren von Microsoft Defender für Office 365 in Microsoft Defender für Endpunkt.  </li>
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
<strong>Hinweis:</strong> Alle Windows Server-Versionen müssen mit der neuesten Version von System Center Configuration Manager 2012 (Versionen 1012 R2, 1511 oder 1602) oder Microsoft Endpoint Configuration Manager (Version 2002 oder höher) verwaltet werden. 

</li>
</ul>

<strong>Folgendes liegt außerhalb des Gültigkeitsbereichs </strong>  
<ul>
<li>  Projektmanagement der Problemlösungsaktivitäten des Kunden.  </li>
<li> Unterstützung <a href=" /fasttrack/us-gov-appendix-overview">von GCC-High oder GCC-DoD (Office 365 US Government).</a></li>
<li>  Unterstützung vor Ort.  </li>
<li>  Fortlaufende Verwaltung und Bedrohungsreaktion.  </li>
<li>  Onboarding oder Konfiguration für die folgenden Microsoft Defender für Endpunkt-Agents:
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
<li> Virtual Desktop Infrastructure (VDI) (persistent oder nicht persistent).  </li>
</ul></li>
<li>  Server-Onboarding und -Konfiguration:
<ul>
<li>  
  Konfigurieren eines Proxyservers für die Offlinekommunikation.  
  </li>
<li>  
  Konfigurieren von Configuration Manager-Bereitstellungspaketen auf Vorgängerversionen von Configuration Manager-Instanzen und -Versionen.  
  </li>
<li>  
  Onboarding von Servern in Azure Security Center.  
  </li>
<li>  
  Server, die nicht von Configuration Manager verwaltet werden.  
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
  Andere produktbasierte Bereitstellung für die Verwaltung mobiler Geräte (Mobile Device Management, MDM).  
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
<li> Gerätesteuerung.</li>
<li>  
  Exploit-Schutz.  
  </li>
<li>  
  Netzwerkfirewall.  
  </li>



</ul></li>
<li> Konfiguration oder Verwaltung von Kontoschutzfeatures wie: </li>
<ul>

<li> Windows Hello</li>
<li> Credential Guard</li>
</ul>
<li> Konfiguration oder Verwaltung von BitLocker.</li>
<li>  Registrierung oder Konfiguration von Microsoft-Bedrohungsexperten.  </li>
<li>  Konfiguration oder Schulung zur Überprüfung von SIEM-Verbindungen (API oder Security Information and Event Management).  </li>
<li>  Registrierung oder Konfiguration von Microsoft 365 Defender.  </li>
<li>  Schulungen oder Anleitungen für die erweiterte Suche.  </li>
<li>  Schulungen oder Anleitungen zur Verwendung oder Erstellung von Kusto-Abfragen.</li>
<li> Schulungen oder Anleitungen zur Defender SmartScreen-Konfiguration mithilfe von Gruppenrichtlinienobjekten (Group Policy Objects, GPOs), Windows-Sicherheit oder Microsoft Edge.</li>
</li>
</ul>
Wenden Sie sich an einen <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft-Partner,</a> um Unterstützung bei diesen Diensten zu erhalten.  
</ul></td>
<td></td>

<tr class="odd">
<td><strong>Microsoft Defender for Identity </strong></td>
<td>  Microsoft Defender for Identity ist eine cloudbasierte Sicherheitslösung, die Ihre lokalen Active Directory-Signale nutzt, um komplexe Bedrohungen, kompromittierte Identitäten und bösartige, gegen Ihre Organisation gerichtete Insideraktionen zu identifizieren, zu erkennen und zu untersuchen. Wir bieten Remoteanleitungen für:
<ul>
<li>  Ausführen des Größenanpassungstools für die Ressourcenkapazitätsplanung. </li>
<li>   Erstellen Ihrer Instanz von Defender for Identity. </li>
<li>   Verbinden von Defender for Identity mit Active Directory. </li>

<li>  Bereitstellen des Sensors zum Erfassen und Analysieren des Netzwerkdatenverkehrs und Windows Ereignisse direkt von Ihren Domänencontrollern, einschließlich: </li>
<ul> 
<li>  Herunterladen des Sensorpakets. </li>
<li>  Konfigurieren des Sensors. </li>
<li>  Automatisches Installieren des Sensors auf dem Domänencontroller. </li>
<li>  Bereitstellen des Sensors in Ihrer Umgebung mit mehreren Gesamtstrukturen. </li>
<li> Konfigurieren des Windows-Ereignissammlers.</li>
</ul>
<li>  Konfigurieren des Portals, einschließlich: </li>
<ul>
<li> Integrieren von Defender for Identity in Microsoft Cloud App Security (Cloud App Security Lizenzierung ist nicht erforderlich). </li>
<li> Konfigurieren von Entitätstags.</li>
<li> Markieren vertraulicher Konten. </li>
<li> Empfangen von E-Mail-Benachrichtigungen für Integritätsprobleme und Sicherheitswarnungen. </li>
<li> Konfigurieren von Warnungsausschlüssen.  </li>
</ul>
<li> Bereitstellungsleitfaden, Konfigurationsunterstützung und Schulung zu:</li>
<ul>
<li> Grundlegendes zum Bericht zur Bewertung des Identitätssicherheitsstatus.</li>
<li> Grundlegendes zur Bewertung der Benutzeruntersuchungspriorität und des Bewertungsberichts "Benutzeruntersuchung".</li>
<li> Grundlegendes zum inaktiven Benutzerbericht.</li>
<li> Erläuterung der Korrekturoptionen für ein kompromittiertes Konto.</li>
</ul>
<li>  Durchführen der Migration von Advanced Threat Analytics (ATA) zu Defender for Identity. </li>
</ul>
<p><strong>Folgendes liegt außerhalb des Gültigkeitsbereichs</strong></p>
<ul>

<li> Projektmanagement der Problemlösungsaktivitäten des Kunden. </li>
<li> Fortlaufendes Management, Reaktion auf Bedrohungen und Behebung.  </li>
<li> Bereitstellen von Defender for Identity als Machbarkeitsstudie.</li>
<li> Unterstützung <a href=" /fasttrack/us-gov-appendix-overview">von GCC-High oder GCC-DoD (Office 365 US Government).</a></li>
<li> Bereitstellen oder Ausführen der folgenden Defender for Identity-Sensoraktivitäten: </li>
<ul>
<li> Manuelle Kapazitätsplanung. </li>
<li> Ausführen des Überwachungstool. </li>
<li> Bereitstellen des eigenständigen Sensors. </li>
<li> Bereitstellen auf Ad FS-Servern (Active Directory-Verbunddienste).
<li> Bereitstellen des Sensors mithilfe eines NIC-Teamadapters (Network Interface Card). </li>
<li> Bereitstellen des Sensors über ein Drittanbietertool. </li>
<li> Herstellen einer Verbindung mit dem Defender for Identity-Clouddienst über eine Webproxyverbindung. </li>
</ul>
<li> Konfigurieren des Microsoft-Kontos (MSA) in Active Directory.
<li> Erstellung und Verwaltung vontokens. </li>
<li> Aktivieren der Netzwerknamenauflösung (Network Name Resolution, NNR). </li>
<li> Konfiguration des Containers "Gelöschte Objekte".</li>
<li> Bereitstellungsleitfaden oder Schulung zu: </li>
<ul>
<li> Korrigieren oder Interpretieren verschiedener Warnungstypen und überwachter Aktivitäten.  </li>
<li> Untersuchen eines Benutzers, Computers, Pfads für laterale Bewegungen oder Entitäten. </li>
<li> Bedrohung oder erweiterte Suche. </li>
<li> Reaktion auf Vorfälle. </li>
</ul>
<li> Bereitstellen eines Lernprogramms zur Sicherheitswarnung für Defender for Identity. </li>
<li> Bereitstellen einer Benachrichtigung, wenn Defender for Identity verdächtige Aktivitäten erkennt, indem Sicherheitswarnungen über einen benannten Sensor an Ihren Syslog-Server gesendet werden.  </li>
<li> Konfigurieren von Defender for Identity zum Ausführen von Abfragen mithilfe des SAMR-Protokolls (Security Account Manager Remote), um lokale Administratoren auf bestimmten Computern zu identifizieren. </li>
<li> Konfigurieren von VPN-Lösungen zum Hinzufügen von Informationen aus der VPN-Verbindung zur Profilseite eines Benutzers.  </li>
<li> SIEM-Integration (Security Information and Event Management) oder API-Integration (einschließlich Azure Sentinel). </li>
</ul></td>
<td><ul>
<li> Entspricht <a href="/defender-for-identity/prerequisites">den Voraussetzungen für Microsoft Defender for Identity.</a> </li>
<li>  Active Directory bereitgestellt.  </li>
<li>  Die Domänencontroller, auf denen Sie Defender for Identity-Sensoren installieren möchten, verfügen über eine Internetverbindung mit dem Defender for Identity-Clouddienst.  </li>
<ul>
<li> Ihre Firewall und Ihr Proxy müssen für die Kommunikation mit dem Defender for Identity-Clouddienst geöffnet sein (*.atp.azure.com Port 443 muss geöffnet sein).</li>
</ul>
<li> Domänencontroller, die auf einem der folgenden Arten ausgeführt werden:</li>
<ul>
<li> Windows Server 2008 R2 SP1.</li>
<li> Windows Server 2012.</li>
<li> Windows Server 2012 R2.</li>
<li> Windows Server 2016.</li>
<li> Windows Server 2019 mit KB4487044 (Os Build 17763.316 oder höher).</li>
</ul>
<li> Microsoft .NET Framework 4.7 oder höher.</li>
<li> Mindestens fünf (5) GB Speicherplatz sind erforderlich, und es werden 10 GB empfohlen.</li>
<li> Zwei (2) Kerne und sechs (6) GB RAM, die auf dem Domänencontroller installiert sind.</li>
</ul></td>
</tr>

<tr class="odd">
<td><strong>Microsoft Defender für Office 365</strong></td>
<td>  Microsoft Defender für Office 365 schützt Ihre Organisation vor bösartigen Bedrohungen durch E-Mail-Nachrichten, Links (URLs) und Tools für die Zusammenarbeit. Defender für Office 365 enthält:<ul>
<li> <a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#configure-microsoft-defender-for-office-365-policies"> Bedrohungsschutzrichtlinien:</a>Definieren Sie Richtlinien für den Bedrohungsschutz, um die entsprechende Schutzebene für Ihre Organisation festzulegen.</li>
<li> <a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#view-microsoft-defender-for-office-365-reports">Berichte:</a>Anzeigen von Echtzeitberichten, um Defender auf Office 365 Leistung in Ihrer Organisation zu überwachen.</li>
<li> <a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#use-threat-investigation-and-response-capabilities">Bedrohungsuntersuchung- und Antwortfunktionen</a> Verwenden Sie brandneue Tools, um Bedrohungen zu untersuchen, zu verstehen, zu simulieren und zu verhindern.</li>
<li> <a href="/microsoft-365/security/office-365-security/office-365-air?view=o365-worldwide">Automatisierte Untersuchungs- und Antwortfunktionen</a> Sparen Sie Zeit und Mühe beim Untersuchen und Beheben von Bedrohungen.</li>
</ul>

Wir bieten Remoteanleitungen für:  
<ul>
<li>  Aktivieren von sicheren Links, sicheren Anlagen und Antiphishing.  </li>
<li>  Konfigurieren von Automatisierung, Untersuchung und Reaktion.  </li>
<li>  Verwenden des Angriffssimulators.  </li>
<li>  Berichterstellung und Bedrohungsanalyse.  </li>
<li>  Grundlegendes zur Vorfallkorrelation im Microsoft 365 Defender-Portal.</li>
</ul>
<p><strong>Folgendes liegt außerhalb des Gültigkeitsbereichs</strong></p>
<ul>
<li> Projektmanagement der Problemlösungsaktivitäten des Kunden.</li>
<li> Fortlaufendes Management, Reaktion auf Bedrohungen und Behebung.</li>
<li> Unterstützung <a href=" /fasttrack/us-gov-appendix-overview">von GCC-High oder GCC-DoD (Office 365 US Government).</a></li>
<li> Diskussionen, in denen Defender für Office 365 mit anderen Sicherheitsangeboten verglichen wird.</li>
<li> Bereitstellen von Defender für Office 365 als Machbarkeitsstudie.</li>
<li> Verbinden von benutzerdefinierten Apps.</li>
<li> Schulungen oder Anleitungen für die erweiterte Suche.</li>
<li> Automatisierte Untersuchung und Behebung, einschließlich Microsoft Power Automate Playbooks.</li>
<li> SIEM-Integration (Security Information and Event Management) oder API-Integration (einschließlich Azure Sentinel).</li>
</ul>
</td>
<td>Abgesehen vom <strong>Core-Onboarding-Teil</strong> im <a href="#general">Allgemeinen</a>gibt es keine Mindestsystemanforderungen.</td>
</tr>


<tr class="even">
<td><strong>Microsoft Information Governance</strong></td>

<td>  Wir bieten Remoteanleitungen für:
<ul>
<li>  Erstellen und Veröffentlichen von Aufbewahrungsbezeichnungen und -richtlinien (wird nur in E5 unterstützt).  
</li>
<li>  Datensatzverwaltung (wird nur in E5 unterstützt).  </li>
<ul><li>  Überprüfen der Erstellung von Dateiplänen. </li>
<li>  Erstellen und Verwalten von Datensätzen (einschließlich ereignisbasierter Datensätze).  </li>
<li>  Überprüfen der Disposition. </ul> </li>
</ul>

<strong> Compliance-Manager</strong>

Wir bieten Remoteanleitungen für:  

<ul> <li>Überprüfen von Rollentypen.  </li>
<li> Hinzufügen und Konfigurieren von Bewertungen.</li>
<li> Bewertung der Compliance durch Implementierung von Verbesserungsmaßnahmen und Bestimmen, wie sich dies auf Ihre Compliancebewertung auswirkt.</li>
<li> Überprüfen der integrierten Steuerelementzuordnung und -bewertung von Steuerelementen.</li>
<li> Generieren eines Berichts innerhalb einer Bewertung.</li>
</ul>

  <strong>Folgendes liegt außerhalb des Gültigkeitsbereichs </strong>  
<ul>
<li> Entwicklung eines Datensatzverwaltungsdateiplans.</li>
<li> Datenkonnektoren.</li>
<li> Entwicklung der Informationsarchitektur in SharePoint.</li>
<li> Benutzerdefiniertes Skripting und Codierung.</li>
<li> Entwurfs-, Architektur- und Drittanbieterdokumentüberprüfung.</li>
<li> Unterstützung für E3.</li>
<li> Einhaltung von Branchen- und regionalen Vorschriften und Anforderungen.</li>
<li> Praktische Implementierung empfohlener Verbesserungsmaßnahmen für Bewertungen im Compliance-Manager.</li>
</ul>

</td>
<td>Abgesehen vom <strong>Core-Onboarding-Teil</strong> im <a href="#general">Allgemeinen</a>gibt es keine Mindestsystemanforderungen.</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Information Protection</strong></td>
<td>  Wir bieten Remoteanleitungen für:
<ul>
<li>  Datenklassifizierung (unterstützt in E3 und E5).  </li>
<li>  Typen vertraulicher Informationen (unterstützt in E3 und E5).  </li>
<li>  Erstellen von Vertraulichkeitsbezeichnungen (unterstützt in E3 und E5).  </li>
<li>  Anwenden von Vertraulichkeitsbezeichnungen (unterstützt in E3 und E5).  </li>
<li>  Trainierbare Klassifizierer (unterstützt in E5).  </li>
<li>  Kennen Sie Ihre Daten mit dem Inhalts-Explorer und dem Aktivitäten-Explorer (unterstützt in E5).  </li>
<li>  Veröffentlichen von Bezeichnungen mithilfe von Richtlinien (manuell und automatisch) (unterstützt in E5).  </li>
<li>  Erstellen von DLP-Richtlinien (Endpoint Data Loss Prevention) für Windows 10-Geräte (unterstützt in E5).  </li>
<li>  Erstellen von DLP-Richtlinien für Microsoft Teams-Chats und -Kanäle.  </li>
</ul>

<strong> Compliance-Manager</strong>

Wir bieten Remoteanleitungen für:  

<ul> <li>Überprüfen von Rollentypen.  </li>
<li> Hinzufügen und Konfigurieren von Bewertungen.</li>
<li> Bewertung der Compliance durch Implementierung von Verbesserungsmaßnahmen und Bestimmen, wie sich dies auf Ihre Compliancebewertung auswirkt.</li>
<li> Überprüfen der integrierten Steuerelementzuordnung und -bewertung von Steuerelementen.</li>
<li> Generieren eines Berichts innerhalb einer Bewertung.</li>
</ul>

<strong> Azure Information Protection</strong>

Wir bieten Remoteanleitungen für:  
<ul>
<li>  Aktivieren und Konfigurieren Ihres Mandanten.  </li>
<li>  Erstellen und Einrichten von Bezeichnungen und Richtlinien (unterstützt in P1 und P2).  </li>
<li>  Anwenden des Informationsschutzes auf Dokumente (unterstützt in P1 und P2).  </li>
<li>  Automatische Klassifizierung und Bezeichnung von Informationen in Office-Apps (z. B. Word, PowerPoint, Excel und Outlook), die unter Windows ausgeführt werden, und verwenden den Azure Information Protection-Client (unterstützt in P2).  </li>
<li>  Ermitteln und Bezeichnen von ruhenden Dateien mithilfe des Azure Information Protection-Scanners (unterstützt in P1 und P2).  </li>
<li>  Überwachung von E-Mails während des Versands unter Verwendung von Exchange Online Nachrichtenflussregeln.  </li>
</ul>

  Wir bieten auch Anleitungen, wenn Sie Schutz mithilfe von Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME) und Verhinderung von Datenverlust (Data Loss Prevention, DLP) anwenden möchten.

<strong>Folgendes liegt außerhalb des Gültigkeitsbereichs </strong>  
<ul>
<li>Kundenschlüssel.</li>
<li>RegEx-Entwicklung (Custom Regular Expressions) für typen vertraulicher Informationen.</li>
<li>Erstellen oder Ändern von Schlüsselwörterbüchern.</li>
<li>Benutzerdefiniertes Skripting und Codierung.</li>
<li> Azure Purview.</li>
<li> Entwurfs-, Architektur- und Drittanbieterdokumentüberprüfung.</li>
<li> Einhaltung von Branchen- und regionalen Vorschriften und Anforderungen.</li>
<li> Praktische Implementierung empfohlener Verbesserungsmaßnahmen für Bewertungen im Compliance-Manager.</li>
</ul>

<ul>

</td>
<td>Abgesehen vom <strong>Core-Onboarding-Teil</strong> im <a href="#general">Allgemeinen</a>gibt es keine Mindestsystemanforderungen mit Ausnahme von Azure Information Protection.

<strong>Azure Information Protection</strong>

Zu den Verantwortlichkeiten der Kunden gehören:  
<ul>
<li>  Eine Liste der zu scannenden Dateifreigabespeicherorte.  </li>
<li>  Eine genehmigte Klassifizierungstaxonomie. </li>
<li> Grundlegendes zu regulatorischen Einschränkungen oder Anforderungen in Bezug auf die Schlüsselverwaltung.  </li>
<li>  Ein für Ihr lokales Active Directory erstelltes Dienstkonto, das mit Azure AD synchronisiert wurde. </li>
<li>  Bezeichnungen, die für die Klassifizierung und den Schutz konfiguriert sind. </li>
<li> Alle Voraussetzungen für den Azure Information Protection-Scanner sind vorhanden. Weitere Informationen finden Sie unter <a href="/azure/information-protection/deploy-aip-scanner-prereqs">"Voraussetzungen für die Installation und Bereitstellung des Azure Information Protection-Scanners für einheitliche Bezeichnungen".</a> </li>
<li>  Stellen Sie sicher, dass auf Benutzergeräten ein unterstütztes Betriebssystem ausgeführt wird und die erforderlichen Komponenten installiert sind. Weitere Informationen finden Sie im Folgenden.</li>
<ul>
<li> <a href="/azure/information-protection/rms-client/clientv2-admin-guide-install">Administratorhandbuch: Installieren des Azure Information Protection-Clients für einheitliche Bezeichnungen für Benutzer</a>   </li>
<li>  <a href="/azure/information-protection/rms-client/mobile-app-faq">Was ist die Azure Information Protection-App für iOS oder Android?</a>  </li>
</ul>
<li> Installation und Konfiguration des Azure RMS-Connectors und der Server, einschließlich des Active Directory RMS (AD RMS)-Connectors für die Hybridunterstützung.  </li>
<li> Setup und Konfiguration von Bring Your Own Key (BYOK), Double Key Encryption (DKE) (nur Unified Labeling Client) oder Hold Your Own Key (HYOK) (nur klassischer Client), wenn Sie eine dieser Optionen für Ihre Bereitstellung benötigen.  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Wir bieten Remoteanleitungen für die Vorbereitung auf die Verwendung von Intune als cloudbasierter Anbieter für die Verwaltung mobiler Geräte (Mobile Device Management, MDM) und anbieter für die Verwaltung mobiler Apps (Mobile App Management, MAM) für Ihre Apps und Geräte. Die genauen Schritte hängen von Ihrer Quellumgebung ab und basieren auf dem Mobilgerät und den Anforderungen an die Verwaltung mobiler Apps. Die Schritte können Folgendes umfassen:
<ul>
<li>  Lizenzierung Ihrer Endbenutzer.  </li>
<li>  Konfigurieren von Identitäten, die von Intune verwendet werden sollen, indem Sie entweder Ihr lokales Active Directory oder Cloudidentitäten (Azure AD) nutzen.  </li>
<li>  Hinzufügen von Benutzern zu Ihrem Intune-Abonnement, Definieren von IT-Administratorrollen und Erstellen von Benutzer- und Gerätegruppen.  </li>
<li>  Konfigurieren Ihrer MDM-Autorität basierend auf Ihren Verwaltungsanforderungen, einschließlich:
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
<li>  Bereitstellung von E-Mail-, Drahtlosnetzwerken und VPN-Profilen, wenn Sie über eine vorhandene Zertifizierungsstelle, ein Drahtlosnetzwerk oder eine VPN-Infrastruktur in Ihrer Organisation verfügen.  </li>
<li>  Herstellen einer Verbindung mit dem Intune Data Warehouse.  </li>
<li>  Integration von Intune mit:
<ul>
<li>  Team Viewer für Remoteunterstützung (ein Team Viewer-Abonnement ist erforderlich).  </li>
<li>  Mobile Threat Defense (MTD)-Partnerlösungen (ein MTD-Abonnement ist erforderlich).  </li>
<li>  Eine Lösung für die Verwaltung von Telekommunikationsausgaben (ein Abonnement für die Verwaltung von Telekommunikationsausgaben ist erforderlich).  </li>

</ul></li>
<li>  Registrieren von Geräten jeder unterstützten Plattform bei Intune.  </li>
</ul></li>
</ul></li>
<li>  Bereitstellen von Anleitungen zum App-Schutz zu:
<ul>
<li>  Konfigurieren von App-Schutzrichtlinien für jede unterstützte Plattform.  </li>
<li>  Konfigurieren von Richtlinien für bedingten Zugriff für verwaltete Apps.  </li>
<li>  Ausrichtung auf die entsprechenden Benutzergruppen mit den zuvor erwähnten MAM-Richtlinien.  </li>
<li>  Verwenden von Nutzungsberichten für verwaltete Apps.  </li>
</ul></li>
<li>  Bereitstellen von Migrationsleitfäden von der älteren PC-Verwaltung zu Intune MDM.  </li>
</ul>
 
</li>
</ul>
  
<strong>Cloudanfügung</strong>  

  Wir führen Sie durch die Vorbereitung auf die Cloudanfügung vorhandener Configuration Manager-Umgebungen mit Intune. Die genauen Schritte hängen von der Quellumgebung ab. Die Schritte können Folgendes umfassen:  
<ul>
<li>  Lizenzierung Ihrer Endbenutzer.  </li>
<li>  Konfigurieren von Identitäten, die von Intune verwendet werden sollen, durch Nutzung Ihres lokalen Active Directory und von Cloudidentitäten.  </li>
<li>  Hinzufügen von Benutzern zu Ihrem Intune-Abonnement, Definieren von IT-Administratorrollen und Erstellen von Benutzer- und Gerätegruppen.  </li>
<li>  Bereitstellen von Anleitungen zum Einrichten der Hybrid-Azure AD-Verknüpfung.  </li>
<li>  Bereitstellen von Anleitungen zum Einrichten von Azure AD für die automatische MDM-Registrierung.  </li>
<li>  Bereitstellen von Anleitungen zum Einrichten des Cloudverwaltungsgateways, wenn es als Lösung für die Co-Verwaltung der internetbasierten Remotegeräteverwaltung verwendet wird.  </li>
<li>  Konfigurieren unterstützter Arbeitsauslastung, die Sie in Intune verschieben möchten.  </li>
<li>  Installieren des Configuration Manager-Clients auf Geräten, die bei Intune registriert sind.  </li>
</ul> 

<strong>Sichere Bereitstellung von Outlook Mobile für iOS und Android</strong> Wir unterstützen Sie bei der sicheren Bereitstellung von Outlook Mobile für iOS und Android in Ihrer Organisation, um sicherzustellen, dass Ihre Benutzer alle erforderlichen Apps installiert haben.  
  Die Schritte zum sicheren Bereitstellen von Outlook Mobile für iOS und Android mit Intune hängen von Ihrer Quellumgebung ab. Dies kann Folgendes umfassen:
<ul>
<li>  Herunterladen der Apps Outlook für iOS und Android, Microsoft Authenticator und Intune Company Portal über den Apple App Store oder Google Play Store.  </li>
<li>  Bereitstellen von Anleitungen für die Einrichtung:
<ul>
<li>  Die Bereitstellung von Outlook für iOS- und Android-, Microsoft Authenticator- und Intune Company Portal-Apps mit Intune.  </li>
<li>  App-Schutzrichtlinien.  </li>
<li>  Richtlinien für bedingten Zugriff.  </li>
<li>  App-Konfigurationsrichtlinien.  </li>
</ul></li>
</ul>  
  </td>
<td>  IT-Administratoren müssen über vorhandene Zertifizierungsstellen-, Drahtlosnetzwerk- und VPN-Infrastrukturen verfügen, die bereits in ihren Produktionsumgebungen arbeiten, wenn sie die Bereitstellung von Drahtlosnetzwerken und VPN-Profilen mit Intune planen.  
  <strong>Hinweis:</strong>Der FastTrack-Dienstvorteil umfasst keine Unterstützung beim Einrichten oder Konfigurieren von Zertifizierungsstellen, Drahtlosnetzwerken, VPN-Infrastrukturen oder Apple MDM-Pushzertifikaten für Intune.  
 
  <strong>Hinweis</strong>: Der FastTrack-Servicevorteil beinhaltet keine Unterstützung bei der Einrichtung oder Aktualisierung des Configuration Manager-Standortservers oder des Configuration Manager-Clients auf die Mindestanforderungen, die zur Unterstützung der Cloudanfügung erforderlich sind. Wenden Sie sich an einen <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft-Partner,</a> um Hilfe zu erhalten.

  <strong>In Microsoft Defender für Endpunkt integriertes Intune</strong> 
 
  <strong>Hinweis:</strong>Wir unterstützen Sie bei der Integration von Intune in Microsoft Defender für Endpunkt und beim Erstellen von Richtlinien zur Gerätecompliance basierend auf der Bewertung der Windows 10-Risikobewertung. Wir bieten keine Unterstützung beim Kauf, der Lizenzierung oder aktivierung. Wenden Sie sich an einen <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft-Partner,</a> um Hilfe zu erhalten.  
  
<strong>Windows Autopilot</strong> 
 
  IT-Administratoren sind für die Registrierung ihrer Geräte in ihrer Organisation verantwortlich, indem sie entweder den Hardware-Anbieter ihre Hardware-IDs in ihrem Namen hochladen lassen oder sie selbst in den Windows-Autopilot-Dienst hochladen.  
  
</td>
</tr>


</tbody>
</table>

## <a name="office-365"></a>Office 365

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
<td><strong>Exchange Online</strong></td>
<td>  Für Exchange Online führen wir Sie durch den Prozess, um Ihre Organisation auf die Verwendung von E-Mails vorzubereiten. Die genauen Schritte hängen von Ihrer Quellumgebung und Ihren E-Mail-Migrationsplänen ab.  
  Wir bieten Remoteanleitungen für:
<ul>
<li>  Einrichten von Exchange Online Protection (EOP)-Funktionen für alle E-Mail-aktivierten Domänen, die in Office 365 überprüft wurden.  </li>
<li>  Verweisen ihrer MX-Einträge (Mail Exchange) auf Office 365.  </li>
<li>  Einrichten des Microsoft Defender für Office 365-Features, wenn es Teil Ihres Abonnementdiensts ist. Weitere Informationen finden Sie im <strong>Microsoft Defender für Office 365-Teil</strong> dieser Tabelle.  </li>
<li>  Einrichten der Verhinderung von Datenverlust (Data Loss Prevention, DLP) für alle E-Mail-aktivierten Domänen, die in Office 365 als Teil Ihres Abonnementdiensts validiert wurden. Dies geschieht, sobald Ihre MX-Einträge auf Office 365 verweisen.</li>
<li>  Einrichten der Office 365-Nachrichtenverschlüsselung (OME) für alle E-Mail-aktivierten Domänen, die in Office 365 als Teil Ihres Abonnementdiensts validiert wurden. Dies geschieht, sobald Ihre MX-Einträge auf Office 365 verweisen.</li>
</ul>
  <strong>Hinweis:</strong> Der Postfachreplikationsdienst (Mailbox Replication Service, MRS) versucht, IRM-E-Mails (Information Rights Managed) von Ihrem lokalen Postfach in das entsprechende Exchange Online-Postfach zu migrieren. Die Möglichkeit, die geschützten Inhalte nach der Migration zu lesen, hängt von der Kundenzuordnung und dem Kopieren von AD RMS-Vorlagen (Active Directory Rights Managed Services) zum Azure RMS-Dienst (Azure Rights Management) ab.  
<ul>
<li>  Konfigurieren von Firewallports.  </li>
<li>  Einrichten von DNS, einschließlich der erforderlichen AutoErmittlung, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) und MX-Einträgen (je nach Bedarf).  </li>
<li>  Einrichten des E-Mail-Nachrichtenflusses zwischen Ihrer Quellmessagingumgebung und Exchange Online (bei Bedarf)  </li>
<li>  Durchführen der E-Mail-Migration von Ihrer Quellmessagingumgebung zu Office 365.  </li>
<li>  Konfigurieren von Postfach-Clients (Outlook für Windows, Outlook im Web und Outlook für iOS und Android).  </li>
</ul>
  <strong>Datenmigration</strong>  <br>
Informationen zur Verwendung des FastTrack-Vorteils für die Datenmigration zu Office 365 finden Sie unter <a href="/fasttrack/data-migration">"Datenmigration".</a>   
<td>  Ihre Quellumgebung muss über eine der folgenden Mindestebenen verfügen:
<ul>
<li>  Einzelne oder mehrere Exchange-Organisationen mit Exchange Server 2003 oder höher.  </li>
<li>  Einzelne IMAP-fähige E-Mail-Umgebung.  </li>
<li>  Eine einzelne G Suite-Umgebung (nur Gmail, Kontakte und Kalender).  </li>
<li>  Informationen zu Multi-Geo-Funktionen finden Sie unter <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo-Funktionen in Exchange Online.</a>  </li>
</ul>
Onlineclientsoftware wie Project für Office 365, Outlook für Windows, Outlook für iOS und Android, OneDrive for Business-Synchronisierungsclient, Power BI Desktop und Skype for Business muss mindestens so sein, wie in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">den Systemanforderungen für Microsoft 365 Office</a>definiert.  </td>
</tr>

<td><strong>Microsoft Defender für Office 365</strong></td>
<td>  Weitere Informationen finden Sie unter <strong>Microsoft Defender für Office 365</strong> in Sicherheit und <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance.</a>  
</td>
<td></td>
</tr>


<tr class="even">
<td><strong>Microsoft Information Governance</strong></td>
<td>  Weitere Informationen finden Sie unter <strong>Microsoft Information Governance</strong> in Security and <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance.</a> 

</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Microsoft Information Protection</strong></td>
<td>  
Weitere Informationen finden Sie unter <strong>Microsoft Information Protection</strong> in Sicherheit und <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance.</a>

</td>
<td>

</td>
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
<li>  Konfigurieren von Teams-App-Richtlinien (Teams-Web-App, Teams-Desktop-App und Teams für iOS- und Android-Apps).  </li>
</ul>
Gegebenenfalls stellen wir auch Anleitungen für Folgendes bereit:
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
<li>  Leitfaden zu Anrufplänen (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">verfügbare Märkte):</a>
<ul>
<li>  Zuweisung von Nummern zu lizenzierten Benutzern  </li>
<li>  Anweisung zum Portieren lokaler Rufnummern über die Benutzeroberfläche bis 999  </li>
<li>  SR-Unterstützung für das Portieren von lokalen Nummern über 999 hinaus  </li>
</ul></li>
<li>  Leitfaden für direct Routing:
<ul>
<li>  Anleitung zum Einrichten der Organisation für das Direct Routing-Design von vom Partner gehosteten Szenarien oder von Kunden bereitgestellte Szenarien für bis zu 10 Standorte.  </li>
<li> Überprüfung der Konfiguration des Session Border Controller (SBC). </li>

<li> Remoteunterstützung bei der Konfiguration des Wählplans. </li>

<li> VoIP-Routenkonfiguration.</li>

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
  <strong>Hinweis:</strong> Wenn Benutzer nicht mit SharePoint Online-Lizenzen zugewiesen und aktiviert sind, verfügen sie nicht über OneDrive for Business-Speicher in Office 365. Die Dateifreigabe funktioniert weiterhin in Kanälen, aber Benutzer können Dateien in Chats ohne OneDrive for Business-Speicher in Office 365 nicht freigeben. Teams unterstützt SharePoint nicht lokal.  <br>
  <strong>Hinweis:</strong> Der ideale Status ist, dass alle Benutzer ihre Postfächer in Exchange Online verwalten können. Benutzer mit lokalen Postfächern müssen ihre Identitäten über Azure AD Connect mit dem Office 365-Verzeichnis synchronisiert haben. Wenn sich das Postfach des Benutzers lokal befindet, kann der Benutzer für diese Exchange-Hybridkunden keine Connectors hinzufügen oder konfigurieren.  
  Die Installationsprogramme für die Windows- und Mac-Desktop-Clients von Microsoft Teams können unter <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> heruntergeladen werden.  </td>
</tr>

<tr class="even">
<td><strong>Outlook für iOS und Android</strong></td>
<td>  Wir bieten Remoteanleitungen für:
<ul>
<li>  Herunterladen von Outlook für iOS und Android über den Apple App Store und Google Play  </li>
<li>  Konfigurieren von Konten und Zugreifen auf das Exchange Online-Postfach  </li>
<li>  Schützen von Outlook Mobile (weitere Informationen finden Sie unter <a href="/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">"Schützen von Outlook für iOS und Android in Exchange Online").</a>  </li>
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
<td>Onlineclientsoftware wie Power BI Desktop muss mindestens so sein, wie sie in den <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Systemanforderungen für Microsoft 365 und Office</a>definiert ist.</td>
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
<td>Onlineclientsoftware wie Project für Office 365 muss auf einer Mindestebene sein, die in den <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Systemanforderungen für Microsoft 365 und Office</a>definiert ist.</td>
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
<td>Onlineclientsoftware wie Project für Office 365 muss auf einer Mindestebene sein, die in den <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Systemanforderungen für Microsoft 365 und Office</a>definiert ist.</td>
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
Je nach Ihrer SharePoint-Version werden weitere Anleitungen für OneDrive for Business bereitgestellt, z. B.:
<ul>
<li>  Identifizieren von Integrationsoptionen und Überprüfen der lokalen und Onlinenetzwerkinfrastruktur und Bandbreite.  </li>
<li>  Installieren von SharePoint Online 2013 SP1 (falls zutreffend), Planen und Implementieren von Synchronisierungs- und Identitätsanforderungen sowie Identifizieren Ihres OneDrive for Business-Synchronisierungsclients.  </li>
<li>  Planen und Implementieren eines einzelnen Rollouts für alle Benutzer (oder ein phasenweises Rollout).  </li>
<li>  Zuweisen von Lizenzen, Umleiten von "Meine Websites" und persönlichen Dokumentbibliotheken zu Office 365 (gilt für SharePoint Online 2013), Einrichten von Benutzergruppen zum Steuern des Zugriffs auf OneDrive (gilt für SharePoint Online 2013).  </li>
<li>Umleiten oder Verschieben bekannter Ordner zu OneDrive.</li>
<li>  Bereitstellen der OneDrive for Business-Clientsynchronisierung.  </li>
</ul>
  <strong>Datenmigration</strong>  <br>
Informationen zur Verwendung des FastTrack-Vorteils für die Datenmigration zu Office 365 finden Sie unter <a href="/fasttrack/data-migration">"Datenmigration".</a>
</ul></td>
<td><br><strong>Für SharePoint-Hybridbereitstellung:</strong>  
<ul>
<li>  Die SharePoint-Hybridkonfiguration umfasst das Konfigurieren der Hybridsuche, Websites, Taxonomie, Inhaltstypen, OneDrive for Business, ein erweitertes App-Startfeld, Extranetwebsites und self-service site creation connected from on-premises to a single target SharePoint Online environment.  </li>
</ul>
  <strong>Hinweis:</strong> Self-Service Site Creation ist nicht im Bereich mit lokalen Servern, auf denen SharePoint 2013 ausgeführt wird.  
<ul>
<li>  Zum Aktivieren der SharePoint-Hybridbereitstellung benötigen Sie eine der folgenden lokalen SharePoint Server-Umgebungen: 2013, 2016 oder 2019.  </li>
</ul>
  <strong>Hinweis:</strong> Das Upgrade von lokalen SharePoint-Umgebungen auf SharePoint Server ist nicht im Bereich. Wenden Sie sich an einen <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft-Partner,</a> um Unterstützung zu erhalten. Weitere Informationen finden Sie unter <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimale öffentliche Updateebenen für SharePoint-Hybridfeatures.</a><em></em>  <br>
  <strong>Hinweis:</strong> Informationen zu Multi-Geo-Funktionen finden Sie unter <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo-Funktionen in OneDrive und SharePoint Online in Office 365.</a><em></em>  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td>
Wir bieten Remoteanleitungen zum Aktivieren des Yammer Enterprise-Diensts.  
</td>
<td>Die Onlineclientsoftware muss mindestens so sein, wie sie in den <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Systemanforderungen für Microsoft 365 und Office</a>definiert ist.</td>
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
<td>  Weitere Informationen finden Sie unter <strong>Azure Active Directory (Azure AD) und Azure AD Premium</strong> in Sicherheit und <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance.</a></td>
<td></td>
</tr>
<tr class="odd">#Sicherheit und Compliance
<td><strong>Azure Information Protection </strong></td>
<td>  Weitere Informationen zu Azure Information Protection finden Sie unter <strong>Microsoft Information Protection</strong> in Sicherheit und <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance.</a>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Weitere Informationen finden Sie unter <strong>Microsoft Intune</strong> in Sicherheit <a href="/fasttrack/products-and-capabilities#security-and-compliance">und Compliance.</a>
  </td>
<td>  
  
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
<li>  Bewerten Der Quellumgebung und der Anforderungen (stellen Sie sicher, dass Microsoft Endpoint Configuration Manager auf die erforderliche Ebene aktualisiert wird, um die Windows 10-Bereitstellung zu unterstützen).  </li>
<li>  Bereitstellen von Windows 10 Enterprise und Microsoft 365 Apps mit Microsoft Endpoint Configuration Manager oder Microsoft 365.  </li>
<li>  Es werden Optionen für die Bewertung Ihrer Windows 10-Apps empfohlen.  </li>
<li>  Aktivieren der Verwendung von Desktop Analytics und Anleitungen durch die Erstellung eines Desktop Analytics-Bereitstellungsplans.  </li>
<li>  Microsoft 365 Apps-Kompatibilitätsbewertung durch Nutzung des Office 365-Bereitschaftsdashboards in Configuration Manager oder mit dem eigenständigen Readiness Toolkit für Office sowie Unterstützung bei der Bereitstellung von Microsoft 365-Apps.  </li>
<li>  Erstellen einer Prüfliste zur Problembehebung, was Sie tun müssen, um Ihre Quellumgebung auf die Mindestanforderungen für eine erfolgreiche Bereitstellung zu bringen.  </li>
<li>  Bereitstellen von Upgrade-Anleitungen für Ihre vorhandenen Geräte auf Windows 10 Enterprise, wenn sie die erforderlichen Gerätehardwareanforderungen erfüllen.  </li>
<li>  Bereitstellen von Upgrade-Anleitungen zur Unterstützung Ihrer vorhandenen Bereitstellungsbewegung. FastTrack bietet Empfehlungen und Anleitungen für ein direktes Upgrade auf Windows 10. Anleitungen stehen auch für eine Windows-Clean Image-Installation und Windows Autopilot-Bereitstellungsszenarien zur Verfügung.  </li>
<li>  Bereitstellen von Microsoft 365-Apps mit Configuration Manager als Teil der Windows 10-Bereitstellung.   </li>
<li>  Bereitstellen von Anleitungen, die Ihrer Organisation helfen, mit Windows 10 Enterprise und Microsoft 365 Apps über Ihre vorhandene Configuration Manager-Umgebung oder Microsoft 365 auf dem laufenden zu bleiben.  </li>
</ul>
  
<strong>Folgendes liegt außerhalb des Gültigkeitsbereichs </strong>  
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
Wenden Sie sich an einen <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft-Partner,</a> um Unterstützung bei diesen Diensten zu erhalten.  </td>
<td>  Für ein PC-Upgrades müssen Sie die folgenden Voraussetzungen erfüllen:
<ul>
<li>  Quellbetriebssystem: Windows 7 Enterprise oder Professional, Windows 8.1 Enterprise oder Professional.  </li>
<li>  Geräte: Desktop-, Notizbuch- oder Tablet-Formfaktor.  </li>
<li>  Zielbetriebssystem: Fenster 10 Enterprise.  </li>
</ul>
Für ein Infrastrukturupgrade müssen Sie diese Voraussetzungen erfüllen:
<ul>
<li>  Microsoft Endpoint Configuration Manager.  </li>
<li>  Die Configuration Manager-Version muss von der Windows 10-Zielversion unterstützt werden. Weitere Informationen finden Sie in der Configuration Manager-Tabelle der unterstützten Versionen unter <a href="/sccm/core/plan-design/configs/support-for-windows-10">Unterstützung für Windows 10 in Configuration Manager</a>.  </li>
</ul>

<tr class="odd">
<td><strong>Microsoft Defender für Endpunkt</strong></td>
<td>  Weitere Informationen finden Sie unter <strong>Microsoft Defender für Endpunkt</strong> in Sicherheit und <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance.</a></td>
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
<td><p>Wir bieten Bereitstellungsleitfaden für das Onboarding in Windows Virtual Desktop (einem Desktop- und App-Virtualisierungsdienst). Windows Virtual Desktop nutzt die Multisitzungserfahrung von Windows 10 und ist für Microsoft 365 Apps for Enterprise mit integrierter Sicherheit und Verwaltung für Microsoft 365 optimiert.</p>
<p>Wir bieten Remoteanleitungen für:</p>
<ul>
<li>Bereitstellen von Windows 10 Enterprise mit mehreren Sitzungen und Microsoft 365 Apps for Enterprise mit den folgenden Komponenten:
<ul>
<li>Azure Marketplace-Image.</li>
<li>Freigegebenes Bild.</li>
<li>Office Deployment Toolkit (ODT).</li>
</ul></li>
<li>Konfigurieren von Microsoft 365 Apps für FSLogix in einem systemeigenen Windows Virtual Desktop. Für FSLogix:
<ul>
<li>Bereitstellen des Agents.</li>
<li>Konfigurieren von Profil- und Office-Containern.</li>
<li>Konfigurieren von Inhaltsausschlüssen und Ordnerumleitungen für Microsoft 365-Apps.</li>
</ul></li>
<li>Bereitstellen von Microsoft Edge.</li>
<li>Bereitstellen von Microsoft Teams mit Optimierung.</li>
</ul>

<strong>Folgendes liegt außerhalb des Gültigkeitsbereichs</strong>
<ul>
<li>Projektmanagement der Windows Virtual Desktop-Infrastrukturbereitstellung des Kunden.</li>
<li>Virtualisierung und Bereitstellung von Drittanbieter-Apps.</li>
<li>Erstellen von benutzerdefinierten Images für Windows Virtual Desktop.</li>
<li>Migrationen und Szenarien, an denen VMware und Citrix beteiligt sind.</li>
<li>Linux-Szenarien.</li>
<li>Konvertierung oder Migration von Benutzerprofilen.</li>
<li>Konfiguration von Microsoft Endpoint Configuration Manager und Microsoft Endpoint Manager für Windows Virtual Desktop (einschließlich Patching und Verwaltung). </li>
<li>Microsoft 365 Defender mit Windows 10 mit mehreren Sitzungen.</li>
</ul>
Wenden Sie sich an einen <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft-Partner,</a> um Unterstützung bei diesen Diensten zu erhalten.</td>
<td>Sie sollten bereits über Folgendes verfügen:
<ul>
<li><a href="/azure/virtual-desktop/overview#requirements">Lizenzierungsanforderungen für Windows Virtual Desktop.</a></li>
<li> Die <a href="/azure/virtual-desktop/overview">erforderliche Infrastruktur zur Unterstützung von Windows Virtual Deskstop.</a> </li>
<ul>
<li><a href="/azure/virtual-desktop/store-fslogix-profile">Speicher für FSLogix-Profilcontainer in Windows Virtual Deskstop.</a> </li>
</ul>
<li>Azure-Netzwerke:
<ul>
<li>Erstellen und Subnetz von virtuellen Netzwerken (Virtual Network, VNET).</li>
<li>Firewall- und Netzwerksicherheitsgruppen.</li>
<li>VPN und ExpressRoute.</li>
<li>Routing von der lokalen Bereitstellung zu Azure.</li>
<li>Firewallregeln, um die Verbindung mit Windows Virtual Desktop zu ermöglichen.
</ul>
Weitere Informationen finden Sie unter <a href="/azure/virtual-desktop/overview#supported-remote-desktop-clients">Unterstützte Remotedesktopclients.</a>
</ul>
<ul><li>Allgemeines Azure AD-Setup:
<ul>
<li>Identitätsstrategie <i>(Sie können nur eine der folgenden drei Optionen verwenden):</i>
<ul>
<li>Active Directory mit Azure AD Connect in Azure.</li>
<li>Active Directory mit azure AD Connect lokal über VPN oder ExpressRoute.</li>
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
<td>  App Assure ist ein Dienst zur Behebung von Problemen mit der Windows 10- und Microsoft 365 Apps-App-Kompatibilität. Wenn Sie den App Assure-Dienst anfordern, arbeiten wir mit Ihnen daran, gültige App-Probleme ohne zusätzliche Kosten für Sie mit einem berechtigten Abonnement zu beheben. Wir bieten auch Anleitungen für Kunden, die bei der Bereitstellung von Windows Virtual Desktop und Microsoft Edge Mit Kompatibilitätsproblemen konfrontiert sind, und unternehmen alle angemessenen Anstrengungen, um Kompatibilitätsprobleme zu beheben. Wir bieten Unterstützung bei der Problembehebung für Apps, die in den folgenden Microsoft-Produkten bereitgestellt werden:
<ul>
<li>  <strong>Windows 10 </strong> (einschließlich ARM64-Geräten)</li>
<li> <strong>Microsoft 365-Apps</strong>  </li>
<li>  <strong>Microsoft Edge –</strong> Anleitungen zur Bereitstellung finden Sie unter <a href="/DeployEdge/microsoft-edge-channels">"Übersicht über die Microsoft Edge-Kanäle".</a>  </li>
<li>  <strong>Windows Virtual Desktop</strong> - Weitere Informationen finden Sie unter <a href="/azure/virtual-desktop/overview">Was ist Windows Virtual Desktop?</a> und Windows <a href="/azure/virtual-desktop/windows-10-multisession-faq">10 Enterprise multi-session FAQ</a>.  </li>
</ul>

<strong>Folgendes liegt außerhalb des Gültigkeitsbereichs </strong>  
<ul>
<li>  App-Bestandserfassung und Tests dazu, was unter Windows 10 und Microsoft 365 Apps funktioniert und was nicht. Weitere Hilfestellung zu diesem Vorgang, finden Sie im <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Bereitstellungscenter für Desktop</a>. Wenn Sie an einer detaillierten Upgradebereitschaftsbewertung interessiert sind, füllen Sie das Formular <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Kundenanforderung auf Bewertung der Bereitschaft für den modernen Desktop</a> aus.</li>
<li>  Untersuchen von ISV-Apps von Drittanbietern auf Windows 10-Kompatibilität und Supportanweisungen. Weitere Informationen finden Sie unter <a href="/sccm/desktop-analytics/overview">Desktopanalysen</a>.</li>
<li>Dienste nur für das App-Packaging. Das Desktop App Assure-Team paketiert jedoch Apps, für die alle Probleme für Windows 10 behoben wurden, um sicherzustellen, dass sie in der Umgebung des Kunden bereitgestellt werden können.</li>
</ul>

<strong>Zu den Zuständigkeiten des Kunden gehören:</strong>  
<ul>
<li>  Erstellen eines App-Inventars.</li>
<li>  Überprüfen der Apps unter Windows 10 und Microsoft 365 Apps.</li>
</ul>
<strong>Hinweis:</strong>  Microsoft kann keine Änderungen an Ihrem Quellcode vornehmen. Das Desktop App Assure-Team kann jedoch App-Entwickler beraten, wenn Quellcode für Ihre Apps verfügbar ist. 


  Wenden Sie sich an einen <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft-Partner,</a> um Unterstützung bei diesen Diensten zu erhalten.  </td>

</td>
<td><strong>Windows 10- und Microsoft 365-Apps</strong>
<ul>
<li>  
  Apps, die unter Windows 7, Windows 8,1, Office 2010 und Office 2013 funktioniert haben, funktionieren ebenfalls unter Windows 10 und Microsoft 365 Apps.  
  </li>
</ul>
<strong>Windows 10 auf ARM</strong>
<ul>
<li>  
Apps, die unter Windows 7, Office 2010 oder höher funktionierten, funktionieren auch unter Windows 10 und Microsoft 365 Apps auf ARM64-Geräten. 
  </li>
</ul>
  <strong>Hinweis:</strong> 
<ul>
<li> Die x64-Emulation (64-Bit) ist in der Vorschau für Kunden verfügbar, die am <a href="https://insider.windows.com/">Windows-Insider-Programm</a>teilnehmen.  </li>
<li>  
 Für Nicht-Windows-Insider-Kunden unter Windows 10, Version 2004 (oder höher), wird ARM64 Photoshop mithilfe von <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL und OpenGL Compatibility Pack</a>unterstützt. 
  </li>
<li>  
  Kunden des Windows-Insider-Programms können eine Insider-Version von OpenCL und OpenGL Compatibility Pack für die Verwendung mit zusätzlichen Apps herunterladen.    
  </li>
</ul>
<strong>Microsoft Edge</strong>
<ul>
<li>  
  Wenn Ihre Web-Apps oder -Websites mit Internet Explorer 11, unterstützten Versionen von Google Chrome oder einer beliebigen Version von Microsoft Edge funktionieren, funktionieren sie auch mit Microsoft Edge.  
  </li>
<li>  
  Da sich das Web ständig weiterentwickelt, überprüfen Sie unbedingt diese veröffentlichte Liste bekannter Änderungen, die sich auf die <a href="/microsoft-edge/web-platform/site-impacting-changes">Websitekompatibilität auswirken, für Microsoft Edge.</a>  
  </li>
</ul>
  <strong>Windows Virtual Desktop </strong>  
<ul>
<li>  
  Virtualisierte Apps, die auf dem Windows Server-Remotedesktop-Sitzungshost (RDSH) ausgeführt werden, können als Bestandteil von Windows Virtual Desktop auch unter Windows 10 Enterprise Multi-Session ausgeführt werden.  
  </li>
<li>  
  Apps, die in einer beliebigen Windows 7- oder Windows 10 Virtual Desktop Infrastructure (VDI)-Umgebung ausgeführt werden, werden auch unter Windows 7 Enterprise und Windows 10 Enterprise als Teil von Windows Virtual Desktop ausgeführt.  
  </li>
<li>  
  Apps, die unter Windows 7 oder Windows 10 auf Kundengeräten ausgeführt werden, können als Bestandteil von Windows Virtual Desktop auch unter Windows 7 Enterprise und Windows 10 Enterprise ausgeführt werden.  
  </li>
</ul>
  <strong>Hinweis:</strong> Windows 10 Enterprise- Kompatibilitätsausschlüsse und -einschränkungen für mehrere Sitzungen umfassen:
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
<th><strong>FastTrack Anleitungsdetails</strong></th>
<th><strong>Erwartungen an die Quellumgebung</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Microsoft Edge</strong> </td>
<td>
Wir bieten Remotebereitstellungs- und Einführungsleitfaden und Kompatibilitätsunterstützung für: <ul> <li>Bereitstellen von Microsoft Edge auf Windows 10 mit Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager oder Intune).  </li>
<li>  Konfigurieren von Microsoft Edge (mithilfe von Gruppenrichtlinien oder Intune-App-Konfiguration und App-Richtlinien).  </li>
<li>  Inventarisieren der Liste der Websites, die möglicherweise im Internet Explorer-Modus verwendet werden müssen.  </li>
<li>  Aktivieren des Internet Explorer-Modus mit der vorhandenen Enterprise Websiteliste. (Weitere Informationen finden Sie unter <a href="/fasttrack/process-and-expectations#engaging-fasttrack">"Ansprechende FastTrack".</a> Wenn Sie über eine Web-App oder Website verfügen, die mit Internet Explorer oder Google Chrome funktioniert und Kompatibilitätsprobleme auftreten, bieten wir außerdem Anleitungen, um das Problem ohne zusätzliche Kosten zu beheben. Um Kompatibilitätsunterstützung für App Assure anzufordern, melden Sie sich beim <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack-Portal</a> an, um ein Engagement zu starten.  </li>
<li> Planungsleitfaden für die Einführung und Konfiguration von Edge für Microsoft Search Lesezeichen.</li>
</ul>

<strong>Folgendes liegt außerhalb des Gültigkeitsbereichs </strong>  
<ul>
<li>Projektmanagement der Microsoft Edge-Bereitstellung des Kunden.</li>
<li>  Unterstützung vor Ort.</li>

</td>
<td></td>
</tr>
</tbody>
</table>
