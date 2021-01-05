---
title: Datenmigration
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/4/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Sie können die Migration von E-Mail- und Dateidaten in ihrer Quellumgebung auf Office 365 (Exchange Online, SharePoint Online und OneDrive for Business) mithilfe von FastTrack migrieren. Die Art der von uns bereitgestellten Unterstützung hängt von der Anzahl der Office 365-Lizenzen ab.
ms.openlocfilehash: ec7bc5cf9c25ef1e386c7fae42a5fd8e1716dee5
ms.sourcegitcommit: cf07b074931fd6877ba7e8938440dc7ebaf4ac69
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 01/04/2021
ms.locfileid: "49750042"
---
# <a name="data-migration"></a><span data-ttu-id="33251-104">Datenmigration</span><span class="sxs-lookup"><span data-stu-id="33251-104">Data Migration</span></span>

<span data-ttu-id="33251-105">Sie können die Migration von E-Mail- und Dateidaten in ihrer Quellumgebung auf Office 365 (Exchange Online, SharePoint Online und OneDrive for Business) mithilfe von FastTrack migrieren.</span><span class="sxs-lookup"><span data-stu-id="33251-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="33251-106">Die Art der von uns bereitgestellten Unterstützung hängt von der Anzahl der Office 365-Lizenzen ab:</span><span class="sxs-lookup"><span data-stu-id="33251-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="33251-107">**Für Office 365-Mandanten mit 150 bis 499-Lizenzen**: FastTrack bietet nur Migrationsanleitungen. Sie sind für die Durchführung der Datenmigration verantwortlich.</span><span class="sxs-lookup"><span data-stu-id="33251-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="33251-108">Wir führen Sie durch die Dokumentation, die Ihnen hilft, ﻿kostenlose Tools für die Durchführung einer Self-Service-Migration zu planen und zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="33251-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="33251-109">**Für Office 365-Mandanten mit 500 oder mehr Lizenzen**: FastTrack bietet Migrationsanleitungen und Datenmigrationsdienste.</span><span class="sxs-lookup"><span data-stu-id="33251-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="33251-110">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des Office 365-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Daten.</span><span class="sxs-lookup"><span data-stu-id="33251-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="33251-111">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="33251-111">You create and schedule your migration events.</span></span> <span data-ttu-id="33251-112">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="33251-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="33251-113">Wenn Sie einen kommerziellen Plan vor dem 1.9.2017 erworben oder verlängert haben, benötigen Sie nur 150 Lizenzen, um für Datenmigrationsdienste qualifiziert zu sein.</span><span class="sxs-lookup"><span data-stu-id="33251-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="33251-114">Bei Plänen für Bildungseinrichtungen sind nur Lehrpersonal und Mitarbeiter für Migrationsdienste berechtigt.</span><span class="sxs-lookup"><span data-stu-id="33251-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="33251-115">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="33251-115">Considerations</span></span>

  - <span data-ttu-id="33251-116">Ihre Quellumgebungen müssen bestimmte Erwartungen erfüllen, um Daten zu Office 365 zu migrieren.</span><span class="sxs-lookup"><span data-stu-id="33251-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="33251-117">Weitere Informationen zu den Erwartungen bezüglich der Quellumgebung für Exchange, SharePoint und OneDrive for Business finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="33251-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="33251-118">Für die Bereitstellung von Datenmigrationsdiensten benötigen wir einen geeigneten Zugriff auf Ihre Quellumgebungen und den Office 365-Mandanten.</span><span class="sxs-lookup"><span data-stu-id="33251-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="33251-119">Unsere Datenmigrationsdienste sind nicht für Daten vorgesehen, die besonderen rechtlichen oder behördlichen Vorschriften unterliegen.</span><span class="sxs-lookup"><span data-stu-id="33251-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="33251-120">Wenn wir Ihre Daten migrieren, können sie an einen beliebigen Ort, an dem wir über Einrichtungen verfügen, übertragen, dort gespeichert und verarbeitet werden (sofern nicht anderweitig für Ihr FastTrack-Migrationsprojekt angegeben).</span><span class="sxs-lookup"><span data-stu-id="33251-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="33251-121">Wir übernehmen keine Garantie für die Geschwindigkeit der E-Mail- oder Dateimigration.</span><span class="sxs-lookup"><span data-stu-id="33251-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="33251-122">Unvorhergesehene Probleme (wie unlesbare oder fehlerhafte Elemente in der Quellumgebung) verhindern möglicherweise, dass einige ihrer Datenelemente migriert werden können.</span><span class="sxs-lookup"><span data-stu-id="33251-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="33251-123">Externe Faktoren, die außerhalb unserer Kontrolle stehen (z. B. Änderungen an den Programmierschnittstellen von Drittanbietern) können zu Änderungen, Verzögerungen oder der Sperrung unserer Datenmigrationsdienste führen.</span><span class="sxs-lookup"><span data-stu-id="33251-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="33251-124">Verfügbarkeit des Migrationsdiensts</span><span class="sxs-lookup"><span data-stu-id="33251-124">Migration service availability</span></span>

  - <span data-ttu-id="33251-125">**Für kommerzielle Kunden und britische Behörden:** Wir stellen Datenmigrationsdienste rund um die Uhr an sieben (7) Tagen pro Woche bereit.</span><span class="sxs-lookup"><span data-stu-id="33251-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="33251-126">**Für Kunden von US-amerikanischen Behörden/Verteidigungsministerium:** Wir stellen Datenmigrationsdienste rund um die Uhr an fünf (5) Werktagen pro Woche bereit.</span><span class="sxs-lookup"><span data-stu-id="33251-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="33251-127">Migration zu Exchange Online</span><span class="sxs-lookup"><span data-stu-id="33251-127">Migration to Exchange Online</span></span>

