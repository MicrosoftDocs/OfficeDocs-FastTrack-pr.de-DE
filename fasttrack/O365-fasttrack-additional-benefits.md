---
title: Anhang B FastTrack Center - zusätzlicher Vorteil
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 11/02/2019
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Priority
description: Kunden, die mindestens 20.000 Lizenzen für einen Exchange Online-Mandanten erwerben, sind für zusätzliche FastTrack Center-Dienste berechtigt. Weitere Informationen finden Sie unter „Berechtigte Dienste und Pläne“.
ms.openlocfilehash: 8da19cd3922e1e37eb382716039dc6a96166191e
ms.sourcegitcommit: f8d7e570b60a55c244af0eceb6fbb0e591257f11
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 11/01/2019
ms.locfileid: "37921293"
---
# <a name="appendix-b---fasttrack-center-additional-benefit"></a>Anhang B: FastTrack Center – zusätzlicher Vorteil

Kunden, die mindestens 20.000 Lizenzen für einen Exchange Online-Mandanten erwerben, sind für zusätzliche FastTrack Center-Dienste berechtigt. Weitere Informationen finden Sie unter [Berechtigte Dienste und Pläne](M365-eligible-services-and-plans.md). 
  
## <a name="onboarding-and-migration-phases"></a>Phasen im Onboarding- und Migrationsprozess

## <a name="core"></a>Haupt-Onboarding

Haupt-Onboarding-Add-Ons umfassen Unterstützung bei der Konfiguration für georedundante Active Directory-Verbunddienste (AD FS) und die AD FS-Clientzugriffsrichtlinien für den Dienst. 
  
## <a name="exchange-online"></a>Exchange Online

Für Exchange Online bieten wir Unterstützung bei der Konfiguration für die folgenden Schritte:
- Einrichten von Unified Messaging (UM) mit Exchange Online.
- Konfigurieren der Koexistenz von Exchange Online und älteren lokalen öffentlichen Ordnern.
- E-Mail-fähige Anwendungsintegration. 
- Planen und Gruppieren der Postfachmigration.
    
## <a name="skype-for-business-online"></a>Skype for Business Online

Für Skype for Business Online bieten wir eine Anleitung für lokale Lync- und Skype for Business-Benutzermigration zu Skype for Business Online.
  
## <a name="office-365-proplus"></a>Office 365 ProPlus

Für Office 365 ProPlus bieten wir Unterstützung in den folgenden Bereichen: 
- Bewertung und Planung mit Fokus auf der Vorbereitung der Umgebung auf die Erstbereitstellung und die Aktualisierungsverwaltung gemäß den Best Practices von Microsoft 
- Entwicklung von Bereitstellungskonfigurationen und Aktualisierungseinstellungen mithilfe des Office 365-Bereitstellungstools und Office-Individualisierungstool. 
- Bereitstellungspaketierung mithilfe von System Center Configuration Manager  
- Ermöglicht die Verwendung des Readiness Toolkit for Office, um potenzielle Kompatibilitätsprobleme mit Ihren VBA-Makros (Microsoft Visual Basic for Applications) und Add-Ins zu identifizieren, die Sie mit Office verwenden.
    
## <a name="fasttrack-responsibilities"></a>FastTrack-Zuständigkeiten

Zu den Zuständigkeiten von FastTrack-Experten während des Onboardings zählen die nachfolgend genannten. Diese gelten möglicherweise zusätzlich zu den in [FastTrack-Zuständigkeiten](O365-fasttrack-responsibilities.md) definierten Aktivitäten oder ersetzen diese.
  
## <a name="general"></a>Allgemein

