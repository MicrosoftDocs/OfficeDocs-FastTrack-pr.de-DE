---
title: FastTrack-Zuständigkeiten
description: Die Zuständigkeiten von "bei", wenn Kunden den Vorteil für EMS nutzen
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: c8fd871e-f1bc-43ec-a5f3-ad025df9b026
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 4c8dd188e0e29613b9221c087f0a8e35ed744179
ms.sourcegitcommit: 28dafb1d0904d29c4e113b03d3c1b0fcd2257508
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/13/2019
ms.locfileid: "33967960"
---
# <a name="fasttrack-responsibilities"></a>FastTrack-Zuständigkeiten

Während des onboardings hat die folgende Verantwortung.

## <a name="general"></a>Allgemein

-   Stellen Sie Remote Support für die erforderlichen Konfigurationsaktivitäten bereit, die in den detaillierten Phasen Beschreibungen aufgeführt sind.

-   Stellen Sie verfügbare Dokumentation, Software Tools und Verwaltungskonsolen bereit, um Konfigurationsaufgaben zu reduzieren oder zu vermeiden.

## <a name="initiate-phase"></a>Einleitungsphase

-   Arbeiten Sie mit dem Onboarding zusammen.

-   Festlegen, für welche berechtigten Dienste das Onboarding erfolgen soll.

## <a name="assess-phase"></a>Analysephase

-   Bereitstellen eines administrativen Überblicks.

-   Bereitstellen von Anleitungen zu:

    -   DNS-, Netzwerk-und Infrastrukturanforderungen.

    -   Clientanforderungen (Internet Browser, Clientbetriebssystem und Dienste)

    -   Bereitstellen von Benutzeridentitäten und -konten.

    -   Aktivieren berechtigter Dienste, die erworben und als Teil des onboardings definiert wurden.

-   Festlegen des Zeitrahmens für Korrekturaktivitäten.

-   Stellen Sie eine Prüfliste für die Behebung sowohl für InTune als auch für Azure AD Premium bereit.

## <a name="remediate-phase"></a>Korrekturphase

-   Halten Sie Konferenzanrufe mit Ihnen gemäß dem vereinbarten Zeitplan an, um den Fortschritt der Korrekturaktivitäten zu überarbeiten, beispielsweise führen Sie durch die Installation Voraussetzungen vor Onboarding a Microsoft Cloud Service.

## <a name="enable-phase"></a>Aktivierungsphase
Bereitstellen von Anleitungen zu:

-   Aktivieren des Microsoft Online Service-Mandanten oder-Abonnements.

-   Konfigurieren von TCP/IP-Protokollen und Firewallports.

-   Konfigurieren von DNS für berechtigte Dienste

-   Überprüfen der Konnektivität mit Microsoft Online Services.

-   Für eine Umgebung mit einer einzelnen Gesamtstruktur:

    -   Installieren eines Verzeichnissynchronisierungsservers zwischen Ihren Active Directory-Domänendiensten (AD DS) und den berechtigten Microsoft Online Services (nur bei Bedarf).

    -   Konfigurieren der verwalteten Authentifizierung (Kenn Wort Hash Synchronisierung oder Pass-Through-Authentifizierung) mit dem Azure Active Directory Connect-Tool. (nur bei Bedarf).

        > [!NOTE]
        > Entwicklung und Implementierung für benutzerdefinierte Regelerweiterungen liegen außerhalb des Bereichs.

-   Für eine einzelne Gesamtstruktur, wenn das Ziel Verbundidentitäten ist: Installieren und Konfigurieren von Active Directory-Verbunddienste (AD FS) für die lokale Domänenauthentifizierung mit InTune in einer fehlertoleranten Konfiguration mit einem einzigen Standort, falls erforderlich.

    > [!NOTE]
    > Für alle Konfigurationen mit mehreren Gesamtstrukturen liegen AD FS-Bereitstellungen außerhalb des Bereichs.

-   Testen der einmaligen Anmeldung (SSO)-Funktionalität, sofern bereitgestellt.

### <a name="enable-phase---microsoft-azure-active-directory-premium"></a>Phase aktivieren – Microsoft Azure Active Directory Premium

Bereitstellen von Anleitungen zu:

