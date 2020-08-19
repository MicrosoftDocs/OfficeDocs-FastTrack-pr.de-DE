---
title: Produkte und Funktionen
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: m365-administration
localization_priority: Priority
ms.collection: FastTrack
description: Dieses Thema enthält Details zu den von der Kurzhilfe unterstützten Arbeits Auslastungs Szenarien und den erforderlichen Anforderungen an die Quellumgebung, bevor wir beginnen können. Basierend auf Ihren aktuellen Einstellungen arbeiten wir mit Ihnen zusammen, um einen Korrektur Plan zu erstellen, der Ihre Quellumgebung auf die Mindestanforderungen für ein erfolgreiches Onboarding bringt.
ms.openlocfilehash: 1b1ffa5812905630723b5d8a23196fbbc18a9c32
ms.sourcegitcommit: 1b2242be54dd0d000c6384f45f18e1951c31998b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 08/18/2020
ms.locfileid: "46800967"
---
# <a name="products-and-capabilities"></a>Produkte und Funktionen

## <a name="services-and-scenarios-supported-by-fasttrack"></a>Von der Kurzfassung unterstützte Dienste und Szenarien

Dieses Thema enthält Details zu den von der Kurzhilfe unterstützten Arbeits Auslastungs Szenarien und den erforderlichen Anforderungen an die Quellumgebung, bevor wir beginnen können. Basierend auf Ihren aktuellen Einstellungen arbeiten wir mit Ihnen zusammen, um einen Korrektur Plan zu erstellen, der Ihre Quellumgebung auf die Mindestanforderungen für ein erfolgreiches Onboarding bringt.

