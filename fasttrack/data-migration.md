---
title: Datenmigration
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 5/19/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Sie können die Migration von E-Mail- und Dateidaten in ihrer Quellumgebung auf Office 365 (Exchange Online, SharePoint Online und OneDrive for Business) mithilfe von FastTrack migrieren. Die Art der von uns bereitgestellten Unterstützung hängt von der Anzahl der Office 365-Lizenzen ab.
ms.openlocfilehash: 916343d73c46410990785515ac5f32de24703acf
ms.sourcegitcommit: 48c1a68ecf668b849037beb05b5490c6b922e833
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52570481"
---
# <a name="data-migration"></a><span data-ttu-id="5d498-104">Datenmigration</span><span class="sxs-lookup"><span data-stu-id="5d498-104">Data Migration</span></span>

<span data-ttu-id="5d498-105">Sie können die Migration von E-Mail- und Dateidaten in ihrer Quellumgebung auf Office 365 (Exchange Online, SharePoint Online und OneDrive for Business) mithilfe von FastTrack migrieren.</span><span class="sxs-lookup"><span data-stu-id="5d498-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="5d498-106">Die Art der von uns bereitgestellten Unterstützung hängt von der Anzahl der Office 365-Lizenzen ab:</span><span class="sxs-lookup"><span data-stu-id="5d498-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="5d498-107">**Für Office 365-Mandanten mit 150 bis 499-Lizenzen**: FastTrack bietet nur Migrationsanleitungen. Sie sind für die Durchführung der Datenmigration verantwortlich.</span><span class="sxs-lookup"><span data-stu-id="5d498-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="5d498-108">Wir führen Sie durch die Dokumentation, die Ihnen hilft, ﻿kostenlose Tools für die Durchführung einer Self-Service-Migration zu planen und zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="5d498-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="5d498-109">**Für Office 365-Mandanten mit 500 oder mehr Lizenzen**: FastTrack bietet Migrationsanleitungen und Datenmigrationsdienste.</span><span class="sxs-lookup"><span data-stu-id="5d498-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="5d498-110">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des Office 365-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Daten.</span><span class="sxs-lookup"><span data-stu-id="5d498-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="5d498-111">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="5d498-111">You create and schedule your migration events.</span></span> <span data-ttu-id="5d498-112">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="5d498-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="5d498-113">Wenn Sie einen kommerziellen Plan vor dem 1.9.2017 erworben oder verlängert haben, benötigen Sie nur 150 Lizenzen, um für Datenmigrationsdienste qualifiziert zu sein.</span><span class="sxs-lookup"><span data-stu-id="5d498-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="5d498-114">Bei Plänen für Bildungseinrichtungen sind nur Lehrpersonal und Mitarbeiter für Migrationsdienste berechtigt.</span><span class="sxs-lookup"><span data-stu-id="5d498-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="5d498-115">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="5d498-115">Considerations</span></span>

  - <span data-ttu-id="5d498-116">Ihre Quellumgebungen müssen bestimmte Erwartungen erfüllen, um Daten zu Office 365 zu migrieren.</span><span class="sxs-lookup"><span data-stu-id="5d498-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="5d498-117">Weitere Informationen zu den Erwartungen bezüglich der Quellumgebung für Exchange, SharePoint und OneDrive for Business finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="5d498-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="5d498-118">Für die Bereitstellung von Datenmigrationsdiensten benötigen wir einen geeigneten Zugriff auf Ihre Quellumgebungen und den Office 365-Mandanten.</span><span class="sxs-lookup"><span data-stu-id="5d498-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="5d498-119">Unsere Datenmigrationsdienste sind nicht für Daten vorgesehen, die besonderen rechtlichen oder behördlichen Vorschriften unterliegen.</span><span class="sxs-lookup"><span data-stu-id="5d498-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="5d498-120">Wenn wir Ihre Daten migrieren, können sie an einen beliebigen Ort, an dem wir über Einrichtungen verfügen, übertragen, dort gespeichert und verarbeitet werden (sofern nicht anderweitig für Ihr FastTrack-Migrationsprojekt angegeben).</span><span class="sxs-lookup"><span data-stu-id="5d498-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="5d498-121">Wir übernehmen keine Garantie für die Geschwindigkeit der E-Mail- oder Dateimigration.</span><span class="sxs-lookup"><span data-stu-id="5d498-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="5d498-122">Unvorhergesehene Probleme (wie unlesbare oder fehlerhafte Elemente in der Quellumgebung) verhindern möglicherweise, dass einige ihrer Datenelemente migriert werden können.</span><span class="sxs-lookup"><span data-stu-id="5d498-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="5d498-123">Externe Faktoren, die außerhalb unserer Kontrolle stehen (z. B. Änderungen an den Programmierschnittstellen von Drittanbietern) können zu Änderungen, Verzögerungen oder der Sperrung unserer Datenmigrationsdienste führen.</span><span class="sxs-lookup"><span data-stu-id="5d498-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="5d498-124">Verfügbarkeit des Migrationsdiensts</span><span class="sxs-lookup"><span data-stu-id="5d498-124">Migration service availability</span></span>

  - <span data-ttu-id="5d498-125">**Für kommerzielle Kunden und britische Behörden:** Wir stellen Datenmigrationsdienste rund um die Uhr an sieben (7) Tagen pro Woche bereit.</span><span class="sxs-lookup"><span data-stu-id="5d498-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="5d498-126">**Für Kunden von US-amerikanischen Behörden/Verteidigungsministerium:** Wir stellen Datenmigrationsdienste rund um die Uhr an fünf (5) Werktagen pro Woche bereit.</span><span class="sxs-lookup"><span data-stu-id="5d498-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="5d498-127">Migration zu Exchange Online</span><span class="sxs-lookup"><span data-stu-id="5d498-127">Migration to Exchange Online</span></span>

<span data-ttu-id="5d498-128">Wenn Sie sich für die Migration Ihrer E-Mails zu Exchange Online mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit.</span><span class="sxs-lookup"><span data-stu-id="5d498-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="5d498-129">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des Exchange Online-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Postfächer.</span><span class="sxs-lookup"><span data-stu-id="5d498-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="5d498-130">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="5d498-130">You create and schedule your migration events.</span></span> <span data-ttu-id="5d498-131">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="5d498-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="5d498-132">Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass E-Mail-Nachrichten von entsprechend geplanten und berechtigten Quellpostfächern ihrer Quellumgebungen zu Exchange Online migriert wurden.</span><span class="sxs-lookup"><span data-stu-id="5d498-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="5d498-133">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="5d498-133">Considerations</span></span>

  - <span data-ttu-id="5d498-134">Bevor Sie die Migration durchführen können, müssen Sie den FastTrack-Onboarding-Vorgang für Exchange Online durchführen.</span><span class="sxs-lookup"><span data-stu-id="5d498-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="5d498-135">Wenn Sie das Onboarding selbst durchgeführt haben, müssen Sie die erforderlichen Überprüfungen und Voraussetzungen erfüllen.</span><span class="sxs-lookup"><span data-stu-id="5d498-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="5d498-136">Ausführliche Informationen finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="5d498-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="5d498-137">FastTrack migriert nur zu aktiven Office 365-Postfächern.</span><span class="sxs-lookup"><span data-stu-id="5d498-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="5d498-138">Sie müssen bestimmte Anforderungen erfüllen, wenn Sie von einer lokalen Exchange-Umgebung migrieren möchten.</span><span class="sxs-lookup"><span data-stu-id="5d498-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="5d498-139">Weitere Informationen finden Sie unter [Voraussetzungen für die Hybridbereitstellung](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="5d498-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="5d498-140">Sämtliche Quellumgebungen müssen über die neuesten Service Packs (SP) verfügen und auf der Rollup (RU)-/Kumulativen Update (KU)-Ebene für das entsprechende Produkt in der Quellumgebung vorhanden sein.</span><span class="sxs-lookup"><span data-stu-id="5d498-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="5d498-141">Verteilerlisten (*MailEnabledGroup*-Objekte) und externe Kontakte (*MailEnabledContact*-Objekte) im lokalen Active Directory befinden, sind nicht Bestandteil einer Postfachdatenmigration.</span><span class="sxs-lookup"><span data-stu-id="5d498-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="5d498-142">Sie können Sie jedoch mithilfe von Azure Active Directory (Azure AD) Connect synchronisieren.</span><span class="sxs-lookup"><span data-stu-id="5d498-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="5d498-143">Quellumgebungen</span><span class="sxs-lookup"><span data-stu-id="5d498-143">Source environments</span></span>