- Aktivieren Ihres Azure AD Premium-Mandanten.

- Konfigurieren von Firewallports.

- Konfigurieren von DNS für berechtigte Dienste

- Überprüfen der Konnektivität mit Azure AD Premium-Diensten.

- Für eine Umgebung mit einer einzelnen Gesamtstruktur:

  -   Installieren einer Verzeichnissynchronisierung zwischen Ihren Active Directory-Domänendiensten (AD DS) und Azure AD Connect, falls erforderlich.

  -   Konfigurieren einer Authentifizierungsmethode (Kenn Wort Hash Synchronisierung oder Pass-Through-Authentifizierung) mit dem Azure AD Connect-Tool.

- Für eine Umgebung mit mehreren Gesamtstrukturen:

  -   Installieren der Azure AD Connect-Synchronisierung, eingerichtet für Szenarien mit mehreren Gesamtstrukturen
- Für Umgebungen mit einer einzigen und mehreren Gesamtstrukturen:
  - Konfigurieren der Azure Active Directory Pass-Through-Authentifizierung, falls erforderlich.
  - Konfigurieren der Azure Active Directory Einmaligen Anmeldens (Single Sign-On, SSO), falls erforderlich.
    > [!NOTE]
    > Die Azure Active Directory Pass-Through-Authentifizierung für Umgebungen mit mehreren Gesamtstrukturen wird unterstützt, wenn es Gesamtstruktur-Vertrauensstellungen zwischen Ihren Active Directory-Gesamtstrukturen gibt und wenn das Namensuffixrouting korrekt konfiguriert ist. Weitere Agents können auf mehreren lokalen Servern installiert werden, um hohe Verfügbarkeit für Anmeldeanforderungen zu bieten.

  - Weitere Informationen finden Sie unter [Azure Active Directory-Passthrough-Authentifizierung: Schnellstart](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-quick-start#step-1-check-prerequisites) und [Azure AD Connect: Nahtloses einmaliges Anmelden: Schnellstart](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start#step-1-check-prerequisites).
  - Weitere Informationen zu Einschränkungen der Pass-Through-Authentifizierung finden Sie unter [Azure Active Directory-Passthrough-Authentifizierung: Aktuelle Einschränkungen](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-current-limitations).
  - Weitere Informationen zu Problemen beim nahtlosen einmaligen Anmelden finden Sie unter [Problembehandlung beim nahtlosen einmaligen Anmelden mit Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-troubleshoot-sso).

      > [!NOTE]
      > Die Kennworthash Synchronisierung und das Kenn Wort Rückschreiben unterstützen mehrere Gesamtstrukturen. Andere Rück schreibe Szenarien werden jedoch nicht unterstützt.

  - Konfigurieren der Synchronisierung zwischen lokalen Active Directory-Gesamtstrukturen und Microsoft Azure Active Directory Premium-Verzeichnis (Azure Active Directory).

    > [!NOTE]
    > Entwicklung und Implementierung für benutzerdefinierte Regelerweiterungen liegen außerhalb des Bereichs.

- Für eine einzelne Gesamtstruktur, wenn das Ziel Verbundidentitäten ist:

  -   Installieren und Konfigurieren von AD FS für die lokale Domänenauthentifizierung mit Azure AD Premium in einer fehlertoleranten Konfiguration mit einem einzigen Standort (falls erforderlich).

  > [!NOTE]
  > Für alle Konfigurationen mit mehreren Gesamtstrukturen liegen AD FS-Bereitstellungen außerhalb des Bereichs.

- Testen der SSO-Funktionalität (falls bereitgestellt).

### <a name="enable-phase---azure-ad-premium--with-azure-ad-connect-and-ad-fs"></a>Aktivieren von Phase-Azure AD Premium – mit Azure AD Connect und AD FS

Anleitungen zum Einrichten von:

- Benutzer proversionierung, einschließlich Lizenzierung.

- Azure AD Connect-Verzeichnissynchronisierung (mit Kenn Wort Rück schreibe-und Kennworthash Synchronisierung).

  - Azure Active Directory Self Service Password Reset (SSPR).

  - Azure mehrstufige Authentifizierung.

  - Bis zu drei (3) oder mehr Software as a Service (SaaS)-Anwendungsintegrationen mit einmaligem Anmelden (Single Sign-on, SSO) vom [Azure Active Directory Marketplace](https://azure.microsoft.com/marketplace/active-directory/).

  - Automatische Benutzer proversionierung für vorintegrierte SaaS-Anwendungen, die in der [Liste](https://docs.microsoft.com/en-us/azure/active-directory/saas-apps/tutorial-list)mit den Lernprogrammen für die APP-Integration aufgeführt sind, beschränkt auf die nur ausgehende Einrichtung.

  - Benutzerdefinierter Anmeldebildschirm, einschließlich Logo, Text und Bildern.

  - Self-Service-und Dynamic-Gruppen (Gruppen).

  - Azure Active Directory-Anwendungs Proxy.

  - Azure Active Directory Connect-Integrität.

  - Azure Active Directory-bedingter Zugriff.

  - Azure Active Directory-Nutzungsbedingungen.

  - Azure Active Directory-Identitätsschutz.

  - Azure Active Directory-privilegierte Identitätsverwaltung.

  - Azure Active Directory-Zugriffsüberprüfungen.

### <a name="enable-phase---intune"></a>Phase-InTune aktivieren

> [!IMPORTANT]
> Bei der Windows 10-klassischen PC-Verwaltung mit InTune wird nicht unterstützt. Nur unterstützt Windows 10-Verwaltung über InTune Mobile Device Management (MDM).

Unter **Stützung** für:

-   Konfigurieren der von InTune zu verwendenden Identitäten durch Nutzung der lokalen Active Directory-oder Cloud-Identitäten (Azure Active Directory).

-   Lizenzierung der Endbenutzer.

-   Hinzufügen von Benutzern zu Ihrem InTune-Abonnement, Definieren von IT-Administratorrollen und Erstellen von Benutzer-und Gerätegruppen.

-   Konfigurieren der MDM-Zertifizierungsstelle für mobile Geräte – basierend auf Ihren Verwaltungsanforderungen, einschließlich:

    -   Festlegen von InTune als MDM-Autorität.

    -   Konfigurieren von Testgruppen, die zum Validieren von MDM-Verwaltungsrichtlinien verwendet werden sollen.

    -   Navigieren im InTune-Verwaltungsportal, um Informationen zu Benutzern und Geräten zu finden.

    -   Einrichten von InTune-Rollen (Helpdesk-Operator, Administratoren usw.)

    -   Konfigurieren der MDM-Verwaltungsrichtlinien und-Dienste wie folgt:

        -   App-Bereitstellung für jede unterstützte Plattform über Weblinks, MSI und/oder Deep Links.

        -   Bereitstellen von Office ProPlus auf Windows 10-Geräten

        -   Volumen Kaufprogramme für die APP-Bereitstellung, einschließlich des VSS-Speichers von Apple, Windows Store for Business und Googles Play for Work Store.

        -   Bereitstellung von e-Mail-, drahtlos-und VPN-Profilen, wenn Sie über eine vorhandene Zertifizierungsstelle, eine WLAN-oder VPN-Infrastruktur in Ihrer Organisation verfügen.

        -   Einrichten des Microsoft InTune Exchange Connectors (falls zutreffend).

        -   Geräte Konfigurationsprofile für unterstützte Geräteplattformen.

    -   Einrichten von Richtlinien für bedingten Zugriff.

    -   Konfigurieren und Bereitstellen von InTune-App-Schutzrichtlinien für jede unterstützte Plattform.

    -   Vorbereiten von Branchen-Apps für InTune-App-Schutzrichtlinien mit Empfehlungen zu den verfügbaren Optionen.

    -   Registrieren von Geräten jeder unterstützten Plattform zu Ihrem InTune-oder Konfigurations-Manager mit dem Microsoft InTune-Dienst.

    -   Herstellen einer Verbindung mit InTune Data Warehouse.

    -   Integrieren von InTune in:
        -   TeamViewer für Remoteunterstützung (TeamViewer-Abonnement erforderlich).

        -   Mobile Threat Defense-Partnerlösungen (Mobile Threat Defense Partner Solution-Abonnement ist erforderlich).

        -   Telecom Expense Management Solutions (Telecom Expense Management Solution-Abonnement ist erforderlich).

        -   Windows Defender Advanced Threat Protection (Windows E5-oder Microsoft 365 E5-Lizenzen sind erforderlich).

    -   Konfigurieren von Software Updates für entsprechende unterstützte Plattformen

    -   Ressourcen für die Planung der Benutzerakzeptanz.

- Einrichten von Windows Autopilot:

    - Konfigurieren und Einrichten von Microsoft InTune für Windows Autopilot.

    - Konfigurieren von dynamischen Azure Ad-Gruppen

    - Fügen Sie Ihr Unternehmensbranding in Azure AD hinzu.

    - Erstellen und Zuweisen von Geräten zu Windows Autopilot-Profilen (beispielsweise ein Windows Autopilot-Profil, das die Erstellung lokaler Administrator Konten einschränkt).

    - Passen Sie die Out-of-Box-Experience (OOBE) an die Anforderungen der Organisation an.

    - Konfigurieren der automatischen MDM-Registrierung in Azure AD und InTune.

    > [!NOTE]
    > Das Einrichten von Windows Autopilot außerhalb von InTune hat keinen Umfang für die Vorteile von "Leistung".

### <a name="enable-phase---co-management"></a>Phase-Co-Management aktivieren

Bereitstellen von Anleitungen zu:

-   Lizenzierung der Endbenutzer.

-   Hinzufügen von Benutzern zu Ihrem InTune-Abonnement, Definieren von IT-Administratorrollen und Erstellen von Benutzer-und Gerätegruppen (wenn InTune nicht installiert ist).

-   Einrichten von Azure Active Directory für die automatische MDM-Registrierung.

-   Richten Sie die hybride Azure Active Directory-Verknüpfung ein.

-   Einrichten des Cloud Management-Gateways.

-   Hinzufügen von Benutzern zu Ihrem InTune-Abonnement, Definieren von IT-Administratorrollen und Erstellen von Benutzer-und Gerätegruppen.

-   Vorbereiten von InTune (wenn InTune nicht installiert ist):

    -   Konfigurieren der MDM-Zertifizierungsstelle für mobile Geräte – basierend auf Ihren Verwaltungsanforderungen, einschließlich:

    -   Festlegen von InTune als MDM-Autorität.

    -   Konfigurieren von Testgruppen, die zum Validieren von MDM-Verwaltungsrichtlinien verwendet werden sollen.

    -   Navigieren im InTune-Verwaltungsportal, um Informationen zu Benutzern und Geräten zu finden.

    -   Einrichten von InTune-Rollen (Helpdesk-Operator, Administratoren usw.)

    -   Konfigurieren und Bereitstellen von InTune-App-Schutzrichtlinien für jede unterstützte Plattform.

    -   Registrieren von Windows 10-Geräten an InTune.

- Aktivieren Sie die Co-Verwaltung in der Configuration Manager-Konsole.

- Wechseln Sie die Arbeitsauslastungen auf InTune.

- Überwachen Sie die Co-Management-Aktivität in Ihrer Umgebung.

### <a name="enable-phase--azure-information-protection"></a>Aktivierungsphase – Azure Information Protection

Unterstützung für: 

- Kunden zum automatischen klassifizieren und Beschriften von Informationen in Office-Apps (wie Word, PowerPoint, Excel und Outlook), die unter Windows und mit dem Azure Information Protection-Client verwendet werden. 
- Dateien im Rest mithilfe des Azure Information Protection-Scanners.
- E-Mails bei der Übertragung mithilfe von Exchange Online-Nachrichtenfluss Regeln. 

Unterstützung finden Sie auch für Kunden, die Schutz mit Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OM) und Data Loss Prevention (DLP) anwenden möchten. 

Kunden erhalten Anleitungen zu folgenden Themen: 

- Aktivieren und konfigurieren Sie Ihren Mandanten.
- Erstellen und Einrichten von Bezeichnungen und Richtlinien
- Anwenden des Informationsschutzes auf Dokumente. 

> [!NOTE]
> **Möchten Sie mehr erfahren?** siehe [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility).

## <a name="next-steps"></a>Nächste Schritte

[Vorteile für EMS – ihre Aufgaben](EMS-your-responsibilities.md)