In diesem Artikel finden Sie eine Anleitung, mit der Sie zunächst mit den wichtigsten Funktionen (gemeinsam für alle Microsoft Online Services) und dann mit dem Onboarding jedes berechtigten Diensts unterstützt werden:

  - [Allgemein](#general)
  - [Office 365](#office-365)
  - [Enterprise Mobility & Sicherheit](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [App Assure](Win-10-app-assure.md)
  - [Das neue Microsoft Edge](Win-10-microsoft-edge.md)

> [!NOTE]
> Informationen zu den Erwartungen der Quellumgebung für Office 365 US-Regierung finden Sie unter [Erwartungen der Quellumgebung für Office 365 US-Regierung](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).
 
## <a name="general"></a>Allgemein

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
<td><strong>Haupt-Onboarding</strong></td>
<td>  Wir bieten Remote-Anleitungen für das Onboarding von Kernen, die Service-Bereitstellung, Mandanten-und Identitätsintegration beinhalten. Es enthält auch Schritte zum Bereitstelleneiner Grundlage für Onboarding-Dienste wie Exchange Online, SharePoint Online und Microsoft Teams, einschließlich einer <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">Diskussion über Sicherheit, Netzwerkkonnektivität und Compliance</a>.  
  Das Onboarding für einen oder mehrere berechtigte Dienste kann beginnen, sobald das Haupt-Onboarding abgeschlossen ist.
</li>
</ul>  

<strong> Identitäts Integration </strong>

Wir bieten Remote-Anleitungen für:
<ul>
<li>Vorbereiten der lokalen Active Directory Identitäten für die Synchronisierung mit Azure Active Directory (Azure AD), einschließlich der Installation und Konfiguration von Azure AD Connect (Einzel-oder Multi-Gesamtstruktur) und Lizenzierung (einschließlich gruppenbasierter Lizenzierung).</li>
<li>Erstellen von Cloud-Identitäten einschließlich Massenimport und Lizenzierung einschließlich der Verwendung der gruppenbasierten Lizenzierung.</li>
<li>Auswählen und Aktivieren der richtigen Authentifizierungsmethode für Ihre Cloud-Reise, Kenn Wort Hash Synchronisierung, Pass-Through-Authentifizierung oder Active Directory Verbunddienste (AD FS).</li>
<li>Aktivieren von AD FS für Kunden mit einer einzelnen Active Directory Gesamtstruktur und mit dem Azure AD Connect-Tool synchronisierten Identitäten. Dies erfordert Windows Server 2012 R2 Active Directory Verbunddienste 2,0 oder höher.</li>
<li>Migrieren der Authentifizierung von AD FS zu Azure AD mit Kenn Wort Hash Synchronisierung oder Pass-Through-Authentifizierung.</li>
<li>Migrieren von vordefinierten Apps (wie Azure AD Gallery Software-as-a-Service (SaaS)-Apps) von AD FS zu Azure AD für einmaliges Anmelden (SSO).</li>
<li>Aktivieren von Saas-App-Integrationen mit SSO aus dem Azure AD-Katalog.</li>
<li>Aktivieren der automatischen Benutzer Bereitstellung für vorab integrierte SaaS-apps, wie in der <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">Liste der APP-Integrations Lernprogramm</a> aufgeführt (beschränkt auf Azure AD Gallery Saas-apps und nur ausgehende Bereitstellung).  </li>
</td>

<td>  <strong>Netzwerkaktivierung </strong>  
  <br>Im Rahmen des Kurzarbeits-Benefits empfehlen wir Ihnen, bewährte Methoden für die Verbindung mit Cloud-Diensten zu finden, um die höchste Leistung von Microsoft 365 sicherzustellen.  
  
<strong>Active Directory Gesamtstrukturen</strong> Auf diesen wird die Funktions Gesamtstrukturebene mit der folgenden Gesamtstrukturkonfiguration auf Windows Server 2003 festgelegt:
<ul>
<li>  Einzelne Active Directory-Gesamtstruktur  </li>
<li>  Eine einzelne Active Directory-Kontogesamtstruktur und Ressourcen-Gesamtstrukturtopologien (Exchange und/oder Lync 2010, Lync 2013 oder Skype for Business)  </li>
<li>  Mehrere Active Directory-Kontogesamtstrukturen und Ressourcen-Gesamtstrukturtopologien (Exchange und/oder Lync 2010, Lync 2013 oder Skype for Business)  </li>
<li>  Mehrere Active Directory-Kontogesamtstrukturen, wobei eine der Gesamtstrukturen eine Gesamtstruktur mit einem zentralen Active Directory-Konto ist, die Exchange und/oder Lync 2010, Lync 2013 oder Skype for Business umfasst.  </li>
<li>  Mehrere Active Directory-Konto-Gesamtstrukturen mit einer jeweils eigenen Exchange-Organisation  </li>
<li>  Bei Bedarf erforderliche Aufgaben für die Mandanten Konfiguration und die Integration in Azure Active Directory.   </li>
</ul>
  <strong>Wichtig</strong>  <ul>
<li>  Bei Szenarien mit mehreren Gesamtstrukturen Active Directory, wenn lync 2010, lync 2013 oder Skype for Business bereitgestellt wird, muss es in derselben Active Directory Gesamtstruktur wie Exchange bereitgestellt werden.  </li>
<li>  Bei der Implementierung mehrerer Active Directory Gesamtstrukturen mit mehreren Exchange-Organisationen in einer Exchange-Multi-Hybrid-Konfiguration werden freigegebene UPN-Namespaces (User Principal Name) zwischen Quell Gesamtstrukturen nicht unterstützt. Primäre SMTP-Namespaces zwischen Exchange-Organisationen sollten ebenfalls getrennt werden. Weitere Informationen finden Sie unter <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybridbereitstellungen mit mehreren Active Directory-Gesamtstrukturen</a>.  </li>
<li>  Bei allen Konfigurationen mit mehreren Gesamtstrukturen liegt die Bereitstellung von Active Directory Verbunddiensten (AD FS) außerhalb des Bereichs. Wenden Sie sich an einen <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft-Partner</a> , um Hilfe zu erhalten.  </li>
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
  Wenn Sie über ein Makro oder ein Add-in verfügen, das mit früheren Versionen von Office ausgeführt wurde und Kompatibilitätsprobleme auftreten, bieten wir Ihnen Anleitungen zur Behebung des Kompatibilitätsproblems ohne zusätzliche Kosten durch das App-Versicher-Programm. Weitere Informationen finden Sie im Abschnitt <strong>App-versichern</strong> von <a href="#windows-10">Windows 10</a> . </li>
</ul></td>
<td><ul>
<li>  Die Online-Client Software muss eine Mindeststufe aufweisen, die in den <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System Anforderungen für Microsoft 365 und Office</a>definiert ist.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Netzwerkintegrität</strong></td>
<td>  Wir bieten Remote-Anleitungen zum Abrufen und Interpretieren von wichtigen Netzwerk Verbindungsdaten aus Ihrer Umgebung, die zeigen, wie die Standorte Ihrer Organisation auf die Microsoft- <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">Grundsätze der Netzwerkkonnektivität</a>abgestimmt sind. Dadurch wird Ihr Netzwerk Ergebnis hervorgehoben, das sich direkt auf Migrations Geschwindigkeit, Benutzerfreundlichkeit, Dienstleistung und Zuverlässigkeit auswirkt.  
  Wir führen Sie auch durch alle Behebungsschritte, die durch diese Daten hervorgehoben werden, um Ihnen dabei zu helfen, Ihr Netzwerk Ergebnis zu verbessern.  </td>
<td><ul>
<li>  Microsoft 365 Admin Center-Zugriff.  </li>
<li>  Es sind aktuelle Versionen von Microsoft 365-apps erforderlich.  </li>
<li>  Die Standortdienste werden gemäß <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">den Empfehlungen zur Netzwerkleistung im Microsoft 365 Admin Center (Vorschau)</a>aktiviert.  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a>Office 365

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
<td><strong>Exchange Online</strong></td>
<td>  Für Exchange Online führen wir Sie durch den Prozess, um Ihre Organisation zur Verwendung von e-Mails zu nutzen. Die genauen Schritte hängen von ihrer Quellumgebung und Ihren e-Mail-Migrationsplänen ab.  
  Wir bieten Remote-Anleitungen für:
<ul>
<li>  Einrichten von Exchange Online Protection (EOP)-Funktionen für alle E-Mail-aktivierten Domänen, die in Office 365 überprüft wurden.  </li>
<li>  Verweist auf die MX-Einträge (Mail Exchange) auf Office 365.  </li>
<li>  Einrichten der Office 365 ATP-Funktion, wenn es sich um einen Teil Ihres Abonnement Diensts handelt. Weitere Informationen finden Sie im Abschnitt <strong>Office 365 Advanced Threat Protection</strong> dieser Tabelle.  </li>
<li>  Einrichten der Verhinderung von Datenverlust (Data Loss Prevention, DLP) für alle E-Mail-aktivierten Domänen, die in Office 365 als Teil Ihres Abonnementdiensts validiert wurden. Dies geschieht, sobald Ihre MX-Einträge auf Office 365 verweisen.</li>
<li>  Einrichten der Office 365-Nachrichtenverschlüsselung (OME) für alle E-Mail-aktivierten Domänen, die in Office 365 als Teil Ihres Abonnementdiensts validiert wurden. Dies geschieht, sobald Ihre MX-Einträge auf Office 365 verweisen.</li>
</ul>
  <strong>Hinweis:</strong> Der Postfachreplikationsdienst (Mailbox Replication Service, Mrs) versucht, IRM-e-Mails (Information Rights Managed) aus Ihrem lokalen Postfach in das entsprechende Exchange Online Postfach zu migrieren. Die Möglichkeit, die geschützten Inhalte nach der Migration zu lesen, hängt von der Kundenzuordnung und dem Kopieren von AD RMS-Vorlagen (Active Directory Rights Managed Services) zum Azure RMS-Dienst (Azure Rights Management) ab.  
<ul>
<li>  Konfigurieren von Firewallports.  </li>
<li>  Einrichten von DNS, einschließlich der erforderlichen AutoErmittlung, des Sender Policy Framework (SPF), der DomainKeys Identified Mail (DKIM), der domänenbasierten Nachrichtenauthentifizierung, Berichterstellung und Konformität (DMARC) und MX-Einträge (je nach Bedarf).  </li>
<li>  Einrichten des E-Mail-Nachrichtenflusses zwischen Ihrer Quellmessagingumgebung und Exchange Online (bei Bedarf)  </li>
<li>  Durchführen der E-Mail-Migration von Ihrer Quellmessagingumgebung zu Office 365.  </li>
<li>  Konfigurieren von Postfach-Clients (Outlook für Windows, Outlook im Web und Outlook für iOS und Android).  </li>
</ul>
  <strong>Datenmigration</strong>  <br>
Informationen zum Verwenden des Vorteile für die Migration von Daten zu Office 365 finden Sie unter <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Datenmigration</a>.   
<td>  Die Quellumgebung muss eine der folgenden Mindeststufen aufweisen:
<ul>
<li>  Einzelne oder mehrere Exchange-Organisationen mit Exchange Server 2003 oder höher.  </li>
<li>  Einzelne IMAP-fähige E-Mail-Umgebung.  </li>
<li>  Eine einzelne G Suite-Umgebung (nur Gmail, Kontakte und Kalender).  </li>
<li>  Informationen zu Multi-Geo-Funktionen finden Sie unter <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo-Funktionen in Exchange Online</a>.  </li>
</ul>
Online-Client Software wie Project für Office 365, Outlook für Windows, Outlook für IOS und Android, OneDrive für Unternehmen synchronisierungsclient, Power BI-Desktop und Skype for Business müssen eine Mindeststufe aufweisen, die unter <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System Requirements for Microsoft 365 Office</a>definiert ist.  </td>
</tr>
<tr class="even">
<td><strong>Microsoft Information Governance</strong></td>
<td>  Wir bieten Remote-Anleitungen für:
<ul>
<li>  Informationsverwaltung.  </li>
<li>  Aufbewahrungsbezeichnungen und Richtlinien.  </li>
<li>  Verwaltung von Unterlagen.  </li>
<li>  Löschungsrichtlinien.  </li>
<li>  Kommunikationscompliance.  </li>
<li>  Insider Risikomanagement.  </li>
<li>  Advanced eDiscovery.  </li>
</ul></td>
<td>Neben dem <strong>Haupt-Onboarding</strong> -Teil im <a href="#general">allgemeinen</a>gibt es keine minimalen Systemanforderungen.</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Information Protection</strong></td>
<td>  Wir bieten Remote-Anleitungen für:
<ul>
<li>  Datenklassifikation.  </li>
<li>  Typen vertraulicher Informationen.  </li>
<li>  Erstellen von Sensitivitäts Bezeichnungen.  </li>
<li>  Anwenden von Sensitivitäts Bezeichnungen.  </li>
<li>  Einheitliche Bezeichnungen.  </li>
<li>  Schulungs Klassifizierer.  </li>
<li>  Kennen ihrer Daten mit dem Inhalts-Explorer und dem Aktivitäts-Explorer.  </li>
<li>  Veröffentlichen von Bezeichnungen mithilfe von Richtlinien (manuell und automatisch).  </li>
<li>  Erstellen von Richtlinien zur Verhinderung von Datenverlust (DLP) für Microsoft Teams-Chats und-Kanäle.  </li>
</ul></td>
<td>Neben dem <strong>Haupt-Onboarding</strong> -Teil im <a href="#general">allgemeinen</a>gibt es keine minimalen Systemanforderungen.</td>
</tr>
<tr class="even">
<td><strong>Microsoft Teams</strong></td>
<td>  Wir bieten Remote-Anleitungen für:
<ul>
<li>  Bestätigen der Mindestanforderungen in Exchange Online, SharePoint Online, Office 365 Gruppen und Azure AD zur Unterstützung von Teams.  </li>
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
<li>  Konfigurieren von Teams-App-Richtlinien (Microsoft Teams-Webanwendung, Teams-Desktop-App und Teams für IOS-und Android-App)  </li>
</ul>
Wenn zutreffend, bieten wir auch Anleitungen für:
<ul>
<li>  Microsoft Teams-Raum Geräte:  </li>
</ul>
<ul>
<li>  Erstellung von Onlinekonten, die für unterstützte Telefonie-und Konferenzraum Geräte erforderlich sind, die im Microsoft <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams-Gerätekatalog</a>aufgeführt sind.  </li>
</ul>
<ul>
<li>  Aktivieren von Audiokonferenzen:  </li>
</ul>
<ul>
<li>  Organisationseinrichtung der Standardeinstellungen für Konferenzbrücke  </li>
<li>  Zuweisen der Konferenzbrücke zu lizenzierten Benutzern  </li>
</ul>
<ul>
<li>  Telefon System:
<ul>
<li>  Organisationseinrichtung der Standardeinstellungen für Cloud Voice  </li>
<li>  Leitfaden für Anrufpläne (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">Verfügbare Märkte</a>):
<ul>
<li>  Zuweisung von Nummern zu lizenzierten Benutzern  </li>
<li>  Anweisung zum Portieren lokaler Rufnummern über die Benutzeroberfläche bis 999  </li>
<li>  SR-Unterstützung für das Portieren von lokalen Nummern über 999 hinaus  </li>
</ul></li>
<li>  Leitfaden für das direkte Routing:
<ul>
<li>  Anleitung zum Einrichten der Organisation für das direkte Routing in von Partnern gehosteten Szenarien oder in kundenseitig bereitgestellten Szenarien für einen einzelnen Standort.  </li>
</ul></li>
</ul></li>
<li>  Aktivieren von Teams-Liveereignissen  </li>
<li>  Einrichten der Organisation und Integration in Microsoft Stream.  </li>
</ul></td>
<td><ul>
<li>  In Azure AD für Office 365 aktivierte Identitäten.  </li>
<li>  Aktivierte Benutzer für SharePoint Online.  </li>
<li>  Exchange-Postfächer sind vorhanden (Online und lokal in einer Exchange-Hybrid Konfiguration).  </li>
<li>  Für Office 365-Gruppen aktiviert.  </li>
</ul>
  <strong>Hinweis:</strong>   Wenn Benutzer nicht mit SharePoint Online Lizenzen zugewiesen und aktiviert werden, haben Sie OneDrive für Unternehmen Speicher in Office 365 nicht. Die Dateifreigabe funktioniert weiterhin in Kanälen, aber Benutzer können keine Dateien in Chats freigeben, ohne OneDrive für Unternehmen Speicher in Office 365. Microsoft Teams unterstützt keine lokale SharePoint-Bereitstellung.  <br>
  <strong>Hinweis:</strong>   Der ideale Status besteht darin, dass alle Benutzer ihre Postfächer in Exchange Online verwaltet haben. Benutzer mit Postfächern, die lokal verwaltet werden, müssen über Azure AD Connect Ihre Identitäten mit dem Office 365 Verzeichnis synchronisieren. Wenn das Postfach des Benutzers lokal ist, kann der Benutzer für diese Exchange-Hybrid Kunden keine Connectors hinzufügen oder konfigurieren.  
  Die Installationsprogramme für die Windows-und Mac-Desktop Clients von Microsoft Teams können unter heruntergeladen werden  <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> .  </td>
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
<tr class="even">
<td><strong>Outlook für iOS und Android</strong></td>
<td>  Wir bieten Remote-Anleitungen für:
<ul>
<li>  Herunterladen von Outlook für iOS und Android über den Apple App Store und Google Play  </li>
<li>  Konfigurieren von Konten und Zugreifen auf das Exchange Online-Postfach  </li>
<li>  Sichern von Outlook Mobile (Weitere Informationen finden Sie unter <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Sichern von Outlook für IOS und Android in Exchange Online</a> ).  </li>
</ul></td>
<td><ul>
<li>  In Azure AD für Office 365 aktivierte Identitäten.  </li>
<li>  Exchange Online konfiguriert und Lizenzen zugewiesen.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Power BI</strong></td>
<td>  Wir bieten Remote-Anleitungen für:
<ul>
<li>  Zuweisen von Power BI-Lizenzen.  </li>
<li>  Bereitstellen der Power BI Desktop-App.  </li>
</ul></td>
<td>Online-Client Software wie Power BI Desktop muss sich auf einem Mindestniveau befinden, das in den <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System Anforderungen für Microsoft 365 und Office</a>definiert ist.</td>
</tr>
<tr class="even">
<td><strong>Project Online</strong></td>
<td>  Wir bieten Remote-Anleitungen für:
<ul>
<li>  Überprüfen grundlegender SharePoint-Funktionen, auf denen Project Online basiert.  </li>
<li>  Hinzufügen des Project Online-Diensts zu Ihrem Mandanten (einschließlich des Hinzufügens von Abonnements zu Benutzern).  </li>
<li>  Einrichten des Enterprise-Ressourcenpools (ERP)  </li>
<li>  Erstellen Ihres ersten Projekts.  </li>
</ul></td>
<td>Online-Client Software wie Project für Office 365 muss auf einer Mindeststufe lauten, die in den <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System Anforderungen für Microsoft 365 und Office</a>definiert ist.</td>
</tr>
<tr class="odd">
<td><strong>Project Online Professional und Premium</strong></td>
<td>  Wir bieten Remote-Anleitungen für:
<ul>
<li>  Beheben von Problemen bei der Bereitstellung  </li>
<li>  Zuweisen von Endbenutzerlizenzen mit Microsoft 365 Admin Center und Windows PowerShell  </li>
<li>  Installieren von Project Online-Desktopclient aus dem Office 365-Portal mithilfe von Klick-und-Los  </li>
<li>  Konfigurieren von Updateeinstellungen mit dem Office 365-Bereitstellungstool  </li>
<li>  Einrichten eines einzelnen lokalen Verteilungsservers für Project Online-Desktopclient, einschließlich Unterstützung beim Erstellen einer configuration.xml-Datei für die Verwendung mit dem Office 365-Bereitstellungstool  </li>
<li>  Herstellen einer Verbindung zwischen Project Online-Desktopclient und Project Online Professional oder Project Online Premium.  </li>
</ul></td>
<td>Online-Client Software wie Project für Office 365 muss auf einer Mindeststufe lauten, die in den <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System Anforderungen für Microsoft 365 und Office</a>definiert ist.</td>
</tr>
<tr class="even">
<td><strong>SharePoint Online und OneDrive for Business</strong></td>
<td>  Wir bieten Remote-Anleitungen für:
<ul>
<li>  Einrichten von DNS  </li>
<li>  Konfigurieren von Firewallports.  </li>
<li>  Bereitstellen von Benutzern und Lizenzen.  </li>
<li>Aktivieren der Websiteerstellung für Ihren SharePoint Online-Administrator.</li>
<li>Planen von Websitesammlungen.</li>
<li>Sichern von Inhalten und Verwalten von Berechtigungen.</li>
<li>Konfigurieren von SharePoint Online-Features.</li>
<li>  Konfigurieren von SharePoint-Hybridfeatures, z. B. Hybridsuche, Hybridwebsites, Hybridtaxonomie, Inhaltstypen, Self-Service Site Creation für hybride Sites (nur SharePoint Server 2013), erweitertes App-Startfeld, Hybrid-OneDrive for Business und Extranet-Websites.  </li>
<li>  Migrationsansatz.  </li>
</ul>
Je nach SharePoint-Version werden zusätzliche Anleitungen für OneDrive für Unternehmen bereitgestellt, wie beispielsweise:
<ul>
<li>  Identifizieren von Integrationsoptionen und Überprüfen der lokalen und Online Netzwerkinfrastruktur und Bandbreite.  </li>
<li>  Installieren von SharePoint Online 2013 SP1 (falls zutreffend), planen und Implementieren von Synchronisierungs-und Identitäts Anforderungen und Identifizieren des OneDrive für Unternehmen Synchronisierungs Clients.  </li>
<li>  Planen und Implementieren eines einzelnen Rollouts für alle Benutzer (oder ein phasenweises Rollout).  </li>
<li>  Zuweisen von Lizenzen, Umleiten von Meine Websites und persönlichen Dokumentbibliotheken an Office 365 (gilt für SharePoint Online 2013), Einrichten von Benutzergruppen zur Steuerung des Zugriffs auf OneDrive (gilt für SharePoint Online 2013).  </li>
<li>Umleiten oder Verschieben von bekannten Ordnern in OneDrive.</li>
<li>  Bereitstellen der OneDrive für Unternehmen-Client Synchronisierung.  </li>
</ul>
  <strong>Datenmigration</strong>  <br>
Informationen zum Verwenden des Vorteile für die Migration von Daten zu Office 365 finden Sie unter <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Datenmigration</a>.
</ul></td>
<td><br><strong>Für SharePoint-Hybrid:</strong>  
<ul>
<li>  Die SharePoint-Hybrid Konfiguration umfasst das Konfigurieren von Hybrid Suche, Websites, Taxonomie, Inhaltstypen, OneDrive für Unternehmen, ein erweitertes App-Startfeld, Extranet-Websites und Self-Service Site Creation, die von einer lokalen zu einer einzelnen Ziel SharePoint Online Umgebung verbunden sind.  </li>
</ul>
  <strong>Hinweis:</strong> Self-Service Site Creation hat keinen Umfang mit lokalen Servern, auf denen SharePoint 2013 läuft.  
<ul>
<li>  Zum Aktivieren von SharePoint-hybridbereitstellung müssen Sie über eine der folgenden lokalen SharePoint Server Umgebungen verfügen: 2013, 2016 oder 2019.  </li>
</ul>
  <strong>Hinweis:</strong> Das Upgrade von lokalen SharePoint-Umgebungen auf SharePoint Server hat keinen Umfang. Wenden Sie sich an einen <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft-Partner</a> , um Hilfe zu erhalten. Weitere Informationen finden Sie unter <a href="https://go.microsoft.com/fwlink/?linkid=853548">minimale öffentliche Update Ebenen für SharePoint-Hybrid Features</a><em>.</em>  <br>
  <strong>Hinweis:</strong> Informationen zu Multi-Geo-Funktionen finden Sie unter <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo-Funktionen in OneDrive und SharePoint Online in Office 365</a><em>.</em>  </td>
</tr>
<tr class="odd">
<td><strong>Skype for Business Online</strong></td>
<td>  Wir bieten Remote-Anleitungen für:
<ul>
<li>  Konfigurieren von Firewallports.  </li>

<li>  Einrichten von DNS  </li>
<li>  Netzwerkbewertung:
<ul>
<li>  Überprüfungen hinsichtlich der Ports und Endpunkte  </li>
<li>  Überprüfungen hinsichtlich der Verbindungsqualität  </li>
<li>  Schätzungen hinsichtlich der Bandbreite  </li>
</ul></li>
<li>  Erstellen von Konten für jedes Raumsystemgerät  </li>
<li>  Bereitstellen eines unterstützten Skype for Business Online-Clients  </li>
<li>  Einrichten einer Serverkonfiguration für geteilte Domänen zwischen Ihrer lokalen Lync 2010-, Lync 2013- oder Skype for Business 2015-Serverumgebung und einem Skype for Business Online-Mandanten (falls zutreffend), Anrufplänen, Skype-Livekonferenzen und einem Telefonsystem und Anrufplänen (auf verfügbaren Märkten).  
  Wenn zutreffend, führt Sie auch die folgenden Schritte durch:  </li>
<li>  Konfigurieren des Raumsystem Geräts:
<ul>
<li>  Erstellung von Onlinekonten, die für unterstützte Konferenzraum Geräte erforderlich sind, die auf der Registerkarte "Besprechungsraum Systeme" im <a href="https://go.microsoft.com/fwlink/?LinkId=615775">Skype for Business Lösungskatalog</a>aufgeführt sind.  </li>
</ul></li>
<li>  Konfigurieren von Hybriden und geteilten Domänenservern.  </li>
<li>  Konfigurieren von Audiokonferenzen:
<ul>
<li>  Organisationseinrichtung der Standardeinstellungen für Konferenzbrücke  </li>
<li>  Zuweisen der Konferenzbrücke zu lizenzierten Benutzern  </li>
</ul></li>
<li>  Konfigurieren der Standardeinstellungen für das Telefon System:
<ul>
<li>  Anrufpläne:
<ul>
<li>  Zuweisung von Nummern zu Lizenzen für Benutzer.  </li>
<li>  Anleitung zur Portierung lokaler Rufnummern über die Benutzeroberfläche bis zu 99  </li>
<li>  Unterstützung für den lokalen Nummern Portierungs Dienst über 999  </li>
</ul></li>
</ul></li>
<li>  Konfigurieren Skype for Business Konferenz Übertragung:
<ul>
<li>  Organisationseinrichtung für den Verbund mit dem Livekonferenzdienst  </li>
</ul></li>
</ul></td>
<td>  <strong>Für lync Hybrid:</strong>  
<ul>
<li>  Einzelne lokale Active Directory-Gesamtstruktur.  </li>
<li>  Eine Lync 2010-Serverumgebung mit Lync 2013-Verwaltungstools oder Skype for Business 2015-Verwaltungstools und Lync 2010-Edge-Serverrolle.  </li>
<li>  Lync 2013-Serverumgebung und Lync 2013-Edge-Serverrolle.  </li>
</ul>
  <strong>Für Skype for Business Hybrid:</strong>  
<ul>
<li>  Einzelne lokale Active Directory-Gesamtstruktur.  </li>
<li>  Einzelne Active Directory-Konto-Gesamtstruktur und Ressourcen-Gesamtstrukturtopologien (Exchange und/oder Skype for Business)  </li>
<li>  Mehrere Active Directory-Kontogesamtstrukturen, wobei eine der Gesamtstrukturen eine Gesamtstruktur mit einem zentralen Active Directory-Konto mit Exchange und/oder Skype for Business ist.  </li>
<li>  Skype for Business Server 2015-Umgebung mit Skype for Business-Edge-Serverrolle.  </li>
</ul>
  <strong>Hinweis:</strong> Dieser zusätzliche Dienst dient zum Konfigurieren und Validieren von Hybrid Aufgaben (Split Domain) und beinhaltet nicht die Einführung lokaler Komponenten (beispielsweise lync 2013 Verwaltungstools oder lync 2013/Skype for Business Online-Servern oder lync 2010-, lync 2013-oder Skype for Business-Edgeserver).  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td><ul>
Wir bieten Remote-Anleitungen für das Aktivieren des jammern Enterprise-Diensts.  
</ul></td>
<td>Die Online-Client Software muss eine Mindeststufe aufweisen, die in den <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System Anforderungen für Microsoft 365 und Office</a>definiert ist.</td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>Enterprise Mobility & Sicherheit

<table>
<thead>
</tr>
<tr class="even">
<td><strong>Azure Active Directory (Azure AD) und Azure AD Premium</strong></td>
<td>  Wir bieten Remote Anleitungen zum Sichern Ihrer Cloud-Identitäten für die folgenden Szenarien.  

 <br/>

<strong>Secure Foundation-Infrastruktur</strong>  </ul>
<ul>
<li>  Konfigurieren und Aktivieren einer starken Authentifizierung für Ihre Identitäten, einschließlich des Schutzes mit der Azure Multi-Factor Authentication (MFA) (nur Cloud), der Microsoft Authenticator-APP und der kombinierten Registrierung für Azure MFA und Self-Service Password Reset (SSPR).  </li>
<li>  Für nicht Azure AD Premium-Kunden werden Anleitungen bereitgestellt, um Ihre Identitäten mit Sicherheitsstandards zu schützen.  </li>
<li>  Für Azure AD Premium-Kunden werden Anleitungen bereitgestellt, um Ihre Identitäten mit bedingtem Zugriff zu schützen.  </li>
<li>  Erkennen und Blockieren der Verwendung von schwachen Kennwörtern mit Azure AD Kennwortschutz.  </li>
<li>  Sichern von Remotezugriff auf lokale Webanwendungen mit Azure AD Anwendungs Proxy.  </li>
<li>  Aktivieren der risikobasierten Erkennung und Behebung mit Azure Identity Protection.  </li>
<li>  Aktivieren eines angepassten Anmeldebildschirms, einschließlich Logo, Text und Bilder mit benutzerdefiniertem Branding.  </li>
<li>  Sicheres Freigeben von apps und Diensten für Gastbenutzer, die Azure AD B2B verwenden.  </li>
<li>  Verwalten des Zugriffs für Ihre Office 365 Administratoren mithilfe integrierter rollenbasierter Zugriffssteuerung (Role-Based Access Control, RBAC) integrierte Administratorrollen und verringern der Anzahl von privilegierten Administratorkonten.  </li>
<li>  Konfigurieren von Hybrid Azure AD Join.  </li>
<li>  Konfigurieren Azure AD Joins.  </li>
</ul>
  
<strong>Überwachen und Berichten</strong>  
<ul>
<li>  
  Aktivieren der Remoteüberwachung für AD FS, Azure AD Connect und Domänencontroller mit Azure AD Connect Health.  
  </li>
</ul>
  
<strong>Governance</strong>  
<ul>
<li>  
  Verwalten des Azure AD Identitäts-und Zugriffs Lebenszyklus mit Azure AD Berechtigungsverwaltung im Maßstab.
  </li>
<li>  
  Verwalten von Azure AD Gruppenmitgliedschaften, Enterprise-App-Zugriff und Rollenzuweisungen mit Azure AD Zugriffsüberprüfungen.  
  </li>
<li>  
  Überprüfen Azure AD Nutzungsbedingungen.  
  </li>
<li>  
  Verwalten und Steuern des Zugriffs auf privilegierte Administratorkonten mit Azure AD privilegierten Identitätsverwaltung.  
  </li>
</ul>
  
<strong>Automatisierung und Effizienz </strong>  
<ul>
<li>  
  Aktivieren Azure AD SSPR.  
  </li>
<li>  Ermöglicht Benutzern das Erstellen und Verwalten Ihrer eigenen Cloud-Sicherheit oder Office 365 Gruppen mit Azure AD Self-Service-Gruppenverwaltung.  </li>
<li>  Verwalten von delegiertem Zugriff auf Enterprise-apps mit Azure AD Delegierter Gruppenverwaltung.  </li>
<li>  Aktivieren Azure AD dynamischer Gruppen.  </li>
<li>  Organisieren von apps im My apps-Portal mithilfe von Auflistungen.  </li>
</ul></td>
<td>Der lokale Active Directory und seine Umgebung wurden auf Azure AD Premium vorbereitet, einschließlich der Behebung identifizierter Probleme, die die Integration in Azure AD und Azure AD Premium Features verhindern.</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection (P2 oder EMS E5)</strong></td>
<td>  Wir bieten Anleitungen zu folgenden Themen:
<ul>
<li>  Aktivieren und konfigurieren Sie den Mandanten.  </li>
<li>  Erstellung und Einrichtung von Bezeichnungen und Richtlinien.  </li>
<li>  Anwendung von Informationsschutz auf Dokumente.  </li>
<li>  Automatische Klassifizierung und Bezeichnung von Informationen in Office-Apps (wie Word, PowerPoint, Excel und Outlook), die unter Windows ausgeführt werden und den Azure Information Protection-Client verwenden.  </li>
<li>  Verwendung von ruhenden Dateien mithilfe des Azure Information Protection Scanners.  </li>
<li>  Überwachung von E-Mails während der Übertragung unter Verwendung von Exchange Online-Nachrichtenflussregeln.  </li>
</ul>
Wir bieten auch Anleitungen, wenn Sie den Schutz mit Microsoft Azure Rights Management Services (Azure RMS), der Office 365-Nachrichtenverschlüsselung (OM) und der Verhinderung von Datenverlust (DLP) anwenden möchten.  </td>
<td>  Sie sollten bereits Folgendes tun:
<ul>
<li>  Verwenden Sie Azure AD.  </li>
<li>  Verwenden Sie entweder Windows oder IOS (andere Betriebssysteme liegen außerhalb des Bereichs).  
  </ul>
<strong>Hinweis</strong>: Computer und mobile Geräte müssen unter einem <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">Betriebssystem</a> ausgeführt werden, das Azure Information Protection unterstützt.  
<li>  Haben Sie Ihre wichtigsten Dateifreigabe Speicherorte.  </li>
<strong>Hinweis</strong>: für die Hybrid Unterstützung ist der AD RMS-Connector erforderlich. 
<li>  Verfügen über eine genehmigte Klassifizierungs Taxonomie.  </li>
<li>  Verstehen Sie alle behördlichen Einschränkungen für ihre geschützte Schlüsselverwaltung.  </li>
</ul>
  
<strong>Azure Information Protection-Scanner</strong>  
  
Sie sollten bereits Folgendes tun:  
<ul>
<li>  Verwenden Sie Windows Server 2012 R2 oder Windows Server 2016.  </li>
<li>  Über eine Internetverbindung verfügen.  </li>
<li>  Haben Sie Microsoft SQL Server 2012 in einer lokalen oder Remoteinstanz.  </li>
<li>  Lassen Sie ein Dienstkonto für Ihre lokale Active Directory erstellt und mit Azure AD synchronisiert.  </li>
<li>  AzInfoProtection.exe heruntergeladen haben.  </li>
<li>  Haben Sie Bezeichnungen für die automatische Klassifizierung/den Schutz konfiguriert.  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Wir bieten Anleitungen zur Vorbereitung der Verwendung von InTune als Cloud-basierter Anbieter für Mobile Geräteverwaltung (MDM) und Mobile App Verwaltung (MAM) für Ihre apps und Geräte. Die genauen Schritte hängen von Ihrer Quellumgebung ab und basieren auf dem Mobilgerät und den Anforderungen an die Verwaltung mobiler Apps. Die Schritte können Folgendes umfassen:
<ul>
<li>  Lizenzierung Ihrer Endbenutzer.  </li>
<li>  Konfigurieren von Identitäten, die von InTune verwendet werden, indem Sie entweder Ihre lokale Active Directory oder Cloud-Identitäten (Azure AD) nutzen.  </li>
<li>  Hinzufügen von Benutzern zu Ihrem Intune-Abonnement, Definieren von IT-Administratorrollen und Erstellen von Benutzer- und Gerätegruppen.  </li>
<li>  Konfigurieren ihrer MDM-Autorität basierend auf Ihren Verwaltungsanforderungen, einschließlich:
<ul>
<li>  Festlegen von Intune als Ihre MDM-Berechtigung, wenn Intune Ihre einzige MDM-Lösung ist.  </li>
</ul></li>
<li>  Bereitstellen von MDM-Anleitungen für Folgendes:
<ul>
<li>  Konfiguration von Testgruppen, die zur Validierung von MDM-Verwaltungsrichtlinien verwendet werden sollen.  </li>
<li>  Konfigurieren von MDM-Verwaltungsrichtlinien und -Diensten wie:
<ul>
<li>  App-Bereitstellung für jede unterstützte Plattform über Weblinks oder Deep Links.  </li>
<li>  Richtlinien für bedingten Zugriff.  </li>
<li>  Bereitstellung von e-Mail-, drahtlosen Netzwerken und VPN-Profilen, wenn Sie über eine vorhandene Zertifizierungsstelle, ein drahtloses Netzwerk oder eine VPN-Infrastruktur in Ihrer Organisation verfügen.  </li>
<li>  Einrichten des Microsoft Intune Exchange Connector (falls vorhanden).  </li>
<li>  Herstellen einer Verbindung mit dem InTune-Data Warehouse.  </li>
<li>  Integration von Intune mit:
<ul>
<li>  TeamViewer für Remoteunterstützung (ein TeamViewer-Abonnement ist erforderlich).  </li>
<li>  Partnerlösungen für Mobile Threat Defense (MTD) (ein MTD-Abonnement ist erforderlich).  </li>
<li>  Eine Lösung für die Verwaltung von Telekom-Ausgaben (ein Abonnement der Telekom Expense Management Solution ist erforderlich).  </li>
<li>  Microsoft Defender ATP (Windows E5 oder Microsoft 365 E5-Lizenzen sind erforderlich).  </li>
</ul></li>
<li>  Registrieren von Geräten jeder unterstützten Plattform bei Intune.  </li>
</ul></li>
</ul></li>
<li>  Bereitstellen von App-Schutz Anleitungen für:
<ul>
<li>  Konfigurieren von App-Schutzrichtlinien für jede unterstützte Plattform.  </li>
<li>  Konfigurieren von Richtlinien für bedingten Zugriff für verwaltete apps.  </li>
<li>  Adressierung der entsprechenden Benutzergruppen mit den zuvor erwähnten MAM-Richtlinien.  </li>
<li>  Verwenden von Verwendungsberichten für verwaltete apps.  </li>
</ul></li>
<li>  Bereitstellen von Migrations Anleitungen von der älteren PC-Verwaltung zu InTune MDM.  </li>
</ul>
  <strong>Hinweis</strong>: die Legacy-PC-Verwaltung wird ab dem 15. Oktober 2020 nicht mehr unterstützt.  
</li>
</ul>
  
<strong>Cloudanfügung</strong>  

  Wir führen Sie durch die Bereitschaft, vorhandene Configuration Manager-Umgebungen mit InTune an die Cloud anzufügen. Die genauen Schritte hängen von der Quellumgebung ab. Die Schritte können Folgendes umfassen:  
<ul>
<li>  Erläutern der Vorteile von Cloudanfügungen von Configuration Manager mit Intune.  </li>
<li>  Lizenzierung Ihrer Endbenutzer.  </li>
<li>  Konfigurieren von Identitäten, die von Intune verwendet werden sollen, durch Nutzung Ihres lokalen Active Directory und von Cloudidentitäten.  </li>
<li>  Hinzufügen von Benutzern zu Ihrem Intune-Abonnement, Definieren von IT-Administratorrollen und Erstellen von Benutzer- und Gerätegruppen.  </li>
<li>  Aktivieren der Cloudanfügung in der Configuration Manager-Konsole.  </li>
<li>  Bereitstellung von Anleitungen zum Einrichten von Hybrid Azure AD Join.  </li>
<li>  Anleitung zum Einrichten von Azure AD für die automatische MDM-Registrierung.  </li>
<li>  Bereitstellen von Anleitungen zum Einrichten von Cloud Management Gateway.  </li>
<li>  Konfigurieren unterstützter Arbeitsauslastung, die Sie in Intune verschieben möchten.  </li>
<li>  Installieren des Configuration Manager-Clients auf Geräten, die bei Intune registriert sind.  </li>
</ul> 

<strong>Sicheres Bereitstellen von Outlook Mobile für IOS und Android</strong> Wir bieten Ihnen Unterstützung bei der sicheren Bereitstellung von Outlook Mobile für IOS und Android in Ihrer Organisation, damit sichergestellt ist, dass Ihre Benutzer alle erforderlichen apps installiert haben.  
  Die Schritte zur sicheren Bereitstellung von Outlook Mobile für IOS und Android mit InTune hängen von ihrer Quellumgebung ab. Sie kann Folgendes umfassen:
<ul>
<li>  Herunterladen der Outlook für IOS-und Android-, Microsoft Authenticator-und InTune-Unternehmens Portal-Apps über den Apple App Store oder den Google Play Store.  </li>
<li>  Anleitung zum Einrichten von:
<ul>
<li>  Die Outlook für IOS-und Android-, Microsoft Authenticator-und InTune-Unternehmens Portal-apps-Bereitstellung mit InTune.  </li>
<li>  App-Schutzrichtlinien.  </li>
<li>  Richtlinien für bedingten Zugriff.  </li>
<li>  App-Konfigurationsrichtlinien.  </li>
</ul></li>
</ul>
  
  <strong>Hinweis: der Kurztext</strong>bietet keine Unterstützung für das Sichern von Outlook für IOS und Android mit Postfachrichtlinien für mobile Geräte von Exchange. Wenden Sie sich an einen <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft-Partner</a> , um Hilfe zu erhalten.  
  </td>
<td>  IT-Administratoren müssen über vorhandene Zertifizierungsstellen, drahtlose Netzwerke und VPN-Infrastrukturen verfügen, die bereits in ihren Produktionsumgebungen arbeiten, wenn Sie die Bereitstellung von Drahtlosnetzwerk-und VPN-Profilen mit InTune planen.  
  <strong>Hinweis</strong>: der beschleunigte Service-Vorteil umfasst keine Unterstützung für das Einrichten oder Konfigurieren von Zertifizierungsstellen, Drahtlosnetzwerken, VPN-Infrastrukturen oder Apple MDM Push-Zertifikaten für InTune.  

<strong>Cloudanfügung in Configuration Manager mit Intune</strong>  

 Mit Cloud-Attach sind IT-Administratoren für die Vorbereitung der lokalen Umgebung verantwortlich. Dies kann die Behebung von Problemen umfassen, die verhindern, dass Sie Ihre Configuration Manager-Umgebungen mit InTune an die Cloud anfügen.  
  <strong>Hinweis</strong>: Der FastTrack-Servicevorteil beinhaltet keine Unterstützung bei der Einrichtung oder Aktualisierung des Configuration Manager-Standortservers oder des Configuration Manager-Clients auf die Mindestanforderungen, die zur Unterstützung der Cloudanfügung erforderlich sind. Wenden Sie sich an einen <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft-Partner</a> , um Hilfe zu erhalten.

  <strong>Integration von Intune in Microsoft Defender Advanced Threat Protection (ATP)</strong> 
 
  <strong>Hinweis</strong>: Wir bieten Unterstützung bei der Integration von InTune in Microsoft Defender ATP und beim Erstellen von Geräte Konformitätsrichtlinien basierend auf der Risiko Bewertungsstufe von Windows 10. Wir bieten keine Unterstützung für den Kauf, die Lizenzierung oder die Aktivierung. Wenden Sie sich an einen <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft-Partner</a> , um Hilfe zu erhalten.  
  
<strong>Windows Autopilot</strong> 
 
  IT-Administratoren sind für die Registrierung ihrer Geräte in ihrer Organisation verantwortlich, indem sie entweder den Hardware-Anbieter ihre Hardware-IDs in ihrem Namen hochladen lassen oder sie selbst in den Windows-Autopilot-Dienst hochladen.  
  
<strong>Sicheres Bereitstellen von Outlook für IOS und Android mit InTune </strong>  
<ul>
<li>  In Azure AD für Office 365 aktivierte Benutzeridentitäten.  </li>
<li>  Exchange Online oder Hybrid Exchange, die mit zugewiesenen Benutzerlizenzen konfiguriert ist.  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a>Windows 10

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
<td><strong>Windows 10</strong></td>
<td>  Wir bieten Anleitungen für ein Upgrade von Windows 7 Professional und Windows 8.1 Professional auf Windows 10 Enterprise.  
  Wir bieten Remote-Anleitungen für:
<ul>
<li>  Grundlegendes zur Absicht von Windows 10.  </li>
<li>  Bewerten der Quellumgebung und der Anforderungen (stellen Sie sicher, dass der Microsoft Endpoint Configuration Manager auf die erforderliche Stufe aktualisiert wurde, um die Windows 10-Bereitstellung zu unterstützen).  </li>
<li>  Bereitstellen von Windows 10 Enterprise-und Microsoft 365-Apps mithilfe von Microsoft Endpoint Configuration Manager oder Microsoft 365.  </li>
<li>  Empfehlen von Optionen für die Bewertung Ihrer Windows 10-apps.  </li>
<li>  Aktivieren der Verwendung von Desktop Analysen und Anleitungen durch Erstellung eines Bereitstellungsplans für Desktop Analysen  </li>
<li>  Microsoft 365 apps-Kompatibilitätsbewertung durch Nutzung des Office 365 Bereitschafts Dashboards in Configuration Manager oder mit dem eigenständigen Readiness Toolkit für Office Plus Unterstützung bei der Bereitstellung von Microsoft 365-apps.  </li>
<li>  Bewertung ihrer modernen Verwaltungsstrategien, einschließlich Cloud-Attaching Configuration Manager mit Microsoft InTune oder Bereitstellen von InTune als einzige Cloud-Verwaltungslösung.  </li>
<li>  Erstellen einer Prüfliste für die Korrektur, was Sie tun müssen, um Ihre Quellumgebung auf die Mindestanforderungen für eine erfolgreiche Bereitstellung zu bringen.  </li>
<li>  Bereitstellen von Upgrade-Anleitungen für Ihre vorhandenen Geräte für Windows 10 Enterprise, wenn Sie die erforderlichen Gerätehardware Anforderungen erfüllen.  </li>
<li>  Bereitstellen von Upgrade-Anleitungen zur Unterstützung Ihrer vorhandenen Bereitstellungs Bewegung. FastTrack bietet Empfehlungen und Anleitungen für ein direktes Upgrade auf Windows 10. Anleitungen stehen auch für eine Windows-Clean Image-Installation und Windows Autopilot-Bereitstellungsszenarien zur Verfügung.  </li>
<li>  Bereitstellen von Microsoft 365-Apps mithilfe von Configuration Manager als Teil der Windows 10-Bereitstellung.   </li>
<li>  Bereitstellen von Anleitungen zur Unterstützung Ihrer Organisation auf dem neuesten Stand mit Windows 10 Enterprise und Microsoft 365-Apps mithilfe Ihrer vorhandenen Configuration Manager-Umgebung oder Microsoft 365.  </li>
<li>  Bereitstellen von Anleitungen für eine moderne Verwaltung durch Cloud-Attaching Configuration Manager an InTune oder durch Bereitstellung von InTune Standalone (falls erforderlich).  </li>
</ul>
  <strong>Das folgende liegt außerhalb des Bereichs </strong>  
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
Wenden Sie sich an einen <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft-Partner</a> , um Unterstützung für diese Dienste zu erhalten.  </td>
<td>  Für ein PC-Upgrades müssen Sie die folgenden Voraussetzungen erfüllen:
<ul>
<li>  Quellbetriebssystem: Windows 7 Enterprise oder Professional, Windows 8.1 Enterprise oder Professional.  </li>
<li>  Geräte: Desktop-, Notebook-oder Tablet-Formfaktor.  </li>
<li>  Zielbetriebssystem: Windows 10 Enterprise.  </li>
</ul>
Für ein Infrastrukturupgrade müssen Sie diese Voraussetzungen erfüllen:
<ul>
<li>  Microsoft Endpoint Configuration Manager.  </li>
<li>  Die Configuration Manager-Version muss von der Windows 10-Zielversion unterstützt werden. Weitere Informationen finden Sie in der Configuration Manager-Support Tabelle unter <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.  </li>
</ul>

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
  Windows Server Semi-Annual Channel (SAC) Version 1803.  
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

</tbody>
</table>
