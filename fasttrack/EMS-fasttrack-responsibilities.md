---
title: FastTrack-Zuständigkeiten
description: Die Zuständigkeiten von FastTrack, wenn Kunden den FastTrack-Leistungsangebot für EMS nutzen
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 06/04/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: c8fd871e-f1bc-43ec-a5f3-ad025df9b026
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: b4444aae990b064cf6b22921d897e0bd948f6ed1
ms.sourcegitcommit: 0e76ab0f36619dee923201098936573be14b4560
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/03/2019
ms.locfileid: "34673455"
---
# <a name="fasttrack-responsibilities"></a>FastTrack-Zuständigkeiten

Zu den Zuständigkeiten von FastTrack während des Onboardings zählen die folgenden.

## <a name="general"></a>Allgemein

-   Remoteunterstützung bei den erforderlichen Konfigurationsaktivitäten, wie in den Phasenbeschreibungen ausführlicher erläutert.

-   Bereitstellen verfügbarer Dokumentation, Softwaretools und Verwaltungskonsolen damit Sie Konfigurationsaufgaben verringern oder ganz weglassen können.

## <a name="initiate-phase"></a>Einleitungsphase

-   Vorbereiten des Onboardings in Zusammenarbeit mit Ihnen.

-   Festlegen, für welche berechtigten Dienste das Onboarding erfolgen soll.

## <a name="assess-phase"></a>Analysephase

-   Bereitstellen eines administrativen Überblicks.

-   Bereitstellen von Anleitungen zu:

    -   DNS-, Netzwerk- und Infrastrukturanforderungen.

    -   Clientanforderungen (benötigte Internetbrowser, Clientbetriebssysteme und Dienste).

    -   Bereitstellen von Benutzeridentitäten und -konten.

    -   Aktivieren berechtigter Dienste, die erworben und als Teil des Onboardings festgelegt wurden.

-   Festlegen des Zeitrahmens für Korrekturaktivitäten.

-   Bereitstellen einer Korrektur-Checkliste für Intune und Azure AD Premium.

## <a name="remediate-phase"></a>Korrekturphase

-   Halten von Konferenzgesprächen mit Ihnen gemäß dem vereinbarten Zeitplan, um den Fortschritt der Korrekturaktivitäten zu überprüfen, z.B. Sie werden durch die Installationsvoraussetzungen begleitet vor dem Onboarding eines Microsoft Cloud Services.

## <a name="enable-phase"></a>Aktivierungsphase
Bereitstellen von Anleitungen zu:

-   Aktivierung des Microsoft Online-Dienstmandanten oder -Abonnements.

-   Konfigurieren von TCP/IP-Protokollen und Firewallports.

-   Konfigurieren von DNS für berechtigte Dienste

-   Überprüfen der Konnektivität mit Microsoft-Onlinediensten.

-   Für eine einzelne Gesamtstruktur-Umgebung:

    -   Installieren eines Verzeichnissynchronisierungsservers zwischen Ihren Active Directory Domain Services (AD DS) und die in Frage kommenden Microsoft Online Services (nur Anleitung, falls erforderlich).

    -   Konfigurieren der verwalteten Authentifizierung (Kennworthashsynchronisierung oder Passthrough-Authentifizierung) mit dem Azure Active Directory Connect-Tool. (nur Anleitung, falls erforderlich).

        > [!NOTE]
        > Entwicklung und Implementierung für benutzerdefinierte Regelerweiterungen werden nicht berücksichtigt.

-   Für eine einzelne Gesamtstruktur mit Verbundidentitäten ist das Ziel: Installieren und Konfigurieren von Active Directory-Verbunddienste (AD FS) für die lokale Domänenauthentifizierung mit Intune in einer fehlertoleranten Konfiguration für einen Einzelstandort, falls erforderlich.

    > [!NOTE]
    > Für alle Konfigurationen mit mehreren Gesamtstrukturen liegen AD FS-Bereitstellungen außerhalb des Bereichs.

-   Testen der Funktionalität für einmaliges Anmelden, sofern bereitgestellt.

### <a name="enable-phase---microsoft-azure-active-directory-premium"></a>Aktivierungsphase -- Microsoft Azure Active Directory Premium

Bereitstellen von Anleitungen zu:

