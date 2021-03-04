---
title: Datenmigration
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 2/24/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Sie können die Migration von E-Mail- und Dateidaten in ihrer Quellumgebung auf Office 365 (Exchange Online, SharePoint Online und OneDrive for Business) mithilfe von FastTrack migrieren. Die Art der von uns bereitgestellten Unterstützung hängt von der Anzahl der Office 365-Lizenzen ab.
ms.openlocfilehash: b02c7c863cdc689fab4a6545ac1acc84f6b03fc2
ms.sourcegitcommit: cf630a48697177b9cce6c0fbc67a7e7a0b752167
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/03/2021
ms.locfileid: "50416612"
---
# <a name="data-migration"></a><span data-ttu-id="fcf34-104">Datenmigration</span><span class="sxs-lookup"><span data-stu-id="fcf34-104">Data Migration</span></span>

<span data-ttu-id="fcf34-105">Sie können die Migration von E-Mail- und Dateidaten in ihrer Quellumgebung auf Office 365 (Exchange Online, SharePoint Online und OneDrive for Business) mithilfe von FastTrack migrieren.</span><span class="sxs-lookup"><span data-stu-id="fcf34-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="fcf34-106">Die Art der von uns bereitgestellten Unterstützung hängt von der Anzahl der Office 365-Lizenzen ab:</span><span class="sxs-lookup"><span data-stu-id="fcf34-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="fcf34-107">**Für Office 365-Mandanten mit 150 bis 499-Lizenzen**: FastTrack bietet nur Migrationsanleitungen. Sie sind für die Durchführung der Datenmigration verantwortlich.</span><span class="sxs-lookup"><span data-stu-id="fcf34-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="fcf34-108">Wir führen Sie durch die Dokumentation, die Ihnen hilft, ﻿kostenlose Tools für die Durchführung einer Self-Service-Migration zu planen und zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="fcf34-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="fcf34-109">**Für Office 365-Mandanten mit 500 oder mehr Lizenzen**: FastTrack bietet Migrationsanleitungen und Datenmigrationsdienste.</span><span class="sxs-lookup"><span data-stu-id="fcf34-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="fcf34-110">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des Office 365-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Daten.</span><span class="sxs-lookup"><span data-stu-id="fcf34-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="fcf34-111">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="fcf34-111">You create and schedule your migration events.</span></span> <span data-ttu-id="fcf34-112">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="fcf34-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="fcf34-113">Wenn Sie einen kommerziellen Plan vor dem 1.9.2017 erworben oder verlängert haben, benötigen Sie nur 150 Lizenzen, um für Datenmigrationsdienste qualifiziert zu sein.</span><span class="sxs-lookup"><span data-stu-id="fcf34-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="fcf34-114">Bei Plänen für Bildungseinrichtungen sind nur Lehrpersonal und Mitarbeiter für Migrationsdienste berechtigt.</span><span class="sxs-lookup"><span data-stu-id="fcf34-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="fcf34-115">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="fcf34-115">Considerations</span></span>

  - <span data-ttu-id="fcf34-116">Ihre Quellumgebungen müssen bestimmte Erwartungen erfüllen, um Daten zu Office 365 zu migrieren.</span><span class="sxs-lookup"><span data-stu-id="fcf34-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="fcf34-117">Weitere Informationen zu den Erwartungen bezüglich der Quellumgebung für Exchange, SharePoint und OneDrive for Business finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="fcf34-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="fcf34-118">Für die Bereitstellung von Datenmigrationsdiensten benötigen wir einen geeigneten Zugriff auf Ihre Quellumgebungen und den Office 365-Mandanten.</span><span class="sxs-lookup"><span data-stu-id="fcf34-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="fcf34-119">Unsere Datenmigrationsdienste sind nicht für Daten vorgesehen, die besonderen rechtlichen oder behördlichen Vorschriften unterliegen.</span><span class="sxs-lookup"><span data-stu-id="fcf34-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="fcf34-120">Wenn wir Ihre Daten migrieren, können sie an einen beliebigen Ort, an dem wir über Einrichtungen verfügen, übertragen, dort gespeichert und verarbeitet werden (sofern nicht anderweitig für Ihr FastTrack-Migrationsprojekt angegeben).</span><span class="sxs-lookup"><span data-stu-id="fcf34-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="fcf34-121">Wir übernehmen keine Garantie für die Geschwindigkeit der E-Mail- oder Dateimigration.</span><span class="sxs-lookup"><span data-stu-id="fcf34-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="fcf34-122">Unvorhergesehene Probleme (wie unlesbare oder fehlerhafte Elemente in der Quellumgebung) verhindern möglicherweise, dass einige ihrer Datenelemente migriert werden können.</span><span class="sxs-lookup"><span data-stu-id="fcf34-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="fcf34-123">Externe Faktoren, die außerhalb unserer Kontrolle stehen (z. B. Änderungen an den Programmierschnittstellen von Drittanbietern) können zu Änderungen, Verzögerungen oder der Sperrung unserer Datenmigrationsdienste führen.</span><span class="sxs-lookup"><span data-stu-id="fcf34-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="fcf34-124">Verfügbarkeit des Migrationsdiensts</span><span class="sxs-lookup"><span data-stu-id="fcf34-124">Migration service availability</span></span>

  - <span data-ttu-id="fcf34-125">**Für kommerzielle Kunden und britische Behörden:** Wir stellen Datenmigrationsdienste rund um die Uhr an sieben (7) Tagen pro Woche bereit.</span><span class="sxs-lookup"><span data-stu-id="fcf34-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="fcf34-126">**Für Kunden von US-amerikanischen Behörden/Verteidigungsministerium:** Wir stellen Datenmigrationsdienste rund um die Uhr an fünf (5) Werktagen pro Woche bereit.</span><span class="sxs-lookup"><span data-stu-id="fcf34-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="fcf34-127">Migration zu Exchange Online</span><span class="sxs-lookup"><span data-stu-id="fcf34-127">Migration to Exchange Online</span></span>

