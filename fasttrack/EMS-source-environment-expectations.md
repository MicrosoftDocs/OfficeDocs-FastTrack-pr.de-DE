---
title: Anforderungen an die Quellumgebung
description: Anforderungen an die Quellumgebung für die Verwendung der Vorteile des Centers für EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: a512e97f48df7fc3040478f4e35fe0c357ef7ce3
ms.sourcegitcommit: ccdd833af651980ea6ac655bf32b4262474b35d4
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/01/2019
ms.locfileid: "33513150"
---
# <a name="source-environment-expectations"></a>Anforderungen an die Quellumgebung

Wenn Sie die [Vorteile von "schnell Center" für Enterprise Mobility + Security (EMS)](EMS-fasttrack-benefit-for-EMS.md) nutzen, um Microsoft Azure Active Directory Premium, Microsoft InTune und Azure Information Protection bereitzustellen, muss Ihre Umgebung die Erwartungen erfüllen. in den folgenden Abschnitten beschrieben.

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
|Sicheres Bereitstellen von Outlook für IOS und Android mit InTune|<br /><br />-Benutzeridentitäten, die in Azure AD für Office 365 aktiviert sind.<br />-Exchange Online oder Hybrid Exchange, die mit zugewiesenen Benutzerlizenzen konfiguriert wurden.<br />|
|Azure Information Protection (P2 oder EMS E5)|<br /><br />Kunden sollten bereits: <br /> -Verwenden von Azure AD.<br />-Verwenden Sie entweder Windows oder IOS (andere Betriebssysteme befinden sich außerhalb des Bereichs).<br /> -Verwenden Sie Office-Clients neuer als Office 2010 SP2, die nicht auf Office Online als hauptclient Vertrauen. <br /> -Haben ihre wichtigsten Dateifreigabe-Speicherorte.  <br /> -Upgrade von Active Directory Rights Management Services (AD RMS) durchgeführt. <br /> -Sie haben eine genehmigte Klassifizierungs Taxonomie. <br /> – Verstehen Sie alle behördlichen Einschränkungen für ihre geschützte Schlüsselverwaltung. <br />|
|Azure Information Protection-Scanner|<br /><br /> Kunden sollten bereits: <br /> -Verwenden Sie Windows Server 2012 R2 oder Windows Server 2016.<br /> -Über eine Internetverbindung verfügen. <br /> -Weisen Sie Microsoft SQL Server 2012 in einer lokalen oder Remoteinstanz an.  <br /> -Ein Dienstkonto für das lokale Active Directory erstellt und mit Azure AD synchronisiert.  <br /> -Haben Sie AzInfoProtection. exe heruntergeladen. <br /> -Haben Sie Bezeichnungen für die automatische Klassifizierung/Schutz konfiguriert.<br />|

> [!NOTE]
> **Möchten Sie mehr erfahren?** 
>  [Enterprise Mobility + Sicherheit](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>Nächste Schritte

[Vorteile des Centers für EMS-Onboarding-Phasen](EMS-onboarding-phases.md)
