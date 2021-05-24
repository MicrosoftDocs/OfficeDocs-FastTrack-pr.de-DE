---
title: Windows Virtual Desktop
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 7/01/2020
audience: ITPro
ms.topic: overview
ms.service: virtual-desktop
localization_priority: None
ms.collection: FastTrack
description: FastTrack bietet Windows Virtual Desktop-Bereitstellungsanleitungen, die Ihnen beim Onboarding auf diesem Desktop helfen.
ms.openlocfilehash: bdec1f6438a34b5ec023be5159329617bc5a78f9
ms.sourcegitcommit: e03f300ee223d72bc5af84d8d94e580dc649442c
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/21/2021
ms.locfileid: "52592438"
---
# <a name="windows-virtual-desktop"></a>Windows Virtual Desktop

<table>
<thead>
<tr class="header">
<th><strong>Dienst</strong></th>
<th><strong>FastTrack-Anleitungsdetails</strong></th>
<th><strong>Anforderungen an die Quellumgebung</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Windows Virtual Desktop</td>
<td><p>FastTrack bietet Windows Virtual Desktop-Bereitstellungsanleitungen, mit deren Hilfe Sie problemlos Windows 10 diesem Desktop- und App-Virtualisierungsdienst integriert werden können und gleichzeitig die für Microsoft 365 Apps für Enterprise optimierte Erfahrung mit integrierter Sicherheit und Verwaltung für Microsoft 365.</p>
<p>Die FastTrack-Experten helfen Ihnen beim:</p>
<ul>
<li><p>Stellen Sie die WVD-Umgebung mit Windows 10 Enterprise mehrsitzungs- und Microsoft 365 Apps für Enterprise wie folgt dar:</p>
<ul>
<li><p>Azure Marketplace Image</p></li>
<li><p>Freigegebenes Bild</p></li>
<li><p>Office Deployment Toolkit (ODT)</p></li>
</ul></li>
<li><p>Konfigurieren von FSLogix</p>
<ul>
<li><p>Bereitstellen von FSLogix Agent mit Profilcontainer</p></li>
<li><p>Bereitstellen von FSLogix Agent mit Office Container</p></li>
<li><p>Konfigurieren des FSLogix-Ordners mit Inhaltsausschlüssen</p></li>
</ul></li>
<li><p>Bereitstellen von Microsoft Edge</p></li>
<li><p>Bereitstellen Microsoft Teams</p></li>
<li><p>Verbinden verwenden Windows Virtual Desktop Clients</p></li>
</ul>
<p><strong>Die folgenden Bereiche sind nicht mehr</strong></p>
<ul>
<li><p>Project verwaltung der Virtuellen Desktopbereitstellung Windows Kunden.</p></li>
<li><p>Unterstützung vor Ort.</p></li>
<li><p>Drittanbieteranwendungsvirtualisierung/-bereitstellung.</p></li>
<li><p>Benutzerdefinierte Bilder.</p></li>
<li><p>Migrationen und Szenarien mit VMware und Citrix.</p></li>
<li><p>Linux-Szenarien.</p></li>
<li><p>Konvertierung oder Migration von Benutzerprofilen.</p></li>
</ul>
<p>Wenden Sie sich <a href="https://go.microsoft.com/fwlink/?linkid=2080150">an einen Microsoft-Partner,</a> um Unterstützung für diese Dienste zu erhalten.</p></td>
<td><p>Sie sollten bereits über Folgendes verfügen:</p>
<ul>
<li><p>[WVD-Lizenzierungsanforderungen](/azure/virtual-desktop/overview#requirements)</p></li>
<li><p>Azure Networking:</p>
<ul>
<li><p>Subnetze für die &amp; VNET-Erstellung</p></li>
<li><p>Firewall/Netzwerksicherheitsgruppen</p></li>
<li><p>VPN /ExpressRoute</p></li>
<li><p>Routing von lokal zu Azure</p></li>
<li><p>Firewallregeln zum Zulassen der Konnektivität mit WVD</p>
<ul>
<li><p>[Dokumentreferenz](/azure/virtual-desktop/overview#supported-remote-desktop-clients)</p></li>
</ul></li>
</ul></li>
<li><p>Azure Active Directory Allgemeines Setup</p>
<ul>
<li><p>Identitätsstrategie <strong>(Wählen Sie NUR 1 der folgenden 3 Optionen aus)</strong></p>
<ul>
<li><p>Active Directory mit Azure AD Verbinden in Azure</p></li>
<li><p>Active Directory mit Azure AD Verbinden Lokal über VPN /ER</p></li>
<li><p>Active Directory Domain Services</p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
