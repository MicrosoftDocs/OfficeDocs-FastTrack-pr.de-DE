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
ms.openlocfilehash: 9e8712b7a1f324d02715527b22eca3f7e4db4656
ms.sourcegitcommit: 5d40d060bbcf4b266a0d6f3e4bbc151f94288b00
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/25/2021
ms.locfileid: "51996234"
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
<td><p>FastTrack bietet Windows Virtual Desktop-Bereitstellungsanleitungen, mit deren Hilfe Sie problemlos in diesen Desktop- und App-Virtualisierungsdienst integriert werden können, während Sie die Mehrsitzungsumgebung von Windows 10 nutzen, die für Microsoft 365 Apps for Enterprise mit integrierter Sicherheit und Verwaltung für Microsoft 365 optimiert ist.</p>
<p>Die FastTrack-Experten helfen Ihnen beim:</p>
<ul>
<li><p>Stellen Sie die WVD-Umgebung mit Windows 10 Enterprise multi-session + Microsoft 365 Apps for Enterprise mithilfe der folgenden Schritte zur Verfügung:</p>
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
<li><p>Bereitstellen von Microsoft Teams</p></li>
<li><p>Herstellen einer Verbindung mit Windows Virtual Desktop Clients</p></li>
</ul>
<p><strong>Die folgenden Bereiche sind nicht mehr</strong></p>
<ul>
<li><p>Projektverwaltung der Windows Virtual Desktop-Bereitstellung des Kunden.</p></li>
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
<li><p><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">WVD-Lizenzierungsanforderungen</a></p></li>
<li><p>Azure Networking:</p>
<ul>
<li><p>Subnetze für die &amp; VNET-Erstellung</p></li>
<li><p>Firewall/Netzwerksicherheitsgruppen</p></li>
<li><p>VPN /ExpressRoute</p></li>
<li><p>Routing von lokal zu Azure</p></li>
<li><p>Firewallregeln zum Zulassen der Konnektivität mit WVD</p>
<ul>
<li><p><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Dokumentreferenz</a></p></li>
</ul></li>
</ul></li>
<li><p>Allgemeines Setup von Azure Active Directory</p>
<ul>
<li><p>Identitätsstrategie <strong>(Wählen Sie NUR 1 der folgenden 3 Optionen aus)</strong></p>
<ul>
<li><p>Active Directory mit Azure AD Connect in Azure</p></li>
<li><p>Active Directory mit Azure AD Connect On Premise über VPN /ER</p></li>
<li><p>Active Directory Domain Services</p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
