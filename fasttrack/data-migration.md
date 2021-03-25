---
title: Datenmigration
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 3/24/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Sie können die Migration von E-Mail- und Dateidaten in ihrer Quellumgebung auf Office 365 (Exchange Online, SharePoint Online und OneDrive for Business) mithilfe von FastTrack migrieren. Die Art der von uns bereitgestellten Unterstützung hängt von der Anzahl der Office 365-Lizenzen ab.
ms.openlocfilehash: f518e8dbda9200318022bad2cc12d1ba68263df8
ms.sourcegitcommit: 31d2c36fd00f47330dc2c90a646f8ce8a9687e1d
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/24/2021
ms.locfileid: "51188024"
---
# <a name="data-migration"></a><span data-ttu-id="3186e-104">Datenmigration</span><span class="sxs-lookup"><span data-stu-id="3186e-104">Data Migration</span></span>

<span data-ttu-id="3186e-105">Sie können die Migration von E-Mail- und Dateidaten in ihrer Quellumgebung auf Office 365 (Exchange Online, SharePoint Online und OneDrive for Business) mithilfe von FastTrack migrieren.</span><span class="sxs-lookup"><span data-stu-id="3186e-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="3186e-106">Die Art der von uns bereitgestellten Unterstützung hängt von der Anzahl der Office 365-Lizenzen ab:</span><span class="sxs-lookup"><span data-stu-id="3186e-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="3186e-107">**Für Office 365-Mandanten mit 150 bis 499-Lizenzen**: FastTrack bietet nur Migrationsanleitungen. Sie sind für die Durchführung der Datenmigration verantwortlich.</span><span class="sxs-lookup"><span data-stu-id="3186e-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="3186e-108">Wir führen Sie durch die Dokumentation, die Ihnen hilft, ﻿kostenlose Tools für die Durchführung einer Self-Service-Migration zu planen und zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="3186e-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="3186e-109">**Für Office 365-Mandanten mit 500 oder mehr Lizenzen**: FastTrack bietet Migrationsanleitungen und Datenmigrationsdienste.</span><span class="sxs-lookup"><span data-stu-id="3186e-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="3186e-110">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des Office 365-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Daten.</span><span class="sxs-lookup"><span data-stu-id="3186e-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="3186e-111">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="3186e-111">You create and schedule your migration events.</span></span> <span data-ttu-id="3186e-112">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="3186e-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="3186e-113">Wenn Sie einen kommerziellen Plan vor dem 1.9.2017 erworben oder verlängert haben, benötigen Sie nur 150 Lizenzen, um für Datenmigrationsdienste qualifiziert zu sein.</span><span class="sxs-lookup"><span data-stu-id="3186e-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="3186e-114">Bei Plänen für Bildungseinrichtungen sind nur Lehrpersonal und Mitarbeiter für Migrationsdienste berechtigt.</span><span class="sxs-lookup"><span data-stu-id="3186e-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="3186e-115">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="3186e-115">Considerations</span></span>

  - <span data-ttu-id="3186e-116">Ihre Quellumgebungen müssen bestimmte Erwartungen erfüllen, um Daten zu Office 365 zu migrieren.</span><span class="sxs-lookup"><span data-stu-id="3186e-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="3186e-117">Weitere Informationen zu den Erwartungen bezüglich der Quellumgebung für Exchange, SharePoint und OneDrive for Business finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="3186e-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="3186e-118">Für die Bereitstellung von Datenmigrationsdiensten benötigen wir einen geeigneten Zugriff auf Ihre Quellumgebungen und den Office 365-Mandanten.</span><span class="sxs-lookup"><span data-stu-id="3186e-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="3186e-119">Unsere Datenmigrationsdienste sind nicht für Daten vorgesehen, die besonderen rechtlichen oder behördlichen Vorschriften unterliegen.</span><span class="sxs-lookup"><span data-stu-id="3186e-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="3186e-120">Wenn wir Ihre Daten migrieren, können sie an einen beliebigen Ort, an dem wir über Einrichtungen verfügen, übertragen, dort gespeichert und verarbeitet werden (sofern nicht anderweitig für Ihr FastTrack-Migrationsprojekt angegeben).</span><span class="sxs-lookup"><span data-stu-id="3186e-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="3186e-121">Wir übernehmen keine Garantie für die Geschwindigkeit der E-Mail- oder Dateimigration.</span><span class="sxs-lookup"><span data-stu-id="3186e-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="3186e-122">Unvorhergesehene Probleme (wie unlesbare oder fehlerhafte Elemente in der Quellumgebung) verhindern möglicherweise, dass einige ihrer Datenelemente migriert werden können.</span><span class="sxs-lookup"><span data-stu-id="3186e-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="3186e-123">Externe Faktoren, die außerhalb unserer Kontrolle stehen (z. B. Änderungen an den Programmierschnittstellen von Drittanbietern) können zu Änderungen, Verzögerungen oder der Sperrung unserer Datenmigrationsdienste führen.</span><span class="sxs-lookup"><span data-stu-id="3186e-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="3186e-124">Verfügbarkeit des Migrationsdiensts</span><span class="sxs-lookup"><span data-stu-id="3186e-124">Migration service availability</span></span>

  - <span data-ttu-id="3186e-125">**Für kommerzielle Kunden und britische Behörden:** Wir stellen Datenmigrationsdienste rund um die Uhr an sieben (7) Tagen pro Woche bereit.</span><span class="sxs-lookup"><span data-stu-id="3186e-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="3186e-126">**Für Kunden von US-amerikanischen Behörden/Verteidigungsministerium:** Wir stellen Datenmigrationsdienste rund um die Uhr an fünf (5) Werktagen pro Woche bereit.</span><span class="sxs-lookup"><span data-stu-id="3186e-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="3186e-127">Migration zu Exchange Online</span><span class="sxs-lookup"><span data-stu-id="3186e-127">Migration to Exchange Online</span></span>

<span data-ttu-id="3186e-128">Wenn Sie sich für die Migration Ihrer E-Mails zu Exchange Online mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit.</span><span class="sxs-lookup"><span data-stu-id="3186e-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="3186e-129">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des Exchange Online-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Postfächer.</span><span class="sxs-lookup"><span data-stu-id="3186e-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="3186e-130">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="3186e-130">You create and schedule your migration events.</span></span> <span data-ttu-id="3186e-131">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="3186e-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="3186e-132">Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass E-Mail-Nachrichten von entsprechend geplanten und berechtigten Quellpostfächern ihrer Quellumgebungen zu Exchange Online migriert wurden.</span><span class="sxs-lookup"><span data-stu-id="3186e-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="3186e-133">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="3186e-133">Considerations</span></span>

  - <span data-ttu-id="3186e-134">Bevor Sie die Migration durchführen können, müssen Sie den FastTrack-Onboarding-Vorgang für Exchange Online durchführen.</span><span class="sxs-lookup"><span data-stu-id="3186e-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="3186e-135">Wenn Sie das Onboarding selbst durchgeführt haben, müssen Sie die erforderlichen Überprüfungen und Voraussetzungen erfüllen.</span><span class="sxs-lookup"><span data-stu-id="3186e-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="3186e-136">Ausführliche Informationen finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="3186e-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="3186e-137">FastTrack migriert nur zu aktiven Office 365-Postfächern.</span><span class="sxs-lookup"><span data-stu-id="3186e-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="3186e-138">Sie müssen bestimmte Anforderungen erfüllen, wenn Sie von einer lokalen Exchange-Umgebung migrieren möchten.</span><span class="sxs-lookup"><span data-stu-id="3186e-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="3186e-139">Weitere Informationen finden Sie unter [Voraussetzungen für die Hybridbereitstellung](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="3186e-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="3186e-140">Sämtliche Quellumgebungen müssen über die neuesten Service Packs (SP) verfügen und auf der Rollup (RU)-/Kumulativen Update (KU)-Ebene für das entsprechende Produkt in der Quellumgebung vorhanden sein.</span><span class="sxs-lookup"><span data-stu-id="3186e-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="3186e-141">Verteilerlisten (*MailEnabledGroup*-Objekte) und externe Kontakte (*MailEnabledContact*-Objekte) im lokalen Active Directory befinden, sind nicht Bestandteil einer Postfachdatenmigration.</span><span class="sxs-lookup"><span data-stu-id="3186e-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="3186e-142">Sie können Sie jedoch mithilfe von Azure Active Directory (Azure AD) Connect synchronisieren.</span><span class="sxs-lookup"><span data-stu-id="3186e-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="3186e-143">Quellumgebungen</span><span class="sxs-lookup"><span data-stu-id="3186e-143">Source environments</span></span>

