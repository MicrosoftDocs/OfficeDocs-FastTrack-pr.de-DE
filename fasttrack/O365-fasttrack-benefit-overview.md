---
title: Übersicht über den FastTrack Center-Vorteil
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 5/01/2020
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: Mit dem FastTrack Center-Vorteil für Office 365 arbeiten Sie remote mit FastTrack-Experten zusammen, um Ihre Office 365-Umgebung betriebsbereit zu machen sowie die Bereitstellung und Nutzung in Ihrer Organisation zu planen. Weitere Informationen zur Berechtigung für dieses Angebot finden Sie unter „FastTrack Center-Vorteil für Office 365“.
ms.openlocfilehash: f3dd071707d469041900f9bab86c07489ffcb4d0
ms.sourcegitcommit: 2775660fc5ccab2e92aee9383e326dba22b7a16b
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 05/01/2020
ms.locfileid: "43999891"
---
# <a name="fasttrack-center-benefit-overview"></a>Übersicht über den FastTrack Center-Vorteil

Mit dem FastTrack Center-Vorteil für Office 365 arbeiten Sie remote mit FastTrack-Experten zusammen, um Ihre Office 365-Umgebung betriebsbereit zu machen sowie die Bereitstellung und Nutzung in Ihrer Organisation zu planen. Weitere Informationen zur Berechtigung für dieses Angebot finden Sie unter [FastTrack Center-Vorteil für Office 365](O365-fasttrack-benefit-for-office-365.md).
  
Es werden folgende Themen behandelt:
- [Der FastTrack-Prozess](O365-fasttrack-process.md) 
- [Anforderungen an die Quellumgebung](O365-source-environment-expectations.md)
- [Phasen im Onboarding- und Migrationsprozess](O365-onboarding-and-migration.md)
- [Datenmigration](O365-data-migration.md)
- [FastTrack-Zuständigkeiten](O365-fasttrack-responsibilities.md)
- [Ihre Zuständigkeiten](O365-your-responsibilities.md) 
- [Anhang A: Migration aus IBM Domino zu Exchange Online](O365-from-ibm-domino-to-exchange-online.md)
- [Anhang B: FastTrack Center - zusätzlicher Vorteil](O365-fasttrack-additional-benefits.md)
- [Anhang C: FastTrack Center-HIPAA-Vertrag für Geschäftspartner](O365-hipaa-business-associate-agreement.md)
- [Anhang D: Übersicht über das FastTrack Center-Leistungsangebot für Office 365 US Government](US-Gov-appendix-overview.md)
    
Wenn das Onboarding abgeschlossen ist, wird Ihr Office 365-Mandant erstellt. Lizenzierte Benutzer können auf Office 365 über eine der folgenden Identitätsoptionen zugreifen:
- Cloud-Identitäten mit eindeutigen Office 365-Konten.
- Synchronisierte Identitäten mit Office 365-Konten, die von Ihrem lokalen Active Directory aus mithilfe von Azure Active Directory Connect (Kennworthash-Synchronisierung oder Pass-Through-Authentifizierung) synchronisiert werden. Für Kunden mit:
  - Eine einzelne Active Directory-Gesamtstrukturumgebung.
  - Unterstützte Active Directory-Topologie mit mehreren Gesamtstrukturen. Unterstützte Topologien finden Sie unter [Anforderungen an die Quellumgebung](O365-source-environment-expectations.md).
- Verbundidentitäten mit Office 365-Konten, für die Folgendes zutrifft:
  - Mit dem Tool Azure Active Directory Connect aus Active Directory synchronisiert, für Kunden mit:
      - einer einzelnen Active Directory-Gesamtstrukturkonfiguration.
      - einer einzelnen Active Directory-Kontogesamtstruktur (auch „Anmeldegesamtstruktur“ genannt) und einer einzelnen Active Directory-Ressourcen- Gesamtstrukturkonfiguration.
  - Sie werden mit einer lokalen Active Directory Federation-Verbunddienste (AD FS)-Infrastruktur konfiguriert, die:
      - Einen Verbund mit einer Windows Server 2012 R2 und höher AD FS-Rolle aus Ihrem lokalen Active Directory bildet.
      - Wenn erforderlich, eine Windows Application Proxy (WAP)-Rolle in Windows Server 2012 R2 und höher, die verwendet wird, um Ihre lokale AD FS-Infrastruktur im Internet zu veröffentlichen.
    > [!NOTE]
    > Die Bereitstellung und Konfiguration von AD FS und WAP erfolgen mit dem [Azure AD Connect-Konfigurations-Assistenten](https://go.microsoft.com/fwlink/?linkid=844794) von Ihrer lokalen Umgebung aus. 
  
- Lizenzierte Benutzer können nun auf [berechtigte Dienste und Pläne](M365-eligible-services-and-plans.md) zugreifen.

