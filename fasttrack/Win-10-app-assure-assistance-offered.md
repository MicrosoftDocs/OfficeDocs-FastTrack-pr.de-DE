---
title: Angebotene Unterstützung
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: Normal
ms.collection: FastTrack
description: Wenn Sie einen der Windows 10- oder Microsoft 365-Dienste erwerben, zeigen Ihnen FastTrack-Spezialisten, wie Sie auf Windows 10 und Microsoft 365 Apps bereitstellen und ohne zusätzliche Kosten (mit einem berechtigenden Abonnement) auf dem neuesten Stand bleiben.
ms.openlocfilehash: 5252f880f126dd20de792e5cbdb18abc2473764d
ms.sourcegitcommit: dd7b2975ade7feaa12be079c8e54fa5612383538
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/22/2020
ms.locfileid: "48206252"
---
# <a name="assistance-offered"></a>Angebotene Unterstützung  

Wenn Sie einen der Windows 10-oder Microsoft 365-Dienste (wie in der [Anspruchsberechtigung](eligibility.md)beschrieben) erwerben, bieten die Spezialisten für die Fehlerbehebung bei der APP-Kompatibilitätsprobleme bei der Bereitstellungneuer Microsoft-Produkte, wie in [unterstützten Microsoft-Produkten](#supported-microsoft-products)beschrieben.

Um Hilfe zu erhalten, füllen Sie die [Serviceanfrage für App Assure](https://go.microsoft.com/fwlink/?linkid=2022721) aus.

Als Partner können Sie auch im Namen eines Kunden Hilfe auf der [FastTrack-Website](https://go.microsoft.com/fwlink/?linkid=780698) anfordern. Melden Sie sich dazu auf der Website an, wählen Sie den entsprechenden Kundendatensatz aus, und klicken Sie auf **Services**. Füllen Sie dann das Formular **Request Assistance for App Assure** aus.

> [!NOTE]
> Unterstützung ist in den folgenden Sprachen verfügbar: Deutsch, traditionelles und vereinfachtes Chinesisch (Ressourcen sprechen nur Man), Englisch, Französisch, Italienisch, Japanisch, Koreanisch, Portugiesisch (Brasilien) und Spanisch. 

## <a name="supported-microsoft-products"></a>Unterstützte Microsoft-Produkte

FastTrack bietet Unterstützung bei der Problembeseitigung für Apps, die auf den folgenden Microsoft-Produkte bereitgestellt werden:

### <a name="windows-10-and-microsoft-365-apps"></a>Windows 10 und Microsoft 365-Apps

- Apps, die unter Windows 7, Windows 8,1, Office 2010 und Office 2013 funktioniert haben, funktionieren ebenfalls unter Windows 10 und Microsoft 365 Apps.

### <a name="windows-10-on-arm"></a>Windows 10 auf dem Arm

- Apps, die an Windows 7, Office 2010 oder höheren Versionen arbeiteten, funktionieren mit Windows 10-und Microsoft 365-apps auf ARM64-Geräten.

> [!NOTE]
> Zu den Ausschlüssen und Einschränkungen von Windows 10 für Arm gehören apps, die auf Software Treibern basieren, die nicht in Arm kompatibel sind, OpenGL oder OpenCL verwenden oder nur in 64-Bit (x64) verfügbar sind.

### <a name="the-new-microsoft-edge"></a>Das neue Microsoft Edge

- Wenn Ihre Web-Apps oder-Websites mit Internet Explorer 11, unterstützte Versionen von Google Chrome oder eine beliebige Version von Microsoft Edge funktionieren, dann funktionieren diese auch mit dem neuen Microsoft Edge.

Hinweise zur Bereitstellung von Microsoft Edge finden Sie unter [Übersicht über die Microsoft Edge-Kanäle](https://docs.microsoft.com/DeployEdge/microsoft-edge-channels). Da das Internet ständig weiterentwickelt wird, veröffentlichen wir eine Liste der bekannten [Änderungen, die Auswirkungen auf die Websitekompatibilität für Microsoft Edge haben](https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes).

### <a name="windows-virtual-desktop"></a>Windows Virtual Desktop

- Virtualisierte Apps, die auf dem Windows Server-Remotedesktop-Sitzungshost (RDSH) ausgeführt werden, können als Bestandteil von Windows Virtual Desktop auch unter Windows 10 Enterprise Multi-Session ausgeführt werden.
- Apps, die in einer VDI-Umgebung (Virtual Desktop Infrastructure) Windows 7 oder Windows 10 ausgeführt werden, werden auch auf Windows 7 Enterprise und Windows 10 Enterprise als Teil des virtuellen Windows-Desktops ausgeführt.
- Apps, die unter Windows 7 oder Windows 10 auf Kundengeräten ausgeführt werden, können als Bestandteil von Windows Virtual Desktop auch unter Windows 7 Enterprise und Windows 10 Enterprise ausgeführt werden.

> [!NOTE]
> Die Kompatibilität mit Windows 10 Enterprise Multi-Session ist unter anderem in folgenden Fällen ausgeschlossen und eingeschränkt: 
> - Eingeschränkte Umleitung von Hardware.
> - A/V-intensive Apps können eine eingeschränkte Kapazität zur Folge haben.
> - 16-Bit-Apps werden für den 64-Bit-Windows Virtual Desktop nicht unterstützt.

Weitere Informationen finden Sie unter[Was ist Windows Virtual Desktop?](https://docs.microsoft.com/azure/virtual-desktop/overview) und [Windows 10 Enterprise Multi-Session FAQ](https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq).

> [!NOTE]
> FastTrack unternimmt alle zumutbaren Anstrengungen, um Kompatibilitätsprobleme zu beheben. 

## <a name="out-of-scope"></a>Nicht inbegriffen

Folgendes ist in den FastTrack-Diensten nicht inbegriffen:
- App-Bestandserfassung und Tests dazu, was unter Windows 10 und Microsoft 365 Apps funktioniert und was nicht. Weitere Hilfestellung zu diesem Vorgang, finden Sie im [Bereitstellungscenter für Desktop](https://go.microsoft.com/fwlink/?linkid=2080140). Wenn Sie an einer detaillierten Upgradebereitschaftsbewertung interessiert sind, füllen Sie das Formular [Kundenanforderung auf Bewertung der Bereitschaft für den modernen Desktop](https://go.microsoft.com/fwlink/?linkid=2053818) aus.
- Untersuchen von ISV-Apps von Drittanbietern auf Windows 10-Kompatibilität und Supportanweisungen. Weitere Informationen finden Sie unter [Desktopanalysen](https://docs.microsoft.com/sccm/desktop-analytics/overview).
- Dienste nur für das App-Packaging. Das Desktop App Assure-Team paketiert jedoch Apps, für die alle Probleme für Windows 10 behoben wurden, um sicherzustellen, dass sie in der Umgebung des Kunden bereitgestellt werden können.

Verantwortlichkeiten des Kunden umfassen:
- Erstellen eines App-Inventars.
- Überprüfen der Apps unter Windows 10 und Microsoft 365 Apps.

> [!NOTE]
> Microsoft kann keine Änderungen an Ihrem Quellcode vornehmen. Das Desktop App Assure-Team kann jedoch App-Entwickler beraten, wenn Quellcode für Ihre Apps verfügbar ist.

> [!NOTE]
> Wenden Sie sich an einen [Microsoft-Partner](https://go.microsoft.com/fwlink/?linkid=2080150), um Unterstützung bei Diensten zu erhalten, deren Unterstützung nicht inbegriffen ist.