<span data-ttu-id="fcf34-128">Wenn Sie sich für die Migration Ihrer E-Mails zu Exchange Online mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit.</span><span class="sxs-lookup"><span data-stu-id="fcf34-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="fcf34-129">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des Exchange Online-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Postfächer.</span><span class="sxs-lookup"><span data-stu-id="fcf34-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="fcf34-130">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="fcf34-130">You create and schedule your migration events.</span></span> <span data-ttu-id="fcf34-131">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="fcf34-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="fcf34-132">Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass E-Mail-Nachrichten von entsprechend geplanten und berechtigten Quellpostfächern ihrer Quellumgebungen zu Exchange Online migriert wurden.</span><span class="sxs-lookup"><span data-stu-id="fcf34-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="fcf34-133">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="fcf34-133">Considerations</span></span>

  - <span data-ttu-id="fcf34-134">Bevor Sie die Migration durchführen können, müssen Sie den FastTrack-Onboarding-Vorgang für Exchange Online durchführen.</span><span class="sxs-lookup"><span data-stu-id="fcf34-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="fcf34-135">Wenn Sie das Onboarding selbst durchgeführt haben, müssen Sie die erforderlichen Überprüfungen und Voraussetzungen erfüllen.</span><span class="sxs-lookup"><span data-stu-id="fcf34-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="fcf34-136">Ausführliche Informationen finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="fcf34-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="fcf34-137">FastTrack migriert nur zu aktiven Office 365-Postfächern.</span><span class="sxs-lookup"><span data-stu-id="fcf34-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="fcf34-138">Sie müssen bestimmte Anforderungen erfüllen, wenn Sie von einer lokalen Exchange-Umgebung migrieren möchten.</span><span class="sxs-lookup"><span data-stu-id="fcf34-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="fcf34-139">Weitere Informationen finden Sie unter [Voraussetzungen für die Hybridbereitstellung](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="fcf34-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="fcf34-140">Sämtliche Quellumgebungen müssen über die neuesten Service Packs (SP) verfügen und auf der Rollup (RU)-/Kumulativen Update (KU)-Ebene für das entsprechende Produkt in der Quellumgebung vorhanden sein.</span><span class="sxs-lookup"><span data-stu-id="fcf34-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="fcf34-141">Verteilerlisten (*MailEnabledGroup*-Objekte) und externe Kontakte (*MailEnabledContact*-Objekte) im lokalen Active Directory befinden, sind nicht Bestandteil einer Postfachdatenmigration.</span><span class="sxs-lookup"><span data-stu-id="fcf34-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="fcf34-142">Sie können Sie jedoch mithilfe von Azure Active Directory (Azure AD) Connect synchronisieren.</span><span class="sxs-lookup"><span data-stu-id="fcf34-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="fcf34-143">Quellumgebungen</span><span class="sxs-lookup"><span data-stu-id="fcf34-143">Source environments</span></span>

