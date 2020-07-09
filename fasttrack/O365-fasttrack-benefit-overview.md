---
title: Übersicht über den FastTrack Center-Vorteil
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: With FastTrack Center Benefit for Office 365, you work remotely with FastTrack Specialists to get your Office 365 environment ready for use and plan rollout and usage within your organization. To learn more about eligibility, see FastTrack Center Benefit for Office 365.
ms.openlocfilehash: 3537f6effa5bd2c65f542496ea42ab70075621ce
ms.sourcegitcommit: 850211891e549e582e649a1dacdc2aa79b520b39
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/01/2020
ms.locfileid: "45011333"
---
# <a name="fasttrack-center-benefit-overview"></a>Übersicht über den FastTrack Center-Vorteil

With FastTrack Center Benefit for Office 365, you work remotely with FastTrack Specialists to get your Office 365 environment ready for use and plan rollout and usage within your organization. To learn more about eligibility, see [FastTrack Center Benefit for Office 365](O365-fasttrack-benefit-for-office-365.md).
  
Es werden folgende Themen behandelt:
- [Der FastTrack-Prozess](O365-fasttrack-process.md) 
- [Anforderungen an die Quellumgebung](O365-source-environment-expectations.md)
- [Phasen im Onboarding- und Migrationsprozess](O365-onboarding-and-migration.md)
- [Datenmigration](O365-data-migration.md)
- [FastTrack-Zuständigkeiten](O365-fasttrack-responsibilities.md)
- [Ihre Zuständigkeiten](O365-your-responsibilities.md) 
- [Anhang A: FastTrack Center – zusätzlicher Vorteil](O365-fasttrack-additional-benefits.md)
- [Anhang B: FastTrack Center-HIPAA-Vertrag für Geschäftspartner](O365-hipaa-business-associate-agreement.md)
- [Anhang C: Übersicht über das FastTrack Center-Leistungsangebot für Office 365 US Government](US-Gov-appendix-overview.md)
    
Your Office 365 tenant is created at the completion of onboarding. Licensed users can access Office 365 by using one of the following identity options:
- Cloud-Identitäten mit eindeutigen Office 365-Konten.
- Synchronized Identities with Office 365 accounts synchronized from your on-premises Active Directory with Azure Active Directory Connect (Password Hash Sync or Pass-through Authentication). These are for customers with:
  - Eine einzelne Active Directory-Gesamtstrukturumgebung.
  - Supported multi-forests Active Directory topology. For supported topologies, see [Source Environment Expectations](O365-source-environment-expectations.md).
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