<span data-ttu-id="33251-128">Wenn Sie sich für die Migration Ihrer E-Mails zu Exchange Online mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit.</span><span class="sxs-lookup"><span data-stu-id="33251-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="33251-129">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des Exchange Online-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Postfächer.</span><span class="sxs-lookup"><span data-stu-id="33251-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="33251-130">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="33251-130">You create and schedule your migration events.</span></span> <span data-ttu-id="33251-131">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="33251-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="33251-132">Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass E-Mail-Nachrichten von entsprechend geplanten und berechtigten Quellpostfächern ihrer Quellumgebungen zu Exchange Online migriert wurden.</span><span class="sxs-lookup"><span data-stu-id="33251-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="33251-133">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="33251-133">Considerations</span></span>

  - <span data-ttu-id="33251-134">Bevor Sie die Migration durchführen können, müssen Sie den FastTrack-Onboarding-Vorgang für Exchange Online durchführen.</span><span class="sxs-lookup"><span data-stu-id="33251-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="33251-135">Wenn Sie das Onboarding selbst durchgeführt haben, müssen Sie die erforderlichen Überprüfungen und Voraussetzungen erfüllen.</span><span class="sxs-lookup"><span data-stu-id="33251-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="33251-136">Ausführliche Informationen finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="33251-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="33251-137">FastTrack migriert nur zu aktiven Office 365-Postfächern.</span><span class="sxs-lookup"><span data-stu-id="33251-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="33251-138">Sie müssen bestimmte Anforderungen erfüllen, wenn Sie von einer lokalen Exchange-Umgebung migrieren möchten.</span><span class="sxs-lookup"><span data-stu-id="33251-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="33251-139">Weitere Informationen finden Sie unter [Voraussetzungen für die Hybridbereitstellung](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="33251-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="33251-140">Sämtliche Quellumgebungen müssen über die neuesten Service Packs (SP) verfügen und auf der Rollup (RU)-/Kumulativen Update (KU)-Ebene für das entsprechende Produkt in der Quellumgebung vorhanden sein.</span><span class="sxs-lookup"><span data-stu-id="33251-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="33251-141">Verteilerlisten (*MailEnabledGroup*-Objekte) und externe Kontakte (*MailEnabledContact*-Objekte) im lokalen Active Directory befinden, sind nicht Bestandteil einer Postfachdatenmigration.</span><span class="sxs-lookup"><span data-stu-id="33251-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="33251-142">Sie können Sie jedoch mithilfe von Azure Active Directory (Azure AD) Connect synchronisieren.</span><span class="sxs-lookup"><span data-stu-id="33251-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="33251-143">Quellumgebungen</span><span class="sxs-lookup"><span data-stu-id="33251-143">Source environments</span></span>