<span data-ttu-id="fcf34-144">Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:</span><span class="sxs-lookup"><span data-stu-id="fcf34-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="fcf34-145">aus einer einzelnen oder aus mehreren Active Directory-Gesamtstrukturen mit einer oder mehreren Exchange-Organisationen (jedes Exchange-E-Mail-System muss Exchange 2010 oder höher sein).</span><span class="sxs-lookup"><span data-stu-id="fcf34-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="fcf34-146">aus einer einzelnen IMAP-fähigen E-Mail-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="fcf34-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="fcf34-147">aus einer G Suite-Umgebung (nur Gmail, Kontakte und Kalender).</span><span class="sxs-lookup"><span data-stu-id="fcf34-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="fcf34-148">Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:</span><span class="sxs-lookup"><span data-stu-id="fcf34-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="fcf34-149"><strong>Quellumgebung</strong></span><span class="sxs-lookup"><span data-stu-id="fcf34-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="fcf34-150"><strong>Migrationstyp</strong></span><span class="sxs-lookup"><span data-stu-id="fcf34-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="fcf34-151"><strong>Was wird migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="fcf34-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="fcf34-152"><strong>Was wird nicht migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="fcf34-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="fcf34-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="fcf34-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="fcf34-154">
<strong>Hinweis:</strong> Informationen zu lokalen Exchange-Abhängigkeiten finden Sie unter <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Voraussetzungen für die Hybridbereitstellung</span></a>.</span><span class="sxs-lookup"><span data-stu-id="fcf34-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="fcf34-155">Migration mit Hybridbereitstellung</span><span class="sxs-lookup"><span data-stu-id="fcf34-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="fcf34-156">E-Mails</span><span class="sxs-lookup"><span data-stu-id="fcf34-156">Emails</span></span></li>
<li><span data-ttu-id="fcf34-157">Serverseitige Postfachregeln</span><span class="sxs-lookup"><span data-stu-id="fcf34-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="fcf34-158">Stellvertretungen</span><span class="sxs-lookup"><span data-stu-id="fcf34-158">Delegates</span></span></li>
<li><span data-ttu-id="fcf34-159">Postfachkontakte</span><span class="sxs-lookup"><span data-stu-id="fcf34-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="fcf34-160">Kalender</span><span class="sxs-lookup"><span data-stu-id="fcf34-160">Calendar</span></span> </li>
<li> <span data-ttu-id="fcf34-161">Aufgaben</span><span class="sxs-lookup"><span data-stu-id="fcf34-161">Tasks</span></span> </li>
<li> <span data-ttu-id="fcf34-162">E-Mails mit Rechteverwaltung</span><span class="sxs-lookup"><span data-stu-id="fcf34-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="fcf34-163">Verschlüsselte E-Mails</span><span class="sxs-lookup"><span data-stu-id="fcf34-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="fcf34-164">Signaturen</span><span class="sxs-lookup"><span data-stu-id="fcf34-164">Signatures</span></span> </li>
<li> <span data-ttu-id="fcf34-165">Persönliches Archiv, das mit dem Benutzerpostfach migriert wird</span><span class="sxs-lookup"><span data-stu-id="fcf34-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="fcf34-166">Wiederherstellbare Elemente</span><span class="sxs-lookup"><span data-stu-id="fcf34-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="fcf34-167">Öffentliche Ordner</span><span class="sxs-lookup"><span data-stu-id="fcf34-167">Public folders</span></span> </li>
<li> <span data-ttu-id="fcf34-168">E-Mail, die die zulässige Nachrichtengröße überschreitet.</span><span class="sxs-lookup"><span data-stu-id="fcf34-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="fcf34-169">Journalarchiv oder eine beliebige Archivlösung von Drittanbietern</span><span class="sxs-lookup"><span data-stu-id="fcf34-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="fcf34-170">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="fcf34-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="fcf34-171">Archivdaten aus PST-Dateien</span><span class="sxs-lookup"><span data-stu-id="fcf34-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="fcf34-172">Beschädigte Elemente</span><span class="sxs-lookup"><span data-stu-id="fcf34-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="fcf34-173">Inaktive Postfächer</span><span class="sxs-lookup"><span data-stu-id="fcf34-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="fcf34-174">Clientseitige Postfachregeln</span><span class="sxs-lookup"><span data-stu-id="fcf34-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="fcf34-175"><strong>G Suite-Umgebung (nur Gmail, Kontakte und Kalender)</strong></span><span class="sxs-lookup"><span data-stu-id="fcf34-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="fcf34-176">
<strong>Hinweis:</strong> Ihre G Suite-Umgebung muss die voraussetzungen erfüllen, die unter <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Ausführen einer G Suite-Migration beschrieben sind.</a></span><span class="sxs-lookup"><span data-stu-id="fcf34-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="fcf34-177">Übernahmemigration oder mehrstufige Migration</span><span class="sxs-lookup"><span data-stu-id="fcf34-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="fcf34-178">E-Mails</span><span class="sxs-lookup"><span data-stu-id="fcf34-178">Emails</span></span> </li>
<li> <span data-ttu-id="fcf34-179">Postfachkontakte (es werden maximal drei E-Mail-Adressen pro Kontakt migriert)</span><span class="sxs-lookup"><span data-stu-id="fcf34-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="fcf34-180">Kalender</span><span class="sxs-lookup"><span data-stu-id="fcf34-180">Calendar</span></span> </li>
<li> <span data-ttu-id="fcf34-181">Bezeichnungen</span><span class="sxs-lookup"><span data-stu-id="fcf34-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="fcf34-182">Regeln</span><span class="sxs-lookup"><span data-stu-id="fcf34-182">Rules</span></span> </li>
<li> <span data-ttu-id="fcf34-183">Stellvertretungen</span><span class="sxs-lookup"><span data-stu-id="fcf34-183">Delegates</span></span> </li>
<li> <span data-ttu-id="fcf34-184">Signaturen</span><span class="sxs-lookup"><span data-stu-id="fcf34-184">Signatures</span></span> </li>
<li> <span data-ttu-id="fcf34-185">Aufgaben</span><span class="sxs-lookup"><span data-stu-id="fcf34-185">Tasks</span></span> </li>
<li> <span data-ttu-id="fcf34-186">E-Mails oder Anhänge, die die zulässige Nachrichtengröße überschreiten</span><span class="sxs-lookup"><span data-stu-id="fcf34-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="fcf34-187">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="fcf34-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="fcf34-188">Archivdaten aus PST-Dateien oder einer Drittanbieter-Archivlösung (z. B. Google Vault)</span><span class="sxs-lookup"><span data-stu-id="fcf34-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="fcf34-189">E-Mails mit Rechteverwaltung oder Verschlüsselung</span><span class="sxs-lookup"><span data-stu-id="fcf34-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="fcf34-190">Beschädigte Elemente</span><span class="sxs-lookup"><span data-stu-id="fcf34-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="fcf34-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="fcf34-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="fcf34-192">Google-Gruppen</span><span class="sxs-lookup"><span data-stu-id="fcf34-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="fcf34-193">Ressourcenpostfächer</span><span class="sxs-lookup"><span data-stu-id="fcf34-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="fcf34-194">Inaktive Postfächer</span><span class="sxs-lookup"><span data-stu-id="fcf34-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="fcf34-195">Urlaubseinstellungen und Einstellungen für automatische Antworten</span><span class="sxs-lookup"><span data-stu-id="fcf34-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="fcf34-196">Freigegebene Kalender, Cloudanlagen, Google Hangout-Links und Ereignisfarben</span><span class="sxs-lookup"><span data-stu-id="fcf34-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="fcf34-197">\*\*Hangout-Unterhaltungen, die als Beschriftungen gespeichert wurden, werden migriert.</span><span class="sxs-lookup"><span data-stu-id="fcf34-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="fcf34-198"><strong>IMAP4-Quelle (wie Domino, GroupWise oder Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="fcf34-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="fcf34-199">Migration mit systemeigenen IMAP4-Tools</span><span class="sxs-lookup"><span data-stu-id="fcf34-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="fcf34-200">E-Mails</span><span class="sxs-lookup"><span data-stu-id="fcf34-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="fcf34-201">Regeln</span><span class="sxs-lookup"><span data-stu-id="fcf34-201">Rules</span></span> </li>
<li> <span data-ttu-id="fcf34-202">Stellvertretungen</span><span class="sxs-lookup"><span data-stu-id="fcf34-202">Delegates</span></span> </li>
<li> <span data-ttu-id="fcf34-203">Verteilerlisten</span><span class="sxs-lookup"><span data-stu-id="fcf34-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="fcf34-204">Externe Kontakte</span><span class="sxs-lookup"><span data-stu-id="fcf34-204">External contacts</span></span> </li>
<li> <span data-ttu-id="fcf34-205">E-Mail-aktivierte Benutzer</span><span class="sxs-lookup"><span data-stu-id="fcf34-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="fcf34-206">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="fcf34-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="fcf34-207">Postfachkontakte</span><span class="sxs-lookup"><span data-stu-id="fcf34-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="fcf34-208">Kalender</span><span class="sxs-lookup"><span data-stu-id="fcf34-208">Calendar</span></span> </li>
<li> <span data-ttu-id="fcf34-209">Signaturen</span><span class="sxs-lookup"><span data-stu-id="fcf34-209">Signatures</span></span> </li>
<li> <span data-ttu-id="fcf34-210">Aufgaben</span><span class="sxs-lookup"><span data-stu-id="fcf34-210">Tasks</span></span> </li>
<li> <span data-ttu-id="fcf34-211">E-Mails, die die zulässige Nachrichtengröße überschreiten</span><span class="sxs-lookup"><span data-stu-id="fcf34-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="fcf34-212">Archivdaten</span><span class="sxs-lookup"><span data-stu-id="fcf34-212">Archive data</span></span> </li>
<li> <span data-ttu-id="fcf34-213">Verschlüsselte E-Mail-Nachrichten</span><span class="sxs-lookup"><span data-stu-id="fcf34-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="fcf34-214">Beschädigte Elemente</span><span class="sxs-lookup"><span data-stu-id="fcf34-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="fcf34-215">Inaktive Postfächer</span><span class="sxs-lookup"><span data-stu-id="fcf34-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="fcf34-216">FastTrack-Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="fcf34-216">FastTrack responsibilities</span></span>

