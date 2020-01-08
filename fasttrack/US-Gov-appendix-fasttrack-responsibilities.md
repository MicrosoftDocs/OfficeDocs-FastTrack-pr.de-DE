---
title: Aufgaben für Office 365 US-Regierung
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 1/03/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: None
ms.collection: FastTrack
description: 'Zu den Zuständigkeiten von FastTrack-Experten während des Onboardings zählen die folgenden:'
ms.openlocfilehash: ab9213c8ea5095531a0a06bb40138c995be093a6
ms.sourcegitcommit: fe68534c2ac30220561ef73ca408986a937ca7df
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 01/07/2020
ms.locfileid: "40959187"
---
# <a name="fasttrack-responsibilities-for-office-365-us-government"></a>Aufgaben für Office 365 US-Regierung

Zu den Zuständigkeiten von FastTrack-Experten während des Onboardings zählen die folgenden:  
  
## <a name="general"></a>Allgemein

- Remoteunterstützung bei einer erfolgreichen Planung für Entwicklung und Implementierung sowie bei den erforderlichen Konfigurationsaktivitäten, wie in den Phasenbeschreibungen ausführlicher erläutert
- Bereitstellen von verfügbarer Dokumentation und Softwaretools, Verwaltungskonsolen und Skripts als Anleitung, sodass Sie Konfigurationsaufgaben verringern oder ganz weglassen können; außerdem Bereitstellen von Ressourcen für eine erfolgreiche Planung.   
    
## <a name="initiate-phase"></a>Einleitungsphase

- Zusammenarbeit mit Ihnen, um Ihre Absichten, Unternehmensziele und Verwendungspläne für den Dienst zu ermitteln. 
- Zusammenarbeit mit Ihnen über Office 365-Zusammenarbeitsdiensten (z. B. Microsoft Teams), um mit dem Onboarding zu beginnen. 
- Festlegen, für welche berechtigten Dienste das Onboarding erfolgen soll. 
    
## <a name="assess-phase"></a>Analysephase

- Abhalten eines Anrufs zur Erfolgsplanung, um Ihnen eine Anleitung für die erfolgreiche Akzeptanz durch die Benutzer an die Hand zu geben.  
- Bereitstellen eines administrativen Überblicks.  
- Bereitstellen von Anleitungen zu: 
  - Domain Name System (DNS)-, Netzwerk- und Infrastrukturanforderungen.  
  - Clientanforderungen (benötigte Internetbrowser, Clientbetriebssysteme. mobile Geräte und Dienste).
  - Bereitstellen von Benutzeridentitäten und -konten. 
  - Aktivieren von berechtigten Diensten, die erworben und als Teil des Onboardings definiert wurden.
  - Unterstützung einer erfolgreichen Diensteinführung und des Werts.   
- Festlegen des Zeitrahmens für Korrekturaktivitäten.
- Bereitstellen einer Checkliste für die Korrekturen.   
- Bewerten der vorhandenen SharePoint Server 2013- oder SharePoint Server 2016-Infrastruktur, einschließlich:  
  - Voraussetzungen für die SharePoint Online-Hybridlösung.  
  - Lokale Infrastrukturbereitschaft für SharePoint Online-Hybridfeatures.  
  - Der Zugriff auf erforderliche SharePoint Online-Endpunkte. 
  - Zielgruppen für die OneDrive for Business-Hybridlösung.    
- Bewerten der vorhandenen Lync- oder Skype for Business Online-Infrastruktur, einschließlich:  
  - Bereitstellungsstrategie für unterstützte Skype for Business-Clients  
  - Zugriff auf die Endpunkte  
  - Verbindungsqualität  
  - Schätzungen hinsichtlich der Bandbreite  
  - Voraussetzungen zum Unterstützen der Serverkonfiguration für geteilte Domänen  
  - Bereitschaft der identifizierten Benutzer für den Wechsel zu Skype for Business Online  
- Analysieren der Messaginginfrastruktur, einschließlich:   
  - Allgemeiner Nachrichtenfluss und Routingaspekte.  
  - Clientzugriff (einschließlich vorhandener veröffentlichter Clientzugriffsendpunkte).  
  - Quellmessagingumgebung für Integrationsanforderungen. 