<span data-ttu-id="33251-144">Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:</span><span class="sxs-lookup"><span data-stu-id="33251-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="33251-145">aus einer einzelnen oder aus mehreren Active Directory-Gesamtstrukturen mit einer oder mehreren Exchange-Organisationen (jedes Exchange-E-Mail-System muss Exchange 2010 oder höher sein).</span><span class="sxs-lookup"><span data-stu-id="33251-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="33251-146">aus einer einzelnen IMAP-fähigen E-Mail-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="33251-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="33251-147">aus einer G Suite-Umgebung (nur Gmail, Kontakte und Kalender).</span><span class="sxs-lookup"><span data-stu-id="33251-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="33251-148">Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:</span><span class="sxs-lookup"><span data-stu-id="33251-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="33251-149"><strong>Quellumgebung</strong></span><span class="sxs-lookup"><span data-stu-id="33251-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="33251-150"><strong>Migrationstyp</strong></span><span class="sxs-lookup"><span data-stu-id="33251-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="33251-151"><strong>Was wird migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="33251-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="33251-152"><strong>Was wird nicht migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="33251-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="33251-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="33251-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="33251-154">
<strong>Hinweis:</strong> Informationen zu lokalen Exchange-Abhängigkeiten finden Sie unter <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Voraussetzungen für die Hybrid Bereitstellung</span></a>.</span><span class="sxs-lookup"><span data-stu-id="33251-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="33251-155">Migration mit Hybridbereitstellung</span><span class="sxs-lookup"><span data-stu-id="33251-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="33251-156">E-Mails</span><span class="sxs-lookup"><span data-stu-id="33251-156">Emails</span></span></li>
<li><span data-ttu-id="33251-157">Postfachregeln</span><span class="sxs-lookup"><span data-stu-id="33251-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="33251-158">Stellvertretungen</span><span class="sxs-lookup"><span data-stu-id="33251-158">Delegates</span></span></li>
<li><span data-ttu-id="33251-159">Postfachkontakte</span><span class="sxs-lookup"><span data-stu-id="33251-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="33251-160">Kalender</span><span class="sxs-lookup"><span data-stu-id="33251-160">Calendar</span></span> </li>
<li> <span data-ttu-id="33251-161">Aufgaben</span><span class="sxs-lookup"><span data-stu-id="33251-161">Tasks</span></span> </li>
<li> <span data-ttu-id="33251-162">E-Mails mit Rechteverwaltung</span><span class="sxs-lookup"><span data-stu-id="33251-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="33251-163">Verschlüsselte E-Mails</span><span class="sxs-lookup"><span data-stu-id="33251-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="33251-164">Signaturen</span><span class="sxs-lookup"><span data-stu-id="33251-164">Signatures</span></span> </li>
<li> <span data-ttu-id="33251-165">Persönliches Archiv, das mit dem Benutzerpostfach migriert wird</span><span class="sxs-lookup"><span data-stu-id="33251-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="33251-166">Wiederherstellbare Elemente</span><span class="sxs-lookup"><span data-stu-id="33251-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="33251-167">Öffentliche Ordner</span><span class="sxs-lookup"><span data-stu-id="33251-167">Public folders</span></span> </li>
<li> <span data-ttu-id="33251-168">E-Mail, die die zulässige Nachrichtengröße überschreitet.</span><span class="sxs-lookup"><span data-stu-id="33251-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="33251-169">Journalarchiv oder eine beliebige Archivlösung von Drittanbietern</span><span class="sxs-lookup"><span data-stu-id="33251-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="33251-170">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="33251-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="33251-171">Archivdaten aus PST-Dateien</span><span class="sxs-lookup"><span data-stu-id="33251-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="33251-172">Beschädigte Elemente</span><span class="sxs-lookup"><span data-stu-id="33251-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="33251-173">Inaktive Postfächer</span><span class="sxs-lookup"><span data-stu-id="33251-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="33251-174"><strong>G Suite-Umgebung (nur Gmail, Kontakte und Kalender)</strong></span><span class="sxs-lookup"><span data-stu-id="33251-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="33251-175">
<strong>Hinweis:</strong> Ihre g Suite-Umgebung muss die unter <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Ausführen einer g Suite-Migration</a>beschriebenen Voraussetzungen erfüllen.</span><span class="sxs-lookup"><span data-stu-id="33251-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="33251-176">Übernahmemigration oder mehrstufige Migration</span><span class="sxs-lookup"><span data-stu-id="33251-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="33251-177">E-Mails</span><span class="sxs-lookup"><span data-stu-id="33251-177">Emails</span></span> </li>
<li> <span data-ttu-id="33251-178">Postfachkontakte (es werden maximal drei E-Mail-Adressen pro Kontakt migriert)</span><span class="sxs-lookup"><span data-stu-id="33251-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="33251-179">Kalender</span><span class="sxs-lookup"><span data-stu-id="33251-179">Calendar</span></span> </li>
<li> <span data-ttu-id="33251-180">Bezeichnungen</span><span class="sxs-lookup"><span data-stu-id="33251-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="33251-181">Regeln</span><span class="sxs-lookup"><span data-stu-id="33251-181">Rules</span></span> </li>
<li> <span data-ttu-id="33251-182">Stellvertretungen</span><span class="sxs-lookup"><span data-stu-id="33251-182">Delegates</span></span> </li>
<li> <span data-ttu-id="33251-183">Signaturen</span><span class="sxs-lookup"><span data-stu-id="33251-183">Signatures</span></span> </li>
<li> <span data-ttu-id="33251-184">Aufgaben</span><span class="sxs-lookup"><span data-stu-id="33251-184">Tasks</span></span> </li>
<li> <span data-ttu-id="33251-185">E-Mails oder Anhänge, die die zulässige Nachrichtengröße überschreiten</span><span class="sxs-lookup"><span data-stu-id="33251-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="33251-186">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="33251-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="33251-187">Archivdaten aus PST-Dateien oder einer Drittanbieter-Archivlösung (z. B. Google Vault)</span><span class="sxs-lookup"><span data-stu-id="33251-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="33251-188">E-Mails mit Rechteverwaltung oder Verschlüsselung</span><span class="sxs-lookup"><span data-stu-id="33251-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="33251-189">Beschädigte Elemente</span><span class="sxs-lookup"><span data-stu-id="33251-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="33251-190">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="33251-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="33251-191">Google-Gruppen</span><span class="sxs-lookup"><span data-stu-id="33251-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="33251-192">Ressourcenpostfächer</span><span class="sxs-lookup"><span data-stu-id="33251-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="33251-193">Inaktive Postfächer</span><span class="sxs-lookup"><span data-stu-id="33251-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="33251-194">Urlaubseinstellungen und Einstellungen für automatische Antworten</span><span class="sxs-lookup"><span data-stu-id="33251-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="33251-195">Freigegebene Kalender, Cloudanlagen, Google Hangout-Links und Ereignisfarben</span><span class="sxs-lookup"><span data-stu-id="33251-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="33251-196">\*\*Hangout-Unterhaltungen, die als Beschriftungen gespeichert wurden, werden migriert.</span><span class="sxs-lookup"><span data-stu-id="33251-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="33251-197"><strong>IMAP4-Quelle (wie Domino, GroupWise oder Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="33251-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="33251-198">Migration mit systemeigenen IMAP4-Tools</span><span class="sxs-lookup"><span data-stu-id="33251-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="33251-199">E-Mails</span><span class="sxs-lookup"><span data-stu-id="33251-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="33251-200">Regeln</span><span class="sxs-lookup"><span data-stu-id="33251-200">Rules</span></span> </li>
<li> <span data-ttu-id="33251-201">Stellvertretungen</span><span class="sxs-lookup"><span data-stu-id="33251-201">Delegates</span></span> </li>
<li> <span data-ttu-id="33251-202">Verteilerlisten</span><span class="sxs-lookup"><span data-stu-id="33251-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="33251-203">Externe Kontakte</span><span class="sxs-lookup"><span data-stu-id="33251-203">External contacts</span></span> </li>
<li> <span data-ttu-id="33251-204">E-Mail-aktivierte Benutzer</span><span class="sxs-lookup"><span data-stu-id="33251-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="33251-205">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="33251-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="33251-206">Postfachkontakte</span><span class="sxs-lookup"><span data-stu-id="33251-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="33251-207">Kalender</span><span class="sxs-lookup"><span data-stu-id="33251-207">Calendar</span></span> </li>
<li> <span data-ttu-id="33251-208">Signaturen</span><span class="sxs-lookup"><span data-stu-id="33251-208">Signatures</span></span> </li>
<li> <span data-ttu-id="33251-209">Aufgaben</span><span class="sxs-lookup"><span data-stu-id="33251-209">Tasks</span></span> </li>
<li> <span data-ttu-id="33251-210">E-Mails, die die zulässige Nachrichtengröße überschreiten</span><span class="sxs-lookup"><span data-stu-id="33251-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="33251-211">Archivdaten</span><span class="sxs-lookup"><span data-stu-id="33251-211">Archive data</span></span> </li>
<li> <span data-ttu-id="33251-212">Verschlüsselte E-Mail-Nachrichten</span><span class="sxs-lookup"><span data-stu-id="33251-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="33251-213">Beschädigte Elemente</span><span class="sxs-lookup"><span data-stu-id="33251-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="33251-214">Inaktive Postfächer</span><span class="sxs-lookup"><span data-stu-id="33251-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="33251-215">FastTrack-Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="33251-215">FastTrack responsibilities</span></span>

<span data-ttu-id="33251-216">Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="33251-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="33251-217">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="33251-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="33251-218">Unsere FastTrack-Spezialisten führen außerdem die folgenden Aktivitäten speziell für Exchange-Migrationen durch:</span><span class="sxs-lookup"><span data-stu-id="33251-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="33251-219">Bereitstellen von Anleitungen, die Ihnen dabei helfen, die Koexistenz von SMTP-E-Mail-Routing zwischen Ihrer Quellumgebung und Exchange Online zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="33251-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="33251-220">Ihre Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="33251-220">Your responsibilities</span></span>

<span data-ttu-id="33251-221">Während des Migrationsprojekts führen Sie Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="33251-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="33251-222">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="33251-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="33251-223">Sie führen außerdem die folgenden Aktivitäten speziell für Exchange-Migrationen aus:</span><span class="sxs-lookup"><span data-stu-id="33251-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="33251-224">Durchführen des FastTrack-Onboarding-Vorgangs für Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="33251-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="33251-225">Wenn Sie das Onboarding selbst durchgeführt haben, müssen Sie die erforderlichen Überprüfungen und Voraussetzungen erfüllen.</span><span class="sxs-lookup"><span data-stu-id="33251-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="33251-226">Ausführliche Informationen finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="33251-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="33251-227">Installieren der entsprechenden Clientsoftwareebene gemäß den Office 365-Richtlinien.</span><span class="sxs-lookup"><span data-stu-id="33251-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="33251-228">Details finden Sie unter [Der moderne Arbeitsplatz](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="33251-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="33251-229">Erfüllen bestimmter Anforderungen, wenn Sie von einer lokalen Exchange-Umgebung migrieren möchten.</span><span class="sxs-lookup"><span data-stu-id="33251-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="33251-230">Weitere Informationen finden Sie unter [Voraussetzungen für die Hybridbereitstellung](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="33251-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="33251-231">Sicherstellen, dass jede Quellumgebung über das neueste Service Pack (SP) und Rollup (RU)/Cumulative Update (CU) verfügt, sofern zutreffend.</span><span class="sxs-lookup"><span data-stu-id="33251-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="33251-232">Konfigurieren und Validieren der Koexistenz von SMTP-E-Mail-Routing zwischen Ihrer Quellumgebung und Exchange Online, sofern zutreffend.</span><span class="sxs-lookup"><span data-stu-id="33251-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="33251-233">Sicherstellen, dass die Größe des Quellpostfachs das Zielpostfachkontingent nicht überschreitet.</span><span class="sxs-lookup"><span data-stu-id="33251-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="33251-234">Abhängig von der Quellplattform müssen Sie möglicherweise Ihre Quelldaten auf 85 % des Zielpostfachkontingents beschränken.</span><span class="sxs-lookup"><span data-stu-id="33251-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="33251-235">Ggf. Migrieren clientseitiger Daten.</span><span class="sxs-lookup"><span data-stu-id="33251-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="33251-236">Dies umfasst unter anderem lokale Adressbücher, Daten in lokalen PST-Dateien, Outlook-Regeln und lokale Outlook-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="33251-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="33251-237">Unterstützen Ihrer Endbenutzer bei der Behebung von Problemen bei der clientbasierten Migration.</span><span class="sxs-lookup"><span data-stu-id="33251-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="33251-238">Migration zu SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="33251-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="33251-239">Wenn Sie sich für die Migration Ihrer Dateien zu SharePoint Online mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit.</span><span class="sxs-lookup"><span data-stu-id="33251-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="33251-240">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des SharePoint Online-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Dateien.</span><span class="sxs-lookup"><span data-stu-id="33251-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="33251-241">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="33251-241">You create and schedule your migration events.</span></span> <span data-ttu-id="33251-242">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="33251-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="33251-243">Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass Dateien von entsprechend geplanten und berechtigten Quellen ihrer Quellumgebungen zu SharePoint Online migriert wurden.</span><span class="sxs-lookup"><span data-stu-id="33251-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="33251-244">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="33251-244">Considerations</span></span>

  - <span data-ttu-id="33251-245">Alle Migrationen unterliegen SharePoint Online-Kontingenten.</span><span class="sxs-lookup"><span data-stu-id="33251-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="33251-246">Weitere Informationen finden Sie unter [<span class="underline">SharePoint Online und OneDrive for Business: Softwarelimits und -beschränkungen</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="33251-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="33251-247">Der Gesamtbetrag sollte auf 75 Prozent des SharePoint Online-Gesamtspeicherkontingents, für das Sie berechtigt sind, beschränkt werden (einschließlich den zusätzlichen Speicher, den Sie möglicherweise separat gekauft haben).</span><span class="sxs-lookup"><span data-stu-id="33251-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="33251-248">Detail der Quellumgebung</span><span class="sxs-lookup"><span data-stu-id="33251-248">Source environment details</span></span>

<span data-ttu-id="33251-249">Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:</span><span class="sxs-lookup"><span data-stu-id="33251-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="33251-250">Dateifreigaben (SMB [Server Message Block]-Dateifreigaben auf Geräten mit Unterstützung für SMB 2.0 und höher)</span><span class="sxs-lookup"><span data-stu-id="33251-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="33251-251">Eine einzelne G Suite-Umgebung (nur Google Drive).</span><span class="sxs-lookup"><span data-stu-id="33251-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="33251-252">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="33251-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="33251-253">Dropbox für Teams (Standard und Erweitert).</span><span class="sxs-lookup"><span data-stu-id="33251-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="33251-254">Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:</span><span class="sxs-lookup"><span data-stu-id="33251-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="33251-255"><strong>Quellumgebung</strong></span><span class="sxs-lookup"><span data-stu-id="33251-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="33251-256"><strong>Migrationstyp</strong></span><span class="sxs-lookup"><span data-stu-id="33251-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="33251-257"><strong>Was wird migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="33251-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="33251-258"><strong>Was wird nicht migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="33251-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="33251-259"><strong>Alle Dateifreigabegeräte mit Unterstützung für SMB 2.0 und höher</strong></span><span class="sxs-lookup"><span data-stu-id="33251-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="33251-260">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="33251-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="33251-261">Dokumente</span><span class="sxs-lookup"><span data-stu-id="33251-261">Documents</span></span> </li>
<li> <span data-ttu-id="33251-262">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="33251-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="33251-263">Datei- und Ordnerberechtigungen auf Benutzerebene\*</span><span class="sxs-lookup"><span data-stu-id="33251-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="33251-264">Datei- und Ordnerberechtigungen auf Gruppenebene\*</span><span class="sxs-lookup"><span data-stu-id="33251-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="33251-265">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="33251-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="33251-266">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="33251-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="33251-267">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="33251-267">Created date</span></span> </li>
<li> <span data-ttu-id="33251-268">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="33251-268">Modified date</span></span> </li>
<li> <span data-ttu-id="33251-269">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="33251-269">Created by</span></span> </li>
<li> <span data-ttu-id="33251-270">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="33251-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="33251-271">\* Setzt die Konfiguration der Verzeichnissynchronisierung voraus.</span><span class="sxs-lookup"><span data-stu-id="33251-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="33251-272">Es werden nur NTFS-Berechtigungen migriert, die für den Windows-Datei-Explorer verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="33251-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="33251-273">Berechtigungen, die direkt auf Dateifreigabegeräten verwaltet werden, werden nicht migriert.</span><span class="sxs-lookup"><span data-stu-id="33251-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="33251-274">Wenn Daten auf einem SMB 2.0-Gerät gespeichert werden, werden die NTFS-äquivalenten Berechtigungen, die vom SMB-Protokoll verfügbar gemacht werden, migriert.</span><span class="sxs-lookup"><span data-stu-id="33251-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="33251-275">Aufgezeichnete Eigentümerschaft und frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="33251-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="33251-276">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="33251-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="33251-277">Frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="33251-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="33251-278">Windows-Datei-/-Ordnerattribute (z. B. „Schreibgeschützt“ und „Ausgeblendet“) </span><span class="sxs-lookup"><span data-stu-id="33251-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="33251-279">Nicht-Windows-NTFS-Dateisystem (New Technology File System) und erweiterte NTFS-Berechtigungen sowie besondere Einstellungen:</span><span class="sxs-lookup"><span data-stu-id="33251-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="33251-280">Explizite Verweigerungsberechtigungen (werden nach der Migration entfernt, Inhalte unterliegen parallelen Berechtigungen oder Berechtigungen im übergeordneten Ordner).</span><span class="sxs-lookup"><span data-stu-id="33251-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="33251-281">Konfiguration der NTFS-Überwachung</span><span class="sxs-lookup"><span data-stu-id="33251-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="33251-282">Zusätzliche Dateimetadaten von der Dateiklassifizierungsinfrastruktur (File Classification Infrastructure, FCI)</span><span class="sxs-lookup"><span data-stu-id="33251-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="33251-283">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="33251-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="33251-284">Ausgeblendete Freigaben</span><span class="sxs-lookup"><span data-stu-id="33251-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="33251-285">Freigabe (z. B. gewährte Berechtigungen auf Freigabeebene)</span><span class="sxs-lookup"><span data-stu-id="33251-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="33251-286">Dateien oder Ordner, die die aktuellen <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online Einschränkungen und-Einschränkungen</span> überschreiten</a> </span><span class="sxs-lookup"><span data-stu-id="33251-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="33251-287"><strong>Einzelne G Suite-Umgebung (nur Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="33251-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="33251-288">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="33251-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="33251-289">Google Docs, Google Tabellen und Google Präsentationen (Dateien werden in das entsprechende Office-Format konvertiert), einschließlich derjenigen über 10 MB</span><span class="sxs-lookup"><span data-stu-id="33251-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="33251-290">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="33251-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="33251-291">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="33251-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="33251-292">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="33251-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="33251-293">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="33251-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="33251-294">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="33251-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="33251-295">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="33251-295">Created date</span></span> </li>
<li> <span data-ttu-id="33251-296">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="33251-296">Modified date</span></span> </li>
<li> <span data-ttu-id="33251-297">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="33251-297">Created by</span></span> </li>
<li> <span data-ttu-id="33251-298">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="33251-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="33251-299">Freigegebene Laufwerke (Ordner und Dateien)</span><span class="sxs-lookup"><span data-stu-id="33251-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="33251-300">Geteilte Inhalte, die im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="33251-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="33251-301">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="33251-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="33251-302">Beschreibungen von Dateien und Ordnern, Ordnerfarben</span><span class="sxs-lookup"><span data-stu-id="33251-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="33251-303">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="33251-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="33251-304">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="33251-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="33251-305">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="33251-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="33251-306">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="33251-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="33251-307">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="33251-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="33251-308">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="33251-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="33251-309">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="33251-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="33251-310">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="33251-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="33251-311">Google Fotos, Google Formulare, Google Maps und andere verbundene Apps</span><span class="sxs-lookup"><span data-stu-id="33251-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="33251-312">Google Zeichnungen</span><span class="sxs-lookup"><span data-stu-id="33251-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="33251-313">Freigegebene Inhalte außerhalb Ihrer Organisation</span><span class="sxs-lookup"><span data-stu-id="33251-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="33251-314">Inhalte, die nicht im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="33251-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="33251-315">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Google Drive-Administratorberichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="33251-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="33251-316">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="33251-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="33251-317">Mitgliedschaftsberechtigungen für freigegebene Laufwerke (<strong>Hinweis</strong>: Verwenden Sie die Google Drive-Administratorberichte, um die Mitgliedschaften für freigegebene Laufwerke zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="33251-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="33251-318">Weisen Sie die Endbenutzer an, diese Mitgliedschaftseinstellungen auf dem Ziel vor der Migration zu konfigurieren.)</span><span class="sxs-lookup"><span data-stu-id="33251-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="33251-319">Dateien, die als eingeschränkt oder nicht kopierbar gekennzeichnet sind</span><span class="sxs-lookup"><span data-stu-id="33251-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="33251-320">Dateien oder Ordner, die die aktuellen <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online Einschränkungen und-Einschränkungen</span> überschreiten</a> </span><span class="sxs-lookup"><span data-stu-id="33251-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="33251-321"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="33251-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="33251-322">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="33251-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="33251-323">Dokumente</span><span class="sxs-lookup"><span data-stu-id="33251-323">Documents</span></span> </li>
<li> <span data-ttu-id="33251-324">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="33251-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="33251-325">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="33251-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="33251-326">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="33251-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="33251-327">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="33251-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="33251-328">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="33251-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="33251-329">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="33251-329">Created date</span></span> </li>
<li> <span data-ttu-id="33251-330">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="33251-330">Modified date</span></span> </li>
<li> <span data-ttu-id="33251-331">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="33251-331">Created by</span></span> </li>
<li> <span data-ttu-id="33251-332">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="33251-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="33251-333">Geteilte Inhalte, die im Besitz des Box-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="33251-333">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="33251-334">Feld Notizen (in das Word-Dokumentformat konvertiert)</span><span class="sxs-lookup"><span data-stu-id="33251-334">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="33251-335">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="33251-335">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="33251-336">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="33251-336">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="33251-337">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="33251-337">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="33251-338">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="33251-338">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="33251-339">Box-Tags und erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="33251-339">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="33251-340">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="33251-340">File lock attributes</span></span> </li>
<li> <span data-ttu-id="33251-341">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="33251-341">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="33251-342">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="33251-342">Trashed items</span></span> </li>
<li> <span data-ttu-id="33251-343">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="33251-343">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="33251-344">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="33251-344">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="33251-345">Box-Apps, Lesezeichen, Favoriten und Workflows</span><span class="sxs-lookup"><span data-stu-id="33251-345">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="33251-346">Inhalte, die nicht im Besitz des migrierten Box-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="33251-346">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="33251-347">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Box-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="33251-347">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="33251-348">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="33251-348">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="33251-349">Dateien oder Ordner, die die aktuellen <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online Einschränkungen und-Einschränkungen</span> überschreiten</a> </span><span class="sxs-lookup"><span data-stu-id="33251-349">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="33251-350"><strong>Dropbox für Teams (Standard und Erweitert)</strong></span><span class="sxs-lookup"><span data-stu-id="33251-350"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="33251-351">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="33251-351">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="33251-352">Dokumente</span><span class="sxs-lookup"><span data-stu-id="33251-352">Documents</span></span> </li>
<li> <span data-ttu-id="33251-353">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="33251-353">File and folder structure</span></span> </li>
<li> <span data-ttu-id="33251-354">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="33251-354">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="33251-355">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="33251-355">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="33251-356">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="33251-356">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="33251-357">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="33251-357">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="33251-358">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="33251-358">Created date</span></span> </li>
<li> <span data-ttu-id="33251-359">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="33251-359">Modified date</span></span> </li>
<li> <span data-ttu-id="33251-360">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="33251-360">Created by</span></span> </li>
<li> <span data-ttu-id="33251-361">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="33251-361">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="33251-362">Freigegebene Teamordner und -inhalte</span><span class="sxs-lookup"><span data-stu-id="33251-362">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="33251-363">Geteilte Inhalte, die im Besitz des Dropbox-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="33251-363">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="33251-364">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="33251-364">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="33251-365">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="33251-365">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="33251-366">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="33251-366">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="33251-367">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="33251-367">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="33251-368">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="33251-368">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="33251-369">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="33251-369">File lock attributes</span></span> </li>
<li> <span data-ttu-id="33251-370">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="33251-370">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="33251-371">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="33251-371">Trashed items</span></span> </li>
<li> <span data-ttu-id="33251-372">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="33251-372">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="33251-373">Nicht gemountete Dropbox-Ordner</span><span class="sxs-lookup"><span data-stu-id="33251-373">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="33251-374">Gelöschte oder getrennte Benutzer</span><span class="sxs-lookup"><span data-stu-id="33251-374">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="33251-375">Dropbox Paper, Showcases und Spaces</span><span class="sxs-lookup"><span data-stu-id="33251-375">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="33251-376">Dropbox-Apps und Favoriten (Pins/Sterne)</span><span class="sxs-lookup"><span data-stu-id="33251-376">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="33251-377">Inhalte, die nicht im Besitz des migrierten Dropbox-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="33251-377">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="33251-378">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Dropbox-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="33251-378">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="33251-379">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="33251-379">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="33251-380">Dateien oder Ordner, die die aktuellen <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online Einschränkungen und-Einschränkungen</span> überschreiten</a> </span><span class="sxs-lookup"><span data-stu-id="33251-380">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="33251-381">FastTrack-Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="33251-381">FastTrack responsibilities</span></span>