<span data-ttu-id="fcf34-217">Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="fcf34-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="fcf34-218">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="fcf34-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="fcf34-219">Unsere FastTrack-Spezialisten führen außerdem die folgenden Aktivitäten speziell für Exchange-Migrationen durch:</span><span class="sxs-lookup"><span data-stu-id="fcf34-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="fcf34-220">Bereitstellen von Anleitungen, die Ihnen dabei helfen, die Koexistenz von SMTP-E-Mail-Routing zwischen Ihrer Quellumgebung und Exchange Online zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="fcf34-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="fcf34-221">Ihre Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="fcf34-221">Your responsibilities</span></span>

<span data-ttu-id="fcf34-222">Während des Migrationsprojekts führen Sie Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="fcf34-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="fcf34-223">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="fcf34-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="fcf34-224">Sie führen außerdem die folgenden Aktivitäten speziell für Exchange-Migrationen aus:</span><span class="sxs-lookup"><span data-stu-id="fcf34-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="fcf34-225">Durchführen des FastTrack-Onboarding-Vorgangs für Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="fcf34-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="fcf34-226">Wenn Sie das Onboarding selbst durchgeführt haben, müssen Sie die erforderlichen Überprüfungen und Voraussetzungen erfüllen.</span><span class="sxs-lookup"><span data-stu-id="fcf34-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="fcf34-227">Ausführliche Informationen finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="fcf34-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="fcf34-228">Installieren der entsprechenden Clientsoftwareebene gemäß den Office 365-Richtlinien.</span><span class="sxs-lookup"><span data-stu-id="fcf34-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="fcf34-229">Details finden Sie unter [Der moderne Arbeitsplatz](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="fcf34-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="fcf34-230">Erfüllen bestimmter Anforderungen, wenn Sie von einer lokalen Exchange-Umgebung migrieren möchten.</span><span class="sxs-lookup"><span data-stu-id="fcf34-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="fcf34-231">Weitere Informationen finden Sie unter [Voraussetzungen für die Hybridbereitstellung](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="fcf34-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="fcf34-232">Sicherstellen, dass jede Quellumgebung über das neueste Service Pack (SP) und Rollup (RU)/Cumulative Update (CU) verfügt, sofern zutreffend.</span><span class="sxs-lookup"><span data-stu-id="fcf34-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="fcf34-233">Konfigurieren und Validieren der Koexistenz von SMTP-E-Mail-Routing zwischen Ihrer Quellumgebung und Exchange Online, sofern zutreffend.</span><span class="sxs-lookup"><span data-stu-id="fcf34-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="fcf34-234">Sicherstellen, dass die Größe des Quellpostfachs das Zielpostfachkontingent nicht überschreitet.</span><span class="sxs-lookup"><span data-stu-id="fcf34-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="fcf34-235">Abhängig von der Quellplattform müssen Sie möglicherweise Ihre Quelldaten auf 85 % des Zielpostfachkontingents beschränken.</span><span class="sxs-lookup"><span data-stu-id="fcf34-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="fcf34-236">Ggf. Migrieren clientseitiger Daten.</span><span class="sxs-lookup"><span data-stu-id="fcf34-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="fcf34-237">Dies umfasst unter anderem lokale Adressbücher, Daten in lokalen PST-Dateien, Outlook-Regeln und lokale Outlook-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="fcf34-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="fcf34-238">Unterstützen Ihrer Endbenutzer bei der Behebung von Problemen bei der clientbasierten Migration.</span><span class="sxs-lookup"><span data-stu-id="fcf34-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="fcf34-239">Migration zu SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="fcf34-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="fcf34-240">Wenn Sie sich für die Migration Ihrer Dateien zu SharePoint Online mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit.</span><span class="sxs-lookup"><span data-stu-id="fcf34-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="fcf34-241">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des SharePoint Online-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Dateien.</span><span class="sxs-lookup"><span data-stu-id="fcf34-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="fcf34-242">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="fcf34-242">You create and schedule your migration events.</span></span> <span data-ttu-id="fcf34-243">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="fcf34-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="fcf34-244">Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass Dateien von entsprechend geplanten und berechtigten Quellen ihrer Quellumgebungen zu SharePoint Online migriert wurden.</span><span class="sxs-lookup"><span data-stu-id="fcf34-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="fcf34-245">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="fcf34-245">Considerations</span></span>

  - <span data-ttu-id="fcf34-246">Alle Migrationen unterliegen SharePoint Online-Kontingenten.</span><span class="sxs-lookup"><span data-stu-id="fcf34-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="fcf34-247">Weitere Informationen finden Sie unter [<span class="underline">SharePoint Online und OneDrive for Business: Softwarelimits und -beschränkungen</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="fcf34-247">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="fcf34-248">Der Gesamtbetrag sollte auf 75 Prozent des SharePoint Online-Gesamtspeicherkontingents, für das Sie berechtigt sind, beschränkt werden (einschließlich den zusätzlichen Speicher, den Sie möglicherweise separat gekauft haben).</span><span class="sxs-lookup"><span data-stu-id="fcf34-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="fcf34-249">Detail der Quellumgebung</span><span class="sxs-lookup"><span data-stu-id="fcf34-249">Source environment details</span></span>

