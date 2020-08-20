---
title: Datenmigration
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Sie können die Migration von E-Mail- und Dateidaten in ihrer Quellumgebung auf Office 365 (Exchange Online, SharePoint Online und OneDrive for Business) mithilfe von FastTrack migrieren. Die Art der von uns bereitgestellten Unterstützung hängt von der Anzahl der Office 365-Lizenzen ab.
ms.openlocfilehash: 6b2c9cc3afba415c200b14fe34e65f1c3286e450
ms.sourcegitcommit: d67bbe7e9f71c9983280cb3858a4fff0d7ac884b
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/20/2020
ms.locfileid: "46817712"
---
# <a name="data-migration"></a><span data-ttu-id="68da0-104">Datenmigration</span><span class="sxs-lookup"><span data-stu-id="68da0-104">Data Migration</span></span>

<span data-ttu-id="68da0-105">Sie können die Migration von E-Mail- und Dateidaten in ihrer Quellumgebung auf Office 365 (Exchange Online, SharePoint Online und OneDrive for Business) mithilfe von FastTrack migrieren.</span><span class="sxs-lookup"><span data-stu-id="68da0-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="68da0-106">Die Art der von uns bereitgestellten Unterstützung hängt von der Anzahl der Office 365-Lizenzen ab:</span><span class="sxs-lookup"><span data-stu-id="68da0-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="68da0-107">**Für Office 365-Mandanten mit 150 bis 499-Lizenzen**: FastTrack bietet nur Migrationsanleitungen. Sie sind für die Durchführung der Datenmigration verantwortlich.</span><span class="sxs-lookup"><span data-stu-id="68da0-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="68da0-108">Wir führen Sie durch die Dokumentation, die Ihnen hilft, ﻿kostenlose Tools für die Durchführung einer Self-Service-Migration zu planen und zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="68da0-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="68da0-109">**Für Office 365-Mandanten mit 500 oder mehr Lizenzen**: FastTrack bietet Migrationsanleitungen und Datenmigrationsdienste.</span><span class="sxs-lookup"><span data-stu-id="68da0-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="68da0-110">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des Office 365-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Daten.</span><span class="sxs-lookup"><span data-stu-id="68da0-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="68da0-111">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="68da0-111">You create and schedule your migration events.</span></span> <span data-ttu-id="68da0-112">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="68da0-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="68da0-113">Wenn Sie einen kommerziellen Plan vor dem 1.9.2017 erworben oder verlängert haben, benötigen Sie nur 150 Lizenzen, um für Datenmigrationsdienste qualifiziert zu sein.</span><span class="sxs-lookup"><span data-stu-id="68da0-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="68da0-114">Bei Plänen für Bildungseinrichtungen sind nur Lehrpersonal und Mitarbeiter für Migrationsdienste berechtigt.</span><span class="sxs-lookup"><span data-stu-id="68da0-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="68da0-115">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="68da0-115">Considerations</span></span>

  - <span data-ttu-id="68da0-116">Ihre Quellumgebungen müssen bestimmte Erwartungen erfüllen, um Daten zu Office 365 zu migrieren.</span><span class="sxs-lookup"><span data-stu-id="68da0-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="68da0-117">Weitere Informationen zu den Erwartungen bezüglich der Quellumgebung für Exchange, SharePoint und OneDrive for Business finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="68da0-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="68da0-118">Für die Bereitstellung von Datenmigrationsdiensten benötigen wir einen geeigneten Zugriff auf Ihre Quellumgebungen und den Office 365-Mandanten.</span><span class="sxs-lookup"><span data-stu-id="68da0-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="68da0-119">Unsere Datenmigrationsdienste sind nicht für Daten vorgesehen, die besonderen rechtlichen oder behördlichen Vorschriften unterliegen.</span><span class="sxs-lookup"><span data-stu-id="68da0-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="68da0-120">Wenn wir Ihre Daten migrieren, können sie an einen beliebigen Ort, an dem wir über Einrichtungen verfügen, übertragen, dort gespeichert und verarbeitet werden (sofern nicht anderweitig für Ihr FastTrack-Migrationsprojekt angegeben).</span><span class="sxs-lookup"><span data-stu-id="68da0-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="68da0-121">Wir übernehmen keine Garantie für die Geschwindigkeit der E-Mail- oder Dateimigration.</span><span class="sxs-lookup"><span data-stu-id="68da0-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="68da0-122">Unvorhergesehene Probleme (wie unlesbare oder fehlerhafte Elemente in der Quellumgebung) verhindern möglicherweise, dass einige ihrer Datenelemente migriert werden können.</span><span class="sxs-lookup"><span data-stu-id="68da0-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="68da0-123">Externe Faktoren, die außerhalb unserer Kontrolle stehen (z. B. Änderungen an den Programmierschnittstellen von Drittanbietern) können zu Änderungen, Verzögerungen oder der Sperrung unserer Datenmigrationsdienste führen.</span><span class="sxs-lookup"><span data-stu-id="68da0-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="68da0-124">Verfügbarkeit des Migrationsdiensts</span><span class="sxs-lookup"><span data-stu-id="68da0-124">Migration service availability</span></span>

  - <span data-ttu-id="68da0-125">**Für kommerzielle Kunden und britische Behörden:** Wir stellen Datenmigrationsdienste rund um die Uhr an sieben (7) Tagen pro Woche bereit.</span><span class="sxs-lookup"><span data-stu-id="68da0-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="68da0-126">**Für Kunden von US-amerikanischen Behörden/Verteidigungsministerium:** Wir stellen Datenmigrationsdienste rund um die Uhr an fünf (5) Werktagen pro Woche bereit.</span><span class="sxs-lookup"><span data-stu-id="68da0-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="68da0-127">Migration zu Exchange Online</span><span class="sxs-lookup"><span data-stu-id="68da0-127">Migration to Exchange Online</span></span>

