---
title: Onboarding-Phasen
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 09/04/2019
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: Priority
ms.collection: FastTrack
description: 'Das Windows 10-Onboarding hat vier Hauptphasen: Einleiten, Analysieren, Korrigieren und Aktivieren.'
ms.openlocfilehash: 9eafd79decb7e7d4c98b177ed0dacf67737099dc
ms.sourcegitcommit: df949b40ade215de00f74771ffadf0d3be0de797
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/03/2019
ms.locfileid: "36712091"
---
# <a name="onboarding-phases"></a>Onboarding-Phasen

Das Windows 10-Onboarding hat vier Hauptphasen: Einleiten, Analysieren, Korrigieren und Aktivieren.

## <a name="initiate"></a>Einleiten

In dieser Phase werden der Onboarding-Prozess beschrieben, Ihre Daten überprüft und eine Einführungsbesprechung angesetzt. Dazu gehört das Verständnis Ihrer Windows 10-Intention.

## <a name="assess"></a>Analysieren

FastTrack-Experten arbeiten mit Ihnen zusammen, um Ihre Quellumgebung und die Anforderungen zu beurteilen. Stellen Sie sicher, dass System Center Configuration Manager auf die erforderliche Stufe aktualisiert wurde, um die Windows 10-Bereitstellung zu unterstützen. 

Wir stellen Ihnen empfohlene Optionen zur Bewertung Ihrer Windows 10-Apps bereit. FastTrack bietet Anleitungen zum Aktivieren der Nutzung von Desktop Analytics und führt Sie durch die Erstellung eines Bereitstellungsplans für Desktop Analytics.

FastTrack kann auch durch die Kompatibilitätsbewertung für Office 365 ProPlus unter Verwendung des Dashboards für die Office 365-Bereitschaft in Configuration Manager oder mit dem eigenständigen Bereitschafts-Toolkit für Office führen. Weitere Informationen zu den verfügbaren Diensten finden Sie unter [FastTrack Center-Vorteil für Office 365](O365-fasttrack-benefit-for-office-365.md). 

## <a name="remediate"></a>Korrigieren

Sie führen die Aufgaben im Korrekturplan für Ihre Quellumgebung aus, damit Sie die Anforderungen für das Onboarding erfüllen. Wir stellen eine Korrekturcheckliste bereit, anhand derer Sie Ihre Umgebung vorbereiten und überprüfen können, ob alle erforderlichen Komponenten vorhanden sind, damit ihre Quellumgebung den minimalen Voraussetzungen für eine erfolgreiche Bereitstellung gerecht wird. 

## <a name="enable"></a>Aktivieren

FastTrack bietet Anleitungen für das Upgrade Ihrer vorhandenen Geräte auf Windows 10 Enterprise, sofern sie die erforderlichen Hardwareanforderungen erfüllen. Upgradeanleitung wird bereitgestellt, um die vorhandene Bereitstellungsaktivität zu unterstützen. FastTrack bietet Empfehlungen und Anleitungen für ein direktes Upgrade auf Windows 10. Anleitungen stehen auch für eine Windows-Clean Image-Installation und [Windows Autopilot](EMS-onboarding-phases.md#windows-autopilot)-Bereitstellungsszenarien zur Verfügung. 

Wir unterstützen Sie bei der Bereitstellung von Office 365 ProPlus mit Configuration Manager als Teil der Windows 10-Bereitstellung. Weitere Informationen zu zugehörigen Diensten finden Sie unter [Office 365 ProPlus](O365-onboarding-and-migration.md#office-365-proplus).

Wir unterstützen Sie dabei, Ihre Organisation bei der Verwendung Ihrer vorhandenen Configuration Manager-Umgebung oder von Microsoft 365 mit Windows 10 Enterprise und Office 365 ProPlus auf dem neuesten Stand zu halten.

> [!NOTE]
> Wenn Sie nicht über Pläne oder Prozesse für die Bereitstellung und Wartung verfügen, können wir basierend auf dem Szenario des direkten Upgrades (empfohlen) oder von [Windows Autopilot](EMS-onboarding-phases.md#windows-autopilot) Anleitungen für bewährte Methoden bereitstellen.

## <a name="out-of-scope"></a>Nicht inbegriffen

FastTrack bietet keine Anleitungen für Folgendes:

- Upgrade von Configuration Manager auf den Current Branch.
- Erstellen von benutzerdefinierten Images für die Bereitstellung von Windows 10.
- Konvertieren eines Windows 10-Systems aus BIOS in UEFI (Unified Extensible Firmware Interface).
- Aktivieren von Windows 10-Sicherheitsfeatures. 
- Konfigurieren der Windows-Bereitstellungsdienste (WDS) für den PXE-Start (Preboot Execution Environment).
- Verwenden des Microsoft Deployment Toolkit (MDT) zum Erfassen und Bereitstellen von Windows 10-Images.
- Verwenden des Migrationstools für den Benutzerstatus (USMT).

  > [!NOTE]
  > Wenden Sie sich an einen [Microsoft-Partner](https://go.microsoft.com/fwlink/?linkid=2080150), um Unterstützung bei Diensten zu erhalten, deren Unterstützung nicht inbegriffen ist.

 