<span data-ttu-id="fcf34-250">Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:</span><span class="sxs-lookup"><span data-stu-id="fcf34-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="fcf34-251">Dateifreigaben (SMB [Server Message Block]-Dateifreigaben auf Geräten mit Unterstützung für SMB 2.0 und höher)</span><span class="sxs-lookup"><span data-stu-id="fcf34-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="fcf34-252">Eine einzelne G Suite-Umgebung (nur Google Drive).</span><span class="sxs-lookup"><span data-stu-id="fcf34-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="fcf34-253">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="fcf34-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="fcf34-254">Dropbox für Teams (Standard und Erweitert).</span><span class="sxs-lookup"><span data-stu-id="fcf34-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="fcf34-255">Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:</span><span class="sxs-lookup"><span data-stu-id="fcf34-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="fcf34-256"><strong>Quellumgebung</strong></span><span class="sxs-lookup"><span data-stu-id="fcf34-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="fcf34-257"><strong>Migrationstyp</strong></span><span class="sxs-lookup"><span data-stu-id="fcf34-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="fcf34-258"><strong>Was wird migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="fcf34-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="fcf34-259"><strong>Was wird nicht migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="fcf34-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="fcf34-260"><strong>Alle Dateifreigabegeräte mit Unterstützung für SMB 2.0 und höher</strong></span><span class="sxs-lookup"><span data-stu-id="fcf34-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="fcf34-261">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="fcf34-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="fcf34-262">Dokumente</span><span class="sxs-lookup"><span data-stu-id="fcf34-262">Documents</span></span> </li>
<li> <span data-ttu-id="fcf34-263">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="fcf34-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="fcf34-264">Datei- und Ordnerberechtigungen auf Benutzerebene\*</span><span class="sxs-lookup"><span data-stu-id="fcf34-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="fcf34-265">Datei- und Ordnerberechtigungen auf Gruppenebene\*</span><span class="sxs-lookup"><span data-stu-id="fcf34-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="fcf34-266">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="fcf34-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="fcf34-267">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="fcf34-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="fcf34-268">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="fcf34-268">Created date</span></span> </li>
<li> <span data-ttu-id="fcf34-269">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="fcf34-269">Modified date</span></span> </li>
<li> <span data-ttu-id="fcf34-270">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="fcf34-270">Created by</span></span> </li>
<li> <span data-ttu-id="fcf34-271">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="fcf34-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="fcf34-272">\* Setzt die Konfiguration der Verzeichnissynchronisierung voraus.</span><span class="sxs-lookup"><span data-stu-id="fcf34-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="fcf34-273">Es werden nur NTFS-Berechtigungen migriert, die für den Windows-Datei-Explorer verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="fcf34-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="fcf34-274">Berechtigungen, die direkt auf Dateifreigabegeräten verwaltet werden, werden nicht migriert.</span><span class="sxs-lookup"><span data-stu-id="fcf34-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="fcf34-275">Wenn Daten auf einem SMB 2.0-Gerät gespeichert werden, werden die NTFS-äquivalenten Berechtigungen, die vom SMB-Protokoll verfügbar gemacht werden, migriert.</span><span class="sxs-lookup"><span data-stu-id="fcf34-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="fcf34-276">Aufgezeichnete Eigentümerschaft und frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="fcf34-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="fcf34-277">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="fcf34-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="fcf34-278">Frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="fcf34-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="fcf34-279">Windows-Datei-/-Ordnerattribute (z. B. „Schreibgeschützt“ und „Ausgeblendet“) </span><span class="sxs-lookup"><span data-stu-id="fcf34-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="fcf34-280">Nicht-Windows-NTFS-Dateisystem (New Technology File System) und erweiterte NTFS-Berechtigungen sowie besondere Einstellungen:</span><span class="sxs-lookup"><span data-stu-id="fcf34-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="fcf34-281">Explizite Verweigerungsberechtigungen (werden nach der Migration entfernt, Inhalte unterliegen parallelen Berechtigungen oder Berechtigungen im übergeordneten Ordner).</span><span class="sxs-lookup"><span data-stu-id="fcf34-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="fcf34-282">Konfiguration der NTFS-Überwachung</span><span class="sxs-lookup"><span data-stu-id="fcf34-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="fcf34-283">Zusätzliche Dateimetadaten von der Dateiklassifizierungsinfrastruktur (File Classification Infrastructure, FCI)</span><span class="sxs-lookup"><span data-stu-id="fcf34-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="fcf34-284">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="fcf34-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="fcf34-285">Ausgeblendete Freigaben</span><span class="sxs-lookup"><span data-stu-id="fcf34-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="fcf34-286">Freigabe (z. B. gewährte Berechtigungen auf Freigabeebene)</span><span class="sxs-lookup"><span data-stu-id="fcf34-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="fcf34-287">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online-Einschränkungen und -Einschränkungen überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="fcf34-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="fcf34-288"><strong>Einzelne G Suite-Umgebung (nur Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="fcf34-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="fcf34-289">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="fcf34-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="fcf34-290">Google Docs, Google Tabellen und Google Präsentationen (Dateien werden in das entsprechende Office-Format konvertiert), einschließlich derjenigen über 10 MB</span><span class="sxs-lookup"><span data-stu-id="fcf34-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="fcf34-291">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="fcf34-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="fcf34-292">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-293">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-294">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="fcf34-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="fcf34-295">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="fcf34-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="fcf34-296">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="fcf34-296">Created date</span></span> </li>
<li> <span data-ttu-id="fcf34-297">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="fcf34-297">Modified date</span></span> </li>
<li> <span data-ttu-id="fcf34-298">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="fcf34-298">Created by</span></span> </li>
<li> <span data-ttu-id="fcf34-299">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="fcf34-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="fcf34-300">Freigegebene Laufwerke (Ordner und Dateien)</span><span class="sxs-lookup"><span data-stu-id="fcf34-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="fcf34-301">Geteilte Inhalte, die im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="fcf34-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="fcf34-302">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="fcf34-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="fcf34-303">Beschreibungen von Dateien und Ordnern, Ordnerfarben</span><span class="sxs-lookup"><span data-stu-id="fcf34-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="fcf34-304">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-305">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-306">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="fcf34-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="fcf34-307">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="fcf34-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="fcf34-308">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="fcf34-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="fcf34-309">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="fcf34-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="fcf34-310">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="fcf34-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="fcf34-311">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="fcf34-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="fcf34-312">Google Fotos, Google Formulare, Google Maps und andere verbundene Apps</span><span class="sxs-lookup"><span data-stu-id="fcf34-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="fcf34-313">Google Zeichnungen</span><span class="sxs-lookup"><span data-stu-id="fcf34-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="fcf34-314">Freigegebene Inhalte außerhalb Ihrer Organisation</span><span class="sxs-lookup"><span data-stu-id="fcf34-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="fcf34-315">Inhalte, die nicht im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="fcf34-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="fcf34-316">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Google Drive-Administratorberichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="fcf34-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="fcf34-317">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="fcf34-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="fcf34-318">Mitgliedschaftsberechtigungen für freigegebene Laufwerke (<strong>Hinweis</strong>: Verwenden Sie die Google Drive-Administratorberichte, um die Mitgliedschaften für freigegebene Laufwerke zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="fcf34-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="fcf34-319">Weisen Sie die Endbenutzer an, diese Mitgliedschaftseinstellungen auf dem Ziel vor der Migration zu konfigurieren.)</span><span class="sxs-lookup"><span data-stu-id="fcf34-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="fcf34-320">Als eingeschränkt markierte oder nicht kopierbare Dateien</span><span class="sxs-lookup"><span data-stu-id="fcf34-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="fcf34-321">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online-Einschränkungen und -Einschränkungen überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="fcf34-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="fcf34-322"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="fcf34-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="fcf34-323">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="fcf34-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="fcf34-324">Dokumente</span><span class="sxs-lookup"><span data-stu-id="fcf34-324">Documents</span></span> </li>
<li> <span data-ttu-id="fcf34-325">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="fcf34-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="fcf34-326">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-327">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-328">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="fcf34-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="fcf34-329">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="fcf34-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="fcf34-330">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="fcf34-330">Created date</span></span> </li>
<li> <span data-ttu-id="fcf34-331">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="fcf34-331">Modified date</span></span> </li>
<li> <span data-ttu-id="fcf34-332">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="fcf34-332">Created by</span></span> </li>
<li> <span data-ttu-id="fcf34-333">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="fcf34-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="fcf34-334">Geteilte Inhalte, die im Besitz des Box-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="fcf34-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="fcf34-335">Box Notes (in Word-Dokumentformat konvertiert)</span><span class="sxs-lookup"><span data-stu-id="fcf34-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="fcf34-336">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="fcf34-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="fcf34-337">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="fcf34-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="fcf34-338">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-339">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-340">Box-Tags und erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="fcf34-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="fcf34-341">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="fcf34-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="fcf34-342">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="fcf34-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="fcf34-343">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="fcf34-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="fcf34-344">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="fcf34-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="fcf34-345">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="fcf34-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="fcf34-346">Box-Apps, Lesezeichen, Favoriten und Workflows</span><span class="sxs-lookup"><span data-stu-id="fcf34-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="fcf34-347">Inhalte, die nicht im Besitz des migrierten Box-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="fcf34-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="fcf34-348">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Box-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="fcf34-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="fcf34-349">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="fcf34-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="fcf34-350">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online-Einschränkungen und -Einschränkungen überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="fcf34-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="fcf34-351"><strong>Dropbox für Teams (Standard und Erweitert)</strong></span><span class="sxs-lookup"><span data-stu-id="fcf34-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="fcf34-352">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="fcf34-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="fcf34-353">Dokumente</span><span class="sxs-lookup"><span data-stu-id="fcf34-353">Documents</span></span> </li>
<li> <span data-ttu-id="fcf34-354">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="fcf34-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="fcf34-355">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-356">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-357">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="fcf34-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="fcf34-358">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="fcf34-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="fcf34-359">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="fcf34-359">Created date</span></span> </li>
<li> <span data-ttu-id="fcf34-360">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="fcf34-360">Modified date</span></span> </li>
<li> <span data-ttu-id="fcf34-361">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="fcf34-361">Created by</span></span> </li>
<li> <span data-ttu-id="fcf34-362">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="fcf34-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="fcf34-363">Freigegebene Teamordner und -inhalte</span><span class="sxs-lookup"><span data-stu-id="fcf34-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="fcf34-364">Geteilte Inhalte, die im Besitz des Dropbox-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="fcf34-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="fcf34-365">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="fcf34-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="fcf34-366">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="fcf34-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="fcf34-367">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-368">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-369">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="fcf34-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="fcf34-370">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="fcf34-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="fcf34-371">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="fcf34-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="fcf34-372">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="fcf34-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="fcf34-373">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="fcf34-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="fcf34-374">Nicht gemountete Dropbox-Ordner</span><span class="sxs-lookup"><span data-stu-id="fcf34-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="fcf34-375">Gelöschte oder getrennte Benutzer</span><span class="sxs-lookup"><span data-stu-id="fcf34-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="fcf34-376">Dropbox Paper, Showcases und Spaces</span><span class="sxs-lookup"><span data-stu-id="fcf34-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="fcf34-377">Dropbox-Apps und Favoriten (Pins/Sterne)</span><span class="sxs-lookup"><span data-stu-id="fcf34-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="fcf34-378">Inhalte, die nicht im Besitz des migrierten Dropbox-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="fcf34-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="fcf34-379">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Dropbox-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="fcf34-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="fcf34-380">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="fcf34-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="fcf34-381">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online-Einschränkungen und -Einschränkungen überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="fcf34-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="fcf34-382">FastTrack-Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="fcf34-382">FastTrack responsibilities</span></span>

