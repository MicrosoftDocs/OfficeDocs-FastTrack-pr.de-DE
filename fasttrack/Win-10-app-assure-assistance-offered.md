---
title: Angebotene Unterstützung
ms.author: v-bermic@microsoft.com
author: rberg-steyer@microsoft.com
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: Normal
ms.collection: FastTrack
description: Wenn Sie einen der Windows 10- oder Microsoft 365-Dienste erwerben, zeigen Ihnen FastTrack-Spezialisten, wie Sie auf Windows 10 und Microsoft 365 Apps bereitstellen und ohne zusätzliche Kosten (mit einem berechtigenden Abonnement) auf dem neuesten Stand bleiben.
ms.openlocfilehash: 4cd513a4e0c1edda3598a6650bdea91d90f5584f
ms.sourcegitcommit: cd8426ce64dda56439933576e7da75b1c27f5de1
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 01/27/2021
ms.locfileid: "50016421"
---
# <a name="assistance-offered"></a>Angebotene Unterstützung  

Wenn Sie einen der Windows 10- oder Microsoft 365-Dienste erwerben (wie [in](eligibility.md)der Berechtigungsliste beschrieben), stellen die FastTrack-Experten Eine Empfehlung und Korrekturhilfen zur Verfügung, wenn bei der Bereitstellung neuerer Microsoft-Produkte, wie in den unterstützten Produkten von [Microsoft](#supported-microsoft-products)beschrieben, Probleme mit der App-Kompatibilität auftreten.

Um Hilfe zu erhalten, füllen Sie die [Serviceanfrage für App Assure](https://go.microsoft.com/fwlink/?linkid=2022721) aus.

Als Partner können Sie auch im Namen eines Kunden Hilfe auf der [FastTrack-Website](https://go.microsoft.com/fwlink/?linkid=780698) anfordern. Melden Sie sich dazu auf der Website an, wählen Sie den entsprechenden Kundendatensatz aus, und klicken Sie auf **Services**. Füllen Sie dann das Formular **Request Assistance for App Assure** aus.

> [!NOTE]
> Unterstützung ist in den folgenden Sprachen verfügbar: Deutsch, traditionelles und vereinfachtes Chinesisch (Ressourcen sprechen nur Man), Englisch, Französisch, Italienisch, Japanisch, Koreanisch, Portugiesisch (Brasilien) und Spanisch. 

## <a name="supported-microsoft-products"></a>Unterstützte Microsoft-Produkte

FastTrack bietet Unterstützung bei der Problembeseitigung für Apps, die auf den folgenden Microsoft-Produkte bereitgestellt werden:

### <a name="windows-10-and-microsoft-365-apps"></a>Windows 10 und Microsoft 365-Apps

- Apps, die unter Windows 7, Windows 8,1, Office 2010 und Office 2013 funktioniert haben, funktionieren ebenfalls unter Windows 10 und Microsoft 365 Apps.

### <a name="windows-10-on-arm"></a>Windows 10 auf ARM

- Apps, die unter Windows 7, Office 2010 oder höher funktioniert haben, funktionieren auf Windows 10- und Microsoft 365-Apps auf ARM64-Geräten.

> [!NOTE]
> Windows 10 unter ARM-Ausschlüssen und -Einschränkungen umfasst Apps, die auf Softwaretreibern angewiesen sind, die nicht mit ARM kompatibel sind, OpenGL oder OpenCL verwenden oder nur als 64-Bit(x64) verfügbar sind.

### <a name="microsoft-edge"></a>Microsoft Edge

- Wenn Ihre Web-Apps oder -Websites mit Internet Explorer 11, unterstützten Versionen von Google Chrome oder einer beliebigen Version von Microsoft Edge funktionieren, funktionieren sie auch mit Microsoft Edge.

Hinweise zur Bereitstellung von Microsoft Edge finden Sie unter [Übersicht über die Microsoft Edge-Kanäle](https://docs.microsoft.com/DeployEdge/microsoft-edge-channels). Da das Internet ständig weiterentwickelt wird, veröffentlichen wir eine Liste der bekannten [Änderungen, die Auswirkungen auf die Websitekompatibilität für Microsoft Edge haben](https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes).

### <a name="windows-virtual-desktop"></a>Windows Virtual Desktop

- Virtualisierte Apps, die auf dem Windows Server-Remotedesktop-Sitzungshost (RDSH) ausgeführt werden, können als Bestandteil von Windows Virtual Desktop auch unter Windows 10 Enterprise Multi-Session ausgeführt werden.
- Apps, die in einer Windows 7- oder Windows 10 Virtual Desktop Infrastructure (VDI)-Umgebung ausgeführt werden, werden auch unter Windows 7 Enterprise und Windows 10 Enterprise als Teil von Windows Virtual Desktop ausgeführt.
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