<span data-ttu-id="68da0-128">Wenn Sie sich für die Migration Ihrer E-Mails zu Exchange Online mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit.</span><span class="sxs-lookup"><span data-stu-id="68da0-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="68da0-129">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des Exchange Online-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Postfächer.</span><span class="sxs-lookup"><span data-stu-id="68da0-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="68da0-130">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="68da0-130">You create and schedule your migration events.</span></span> <span data-ttu-id="68da0-131">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="68da0-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="68da0-132">Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass E-Mail-Nachrichten von entsprechend geplanten und berechtigten Quellpostfächern ihrer Quellumgebungen zu Exchange Online migriert wurden.</span><span class="sxs-lookup"><span data-stu-id="68da0-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="68da0-133">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="68da0-133">Considerations</span></span>

  - <span data-ttu-id="68da0-134">Bevor Sie die Migration durchführen können, müssen Sie den FastTrack-Onboarding-Vorgang für Exchange Online durchführen.</span><span class="sxs-lookup"><span data-stu-id="68da0-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="68da0-135">Wenn Sie das Onboarding selbst durchgeführt haben, müssen Sie die erforderlichen Überprüfungen und Voraussetzungen erfüllen.</span><span class="sxs-lookup"><span data-stu-id="68da0-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="68da0-136">Ausführliche Informationen finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="68da0-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="68da0-137">FastTrack migriert nur zu aktiven Office 365-Postfächern.</span><span class="sxs-lookup"><span data-stu-id="68da0-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="68da0-138">Sie müssen bestimmte Anforderungen erfüllen, wenn Sie von einer lokalen Exchange-Umgebung migrieren möchten.</span><span class="sxs-lookup"><span data-stu-id="68da0-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="68da0-139">Weitere Informationen finden Sie unter [Voraussetzungen für die Hybridbereitstellung](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="68da0-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="68da0-140">Sämtliche Quellumgebungen müssen über die neuesten Service Packs (SP) verfügen und auf der Rollup (RU)-/Kumulativen Update (KU)-Ebene für das entsprechende Produkt in der Quellumgebung vorhanden sein.</span><span class="sxs-lookup"><span data-stu-id="68da0-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="68da0-141">Verteilerlisten (*MailEnabledGroup*-Objekte) und externe Kontakte (*MailEnabledContact*-Objekte) im lokalen Active Directory befinden, sind nicht Bestandteil einer Postfachdatenmigration.</span><span class="sxs-lookup"><span data-stu-id="68da0-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="68da0-142">Sie können Sie jedoch mithilfe von Azure Active Directory (Azure AD) Connect synchronisieren.</span><span class="sxs-lookup"><span data-stu-id="68da0-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="68da0-143">Quellumgebungen</span><span class="sxs-lookup"><span data-stu-id="68da0-143">Source environments</span></span>