<span data-ttu-id="5d498-144">Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:</span><span class="sxs-lookup"><span data-stu-id="5d498-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="5d498-145">aus einer einzelnen oder aus mehreren Active Directory-Gesamtstrukturen mit einer oder mehreren Exchange-Organisationen (jedes Exchange-E-Mail-System muss Exchange 2010 oder höher sein).</span><span class="sxs-lookup"><span data-stu-id="5d498-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="5d498-146">aus einer einzelnen IMAP-fähigen E-Mail-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="5d498-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="5d498-147">aus einer G Suite-Umgebung (nur Gmail, Kontakte und Kalender).</span><span class="sxs-lookup"><span data-stu-id="5d498-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="5d498-148">Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:</span><span class="sxs-lookup"><span data-stu-id="5d498-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="5d498-149"><strong>Quellumgebung</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="5d498-150"><strong>Migrationstyp</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="5d498-151"><strong>Was wird migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="5d498-152"><strong>Was wird nicht migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="5d498-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="5d498-154">
<strong>Hinweis:</strong> Informationen zu lokalen Exchange Abhängigkeiten finden Sie unter <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Voraussetzungen für die Hybridbereitstellung</span></a>.</span><span class="sxs-lookup"><span data-stu-id="5d498-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="5d498-155">Migration mit Hybridbereitstellung</span><span class="sxs-lookup"><span data-stu-id="5d498-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="5d498-156">E-Mails</span><span class="sxs-lookup"><span data-stu-id="5d498-156">Emails</span></span></li>
<li><span data-ttu-id="5d498-157">Serverseitige Postfachregeln</span><span class="sxs-lookup"><span data-stu-id="5d498-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="5d498-158">Stellvertretungen</span><span class="sxs-lookup"><span data-stu-id="5d498-158">Delegates</span></span></li>
<li><span data-ttu-id="5d498-159">Postfachkontakte</span><span class="sxs-lookup"><span data-stu-id="5d498-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="5d498-160">Kalender</span><span class="sxs-lookup"><span data-stu-id="5d498-160">Calendar</span></span> </li>
<li> <span data-ttu-id="5d498-161">Aufgaben</span><span class="sxs-lookup"><span data-stu-id="5d498-161">Tasks</span></span> </li>
<li> <span data-ttu-id="5d498-162">E-Mails mit Rechteverwaltung</span><span class="sxs-lookup"><span data-stu-id="5d498-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="5d498-163">Verschlüsselte E-Mails</span><span class="sxs-lookup"><span data-stu-id="5d498-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="5d498-164">Signaturen</span><span class="sxs-lookup"><span data-stu-id="5d498-164">Signatures</span></span> </li>
<li> <span data-ttu-id="5d498-165">Persönliches Archiv, das mit dem Benutzerpostfach migriert wird</span><span class="sxs-lookup"><span data-stu-id="5d498-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="5d498-166">Wiederherstellbare Elemente</span><span class="sxs-lookup"><span data-stu-id="5d498-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5d498-167">Öffentliche Ordner</span><span class="sxs-lookup"><span data-stu-id="5d498-167">Public folders</span></span> </li>
<li> <span data-ttu-id="5d498-168">E-Mail, die die zulässige Nachrichtengröße überschreitet.</span><span class="sxs-lookup"><span data-stu-id="5d498-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="5d498-169">Journalarchiv oder eine beliebige Archivlösung von Drittanbietern</span><span class="sxs-lookup"><span data-stu-id="5d498-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="5d498-170">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="5d498-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="5d498-171">Archivdaten aus PST-Dateien</span><span class="sxs-lookup"><span data-stu-id="5d498-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="5d498-172">Beschädigte Elemente</span><span class="sxs-lookup"><span data-stu-id="5d498-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="5d498-173">Inaktive Postfächer</span><span class="sxs-lookup"><span data-stu-id="5d498-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="5d498-174">Clientseitige Postfachregeln</span><span class="sxs-lookup"><span data-stu-id="5d498-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5d498-175"><strong>G Suite-Umgebung (nur Gmail, Kontakte und Kalender)</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="5d498-176">
<strong>Hinweis:</strong> Ihre G Suite-Umgebung muss die voraussetzungen erfüllen, die unter <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Ausführen einer G Suite-Migration beschrieben sind.</a></span><span class="sxs-lookup"><span data-stu-id="5d498-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="5d498-177">Übernahmemigration oder mehrstufige Migration</span><span class="sxs-lookup"><span data-stu-id="5d498-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="5d498-178">E-Mails</span><span class="sxs-lookup"><span data-stu-id="5d498-178">Emails</span></span> </li>
<li> <span data-ttu-id="5d498-179">Postfachkontakte (es werden maximal drei E-Mail-Adressen pro Kontakt migriert)</span><span class="sxs-lookup"><span data-stu-id="5d498-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="5d498-180">Kalender</span><span class="sxs-lookup"><span data-stu-id="5d498-180">Calendar</span></span> </li>
<li> <span data-ttu-id="5d498-181">Bezeichnungen</span><span class="sxs-lookup"><span data-stu-id="5d498-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5d498-182">Regeln</span><span class="sxs-lookup"><span data-stu-id="5d498-182">Rules</span></span> </li>
<li> <span data-ttu-id="5d498-183">Stellvertretungen</span><span class="sxs-lookup"><span data-stu-id="5d498-183">Delegates</span></span> </li>
<li> <span data-ttu-id="5d498-184">Signaturen</span><span class="sxs-lookup"><span data-stu-id="5d498-184">Signatures</span></span> </li>
<li> <span data-ttu-id="5d498-185">Aufgaben</span><span class="sxs-lookup"><span data-stu-id="5d498-185">Tasks</span></span> </li>
<li> <span data-ttu-id="5d498-186">E-Mails oder Anhänge, die die zulässige Nachrichtengröße überschreiten</span><span class="sxs-lookup"><span data-stu-id="5d498-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="5d498-187">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="5d498-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="5d498-188">Archivdaten aus PST-Dateien oder einer Drittanbieter-Archivlösung (z. B. Google Vault)</span><span class="sxs-lookup"><span data-stu-id="5d498-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="5d498-189">E-Mails mit Rechteverwaltung oder Verschlüsselung</span><span class="sxs-lookup"><span data-stu-id="5d498-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="5d498-190">Beschädigte Elemente</span><span class="sxs-lookup"><span data-stu-id="5d498-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="5d498-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="5d498-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="5d498-192">Google-Gruppen</span><span class="sxs-lookup"><span data-stu-id="5d498-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="5d498-193">Ressourcenpostfächer</span><span class="sxs-lookup"><span data-stu-id="5d498-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="5d498-194">Inaktive Postfächer</span><span class="sxs-lookup"><span data-stu-id="5d498-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="5d498-195">Urlaubseinstellungen und Einstellungen für automatische Antworten</span><span class="sxs-lookup"><span data-stu-id="5d498-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="5d498-196">Freigegebene Kalender, Cloudanlagen, Google Hangout-Links und Ereignisfarben</span><span class="sxs-lookup"><span data-stu-id="5d498-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="5d498-197">\*\*Hangout-Unterhaltungen, die als Beschriftungen gespeichert wurden, werden migriert.</span><span class="sxs-lookup"><span data-stu-id="5d498-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5d498-198"><strong>IMAP4-Quelle (wie Domino, GroupWise oder Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="5d498-199">Migration mit systemeigenen IMAP4-Tools</span><span class="sxs-lookup"><span data-stu-id="5d498-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="5d498-200">E-Mails</span><span class="sxs-lookup"><span data-stu-id="5d498-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="5d498-201">Regeln</span><span class="sxs-lookup"><span data-stu-id="5d498-201">Rules</span></span> </li>
<li> <span data-ttu-id="5d498-202">Stellvertretungen</span><span class="sxs-lookup"><span data-stu-id="5d498-202">Delegates</span></span> </li>
<li> <span data-ttu-id="5d498-203">Verteilerlisten</span><span class="sxs-lookup"><span data-stu-id="5d498-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="5d498-204">Externe Kontakte</span><span class="sxs-lookup"><span data-stu-id="5d498-204">External contacts</span></span> </li>
<li> <span data-ttu-id="5d498-205">E-Mail-aktivierte Benutzer</span><span class="sxs-lookup"><span data-stu-id="5d498-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="5d498-206">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="5d498-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="5d498-207">Postfachkontakte</span><span class="sxs-lookup"><span data-stu-id="5d498-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="5d498-208">Kalender</span><span class="sxs-lookup"><span data-stu-id="5d498-208">Calendar</span></span> </li>
<li> <span data-ttu-id="5d498-209">Signaturen</span><span class="sxs-lookup"><span data-stu-id="5d498-209">Signatures</span></span> </li>
<li> <span data-ttu-id="5d498-210">Aufgaben</span><span class="sxs-lookup"><span data-stu-id="5d498-210">Tasks</span></span> </li>
<li> <span data-ttu-id="5d498-211">E-Mails, die die zulässige Nachrichtengröße überschreiten</span><span class="sxs-lookup"><span data-stu-id="5d498-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="5d498-212">Archivdaten</span><span class="sxs-lookup"><span data-stu-id="5d498-212">Archive data</span></span> </li>
<li> <span data-ttu-id="5d498-213">Verschlüsselte E-Mail-Nachrichten</span><span class="sxs-lookup"><span data-stu-id="5d498-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="5d498-214">Beschädigte Elemente</span><span class="sxs-lookup"><span data-stu-id="5d498-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="5d498-215">Inaktive Postfächer</span><span class="sxs-lookup"><span data-stu-id="5d498-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-exchange-online-migrations"></a><span data-ttu-id="5d498-216">FastTrack-Verantwortlichkeiten für Exchange Online Migrationen</span><span class="sxs-lookup"><span data-stu-id="5d498-216">FastTrack responsibilities for Exchange Online migrations</span></span>

<span data-ttu-id="5d498-217">Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="5d498-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="5d498-218">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="5d498-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="5d498-219">Unsere FastTrack-Spezialisten führen außerdem die folgenden Aktivitäten speziell für Exchange-Migrationen durch:</span><span class="sxs-lookup"><span data-stu-id="5d498-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="5d498-220">Bereitstellen von Anleitungen, die Ihnen dabei helfen, die Koexistenz von SMTP-E-Mail-Routing zwischen Ihrer Quellumgebung und Exchange Online zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="5d498-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="5d498-221">Ihre Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="5d498-221">Your responsibilities</span></span>

<span data-ttu-id="5d498-222">Während des Migrationsprojekts führen Sie Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="5d498-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="5d498-223">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="5d498-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="5d498-224">Sie führen außerdem die folgenden Aktivitäten speziell für Exchange-Migrationen aus:</span><span class="sxs-lookup"><span data-stu-id="5d498-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="5d498-225">Durchführen des FastTrack-Onboarding-Vorgangs für Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="5d498-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="5d498-226">Wenn Sie das Onboarding selbst durchgeführt haben, müssen Sie die erforderlichen Überprüfungen und Voraussetzungen erfüllen.</span><span class="sxs-lookup"><span data-stu-id="5d498-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="5d498-227">Ausführliche Informationen finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="5d498-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="5d498-228">Installieren der entsprechenden Clientsoftwareebene gemäß den Office 365-Richtlinien.</span><span class="sxs-lookup"><span data-stu-id="5d498-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="5d498-229">Details finden Sie unter [Der moderne Arbeitsplatz](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="5d498-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="5d498-230">Erfüllen bestimmter Anforderungen, wenn Sie von einer lokalen Exchange-Umgebung migrieren möchten.</span><span class="sxs-lookup"><span data-stu-id="5d498-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="5d498-231">Weitere Informationen finden Sie unter [Voraussetzungen für die Hybridbereitstellung](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="5d498-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="5d498-232">Sicherstellen, dass jede Quellumgebung über das neueste Service Pack (SP) und Rollup (RU)/Cumulative Update (CU) verfügt, sofern zutreffend.</span><span class="sxs-lookup"><span data-stu-id="5d498-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="5d498-233">Konfigurieren und Validieren der Koexistenz von SMTP-E-Mail-Routing zwischen Ihrer Quellumgebung und Exchange Online, sofern zutreffend.</span><span class="sxs-lookup"><span data-stu-id="5d498-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="5d498-234">Sicherstellen, dass die Größe des Quellpostfachs das Zielpostfachkontingent nicht überschreitet.</span><span class="sxs-lookup"><span data-stu-id="5d498-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="5d498-235">Abhängig von der Quellplattform müssen Sie möglicherweise Ihre Quelldaten auf 85 % des Zielpostfachkontingents beschränken.</span><span class="sxs-lookup"><span data-stu-id="5d498-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="5d498-236">Ggf. Migrieren clientseitiger Daten.</span><span class="sxs-lookup"><span data-stu-id="5d498-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="5d498-237">Dies umfasst unter anderem lokale Adressbücher, Daten in lokalen PST-Dateien, Outlook-Regeln und lokale Outlook-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="5d498-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="5d498-238">Unterstützen Ihrer Endbenutzer bei der Behebung von Problemen bei der clientbasierten Migration.</span><span class="sxs-lookup"><span data-stu-id="5d498-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="5d498-239">Migration zu SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="5d498-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="5d498-240">Wenn Sie sich für die Migration Ihrer Dateien zu SharePoint Online mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit.</span><span class="sxs-lookup"><span data-stu-id="5d498-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="5d498-241">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des SharePoint Online-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Dateien.</span><span class="sxs-lookup"><span data-stu-id="5d498-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="5d498-242">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="5d498-242">You create and schedule your migration events.</span></span> <span data-ttu-id="5d498-243">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="5d498-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="5d498-244">Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass Dateien von entsprechend geplanten und berechtigten Quellen ihrer Quellumgebungen zu SharePoint Online migriert wurden.</span><span class="sxs-lookup"><span data-stu-id="5d498-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="5d498-245">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="5d498-245">Considerations</span></span>

 - <span data-ttu-id="5d498-246">Alle Migrationen unterliegen SharePoint Online-Kontingenten.</span><span class="sxs-lookup"><span data-stu-id="5d498-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="5d498-247">Weitere Informationen <a href="https://go.microsoft.com/fwlink/?LinkId=698855">finden SharePoint Grenzwerte.</a></span><span class="sxs-lookup"><span data-stu-id="5d498-247">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="5d498-248">Der Gesamtbetrag sollte auf 75 Prozent des SharePoint Online-Gesamtspeicherkontingents, für das Sie berechtigt sind, beschränkt werden (einschließlich den zusätzlichen Speicher, den Sie möglicherweise separat gekauft haben).</span><span class="sxs-lookup"><span data-stu-id="5d498-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

### <a name="source-environment-details"></a><span data-ttu-id="5d498-249">Detail der Quellumgebung</span><span class="sxs-lookup"><span data-stu-id="5d498-249">Source environment details</span></span>

<span data-ttu-id="5d498-250">Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:</span><span class="sxs-lookup"><span data-stu-id="5d498-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="5d498-251">Dateifreigaben (SMB [Server Message Block]-Dateifreigaben auf Geräten mit Unterstützung für SMB 2.0 und höher)</span><span class="sxs-lookup"><span data-stu-id="5d498-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="5d498-252">Eine einzelne G Suite-Umgebung (nur Google Drive).</span><span class="sxs-lookup"><span data-stu-id="5d498-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="5d498-253">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="5d498-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="5d498-254">Dropbox für Teams (Standard und Erweitert).</span><span class="sxs-lookup"><span data-stu-id="5d498-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="5d498-255">Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:</span><span class="sxs-lookup"><span data-stu-id="5d498-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="5d498-256"><strong>Quellumgebung</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="5d498-257"><strong>Migrationstyp</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="5d498-258"><strong>Was wird migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="5d498-259"><strong>Was wird nicht migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="5d498-260"><strong>Alle Dateifreigabegeräte mit Unterstützung für SMB 2.0 und höher</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="5d498-261">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="5d498-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5d498-262">Dokumente</span><span class="sxs-lookup"><span data-stu-id="5d498-262">Documents</span></span> </li>
<li> <span data-ttu-id="5d498-263">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="5d498-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5d498-264">Datei- und Ordnerberechtigungen auf Benutzerebene\*</span><span class="sxs-lookup"><span data-stu-id="5d498-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="5d498-265">Datei- und Ordnerberechtigungen auf Gruppenebene\*</span><span class="sxs-lookup"><span data-stu-id="5d498-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="5d498-266">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="5d498-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5d498-267">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="5d498-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5d498-268">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-268">Created date</span></span> </li>
<li> <span data-ttu-id="5d498-269">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-269">Modified date</span></span> </li>
<li> <span data-ttu-id="5d498-270">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="5d498-270">Created by</span></span> </li>
<li> <span data-ttu-id="5d498-271">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="5d498-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="5d498-272">\* Setzt die Konfiguration der Verzeichnissynchronisierung voraus.</span><span class="sxs-lookup"><span data-stu-id="5d498-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="5d498-273">Es werden nur NTFS-Berechtigungen migriert, die für den Windows-Datei-Explorer verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="5d498-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="5d498-274">Berechtigungen, die direkt auf Dateifreigabegeräten verwaltet werden, werden nicht migriert.</span><span class="sxs-lookup"><span data-stu-id="5d498-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="5d498-275">Wenn Daten auf einem SMB 2.0-Gerät gespeichert werden, werden die NTFS-äquivalenten Berechtigungen, die vom SMB-Protokoll verfügbar gemacht werden, migriert.</span><span class="sxs-lookup"><span data-stu-id="5d498-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="5d498-276">Aufgezeichnete Eigentümerschaft und frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="5d498-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="5d498-277">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="5d498-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5d498-278">Frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="5d498-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="5d498-279">Windows-Datei-/-Ordnerattribute (z. B. „Schreibgeschützt“ und „Ausgeblendet“) </span><span class="sxs-lookup"><span data-stu-id="5d498-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="5d498-280">Nicht-Windows-NTFS-Dateisystem (New Technology File System) und erweiterte NTFS-Berechtigungen sowie besondere Einstellungen:</span><span class="sxs-lookup"><span data-stu-id="5d498-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="5d498-281">Explizite Verweigerungsberechtigungen (werden nach der Migration entfernt, Inhalte unterliegen parallelen Berechtigungen oder Berechtigungen im übergeordneten Ordner).</span><span class="sxs-lookup"><span data-stu-id="5d498-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="5d498-282">Konfiguration der NTFS-Überwachung</span><span class="sxs-lookup"><span data-stu-id="5d498-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="5d498-283">Zusätzliche Dateimetadaten von der Dateiklassifizierungsinfrastruktur (File Classification Infrastructure, FCI)</span><span class="sxs-lookup"><span data-stu-id="5d498-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="5d498-284">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="5d498-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5d498-285">Ausgeblendete Freigaben</span><span class="sxs-lookup"><span data-stu-id="5d498-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="5d498-286">Freigabe (z. B. gewährte Berechtigungen auf Freigabeebene)</span><span class="sxs-lookup"><span data-stu-id="5d498-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="5d498-287">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">Onlineeinschränkungen SharePoint überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="5d498-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5d498-288"><strong>Einzelne G Suite-Umgebung (nur Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="5d498-289">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="5d498-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5d498-290">Google Docs, Google Tabellen und Google Präsentationen (Dateien werden in das entsprechende Office-Format konvertiert), einschließlich derjenigen über 10 MB</span><span class="sxs-lookup"><span data-stu-id="5d498-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="5d498-291">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="5d498-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5d498-292">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5d498-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5d498-293">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5d498-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5d498-294">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="5d498-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5d498-295">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="5d498-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5d498-296">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-296">Created date</span></span> </li>
<li> <span data-ttu-id="5d498-297">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-297">Modified date</span></span> </li>
<li> <span data-ttu-id="5d498-298">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="5d498-298">Created by</span></span> </li>
<li> <span data-ttu-id="5d498-299">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="5d498-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="5d498-300">Freigegebene Laufwerke (Ordner und Dateien)</span><span class="sxs-lookup"><span data-stu-id="5d498-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="5d498-301">Geteilte Inhalte, die im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="5d498-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5d498-302">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="5d498-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="5d498-303">Beschreibungen von Dateien und Ordnern, Ordnerfarben</span><span class="sxs-lookup"><span data-stu-id="5d498-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="5d498-304">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5d498-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="5d498-305">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5d498-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="5d498-306">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="5d498-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="5d498-307">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="5d498-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="5d498-308">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="5d498-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5d498-309">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="5d498-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="5d498-310">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="5d498-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5d498-311">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="5d498-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="5d498-312">Google Fotos, Google Formulare, Google Maps und andere verbundene Apps</span><span class="sxs-lookup"><span data-stu-id="5d498-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="5d498-313">Google Zeichnungen</span><span class="sxs-lookup"><span data-stu-id="5d498-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="5d498-314">Freigegebene Inhalte außerhalb Ihrer Organisation</span><span class="sxs-lookup"><span data-stu-id="5d498-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="5d498-315">Inhalte, die nicht im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="5d498-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="5d498-316">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Google Drive-Administratorberichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="5d498-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="5d498-317">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="5d498-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="5d498-318">Mitgliedschaftsberechtigungen für freigegebene Laufwerke (<strong>Hinweis</strong>: Verwenden Sie die Google Drive-Administratorberichte, um die Mitgliedschaften für freigegebene Laufwerke zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="5d498-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="5d498-319">Weisen Sie die Endbenutzer an, diese Mitgliedschaftseinstellungen auf dem Ziel vor der Migration zu konfigurieren.)</span><span class="sxs-lookup"><span data-stu-id="5d498-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="5d498-320">Als eingeschränkt markierte oder nicht kopierbare Dateien</span><span class="sxs-lookup"><span data-stu-id="5d498-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="5d498-321">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">Onlineeinschränkungen SharePoint überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="5d498-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5d498-322"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="5d498-323">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="5d498-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5d498-324">Dokumente</span><span class="sxs-lookup"><span data-stu-id="5d498-324">Documents</span></span> </li>
<li> <span data-ttu-id="5d498-325">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="5d498-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5d498-326">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5d498-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5d498-327">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5d498-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5d498-328">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="5d498-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5d498-329">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="5d498-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5d498-330">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-330">Created date</span></span> </li>
<li> <span data-ttu-id="5d498-331">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-331">Modified date</span></span> </li>
<li> <span data-ttu-id="5d498-332">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="5d498-332">Created by</span></span> </li>
<li> <span data-ttu-id="5d498-333">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="5d498-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="5d498-334">Geteilte Inhalte, die im Besitz des Box-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="5d498-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="5d498-335">Box Notes (in Word-Dokumentformat konvertiert)</span><span class="sxs-lookup"><span data-stu-id="5d498-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5d498-336">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="5d498-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="5d498-337">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="5d498-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="5d498-338">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5d498-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="5d498-339">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5d498-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="5d498-340">Box-Tags und erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="5d498-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="5d498-341">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="5d498-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="5d498-342">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="5d498-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5d498-343">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="5d498-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="5d498-344">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="5d498-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5d498-345">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="5d498-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="5d498-346">Box-Apps, Lesezeichen, Favoriten und Workflows</span><span class="sxs-lookup"><span data-stu-id="5d498-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="5d498-347">Inhalte, die nicht im Besitz des migrierten Box-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="5d498-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="5d498-348">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Box-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="5d498-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="5d498-349">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="5d498-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="5d498-350">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">Onlineeinschränkungen SharePoint überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="5d498-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5d498-351"><strong>Dropbox für Teams (Standard und Erweitert)</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="5d498-352">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="5d498-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5d498-353">Dokumente</span><span class="sxs-lookup"><span data-stu-id="5d498-353">Documents</span></span> </li>
<li> <span data-ttu-id="5d498-354">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="5d498-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5d498-355">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5d498-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5d498-356">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5d498-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5d498-357">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="5d498-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5d498-358">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="5d498-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5d498-359">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-359">Created date</span></span> </li>
<li> <span data-ttu-id="5d498-360">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-360">Modified date</span></span> </li>
<li> <span data-ttu-id="5d498-361">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="5d498-361">Created by</span></span> </li>
<li> <span data-ttu-id="5d498-362">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="5d498-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="5d498-363">Freigegebene Teamordner und -inhalte</span><span class="sxs-lookup"><span data-stu-id="5d498-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="5d498-364">Geteilte Inhalte, die im Besitz des Dropbox-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="5d498-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5d498-365">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="5d498-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="5d498-366">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="5d498-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="5d498-367">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5d498-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="5d498-368">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5d498-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="5d498-369">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="5d498-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="5d498-370">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="5d498-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="5d498-371">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="5d498-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5d498-372">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="5d498-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="5d498-373">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="5d498-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5d498-374">Nicht gemountete Dropbox-Ordner</span><span class="sxs-lookup"><span data-stu-id="5d498-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="5d498-375">Gelöschte oder getrennte Benutzer</span><span class="sxs-lookup"><span data-stu-id="5d498-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="5d498-376">Dropbox Paper, Showcases und Spaces</span><span class="sxs-lookup"><span data-stu-id="5d498-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="5d498-377">Dropbox-Apps und Favoriten (Pins/Sterne)</span><span class="sxs-lookup"><span data-stu-id="5d498-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="5d498-378">Inhalte, die nicht im Besitz des migrierten Dropbox-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="5d498-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="5d498-379">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Dropbox-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="5d498-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="5d498-380">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="5d498-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="5d498-381">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">Onlineeinschränkungen SharePoint überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="5d498-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-sharepoint-online-migrations"></a><span data-ttu-id="5d498-382">FastTrack-Verantwortlichkeiten für SharePoint Onlinemigrationen</span><span class="sxs-lookup"><span data-stu-id="5d498-382">FastTrack responsibilities for SharePoint Online migrations</span></span>

<span data-ttu-id="5d498-383">Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="5d498-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="5d498-384">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="5d498-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="5d498-385">Ihre Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="5d498-385">Your responsibilities</span></span>

<span data-ttu-id="5d498-386">Während des Migrationsprojekts führen Sie Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="5d498-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="5d498-387">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="5d498-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="5d498-388">Sie führen außerdem die folgenden Aktivitäten speziell für SharePoint Online-Migrationen aus:</span><span class="sxs-lookup"><span data-stu-id="5d498-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="5d498-389">Bereitstellen aller SharePoint-Teamwebsites, die für Ihre Migrationsereignisse vorgesehen sind.</span><span class="sxs-lookup"><span data-stu-id="5d498-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="5d498-390">Migration zu OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="5d498-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="5d498-391">Wenn Sie sich für die Migration Ihrer Dateien zu OneDrive for Business mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit.</span><span class="sxs-lookup"><span data-stu-id="5d498-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="5d498-392">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des OneDrive for Business-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Dateien.</span><span class="sxs-lookup"><span data-stu-id="5d498-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="5d498-393">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="5d498-393">You create and schedule your migration events.</span></span> <span data-ttu-id="5d498-394">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="5d498-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="5d498-395">Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass Dateien von entsprechend geplanten und berechtigten Quellen ihrer Quellumgebungen zu OneDrive for Business migriert wurden.</span><span class="sxs-lookup"><span data-stu-id="5d498-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

### <a name="considerations"></a><span data-ttu-id="5d498-396">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="5d498-396">Considerations</span></span>

  - <span data-ttu-id="5d498-397">Alle Migrationen unterliegen SharePoint Online-Kontingenten.</span><span class="sxs-lookup"><span data-stu-id="5d498-397">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="5d498-398">Weitere Informationen <a href="https://go.microsoft.com/fwlink/?LinkId=698855">finden SharePoint Grenzwerte.</a></span><span class="sxs-lookup"><span data-stu-id="5d498-398">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="5d498-399">Der Gesamtbetrag sollte auf 75 Prozent der Daten des SharePoint Online-Gesamtspeicherkontingents, für das Sie berechtigt sind, beschränkt werden (einschließlich den zusätzlichen Speicher, den Sie möglicherweise separat gekauft haben).</span><span class="sxs-lookup"><span data-stu-id="5d498-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="5d498-400">FastTrack migriert nur zu aktiven OneDrive for Business-Laufwerken.</span><span class="sxs-lookup"><span data-stu-id="5d498-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

### <a name="source-environment-details"></a><span data-ttu-id="5d498-401">Detail der Quellumgebung</span><span class="sxs-lookup"><span data-stu-id="5d498-401">Source environment details</span></span>

<span data-ttu-id="5d498-402">Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:</span><span class="sxs-lookup"><span data-stu-id="5d498-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="5d498-403">Dateifreigaben (SMB-Dateifreigaben auf Geräten mit Unterstützung für SMB 2.0 und höher)</span><span class="sxs-lookup"><span data-stu-id="5d498-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="5d498-404">Einzelne G Suite-Umgebung (nur Google Drive).</span><span class="sxs-lookup"><span data-stu-id="5d498-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="5d498-405">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="5d498-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="5d498-406">Dropbox für Teams (Standard und Erweitert).</span><span class="sxs-lookup"><span data-stu-id="5d498-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="5d498-407">Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:</span><span class="sxs-lookup"><span data-stu-id="5d498-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="5d498-408"><strong>Quellumgebung</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="5d498-409"><strong>Migrationstyp</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="5d498-410"><strong>Was wird migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="5d498-411"><strong>Was wird nicht migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="5d498-412"><strong>Alle Dateifreigabegeräte mit Unterstützung für SMB 2.0 und höher</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="5d498-413">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="5d498-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5d498-414">Dokumente</span><span class="sxs-lookup"><span data-stu-id="5d498-414">Documents</span></span> </li>
<li> <span data-ttu-id="5d498-415">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="5d498-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5d498-416">Datei- und Ordnerberechtigungen auf Benutzerebene\*</span><span class="sxs-lookup"><span data-stu-id="5d498-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="5d498-417">Datei- und Ordnerberechtigungen auf Gruppenebene\*</span><span class="sxs-lookup"><span data-stu-id="5d498-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="5d498-418">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="5d498-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5d498-419">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="5d498-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5d498-420">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-420">Created date</span></span> </li>
<li> <span data-ttu-id="5d498-421">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-421">Modified date</span></span> </li>
<li> <span data-ttu-id="5d498-422">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="5d498-422">Created by</span></span> </li>
<li> <span data-ttu-id="5d498-423">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="5d498-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="5d498-424">\* Setzt die Konfiguration der Verzeichnissynchronisierung voraus.</span><span class="sxs-lookup"><span data-stu-id="5d498-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="5d498-425">Es werden nur NTFS-Berechtigungen migriert, die für den Windows-Datei-Explorer verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="5d498-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="5d498-426">Berechtigungen, die direkt auf Dateifreigabegeräten verwaltet werden, werden nicht migriert.</span><span class="sxs-lookup"><span data-stu-id="5d498-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="5d498-427">Wenn Daten auf einem SMB 2.0-Gerät gespeichert werden, werden die NTFS-äquivalenten Berechtigungen, die vom SMB-Protokoll verfügbar gemacht werden, migriert.</span><span class="sxs-lookup"><span data-stu-id="5d498-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="5d498-428">Aufgezeichnete Eigentümerschaft und frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="5d498-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="5d498-429">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="5d498-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5d498-430">Frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="5d498-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="5d498-431">Windows-Datei-/-Ordnerattribute (z. B. „Schreibgeschützt“ und „Ausgeblendet“) </span><span class="sxs-lookup"><span data-stu-id="5d498-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="5d498-432">Nicht-Windows-NTFS-Dateisystem (New Technology File System) und erweiterte NTFS-Berechtigungen sowie besondere Einstellungen:</span><span class="sxs-lookup"><span data-stu-id="5d498-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="5d498-433">Explizite Verweigerungsberechtigungen (werden nach der Migration entfernt, Inhalte unterliegen parallelen Berechtigungen oder Berechtigungen im übergeordneten Ordner).</span><span class="sxs-lookup"><span data-stu-id="5d498-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="5d498-434">Konfiguration der NTFS-Überwachung</span><span class="sxs-lookup"><span data-stu-id="5d498-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="5d498-435">Zusätzliche Dateimetadaten von der Dateiklassifizierungsinfrastruktur (File Classification Infrastructure, FCI)</span><span class="sxs-lookup"><span data-stu-id="5d498-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="5d498-436">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="5d498-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5d498-437">Ausgeblendete Freigaben</span><span class="sxs-lookup"><span data-stu-id="5d498-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="5d498-438">Freigabe (z. B. gewährte Berechtigungen auf Freigabeebene)</span><span class="sxs-lookup"><span data-stu-id="5d498-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="5d498-439">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">Onlineeinschränkungen SharePoint überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="5d498-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5d498-440"><strong>Einzelne G Suite-Umgebung (nur Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="5d498-441">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="5d498-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5d498-442">Google Docs, Google Tabellen und Google Präsentationen (Dateien werden in das entsprechende Office-Format konvertiert, einschließlich derjenigen über 10 MB)</span><span class="sxs-lookup"><span data-stu-id="5d498-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="5d498-443">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="5d498-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5d498-444">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5d498-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5d498-445">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5d498-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5d498-446">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="5d498-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5d498-447">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="5d498-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5d498-448">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-448">Created date</span></span> </li>
<li> <span data-ttu-id="5d498-449">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-449">Modified date</span></span> </li>
<li> <span data-ttu-id="5d498-450">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="5d498-450">Created by</span></span> </li>
<li> <span data-ttu-id="5d498-451">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="5d498-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="5d498-452">Freigegebene Laufwerke (Ordner und Dateien)</span><span class="sxs-lookup"><span data-stu-id="5d498-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="5d498-453">Geteilte Inhalte, die im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="5d498-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5d498-454">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="5d498-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="5d498-455">Beschreibungen von Dateien und Ordnern, Ordnerfarben</span><span class="sxs-lookup"><span data-stu-id="5d498-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="5d498-456">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5d498-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="5d498-457">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5d498-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="5d498-458">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="5d498-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="5d498-459">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="5d498-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="5d498-460">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="5d498-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5d498-461">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="5d498-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="5d498-462">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="5d498-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5d498-463">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="5d498-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="5d498-464">Google Fotos, Google Formulare, Google Maps und andere verbundene Apps</span><span class="sxs-lookup"><span data-stu-id="5d498-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="5d498-465">Google Zeichnungen</span><span class="sxs-lookup"><span data-stu-id="5d498-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="5d498-466">Freigegebene Inhalte außerhalb Ihrer Organisation</span><span class="sxs-lookup"><span data-stu-id="5d498-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="5d498-467">Inhalte, die nicht im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="5d498-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="5d498-468">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Google Drive-Administratorberichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="5d498-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="5d498-469">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="5d498-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="5d498-470">Mitgliedschaftsberechtigungen für freigegebene Laufwerke (<strong>Hinweis</strong>: Verwenden Sie die Google Drive-Administratorberichte, um die Mitgliedschaften für freigegebene Laufwerke zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="5d498-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="5d498-471">Weisen Sie die Endbenutzer an, diese Mitgliedschaftseinstellungen auf dem Ziel vor der Migration zu konfigurieren.)</span><span class="sxs-lookup"><span data-stu-id="5d498-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="5d498-472">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">Onlineeinschränkungen SharePoint überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="5d498-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5d498-473"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="5d498-474">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="5d498-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5d498-475">Dokumente</span><span class="sxs-lookup"><span data-stu-id="5d498-475">Documents</span></span> </li>
<li> <span data-ttu-id="5d498-476">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="5d498-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5d498-477">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5d498-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5d498-478">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5d498-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5d498-479">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="5d498-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5d498-480">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="5d498-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5d498-481">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-481">Created date</span></span> </li>
<li> <span data-ttu-id="5d498-482">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-482">Modified date</span></span> </li>
<li> <span data-ttu-id="5d498-483">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="5d498-483">Created by</span></span> </li>
<li> <span data-ttu-id="5d498-484">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="5d498-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="5d498-485">Geteilte Inhalte, die im Besitz des Box-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="5d498-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5d498-486">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="5d498-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="5d498-487">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="5d498-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="5d498-488">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5d498-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="5d498-489">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5d498-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="5d498-490">Box-Tags und erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="5d498-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="5d498-491">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="5d498-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="5d498-492">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="5d498-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5d498-493">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="5d498-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="5d498-494">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="5d498-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5d498-495">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="5d498-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="5d498-496">Box-Apps, Lesezeichen, Favoriten und Workflows</span><span class="sxs-lookup"><span data-stu-id="5d498-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="5d498-497">Inhalte, die nicht im Besitz des migrierten Box-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="5d498-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="5d498-498">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Box-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="5d498-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="5d498-499">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="5d498-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="5d498-500">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">Onlineeinschränkungen SharePoint überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="5d498-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5d498-501"><strong>Dropbox für Teams (Standard und Erweitert)</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="5d498-502">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="5d498-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5d498-503">Dokumente</span><span class="sxs-lookup"><span data-stu-id="5d498-503">Documents</span></span> </li>
<li> <span data-ttu-id="5d498-504">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="5d498-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5d498-505">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5d498-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5d498-506">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5d498-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5d498-507">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="5d498-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5d498-508">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="5d498-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5d498-509">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-509">Created date</span></span> </li>
<li> <span data-ttu-id="5d498-510">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-510">Modified date</span></span> </li>
<li> <span data-ttu-id="5d498-511">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="5d498-511">Created by</span></span> </li>
<li> <span data-ttu-id="5d498-512">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="5d498-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="5d498-513">Freigegebene Teamordner und -inhalte</span><span class="sxs-lookup"><span data-stu-id="5d498-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="5d498-514">Geteilte Inhalte, die im Besitz des Dropbox-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="5d498-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5d498-515">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="5d498-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="5d498-516">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="5d498-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="5d498-517">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5d498-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="5d498-518">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5d498-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="5d498-519">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="5d498-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="5d498-520">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="5d498-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="5d498-521">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="5d498-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5d498-522">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="5d498-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="5d498-523">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="5d498-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5d498-524">Nicht gemountete Dropbox-Ordner</span><span class="sxs-lookup"><span data-stu-id="5d498-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="5d498-525">Gelöschte oder getrennte Benutzer</span><span class="sxs-lookup"><span data-stu-id="5d498-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="5d498-526">Dropbox Paper, Showcases und Spaces</span><span class="sxs-lookup"><span data-stu-id="5d498-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="5d498-527">Dropbox-Apps und Favoriten (Pins/Sterne)</span><span class="sxs-lookup"><span data-stu-id="5d498-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="5d498-528">Inhalte, die nicht im Besitz des migrierten Dropbox-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="5d498-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="5d498-529">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Dropbox-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="5d498-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="5d498-530">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="5d498-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="5d498-531">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">Onlineeinschränkungen SharePoint überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="5d498-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-onedrive-for-business-migrations"></a><span data-ttu-id="5d498-532">FastTrack-Verantwortlichkeiten für OneDrive for Business Migrationen</span><span class="sxs-lookup"><span data-stu-id="5d498-532">FastTrack responsibilities for OneDrive for Business migrations</span></span>

<span data-ttu-id="5d498-533">Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="5d498-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="5d498-534">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="5d498-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="5d498-535">Ihre Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="5d498-535">Your responsibilities</span></span>

<span data-ttu-id="5d498-536">Während des Migrationsprojekts führen Sie Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="5d498-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="5d498-537">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="5d498-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="5d498-538">Sie führen außerdem die folgenden Aktivitäten speziell für OneDrive for Business-Migrationen aus:</span><span class="sxs-lookup"><span data-stu-id="5d498-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="5d498-539">Bereitstellen aller OneDrive for Business-Websites, die für Ihre Migrationsereignisse bestimmt sind.</span><span class="sxs-lookup"><span data-stu-id="5d498-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a><span data-ttu-id="5d498-540">Migration zu Microsoft Teams und Microsoft 365 Gruppen</span><span class="sxs-lookup"><span data-stu-id="5d498-540">Migration to Microsoft Teams and Microsoft 365 Groups</span></span>

<span data-ttu-id="5d498-541">Wenn Sie FastTrack verwenden, um Ihre Dateien zu Microsoft Teams und Microsoft 365 zu migrieren, bieten wir Migrationsleitfäden und Datenmigrationsdienste.</span><span class="sxs-lookup"><span data-stu-id="5d498-541">When you choose to use FastTrack to migrate your files to Microsoft Teams and Microsoft 365 Groups, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="5d498-542">Wir bieten Anleitungen, mit denen Sie Ihre Migration planen, Ihre Quellumgebungen und Teams- und Microsoft 365-Gruppen konfigurieren und unsere Datenmigrationsdienste nutzen können, um Ihre Dateien zu migrieren.</span><span class="sxs-lookup"><span data-stu-id="5d498-542">We provide guidance to help you plan your migration, configure your source environments and Teams and Microsoft 365 Groups, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="5d498-543">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="5d498-543">You create and schedule your migration events.</span></span> <span data-ttu-id="5d498-544">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="5d498-544">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="5d498-545">Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie erwarten, dass Dateien aus entsprechend geplanten und berechtigten Quellen Ihrer Quellumgebungen zu Teams und Microsoft 365 migriert wurden.</span><span class="sxs-lookup"><span data-stu-id="5d498-545">When your migration events are completed, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to Teams and Microsoft 365 Groups.</span></span> <span data-ttu-id="5d498-546">Teams und Microsoft 365 Gruppen müssen vom Kunden vorab bereitgestellt werden, bevor sie Daten zu diesen Zieltypen migrieren können.</span><span class="sxs-lookup"><span data-stu-id="5d498-546">Teams channels and Microsoft 365 Groups  must be pre-provisioned by the customer before they can migrate data into these destination types.</span></span> <span data-ttu-id="5d498-547">Teams und Microsoft 365 Gruppen wirkt sich auf Ihre Berechtigungen auf den Dateizielspeicherort aus.</span><span class="sxs-lookup"><span data-stu-id="5d498-547">Teams and Microsoft 365 Groups impacts your permissions on the file destination location.</span></span> <span data-ttu-id="5d498-548">Teams und Microsoft 365 Gruppen sind so aufgebaut, dass die Zusammenarbeit ermöglicht wird.</span><span class="sxs-lookup"><span data-stu-id="5d498-548">Teams and Microsoft 365 Groups are built to allow collaboration.</span></span> <span data-ttu-id="5d498-549">Der Teams oder Microsoft 365 bestimmt, wer bei der Migration zu diesen Zielen Zugriff auf diese Dateien hat.</span><span class="sxs-lookup"><span data-stu-id="5d498-549">The Teams channel or Microsoft 365 group determine who has access to those files when migrating into those destinations.</span></span> <span data-ttu-id="5d498-550">FastTrack fügt während der Migration keine Endbenutzer oder Gruppen zu Teams kanal- oder Microsoft 365 Gruppenberechtigung hinzu.</span><span class="sxs-lookup"><span data-stu-id="5d498-550">FastTrack doesn't add end users or groups to any Teams channel or Microsoft 365 Groups permission during migration.</span></span>

### <a name="considerations"></a><span data-ttu-id="5d498-551">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="5d498-551">Considerations</span></span>

- <span data-ttu-id="5d498-552">Alle Migrationen unterliegen SharePoint Online-Kontingenten.</span><span class="sxs-lookup"><span data-stu-id="5d498-552">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="5d498-553">Weitere Informationen <a href="https://go.microsoft.com/fwlink/?LinkId=698855">finden SharePoint Grenzwerte.</a></span><span class="sxs-lookup"><span data-stu-id="5d498-553">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
- <span data-ttu-id="5d498-554">Der Gesamtbetrag sollte auf 75 Prozent des SharePoint Online-Gesamtspeicherkontingents, für das Sie berechtigt sind, beschränkt werden (einschließlich den zusätzlichen Speicher, den Sie möglicherweise separat gekauft haben).</span><span class="sxs-lookup"><span data-stu-id="5d498-554">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span> 


### <a name="source-environment-details"></a><span data-ttu-id="5d498-555">Detail der Quellumgebung</span><span class="sxs-lookup"><span data-stu-id="5d498-555">Source environment details</span></span>

<span data-ttu-id="5d498-556">Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:</span><span class="sxs-lookup"><span data-stu-id="5d498-556">Our data migration services migrate data from these source environments:</span></span> 

- <span data-ttu-id="5d498-557">Dateifreigaben (SMB [Server Message Block]-Dateifreigaben auf Geräten mit Unterstützung für SMB 2.0 und höher)</span><span class="sxs-lookup"><span data-stu-id="5d498-557">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
-  <span data-ttu-id="5d498-558">Eine einzelne G Suite-Umgebung (nur Google Drive).</span><span class="sxs-lookup"><span data-stu-id="5d498-558">A single G Suite environment (Google Drive only).</span></span> 
- <span data-ttu-id="5d498-559">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="5d498-559">Box (Starter, Business, Enterprise).</span></span> 
- <span data-ttu-id="5d498-560">Dropbox für Teams (Standard und Erweitert).</span><span class="sxs-lookup"><span data-stu-id="5d498-560">Dropbox for Teams (Standard and Advanced).</span></span> 

<span data-ttu-id="5d498-561">Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:</span><span class="sxs-lookup"><span data-stu-id="5d498-561">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="5d498-562"><strong>Quellumgebung</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-562"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="5d498-563"><strong>Migrationstyp</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-563"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="5d498-564"><strong>Was wird migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-564"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="5d498-565"><strong>Was wird nicht migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-565"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="5d498-566"><strong>Alle Dateifreigabegeräte mit Unterstützung für SMB 2.0 und höher</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-566"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="5d498-567">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="5d498-567">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5d498-568">Dokumente</span><span class="sxs-lookup"><span data-stu-id="5d498-568">Documents</span></span> </li>
<li> <span data-ttu-id="5d498-569">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="5d498-569">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5d498-570">Datei- und Ordnerberechtigungen auf Benutzerebene\*</span><span class="sxs-lookup"><span data-stu-id="5d498-570">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="5d498-571">Datei- und Ordnerberechtigungen auf Gruppenebene\*</span><span class="sxs-lookup"><span data-stu-id="5d498-571">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="5d498-572">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="5d498-572">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5d498-573">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="5d498-573">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5d498-574">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-574">Created date</span></span> </li>
<li> <span data-ttu-id="5d498-575">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-575">Modified date</span></span> </li>
<li> <span data-ttu-id="5d498-576">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="5d498-576">Created by</span></span> </li>
<li> <span data-ttu-id="5d498-577">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="5d498-577">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="5d498-578">\* Setzt die Konfiguration der Verzeichnissynchronisierung voraus.</span><span class="sxs-lookup"><span data-stu-id="5d498-578">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="5d498-579">Es werden nur NTFS-Berechtigungen migriert, die für den Windows-Datei-Explorer verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="5d498-579">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="5d498-580">Berechtigungen, die direkt auf Dateifreigabegeräten verwaltet werden, werden nicht migriert.</span><span class="sxs-lookup"><span data-stu-id="5d498-580">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="5d498-581">Wenn Daten auf einem SMB 2.0-Gerät gespeichert werden, werden die NTFS-äquivalenten Berechtigungen, die vom SMB-Protokoll verfügbar gemacht werden, migriert.</span><span class="sxs-lookup"><span data-stu-id="5d498-581">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> <span data-ttu-id="5d498-582">Berechtigungen werden von der gruppe Microsoft 365 und/oder Microsoft Teams betroffen.</span><span class="sxs-lookup"><span data-stu-id="5d498-582">Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="5d498-583">Wenn das Ziel ein Microsoft 365 oder Microsoft Teams ist, bestimmt die Gruppe oder der Kanal das endgültige Berechtigungsprofil für migrierte Dateien.</span><span class="sxs-lookup"><span data-stu-id="5d498-583">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="5d498-584">Es wird empfohlen, keine Berechtigungen für Dateien zu migrieren, die zu einer Microsoft 365 oder einem Microsoft Teams werden.</span><span class="sxs-lookup"><span data-stu-id="5d498-584">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span></td>
<td><ul>
<li> <span data-ttu-id="5d498-585">Besitzverlauf und frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="5d498-585">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="5d498-586">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="5d498-586">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5d498-587">Frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="5d498-587">Previous versions</span></span> </li>
<li> <span data-ttu-id="5d498-588">Windows-Datei-/-Ordnerattribute (z. B. „Schreibgeschützt“ und „Ausgeblendet“) </span><span class="sxs-lookup"><span data-stu-id="5d498-588">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="5d498-589">Nicht-Windows-NTFS-Dateisystem (New Technology File System) und erweiterte NTFS-Berechtigungen sowie besondere Einstellungen:</span><span class="sxs-lookup"><span data-stu-id="5d498-589">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="5d498-590">Explizite Verweigerungsberechtigungen (werden nach der Migration entfernt, Inhalte unterliegen parallelen Berechtigungen oder Berechtigungen im übergeordneten Ordner).</span><span class="sxs-lookup"><span data-stu-id="5d498-590">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="5d498-591">Konfiguration der NTFS-Überwachung</span><span class="sxs-lookup"><span data-stu-id="5d498-591">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="5d498-592">Zusätzliche Dateimetadaten von der Dateiklassifizierungsinfrastruktur (File Classification Infrastructure, FCI)</span><span class="sxs-lookup"><span data-stu-id="5d498-592">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="5d498-593">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="5d498-593">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5d498-594">Ausgeblendete Freigaben</span><span class="sxs-lookup"><span data-stu-id="5d498-594">Hidden shares</span></span> </li>
<li> <span data-ttu-id="5d498-595">Freigabe (z. B. gewährte Berechtigungen auf Freigabeebene)</span><span class="sxs-lookup"><span data-stu-id="5d498-595">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="5d498-596">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">Onlineeinschränkungen SharePoint überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="5d498-596">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5d498-597"><strong>Einzelne G Suite-Umgebung (nur Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-597"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="5d498-598">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="5d498-598">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5d498-599">Google Docs, Google Tabellen und Google Präsentationen (Dateien werden in das entsprechende Office-Format konvertiert, einschließlich derjenigen über 10 MB)</span><span class="sxs-lookup"><span data-stu-id="5d498-599">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="5d498-600">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="5d498-600">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5d498-601">Ordnerberechtigungen auf Benutzerebene\*</span><span class="sxs-lookup"><span data-stu-id="5d498-601">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="5d498-602">Ordnerberechtigungen auf Gruppenebene\*</span><span class="sxs-lookup"><span data-stu-id="5d498-602">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="5d498-603">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="5d498-603">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5d498-604">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="5d498-604">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5d498-605">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-605">Created date</span></span> </li>
<li> <span data-ttu-id="5d498-606">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-606">Modified date</span></span> </li>
<li> <span data-ttu-id="5d498-607">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="5d498-607">Created by</span></span> </li>
<li> <span data-ttu-id="5d498-608">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="5d498-608">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="5d498-609">Freigegebene Laufwerke (Ordner und Dateien)</span><span class="sxs-lookup"><span data-stu-id="5d498-609">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="5d498-610">Geteilte Inhalte, die im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="5d498-610">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="5d498-611">\*Berechtigungen werden von der Microsoft 365 gruppe und/oder Microsoft Teams betroffen.</span><span class="sxs-lookup"><span data-stu-id="5d498-611">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="5d498-612">Wenn das Ziel ein Microsoft 365 oder Microsoft Teams ist, bestimmt die Gruppe oder der Kanal das endgültige Berechtigungsprofil für migrierte Dateien.</span><span class="sxs-lookup"><span data-stu-id="5d498-612">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="5d498-613">Es wird empfohlen, keine Berechtigungen für Dateien zu migrieren, die zu einer Microsoft 365 oder einem Microsoft Teams werden.</span><span class="sxs-lookup"><span data-stu-id="5d498-613">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> 
</td>
<td><ul>
<li> <span data-ttu-id="5d498-614">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="5d498-614">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="5d498-615">Beschreibungen von Dateien und Ordnern, Ordnerfarben</span><span class="sxs-lookup"><span data-stu-id="5d498-615">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="5d498-616">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5d498-616">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="5d498-617">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5d498-617">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="5d498-618">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="5d498-618">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="5d498-619">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="5d498-619">File lock attributes</span></span> </li>
<li> <span data-ttu-id="5d498-620">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="5d498-620">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5d498-621">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="5d498-621">Trashed items</span></span> </li>
<li> <span data-ttu-id="5d498-622">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="5d498-622">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5d498-623">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="5d498-623">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="5d498-624">Google Fotos, Google Formulare, Google Maps und andere verbundene Apps</span><span class="sxs-lookup"><span data-stu-id="5d498-624">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="5d498-625">Google Zeichnungen</span><span class="sxs-lookup"><span data-stu-id="5d498-625">Google Drawings</span></span> </li>
<li> <span data-ttu-id="5d498-626">Freigegebene Inhalte außerhalb Ihrer Organisation</span><span class="sxs-lookup"><span data-stu-id="5d498-626">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="5d498-627">Inhalte, die nicht im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="5d498-627">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="5d498-628">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Google Drive-Administratorberichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="5d498-628">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="5d498-629">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="5d498-629">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="5d498-630">Mitgliedschaftsberechtigungen für freigegebene Laufwerke (<strong>Hinweis</strong>: Verwenden Sie die Google Drive-Administratorberichte, um die Mitgliedschaften für freigegebene Laufwerke zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="5d498-630">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="5d498-631">Weisen Sie die Endbenutzer an, diese Mitgliedschaftseinstellungen auf dem Ziel vor der Migration zu konfigurieren.)</span><span class="sxs-lookup"><span data-stu-id="5d498-631">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="5d498-632">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">Onlineeinschränkungen SharePoint überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="5d498-632">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5d498-633"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-633"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="5d498-634">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="5d498-634">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5d498-635">Dokumente</span><span class="sxs-lookup"><span data-stu-id="5d498-635">Documents</span></span> </li>
<li> <span data-ttu-id="5d498-636">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="5d498-636">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5d498-637">Ordnerberechtigungen auf Benutzerebene\*</span><span class="sxs-lookup"><span data-stu-id="5d498-637">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="5d498-638">Ordnerberechtigungen auf Gruppenebene\*</span><span class="sxs-lookup"><span data-stu-id="5d498-638">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="5d498-639">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="5d498-639">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5d498-640">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="5d498-640">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5d498-641">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-641">Created date</span></span> </li>
<li> <span data-ttu-id="5d498-642">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-642">Modified date</span></span> </li>
<li> <span data-ttu-id="5d498-643">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="5d498-643">Created by</span></span> </li>
<li> <span data-ttu-id="5d498-644">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="5d498-644">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="5d498-645">Geteilte Inhalte, die im Besitz des Box-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="5d498-645">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="5d498-646">Box Notes (in Word-Dokumentformat konvertiert)</span><span class="sxs-lookup"><span data-stu-id="5d498-646">Box Notes (converted to Word document format)</span></span> </li>
</ul>
<br>
<span data-ttu-id="5d498-647">\*Berechtigungen werden von der Microsoft 365 gruppe und/oder Microsoft Teams betroffen.</span><span class="sxs-lookup"><span data-stu-id="5d498-647">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="5d498-648">Wenn das Ziel ein Microsoft 365 oder Microsoft Teams ist, bestimmt die Gruppe oder der Kanal das endgültige Berechtigungsprofil für migrierte Dateien.</span><span class="sxs-lookup"><span data-stu-id="5d498-648">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="5d498-649">Es wird empfohlen, keine Berechtigungen für Dateien zu migrieren, die zu einer Microsoft 365 oder einem Microsoft Teams werden.</span><span class="sxs-lookup"><span data-stu-id="5d498-649">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="5d498-650">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="5d498-650">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="5d498-651">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="5d498-651">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="5d498-652">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5d498-652">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="5d498-653">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5d498-653">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="5d498-654">Box-Tags und erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="5d498-654">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="5d498-655">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="5d498-655">File lock attributes</span></span> </li>
<li> <span data-ttu-id="5d498-656">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="5d498-656">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5d498-657">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="5d498-657">Trashed items</span></span> </li>
<li> <span data-ttu-id="5d498-658">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="5d498-658">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5d498-659">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="5d498-659">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="5d498-660">Box-Apps, Lesezeichen, Favoriten und Workflows</span><span class="sxs-lookup"><span data-stu-id="5d498-660">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="5d498-661">Inhalte, die nicht im Besitz des migrierten Box-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="5d498-661">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="5d498-662">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Box-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="5d498-662">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="5d498-663">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="5d498-663">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="5d498-664">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">Onlineeinschränkungen SharePoint überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="5d498-664">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5d498-665"><strong>Dropbox für Teams (Standard und Erweitert)</strong></span><span class="sxs-lookup"><span data-stu-id="5d498-665"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="5d498-666">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="5d498-666">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5d498-667">Dokumente</span><span class="sxs-lookup"><span data-stu-id="5d498-667">Documents</span></span> </li>
<li> <span data-ttu-id="5d498-668">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="5d498-668">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5d498-669">Ordnerberechtigungen auf Benutzerebene\*</span><span class="sxs-lookup"><span data-stu-id="5d498-669">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="5d498-670">Ordnerberechtigungen auf Gruppenebene\*</span><span class="sxs-lookup"><span data-stu-id="5d498-670">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="5d498-671">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="5d498-671">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5d498-672">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="5d498-672">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5d498-673">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-673">Created date</span></span> </li>
<li> <span data-ttu-id="5d498-674">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="5d498-674">Modified date</span></span> </li>
<li> <span data-ttu-id="5d498-675">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="5d498-675">Created by</span></span> </li>
<li> <span data-ttu-id="5d498-676">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="5d498-676">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="5d498-677">Freigegebene Teamordner und -inhalte</span><span class="sxs-lookup"><span data-stu-id="5d498-677">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="5d498-678">Geteilte Inhalte, die im Besitz des Dropbox-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="5d498-678">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="5d498-679">\*Berechtigungen werden von der Microsoft 365 gruppe und/oder Microsoft Teams betroffen.</span><span class="sxs-lookup"><span data-stu-id="5d498-679">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="5d498-680">Wenn das Ziel ein Microsoft 365 oder Microsoft Teams ist, bestimmt die Gruppe oder der Kanal das endgültige Berechtigungsprofil für migrierte Dateien.</span><span class="sxs-lookup"><span data-stu-id="5d498-680">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="5d498-681">Es wird empfohlen, keine Berechtigungen für Dateien zu migrieren, die zu einer Microsoft 365 oder einem Microsoft Teams werden.</span><span class="sxs-lookup"><span data-stu-id="5d498-681">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span>
</td>
<td><ul>
<li> <span data-ttu-id="5d498-682">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="5d498-682">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="5d498-683">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="5d498-683">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="5d498-684">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5d498-684">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="5d498-685">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5d498-685">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="5d498-686">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="5d498-686">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="5d498-687">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="5d498-687">File lock attributes</span></span> </li>
<li> <span data-ttu-id="5d498-688">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="5d498-688">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5d498-689">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="5d498-689">Trashed items</span></span> </li>
<li> <span data-ttu-id="5d498-690">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="5d498-690">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5d498-691">Nicht gemountete Dropbox-Ordner</span><span class="sxs-lookup"><span data-stu-id="5d498-691">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="5d498-692">Gelöschte oder getrennte Benutzer</span><span class="sxs-lookup"><span data-stu-id="5d498-692">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="5d498-693">Dropbox Paper, Showcases und Spaces</span><span class="sxs-lookup"><span data-stu-id="5d498-693">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="5d498-694">Dropbox-Apps und Favoriten (Pins/Sterne)</span><span class="sxs-lookup"><span data-stu-id="5d498-694">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="5d498-695">Inhalte, die nicht im Besitz des migrierten Dropbox-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="5d498-695">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="5d498-696">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Dropbox-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="5d498-696">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="5d498-697">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="5d498-697">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="5d498-698">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">Onlineeinschränkungen SharePoint überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="5d498-698">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-microsoft-teams-and-microsoft-365-groups-migrations"></a><span data-ttu-id="5d498-699">FastTrack-Verantwortlichkeiten für Migrationen Microsoft Teams und Microsoft 365 Gruppen</span><span class="sxs-lookup"><span data-stu-id="5d498-699">FastTrack responsibilities for Microsoft Teams and Microsoft 365 Groups migrations</span></span>

<span data-ttu-id="5d498-700">Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="5d498-700">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="5d498-701">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="5d498-701">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="5d498-702">Ihre Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="5d498-702">Your responsibilities</span></span> 

<span data-ttu-id="5d498-703">Während des Migrationsprojekts führen Sie Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="5d498-703">You perform standard activities during the migration project.</span></span> <span data-ttu-id="5d498-704">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="5d498-704">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>
<span data-ttu-id="5d498-705">Außerdem führen Sie die folgenden Aktivitäten aus, die speziell für migrationsspezifische Microsoft Teams und Microsoft 365 gruppenspezifisch sind:</span><span class="sxs-lookup"><span data-stu-id="5d498-705">You also perform the following activities, specific to Microsoft Teams and Microsoft 365 Groups migrations:</span></span> 

- <span data-ttu-id="5d498-706">Bereitstellen aller Microsoft Teams und Microsoft 365 Gruppen, die auf Ihre Migrationsereignisse ausgerichtet sind.</span><span class="sxs-lookup"><span data-stu-id="5d498-706">Provision all Microsoft Teams channels and Microsoft 365 Groups as targeted by your migration events.</span></span>

> [!NOTE]
><span data-ttu-id="5d498-707">FastTrack gibt keine Vorabbereitstellung Microsoft Teams Kanälen oder Microsoft 365 Gruppen.</span><span class="sxs-lookup"><span data-stu-id="5d498-707">FastTrack doesn't pre-provision Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="5d498-708">FastTrack fügt keine Endbenutzer oder Gruppen zu Microsoft Teams kanälen oder Microsoft 365 hinzu.</span><span class="sxs-lookup"><span data-stu-id="5d498-708">FastTrack doesn't add end users or groups to Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="5d498-709">Sie müssen Ihre Endbenutzer oder Gruppen allen Microsoft Teams-Kanälen und Microsoft 365-Gruppen hinzufügen, bevor Sie Daten zu diesen Zielen migrieren, damit diese Endbenutzer Zugriff auf diese neu migrierten Dokumente haben.</span><span class="sxs-lookup"><span data-stu-id="5d498-709">You must add your end users or groups to all Microsoft Teams channels and Microsoft 365 Groups before you migrate data into those destinations so those end users have access to those newly migrated documents</span></span>