<span data-ttu-id="3186e-144">Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:</span><span class="sxs-lookup"><span data-stu-id="3186e-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="3186e-145">aus einer einzelnen oder aus mehreren Active Directory-Gesamtstrukturen mit einer oder mehreren Exchange-Organisationen (jedes Exchange-E-Mail-System muss Exchange 2010 oder höher sein).</span><span class="sxs-lookup"><span data-stu-id="3186e-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="3186e-146">aus einer einzelnen IMAP-fähigen E-Mail-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="3186e-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="3186e-147">aus einer G Suite-Umgebung (nur Gmail, Kontakte und Kalender).</span><span class="sxs-lookup"><span data-stu-id="3186e-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="3186e-148">Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:</span><span class="sxs-lookup"><span data-stu-id="3186e-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="3186e-149"><strong>Quellumgebung</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="3186e-150"><strong>Migrationstyp</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="3186e-151"><strong>Was wird migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="3186e-152"><strong>Was wird nicht migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="3186e-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="3186e-154">
<strong>Hinweis:</strong> Informationen zu lokalen Exchange-Abhängigkeiten finden Sie unter <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Voraussetzungen für die Hybridbereitstellung</span></a>.</span><span class="sxs-lookup"><span data-stu-id="3186e-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="3186e-155">Migration mit Hybridbereitstellung</span><span class="sxs-lookup"><span data-stu-id="3186e-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="3186e-156">E-Mails</span><span class="sxs-lookup"><span data-stu-id="3186e-156">Emails</span></span></li>
<li><span data-ttu-id="3186e-157">Serverseitige Postfachregeln</span><span class="sxs-lookup"><span data-stu-id="3186e-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="3186e-158">Stellvertretungen</span><span class="sxs-lookup"><span data-stu-id="3186e-158">Delegates</span></span></li>
<li><span data-ttu-id="3186e-159">Postfachkontakte</span><span class="sxs-lookup"><span data-stu-id="3186e-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="3186e-160">Kalender</span><span class="sxs-lookup"><span data-stu-id="3186e-160">Calendar</span></span> </li>
<li> <span data-ttu-id="3186e-161">Aufgaben</span><span class="sxs-lookup"><span data-stu-id="3186e-161">Tasks</span></span> </li>
<li> <span data-ttu-id="3186e-162">E-Mails mit Rechteverwaltung</span><span class="sxs-lookup"><span data-stu-id="3186e-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="3186e-163">Verschlüsselte E-Mails</span><span class="sxs-lookup"><span data-stu-id="3186e-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="3186e-164">Signaturen</span><span class="sxs-lookup"><span data-stu-id="3186e-164">Signatures</span></span> </li>
<li> <span data-ttu-id="3186e-165">Persönliches Archiv, das mit dem Benutzerpostfach migriert wird</span><span class="sxs-lookup"><span data-stu-id="3186e-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="3186e-166">Wiederherstellbare Elemente</span><span class="sxs-lookup"><span data-stu-id="3186e-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3186e-167">Öffentliche Ordner</span><span class="sxs-lookup"><span data-stu-id="3186e-167">Public folders</span></span> </li>
<li> <span data-ttu-id="3186e-168">E-Mail, die die zulässige Nachrichtengröße überschreitet.</span><span class="sxs-lookup"><span data-stu-id="3186e-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="3186e-169">Journalarchiv oder eine beliebige Archivlösung von Drittanbietern</span><span class="sxs-lookup"><span data-stu-id="3186e-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="3186e-170">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="3186e-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3186e-171">Archivdaten aus PST-Dateien</span><span class="sxs-lookup"><span data-stu-id="3186e-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="3186e-172">Beschädigte Elemente</span><span class="sxs-lookup"><span data-stu-id="3186e-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="3186e-173">Inaktive Postfächer</span><span class="sxs-lookup"><span data-stu-id="3186e-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="3186e-174">Clientseitige Postfachregeln</span><span class="sxs-lookup"><span data-stu-id="3186e-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3186e-175"><strong>G Suite-Umgebung (nur Gmail, Kontakte und Kalender)</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="3186e-176">
<strong>Hinweis:</strong> Ihre G Suite-Umgebung muss die voraussetzungen erfüllen, die unter <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Ausführen einer G Suite-Migration beschrieben sind.</a></span><span class="sxs-lookup"><span data-stu-id="3186e-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="3186e-177">Übernahmemigration oder mehrstufige Migration</span><span class="sxs-lookup"><span data-stu-id="3186e-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="3186e-178">E-Mails</span><span class="sxs-lookup"><span data-stu-id="3186e-178">Emails</span></span> </li>
<li> <span data-ttu-id="3186e-179">Postfachkontakte (es werden maximal drei E-Mail-Adressen pro Kontakt migriert)</span><span class="sxs-lookup"><span data-stu-id="3186e-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="3186e-180">Kalender</span><span class="sxs-lookup"><span data-stu-id="3186e-180">Calendar</span></span> </li>
<li> <span data-ttu-id="3186e-181">Bezeichnungen</span><span class="sxs-lookup"><span data-stu-id="3186e-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3186e-182">Regeln</span><span class="sxs-lookup"><span data-stu-id="3186e-182">Rules</span></span> </li>
<li> <span data-ttu-id="3186e-183">Stellvertretungen</span><span class="sxs-lookup"><span data-stu-id="3186e-183">Delegates</span></span> </li>
<li> <span data-ttu-id="3186e-184">Signaturen</span><span class="sxs-lookup"><span data-stu-id="3186e-184">Signatures</span></span> </li>
<li> <span data-ttu-id="3186e-185">Aufgaben</span><span class="sxs-lookup"><span data-stu-id="3186e-185">Tasks</span></span> </li>
<li> <span data-ttu-id="3186e-186">E-Mails oder Anhänge, die die zulässige Nachrichtengröße überschreiten</span><span class="sxs-lookup"><span data-stu-id="3186e-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="3186e-187">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="3186e-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3186e-188">Archivdaten aus PST-Dateien oder einer Drittanbieter-Archivlösung (z. B. Google Vault)</span><span class="sxs-lookup"><span data-stu-id="3186e-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="3186e-189">E-Mails mit Rechteverwaltung oder Verschlüsselung</span><span class="sxs-lookup"><span data-stu-id="3186e-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="3186e-190">Beschädigte Elemente</span><span class="sxs-lookup"><span data-stu-id="3186e-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="3186e-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="3186e-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="3186e-192">Google-Gruppen</span><span class="sxs-lookup"><span data-stu-id="3186e-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="3186e-193">Ressourcenpostfächer</span><span class="sxs-lookup"><span data-stu-id="3186e-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="3186e-194">Inaktive Postfächer</span><span class="sxs-lookup"><span data-stu-id="3186e-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="3186e-195">Urlaubseinstellungen und Einstellungen für automatische Antworten</span><span class="sxs-lookup"><span data-stu-id="3186e-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="3186e-196">Freigegebene Kalender, Cloudanlagen, Google Hangout-Links und Ereignisfarben</span><span class="sxs-lookup"><span data-stu-id="3186e-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="3186e-197">\*\*Hangout-Unterhaltungen, die als Beschriftungen gespeichert wurden, werden migriert.</span><span class="sxs-lookup"><span data-stu-id="3186e-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="3186e-198"><strong>IMAP4-Quelle (wie Domino, GroupWise oder Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="3186e-199">Migration mit systemeigenen IMAP4-Tools</span><span class="sxs-lookup"><span data-stu-id="3186e-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="3186e-200">E-Mails</span><span class="sxs-lookup"><span data-stu-id="3186e-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="3186e-201">Regeln</span><span class="sxs-lookup"><span data-stu-id="3186e-201">Rules</span></span> </li>
<li> <span data-ttu-id="3186e-202">Stellvertretungen</span><span class="sxs-lookup"><span data-stu-id="3186e-202">Delegates</span></span> </li>
<li> <span data-ttu-id="3186e-203">Verteilerlisten</span><span class="sxs-lookup"><span data-stu-id="3186e-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="3186e-204">Externe Kontakte</span><span class="sxs-lookup"><span data-stu-id="3186e-204">External contacts</span></span> </li>
<li> <span data-ttu-id="3186e-205">E-Mail-aktivierte Benutzer</span><span class="sxs-lookup"><span data-stu-id="3186e-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="3186e-206">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="3186e-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3186e-207">Postfachkontakte</span><span class="sxs-lookup"><span data-stu-id="3186e-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="3186e-208">Kalender</span><span class="sxs-lookup"><span data-stu-id="3186e-208">Calendar</span></span> </li>
<li> <span data-ttu-id="3186e-209">Signaturen</span><span class="sxs-lookup"><span data-stu-id="3186e-209">Signatures</span></span> </li>
<li> <span data-ttu-id="3186e-210">Aufgaben</span><span class="sxs-lookup"><span data-stu-id="3186e-210">Tasks</span></span> </li>
<li> <span data-ttu-id="3186e-211">E-Mails, die die zulässige Nachrichtengröße überschreiten</span><span class="sxs-lookup"><span data-stu-id="3186e-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="3186e-212">Archivdaten</span><span class="sxs-lookup"><span data-stu-id="3186e-212">Archive data</span></span> </li>
<li> <span data-ttu-id="3186e-213">Verschlüsselte E-Mail-Nachrichten</span><span class="sxs-lookup"><span data-stu-id="3186e-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="3186e-214">Beschädigte Elemente</span><span class="sxs-lookup"><span data-stu-id="3186e-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="3186e-215">Inaktive Postfächer</span><span class="sxs-lookup"><span data-stu-id="3186e-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="3186e-216">FastTrack-Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="3186e-216">FastTrack responsibilities</span></span>

<span data-ttu-id="3186e-217">Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="3186e-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="3186e-218">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="3186e-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="3186e-219">Unsere FastTrack-Spezialisten führen außerdem die folgenden Aktivitäten speziell für Exchange-Migrationen durch:</span><span class="sxs-lookup"><span data-stu-id="3186e-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="3186e-220">Bereitstellen von Anleitungen, die Ihnen dabei helfen, die Koexistenz von SMTP-E-Mail-Routing zwischen Ihrer Quellumgebung und Exchange Online zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="3186e-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="3186e-221">Ihre Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="3186e-221">Your responsibilities</span></span>

<span data-ttu-id="3186e-222">Während des Migrationsprojekts führen Sie Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="3186e-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="3186e-223">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="3186e-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="3186e-224">Sie führen außerdem die folgenden Aktivitäten speziell für Exchange-Migrationen aus:</span><span class="sxs-lookup"><span data-stu-id="3186e-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="3186e-225">Durchführen des FastTrack-Onboarding-Vorgangs für Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="3186e-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="3186e-226">Wenn Sie das Onboarding selbst durchgeführt haben, müssen Sie die erforderlichen Überprüfungen und Voraussetzungen erfüllen.</span><span class="sxs-lookup"><span data-stu-id="3186e-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="3186e-227">Ausführliche Informationen finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="3186e-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="3186e-228">Installieren der entsprechenden Clientsoftwareebene gemäß den Office 365-Richtlinien.</span><span class="sxs-lookup"><span data-stu-id="3186e-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="3186e-229">Details finden Sie unter [Der moderne Arbeitsplatz](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="3186e-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="3186e-230">Erfüllen bestimmter Anforderungen, wenn Sie von einer lokalen Exchange-Umgebung migrieren möchten.</span><span class="sxs-lookup"><span data-stu-id="3186e-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="3186e-231">Weitere Informationen finden Sie unter [Voraussetzungen für die Hybridbereitstellung](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="3186e-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="3186e-232">Sicherstellen, dass jede Quellumgebung über das neueste Service Pack (SP) und Rollup (RU)/Cumulative Update (CU) verfügt, sofern zutreffend.</span><span class="sxs-lookup"><span data-stu-id="3186e-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="3186e-233">Konfigurieren und Validieren der Koexistenz von SMTP-E-Mail-Routing zwischen Ihrer Quellumgebung und Exchange Online, sofern zutreffend.</span><span class="sxs-lookup"><span data-stu-id="3186e-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="3186e-234">Sicherstellen, dass die Größe des Quellpostfachs das Zielpostfachkontingent nicht überschreitet.</span><span class="sxs-lookup"><span data-stu-id="3186e-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="3186e-235">Abhängig von der Quellplattform müssen Sie möglicherweise Ihre Quelldaten auf 85 % des Zielpostfachkontingents beschränken.</span><span class="sxs-lookup"><span data-stu-id="3186e-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="3186e-236">Ggf. Migrieren clientseitiger Daten.</span><span class="sxs-lookup"><span data-stu-id="3186e-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="3186e-237">Dies umfasst unter anderem lokale Adressbücher, Daten in lokalen PST-Dateien, Outlook-Regeln und lokale Outlook-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="3186e-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="3186e-238">Unterstützen Ihrer Endbenutzer bei der Behebung von Problemen bei der clientbasierten Migration.</span><span class="sxs-lookup"><span data-stu-id="3186e-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="3186e-239">Migration zu SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="3186e-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="3186e-240">Wenn Sie sich für die Migration Ihrer Dateien zu SharePoint Online mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit.</span><span class="sxs-lookup"><span data-stu-id="3186e-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="3186e-241">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des SharePoint Online-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Dateien.</span><span class="sxs-lookup"><span data-stu-id="3186e-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="3186e-242">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="3186e-242">You create and schedule your migration events.</span></span> <span data-ttu-id="3186e-243">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="3186e-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="3186e-244">Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass Dateien von entsprechend geplanten und berechtigten Quellen ihrer Quellumgebungen zu SharePoint Online migriert wurden.</span><span class="sxs-lookup"><span data-stu-id="3186e-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="3186e-245">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="3186e-245">Considerations</span></span>

 - <span data-ttu-id="3186e-246">Alle Migrationen unterliegen SharePoint Online-Kontingenten.</span><span class="sxs-lookup"><span data-stu-id="3186e-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="3186e-247">Weitere Informationen <a href="https://go.microsoft.com/fwlink/?LinkId=698855">finden Sie unter SharePoint-Grenzwerte.</a></span><span class="sxs-lookup"><span data-stu-id="3186e-247">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="3186e-248">Der Gesamtbetrag sollte auf 75 Prozent des SharePoint Online-Gesamtspeicherkontingents, für das Sie berechtigt sind, beschränkt werden (einschließlich den zusätzlichen Speicher, den Sie möglicherweise separat gekauft haben).</span><span class="sxs-lookup"><span data-stu-id="3186e-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="3186e-249">Detail der Quellumgebung</span><span class="sxs-lookup"><span data-stu-id="3186e-249">Source environment details</span></span>

<span data-ttu-id="3186e-250">Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:</span><span class="sxs-lookup"><span data-stu-id="3186e-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="3186e-251">Dateifreigaben (SMB [Server Message Block]-Dateifreigaben auf Geräten mit Unterstützung für SMB 2.0 und höher)</span><span class="sxs-lookup"><span data-stu-id="3186e-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="3186e-252">Eine einzelne G Suite-Umgebung (nur Google Drive).</span><span class="sxs-lookup"><span data-stu-id="3186e-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="3186e-253">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="3186e-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="3186e-254">Dropbox für Teams (Standard und Erweitert).</span><span class="sxs-lookup"><span data-stu-id="3186e-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="3186e-255">Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:</span><span class="sxs-lookup"><span data-stu-id="3186e-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="3186e-256"><strong>Quellumgebung</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="3186e-257"><strong>Migrationstyp</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="3186e-258"><strong>Was wird migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="3186e-259"><strong>Was wird nicht migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="3186e-260"><strong>Alle Dateifreigabegeräte mit Unterstützung für SMB 2.0 und höher</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="3186e-261">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="3186e-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3186e-262">Dokumente</span><span class="sxs-lookup"><span data-stu-id="3186e-262">Documents</span></span> </li>
<li> <span data-ttu-id="3186e-263">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="3186e-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3186e-264">Datei- und Ordnerberechtigungen auf Benutzerebene\*</span><span class="sxs-lookup"><span data-stu-id="3186e-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3186e-265">Datei- und Ordnerberechtigungen auf Gruppenebene\*</span><span class="sxs-lookup"><span data-stu-id="3186e-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3186e-266">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="3186e-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3186e-267">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="3186e-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3186e-268">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-268">Created date</span></span> </li>
<li> <span data-ttu-id="3186e-269">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-269">Modified date</span></span> </li>
<li> <span data-ttu-id="3186e-270">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="3186e-270">Created by</span></span> </li>
<li> <span data-ttu-id="3186e-271">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="3186e-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="3186e-272">\* Setzt die Konfiguration der Verzeichnissynchronisierung voraus.</span><span class="sxs-lookup"><span data-stu-id="3186e-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="3186e-273">Es werden nur NTFS-Berechtigungen migriert, die für den Windows-Datei-Explorer verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="3186e-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="3186e-274">Berechtigungen, die direkt auf Dateifreigabegeräten verwaltet werden, werden nicht migriert.</span><span class="sxs-lookup"><span data-stu-id="3186e-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="3186e-275">Wenn Daten auf einem SMB 2.0-Gerät gespeichert werden, werden die NTFS-äquivalenten Berechtigungen, die vom SMB-Protokoll verfügbar gemacht werden, migriert.</span><span class="sxs-lookup"><span data-stu-id="3186e-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="3186e-276">Aufgezeichnete Eigentümerschaft und frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="3186e-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="3186e-277">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="3186e-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3186e-278">Frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="3186e-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="3186e-279">Windows-Datei-/-Ordnerattribute (z. B. „Schreibgeschützt“ und „Ausgeblendet“) </span><span class="sxs-lookup"><span data-stu-id="3186e-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="3186e-280">Nicht-Windows-NTFS-Dateisystem (New Technology File System) und erweiterte NTFS-Berechtigungen sowie besondere Einstellungen:</span><span class="sxs-lookup"><span data-stu-id="3186e-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="3186e-281">Explizite Verweigerungsberechtigungen (werden nach der Migration entfernt, Inhalte unterliegen parallelen Berechtigungen oder Berechtigungen im übergeordneten Ordner).</span><span class="sxs-lookup"><span data-stu-id="3186e-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="3186e-282">Konfiguration der NTFS-Überwachung</span><span class="sxs-lookup"><span data-stu-id="3186e-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="3186e-283">Zusätzliche Dateimetadaten von der Dateiklassifizierungsinfrastruktur (File Classification Infrastructure, FCI)</span><span class="sxs-lookup"><span data-stu-id="3186e-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="3186e-284">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="3186e-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3186e-285">Ausgeblendete Freigaben</span><span class="sxs-lookup"><span data-stu-id="3186e-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="3186e-286">Freigabe (z. B. gewährte Berechtigungen auf Freigabeebene)</span><span class="sxs-lookup"><span data-stu-id="3186e-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="3186e-287">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online-Einschränkungen und -Einschränkungen überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="3186e-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3186e-288"><strong>Einzelne G Suite-Umgebung (nur Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="3186e-289">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="3186e-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3186e-290">Google Docs, Google Tabellen und Google Präsentationen (Dateien werden in das entsprechende Office-Format konvertiert), einschließlich derjenigen über 10 MB</span><span class="sxs-lookup"><span data-stu-id="3186e-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="3186e-291">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="3186e-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3186e-292">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="3186e-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3186e-293">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="3186e-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3186e-294">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="3186e-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3186e-295">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="3186e-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3186e-296">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-296">Created date</span></span> </li>
<li> <span data-ttu-id="3186e-297">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-297">Modified date</span></span> </li>
<li> <span data-ttu-id="3186e-298">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="3186e-298">Created by</span></span> </li>
<li> <span data-ttu-id="3186e-299">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="3186e-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3186e-300">Freigegebene Laufwerke (Ordner und Dateien)</span><span class="sxs-lookup"><span data-stu-id="3186e-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="3186e-301">Geteilte Inhalte, die im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="3186e-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3186e-302">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="3186e-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3186e-303">Beschreibungen von Dateien und Ordnern, Ordnerfarben</span><span class="sxs-lookup"><span data-stu-id="3186e-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="3186e-304">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="3186e-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3186e-305">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="3186e-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3186e-306">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="3186e-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3186e-307">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="3186e-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3186e-308">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="3186e-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3186e-309">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="3186e-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="3186e-310">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="3186e-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3186e-311">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="3186e-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3186e-312">Google Fotos, Google Formulare, Google Maps und andere verbundene Apps</span><span class="sxs-lookup"><span data-stu-id="3186e-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="3186e-313">Google Zeichnungen</span><span class="sxs-lookup"><span data-stu-id="3186e-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="3186e-314">Freigegebene Inhalte außerhalb Ihrer Organisation</span><span class="sxs-lookup"><span data-stu-id="3186e-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="3186e-315">Inhalte, die nicht im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="3186e-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="3186e-316">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Google Drive-Administratorberichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="3186e-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="3186e-317">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="3186e-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3186e-318">Mitgliedschaftsberechtigungen für freigegebene Laufwerke (<strong>Hinweis</strong>: Verwenden Sie die Google Drive-Administratorberichte, um die Mitgliedschaften für freigegebene Laufwerke zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="3186e-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="3186e-319">Weisen Sie die Endbenutzer an, diese Mitgliedschaftseinstellungen auf dem Ziel vor der Migration zu konfigurieren.)</span><span class="sxs-lookup"><span data-stu-id="3186e-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="3186e-320">Als eingeschränkt markierte oder nicht kopierbare Dateien</span><span class="sxs-lookup"><span data-stu-id="3186e-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="3186e-321">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online-Einschränkungen und -Einschränkungen überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="3186e-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="3186e-322"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="3186e-323">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="3186e-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3186e-324">Dokumente</span><span class="sxs-lookup"><span data-stu-id="3186e-324">Documents</span></span> </li>
<li> <span data-ttu-id="3186e-325">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="3186e-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3186e-326">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="3186e-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3186e-327">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="3186e-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3186e-328">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="3186e-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3186e-329">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="3186e-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3186e-330">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-330">Created date</span></span> </li>
<li> <span data-ttu-id="3186e-331">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-331">Modified date</span></span> </li>
<li> <span data-ttu-id="3186e-332">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="3186e-332">Created by</span></span> </li>
<li> <span data-ttu-id="3186e-333">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="3186e-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3186e-334">Geteilte Inhalte, die im Besitz des Box-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="3186e-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="3186e-335">Box Notes (in Word-Dokumentformat konvertiert)</span><span class="sxs-lookup"><span data-stu-id="3186e-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3186e-336">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="3186e-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3186e-337">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="3186e-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3186e-338">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="3186e-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3186e-339">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="3186e-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3186e-340">Box-Tags und erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="3186e-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="3186e-341">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="3186e-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3186e-342">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="3186e-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3186e-343">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="3186e-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="3186e-344">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="3186e-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3186e-345">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="3186e-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3186e-346">Box-Apps, Lesezeichen, Favoriten und Workflows</span><span class="sxs-lookup"><span data-stu-id="3186e-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="3186e-347">Inhalte, die nicht im Besitz des migrierten Box-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="3186e-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="3186e-348">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Box-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="3186e-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="3186e-349">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="3186e-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3186e-350">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online-Einschränkungen und -Einschränkungen überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="3186e-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3186e-351"><strong>Dropbox für Teams (Standard und Erweitert)</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="3186e-352">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="3186e-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3186e-353">Dokumente</span><span class="sxs-lookup"><span data-stu-id="3186e-353">Documents</span></span> </li>
<li> <span data-ttu-id="3186e-354">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="3186e-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3186e-355">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="3186e-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3186e-356">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="3186e-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3186e-357">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="3186e-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3186e-358">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="3186e-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3186e-359">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-359">Created date</span></span> </li>
<li> <span data-ttu-id="3186e-360">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-360">Modified date</span></span> </li>
<li> <span data-ttu-id="3186e-361">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="3186e-361">Created by</span></span> </li>
<li> <span data-ttu-id="3186e-362">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="3186e-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3186e-363">Freigegebene Teamordner und -inhalte</span><span class="sxs-lookup"><span data-stu-id="3186e-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="3186e-364">Geteilte Inhalte, die im Besitz des Dropbox-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="3186e-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3186e-365">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="3186e-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3186e-366">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="3186e-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3186e-367">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="3186e-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3186e-368">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="3186e-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3186e-369">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="3186e-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3186e-370">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="3186e-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3186e-371">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="3186e-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3186e-372">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="3186e-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="3186e-373">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="3186e-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3186e-374">Nicht gemountete Dropbox-Ordner</span><span class="sxs-lookup"><span data-stu-id="3186e-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="3186e-375">Gelöschte oder getrennte Benutzer</span><span class="sxs-lookup"><span data-stu-id="3186e-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="3186e-376">Dropbox Paper, Showcases und Spaces</span><span class="sxs-lookup"><span data-stu-id="3186e-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="3186e-377">Dropbox-Apps und Favoriten (Pins/Sterne)</span><span class="sxs-lookup"><span data-stu-id="3186e-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="3186e-378">Inhalte, die nicht im Besitz des migrierten Dropbox-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="3186e-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="3186e-379">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Dropbox-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="3186e-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="3186e-380">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="3186e-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="3186e-381">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online-Einschränkungen und -Einschränkungen überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="3186e-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="3186e-382">FastTrack-Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="3186e-382">FastTrack responsibilities</span></span>

<span data-ttu-id="3186e-383">Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="3186e-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="3186e-384">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="3186e-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="3186e-385">Ihre Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="3186e-385">Your responsibilities</span></span>

<span data-ttu-id="3186e-386">Während des Migrationsprojekts führen Sie Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="3186e-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="3186e-387">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="3186e-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="3186e-388">Sie führen außerdem die folgenden Aktivitäten speziell für SharePoint Online-Migrationen aus:</span><span class="sxs-lookup"><span data-stu-id="3186e-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="3186e-389">Bereitstellen aller SharePoint-Teamwebsites, die für Ihre Migrationsereignisse vorgesehen sind.</span><span class="sxs-lookup"><span data-stu-id="3186e-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="3186e-390">Migration zu OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="3186e-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="3186e-391">Wenn Sie sich für die Migration Ihrer Dateien zu OneDrive for Business mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit.</span><span class="sxs-lookup"><span data-stu-id="3186e-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="3186e-392">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des OneDrive for Business-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Dateien.</span><span class="sxs-lookup"><span data-stu-id="3186e-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="3186e-393">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="3186e-393">You create and schedule your migration events.</span></span> <span data-ttu-id="3186e-394">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="3186e-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="3186e-395">Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass Dateien von entsprechend geplanten und berechtigten Quellen ihrer Quellumgebungen zu OneDrive for Business migriert wurden.</span><span class="sxs-lookup"><span data-stu-id="3186e-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="3186e-396">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="3186e-396">Considerations</span></span>

  - <span data-ttu-id="3186e-397">Alle Migrationen unterliegen SharePoint Online-Kontingenten.</span><span class="sxs-lookup"><span data-stu-id="3186e-397">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="3186e-398">Weitere Informationen <a href="https://go.microsoft.com/fwlink/?LinkId=698855">finden Sie unter SharePoint-Grenzwerte.</a></span><span class="sxs-lookup"><span data-stu-id="3186e-398">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="3186e-399">Der Gesamtbetrag sollte auf 75 Prozent der Daten des SharePoint Online-Gesamtspeicherkontingents, für das Sie berechtigt sind, beschränkt werden (einschließlich den zusätzlichen Speicher, den Sie möglicherweise separat gekauft haben).</span><span class="sxs-lookup"><span data-stu-id="3186e-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="3186e-400">FastTrack migriert nur zu aktiven OneDrive for Business-Laufwerken.</span><span class="sxs-lookup"><span data-stu-id="3186e-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="3186e-401">Detail der Quellumgebung</span><span class="sxs-lookup"><span data-stu-id="3186e-401">Source environment details</span></span>

<span data-ttu-id="3186e-402">Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:</span><span class="sxs-lookup"><span data-stu-id="3186e-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="3186e-403">Dateifreigaben (SMB-Dateifreigaben auf Geräten mit Unterstützung für SMB 2.0 und höher)</span><span class="sxs-lookup"><span data-stu-id="3186e-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="3186e-404">Einzelne G Suite-Umgebung (nur Google Drive).</span><span class="sxs-lookup"><span data-stu-id="3186e-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="3186e-405">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="3186e-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="3186e-406">Dropbox für Teams (Standard und Erweitert).</span><span class="sxs-lookup"><span data-stu-id="3186e-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="3186e-407">Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:</span><span class="sxs-lookup"><span data-stu-id="3186e-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="3186e-408"><strong>Quellumgebung</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="3186e-409"><strong>Migrationstyp</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="3186e-410"><strong>Was wird migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="3186e-411"><strong>Was wird nicht migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="3186e-412"><strong>Alle Dateifreigabegeräte mit Unterstützung für SMB 2.0 und höher</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="3186e-413">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="3186e-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3186e-414">Dokumente</span><span class="sxs-lookup"><span data-stu-id="3186e-414">Documents</span></span> </li>
<li> <span data-ttu-id="3186e-415">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="3186e-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3186e-416">Datei- und Ordnerberechtigungen auf Benutzerebene\*</span><span class="sxs-lookup"><span data-stu-id="3186e-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3186e-417">Datei- und Ordnerberechtigungen auf Gruppenebene\*</span><span class="sxs-lookup"><span data-stu-id="3186e-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3186e-418">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="3186e-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3186e-419">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="3186e-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3186e-420">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-420">Created date</span></span> </li>
<li> <span data-ttu-id="3186e-421">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-421">Modified date</span></span> </li>
<li> <span data-ttu-id="3186e-422">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="3186e-422">Created by</span></span> </li>
<li> <span data-ttu-id="3186e-423">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="3186e-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="3186e-424">\* Setzt die Konfiguration der Verzeichnissynchronisierung voraus.</span><span class="sxs-lookup"><span data-stu-id="3186e-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="3186e-425">Es werden nur NTFS-Berechtigungen migriert, die für den Windows-Datei-Explorer verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="3186e-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="3186e-426">Berechtigungen, die direkt auf Dateifreigabegeräten verwaltet werden, werden nicht migriert.</span><span class="sxs-lookup"><span data-stu-id="3186e-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="3186e-427">Wenn Daten auf einem SMB 2.0-Gerät gespeichert werden, werden die NTFS-äquivalenten Berechtigungen, die vom SMB-Protokoll verfügbar gemacht werden, migriert.</span><span class="sxs-lookup"><span data-stu-id="3186e-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="3186e-428">Aufgezeichnete Eigentümerschaft und frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="3186e-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="3186e-429">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="3186e-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3186e-430">Frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="3186e-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="3186e-431">Windows-Datei-/-Ordnerattribute (z. B. „Schreibgeschützt“ und „Ausgeblendet“) </span><span class="sxs-lookup"><span data-stu-id="3186e-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="3186e-432">Nicht-Windows-NTFS-Dateisystem (New Technology File System) und erweiterte NTFS-Berechtigungen sowie besondere Einstellungen:</span><span class="sxs-lookup"><span data-stu-id="3186e-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="3186e-433">Explizite Verweigerungsberechtigungen (werden nach der Migration entfernt, Inhalte unterliegen parallelen Berechtigungen oder Berechtigungen im übergeordneten Ordner).</span><span class="sxs-lookup"><span data-stu-id="3186e-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="3186e-434">Konfiguration der NTFS-Überwachung</span><span class="sxs-lookup"><span data-stu-id="3186e-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="3186e-435">Zusätzliche Dateimetadaten von der Dateiklassifizierungsinfrastruktur (File Classification Infrastructure, FCI)</span><span class="sxs-lookup"><span data-stu-id="3186e-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="3186e-436">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="3186e-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3186e-437">Ausgeblendete Freigaben</span><span class="sxs-lookup"><span data-stu-id="3186e-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="3186e-438">Freigabe (z. B. gewährte Berechtigungen auf Freigabeebene)</span><span class="sxs-lookup"><span data-stu-id="3186e-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="3186e-439">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online-Einschränkungen und -Einschränkungen überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="3186e-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3186e-440"><strong>Einzelne G Suite-Umgebung (nur Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="3186e-441">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="3186e-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3186e-442">Google Docs, Google Tabellen und Google Präsentationen (Dateien werden in das entsprechende Office-Format konvertiert, einschließlich derjenigen über 10 MB)</span><span class="sxs-lookup"><span data-stu-id="3186e-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="3186e-443">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="3186e-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3186e-444">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="3186e-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3186e-445">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="3186e-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3186e-446">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="3186e-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3186e-447">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="3186e-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3186e-448">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-448">Created date</span></span> </li>
<li> <span data-ttu-id="3186e-449">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-449">Modified date</span></span> </li>
<li> <span data-ttu-id="3186e-450">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="3186e-450">Created by</span></span> </li>
<li> <span data-ttu-id="3186e-451">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="3186e-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3186e-452">Freigegebene Laufwerke (Ordner und Dateien)</span><span class="sxs-lookup"><span data-stu-id="3186e-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="3186e-453">Geteilte Inhalte, die im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="3186e-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3186e-454">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="3186e-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3186e-455">Beschreibungen von Dateien und Ordnern, Ordnerfarben</span><span class="sxs-lookup"><span data-stu-id="3186e-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="3186e-456">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="3186e-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3186e-457">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="3186e-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3186e-458">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="3186e-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3186e-459">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="3186e-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3186e-460">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="3186e-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3186e-461">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="3186e-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="3186e-462">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="3186e-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3186e-463">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="3186e-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3186e-464">Google Fotos, Google Formulare, Google Maps und andere verbundene Apps</span><span class="sxs-lookup"><span data-stu-id="3186e-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="3186e-465">Google Zeichnungen</span><span class="sxs-lookup"><span data-stu-id="3186e-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="3186e-466">Freigegebene Inhalte außerhalb Ihrer Organisation</span><span class="sxs-lookup"><span data-stu-id="3186e-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="3186e-467">Inhalte, die nicht im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="3186e-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="3186e-468">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Google Drive-Administratorberichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="3186e-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="3186e-469">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="3186e-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3186e-470">Mitgliedschaftsberechtigungen für freigegebene Laufwerke (<strong>Hinweis</strong>: Verwenden Sie die Google Drive-Administratorberichte, um die Mitgliedschaften für freigegebene Laufwerke zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="3186e-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="3186e-471">Weisen Sie die Endbenutzer an, diese Mitgliedschaftseinstellungen auf dem Ziel vor der Migration zu konfigurieren.)</span><span class="sxs-lookup"><span data-stu-id="3186e-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="3186e-472">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online-Einschränkungen und -Einschränkungen überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="3186e-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="3186e-473"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="3186e-474">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="3186e-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3186e-475">Dokumente</span><span class="sxs-lookup"><span data-stu-id="3186e-475">Documents</span></span> </li>
<li> <span data-ttu-id="3186e-476">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="3186e-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3186e-477">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="3186e-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3186e-478">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="3186e-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3186e-479">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="3186e-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3186e-480">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="3186e-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3186e-481">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-481">Created date</span></span> </li>
<li> <span data-ttu-id="3186e-482">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-482">Modified date</span></span> </li>
<li> <span data-ttu-id="3186e-483">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="3186e-483">Created by</span></span> </li>
<li> <span data-ttu-id="3186e-484">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="3186e-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3186e-485">Geteilte Inhalte, die im Besitz des Box-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="3186e-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3186e-486">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="3186e-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3186e-487">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="3186e-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3186e-488">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="3186e-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3186e-489">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="3186e-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3186e-490">Box-Tags und erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="3186e-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="3186e-491">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="3186e-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3186e-492">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="3186e-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3186e-493">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="3186e-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="3186e-494">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="3186e-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3186e-495">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="3186e-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3186e-496">Box-Apps, Lesezeichen, Favoriten und Workflows</span><span class="sxs-lookup"><span data-stu-id="3186e-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="3186e-497">Inhalte, die nicht im Besitz des migrierten Box-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="3186e-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="3186e-498">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Box-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="3186e-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="3186e-499">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="3186e-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3186e-500">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online-Einschränkungen und -Einschränkungen überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="3186e-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3186e-501"><strong>Dropbox für Teams (Standard und Erweitert)</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="3186e-502">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="3186e-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3186e-503">Dokumente</span><span class="sxs-lookup"><span data-stu-id="3186e-503">Documents</span></span> </li>
<li> <span data-ttu-id="3186e-504">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="3186e-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3186e-505">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="3186e-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3186e-506">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="3186e-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3186e-507">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="3186e-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3186e-508">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="3186e-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3186e-509">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-509">Created date</span></span> </li>
<li> <span data-ttu-id="3186e-510">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-510">Modified date</span></span> </li>
<li> <span data-ttu-id="3186e-511">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="3186e-511">Created by</span></span> </li>
<li> <span data-ttu-id="3186e-512">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="3186e-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3186e-513">Freigegebene Teamordner und -inhalte</span><span class="sxs-lookup"><span data-stu-id="3186e-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="3186e-514">Geteilte Inhalte, die im Besitz des Dropbox-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="3186e-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3186e-515">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="3186e-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3186e-516">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="3186e-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3186e-517">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="3186e-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3186e-518">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="3186e-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3186e-519">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="3186e-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3186e-520">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="3186e-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3186e-521">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="3186e-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3186e-522">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="3186e-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="3186e-523">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="3186e-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3186e-524">Nicht gemountete Dropbox-Ordner</span><span class="sxs-lookup"><span data-stu-id="3186e-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="3186e-525">Gelöschte oder getrennte Benutzer</span><span class="sxs-lookup"><span data-stu-id="3186e-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="3186e-526">Dropbox Paper, Showcases und Spaces</span><span class="sxs-lookup"><span data-stu-id="3186e-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="3186e-527">Dropbox-Apps und Favoriten (Pins/Sterne)</span><span class="sxs-lookup"><span data-stu-id="3186e-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="3186e-528">Inhalte, die nicht im Besitz des migrierten Dropbox-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="3186e-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="3186e-529">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Dropbox-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="3186e-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="3186e-530">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="3186e-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3186e-531">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online-Einschränkungen und -Einschränkungen überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="3186e-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="3186e-532">FastTrack-Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="3186e-532">FastTrack responsibilities</span></span>

<span data-ttu-id="3186e-533">Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="3186e-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="3186e-534">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="3186e-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="3186e-535">Ihre Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="3186e-535">Your responsibilities</span></span>

<span data-ttu-id="3186e-536">Während des Migrationsprojekts führen Sie Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="3186e-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="3186e-537">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="3186e-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="3186e-538">Sie führen außerdem die folgenden Aktivitäten speziell für OneDrive for Business-Migrationen aus:</span><span class="sxs-lookup"><span data-stu-id="3186e-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="3186e-539">Bereitstellen aller OneDrive for Business-Websites, die für Ihre Migrationsereignisse bestimmt sind.</span><span class="sxs-lookup"><span data-stu-id="3186e-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a><span data-ttu-id="3186e-540">Migration zu Microsoft Teams und Microsoft 365-Gruppen</span><span class="sxs-lookup"><span data-stu-id="3186e-540">Migration to Microsoft Teams and Microsoft 365 Groups</span></span>

<span data-ttu-id="3186e-541">Wenn Sie FastTrack verwenden, um Ihre Dateien zu Microsoft Teams und Microsoft 365-Gruppen zu migrieren, bieten wir Migrationsleitfäden und Datenmigrationsdienste.</span><span class="sxs-lookup"><span data-stu-id="3186e-541">When you choose to use FastTrack to migrate your files to Microsoft Teams and Microsoft 365 Groups, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="3186e-542">Wir bieten Anleitungen, mit denen Sie Ihre Migration planen, Ihre Quellumgebungen und Teams und Microsoft 365-Gruppen konfigurieren und unsere Datenmigrationsdienste nutzen können, um Ihre Dateien zu migrieren.</span><span class="sxs-lookup"><span data-stu-id="3186e-542">We provide guidance to help you plan your migration, configure your source environments and Teams and Microsoft 365 Groups, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="3186e-543">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="3186e-543">You create and schedule your migration events.</span></span> <span data-ttu-id="3186e-544">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="3186e-544">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="3186e-545">Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie erwarten, dass Dateien aus entsprechend geplanten und berechtigten Quellen Ihrer Quellumgebungen zu Teams und Microsoft 365-Gruppen migriert wurden.</span><span class="sxs-lookup"><span data-stu-id="3186e-545">When your migration events are completed, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to Teams and Microsoft 365 Groups.</span></span> <span data-ttu-id="3186e-546">Teams-Kanäle und Microsoft 365-Gruppen müssen vom Kunden vorab bereitgestellt werden, bevor sie Daten zu diesen Zieltypen migrieren können.</span><span class="sxs-lookup"><span data-stu-id="3186e-546">Teams channels and Microsoft 365 Groups  must be pre-provisioned by the customer before they can migrate data into these destination types.</span></span> <span data-ttu-id="3186e-547">Teams und Microsoft 365-Gruppen haben Auswirkungen auf Ihre Berechtigungen für den Dateizielspeicherort.</span><span class="sxs-lookup"><span data-stu-id="3186e-547">Teams and Microsoft 365 Groups impacts your permissions on the file destination location.</span></span> <span data-ttu-id="3186e-548">Teams und Microsoft 365-Gruppen sind so aufgebaut, dass die Zusammenarbeit ermöglicht wird.</span><span class="sxs-lookup"><span data-stu-id="3186e-548">Teams and Microsoft 365 Groups are built to allow collaboration.</span></span> <span data-ttu-id="3186e-549">Der Microsoft 365-Kanal oder die Microsoft 365-Gruppe bestimmen, wer bei der Migration zu diesen Zielen Zugriff auf diese Dateien hat.</span><span class="sxs-lookup"><span data-stu-id="3186e-549">The Teams channel or Microsoft 365 group determine who has access to those files when migrating into those destinations.</span></span> <span data-ttu-id="3186e-550">FastTrack fügt während der Migration keine Endbenutzer oder Gruppen zu einem Teams-Kanal oder zu Microsoft 365-Gruppen hinzu.</span><span class="sxs-lookup"><span data-stu-id="3186e-550">FastTrack doesn't add end users or groups to any Teams channel or Microsoft 365 Groups permission during migration.</span></span>

## <a name="considerations"></a><span data-ttu-id="3186e-551">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="3186e-551">Considerations</span></span>

- <span data-ttu-id="3186e-552">Alle Migrationen unterliegen SharePoint Online-Kontingenten.</span><span class="sxs-lookup"><span data-stu-id="3186e-552">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="3186e-553">Weitere Informationen <a href="https://go.microsoft.com/fwlink/?LinkId=698855">finden Sie unter SharePoint-Grenzwerte.</a></span><span class="sxs-lookup"><span data-stu-id="3186e-553">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
- <span data-ttu-id="3186e-554">Der Gesamtbetrag sollte auf 75 Prozent des SharePoint Online-Gesamtspeicherkontingents, für das Sie berechtigt sind, beschränkt werden (einschließlich den zusätzlichen Speicher, den Sie möglicherweise separat gekauft haben).</span><span class="sxs-lookup"><span data-stu-id="3186e-554">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span> 


## <a name="source-environment-details"></a><span data-ttu-id="3186e-555">Detail der Quellumgebung</span><span class="sxs-lookup"><span data-stu-id="3186e-555">Source environment details</span></span>

<span data-ttu-id="3186e-556">Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:</span><span class="sxs-lookup"><span data-stu-id="3186e-556">Our data migration services migrate data from these source environments:</span></span> 

- <span data-ttu-id="3186e-557">Dateifreigaben (SMB [Server Message Block]-Dateifreigaben auf Geräten mit Unterstützung für SMB 2.0 und höher)</span><span class="sxs-lookup"><span data-stu-id="3186e-557">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
-  <span data-ttu-id="3186e-558">Eine einzelne G Suite-Umgebung (nur Google Drive).</span><span class="sxs-lookup"><span data-stu-id="3186e-558">A single G Suite environment (Google Drive only).</span></span> 
- <span data-ttu-id="3186e-559">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="3186e-559">Box (Starter, Business, Enterprise).</span></span> 
- <span data-ttu-id="3186e-560">Dropbox für Teams (Standard und Erweitert).</span><span class="sxs-lookup"><span data-stu-id="3186e-560">Dropbox for Teams (Standard and Advanced).</span></span> 

<span data-ttu-id="3186e-561">Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:</span><span class="sxs-lookup"><span data-stu-id="3186e-561">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="3186e-562"><strong>Quellumgebung</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-562"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="3186e-563"><strong>Migrationstyp</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-563"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="3186e-564"><strong>Was wird migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-564"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="3186e-565"><strong>Was wird nicht migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-565"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="3186e-566"><strong>Alle Dateifreigabegeräte mit Unterstützung für SMB 2.0 und höher</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-566"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="3186e-567">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="3186e-567">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3186e-568">Dokumente</span><span class="sxs-lookup"><span data-stu-id="3186e-568">Documents</span></span> </li>
<li> <span data-ttu-id="3186e-569">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="3186e-569">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3186e-570">Datei- und Ordnerberechtigungen auf Benutzerebene\*</span><span class="sxs-lookup"><span data-stu-id="3186e-570">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3186e-571">Datei- und Ordnerberechtigungen auf Gruppenebene\*</span><span class="sxs-lookup"><span data-stu-id="3186e-571">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3186e-572">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="3186e-572">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3186e-573">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="3186e-573">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3186e-574">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-574">Created date</span></span> </li>
<li> <span data-ttu-id="3186e-575">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-575">Modified date</span></span> </li>
<li> <span data-ttu-id="3186e-576">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="3186e-576">Created by</span></span> </li>
<li> <span data-ttu-id="3186e-577">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="3186e-577">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="3186e-578">\* Setzt die Konfiguration der Verzeichnissynchronisierung voraus.</span><span class="sxs-lookup"><span data-stu-id="3186e-578">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="3186e-579">Es werden nur NTFS-Berechtigungen migriert, die für den Windows-Datei-Explorer verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="3186e-579">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="3186e-580">Berechtigungen, die direkt auf Dateifreigabegeräten verwaltet werden, werden nicht migriert.</span><span class="sxs-lookup"><span data-stu-id="3186e-580">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="3186e-581">Wenn Daten auf einem SMB 2.0-Gerät gespeichert werden, werden die NTFS-äquivalenten Berechtigungen, die vom SMB-Protokoll verfügbar gemacht werden, migriert.</span><span class="sxs-lookup"><span data-stu-id="3186e-581">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> <span data-ttu-id="3186e-582">Berechtigungen werden vom Microsoft 365-Gruppen- und/oder Microsoft Teams-Kanal betroffen.</span><span class="sxs-lookup"><span data-stu-id="3186e-582">Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="3186e-583">Wenn es sich bei dem Ziel um einen Microsoft 365-Gruppen- oder Microsoft Teams-Kanal handelt, bestimmt die Gruppe oder der Kanal das endgültige Berechtigungsprofil für migrierte Dateien.</span><span class="sxs-lookup"><span data-stu-id="3186e-583">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="3186e-584">Es wird empfohlen, keine Berechtigungen für Dateien zu migrieren, die zu einem Microsoft 365-Gruppen- oder Microsoft Teams-Kanal migriert werden.</span><span class="sxs-lookup"><span data-stu-id="3186e-584">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span></td>
<td><ul>
<li> <span data-ttu-id="3186e-585">Besitzverlauf und frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="3186e-585">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="3186e-586">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="3186e-586">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3186e-587">Frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="3186e-587">Previous versions</span></span> </li>
<li> <span data-ttu-id="3186e-588">Windows-Datei-/-Ordnerattribute (z. B. „Schreibgeschützt“ und „Ausgeblendet“) </span><span class="sxs-lookup"><span data-stu-id="3186e-588">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="3186e-589">Nicht-Windows-NTFS-Dateisystem (New Technology File System) und erweiterte NTFS-Berechtigungen sowie besondere Einstellungen:</span><span class="sxs-lookup"><span data-stu-id="3186e-589">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="3186e-590">Explizite Verweigerungsberechtigungen (werden nach der Migration entfernt, Inhalte unterliegen parallelen Berechtigungen oder Berechtigungen im übergeordneten Ordner).</span><span class="sxs-lookup"><span data-stu-id="3186e-590">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="3186e-591">Konfiguration der NTFS-Überwachung</span><span class="sxs-lookup"><span data-stu-id="3186e-591">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="3186e-592">Zusätzliche Dateimetadaten von der Dateiklassifizierungsinfrastruktur (File Classification Infrastructure, FCI)</span><span class="sxs-lookup"><span data-stu-id="3186e-592">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="3186e-593">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="3186e-593">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3186e-594">Ausgeblendete Freigaben</span><span class="sxs-lookup"><span data-stu-id="3186e-594">Hidden shares</span></span> </li>
<li> <span data-ttu-id="3186e-595">Freigabe (z. B. gewährte Berechtigungen auf Freigabeebene)</span><span class="sxs-lookup"><span data-stu-id="3186e-595">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="3186e-596">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online-Einschränkungen und -Einschränkungen überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="3186e-596">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3186e-597"><strong>Einzelne G Suite-Umgebung (nur Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-597"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="3186e-598">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="3186e-598">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3186e-599">Google Docs, Google Tabellen und Google Präsentationen (Dateien werden in das entsprechende Office-Format konvertiert, einschließlich derjenigen über 10 MB)</span><span class="sxs-lookup"><span data-stu-id="3186e-599">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="3186e-600">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="3186e-600">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3186e-601">Ordnerberechtigungen auf Benutzerebene\*</span><span class="sxs-lookup"><span data-stu-id="3186e-601">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3186e-602">Ordnerberechtigungen auf Gruppenebene\*</span><span class="sxs-lookup"><span data-stu-id="3186e-602">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3186e-603">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="3186e-603">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3186e-604">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="3186e-604">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3186e-605">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-605">Created date</span></span> </li>
<li> <span data-ttu-id="3186e-606">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-606">Modified date</span></span> </li>
<li> <span data-ttu-id="3186e-607">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="3186e-607">Created by</span></span> </li>
<li> <span data-ttu-id="3186e-608">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="3186e-608">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3186e-609">Freigegebene Laufwerke (Ordner und Dateien)</span><span class="sxs-lookup"><span data-stu-id="3186e-609">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="3186e-610">Geteilte Inhalte, die im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="3186e-610">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="3186e-611">\*Berechtigungen werden vom Microsoft 365-Gruppen- und/oder Microsoft #A0 betroffen.</span><span class="sxs-lookup"><span data-stu-id="3186e-611">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="3186e-612">Wenn es sich bei dem Ziel um einen Microsoft 365-Gruppen- oder Microsoft Teams-Kanal handelt, bestimmt die Gruppe oder der Kanal das endgültige Berechtigungsprofil für migrierte Dateien.</span><span class="sxs-lookup"><span data-stu-id="3186e-612">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="3186e-613">Es wird empfohlen, keine Berechtigungen für Dateien zu migrieren, die zu einem Microsoft 365-Gruppen- oder Microsoft Teams-Kanal migriert werden.</span><span class="sxs-lookup"><span data-stu-id="3186e-613">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> 
</td>
<td><ul>
<li> <span data-ttu-id="3186e-614">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="3186e-614">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3186e-615">Beschreibungen von Dateien und Ordnern, Ordnerfarben</span><span class="sxs-lookup"><span data-stu-id="3186e-615">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="3186e-616">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="3186e-616">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3186e-617">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="3186e-617">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3186e-618">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="3186e-618">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3186e-619">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="3186e-619">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3186e-620">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="3186e-620">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3186e-621">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="3186e-621">Trashed items</span></span> </li>
<li> <span data-ttu-id="3186e-622">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="3186e-622">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3186e-623">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="3186e-623">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3186e-624">Google Fotos, Google Formulare, Google Maps und andere verbundene Apps</span><span class="sxs-lookup"><span data-stu-id="3186e-624">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="3186e-625">Google Zeichnungen</span><span class="sxs-lookup"><span data-stu-id="3186e-625">Google Drawings</span></span> </li>
<li> <span data-ttu-id="3186e-626">Freigegebene Inhalte außerhalb Ihrer Organisation</span><span class="sxs-lookup"><span data-stu-id="3186e-626">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="3186e-627">Inhalte, die nicht im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="3186e-627">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="3186e-628">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Google Drive-Administratorberichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="3186e-628">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="3186e-629">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="3186e-629">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3186e-630">Mitgliedschaftsberechtigungen für freigegebene Laufwerke (<strong>Hinweis</strong>: Verwenden Sie die Google Drive-Administratorberichte, um die Mitgliedschaften für freigegebene Laufwerke zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="3186e-630">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="3186e-631">Weisen Sie die Endbenutzer an, diese Mitgliedschaftseinstellungen auf dem Ziel vor der Migration zu konfigurieren.)</span><span class="sxs-lookup"><span data-stu-id="3186e-631">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="3186e-632">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online-Einschränkungen und -Einschränkungen überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="3186e-632">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="3186e-633"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-633"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="3186e-634">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="3186e-634">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3186e-635">Dokumente</span><span class="sxs-lookup"><span data-stu-id="3186e-635">Documents</span></span> </li>
<li> <span data-ttu-id="3186e-636">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="3186e-636">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3186e-637">Ordnerberechtigungen auf Benutzerebene\*</span><span class="sxs-lookup"><span data-stu-id="3186e-637">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3186e-638">Ordnerberechtigungen auf Gruppenebene\*</span><span class="sxs-lookup"><span data-stu-id="3186e-638">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3186e-639">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="3186e-639">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3186e-640">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="3186e-640">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3186e-641">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-641">Created date</span></span> </li>
<li> <span data-ttu-id="3186e-642">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-642">Modified date</span></span> </li>
<li> <span data-ttu-id="3186e-643">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="3186e-643">Created by</span></span> </li>
<li> <span data-ttu-id="3186e-644">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="3186e-644">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3186e-645">Geteilte Inhalte, die im Besitz des Box-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="3186e-645">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="3186e-646">Box Notes (in Word-Dokumentformat konvertiert)</span><span class="sxs-lookup"><span data-stu-id="3186e-646">Box Notes (converted to Word document format)</span></span> </li>
</ul>
<br>
<span data-ttu-id="3186e-647">\*Berechtigungen werden vom Microsoft 365-Gruppen- und/oder Microsoft #A0 betroffen.</span><span class="sxs-lookup"><span data-stu-id="3186e-647">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="3186e-648">Wenn es sich bei dem Ziel um einen Microsoft 365-Gruppen- oder Microsoft Teams-Kanal handelt, bestimmt die Gruppe oder der Kanal das endgültige Berechtigungsprofil für migrierte Dateien.</span><span class="sxs-lookup"><span data-stu-id="3186e-648">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="3186e-649">Es wird empfohlen, keine Berechtigungen für Dateien zu migrieren, die zu einem Microsoft 365-Gruppen- oder Microsoft Teams-Kanal migriert werden.</span><span class="sxs-lookup"><span data-stu-id="3186e-649">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="3186e-650">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="3186e-650">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3186e-651">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="3186e-651">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3186e-652">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="3186e-652">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3186e-653">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="3186e-653">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3186e-654">Box-Tags und erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="3186e-654">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="3186e-655">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="3186e-655">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3186e-656">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="3186e-656">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3186e-657">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="3186e-657">Trashed items</span></span> </li>
<li> <span data-ttu-id="3186e-658">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="3186e-658">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3186e-659">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="3186e-659">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3186e-660">Box-Apps, Lesezeichen, Favoriten und Workflows</span><span class="sxs-lookup"><span data-stu-id="3186e-660">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="3186e-661">Inhalte, die nicht im Besitz des migrierten Box-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="3186e-661">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="3186e-662">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Box-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="3186e-662">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="3186e-663">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="3186e-663">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3186e-664">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online-Einschränkungen und -Einschränkungen überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="3186e-664">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3186e-665"><strong>Dropbox für Teams (Standard und Erweitert)</strong></span><span class="sxs-lookup"><span data-stu-id="3186e-665"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="3186e-666">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="3186e-666">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3186e-667">Dokumente</span><span class="sxs-lookup"><span data-stu-id="3186e-667">Documents</span></span> </li>
<li> <span data-ttu-id="3186e-668">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="3186e-668">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3186e-669">Ordnerberechtigungen auf Benutzerebene\*</span><span class="sxs-lookup"><span data-stu-id="3186e-669">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3186e-670">Ordnerberechtigungen auf Gruppenebene\*</span><span class="sxs-lookup"><span data-stu-id="3186e-670">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3186e-671">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="3186e-671">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3186e-672">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="3186e-672">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3186e-673">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-673">Created date</span></span> </li>
<li> <span data-ttu-id="3186e-674">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="3186e-674">Modified date</span></span> </li>
<li> <span data-ttu-id="3186e-675">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="3186e-675">Created by</span></span> </li>
<li> <span data-ttu-id="3186e-676">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="3186e-676">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3186e-677">Freigegebene Teamordner und -inhalte</span><span class="sxs-lookup"><span data-stu-id="3186e-677">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="3186e-678">Geteilte Inhalte, die im Besitz des Dropbox-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="3186e-678">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="3186e-679">\*Berechtigungen werden vom Microsoft 365-Gruppen- und/oder Microsoft #A0 betroffen.</span><span class="sxs-lookup"><span data-stu-id="3186e-679">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="3186e-680">Wenn es sich bei dem Ziel um einen Microsoft 365-Gruppen- oder Microsoft Teams-Kanal handelt, bestimmt die Gruppe oder der Kanal das endgültige Berechtigungsprofil für migrierte Dateien.</span><span class="sxs-lookup"><span data-stu-id="3186e-680">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="3186e-681">Es wird empfohlen, keine Berechtigungen für Dateien zu migrieren, die zu einem Microsoft 365-Gruppen- oder Microsoft Teams-Kanal migriert werden.</span><span class="sxs-lookup"><span data-stu-id="3186e-681">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span>
</td>
<td><ul>
<li> <span data-ttu-id="3186e-682">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="3186e-682">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3186e-683">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="3186e-683">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3186e-684">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="3186e-684">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3186e-685">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="3186e-685">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3186e-686">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="3186e-686">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3186e-687">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="3186e-687">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3186e-688">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="3186e-688">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3186e-689">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="3186e-689">Trashed items</span></span> </li>
<li> <span data-ttu-id="3186e-690">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="3186e-690">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3186e-691">Nicht gemountete Dropbox-Ordner</span><span class="sxs-lookup"><span data-stu-id="3186e-691">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="3186e-692">Gelöschte oder getrennte Benutzer</span><span class="sxs-lookup"><span data-stu-id="3186e-692">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="3186e-693">Dropbox Paper, Showcases und Spaces</span><span class="sxs-lookup"><span data-stu-id="3186e-693">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="3186e-694">Dropbox-Apps und Favoriten (Pins/Sterne)</span><span class="sxs-lookup"><span data-stu-id="3186e-694">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="3186e-695">Inhalte, die nicht im Besitz des migrierten Dropbox-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="3186e-695">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="3186e-696">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Dropbox-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="3186e-696">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="3186e-697">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="3186e-697">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3186e-698">Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online-Einschränkungen und -Einschränkungen überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="3186e-698">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="3186e-699">FastTrack-Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="3186e-699">FastTrack responsibilities</span></span>

<span data-ttu-id="3186e-700">Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="3186e-700">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="3186e-701">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="3186e-701">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="3186e-702">Ihre Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="3186e-702">Your responsibilities</span></span> 

<span data-ttu-id="3186e-703">Während des Migrationsprojekts führen Sie Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="3186e-703">You perform standard activities during the migration project.</span></span> <span data-ttu-id="3186e-704">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="3186e-704">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>
<span data-ttu-id="3186e-705">Sie führen außerdem die folgenden Aktivitäten aus, die speziell für Migrationen von Microsoft Teams und Microsoft 365-Gruppen verwendet werden:</span><span class="sxs-lookup"><span data-stu-id="3186e-705">You also perform the following activities, specific to Microsoft Teams and Microsoft 365 Groups migrations:</span></span> 

- <span data-ttu-id="3186e-706">Bereitstellen aller Microsoft Teams-Kanäle und Microsoft 365-Gruppen, die auf Ihre Migrationsereignisse ausgerichtet sind.</span><span class="sxs-lookup"><span data-stu-id="3186e-706">Provision all Microsoft Teams channels and Microsoft 365 Groups as targeted by your migration events.</span></span>

> [!NOTE]
><span data-ttu-id="3186e-707">FastTrack stellt keine Microsoft Teams-Kanäle oder Microsoft 365-Gruppen vorab zur Verfügung.</span><span class="sxs-lookup"><span data-stu-id="3186e-707">FastTrack doesn't pre-provision Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="3186e-708">FastTrack fügt keine Endbenutzer oder Gruppen zu Microsoft Teams-Kanälen oder Microsoft 365-Gruppen hinzu.</span><span class="sxs-lookup"><span data-stu-id="3186e-708">FastTrack doesn't add end users or groups to Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="3186e-709">Sie müssen Ihre Endbenutzer oder Gruppen zu allen Microsoft Teams-Kanälen und Microsoft 365-Gruppen hinzufügen, bevor Sie Daten zu diesen Zielen migrieren, damit diese Endbenutzer Zugriff auf diese neu migrierten Dokumente haben.</span><span class="sxs-lookup"><span data-stu-id="3186e-709">You must add your end users or groups to all Microsoft Teams channels and Microsoft 365 Groups before you migrate data into those destinations so those end users have access to those newly migrated documents</span></span>