- Aktivieren Ihres Azure AD Premium-Mandanten.

- Konfigurieren von Firewallports.

- Konfigurieren von DNS für berechtigte Dienste.

- Überprüfung der Konnektivität zu Azure AD Premium-Diensten.

- Für eine einzelne Gesamtstruktur-Umgebung:

  -   Installieren eines Verzeichnissynchronisierungsservers zwischen Ihren Active Directory Domain Services (AD DS) und Azure AD Connect, falls erforderlich.

  -   Konfigurieren der verwalteten Authentifizierung Methode (Kennworthashsynchronisierung oder Passthrough-Authentifizierung) mit dem Azure Active Directory Connect-Tool.

- Für eine Umgebung mit mehreren Gesamtstrukturen:

  -   Installieren von Azure AD Connect-Synchronisierung, eingerichtet für eine Umgebung mit mehreren Gesamtstrukturen.
- Für Umgebungen mit einer einzigen und mehreren Gesamtstrukturen:
  - Konfigurieren der Azure Active Directory Pass-Through-Authentifizierung, falls erforderlich.
  - Konfigurieren der Azure Active Directory Einmaligen Anmeldens (Single Sign-On, SSO), falls erforderlich.
    > [!NOTE]
    > Die Azure Active Directory Pass-Through-Authentifizierung für Umgebungen mit mehreren Gesamtstrukturen wird unterstützt, wenn es Gesamtstruktur-Vertrauensstellungen zwischen Ihren Active Directory-Gesamtstrukturen gibt und wenn das Namensuffixrouting korrekt konfiguriert ist. Weitere Agents können auf mehreren lokalen Servern installiert werden, um hohe Verfügbarkeit für Anmeldeanforderungen zu bieten.

  - Weitere Informationen finden Sie unter [Azure Active Directory-Passthrough-Authentifizierung: Schnellstart](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-quick-start#step-1-check-prerequisites) und [Azure AD Connect: Nahtloses einmaliges Anmelden: Schnellstart](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start#step-1-check-prerequisites).
  - Weitere Informationen zu Einschränkungen der Pass-Through-Authentifizierung finden Sie unter [Azure Active Directory-Passthrough-Authentifizierung: aktuelle Einschränkungen](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-current-limitations).
  - Weitere Informationen zu Problemen beim nahtlosen einmaligen Anmelden finden Sie unter [Problembehandlung beim nahtlosen einmaligen Anmelden mit Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-troubleshoot-sso).

      > [!NOTE]
      > Kennworthashsynchronisierung und Kennwortrückschreiben unterstützen mehrere Gesamtstrukturen. Andere Rückschreibungsszenarien werden jedoch nicht unterstützt.

  - Konfigurieren der Synchronisierung zwischen lokalen Active Directory-Gesamtstrukturen und Microsoft Azure Active Directory Premium-Verzeichnis (Azure Active Directory).

    > [!NOTE]
    > Entwicklung und Implementierung für benutzerdefinierte Regelerweiterungen werden nicht berücksichtigt.

- Für eine einzelne Gesamtstruktur das Ziel Verbundidentitäten sind:

  -   Installieren und Konfigurieren von AD FS für die lokale Domänenauthentifizierung mit Azure AD Premium in einer fehlertoleranten Konfiguration für einen Einzelstandort, falls erforderlich.

  > [!NOTE]
  > Für alle Konfigurationen mit mehreren Gesamtstrukturen liegen AD FS-Bereitstellungen außerhalb des Bereichs.

- Testen der Funktionalität für einmaliges Anmelden (sofern bereitgestellt).

### <a name="enable-phase---azure-ad-premium---with-azure-ad-connect-and-ad-fs"></a>Aktivierungsphase – Azure AD Premium aktivieren – mit Azure AD Connect und AD FS

Bereitstellen von Anleitungen für die Einrichtung:

- Benutzerbereitstellung, einschließlich Lizenzierung.

- Azure AD Connect Verzeichnis-Synchronisation (mit Kennwortrücksetzung und Kennworthashsynchronisierung).

  - Azure Active Directory Self-Service-Kennwortzurücksetzung

  - Azure Multi-Factor Authentication.

  - Bis zu drei (3) oder mehr SaaS-Anwendungsintegrationen (Software as a Service) mit einmaligem Anmelden (Single Sign-On, SSO) aus dem[Azure Active Directory Marketplace](https://azure.microsoft.com/marketplace/active-directory/).

  - Automatische Benutzerbereitstellung für vorintegrierte SaaS-Anwendungen, wie sie in der [Liste der App-Integrationstutorials](https://docs.microsoft.com/de-DE/azure/active-directory/saas-apps/tutorial-list) aufgeführt sind, beschränkt auf die ausgehende Bereitstellung.

  - Benutzerdefinierter Anmeldebildschirm, einschließlich Logo, Text und Bildern.

  - Self-Service-und dynamische Gruppen (Gruppen).

  - Azure Active Directory-Anwendungsproxy.

  - Azure Active Directory Connect Health.

  - Bedingter Zugriff in Azure Active Directory Domain Services.

  - Azure Active Directory Nutzungsbedingungen.

  - Azure Active Directory Identity Protection.

  - Azure Active Directory Privileged Identity Management.

  - Azure Active Directory Domain Services ugriffsüberprüfungen.

### <a name="enable-phase---intune"></a>Aktivierungsphase – Intune

> [!IMPORTANT]
> FastTrack unterstützt nicht die klassische PC-Verwaltung von Windows 10 mit Intune. FastTrack unterstützt nur die Windows 10-Verwaltung durch Intune Mobile Device Management (MDM).

Unterstützung bei den folgenden Schritten:

-   Konfigurieren von Identitäten, die von Intune verwendet werden sollen, entweder durch Nutzung Ihres lokalen Active Directory oder von Cloud Identitäten (Azure Active Directory).

-   Lizenzierung Ihrer Endbenutzer.

-   Hinzufügen von Benutzern zu Ihrem Intune-Abonnement, Definieren von IT-Administrationsrollen und Erstellen von Benutzer- und Gerätegruppen.

-   Konfigurieren der Berechtigung für Ihre Mobile Device Management MDM), basierend auf Ihren Verwaltungsanforderungen, einschließlich:

    -   Festlegen von Intune als Ihre MDM-Autorität.

    -   Konfiguration von Testgruppen, die zur Validierung von MDM-Verwaltungsrichtlinien verwendet werden sollen.

    -   Navigieren durch das Intune-Administrationsportal, um Informationen über Benutzer und Geräte zu finden.

    -   Einrichten von Intune-Rollen (Helpdesk-Operator, Administratoren, usw).

    -   Konfigurieren von MDM-Verwaltungsrichtlinien und -Diensten wie:

        -   App-Bereitstellung für jede unterstützte Plattform über Weblinks, MSI und/oder Deep Links..

        -   Bereitstellung von Office ProPlus auf Windows 10-Geräten.

        -   Programme zum Kauf von Volumen für die App-Bereitstellung, einschließlich Apple's VPP, Windows Store for Business und Google Play for Work Store.

        -   Bereitstellung von E-Mail-, Wireless-Netzwerken und VPN-Profilen, wenn Sie eine bestehende Zertifizierungsstelle, Wi-Fi- oder VPN-Infrastruktur in Ihrer Organisation haben.

        -   Einrichten des Microsoft Intune Exchange Connector (falls vorhanden).

        -   Gerätekonfigurationsprofile für unterstützte Geräteplattformen.

    -   Einstellung von Richtlinien für den bedingten Zugriff.

    -   Konfiguration und Bereitstellung von Intune App Schutzrichtlinien für jede unterstützte Plattform.

    -   Vorbereitung von branchenspezifischen (LOB) Apps für Intune App Schutzrichtlinien, mit Anleitung zu den verfügbaren Optionen.

    -   Registrieren von Geräten jeder unterstützten Plattform für Ihren Intune oder Configuration Manager mit Microsoft Intune Service.

    -   Verbindung zum Intune Data Warehouse.

    -   Integration von Intune mit:
        -   Team Viewer für Remote-Unterstützung (Team Viewer-Abonnement erforderlich).

        -   Mobile Threat Defense Partnerlösungen (Mobile Threat Defense Partner Solution-Abonnement erforderlich).

        -   Telecom Expense Management Lösungen (Telecom Expense Management Solution-Abonnement ist erforderlich).

        -   Windows Defender Advanced Threat Protection (Windows E5 oder Microsoft 365 E5 Lizenzen sind erforderlich).

    -   Konfigurieren von Software-Updates für die jeweils unterstützten Plattformen.

    -   Ressourcen für das Planen der Benutzerakzeptanz.

- Einrichten des Windows-Autopiloten:

    - Konfigurieren und Einrichten von Microsoft Intune für Windows Autopilot.

    - Konfigurieren von dynamischen Gruppen in Azure AD

    - Einfügen Ihres Firmenlogo in Azure AD.

    - Erstellen und Zuweisen von Geräten zu Windows-Autopilot-Profilen (z.B. ein Windows-Autopilot-Profil, das die Erstellung eines lokalen Administratorkontos einschränkt).

    - Passen Sie die Out-of-Box-Erfahrung (OOBE) an, um den Anforderungen der Organisation zu entsprechen.

    - Konfigurieren der automatischen MDM-Registrierung in Azure AD und Intune.

    > [!NOTE]
    > Die Einrichtung von Windows Autopilot außerhalb von Intune ist für den FastTrack-Vorteil nicht möglich.

### <a name="enable-phase---co-management"></a>Aktivierungsphase – Co-Verwaltung

Unterstützung bei den folgenden Schritten:

-   Lizenzierung Ihrer Endbenutzer.

-   Hinzufügen von Benutzern zu Ihrem Intune-Abonnement, Definieren von IT-Administrationsrollen und Erstellen von Benutzer- und Gerätegruppen (falls Intune nicht installiert ist).

-   Einrichten von Azure Active Directory Domain Services für die automatische MDM-Registrierung.

-   Einrichten einer hybriden Azure Active Directory-Verknüpfung.

-   Einrichten des Cloud Management-Gateways.

-   Hinzufügen von Benutzern zu Ihrem Intune-Abonnement, Definieren von IT-Administrationsrollen und Erstellen von Benutzer- und Gerätegruppen.

-   Vorbereiten von Intune (falls Intune nicht installiert ist):

    -   Konfigurieren der Berechtigung für Ihre Mobile Device Management MDM), basierend auf Ihren Verwaltungsanforderungen, einschließlich:

    -   Festlegen von Intune als Ihre MDM-Autorität.

    -   Konfiguration von Testgruppen, die zur Validierung von MDM-Verwaltungsrichtlinien verwendet werden sollen.

    -   Navigieren durch das Intune-Administrationsportal, um Informationen über Benutzer und Geräte zu finden.

    -   Einrichten von Intune-Rollen (Helpdesk-Operator, Administratoren, usw).

    -   Konfiguration und Bereitstellung von Intune App Schutzrichtlinien für jede unterstützte Plattform.

    -   Registrieren von Windows 10-Geräten zu Ihrem Intune.

- Aktivierung der Co-Verwaltung in der Configuration Manager-Konsole.

- Wechseln der Arbeitsauslastung auf Intune.

- Überwachen der Co-Verwaltung Aktivitäten in Ihrer Umgebung.

### <a name="enable-phase--azure-information-protection"></a>Aktivierungsphase – Azure Information Protection

Unterstützung bei den folgenden Schritten: 

- Aktivierung und Konfiguration des Kundenmandanten.

- Erstellen und Einrichten von Bezeichnung und Richtlinien.

- Anwendung von Informationsschutz auf Dokumente. 

- Automatische Klassifizierung und Bezeichnung von Informationen in Office-Anwendungen (wie Word, PowerPoint, Excel und Outlook), die unter Windows ausgeführt werden und den Azure Information Protection Client verwenden.

- Verwendung von ruhenden Dateien mit dem Azure Information Protection Scanner.

- Überwachung von E-Mails während des Versands unter Verwendung von Exchange Online Nachrichtenflussregeln.

Anleitungen werden auch für Kunden bereitgestellt, die Schutz mit Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME) und Data Loss Prevention (DLP) anwenden möchten.

> [!NOTE]
> **Mehr Informationen** finden Sie unter[Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility).

## <a name="next-steps"></a>Nächste Schritte

[FastTrack-Vorteil für EMS – Ihre Verantwortung](EMS-your-responsibilities.md)