<span data-ttu-id="fcf34-383">Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="fcf34-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="fcf34-384">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="fcf34-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="fcf34-385">Ihre Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="fcf34-385">Your responsibilities</span></span>

<span data-ttu-id="fcf34-386">Während des Migrationsprojekts führen Sie Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="fcf34-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="fcf34-387">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="fcf34-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="fcf34-388">Sie führen außerdem die folgenden Aktivitäten speziell für SharePoint Online-Migrationen aus:</span><span class="sxs-lookup"><span data-stu-id="fcf34-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="fcf34-389">Bereitstellen aller SharePoint-Teamwebsites, die für Ihre Migrationsereignisse vorgesehen sind.</span><span class="sxs-lookup"><span data-stu-id="fcf34-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="fcf34-390">Migration zu OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="fcf34-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="fcf34-391">Wenn Sie sich für die Migration Ihrer Dateien zu OneDrive for Business mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit.</span><span class="sxs-lookup"><span data-stu-id="fcf34-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="fcf34-392">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des OneDrive for Business-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Dateien.</span><span class="sxs-lookup"><span data-stu-id="fcf34-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="fcf34-393">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="fcf34-393">You create and schedule your migration events.</span></span> <span data-ttu-id="fcf34-394">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="fcf34-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="fcf34-395">Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass Dateien von entsprechend geplanten und berechtigten Quellen ihrer Quellumgebungen zu OneDrive for Business migriert wurden.</span><span class="sxs-lookup"><span data-stu-id="fcf34-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="fcf34-396">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="fcf34-396">Considerations</span></span>

  - <span data-ttu-id="fcf34-397">Alle Migrationen unterliegen den OneDrive for Business-Kontingenten.</span><span class="sxs-lookup"><span data-stu-id="fcf34-397">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="fcf34-398">Weitere Informationen finden Sie unter [<span class="underline">SharePoint Online und OneDrive for Business: Softwarelimits und -beschränkungen</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="fcf34-398">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="fcf34-399">Der Gesamtbetrag sollte auf 75 Prozent der Daten des SharePoint Online-Gesamtspeicherkontingents, für das Sie berechtigt sind, beschränkt werden (einschließlich den zusätzlichen Speicher, den Sie möglicherweise separat gekauft haben).</span><span class="sxs-lookup"><span data-stu-id="fcf34-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="fcf34-400">FastTrack migriert nur zu aktiven OneDrive for Business-Laufwerken.</span><span class="sxs-lookup"><span data-stu-id="fcf34-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="fcf34-401">Detail der Quellumgebung</span><span class="sxs-lookup"><span data-stu-id="fcf34-401">Source environment details</span></span>

<span data-ttu-id="fcf34-402">Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:</span><span class="sxs-lookup"><span data-stu-id="fcf34-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="fcf34-403">Dateifreigaben (SMB-Dateifreigaben auf Geräten mit Unterstützung für SMB 2.0 und höher)</span><span class="sxs-lookup"><span data-stu-id="fcf34-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="fcf34-404">Einzelne G Suite-Umgebung (nur Google Drive).</span><span class="sxs-lookup"><span data-stu-id="fcf34-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="fcf34-405">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="fcf34-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="fcf34-406">Dropbox für Teams (Standard und Erweitert).</span><span class="sxs-lookup"><span data-stu-id="fcf34-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="fcf34-407">Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:</span><span class="sxs-lookup"><span data-stu-id="fcf34-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="fcf34-408"><strong>Quellumgebung</strong></span><span class="sxs-lookup"><span data-stu-id="fcf34-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="fcf34-409"><strong>Migrationstyp</strong></span><span class="sxs-lookup"><span data-stu-id="fcf34-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="fcf34-410"><strong>Was wird migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="fcf34-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="fcf34-411"><strong>Was wird nicht migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="fcf34-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="fcf34-412"><strong>Alle Dateifreigabegeräte mit Unterstützung für SMB 2.0 und höher</strong></span><span class="sxs-lookup"><span data-stu-id="fcf34-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="fcf34-413">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="fcf34-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="fcf34-414">Dokumente</span><span class="sxs-lookup"><span data-stu-id="fcf34-414">Documents</span></span> </li>
<li> <span data-ttu-id="fcf34-415">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="fcf34-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="fcf34-416">Datei- und Ordnerberechtigungen auf Benutzerebene\*</span><span class="sxs-lookup"><span data-stu-id="fcf34-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="fcf34-417">Datei- und Ordnerberechtigungen auf Gruppenebene\*</span><span class="sxs-lookup"><span data-stu-id="fcf34-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="fcf34-418">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="fcf34-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="fcf34-419">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="fcf34-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="fcf34-420">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="fcf34-420">Created date</span></span> </li>
<li> <span data-ttu-id="fcf34-421">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="fcf34-421">Modified date</span></span> </li>
<li> <span data-ttu-id="fcf34-422">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="fcf34-422">Created by</span></span> </li>
<li> <span data-ttu-id="fcf34-423">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="fcf34-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="fcf34-424">\* Setzt die Konfiguration der Verzeichnissynchronisierung voraus.</span><span class="sxs-lookup"><span data-stu-id="fcf34-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="fcf34-425">Es werden nur NTFS-Berechtigungen migriert, die für den Windows-Datei-Explorer verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="fcf34-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="fcf34-426">Berechtigungen, die direkt auf Dateifreigabegeräten verwaltet werden, werden nicht migriert.</span><span class="sxs-lookup"><span data-stu-id="fcf34-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="fcf34-427">Wenn Daten auf einem SMB 2.0-Gerät gespeichert werden, werden die NTFS-äquivalenten Berechtigungen, die vom SMB-Protokoll verfügbar gemacht werden, migriert.</span><span class="sxs-lookup"><span data-stu-id="fcf34-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="fcf34-428">Aufgezeichnete Eigentümerschaft und frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="fcf34-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="fcf34-429">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="fcf34-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="fcf34-430">Frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="fcf34-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="fcf34-431">Windows-Datei-/-Ordnerattribute (z. B. „Schreibgeschützt“ und „Ausgeblendet“) </span><span class="sxs-lookup"><span data-stu-id="fcf34-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="fcf34-432">Nicht-Windows-NTFS-Dateisystem (New Technology File System) und erweiterte NTFS-Berechtigungen sowie besondere Einstellungen:</span><span class="sxs-lookup"><span data-stu-id="fcf34-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="fcf34-433">Explizite Verweigerungsberechtigungen (werden nach der Migration entfernt, Inhalte unterliegen parallelen Berechtigungen oder Berechtigungen im übergeordneten Ordner).</span><span class="sxs-lookup"><span data-stu-id="fcf34-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="fcf34-434">Konfiguration der NTFS-Überwachung</span><span class="sxs-lookup"><span data-stu-id="fcf34-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="fcf34-435">Zusätzliche Dateimetadaten von der Dateiklassifizierungsinfrastruktur (File Classification Infrastructure, FCI)</span><span class="sxs-lookup"><span data-stu-id="fcf34-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="fcf34-436">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="fcf34-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="fcf34-437">Ausgeblendete Freigaben</span><span class="sxs-lookup"><span data-stu-id="fcf34-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="fcf34-438">Freigabe (z. B. gewährte Berechtigungen auf Freigabeebene)</span><span class="sxs-lookup"><span data-stu-id="fcf34-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="fcf34-439">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online-Einschränkungen und -Einschränkungen überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="fcf34-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="fcf34-440"><strong>Einzelne G Suite-Umgebung (nur Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="fcf34-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="fcf34-441">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="fcf34-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="fcf34-442">Google Docs, Google Tabellen und Google Präsentationen (Dateien werden in das entsprechende Office-Format konvertiert, einschließlich derjenigen über 10 MB)</span><span class="sxs-lookup"><span data-stu-id="fcf34-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="fcf34-443">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="fcf34-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="fcf34-444">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-445">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-446">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="fcf34-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="fcf34-447">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="fcf34-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="fcf34-448">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="fcf34-448">Created date</span></span> </li>
<li> <span data-ttu-id="fcf34-449">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="fcf34-449">Modified date</span></span> </li>
<li> <span data-ttu-id="fcf34-450">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="fcf34-450">Created by</span></span> </li>
<li> <span data-ttu-id="fcf34-451">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="fcf34-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="fcf34-452">Freigegebene Laufwerke (Ordner und Dateien)</span><span class="sxs-lookup"><span data-stu-id="fcf34-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="fcf34-453">Geteilte Inhalte, die im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="fcf34-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="fcf34-454">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="fcf34-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="fcf34-455">Beschreibungen von Dateien und Ordnern, Ordnerfarben</span><span class="sxs-lookup"><span data-stu-id="fcf34-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="fcf34-456">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-457">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-458">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="fcf34-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="fcf34-459">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="fcf34-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="fcf34-460">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="fcf34-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="fcf34-461">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="fcf34-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="fcf34-462">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="fcf34-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="fcf34-463">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="fcf34-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="fcf34-464">Google Fotos, Google Formulare, Google Maps und andere verbundene Apps</span><span class="sxs-lookup"><span data-stu-id="fcf34-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="fcf34-465">Google Zeichnungen</span><span class="sxs-lookup"><span data-stu-id="fcf34-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="fcf34-466">Freigegebene Inhalte außerhalb Ihrer Organisation</span><span class="sxs-lookup"><span data-stu-id="fcf34-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="fcf34-467">Inhalte, die nicht im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="fcf34-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="fcf34-468">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Google Drive-Administratorberichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="fcf34-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="fcf34-469">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="fcf34-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="fcf34-470">Mitgliedschaftsberechtigungen für freigegebene Laufwerke (<strong>Hinweis</strong>: Verwenden Sie die Google Drive-Administratorberichte, um die Mitgliedschaften für freigegebene Laufwerke zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="fcf34-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="fcf34-471">Weisen Sie die Endbenutzer an, diese Mitgliedschaftseinstellungen auf dem Ziel vor der Migration zu konfigurieren.)</span><span class="sxs-lookup"><span data-stu-id="fcf34-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="fcf34-472">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online-Einschränkungen und -Einschränkungen überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="fcf34-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="fcf34-473"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="fcf34-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="fcf34-474">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="fcf34-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="fcf34-475">Dokumente</span><span class="sxs-lookup"><span data-stu-id="fcf34-475">Documents</span></span> </li>
<li> <span data-ttu-id="fcf34-476">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="fcf34-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="fcf34-477">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-478">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-479">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="fcf34-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="fcf34-480">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="fcf34-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="fcf34-481">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="fcf34-481">Created date</span></span> </li>
<li> <span data-ttu-id="fcf34-482">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="fcf34-482">Modified date</span></span> </li>
<li> <span data-ttu-id="fcf34-483">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="fcf34-483">Created by</span></span> </li>
<li> <span data-ttu-id="fcf34-484">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="fcf34-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="fcf34-485">Geteilte Inhalte, die im Besitz des Box-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="fcf34-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="fcf34-486">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="fcf34-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="fcf34-487">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="fcf34-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="fcf34-488">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-489">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-490">Box-Tags und erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="fcf34-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="fcf34-491">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="fcf34-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="fcf34-492">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="fcf34-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="fcf34-493">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="fcf34-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="fcf34-494">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="fcf34-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="fcf34-495">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="fcf34-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="fcf34-496">Box-Apps, Lesezeichen, Favoriten und Workflows</span><span class="sxs-lookup"><span data-stu-id="fcf34-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="fcf34-497">Inhalte, die nicht im Besitz des migrierten Box-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="fcf34-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="fcf34-498">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Box-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="fcf34-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="fcf34-499">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="fcf34-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="fcf34-500">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online-Einschränkungen und -Einschränkungen überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="fcf34-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="fcf34-501"><strong>Dropbox für Teams (Standard und Erweitert)</strong></span><span class="sxs-lookup"><span data-stu-id="fcf34-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="fcf34-502">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="fcf34-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="fcf34-503">Dokumente</span><span class="sxs-lookup"><span data-stu-id="fcf34-503">Documents</span></span> </li>
<li> <span data-ttu-id="fcf34-504">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="fcf34-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="fcf34-505">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-506">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-507">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="fcf34-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="fcf34-508">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="fcf34-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="fcf34-509">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="fcf34-509">Created date</span></span> </li>
<li> <span data-ttu-id="fcf34-510">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="fcf34-510">Modified date</span></span> </li>
<li> <span data-ttu-id="fcf34-511">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="fcf34-511">Created by</span></span> </li>
<li> <span data-ttu-id="fcf34-512">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="fcf34-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="fcf34-513">Freigegebene Teamordner und -inhalte</span><span class="sxs-lookup"><span data-stu-id="fcf34-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="fcf34-514">Geteilte Inhalte, die im Besitz des Dropbox-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="fcf34-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="fcf34-515">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="fcf34-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="fcf34-516">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="fcf34-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="fcf34-517">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-518">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="fcf34-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="fcf34-519">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="fcf34-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="fcf34-520">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="fcf34-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="fcf34-521">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="fcf34-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="fcf34-522">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="fcf34-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="fcf34-523">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="fcf34-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="fcf34-524">Nicht gemountete Dropbox-Ordner</span><span class="sxs-lookup"><span data-stu-id="fcf34-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="fcf34-525">Gelöschte oder getrennte Benutzer</span><span class="sxs-lookup"><span data-stu-id="fcf34-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="fcf34-526">Dropbox Paper, Showcases und Spaces</span><span class="sxs-lookup"><span data-stu-id="fcf34-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="fcf34-527">Dropbox-Apps und Favoriten (Pins/Sterne)</span><span class="sxs-lookup"><span data-stu-id="fcf34-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="fcf34-528">Inhalte, die nicht im Besitz des migrierten Dropbox-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="fcf34-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="fcf34-529">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Dropbox-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="fcf34-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="fcf34-530">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="fcf34-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="fcf34-531">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online-Einschränkungen und -Einschränkungen überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="fcf34-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="fcf34-532">FastTrack-Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="fcf34-532">FastTrack responsibilities</span></span>

<span data-ttu-id="fcf34-533">Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="fcf34-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="fcf34-534">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="fcf34-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="fcf34-535">Ihre Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="fcf34-535">Your responsibilities</span></span>

<span data-ttu-id="fcf34-536">Während des Migrationsprojekts führen Sie Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="fcf34-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="fcf34-537">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="fcf34-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="fcf34-538">Sie führen außerdem die folgenden Aktivitäten speziell für OneDrive for Business-Migrationen aus:</span><span class="sxs-lookup"><span data-stu-id="fcf34-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="fcf34-539">Bereitstellen aller OneDrive for Business-Websites, die für Ihre Migrationsereignisse bestimmt sind.</span><span class="sxs-lookup"><span data-stu-id="fcf34-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
