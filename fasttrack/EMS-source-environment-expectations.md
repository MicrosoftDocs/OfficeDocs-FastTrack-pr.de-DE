---
title: Anforderungen an die Quellumgebung
description: Anforderungen an die Quellumgebung für die Verwendung der Vorteile des Centers für EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 03/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 6b3a5ed24ac254c3a989a584df0cbd89533ff1af
ms.sourcegitcommit: 5abb49be2bfa99110f17245839c3468318b8a3db
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/01/2019
ms.locfileid: "30359983"
---
# <a name="source-environment-expectations"></a>Anforderungen an die Quellumgebung

Wenn Sie den [Vorteil für Enterprise Mobility + Security (EMS)](EMS-fasttrack-benefit-for-EMS.md) nutzen, um Microsoft Azure Active Directory Premium und Microsoft InTune zur Verfügung zu stellen, muss Ihre Umgebung die in den folgenden Abschnitten beschriebenen Erwartungen erfüllen.

Möglicherweise verfügen Sie bereits über ein lokales Active Directory in Ihrer Organisation, das Sie in Enterprise Mobility + Security (EMS) oder in einzelne Dienste integrieren möchten, die das Rich-Identity-Management über eine einzige Konsole verwenden. Der Vorteil des Centers für Enterprise Mobility + Security (EMS) bietet Ihnen Unterstützung bei der Integration von Azure Active Directory in Ihre vorhandene lokale Active Directory-Umgebung.

In der folgenden Tabelle sind die Erwartungen für die vorhandene Quellumgebung für das Onboarding dargestellt.

|Aktivität|Anforderung an die Quellumgebung|
|------------|----------------------------------|
|Kern-on-Boarding|Active Directory-Gesamtstrukturen mit der auf Windows Server 2008 oder höher festgelegten Funktions Gesamtstrukturebene mit der folgenden Gesamtstrukturkonfiguration:<br /><br />-Einzelne Active Directory-Gesamtstruktur<br />-Mehrere Active Directory-Gesamtstrukturen </br></br>**Hinweis**: für alle Konfigurationen mit mehreren Gesamtstrukturen liegt die Active Directory-Verbunddienste (AD FS)-Bereitstellung außerhalb des Umfangs der Vorteile des Centers.|
|Azure AD Premium-on-Boarding|Das lokale Active Directory und seine Umgebung wurden für Azure AD Premium bereitgestellt, das die Behebung identifizierter Probleme umfasst, die die Integration in Azure AD und Azure AD Premium-Features verhindern.|
|InTune-on-Boarding| IT-Administratoren müssen bei der Planung der Bereitstellung von WiFi-und VPN-Profilen mit InTune bereits vorhandene Zertifizierungsstellen, WiFi-und VPN-Infrastrukturen in ihren Produktionsumgebungen verwenden.<br /><br /> **Hinweis**: der Dienst Vorteil umfasst keine Unterstützung für das Einrichten oder Konfigurieren von Zertifizierungsstellen, WiFi, VPN-Infrastrukturen oder Apple MDM-Push-Zertifikaten für  |
|Mitverwaltung|Mit der Zusammenarbeit sind IT-Administratoren für die Vorbereitung der lokalen Umgebung zuständig, die möglicherweise die Behebung von Problemen umfasst, die das gleichzeitige Verwalten von Windows 10-Geräten mit Configuration Manager und InTune verhindern.<br /><br />**Hinweis**: der Dienst Vorteil von "Leistung" bietet keine Unterstützung für das Einrichten oder Aktualisieren des Configuration Manager-Standortservers und/oder des Configuration Manager-Clients auf die Mindestanforderungen für die Unterstützung der Zusammenarbeit mit Windows 10-Geräten. |
|InTune integriert in Windows Defender Advanced Threat Protection (Windows Defender ATP)|Ihr Windows Defender ATP-Abonnement wurde basierend auf den Sicherheitsanforderungen Ihres Unternehmens aktiviert und konfiguriert.<br /><br />**Hinweis**: der Dienst Vorteil von "Serviceleistungen" bietet Unterstützung bei der Integration von InTune in Windows Defender ATP und der Erstellung von Geräte Konformitätsrichtlinien basierend auf der Bewertung der Windows 10-Risikostufe. Der Dienst Vorteil von Service bietet keine Unterstützung beim Erwerb, der Lizenzierung, der Aktivierung oder der Verwendung von Windows Defender ATP und der Security Center-Konsole. |
|Windows Autopilot|IT-Administratoren sind für die Registrierung Ihrer Geräte in Ihrer Organisation verantwortlich, indem Sie entweder den Hardwareanbieter in Ihrem Namen hochladen oder ihn selbst in den Windows Autopilot-Dienst hochladen. |
|Sicheres Bereitstellen von Outlook für iOS und Android mit InTune|<br /><br />-Benutzeridentitäten, die in Azure AD für Office 365 aktiviert sind.<br />-Exchange Online oder Hybrid Exchange, die mit zugewiesenen Benutzerlizenzen konfiguriert wurden.<br />|

> [!NOTE]
> **Möchten Sie mehr erfahren?** 
>  [Enterprise Mobility + Sicherheit](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>Nächste Schritte

[Vorteile des Centers für EMS-Onboarding-Phasen](EMS-onboarding-phases.md)