<span data-ttu-id="68da0-144">Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:</span><span class="sxs-lookup"><span data-stu-id="68da0-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="68da0-145">aus einer einzelnen oder aus mehreren Active Directory-Gesamtstrukturen mit einer oder mehreren Exchange-Organisationen (jedes Exchange-E-Mail-System muss Exchange 2010 oder höher sein).</span><span class="sxs-lookup"><span data-stu-id="68da0-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="68da0-146">aus einer einzelnen IMAP-fähigen E-Mail-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="68da0-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="68da0-147">aus einer G Suite-Umgebung (nur Gmail, Kontakte und Kalender).</span><span class="sxs-lookup"><span data-stu-id="68da0-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="68da0-148">Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:</span><span class="sxs-lookup"><span data-stu-id="68da0-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="68da0-149"><strong>Quellumgebung</strong></span><span class="sxs-lookup"><span data-stu-id="68da0-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="68da0-150"><strong>Migrationstyp</strong></span><span class="sxs-lookup"><span data-stu-id="68da0-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="68da0-151"><strong>Was wird migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="68da0-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="68da0-152"><strong>Was wird nicht migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="68da0-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="68da0-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="68da0-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="68da0-154">
<strong>Hinweis:</strong> Informationen zu lokalen Exchange-Abhängigkeiten finden Sie unter  <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Voraussetzungen für die Hybridbereitstellung</span></a>.</span><span class="sxs-lookup"><span data-stu-id="68da0-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="68da0-155">Migration mit Hybridbereitstellung</span><span class="sxs-lookup"><span data-stu-id="68da0-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="68da0-156">E-Mails</span><span class="sxs-lookup"><span data-stu-id="68da0-156">Emails</span></span></li>
<li><span data-ttu-id="68da0-157">Postfachregeln</span><span class="sxs-lookup"><span data-stu-id="68da0-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="68da0-158">Stellvertretungen</span><span class="sxs-lookup"><span data-stu-id="68da0-158">Delegates</span></span></li>
<li><span data-ttu-id="68da0-159">Postfachkontakte</span><span class="sxs-lookup"><span data-stu-id="68da0-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="68da0-160">Kalender</span><span class="sxs-lookup"><span data-stu-id="68da0-160">Calendar</span></span> </li>
<li> <span data-ttu-id="68da0-161">Aufgaben</span><span class="sxs-lookup"><span data-stu-id="68da0-161">Tasks</span></span> </li>
<li> <span data-ttu-id="68da0-162">E-Mails mit Rechteverwaltung</span><span class="sxs-lookup"><span data-stu-id="68da0-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="68da0-163">Verschlüsselte E-Mails</span><span class="sxs-lookup"><span data-stu-id="68da0-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="68da0-164">Signaturen</span><span class="sxs-lookup"><span data-stu-id="68da0-164">Signatures</span></span> </li>
<li> <span data-ttu-id="68da0-165">Persönliches Archiv, das mit dem Benutzerpostfach migriert wird</span><span class="sxs-lookup"><span data-stu-id="68da0-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="68da0-166">Wiederherstellbare Elemente</span><span class="sxs-lookup"><span data-stu-id="68da0-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="68da0-167">Öffentliche Ordner</span><span class="sxs-lookup"><span data-stu-id="68da0-167">Public folders</span></span> </li>
<li> <span data-ttu-id="68da0-168">E-Mail, die die zulässige Nachrichtengröße überschreitet.</span><span class="sxs-lookup"><span data-stu-id="68da0-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="68da0-169">Journalarchiv oder eine beliebige Archivlösung von Drittanbietern</span><span class="sxs-lookup"><span data-stu-id="68da0-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="68da0-170">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="68da0-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="68da0-171">Archivdaten aus PST-Dateien</span><span class="sxs-lookup"><span data-stu-id="68da0-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="68da0-172">Beschädigte Elemente</span><span class="sxs-lookup"><span data-stu-id="68da0-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="68da0-173">Inaktive Postfächer</span><span class="sxs-lookup"><span data-stu-id="68da0-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="68da0-174"><strong>G Suite-Umgebung (nur Gmail, Kontakte und Kalender)</strong></span><span class="sxs-lookup"><span data-stu-id="68da0-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="68da0-175">
<strong>Hinweis:</strong> Ihre G Suite-Umgebung muss die Voraussetzungen erfüllen, die unter <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Durchführen einer G Suite-Migration</a> beschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="68da0-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="68da0-176">Übernahmemigration oder mehrstufige Migration</span><span class="sxs-lookup"><span data-stu-id="68da0-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="68da0-177">E-Mails</span><span class="sxs-lookup"><span data-stu-id="68da0-177">Emails</span></span> </li>
<li> <span data-ttu-id="68da0-178">Postfachkontakte (es werden maximal drei E-Mail-Adressen pro Kontakt migriert)</span><span class="sxs-lookup"><span data-stu-id="68da0-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="68da0-179">Kalender</span><span class="sxs-lookup"><span data-stu-id="68da0-179">Calendar</span></span> </li>
<li> <span data-ttu-id="68da0-180">Bezeichnungen</span><span class="sxs-lookup"><span data-stu-id="68da0-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="68da0-181">Regeln</span><span class="sxs-lookup"><span data-stu-id="68da0-181">Rules</span></span> </li>
<li> <span data-ttu-id="68da0-182">Stellvertretungen</span><span class="sxs-lookup"><span data-stu-id="68da0-182">Delegates</span></span> </li>
<li> <span data-ttu-id="68da0-183">Signaturen</span><span class="sxs-lookup"><span data-stu-id="68da0-183">Signatures</span></span> </li>
<li> <span data-ttu-id="68da0-184">Aufgaben</span><span class="sxs-lookup"><span data-stu-id="68da0-184">Tasks</span></span> </li>
<li> <span data-ttu-id="68da0-185">E-Mails oder Anhänge, die die zulässige Nachrichtengröße überschreiten</span><span class="sxs-lookup"><span data-stu-id="68da0-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="68da0-186">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="68da0-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="68da0-187">Archivdaten aus PST-Dateien oder einer Drittanbieter-Archivlösung (z. B. Google Vault)</span><span class="sxs-lookup"><span data-stu-id="68da0-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="68da0-188">E-Mails mit Rechteverwaltung oder Verschlüsselung</span><span class="sxs-lookup"><span data-stu-id="68da0-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="68da0-189">Beschädigte Elemente</span><span class="sxs-lookup"><span data-stu-id="68da0-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="68da0-190">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="68da0-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="68da0-191">Google-Gruppen</span><span class="sxs-lookup"><span data-stu-id="68da0-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="68da0-192">Ressourcenpostfächer</span><span class="sxs-lookup"><span data-stu-id="68da0-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="68da0-193">Inaktive Postfächer</span><span class="sxs-lookup"><span data-stu-id="68da0-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="68da0-194">Urlaubseinstellungen und Einstellungen für automatische Antworten</span><span class="sxs-lookup"><span data-stu-id="68da0-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="68da0-195">Freigegebene Kalender, Cloudanlagen, Google Hangout-Links und Ereignisfarben</span><span class="sxs-lookup"><span data-stu-id="68da0-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="68da0-196">\*\*Hangout-Unterhaltungen, die als Beschriftungen gespeichert wurden, werden migriert.</span><span class="sxs-lookup"><span data-stu-id="68da0-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="68da0-197"><strong>IMAP4-Quelle (wie Domino, GroupWise oder Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="68da0-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="68da0-198">Migration mit systemeigenen IMAP4-Tools</span><span class="sxs-lookup"><span data-stu-id="68da0-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="68da0-199">E-Mails</span><span class="sxs-lookup"><span data-stu-id="68da0-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="68da0-200">Regeln</span><span class="sxs-lookup"><span data-stu-id="68da0-200">Rules</span></span> </li>
<li> <span data-ttu-id="68da0-201">Stellvertretungen</span><span class="sxs-lookup"><span data-stu-id="68da0-201">Delegates</span></span> </li>
<li> <span data-ttu-id="68da0-202">Verteilerlisten</span><span class="sxs-lookup"><span data-stu-id="68da0-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="68da0-203">Externe Kontakte</span><span class="sxs-lookup"><span data-stu-id="68da0-203">External contacts</span></span> </li>
<li> <span data-ttu-id="68da0-204">E-Mail-aktivierte Benutzer</span><span class="sxs-lookup"><span data-stu-id="68da0-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="68da0-205">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="68da0-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="68da0-206">Postfachkontakte</span><span class="sxs-lookup"><span data-stu-id="68da0-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="68da0-207">Kalender</span><span class="sxs-lookup"><span data-stu-id="68da0-207">Calendar</span></span> </li>
<li> <span data-ttu-id="68da0-208">Signaturen</span><span class="sxs-lookup"><span data-stu-id="68da0-208">Signatures</span></span> </li>
<li> <span data-ttu-id="68da0-209">Aufgaben</span><span class="sxs-lookup"><span data-stu-id="68da0-209">Tasks</span></span> </li>
<li> <span data-ttu-id="68da0-210">E-Mails, die die zulässige Nachrichtengröße überschreiten</span><span class="sxs-lookup"><span data-stu-id="68da0-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="68da0-211">Archivdaten</span><span class="sxs-lookup"><span data-stu-id="68da0-211">Archive data</span></span> </li>
<li> <span data-ttu-id="68da0-212">Verschlüsselte E-Mail-Nachrichten</span><span class="sxs-lookup"><span data-stu-id="68da0-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="68da0-213">Beschädigte Elemente</span><span class="sxs-lookup"><span data-stu-id="68da0-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="68da0-214">Inaktive Postfächer</span><span class="sxs-lookup"><span data-stu-id="68da0-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="68da0-215">FastTrack-Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="68da0-215">FastTrack responsibilities</span></span>

<span data-ttu-id="68da0-216">Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="68da0-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="68da0-217">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="68da0-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="68da0-218">Unsere FastTrack-Spezialisten führen außerdem die folgenden Aktivitäten speziell für Exchange-Migrationen durch:</span><span class="sxs-lookup"><span data-stu-id="68da0-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="68da0-219">Bereitstellen von Anleitungen, die Ihnen dabei helfen, die Koexistenz von SMTP-E-Mail-Routing zwischen Ihrer Quellumgebung und Exchange Online zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="68da0-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="68da0-220">Ihre Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="68da0-220">Your responsibilities</span></span>

<span data-ttu-id="68da0-221">Während des Migrationsprojekts führen Sie Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="68da0-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="68da0-222">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="68da0-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="68da0-223">Sie führen außerdem die folgenden Aktivitäten speziell für Exchange-Migrationen aus:</span><span class="sxs-lookup"><span data-stu-id="68da0-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="68da0-224">Durchführen des FastTrack-Onboarding-Vorgangs für Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="68da0-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="68da0-225">Wenn Sie das Onboarding selbst durchgeführt haben, müssen Sie die erforderlichen Überprüfungen und Voraussetzungen erfüllen.</span><span class="sxs-lookup"><span data-stu-id="68da0-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="68da0-226">Ausführliche Informationen finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="68da0-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="68da0-227">Installieren der entsprechenden Clientsoftwareebene gemäß den Office 365-Richtlinien.</span><span class="sxs-lookup"><span data-stu-id="68da0-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="68da0-228">Details finden Sie unter [Der moderne Arbeitsplatz](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="68da0-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="68da0-229">Erfüllen bestimmter Anforderungen, wenn Sie von einer lokalen Exchange-Umgebung migrieren möchten.</span><span class="sxs-lookup"><span data-stu-id="68da0-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="68da0-230">Weitere Informationen finden Sie unter [Voraussetzungen für die Hybridbereitstellung](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="68da0-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="68da0-231">Sicherstellen, dass jede Quellumgebung über das neueste Service Pack (SP) und Rollup (RU)/Cumulative Update (CU) verfügt, sofern zutreffend.</span><span class="sxs-lookup"><span data-stu-id="68da0-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="68da0-232">Konfigurieren und Validieren der Koexistenz von SMTP-E-Mail-Routing zwischen Ihrer Quellumgebung und Exchange Online, sofern zutreffend.</span><span class="sxs-lookup"><span data-stu-id="68da0-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="68da0-233">Sicherstellen, dass die Größe des Quellpostfachs das Zielpostfachkontingent nicht überschreitet.</span><span class="sxs-lookup"><span data-stu-id="68da0-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="68da0-234">Abhängig von der Quellplattform müssen Sie möglicherweise Ihre Quelldaten auf 85 % des Zielpostfachkontingents beschränken.</span><span class="sxs-lookup"><span data-stu-id="68da0-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="68da0-235">Ggf. Migrieren clientseitiger Daten.</span><span class="sxs-lookup"><span data-stu-id="68da0-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="68da0-236">Dies umfasst unter anderem lokale Adressbücher, Daten in lokalen PST-Dateien, Outlook-Regeln und lokale Outlook-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="68da0-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="68da0-237">Unterstützen Ihrer Endbenutzer bei der Behebung von Problemen bei der clientbasierten Migration.</span><span class="sxs-lookup"><span data-stu-id="68da0-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="68da0-238">Migration zu SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="68da0-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="68da0-239">Wenn Sie sich für die Migration Ihrer Dateien zu SharePoint Online mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit.</span><span class="sxs-lookup"><span data-stu-id="68da0-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="68da0-240">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des SharePoint Online-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Dateien.</span><span class="sxs-lookup"><span data-stu-id="68da0-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="68da0-241">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="68da0-241">You create and schedule your migration events.</span></span> <span data-ttu-id="68da0-242">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="68da0-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="68da0-243">Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass Dateien von entsprechend geplanten und berechtigten Quellen ihrer Quellumgebungen zu SharePoint Online migriert wurden.</span><span class="sxs-lookup"><span data-stu-id="68da0-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="68da0-244">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="68da0-244">Considerations</span></span>

  - <span data-ttu-id="68da0-245">Alle Migrationen unterliegen SharePoint Online-Kontingenten.</span><span class="sxs-lookup"><span data-stu-id="68da0-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="68da0-246">Weitere Informationen finden Sie unter [<span class="underline">SharePoint Online und OneDrive for Business: Softwarelimits und -beschränkungen</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="68da0-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="68da0-247">Der Gesamtbetrag sollte auf 75 Prozent des SharePoint Online-Gesamtspeicherkontingents, für das Sie berechtigt sind, beschränkt werden (einschließlich den zusätzlichen Speicher, den Sie möglicherweise separat gekauft haben).</span><span class="sxs-lookup"><span data-stu-id="68da0-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="68da0-248">Detail der Quellumgebung</span><span class="sxs-lookup"><span data-stu-id="68da0-248">Source environment details</span></span>

<span data-ttu-id="68da0-249">Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:</span><span class="sxs-lookup"><span data-stu-id="68da0-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="68da0-250">Dateifreigaben (SMB [Server Message Block]-Dateifreigaben auf Geräten mit Unterstützung für SMB 2.0 und höher)</span><span class="sxs-lookup"><span data-stu-id="68da0-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="68da0-251">Eine einzelne G Suite-Umgebung (nur Google Drive).</span><span class="sxs-lookup"><span data-stu-id="68da0-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="68da0-252">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="68da0-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="68da0-253">Dropbox für Teams (Standard und Erweitert).</span><span class="sxs-lookup"><span data-stu-id="68da0-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="68da0-254">Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:</span><span class="sxs-lookup"><span data-stu-id="68da0-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="68da0-255"><strong>Quellumgebung</strong></span><span class="sxs-lookup"><span data-stu-id="68da0-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="68da0-256"><strong>Migrationstyp</strong></span><span class="sxs-lookup"><span data-stu-id="68da0-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="68da0-257"><strong>Was wird migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="68da0-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="68da0-258"><strong>Was wird nicht migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="68da0-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="68da0-259"><strong>Alle Dateifreigabegeräte mit Unterstützung für SMB 2.0 und höher</strong></span><span class="sxs-lookup"><span data-stu-id="68da0-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="68da0-260">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="68da0-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="68da0-261">Dokumente</span><span class="sxs-lookup"><span data-stu-id="68da0-261">Documents</span></span> </li>
<li> <span data-ttu-id="68da0-262">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="68da0-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="68da0-263">Datei- und Ordnerberechtigungen auf Benutzerebene\*</span><span class="sxs-lookup"><span data-stu-id="68da0-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="68da0-264">Datei- und Ordnerberechtigungen auf Gruppenebene\*</span><span class="sxs-lookup"><span data-stu-id="68da0-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="68da0-265">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="68da0-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="68da0-266">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="68da0-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="68da0-267">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="68da0-267">Created date</span></span> </li>
<li> <span data-ttu-id="68da0-268">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="68da0-268">Modified date</span></span> </li>
<li> <span data-ttu-id="68da0-269">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="68da0-269">Created by</span></span> </li>
<li> <span data-ttu-id="68da0-270">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="68da0-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="68da0-271">\* Setzt die Konfiguration der Verzeichnissynchronisierung voraus.</span><span class="sxs-lookup"><span data-stu-id="68da0-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="68da0-272">Es werden nur NTFS-Berechtigungen migriert, die für den Windows-Datei-Explorer verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="68da0-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="68da0-273">Berechtigungen, die direkt auf Dateifreigabegeräten verwaltet werden, werden nicht migriert.</span><span class="sxs-lookup"><span data-stu-id="68da0-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="68da0-274">Wenn Daten auf einem SMB 2.0-Gerät gespeichert werden, werden die NTFS-äquivalenten Berechtigungen, die vom SMB-Protokoll verfügbar gemacht werden, migriert.</span><span class="sxs-lookup"><span data-stu-id="68da0-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="68da0-275">Aufgezeichnete Eigentümerschaft und frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="68da0-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="68da0-276">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="68da0-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="68da0-277">Frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="68da0-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="68da0-278">Windows-Datei-/-Ordnerattribute (z. B. „Schreibgeschützt“ und „Ausgeblendet“) </span><span class="sxs-lookup"><span data-stu-id="68da0-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="68da0-279">Nicht-Windows-NTFS-Dateisystem (New Technology File System) und erweiterte NTFS-Berechtigungen sowie besondere Einstellungen:</span><span class="sxs-lookup"><span data-stu-id="68da0-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="68da0-280">Explizite Verweigerungsberechtigungen (werden nach der Migration entfernt, Inhalte unterliegen parallelen Berechtigungen oder Berechtigungen im übergeordneten Ordner).</span><span class="sxs-lookup"><span data-stu-id="68da0-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="68da0-281">Konfiguration der NTFS-Überwachung</span><span class="sxs-lookup"><span data-stu-id="68da0-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="68da0-282">Zusätzliche Dateimetadaten von der Dateiklassifizierungsinfrastruktur (File Classification Infrastructure, FCI)</span><span class="sxs-lookup"><span data-stu-id="68da0-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="68da0-283">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="68da0-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="68da0-284">Ausgeblendete Freigaben</span><span class="sxs-lookup"><span data-stu-id="68da0-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="68da0-285">Freigabe (z. B. gewährte Berechtigungen auf Freigabeebene)</span><span class="sxs-lookup"><span data-stu-id="68da0-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="68da0-286">Dateien oder Ordner, die die aktuellen  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Einschränkungen und Begrenzen von SharePoint Online</span></a>  überschreiten</span><span class="sxs-lookup"><span data-stu-id="68da0-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="68da0-287"><strong>Einzelne G Suite-Umgebung (nur Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="68da0-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="68da0-288">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="68da0-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="68da0-289">Google Docs, Google Tabellen und Google Präsentationen (Dateien werden in das entsprechende Office-Format konvertiert), einschließlich derjenigen über 10 MB</span><span class="sxs-lookup"><span data-stu-id="68da0-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="68da0-290">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="68da0-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="68da0-291">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="68da0-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="68da0-292">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="68da0-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="68da0-293">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="68da0-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="68da0-294">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="68da0-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="68da0-295">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="68da0-295">Created date</span></span> </li>
<li> <span data-ttu-id="68da0-296">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="68da0-296">Modified date</span></span> </li>
<li> <span data-ttu-id="68da0-297">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="68da0-297">Created by</span></span> </li>
<li> <span data-ttu-id="68da0-298">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="68da0-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="68da0-299">Freigegebene Laufwerke (Ordner und Dateien)</span><span class="sxs-lookup"><span data-stu-id="68da0-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="68da0-300">Geteilte Inhalte, die im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="68da0-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="68da0-301">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="68da0-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="68da0-302">Beschreibungen von Dateien und Ordnern, Ordnerfarben</span><span class="sxs-lookup"><span data-stu-id="68da0-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="68da0-303">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="68da0-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="68da0-304">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="68da0-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="68da0-305">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="68da0-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="68da0-306">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="68da0-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="68da0-307">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="68da0-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="68da0-308">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="68da0-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="68da0-309">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="68da0-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="68da0-310">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="68da0-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="68da0-311">Google Fotos, Google Formulare, Google Maps und andere verbundene Apps</span><span class="sxs-lookup"><span data-stu-id="68da0-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="68da0-312">Google Zeichnungen</span><span class="sxs-lookup"><span data-stu-id="68da0-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="68da0-313">Freigegebene Inhalte außerhalb Ihrer Organisation</span><span class="sxs-lookup"><span data-stu-id="68da0-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="68da0-314">Inhalte, die nicht im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="68da0-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="68da0-315">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Google Drive-Administratorberichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="68da0-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="68da0-316">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="68da0-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="68da0-317">Mitgliedschaftsberechtigungen für freigegebene Laufwerke (<strong>Hinweis</strong>: Verwenden Sie die Google Drive-Administratorberichte, um die Mitgliedschaften für freigegebene Laufwerke zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="68da0-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="68da0-318">Weisen Sie die Endbenutzer an, diese Mitgliedschaftseinstellungen auf dem Ziel vor der Migration zu konfigurieren.)</span><span class="sxs-lookup"><span data-stu-id="68da0-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="68da0-319">Dateien oder Ordner, die die aktuellen  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Einschränkungen und Begrenzen von SharePoint Online</span></a>  überschreiten</span><span class="sxs-lookup"><span data-stu-id="68da0-319">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="68da0-320"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="68da0-320"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="68da0-321">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="68da0-321">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="68da0-322">Dokumente</span><span class="sxs-lookup"><span data-stu-id="68da0-322">Documents</span></span> </li>
<li> <span data-ttu-id="68da0-323">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="68da0-323">File and folder structure</span></span> </li>
<li> <span data-ttu-id="68da0-324">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="68da0-324">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="68da0-325">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="68da0-325">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="68da0-326">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="68da0-326">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="68da0-327">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="68da0-327">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="68da0-328">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="68da0-328">Created date</span></span> </li>
<li> <span data-ttu-id="68da0-329">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="68da0-329">Modified date</span></span> </li>
<li> <span data-ttu-id="68da0-330">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="68da0-330">Created by</span></span> </li>
<li> <span data-ttu-id="68da0-331">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="68da0-331">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="68da0-332">Geteilte Inhalte, die im Besitz des Box-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="68da0-332">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="68da0-333">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="68da0-333">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="68da0-334">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="68da0-334">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="68da0-335">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="68da0-335">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="68da0-336">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="68da0-336">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="68da0-337">Box-Tags und erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="68da0-337">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="68da0-338">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="68da0-338">File lock attributes</span></span> </li>
<li> <span data-ttu-id="68da0-339">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="68da0-339">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="68da0-340">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="68da0-340">Trashed items</span></span> </li>
<li> <span data-ttu-id="68da0-341">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="68da0-341">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="68da0-342">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="68da0-342">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="68da0-343">Box-Apps, Lesezeichen, Favoriten und Workflows</span><span class="sxs-lookup"><span data-stu-id="68da0-343">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="68da0-344">Inhalte, die nicht im Besitz des migrierten Box-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="68da0-344">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="68da0-345">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Box-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="68da0-345">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="68da0-346">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="68da0-346">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="68da0-347">Dateien oder Ordner, die die aktuellen  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Einschränkungen und Begrenzen von SharePoint Online</span></a>  überschreiten</span><span class="sxs-lookup"><span data-stu-id="68da0-347">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="68da0-348"><strong>Dropbox für Teams (Standard und Erweitert)</strong></span><span class="sxs-lookup"><span data-stu-id="68da0-348"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="68da0-349">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="68da0-349">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="68da0-350">Dokumente</span><span class="sxs-lookup"><span data-stu-id="68da0-350">Documents</span></span> </li>
<li> <span data-ttu-id="68da0-351">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="68da0-351">File and folder structure</span></span> </li>
<li> <span data-ttu-id="68da0-352">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="68da0-352">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="68da0-353">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="68da0-353">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="68da0-354">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="68da0-354">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="68da0-355">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="68da0-355">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="68da0-356">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="68da0-356">Created date</span></span> </li>
<li> <span data-ttu-id="68da0-357">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="68da0-357">Modified date</span></span> </li>
<li> <span data-ttu-id="68da0-358">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="68da0-358">Created by</span></span> </li>
<li> <span data-ttu-id="68da0-359">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="68da0-359">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="68da0-360">Freigegebene Teamordner und -inhalte</span><span class="sxs-lookup"><span data-stu-id="68da0-360">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="68da0-361">Geteilte Inhalte, die im Besitz des Dropbox-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="68da0-361">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="68da0-362">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="68da0-362">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="68da0-363">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="68da0-363">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="68da0-364">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="68da0-364">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="68da0-365">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="68da0-365">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="68da0-366">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="68da0-366">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="68da0-367">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="68da0-367">File lock attributes</span></span> </li>
<li> <span data-ttu-id="68da0-368">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="68da0-368">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="68da0-369">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="68da0-369">Trashed items</span></span> </li>
<li> <span data-ttu-id="68da0-370">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="68da0-370">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="68da0-371">Nicht gemountete Dropbox-Ordner</span><span class="sxs-lookup"><span data-stu-id="68da0-371">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="68da0-372">Gelöschte oder getrennte Benutzer</span><span class="sxs-lookup"><span data-stu-id="68da0-372">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="68da0-373">Dropbox Paper, Showcases und Spaces</span><span class="sxs-lookup"><span data-stu-id="68da0-373">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="68da0-374">Dropbox-Apps und Favoriten (Pins/Sterne)</span><span class="sxs-lookup"><span data-stu-id="68da0-374">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="68da0-375">Inhalte, die nicht im Besitz des migrierten Dropbox-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="68da0-375">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="68da0-376">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Dropbox-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="68da0-376">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="68da0-377">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="68da0-377">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="68da0-378">Dateien oder Ordner, die die aktuellen  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Einschränkungen und Begrenzen von SharePoint Online</span></a>  überschreiten</span><span class="sxs-lookup"><span data-stu-id="68da0-378">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="68da0-379">FastTrack-Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="68da0-379">FastTrack responsibilities</span></span>