- Stellen Sie die Migration von Daten bereit, wenn der FastTrack Center-Datenmigrationsdienst verwendet wird und wenn Sie berechtigt sind.
    
## <a name="remediate-phase"></a>Korrekturphase

- Abhalten von Telefonkonferenzen mit Ihnen gemäß dem vereinbarten Zeitplan zum Überprüfen des Fortschritts der Korrekturaktivitäten und der Erfolgsplanung.   
- Unterstützen bei der Ausführen von Bewertungstools, um Probleme zu identifizieren und zu beheben sowie die Ergebnisse zu interpretieren.
    
## <a name="enable-phase"></a>Aktivierungsphase

Bereitstellen von Anleitungen zu: 
- Auswertung des Fortschritts der Erfolgsplanung und Ermitteln, welche weitere Unterstützung Sie benötigen.    
- Aktivieren des Office 365-Mandanten.
- Konfigurieren von TCP/IP-Protokollen und Firewallports.   
- Konfigurieren von DNS für berechtigte Dienste   
- Überprüfen der Konnektivität mit Office 365.   
- Verbinden Ihres lokalen Active Directory mit Azure Active Directory:   
  - Installieren eines Verzeichnissynchronisierungsservers zwischen Ihren Office 365-Domänendiensten (AD DS) und Active Directory, falls erforderlich.   
  - Konfigurieren der Kennwortsynchronisierung (Kennworthash) für Office 365 (Azure Active Directory) mit dem Tool „Azure Active Directory Connect“, falls erforderlich.  
  - Für Umgebungen mit einer einzigen und mehreren Gesamtstrukturen:
      - Konfigurieren von Azure Active Directory Pass-Through-Authentifizierung, falls erforderlich (in gcc High-oder DoD-Plänen nicht verfügbar).
      - Konfigurieren von Azure Active Directory nahtloses einmaliges Anmelden (Single Sign-on, SSO), falls erforderlich (nicht verfügbar in gcc High-oder DoD-Plänen)
    > [!NOTE]
    > Die Azure Active Directory Pass-Through-Authentifizierung für Umgebungen mit mehreren Gesamtstrukturen wird unterstützt, wenn es Gesamtstruktur-Vertrauensstellungen zwischen Ihren Active Directory-Gesamtstrukturen gibt und wenn das Namensuffixrouting korrekt konfiguriert ist. Weitere Agents können auf mehreren lokalen Servern installiert werden, um hohe Verfügbarkeit für Anmeldeanforderungen zu bieten. Weitere Informationen finden Sie unter [Azure Active Directory-Passthrough-Authentifizierung: Schnellstart](https://go.microsoft.com/fwlink/?linkid=860094) und [Azure AD Connect: Nahtloses einmaliges Anmelden: Schnellstart](https://go.microsoft.com/fwlink/?linkid=860095).[!NOTE]
    > Weitere Informationen zu Einschränkungen der Pass-Through-Authentifizierung finden Sie unter [Azure Active Directory-Passthrough-Authentifizierung: aktuelle Einschränkungen](https://go.microsoft.com/fwlink/?linkid=860356).[!NOTE]
    > Weitere Informationen zu Problemen beim nahtlosen einmaligen Anmelden finden Sie unter [Problembehandlung beim nahtlosen einmaligen Anmelden mit Azure Active Directory](https://go.microsoft.com/fwlink/?linkid=841926). 
- Für eine einzelne Gesamtstruktur mit Verbundidentitäten ist das Ziel: 
  - Installieren und Konfigurieren von AD FS für die lokale Domänenauthentifizierung mit Office 365 in einer fehlertoleranten Konfiguration für einen Einzelstandort, falls erforderlich.  
  - Installieren und Konfigurieren von WAP zur Veröffentlichung Ihrer AD FS-Infrastruktur im Internet, wenn erforderlich. 
    > [!NOTE]
    > Für alle Konfigurationen mit mehreren Gesamtstrukturen liegen AD FS-Bereitstellungen außerhalb des Bereichs. 
- Testen der Funktionalität für einmaliges Anmelden, sofern bereitgestellt.   
- Unterstützung einer erfolgreichen Diensteinführung und des Werts.
    
## <a name="exchange-online"></a>Exchange Online

Bereitstellen von Anleitungen zu: 
- Erstellen oder Aktualisieren von DNS-Datensätzen.    
- Aktivieren des E-Mail-Routings zwischen dem Quellmessagingsystem und Office 365-Umgebungen    
- Konfigurieren von Exchange Online Protection-Funktionen (einschließlich Exchange Online Advanced Threat ProtectionFunktionen, falls in Ihrem Abonnement verfügbar) und Sicherstellen, dass die MX-Einträge auf Office 365 für alle E-Mail-aktivierten Domänen verweisen.   
- Konfigurieren der Hybrideinrichtung zwischen einer einzelnen lokalen Exchange-Organisation und Office 365 *oder* zwischen mehreren lokalen Exchange-Organisationen und Office 365. 
- Einrichten von Unified Messaging (um) mit Exchange Online (um ist in gcc DoD-Plänen nicht verfügbar). 
    
Weitere Informationen zu den Zuständigkeiten bei der Datenmigration finden Sie unter [Datenmigration](O365-data-migration.md).
  
## <a name="sharepoint-online"></a>SharePoint Online

Bereitstellen von Anleitungen zu:
- Einrichten von Benutzerkonten einschließlich Lizenzierung.   
- Aktivieren der Websiteerstellung für Ihren SharePoint Online-Administrator.   
- Planen von Websitesammlungen.   
- Sichern von Inhalten und Verwalten von Berechtigungen.   
- Aktivieren persönlichen Websites und von Features für das soziale Netzwerk.   
- Konfigurieren von SharePoint Online-Features.    
- Durchführen der Datenmigration, falls der FastTrack Center-Datenmigrationsdienst verwendet wird und die Berechtigungskriterien erfüllt sind  
- Auswerten der lokalen SharePoint-Farminfrastrukturkonfiguration, die für die SharePoint Online-Hybridlösung erforderlich ist.    
- Mithilfe von Tools und Automatisierung für: 
  - Das Konfigurieren lokaler Cloud-Suchdienstanwendungen.    
  - Das Konfigurieren einer Vertrauensstellung zwischen einer lokalen SharePoint- und einer Cloudumgebung.   
- Das Konfigurieren von lokalen SharePoint-Websites zur Verwendung von SharePoint Online-Hybridfeatures.
    
## <a name="onedrive-for-business"></a>OneDrive for Business

Bereitstellen von Anleitungen zu: 
- Bestimmen lokaler SharePoint-Versionen und von Integrationsoptionen.    
- Bestimmen von Synchronisierungs- und Identitätsoptionen.   
- Auswählen einer Einführungsoption:   
  - Just-in-Time-Einführung  
  - Gestaffelte Einführung (in aufeinanderfolgenden Phasen)   
- Vorbereiten der lokalen Umgebung auf die Bereitstellung von OneDrive for Business:  
  - Bestimmen des ordnungsgemäßen OneDrive for Business-Synchronisierungsclients. 
  - Konfigurieren von DNS, Netzwerkports und Firewall.   
- Zuweisen von Endbenutzerlizenzen.   
- Einrichten von SharePoint Online-Gruppen zum Festlegen, wer OneDrive for Business erhält.    
- Bereitstellen des OneDrive for Business-Synchronisierungsclients auf Desktops.   
- So konfigurieren Sie die SharePoint Online-Hybridlösung OneDrive for Business-Umleitung (nur SharePoint 2013 und SharePoint 2016).  
- Migration von Daten, wenn der FastTrack Center-Datenmigrationsdienst verwendet wird und wenn Sie berechtigt sind.
    
## <a name="skype-for-business-online"></a>Skype for Business Online

Bereitstellen von Anleitungen zu:
- Bereitstellen von Skype for Business-Identitäten für Office 365.   
- Aktivieren von Onlinekonferenz-, Chat- und Anwesenheitsfeatures für Office 365.  
- Erstellen von Konten zum Zuordnen zu unterstützten Raumsystemgeräten (bis zu 10 Konten)    
- Konfigurieren einer Serverumgebung für geteilte Domänen zur Unterstützung von Lync-Hybrid- oder Skype for Business Online-Hybridszenarien (falls zutreffend)   
- Aktivieren von Audiokonferenzen:   
  - Organisationseinrichtung der Standardeinstellungen für Konferenzbrücke   
  - Zuweisen einer Konferenzbrücke zu lizenzierten Benutzern 
- Aktivieren des Telefonsystems (nicht verfügbar in gcc High-oder DoD-Plänen):  
  - Aktivieren des Telefonsystems und Plänen für Anrufonboarding (auf verfügbaren Märkten) 
  - Zuweisung von Nummern zu lizenzierten Benutzern  
  - Anweisung zum Portieren lokaler Rufnummern über die Benutzeroberfläche bis 999  
  - SR-Unterstützung für das Portieren von lokalen Nummern über 999 hinaus  
- Aktivieren Skype for Business Besprechungs Übertragung (nicht verfügbar in gcc High-oder DoD-Plänen):  
  - Anleitung zum Aktivieren des Onboardings bei Skype for Business-Livekonferenzen  
  - Organisationseinrichtung für den Verbund mit dem Livekonferenzdienst
    
## <a name="microsoft-teams"></a>Microsoft Teams

Bereitstellen von Anleitungen zu:
- Sicherstellen der Mindestanforderungen   
- Konfigurieren von Firewallports.  
- Einrichten von DNS  
- Sicherstellen, dass Microsoft Teams auf Ihrem Office 365-Mandanten aktiviert ist   
- Aktivieren oder Deaktivieren von Benutzerlizenzen  
- Microsoft Teams-Client-Verteilung.    
- Features für IT-Experten und Administratoren. 
- Wichtige Produktfunktionen  
- Kundenerfolgsvorlagen
    
## <a name="power-bi"></a>Power BI

Bereitstellen von Anleitungen zu:
- Überprüfen der Power BI-Abonnementpläne.    
- Hinzufügen des Power BI-Diensts    
- Herunterladen der Power BI Desktop-App.
    
## <a name="project-online"></a>Project Online

Bereitstellen von Anleitungen zu:  
- Überprüfung von Abonnementplänen  
- Überprüfen der grundlegenden SharePoint-Funktionen    
- Hinzufügen des Project Online-Diensts  
- Hinzufügen von Benutzern zu Project Online, einschließlich ERP-Synchronisierung  
- Überprüfen grundlegender Project Online-Funktionen durch Erstellen eines Projekts
    
## <a name="yammer-enterprise"></a>Yammer Enterprise

Hilfestellung zum Umwandeln Ihres einzelnen Yammer Basic-Netzwerks in ein einzelnes Yammer Enterprise-Netzwerk.

> [!NOTE]
> Jammern Enterprise ist keine Komponente von Office 365 US-Regierung, kann aber ohne Kosten als eigenständiges Angebot für jeden Benutzer erworben werden, der für Office 365 in gcc lizenziert ist. Dieses Angebot ist derzeit auf Kunden beschränkt, die über Enterprise Agreement und Enterprise Agreement Subscription kaufen. Jammern ist in gcc High-oder DoD-Plänen nicht verfügbar.
  
## <a name="office-365-proplus"></a>Office 365 ProPlus

Bereitstellen von Anleitungen zu:
- Beheben von Problemen bei der Bereitstellung   
- Zuweisen von Endbenutzerlizenzen mit [Microsoft 365 Admin Center](https://go.microsoft.com/fwlink/?linkid=2032704) und Windows PowerShell  
- Installieren von Office 365 ProPlus aus dem Office 365-Portal mithilfe von Klick-und-Los   
- Installieren von Office Mobile-Apps (wie Outlook Mobile, Word Mobile, Excel Mobile und PowerPoint Mobile) auf Ihren iOS-, Android- oder Windows Mobile-Geräten.   
- Konfigurieren von Update-Einstellungen mit dem Office 2016-Bereitstellungstool oder den Gruppenrichtlinienvorlagen   
- Einrichten eines einzelnen lokalen Verteilungsservers für Office 365 ProPlus, einschließlich Unterstützung beim Erstellen einer configuration.xml-Datei für die Verwendung mit dem Office 365-Bereitstellungstool   
- Bereitstellen mit System Center Configuration Manager, einschließlich Unterstützung beim Erstellen des System Center Configuration Manager-Pakets

    