<span data-ttu-id="33251-382">Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="33251-382">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="33251-383">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="33251-383">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="33251-384">Ihre Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="33251-384">Your responsibilities</span></span>

<span data-ttu-id="33251-385">Während des Migrationsprojekts führen Sie Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="33251-385">You perform standard activities during the migration project.</span></span> <span data-ttu-id="33251-386">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="33251-386">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="33251-387">Sie führen außerdem die folgenden Aktivitäten speziell für SharePoint Online-Migrationen aus:</span><span class="sxs-lookup"><span data-stu-id="33251-387">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="33251-388">Bereitstellen aller SharePoint-Teamwebsites, die für Ihre Migrationsereignisse vorgesehen sind.</span><span class="sxs-lookup"><span data-stu-id="33251-388">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="33251-389">Migration zu OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="33251-389">Migration to OneDrive for Business</span></span>

<span data-ttu-id="33251-390">Wenn Sie sich für die Migration Ihrer Dateien zu OneDrive for Business mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit.</span><span class="sxs-lookup"><span data-stu-id="33251-390">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="33251-391">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des OneDrive for Business-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Dateien.</span><span class="sxs-lookup"><span data-stu-id="33251-391">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="33251-392">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="33251-392">You create and schedule your migration events.</span></span> <span data-ttu-id="33251-393">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="33251-393">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="33251-394">Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass Dateien von entsprechend geplanten und berechtigten Quellen ihrer Quellumgebungen zu OneDrive for Business migriert wurden.</span><span class="sxs-lookup"><span data-stu-id="33251-394">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="33251-395">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="33251-395">Considerations</span></span>

  - <span data-ttu-id="33251-396">Alle Migrationen unterliegen den OneDrive for Business-Kontingenten.</span><span class="sxs-lookup"><span data-stu-id="33251-396">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="33251-397">Weitere Informationen finden Sie unter [<span class="underline">SharePoint Online und OneDrive for Business: Softwarelimits und -beschränkungen</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="33251-397">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="33251-398">Der Gesamtbetrag sollte auf 75 Prozent der Daten des SharePoint Online-Gesamtspeicherkontingents, für das Sie berechtigt sind, beschränkt werden (einschließlich den zusätzlichen Speicher, den Sie möglicherweise separat gekauft haben).</span><span class="sxs-lookup"><span data-stu-id="33251-398">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="33251-399">FastTrack migriert nur zu aktiven OneDrive for Business-Laufwerken.</span><span class="sxs-lookup"><span data-stu-id="33251-399">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="33251-400">Detail der Quellumgebung</span><span class="sxs-lookup"><span data-stu-id="33251-400">Source environment details</span></span>

<span data-ttu-id="33251-401">Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:</span><span class="sxs-lookup"><span data-stu-id="33251-401">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="33251-402">Dateifreigaben (SMB-Dateifreigaben auf Geräten mit Unterstützung für SMB 2.0 und höher)</span><span class="sxs-lookup"><span data-stu-id="33251-402">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="33251-403">Einzelne G Suite-Umgebung (nur Google Drive).</span><span class="sxs-lookup"><span data-stu-id="33251-403">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="33251-404">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="33251-404">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="33251-405">Dropbox für Teams (Standard und Erweitert).</span><span class="sxs-lookup"><span data-stu-id="33251-405">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="33251-406">Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:</span><span class="sxs-lookup"><span data-stu-id="33251-406">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="33251-407"><strong>Quellumgebung</strong></span><span class="sxs-lookup"><span data-stu-id="33251-407"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="33251-408"><strong>Migrationstyp</strong></span><span class="sxs-lookup"><span data-stu-id="33251-408"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="33251-409"><strong>Was wird migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="33251-409"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="33251-410"><strong>Was wird nicht migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="33251-410"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="33251-411"><strong>Alle Dateifreigabegeräte mit Unterstützung für SMB 2.0 und höher</strong></span><span class="sxs-lookup"><span data-stu-id="33251-411"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="33251-412">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="33251-412">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="33251-413">Dokumente</span><span class="sxs-lookup"><span data-stu-id="33251-413">Documents</span></span> </li>
<li> <span data-ttu-id="33251-414">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="33251-414">File and folder structure</span></span> </li>
<li> <span data-ttu-id="33251-415">Datei- und Ordnerberechtigungen auf Benutzerebene\*</span><span class="sxs-lookup"><span data-stu-id="33251-415">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="33251-416">Datei- und Ordnerberechtigungen auf Gruppenebene\*</span><span class="sxs-lookup"><span data-stu-id="33251-416">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="33251-417">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="33251-417">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="33251-418">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="33251-418">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="33251-419">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="33251-419">Created date</span></span> </li>
<li> <span data-ttu-id="33251-420">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="33251-420">Modified date</span></span> </li>
<li> <span data-ttu-id="33251-421">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="33251-421">Created by</span></span> </li>
<li> <span data-ttu-id="33251-422">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="33251-422">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="33251-423">\* Setzt die Konfiguration der Verzeichnissynchronisierung voraus.</span><span class="sxs-lookup"><span data-stu-id="33251-423">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="33251-424">Es werden nur NTFS-Berechtigungen migriert, die für den Windows-Datei-Explorer verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="33251-424">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="33251-425">Berechtigungen, die direkt auf Dateifreigabegeräten verwaltet werden, werden nicht migriert.</span><span class="sxs-lookup"><span data-stu-id="33251-425">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="33251-426">Wenn Daten auf einem SMB 2.0-Gerät gespeichert werden, werden die NTFS-äquivalenten Berechtigungen, die vom SMB-Protokoll verfügbar gemacht werden, migriert.</span><span class="sxs-lookup"><span data-stu-id="33251-426">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="33251-427">Aufgezeichnete Eigentümerschaft und frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="33251-427">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="33251-428">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="33251-428">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="33251-429">Frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="33251-429">Previous versions</span></span> </li>
<li> <span data-ttu-id="33251-430">Windows-Datei-/-Ordnerattribute (z. B. „Schreibgeschützt“ und „Ausgeblendet“) </span><span class="sxs-lookup"><span data-stu-id="33251-430">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="33251-431">Nicht-Windows-NTFS-Dateisystem (New Technology File System) und erweiterte NTFS-Berechtigungen sowie besondere Einstellungen:</span><span class="sxs-lookup"><span data-stu-id="33251-431">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="33251-432">Explizite Verweigerungsberechtigungen (werden nach der Migration entfernt, Inhalte unterliegen parallelen Berechtigungen oder Berechtigungen im übergeordneten Ordner).</span><span class="sxs-lookup"><span data-stu-id="33251-432">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="33251-433">Konfiguration der NTFS-Überwachung</span><span class="sxs-lookup"><span data-stu-id="33251-433">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="33251-434">Zusätzliche Dateimetadaten von der Dateiklassifizierungsinfrastruktur (File Classification Infrastructure, FCI)</span><span class="sxs-lookup"><span data-stu-id="33251-434">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="33251-435">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="33251-435">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="33251-436">Ausgeblendete Freigaben</span><span class="sxs-lookup"><span data-stu-id="33251-436">Hidden shares</span></span> </li>
<li> <span data-ttu-id="33251-437">Freigabe (z. B. gewährte Berechtigungen auf Freigabeebene)</span><span class="sxs-lookup"><span data-stu-id="33251-437">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="33251-438">Dateien oder Ordner, die die aktuellen <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online Einschränkungen und-Einschränkungen</span> überschreiten</a> </span><span class="sxs-lookup"><span data-stu-id="33251-438">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="33251-439"><strong>Einzelne G Suite-Umgebung (nur Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="33251-439"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="33251-440">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="33251-440">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="33251-441">Google Docs, Google Tabellen und Google Präsentationen (Dateien werden in das entsprechende Office-Format konvertiert, einschließlich derjenigen über 10 MB)</span><span class="sxs-lookup"><span data-stu-id="33251-441">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="33251-442">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="33251-442">File and folder structure</span></span> </li>
<li> <span data-ttu-id="33251-443">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="33251-443">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="33251-444">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="33251-444">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="33251-445">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="33251-445">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="33251-446">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="33251-446">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="33251-447">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="33251-447">Created date</span></span> </li>
<li> <span data-ttu-id="33251-448">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="33251-448">Modified date</span></span> </li>
<li> <span data-ttu-id="33251-449">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="33251-449">Created by</span></span> </li>
<li> <span data-ttu-id="33251-450">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="33251-450">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="33251-451">Freigegebene Laufwerke (Ordner und Dateien)</span><span class="sxs-lookup"><span data-stu-id="33251-451">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="33251-452">Geteilte Inhalte, die im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="33251-452">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="33251-453">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="33251-453">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="33251-454">Beschreibungen von Dateien und Ordnern, Ordnerfarben</span><span class="sxs-lookup"><span data-stu-id="33251-454">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="33251-455">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="33251-455">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="33251-456">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="33251-456">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="33251-457">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="33251-457">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="33251-458">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="33251-458">File lock attributes</span></span> </li>
<li> <span data-ttu-id="33251-459">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="33251-459">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="33251-460">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="33251-460">Trashed items</span></span> </li>
<li> <span data-ttu-id="33251-461">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="33251-461">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="33251-462">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="33251-462">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="33251-463">Google Fotos, Google Formulare, Google Maps und andere verbundene Apps</span><span class="sxs-lookup"><span data-stu-id="33251-463">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="33251-464">Google Zeichnungen</span><span class="sxs-lookup"><span data-stu-id="33251-464">Google Drawings</span></span> </li>
<li> <span data-ttu-id="33251-465">Freigegebene Inhalte außerhalb Ihrer Organisation</span><span class="sxs-lookup"><span data-stu-id="33251-465">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="33251-466">Inhalte, die nicht im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="33251-466">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="33251-467">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Google Drive-Administratorberichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="33251-467">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="33251-468">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="33251-468">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="33251-469">Mitgliedschaftsberechtigungen für freigegebene Laufwerke (<strong>Hinweis</strong>: Verwenden Sie die Google Drive-Administratorberichte, um die Mitgliedschaften für freigegebene Laufwerke zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="33251-469">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="33251-470">Weisen Sie die Endbenutzer an, diese Mitgliedschaftseinstellungen auf dem Ziel vor der Migration zu konfigurieren.)</span><span class="sxs-lookup"><span data-stu-id="33251-470">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="33251-471">Dateien oder Ordner, die die aktuellen <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online Einschränkungen und-Einschränkungen</span> überschreiten</a> </span><span class="sxs-lookup"><span data-stu-id="33251-471">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="33251-472"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="33251-472"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="33251-473">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="33251-473">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="33251-474">Dokumente</span><span class="sxs-lookup"><span data-stu-id="33251-474">Documents</span></span> </li>
<li> <span data-ttu-id="33251-475">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="33251-475">File and folder structure</span></span> </li>
<li> <span data-ttu-id="33251-476">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="33251-476">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="33251-477">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="33251-477">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="33251-478">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="33251-478">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="33251-479">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="33251-479">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="33251-480">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="33251-480">Created date</span></span> </li>
<li> <span data-ttu-id="33251-481">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="33251-481">Modified date</span></span> </li>
<li> <span data-ttu-id="33251-482">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="33251-482">Created by</span></span> </li>
<li> <span data-ttu-id="33251-483">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="33251-483">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="33251-484">Geteilte Inhalte, die im Besitz des Box-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="33251-484">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="33251-485">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="33251-485">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="33251-486">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="33251-486">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="33251-487">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="33251-487">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="33251-488">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="33251-488">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="33251-489">Box-Tags und erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="33251-489">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="33251-490">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="33251-490">File lock attributes</span></span> </li>
<li> <span data-ttu-id="33251-491">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="33251-491">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="33251-492">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="33251-492">Trashed items</span></span> </li>
<li> <span data-ttu-id="33251-493">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="33251-493">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="33251-494">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="33251-494">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="33251-495">Box-Apps, Lesezeichen, Favoriten und Workflows</span><span class="sxs-lookup"><span data-stu-id="33251-495">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="33251-496">Inhalte, die nicht im Besitz des migrierten Box-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="33251-496">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="33251-497">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Box-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="33251-497">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="33251-498">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="33251-498">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="33251-499">Dateien oder Ordner, die die aktuellen <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online Einschränkungen und-Einschränkungen</span> überschreiten</a> </span><span class="sxs-lookup"><span data-stu-id="33251-499">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="33251-500"><strong>Dropbox für Teams (Standard und Erweitert)</strong></span><span class="sxs-lookup"><span data-stu-id="33251-500"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="33251-501">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="33251-501">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="33251-502">Dokumente</span><span class="sxs-lookup"><span data-stu-id="33251-502">Documents</span></span> </li>
<li> <span data-ttu-id="33251-503">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="33251-503">File and folder structure</span></span> </li>
<li> <span data-ttu-id="33251-504">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="33251-504">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="33251-505">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="33251-505">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="33251-506">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="33251-506">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="33251-507">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="33251-507">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="33251-508">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="33251-508">Created date</span></span> </li>
<li> <span data-ttu-id="33251-509">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="33251-509">Modified date</span></span> </li>
<li> <span data-ttu-id="33251-510">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="33251-510">Created by</span></span> </li>
<li> <span data-ttu-id="33251-511">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="33251-511">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="33251-512">Freigegebene Teamordner und -inhalte</span><span class="sxs-lookup"><span data-stu-id="33251-512">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="33251-513">Geteilte Inhalte, die im Besitz des Dropbox-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="33251-513">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="33251-514">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="33251-514">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="33251-515">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="33251-515">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="33251-516">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="33251-516">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="33251-517">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="33251-517">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="33251-518">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="33251-518">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="33251-519">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="33251-519">File lock attributes</span></span> </li>
<li> <span data-ttu-id="33251-520">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="33251-520">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="33251-521">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="33251-521">Trashed items</span></span> </li>
<li> <span data-ttu-id="33251-522">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="33251-522">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="33251-523">Nicht gemountete Dropbox-Ordner</span><span class="sxs-lookup"><span data-stu-id="33251-523">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="33251-524">Gelöschte oder getrennte Benutzer</span><span class="sxs-lookup"><span data-stu-id="33251-524">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="33251-525">Dropbox Paper, Showcases und Spaces</span><span class="sxs-lookup"><span data-stu-id="33251-525">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="33251-526">Dropbox-Apps und Favoriten (Pins/Sterne)</span><span class="sxs-lookup"><span data-stu-id="33251-526">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="33251-527">Inhalte, die nicht im Besitz des migrierten Dropbox-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="33251-527">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="33251-528">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Dropbox-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="33251-528">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="33251-529">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="33251-529">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="33251-530">Dateien oder Ordner, die die aktuellen <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online Einschränkungen und-Einschränkungen</span> überschreiten</a> </span><span class="sxs-lookup"><span data-stu-id="33251-530">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="33251-531">FastTrack-Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="33251-531">FastTrack responsibilities</span></span>

<span data-ttu-id="33251-532">Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="33251-532">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="33251-533">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="33251-533">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="33251-534">Ihre Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="33251-534">Your responsibilities</span></span>

<span data-ttu-id="33251-535">Während des Migrationsprojekts führen Sie Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="33251-535">You perform standard activities during the migration project.</span></span> <span data-ttu-id="33251-536">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="33251-536">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="33251-537">Sie führen außerdem die folgenden Aktivitäten speziell für OneDrive for Business-Migrationen aus:</span><span class="sxs-lookup"><span data-stu-id="33251-537">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="33251-538">Bereitstellen aller OneDrive for Business-Websites, die für Ihre Migrationsereignisse bestimmt sind.</span><span class="sxs-lookup"><span data-stu-id="33251-538">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