- Remoteunterstützung bei einer erfolgreichen Planung für Entwicklung, Implementierung und bei den erforderlichen Konfigurationsaktivitäten, wie in den [Phasen im Onboarding- und Migrationsprozess](#onboarding-and-migration-phases) ausführlicher erläutert.
    
## <a name="assess-phase"></a>Analysephase

- Abhalten eines Anrufs zur Erfolgsplanung, um Ihnen eine Anleitung für die erfolgreiche Akzeptanz durch die Benutzer an die Hand zu geben. 
- Analyse der Umgebung zur Unterstützung der Konfiguration von georedundanten AD FS  
- Ausführen einer Analyse zum Ermitteln der Anforderungen für AD FS-Clientzugriff
    
## <a name="enable-phase"></a>Aktivierungsphase

### <a name="geo-redundant-ad-fs-guidance"></a>Unterstützung bei georedundantem AD FS

- Bereitstellung eines standardmäßigen Referenzarchitekturentwurfs für eine georedundante AD FS-Topologie über zwei (2) Rechenzentren. Die Standardarchitektur bietet Folgendes:
  - Verbundauthentifizierung für Dienste, die im FastTrack Center-Vorteil enthalten sind 
  - Ausfallsicherheit eines einzelnen Standorts  
  - Hochverfügbarkeit und Failover  
  - Größenanpassung 
- Unterstützung bei der Verwendung der integrierten Windows-Datenbank und von SQL Server als Datenbankinstanz für die AD FS-Farm   
- Überprüfen der Einrichtung von Verbundauthentifizierung für jede im Bereich enthaltene Gesamtstruktur  
- Überprüfen der Authentifizierungsfunktion für bis zu 10 Benutzer
    
> [!NOTE]
> AD FS-Bereitstellungen sind für Kunden, die für zusätzliche Vorteile berechtigt sind, mit mehreren Active DirectoryGesamtstrukturkonfigurationen enthalten. 
  
### <a name="ad-fs-client-access-policy-guidance"></a>Unterstützung bei der AD FS-Clientzugriffsrichtlinie

- Überprüfen der Richtlinien und der Konfiguration, die für sichere Office 365-Ressourcen erforderlich sind  
- Unterstützung bei der Konfiguration von AD FS-Clientzugriffsrichtlinien für ermittelte Clientzugriffszenarien innerhalb der unterstützten Szenarien Weitere Informationen finden Sie unter [Einschränken des Zugriffs auf Office 365-Dienste basierend auf dem Speicherort des Clients](https://go.microsoft.com/fwlink/?LinkID=525689). 
- Überprüfung der Verbundauthentifizierungsfunktion mit geänderten Clientzugriffsrichtlinien für ermittelte Zugriffsszenarien mit einer Konfiguration von bis zu 10 Benutzern
    
## <a name="exchange-online"></a>Exchange Online

### <a name="exchange-unified-messaging-guidance"></a>Unterstützung bei Exchange Unified Messaging

- Unterstützung bei der erforderlichen Konfiguration von Exchange Online für die Verwendung von bis zu 10: 
  - UM-Wählplänen   
  - UM-Postfachrichtlinien 
  - Automatischen Telefonzentralen  
- Unterstützung bei der Konfiguration der lokalen Lync- oder der Skype for Business-Umgebung zum Aktivieren von UM, insbesondere für:  
  - Von Exchange Online gehostete Richtlinien  
  - Von Exchange Online gehostete Voicemailrichtlinien 
  - Automatische UM-Telefonzentralenkontakte und Outlook-Voicemail, damit Benutzer zu Exchange Online umgeleitet werden. 
  - Unterstützung bei der Erstellung von für den Verbund benötigten SRV-Einträgen
> [!NOTE]
> UM kann mit unterstützten UM-IP-Gateways und Sitzungsrahmencontrollern (Session Border Controllers, SBCs) konfiguriert werden. Weitere Informationen finden Sie unter [Telefonsystemintegration mit UM](https://go.microsoft.com/fwlink/?LinkID=809293). 
  
### <a name="public-folder-coexistence-guidance"></a>Unterstützung bei Koexistenz öffentlicher Ordner

- Unterstützung bei der Koexistenz einer einzelnen öffentlichen Ordnerstruktur, einschließlich:  
  - Vorbereitung der öffentlichen Ordner in Exchange 2007, Exchange 2010 und Exchange 2013. 
  - Windows PowerShell-Cmdlets, die für die Synchronisierung der Hierarchie öffentlicher Exchange 2007-, Exchange 2010- und Exchange 2013-Ordner mit Exchange Online erforderlich sind.  
  - Konfiguration von Exchange Online, damit der Zugriff auf öffentliche Ordner zu lokalen öffentlichen Ordnern umgeleitet wird.  
  - Konfiguration des Zugriffs auf öffentliche Ordner aus Exchange Online für eine einzelne Exchange 2007-, Exchange 2010- oder die lokale Exchange 2013-Umgebung.  
  - Unterstützung bei der Überprüfung des Zugriffs auf die öffentliche Ordnerumgebung für bis zu 10 Benutzer in Exchange Online
    
### <a name="mail-enabled-application-integration-guidance"></a>Leitfaden zur Integration E-Mail-fähiger Anwendungen

- Bereitstellen von Vorlagen für:  
  - Anwendungen zum Versenden von Massen-E-Mails  
  - Programme, die E-Mails über Exchange umleiten  
  - Anwendungen, die Exchange-Postfächer verwenden  
  - Programme, für die Drittanbieter- oder benutzerdefinierte Komponenten auf Exchange-Servern installiert werden müssen
    
### <a name="mailbox-migration-planning-and-grouping"></a>Planen und Gruppieren der Postfachmigration

- Unterstützung bei der Erstellung eines Migrationsplans, einschließlich:  
  - Gruppieren von Benutzern und Ressourcen in Batches
  - Koordinieren der Bereitstellung der erforderlichen Softwarepakete und der Migrationsbatches   
  - Unterstützung beim Erstellen eines Kommunikationsplans für Endbenutzer 
  - Koordinieren der Größe von Migrationsbatches, Fehlerquoten und erwarteten Helpdesk-Unterstützung 
- Unterstützung beim Gruppieren von Benutzer- und Ressourcenpostfächern in Batches nach Typ, Geschäftsfunktion und Stellvertretungszugriff basierend auf relevanten, vom Kunden angegebenen Informationen
    
## <a name="skype-for-business-online"></a>Skype for Business Online

- Hilfestellung für das Migrieren von Benutzern in Batches in einer Skype for Business-Hybridbereitstellung (Kontaktlisten von Benutzern werden beibehalten)
    
## <a name="office-365-proplus"></a>Office 365 ProPlus

- Bereitstellen von Hilfestellung und Unterstützung für:  
  - Bewertung und Planung der Erstbereitstellung und Aktualisierungsverwaltung gemäß den Best Practices von Microsoft
  - Ermöglicht die Verwendung des Readiness Toolkit for Office, um potenzielle Kompatibilitätsprobleme mit Ihren Microsoft VBA-Makros und Add-Ins zu identifizieren, die Sie mit Office verwenden.
  
## <a name="your-responsibilities"></a>Ihre Zuständigkeiten

Zu Ihren Zuständigkeiten während des Onboardings zählen die nachfolgend genannten. Diese gelten zusätzlich zu den Abschnitt [Ihre Zuständigkeiten](O365-your-responsibilities.md) definierten Aufgaben. 
  
- Zuweisen und Verwalten von Ressourcen gemäß dem Projektplan  
- Rechtzeitige Einleitung entsprechender Maßnahmen zum Verringern von Sicherheitsrisiken und Beheben der Probleme von Kunden, Partnerprojektmanagern und dem FastTrack Manager   
- Prüfen der Statusberichte und Einleiten entsprechender Maßnahmen   
- Bestimmen eines Operational Sponsors oder Leiters mit Entscheidungsbefugnis für die Leitung des Projektausschusses  
- Bestimmen eines Executive Sponsors für die Zusammenarbeit mit dem Executive Sponsor von Microsoft  
- Abhalten einer monatlichen Projektbesprechung
    

  