<span data-ttu-id="68da0-380">Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="68da0-380">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="68da0-381">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="68da0-381">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="68da0-382">Ihre Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="68da0-382">Your responsibilities</span></span>

<span data-ttu-id="68da0-383">Während des Migrationsprojekts führen Sie Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="68da0-383">You perform standard activities during the migration project.</span></span> <span data-ttu-id="68da0-384">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="68da0-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="68da0-385">Sie führen außerdem die folgenden Aktivitäten speziell für SharePoint Online-Migrationen aus:</span><span class="sxs-lookup"><span data-stu-id="68da0-385">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="68da0-386">Bereitstellen aller SharePoint-Teamwebsites, die für Ihre Migrationsereignisse vorgesehen sind.</span><span class="sxs-lookup"><span data-stu-id="68da0-386">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="68da0-387">Migration zu OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="68da0-387">Migration to OneDrive for Business</span></span>

<span data-ttu-id="68da0-388">Wenn Sie sich für die Migration Ihrer Dateien zu OneDrive for Business mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit.</span><span class="sxs-lookup"><span data-stu-id="68da0-388">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="68da0-389">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des OneDrive for Business-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Dateien.</span><span class="sxs-lookup"><span data-stu-id="68da0-389">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="68da0-390">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="68da0-390">You create and schedule your migration events.</span></span> <span data-ttu-id="68da0-391">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="68da0-391">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="68da0-392">Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass Dateien von entsprechend geplanten und berechtigten Quellen ihrer Quellumgebungen zu OneDrive for Business migriert wurden.</span><span class="sxs-lookup"><span data-stu-id="68da0-392">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="68da0-393">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="68da0-393">Considerations</span></span>

  - <span data-ttu-id="68da0-394">Alle Migrationen unterliegen den OneDrive for Business-Kontingenten.</span><span class="sxs-lookup"><span data-stu-id="68da0-394">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="68da0-395">Weitere Informationen finden Sie unter [<span class="underline">SharePoint Online und OneDrive for Business: Softwarelimits und -beschränkungen</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="68da0-395">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="68da0-396">Der Gesamtbetrag sollte auf 75 Prozent der Daten des SharePoint Online-Gesamtspeicherkontingents, für das Sie berechtigt sind, beschränkt werden (einschließlich den zusätzlichen Speicher, den Sie möglicherweise separat gekauft haben).</span><span class="sxs-lookup"><span data-stu-id="68da0-396">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="68da0-397">FastTrack migriert nur zu aktiven OneDrive for Business-Laufwerken.</span><span class="sxs-lookup"><span data-stu-id="68da0-397">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="68da0-398">Detail der Quellumgebung</span><span class="sxs-lookup"><span data-stu-id="68da0-398">Source environment details</span></span>

<span data-ttu-id="68da0-399">Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:</span><span class="sxs-lookup"><span data-stu-id="68da0-399">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="68da0-400">Dateifreigaben (SMB-Dateifreigaben auf Geräten mit Unterstützung für SMB 2.0 und höher)</span><span class="sxs-lookup"><span data-stu-id="68da0-400">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="68da0-401">Einzelne G Suite-Umgebung (nur Google Drive).</span><span class="sxs-lookup"><span data-stu-id="68da0-401">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="68da0-402">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="68da0-402">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="68da0-403">Dropbox für Teams (Standard und Erweitert).</span><span class="sxs-lookup"><span data-stu-id="68da0-403">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="68da0-404">Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:</span><span class="sxs-lookup"><span data-stu-id="68da0-404">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="68da0-405"><strong>Quellumgebung</strong></span><span class="sxs-lookup"><span data-stu-id="68da0-405"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="68da0-406"><strong>Migrationstyp</strong></span><span class="sxs-lookup"><span data-stu-id="68da0-406"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="68da0-407"><strong>Was wird migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="68da0-407"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="68da0-408"><strong>Was wird nicht migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="68da0-408"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="68da0-409"><strong>Alle Dateifreigabegeräte mit Unterstützung für SMB 2.0 und höher</strong></span><span class="sxs-lookup"><span data-stu-id="68da0-409"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="68da0-410">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="68da0-410">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="68da0-411">Dokumente</span><span class="sxs-lookup"><span data-stu-id="68da0-411">Documents</span></span> </li>
<li> <span data-ttu-id="68da0-412">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="68da0-412">File and folder structure</span></span> </li>
<li> <span data-ttu-id="68da0-413">Datei- und Ordnerberechtigungen auf Benutzerebene\*</span><span class="sxs-lookup"><span data-stu-id="68da0-413">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="68da0-414">Datei- und Ordnerberechtigungen auf Gruppenebene\*</span><span class="sxs-lookup"><span data-stu-id="68da0-414">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="68da0-415">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="68da0-415">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="68da0-416">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="68da0-416">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="68da0-417">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="68da0-417">Created date</span></span> </li>
<li> <span data-ttu-id="68da0-418">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="68da0-418">Modified date</span></span> </li>
<li> <span data-ttu-id="68da0-419">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="68da0-419">Created by</span></span> </li>
<li> <span data-ttu-id="68da0-420">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="68da0-420">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="68da0-421">\* Setzt die Konfiguration der Verzeichnissynchronisierung voraus.</span><span class="sxs-lookup"><span data-stu-id="68da0-421">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="68da0-422">Es werden nur NTFS-Berechtigungen migriert, die für den Windows-Datei-Explorer verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="68da0-422">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="68da0-423">Berechtigungen, die direkt auf Dateifreigabegeräten verwaltet werden, werden nicht migriert.</span><span class="sxs-lookup"><span data-stu-id="68da0-423">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="68da0-424">Wenn Daten auf einem SMB 2.0-Gerät gespeichert werden, werden die NTFS-äquivalenten Berechtigungen, die vom SMB-Protokoll verfügbar gemacht werden, migriert.</span><span class="sxs-lookup"><span data-stu-id="68da0-424">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="68da0-425">Aufgezeichnete Eigentümerschaft und frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="68da0-425">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="68da0-426">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="68da0-426">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="68da0-427">Frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="68da0-427">Previous versions</span></span> </li>
<li> <span data-ttu-id="68da0-428">Windows-Datei-/-Ordnerattribute (z. B. „Schreibgeschützt“ und „Ausgeblendet“) </span><span class="sxs-lookup"><span data-stu-id="68da0-428">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="68da0-429">Nicht-Windows-NTFS-Dateisystem (New Technology File System) und erweiterte NTFS-Berechtigungen sowie besondere Einstellungen:</span><span class="sxs-lookup"><span data-stu-id="68da0-429">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="68da0-430">Explizite Verweigerungsberechtigungen (werden nach der Migration entfernt, Inhalte unterliegen parallelen Berechtigungen oder Berechtigungen im übergeordneten Ordner).</span><span class="sxs-lookup"><span data-stu-id="68da0-430">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="68da0-431">Konfiguration der NTFS-Überwachung</span><span class="sxs-lookup"><span data-stu-id="68da0-431">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="68da0-432">Zusätzliche Dateimetadaten von der Dateiklassifizierungsinfrastruktur (File Classification Infrastructure, FCI)</span><span class="sxs-lookup"><span data-stu-id="68da0-432">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="68da0-433">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="68da0-433">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="68da0-434">Ausgeblendete Freigaben</span><span class="sxs-lookup"><span data-stu-id="68da0-434">Hidden shares</span></span> </li>
<li> <span data-ttu-id="68da0-435">Freigabe (z. B. gewährte Berechtigungen auf Freigabeebene)</span><span class="sxs-lookup"><span data-stu-id="68da0-435">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="68da0-436">Dateien oder Ordner, die die aktuellen  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Einschränkungen und Begrenzen von SharePoint Online</span></a>  überschreiten</span><span class="sxs-lookup"><span data-stu-id="68da0-436">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="68da0-437"><strong>Einzelne G Suite-Umgebung (nur Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="68da0-437"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="68da0-438">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="68da0-438">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="68da0-439">Google Docs, Google Tabellen und Google Präsentationen (Dateien werden in das entsprechende Office-Format konvertiert, einschließlich derjenigen über 10 MB)</span><span class="sxs-lookup"><span data-stu-id="68da0-439">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="68da0-440">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="68da0-440">File and folder structure</span></span> </li>
<li> <span data-ttu-id="68da0-441">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="68da0-441">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="68da0-442">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="68da0-442">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="68da0-443">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="68da0-443">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="68da0-444">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="68da0-444">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="68da0-445">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="68da0-445">Created date</span></span> </li>
<li> <span data-ttu-id="68da0-446">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="68da0-446">Modified date</span></span> </li>
<li> <span data-ttu-id="68da0-447">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="68da0-447">Created by</span></span> </li>
<li> <span data-ttu-id="68da0-448">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="68da0-448">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="68da0-449">Freigegebene Laufwerke (Ordner und Dateien)</span><span class="sxs-lookup"><span data-stu-id="68da0-449">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="68da0-450">Geteilte Inhalte, die im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="68da0-450">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="68da0-451">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="68da0-451">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="68da0-452">Beschreibungen von Dateien und Ordnern, Ordnerfarben</span><span class="sxs-lookup"><span data-stu-id="68da0-452">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="68da0-453">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="68da0-453">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="68da0-454">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="68da0-454">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="68da0-455">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="68da0-455">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="68da0-456">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="68da0-456">File lock attributes</span></span> </li>
<li> <span data-ttu-id="68da0-457">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="68da0-457">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="68da0-458">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="68da0-458">Trashed items</span></span> </li>
<li> <span data-ttu-id="68da0-459">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="68da0-459">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="68da0-460">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="68da0-460">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="68da0-461">Google Fotos, Google Formulare, Google Maps und andere verbundene Apps</span><span class="sxs-lookup"><span data-stu-id="68da0-461">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="68da0-462">Google Zeichnungen</span><span class="sxs-lookup"><span data-stu-id="68da0-462">Google Drawings</span></span> </li>
<li> <span data-ttu-id="68da0-463">Freigegebene Inhalte außerhalb Ihrer Organisation</span><span class="sxs-lookup"><span data-stu-id="68da0-463">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="68da0-464">Inhalte, die nicht im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="68da0-464">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="68da0-465">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Google Drive-Administratorberichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="68da0-465">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="68da0-466">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="68da0-466">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="68da0-467">Mitgliedschaftsberechtigungen für freigegebene Laufwerke (<strong>Hinweis</strong>: Verwenden Sie die Google Drive-Administratorberichte, um die Mitgliedschaften für freigegebene Laufwerke zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="68da0-467">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="68da0-468">Weisen Sie die Endbenutzer an, diese Mitgliedschaftseinstellungen auf dem Ziel vor der Migration zu konfigurieren.)</span><span class="sxs-lookup"><span data-stu-id="68da0-468">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="68da0-469">Dateien oder Ordner, die die aktuellen  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Einschränkungen und Begrenzen von SharePoint Online</span></a>  überschreiten</span><span class="sxs-lookup"><span data-stu-id="68da0-469">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="68da0-470"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="68da0-470"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="68da0-471">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="68da0-471">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="68da0-472">Dokumente</span><span class="sxs-lookup"><span data-stu-id="68da0-472">Documents</span></span> </li>
<li> <span data-ttu-id="68da0-473">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="68da0-473">File and folder structure</span></span> </li>
<li> <span data-ttu-id="68da0-474">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="68da0-474">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="68da0-475">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="68da0-475">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="68da0-476">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="68da0-476">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="68da0-477">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="68da0-477">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="68da0-478">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="68da0-478">Created date</span></span> </li>
<li> <span data-ttu-id="68da0-479">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="68da0-479">Modified date</span></span> </li>
<li> <span data-ttu-id="68da0-480">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="68da0-480">Created by</span></span> </li>
<li> <span data-ttu-id="68da0-481">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="68da0-481">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="68da0-482">Geteilte Inhalte, die im Besitz des Box-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="68da0-482">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="68da0-483">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="68da0-483">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="68da0-484">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="68da0-484">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="68da0-485">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="68da0-485">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="68da0-486">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="68da0-486">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="68da0-487">Box-Tags und erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="68da0-487">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="68da0-488">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="68da0-488">File lock attributes</span></span> </li>
<li> <span data-ttu-id="68da0-489">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="68da0-489">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="68da0-490">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="68da0-490">Trashed items</span></span> </li>
<li> <span data-ttu-id="68da0-491">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="68da0-491">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="68da0-492">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="68da0-492">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="68da0-493">Box-Apps, Lesezeichen, Favoriten und Workflows</span><span class="sxs-lookup"><span data-stu-id="68da0-493">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="68da0-494">Inhalte, die nicht im Besitz des migrierten Box-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="68da0-494">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="68da0-495">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Box-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="68da0-495">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="68da0-496">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="68da0-496">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="68da0-497">Dateien oder Ordner, die die aktuellen  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Einschränkungen und Begrenzen von SharePoint Online</span></a>  überschreiten</span><span class="sxs-lookup"><span data-stu-id="68da0-497">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="68da0-498"><strong>Dropbox für Teams (Standard und Erweitert)</strong></span><span class="sxs-lookup"><span data-stu-id="68da0-498"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="68da0-499">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="68da0-499">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="68da0-500">Dokumente</span><span class="sxs-lookup"><span data-stu-id="68da0-500">Documents</span></span> </li>
<li> <span data-ttu-id="68da0-501">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="68da0-501">File and folder structure</span></span> </li>
<li> <span data-ttu-id="68da0-502">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="68da0-502">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="68da0-503">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="68da0-503">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="68da0-504">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="68da0-504">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="68da0-505">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="68da0-505">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="68da0-506">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="68da0-506">Created date</span></span> </li>
<li> <span data-ttu-id="68da0-507">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="68da0-507">Modified date</span></span> </li>
<li> <span data-ttu-id="68da0-508">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="68da0-508">Created by</span></span> </li>
<li> <span data-ttu-id="68da0-509">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="68da0-509">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="68da0-510">Freigegebene Teamordner und -inhalte</span><span class="sxs-lookup"><span data-stu-id="68da0-510">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="68da0-511">Geteilte Inhalte, die im Besitz des Dropbox-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="68da0-511">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="68da0-512">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="68da0-512">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="68da0-513">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="68da0-513">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="68da0-514">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="68da0-514">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="68da0-515">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="68da0-515">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="68da0-516">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="68da0-516">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="68da0-517">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="68da0-517">File lock attributes</span></span> </li>
<li> <span data-ttu-id="68da0-518">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="68da0-518">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="68da0-519">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="68da0-519">Trashed items</span></span> </li>
<li> <span data-ttu-id="68da0-520">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="68da0-520">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="68da0-521">Nicht gemountete Dropbox-Ordner</span><span class="sxs-lookup"><span data-stu-id="68da0-521">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="68da0-522">Gelöschte oder getrennte Benutzer</span><span class="sxs-lookup"><span data-stu-id="68da0-522">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="68da0-523">Dropbox Paper, Showcases und Spaces</span><span class="sxs-lookup"><span data-stu-id="68da0-523">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="68da0-524">Dropbox-Apps und Favoriten (Pins/Sterne)</span><span class="sxs-lookup"><span data-stu-id="68da0-524">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="68da0-525">Inhalte, die nicht im Besitz des migrierten Dropbox-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="68da0-525">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="68da0-526">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Dropbox-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="68da0-526">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="68da0-527">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="68da0-527">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="68da0-528">Dateien oder Ordner, die die aktuellen  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Einschränkungen und Begrenzen von SharePoint Online</span></a>  überschreiten</span><span class="sxs-lookup"><span data-stu-id="68da0-528">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="68da0-529">FastTrack-Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="68da0-529">FastTrack responsibilities</span></span>

<span data-ttu-id="68da0-530">Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="68da0-530">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="68da0-531">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="68da0-531">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="68da0-532">Ihre Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="68da0-532">Your responsibilities</span></span>

<span data-ttu-id="68da0-533">Während des Migrationsprojekts führen Sie Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="68da0-533">You perform standard activities during the migration project.</span></span> <span data-ttu-id="68da0-534">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="68da0-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="68da0-535">Sie führen außerdem die folgenden Aktivitäten speziell für OneDrive for Business-Migrationen aus:</span><span class="sxs-lookup"><span data-stu-id="68da0-535">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="68da0-536">Bereitstellen aller OneDrive for Business-Websites, die für Ihre Migrationsereignisse bestimmt sind.</span><span class="sxs-lookup"><span data-stu-id="68da0-536">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
