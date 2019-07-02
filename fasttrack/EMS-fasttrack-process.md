---
title: Der FastTrack-Prozess
description: Überblick über den FastTrack Center-Leistungsangebot Onboarding Prozess
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 07/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 5e4b7adf0dccbe66798a623f2c918f2ab0ebc8a0
ms.sourcegitcommit: ed0bbc37b887f2ea408575b1a667550b2797cc0a
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/01/2019
ms.locfileid: "35410694"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a>FastTrack Center-Leistungsangebotprozess für Enterprise Mobility + Security (EMS)
Wenn Ihre Organisation Anspruch auf den Center-Leistungsangebot für EMS hat, können Sie mit FastTrack Experten remote zusammenarbeiten, um Microsoft Azure Active Directory Premium, Microsoft Intune und Azure Information Protection betriebsbereit zu machen. Sie können auch Hilfe über die Website [FastTrack Website](https://www.microsoft.com/fasttrack/microsoft-365/ems)für Azure Information Protection, Microsoft Cloud App Security und Microsoft Advanced Threat Analytics anfordern. Unter [Berechtigte Dienstleistungen und Pläne](M365-eligible-services-and-plans.md) erfahren Sie, ob Ihre Organisation berechtigt ist.


Hier erfahren Sie, was mit dem Onboarding-Prozess verbunden ist:

-   [Übersicht zum Onboarding-Prozess](EMS-fasttrack-benefit-overview.md)

-   [Anforderungen an die Quellumgebung](EMS-source-environment-expectations.md)

-   [Phasen im Onboarding-Prozess](EMS-onboarding-phases.md)

-   [FastTrack-Zuständigkeiten](EMS-fasttrack-responsibilities.md) für jede Phase

-   [Kundenverantwortlichkeiten](EMS-your-responsibilities.md) für jede Phase

Nachstehend wird erklärt, was Sie nach Abschluss des Onboardings erwarten können:

-   Ihre EMS-Mandanten für die von Ihnen ausgewählten Dienstleistungen werden erstellt.

-   Lizenzierte Benutzer können auf EMS-Dienste über eine der folgenden Identitätsoptionen zugreifen:

    -   Cloud-Identitäten (eindeutige EMS-Konten)

    -   Synchronisierte Identitäten: EMS-Konten, die von Ihrem lokalen Active Directory aus mithilfe vom Azure Active Directory Connect-Tool (Kennworthash-Synchronisierung oder Pass-Through-Authentifizierung) synchronisiert werden. Diese Option ist für Kunden mit einer einzelne Gesamtstruktur oder mehreren Active Directory Domain Services-Gesamtstrukturen.

    -   Verbundidentitäten -- mit Microsoft EMS-Konten, für die Folgendes zutrifft:

        -   Synchronisiert aus Active Directory Domain Services mit dem Azure AD Connect-Tool. Diese Option ist für Kunden mit einer einzelnen Active Directory Domain Services-Gesamtstruktur Konfiguration.

        -   Verbunden mit Windows Server 2012 R2 Active Directory-Verbunddienste (AD FS) 2.0 oder höher von Ihrem lokalen Active Directory.

        -   Die Möglichkeit, Informationen sowohl im Ruhezustand als auch während des Transports mit Azure Information Protection automatisch zu klassifizieren und zu schützen. 

        -   Die Möglichkeit, Informationen innerhalb von lokalen Dateifreigaben und SharePoint-Servern mit dem Azure Information Protection Scanner zu erkennen. 

        -   Die Möglichkeit, Ihre Azure Information Protection Mandantenschlüssel innerhalb des Azure Key Vault zu verwalten. 
