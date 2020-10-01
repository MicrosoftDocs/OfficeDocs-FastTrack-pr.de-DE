---
title: Datenmigration
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 10/1/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Sie können die Migration von E-Mail- und Dateidaten in ihrer Quellumgebung auf Office 365 (Exchange Online, SharePoint Online und OneDrive for Business) mithilfe von FastTrack migrieren. Die Art der von uns bereitgestellten Unterstützung hängt von der Anzahl der Office 365-Lizenzen ab.
ms.openlocfilehash: a8bb82e5a0409c52fe2603d33a4412182288f24a
ms.sourcegitcommit: c2bf382289217ef12913ef3419e6378716fd411a
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/30/2020
ms.locfileid: "48319947"
---
# <a name="data-migration"></a><span data-ttu-id="5b735-104">Datenmigration</span><span class="sxs-lookup"><span data-stu-id="5b735-104">Data Migration</span></span>

<span data-ttu-id="5b735-105">Sie können die Migration von E-Mail- und Dateidaten in ihrer Quellumgebung auf Office 365 (Exchange Online, SharePoint Online und OneDrive for Business) mithilfe von FastTrack migrieren.</span><span class="sxs-lookup"><span data-stu-id="5b735-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="5b735-106">Die Art der von uns bereitgestellten Unterstützung hängt von der Anzahl der Office 365-Lizenzen ab:</span><span class="sxs-lookup"><span data-stu-id="5b735-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="5b735-107">**Für Office 365-Mandanten mit 150 bis 499-Lizenzen**: FastTrack bietet nur Migrationsanleitungen. Sie sind für die Durchführung der Datenmigration verantwortlich.</span><span class="sxs-lookup"><span data-stu-id="5b735-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="5b735-108">Wir führen Sie durch die Dokumentation, die Ihnen hilft, ﻿kostenlose Tools für die Durchführung einer Self-Service-Migration zu planen und zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="5b735-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="5b735-109">**Für Office 365-Mandanten mit 500 oder mehr Lizenzen**: FastTrack bietet Migrationsanleitungen und Datenmigrationsdienste.</span><span class="sxs-lookup"><span data-stu-id="5b735-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="5b735-110">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des Office 365-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Daten.</span><span class="sxs-lookup"><span data-stu-id="5b735-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="5b735-111">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="5b735-111">You create and schedule your migration events.</span></span> <span data-ttu-id="5b735-112">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="5b735-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="5b735-113">Wenn Sie einen kommerziellen Plan vor dem 1.9.2017 erworben oder verlängert haben, benötigen Sie nur 150 Lizenzen, um für Datenmigrationsdienste qualifiziert zu sein.</span><span class="sxs-lookup"><span data-stu-id="5b735-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="5b735-114">Bei Plänen für Bildungseinrichtungen sind nur Lehrpersonal und Mitarbeiter für Migrationsdienste berechtigt.</span><span class="sxs-lookup"><span data-stu-id="5b735-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="5b735-115">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="5b735-115">Considerations</span></span>

  - <span data-ttu-id="5b735-116">Ihre Quellumgebungen müssen bestimmte Erwartungen erfüllen, um Daten zu Office 365 zu migrieren.</span><span class="sxs-lookup"><span data-stu-id="5b735-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="5b735-117">Weitere Informationen zu den Erwartungen bezüglich der Quellumgebung für Exchange, SharePoint und OneDrive for Business finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="5b735-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="5b735-118">Für die Bereitstellung von Datenmigrationsdiensten benötigen wir einen geeigneten Zugriff auf Ihre Quellumgebungen und den Office 365-Mandanten.</span><span class="sxs-lookup"><span data-stu-id="5b735-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="5b735-119">Unsere Datenmigrationsdienste sind nicht für Daten vorgesehen, die besonderen rechtlichen oder behördlichen Vorschriften unterliegen.</span><span class="sxs-lookup"><span data-stu-id="5b735-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="5b735-120">Wenn wir Ihre Daten migrieren, können sie an einen beliebigen Ort, an dem wir über Einrichtungen verfügen, übertragen, dort gespeichert und verarbeitet werden (sofern nicht anderweitig für Ihr FastTrack-Migrationsprojekt angegeben).</span><span class="sxs-lookup"><span data-stu-id="5b735-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="5b735-121">Wir übernehmen keine Garantie für die Geschwindigkeit der E-Mail- oder Dateimigration.</span><span class="sxs-lookup"><span data-stu-id="5b735-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="5b735-122">Unvorhergesehene Probleme (wie unlesbare oder fehlerhafte Elemente in der Quellumgebung) verhindern möglicherweise, dass einige ihrer Datenelemente migriert werden können.</span><span class="sxs-lookup"><span data-stu-id="5b735-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="5b735-123">Externe Faktoren, die außerhalb unserer Kontrolle stehen (z. B. Änderungen an den Programmierschnittstellen von Drittanbietern) können zu Änderungen, Verzögerungen oder der Sperrung unserer Datenmigrationsdienste führen.</span><span class="sxs-lookup"><span data-stu-id="5b735-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="5b735-124">Verfügbarkeit des Migrationsdiensts</span><span class="sxs-lookup"><span data-stu-id="5b735-124">Migration service availability</span></span>

  - <span data-ttu-id="5b735-125">**Für kommerzielle Kunden und britische Behörden:** Wir stellen Datenmigrationsdienste rund um die Uhr an sieben (7) Tagen pro Woche bereit.</span><span class="sxs-lookup"><span data-stu-id="5b735-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="5b735-126">**Für Kunden von US-amerikanischen Behörden/Verteidigungsministerium:** Wir stellen Datenmigrationsdienste rund um die Uhr an fünf (5) Werktagen pro Woche bereit.</span><span class="sxs-lookup"><span data-stu-id="5b735-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="5b735-127">Migration zu Exchange Online</span><span class="sxs-lookup"><span data-stu-id="5b735-127">Migration to Exchange Online</span></span>

<span data-ttu-id="5b735-128">Wenn Sie sich für die Migration Ihrer E-Mails zu Exchange Online mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit.</span><span class="sxs-lookup"><span data-stu-id="5b735-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="5b735-129">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des Exchange Online-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Postfächer.</span><span class="sxs-lookup"><span data-stu-id="5b735-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="5b735-130">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="5b735-130">You create and schedule your migration events.</span></span> <span data-ttu-id="5b735-131">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="5b735-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="5b735-132">Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass E-Mail-Nachrichten von entsprechend geplanten und berechtigten Quellpostfächern ihrer Quellumgebungen zu Exchange Online migriert wurden.</span><span class="sxs-lookup"><span data-stu-id="5b735-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="5b735-133">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="5b735-133">Considerations</span></span>

  - <span data-ttu-id="5b735-134">Bevor Sie die Migration durchführen können, müssen Sie den FastTrack-Onboarding-Vorgang für Exchange Online durchführen.</span><span class="sxs-lookup"><span data-stu-id="5b735-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="5b735-135">Wenn Sie das Onboarding selbst durchgeführt haben, müssen Sie die erforderlichen Überprüfungen und Voraussetzungen erfüllen.</span><span class="sxs-lookup"><span data-stu-id="5b735-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="5b735-136">Ausführliche Informationen finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="5b735-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="5b735-137">FastTrack migriert nur zu aktiven Office 365-Postfächern.</span><span class="sxs-lookup"><span data-stu-id="5b735-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="5b735-138">Sie müssen bestimmte Anforderungen erfüllen, wenn Sie von einer lokalen Exchange-Umgebung migrieren möchten.</span><span class="sxs-lookup"><span data-stu-id="5b735-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="5b735-139">Weitere Informationen finden Sie unter [Voraussetzungen für die Hybridbereitstellung](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="5b735-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="5b735-140">Sämtliche Quellumgebungen müssen über die neuesten Service Packs (SP) verfügen und auf der Rollup (RU)-/Kumulativen Update (KU)-Ebene für das entsprechende Produkt in der Quellumgebung vorhanden sein.</span><span class="sxs-lookup"><span data-stu-id="5b735-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="5b735-141">Verteilerlisten (*MailEnabledGroup*-Objekte) und externe Kontakte (*MailEnabledContact*-Objekte) im lokalen Active Directory befinden, sind nicht Bestandteil einer Postfachdatenmigration.</span><span class="sxs-lookup"><span data-stu-id="5b735-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="5b735-142">Sie können Sie jedoch mithilfe von Azure Active Directory (Azure AD) Connect synchronisieren.</span><span class="sxs-lookup"><span data-stu-id="5b735-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="5b735-143">Quellumgebungen</span><span class="sxs-lookup"><span data-stu-id="5b735-143">Source environments</span></span>

<span data-ttu-id="5b735-144">Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:</span><span class="sxs-lookup"><span data-stu-id="5b735-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="5b735-145">aus einer einzelnen oder aus mehreren Active Directory-Gesamtstrukturen mit einer oder mehreren Exchange-Organisationen (jedes Exchange-E-Mail-System muss Exchange 2010 oder höher sein).</span><span class="sxs-lookup"><span data-stu-id="5b735-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="5b735-146">aus einer einzelnen IMAP-fähigen E-Mail-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="5b735-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="5b735-147">aus einer G Suite-Umgebung (nur Gmail, Kontakte und Kalender).</span><span class="sxs-lookup"><span data-stu-id="5b735-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="5b735-148">Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:</span><span class="sxs-lookup"><span data-stu-id="5b735-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="5b735-149"><strong>Quellumgebung</strong></span><span class="sxs-lookup"><span data-stu-id="5b735-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="5b735-150"><strong>Migrationstyp</strong></span><span class="sxs-lookup"><span data-stu-id="5b735-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="5b735-151"><strong>Was wird migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="5b735-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="5b735-152"><strong>Was wird nicht migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="5b735-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="5b735-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="5b735-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="5b735-154">
<strong>Hinweis:</strong> Informationen zu lokalen Exchange-Abhängigkeiten finden Sie unter  <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Voraussetzungen für die Hybridbereitstellung</span></a>.</span><span class="sxs-lookup"><span data-stu-id="5b735-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="5b735-155">Migration mit Hybridbereitstellung</span><span class="sxs-lookup"><span data-stu-id="5b735-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="5b735-156">E-Mails</span><span class="sxs-lookup"><span data-stu-id="5b735-156">Emails</span></span></li>
<li><span data-ttu-id="5b735-157">Postfachregeln</span><span class="sxs-lookup"><span data-stu-id="5b735-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="5b735-158">Stellvertretungen</span><span class="sxs-lookup"><span data-stu-id="5b735-158">Delegates</span></span></li>
<li><span data-ttu-id="5b735-159">Postfachkontakte</span><span class="sxs-lookup"><span data-stu-id="5b735-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="5b735-160">Kalender</span><span class="sxs-lookup"><span data-stu-id="5b735-160">Calendar</span></span> </li>
<li> <span data-ttu-id="5b735-161">Aufgaben</span><span class="sxs-lookup"><span data-stu-id="5b735-161">Tasks</span></span> </li>
<li> <span data-ttu-id="5b735-162">E-Mails mit Rechteverwaltung</span><span class="sxs-lookup"><span data-stu-id="5b735-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="5b735-163">Verschlüsselte E-Mails</span><span class="sxs-lookup"><span data-stu-id="5b735-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="5b735-164">Signaturen</span><span class="sxs-lookup"><span data-stu-id="5b735-164">Signatures</span></span> </li>
<li> <span data-ttu-id="5b735-165">Persönliches Archiv, das mit dem Benutzerpostfach migriert wird</span><span class="sxs-lookup"><span data-stu-id="5b735-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="5b735-166">Wiederherstellbare Elemente</span><span class="sxs-lookup"><span data-stu-id="5b735-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5b735-167">Öffentliche Ordner</span><span class="sxs-lookup"><span data-stu-id="5b735-167">Public folders</span></span> </li>
<li> <span data-ttu-id="5b735-168">E-Mail, die die zulässige Nachrichtengröße überschreitet.</span><span class="sxs-lookup"><span data-stu-id="5b735-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="5b735-169">Journalarchiv oder eine beliebige Archivlösung von Drittanbietern</span><span class="sxs-lookup"><span data-stu-id="5b735-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="5b735-170">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="5b735-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="5b735-171">Archivdaten aus PST-Dateien</span><span class="sxs-lookup"><span data-stu-id="5b735-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="5b735-172">Beschädigte Elemente</span><span class="sxs-lookup"><span data-stu-id="5b735-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="5b735-173">Inaktive Postfächer</span><span class="sxs-lookup"><span data-stu-id="5b735-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b735-174"><strong>G Suite-Umgebung (nur Gmail, Kontakte und Kalender)</strong></span><span class="sxs-lookup"><span data-stu-id="5b735-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="5b735-175">
<strong>Hinweis:</strong> Ihre G Suite-Umgebung muss die Voraussetzungen erfüllen, die unter <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Durchführen einer G Suite-Migration</a> beschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="5b735-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="5b735-176">Übernahmemigration oder mehrstufige Migration</span><span class="sxs-lookup"><span data-stu-id="5b735-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="5b735-177">E-Mails</span><span class="sxs-lookup"><span data-stu-id="5b735-177">Emails</span></span> </li>
<li> <span data-ttu-id="5b735-178">Postfachkontakte (es werden maximal drei E-Mail-Adressen pro Kontakt migriert)</span><span class="sxs-lookup"><span data-stu-id="5b735-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="5b735-179">Kalender</span><span class="sxs-lookup"><span data-stu-id="5b735-179">Calendar</span></span> </li>
<li> <span data-ttu-id="5b735-180">Bezeichnungen</span><span class="sxs-lookup"><span data-stu-id="5b735-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5b735-181">Regeln</span><span class="sxs-lookup"><span data-stu-id="5b735-181">Rules</span></span> </li>
<li> <span data-ttu-id="5b735-182">Stellvertretungen</span><span class="sxs-lookup"><span data-stu-id="5b735-182">Delegates</span></span> </li>
<li> <span data-ttu-id="5b735-183">Signaturen</span><span class="sxs-lookup"><span data-stu-id="5b735-183">Signatures</span></span> </li>
<li> <span data-ttu-id="5b735-184">Aufgaben</span><span class="sxs-lookup"><span data-stu-id="5b735-184">Tasks</span></span> </li>
<li> <span data-ttu-id="5b735-185">E-Mails oder Anhänge, die die zulässige Nachrichtengröße überschreiten</span><span class="sxs-lookup"><span data-stu-id="5b735-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="5b735-186">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="5b735-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="5b735-187">Archivdaten aus PST-Dateien oder einer Drittanbieter-Archivlösung (z. B. Google Vault)</span><span class="sxs-lookup"><span data-stu-id="5b735-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="5b735-188">E-Mails mit Rechteverwaltung oder Verschlüsselung</span><span class="sxs-lookup"><span data-stu-id="5b735-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="5b735-189">Beschädigte Elemente</span><span class="sxs-lookup"><span data-stu-id="5b735-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="5b735-190">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="5b735-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="5b735-191">Google-Gruppen</span><span class="sxs-lookup"><span data-stu-id="5b735-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="5b735-192">Ressourcenpostfächer</span><span class="sxs-lookup"><span data-stu-id="5b735-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="5b735-193">Inaktive Postfächer</span><span class="sxs-lookup"><span data-stu-id="5b735-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="5b735-194">Urlaubseinstellungen und Einstellungen für automatische Antworten</span><span class="sxs-lookup"><span data-stu-id="5b735-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="5b735-195">Freigegebene Kalender, Cloudanlagen, Google Hangout-Links und Ereignisfarben</span><span class="sxs-lookup"><span data-stu-id="5b735-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="5b735-196">\*\*Hangout-Unterhaltungen, die als Beschriftungen gespeichert wurden, werden migriert.</span><span class="sxs-lookup"><span data-stu-id="5b735-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b735-197"><strong>IMAP4-Quelle (wie Domino, GroupWise oder Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="5b735-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="5b735-198">Migration mit systemeigenen IMAP4-Tools</span><span class="sxs-lookup"><span data-stu-id="5b735-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="5b735-199">E-Mails</span><span class="sxs-lookup"><span data-stu-id="5b735-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="5b735-200">Regeln</span><span class="sxs-lookup"><span data-stu-id="5b735-200">Rules</span></span> </li>
<li> <span data-ttu-id="5b735-201">Stellvertretungen</span><span class="sxs-lookup"><span data-stu-id="5b735-201">Delegates</span></span> </li>
<li> <span data-ttu-id="5b735-202">Verteilerlisten</span><span class="sxs-lookup"><span data-stu-id="5b735-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="5b735-203">Externe Kontakte</span><span class="sxs-lookup"><span data-stu-id="5b735-203">External contacts</span></span> </li>
<li> <span data-ttu-id="5b735-204">E-Mail-aktivierte Benutzer</span><span class="sxs-lookup"><span data-stu-id="5b735-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="5b735-205">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="5b735-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="5b735-206">Postfachkontakte</span><span class="sxs-lookup"><span data-stu-id="5b735-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="5b735-207">Kalender</span><span class="sxs-lookup"><span data-stu-id="5b735-207">Calendar</span></span> </li>
<li> <span data-ttu-id="5b735-208">Signaturen</span><span class="sxs-lookup"><span data-stu-id="5b735-208">Signatures</span></span> </li>
<li> <span data-ttu-id="5b735-209">Aufgaben</span><span class="sxs-lookup"><span data-stu-id="5b735-209">Tasks</span></span> </li>
<li> <span data-ttu-id="5b735-210">E-Mails, die die zulässige Nachrichtengröße überschreiten</span><span class="sxs-lookup"><span data-stu-id="5b735-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="5b735-211">Archivdaten</span><span class="sxs-lookup"><span data-stu-id="5b735-211">Archive data</span></span> </li>
<li> <span data-ttu-id="5b735-212">Verschlüsselte E-Mail-Nachrichten</span><span class="sxs-lookup"><span data-stu-id="5b735-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="5b735-213">Beschädigte Elemente</span><span class="sxs-lookup"><span data-stu-id="5b735-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="5b735-214">Inaktive Postfächer</span><span class="sxs-lookup"><span data-stu-id="5b735-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="5b735-215">FastTrack-Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="5b735-215">FastTrack responsibilities</span></span>

<span data-ttu-id="5b735-216">Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="5b735-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="5b735-217">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="5b735-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="5b735-218">Unsere FastTrack-Spezialisten führen außerdem die folgenden Aktivitäten speziell für Exchange-Migrationen durch:</span><span class="sxs-lookup"><span data-stu-id="5b735-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="5b735-219">Bereitstellen von Anleitungen, die Ihnen dabei helfen, die Koexistenz von SMTP-E-Mail-Routing zwischen Ihrer Quellumgebung und Exchange Online zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="5b735-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="5b735-220">Ihre Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="5b735-220">Your responsibilities</span></span>

<span data-ttu-id="5b735-221">Während des Migrationsprojekts führen Sie Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="5b735-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="5b735-222">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="5b735-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="5b735-223">Sie führen außerdem die folgenden Aktivitäten speziell für Exchange-Migrationen aus:</span><span class="sxs-lookup"><span data-stu-id="5b735-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="5b735-224">Durchführen des FastTrack-Onboarding-Vorgangs für Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="5b735-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="5b735-225">Wenn Sie das Onboarding selbst durchgeführt haben, müssen Sie die erforderlichen Überprüfungen und Voraussetzungen erfüllen.</span><span class="sxs-lookup"><span data-stu-id="5b735-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="5b735-226">Ausführliche Informationen finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="5b735-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="5b735-227">Installieren der entsprechenden Clientsoftwareebene gemäß den Office 365-Richtlinien.</span><span class="sxs-lookup"><span data-stu-id="5b735-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="5b735-228">Details finden Sie unter [Der moderne Arbeitsplatz](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="5b735-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="5b735-229">Erfüllen bestimmter Anforderungen, wenn Sie von einer lokalen Exchange-Umgebung migrieren möchten.</span><span class="sxs-lookup"><span data-stu-id="5b735-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="5b735-230">Weitere Informationen finden Sie unter [Voraussetzungen für die Hybridbereitstellung](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="5b735-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="5b735-231">Sicherstellen, dass jede Quellumgebung über das neueste Service Pack (SP) und Rollup (RU)/Cumulative Update (CU) verfügt, sofern zutreffend.</span><span class="sxs-lookup"><span data-stu-id="5b735-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="5b735-232">Konfigurieren und Validieren der Koexistenz von SMTP-E-Mail-Routing zwischen Ihrer Quellumgebung und Exchange Online, sofern zutreffend.</span><span class="sxs-lookup"><span data-stu-id="5b735-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="5b735-233">Sicherstellen, dass die Größe des Quellpostfachs das Zielpostfachkontingent nicht überschreitet.</span><span class="sxs-lookup"><span data-stu-id="5b735-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="5b735-234">Abhängig von der Quellplattform müssen Sie möglicherweise Ihre Quelldaten auf 85 % des Zielpostfachkontingents beschränken.</span><span class="sxs-lookup"><span data-stu-id="5b735-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="5b735-235">Ggf. Migrieren clientseitiger Daten.</span><span class="sxs-lookup"><span data-stu-id="5b735-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="5b735-236">Dies umfasst unter anderem lokale Adressbücher, Daten in lokalen PST-Dateien, Outlook-Regeln und lokale Outlook-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="5b735-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="5b735-237">Unterstützen Ihrer Endbenutzer bei der Behebung von Problemen bei der clientbasierten Migration.</span><span class="sxs-lookup"><span data-stu-id="5b735-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="5b735-238">Migration zu SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="5b735-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="5b735-239">Wenn Sie sich für die Migration Ihrer Dateien zu SharePoint Online mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit.</span><span class="sxs-lookup"><span data-stu-id="5b735-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="5b735-240">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des SharePoint Online-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Dateien.</span><span class="sxs-lookup"><span data-stu-id="5b735-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="5b735-241">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="5b735-241">You create and schedule your migration events.</span></span> <span data-ttu-id="5b735-242">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="5b735-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="5b735-243">Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass Dateien von entsprechend geplanten und berechtigten Quellen ihrer Quellumgebungen zu SharePoint Online migriert wurden.</span><span class="sxs-lookup"><span data-stu-id="5b735-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="5b735-244">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="5b735-244">Considerations</span></span>

  - <span data-ttu-id="5b735-245">Alle Migrationen unterliegen SharePoint Online-Kontingenten.</span><span class="sxs-lookup"><span data-stu-id="5b735-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="5b735-246">Weitere Informationen finden Sie unter [<span class="underline">SharePoint Online und OneDrive for Business: Softwarelimits und -beschränkungen</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="5b735-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="5b735-247">Der Gesamtbetrag sollte auf 75 Prozent des SharePoint Online-Gesamtspeicherkontingents, für das Sie berechtigt sind, beschränkt werden (einschließlich den zusätzlichen Speicher, den Sie möglicherweise separat gekauft haben).</span><span class="sxs-lookup"><span data-stu-id="5b735-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="5b735-248">Detail der Quellumgebung</span><span class="sxs-lookup"><span data-stu-id="5b735-248">Source environment details</span></span>

<span data-ttu-id="5b735-249">Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:</span><span class="sxs-lookup"><span data-stu-id="5b735-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="5b735-250">Dateifreigaben (SMB [Server Message Block]-Dateifreigaben auf Geräten mit Unterstützung für SMB 2.0 und höher)</span><span class="sxs-lookup"><span data-stu-id="5b735-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="5b735-251">Eine einzelne G Suite-Umgebung (nur Google Drive).</span><span class="sxs-lookup"><span data-stu-id="5b735-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="5b735-252">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="5b735-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="5b735-253">Dropbox für Teams (Standard und Erweitert).</span><span class="sxs-lookup"><span data-stu-id="5b735-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="5b735-254">Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:</span><span class="sxs-lookup"><span data-stu-id="5b735-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="5b735-255"><strong>Quellumgebung</strong></span><span class="sxs-lookup"><span data-stu-id="5b735-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="5b735-256"><strong>Migrationstyp</strong></span><span class="sxs-lookup"><span data-stu-id="5b735-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="5b735-257"><strong>Was wird migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="5b735-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="5b735-258"><strong>Was wird nicht migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="5b735-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="5b735-259"><strong>Alle Dateifreigabegeräte mit Unterstützung für SMB 2.0 und höher</strong></span><span class="sxs-lookup"><span data-stu-id="5b735-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="5b735-260">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="5b735-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5b735-261">Dokumente</span><span class="sxs-lookup"><span data-stu-id="5b735-261">Documents</span></span> </li>
<li> <span data-ttu-id="5b735-262">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="5b735-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5b735-263">Datei- und Ordnerberechtigungen auf Benutzerebene\*</span><span class="sxs-lookup"><span data-stu-id="5b735-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="5b735-264">Datei- und Ordnerberechtigungen auf Gruppenebene\*</span><span class="sxs-lookup"><span data-stu-id="5b735-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="5b735-265">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="5b735-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5b735-266">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="5b735-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5b735-267">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="5b735-267">Created date</span></span> </li>
<li> <span data-ttu-id="5b735-268">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="5b735-268">Modified date</span></span> </li>
<li> <span data-ttu-id="5b735-269">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="5b735-269">Created by</span></span> </li>
<li> <span data-ttu-id="5b735-270">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="5b735-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="5b735-271">\* Setzt die Konfiguration der Verzeichnissynchronisierung voraus.</span><span class="sxs-lookup"><span data-stu-id="5b735-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="5b735-272">Es werden nur NTFS-Berechtigungen migriert, die für den Windows-Datei-Explorer verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="5b735-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="5b735-273">Berechtigungen, die direkt auf Dateifreigabegeräten verwaltet werden, werden nicht migriert.</span><span class="sxs-lookup"><span data-stu-id="5b735-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="5b735-274">Wenn Daten auf einem SMB 2.0-Gerät gespeichert werden, werden die NTFS-äquivalenten Berechtigungen, die vom SMB-Protokoll verfügbar gemacht werden, migriert.</span><span class="sxs-lookup"><span data-stu-id="5b735-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="5b735-275">Aufgezeichnete Eigentümerschaft und frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="5b735-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="5b735-276">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="5b735-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5b735-277">Frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="5b735-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="5b735-278">Windows-Datei-/-Ordnerattribute (z. B. „Schreibgeschützt“ und „Ausgeblendet“) </span><span class="sxs-lookup"><span data-stu-id="5b735-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="5b735-279">Nicht-Windows-NTFS-Dateisystem (New Technology File System) und erweiterte NTFS-Berechtigungen sowie besondere Einstellungen:</span><span class="sxs-lookup"><span data-stu-id="5b735-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="5b735-280">Explizite Verweigerungsberechtigungen (werden nach der Migration entfernt, Inhalte unterliegen parallelen Berechtigungen oder Berechtigungen im übergeordneten Ordner).</span><span class="sxs-lookup"><span data-stu-id="5b735-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="5b735-281">Konfiguration der NTFS-Überwachung</span><span class="sxs-lookup"><span data-stu-id="5b735-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="5b735-282">Zusätzliche Dateimetadaten von der Dateiklassifizierungsinfrastruktur (File Classification Infrastructure, FCI)</span><span class="sxs-lookup"><span data-stu-id="5b735-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="5b735-283">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="5b735-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5b735-284">Ausgeblendete Freigaben</span><span class="sxs-lookup"><span data-stu-id="5b735-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="5b735-285">Freigabe (z. B. gewährte Berechtigungen auf Freigabeebene)</span><span class="sxs-lookup"><span data-stu-id="5b735-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="5b735-286">Dateien oder Ordner, die die aktuellen  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Einschränkungen und Begrenzen von SharePoint Online</span></a>  überschreiten</span><span class="sxs-lookup"><span data-stu-id="5b735-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b735-287"><strong>Einzelne G Suite-Umgebung (nur Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="5b735-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="5b735-288">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="5b735-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5b735-289">Google Docs, Google Tabellen und Google Präsentationen (Dateien werden in das entsprechende Office-Format konvertiert), einschließlich derjenigen über 10 MB</span><span class="sxs-lookup"><span data-stu-id="5b735-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="5b735-290">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="5b735-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5b735-291">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5b735-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5b735-292">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5b735-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5b735-293">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="5b735-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5b735-294">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="5b735-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5b735-295">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="5b735-295">Created date</span></span> </li>
<li> <span data-ttu-id="5b735-296">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="5b735-296">Modified date</span></span> </li>
<li> <span data-ttu-id="5b735-297">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="5b735-297">Created by</span></span> </li>
<li> <span data-ttu-id="5b735-298">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="5b735-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="5b735-299">Freigegebene Laufwerke (Ordner und Dateien)</span><span class="sxs-lookup"><span data-stu-id="5b735-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="5b735-300">Geteilte Inhalte, die im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="5b735-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5b735-301">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="5b735-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="5b735-302">Beschreibungen von Dateien und Ordnern, Ordnerfarben</span><span class="sxs-lookup"><span data-stu-id="5b735-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="5b735-303">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5b735-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="5b735-304">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5b735-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="5b735-305">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="5b735-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="5b735-306">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="5b735-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="5b735-307">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="5b735-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5b735-308">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="5b735-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="5b735-309">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="5b735-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5b735-310">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="5b735-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="5b735-311">Google Fotos, Google Formulare, Google Maps und andere verbundene Apps</span><span class="sxs-lookup"><span data-stu-id="5b735-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="5b735-312">Google Zeichnungen</span><span class="sxs-lookup"><span data-stu-id="5b735-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="5b735-313">Freigegebene Inhalte außerhalb Ihrer Organisation</span><span class="sxs-lookup"><span data-stu-id="5b735-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="5b735-314">Inhalte, die nicht im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="5b735-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="5b735-315">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Google Drive-Administratorberichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="5b735-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="5b735-316">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="5b735-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="5b735-317">Mitgliedschaftsberechtigungen für freigegebene Laufwerke (<strong>Hinweis</strong>: Verwenden Sie die Google Drive-Administratorberichte, um die Mitgliedschaften für freigegebene Laufwerke zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="5b735-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="5b735-318">Weisen Sie die Endbenutzer an, diese Mitgliedschaftseinstellungen auf dem Ziel vor der Migration zu konfigurieren.)</span><span class="sxs-lookup"><span data-stu-id="5b735-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="5b735-319">Dateien, die als eingeschränkt oder nicht kopierbar gekennzeichnet sind</span><span class="sxs-lookup"><span data-stu-id="5b735-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="5b735-320">Dateien oder Ordner, die die aktuellen  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Einschränkungen und Begrenzen von SharePoint Online</span></a>  überschreiten</span><span class="sxs-lookup"><span data-stu-id="5b735-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b735-321"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="5b735-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="5b735-322">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="5b735-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5b735-323">Dokumente</span><span class="sxs-lookup"><span data-stu-id="5b735-323">Documents</span></span> </li>
<li> <span data-ttu-id="5b735-324">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="5b735-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5b735-325">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5b735-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5b735-326">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5b735-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5b735-327">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="5b735-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5b735-328">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="5b735-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5b735-329">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="5b735-329">Created date</span></span> </li>
<li> <span data-ttu-id="5b735-330">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="5b735-330">Modified date</span></span> </li>
<li> <span data-ttu-id="5b735-331">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="5b735-331">Created by</span></span> </li>
<li> <span data-ttu-id="5b735-332">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="5b735-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="5b735-333">Geteilte Inhalte, die im Besitz des Box-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="5b735-333">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5b735-334">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="5b735-334">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="5b735-335">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="5b735-335">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="5b735-336">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5b735-336">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="5b735-337">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5b735-337">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="5b735-338">Box-Tags und erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="5b735-338">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="5b735-339">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="5b735-339">File lock attributes</span></span> </li>
<li> <span data-ttu-id="5b735-340">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="5b735-340">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5b735-341">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="5b735-341">Trashed items</span></span> </li>
<li> <span data-ttu-id="5b735-342">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="5b735-342">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5b735-343">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="5b735-343">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="5b735-344">Box-Apps, Lesezeichen, Favoriten und Workflows</span><span class="sxs-lookup"><span data-stu-id="5b735-344">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="5b735-345">Inhalte, die nicht im Besitz des migrierten Box-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="5b735-345">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="5b735-346">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Box-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="5b735-346">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="5b735-347">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="5b735-347">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="5b735-348">Dateien oder Ordner, die die aktuellen  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Einschränkungen und Begrenzen von SharePoint Online</span></a>  überschreiten</span><span class="sxs-lookup"><span data-stu-id="5b735-348">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b735-349"><strong>Dropbox für Teams (Standard und Erweitert)</strong></span><span class="sxs-lookup"><span data-stu-id="5b735-349"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="5b735-350">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="5b735-350">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5b735-351">Dokumente</span><span class="sxs-lookup"><span data-stu-id="5b735-351">Documents</span></span> </li>
<li> <span data-ttu-id="5b735-352">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="5b735-352">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5b735-353">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5b735-353">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5b735-354">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5b735-354">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5b735-355">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="5b735-355">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5b735-356">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="5b735-356">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5b735-357">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="5b735-357">Created date</span></span> </li>
<li> <span data-ttu-id="5b735-358">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="5b735-358">Modified date</span></span> </li>
<li> <span data-ttu-id="5b735-359">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="5b735-359">Created by</span></span> </li>
<li> <span data-ttu-id="5b735-360">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="5b735-360">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="5b735-361">Freigegebene Teamordner und -inhalte</span><span class="sxs-lookup"><span data-stu-id="5b735-361">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="5b735-362">Geteilte Inhalte, die im Besitz des Dropbox-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="5b735-362">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5b735-363">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="5b735-363">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="5b735-364">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="5b735-364">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="5b735-365">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5b735-365">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="5b735-366">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5b735-366">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="5b735-367">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="5b735-367">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="5b735-368">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="5b735-368">File lock attributes</span></span> </li>
<li> <span data-ttu-id="5b735-369">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="5b735-369">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5b735-370">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="5b735-370">Trashed items</span></span> </li>
<li> <span data-ttu-id="5b735-371">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="5b735-371">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5b735-372">Nicht gemountete Dropbox-Ordner</span><span class="sxs-lookup"><span data-stu-id="5b735-372">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="5b735-373">Gelöschte oder getrennte Benutzer</span><span class="sxs-lookup"><span data-stu-id="5b735-373">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="5b735-374">Dropbox Paper, Showcases und Spaces</span><span class="sxs-lookup"><span data-stu-id="5b735-374">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="5b735-375">Dropbox-Apps und Favoriten (Pins/Sterne)</span><span class="sxs-lookup"><span data-stu-id="5b735-375">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="5b735-376">Inhalte, die nicht im Besitz des migrierten Dropbox-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="5b735-376">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="5b735-377">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Dropbox-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="5b735-377">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="5b735-378">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="5b735-378">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="5b735-379">Dateien oder Ordner, die die aktuellen  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Einschränkungen und Begrenzen von SharePoint Online</span></a>  überschreiten</span><span class="sxs-lookup"><span data-stu-id="5b735-379">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="5b735-380">FastTrack-Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="5b735-380">FastTrack responsibilities</span></span>

<span data-ttu-id="5b735-381">Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="5b735-381">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="5b735-382">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="5b735-382">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="5b735-383">Ihre Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="5b735-383">Your responsibilities</span></span>

<span data-ttu-id="5b735-384">Während des Migrationsprojekts führen Sie Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="5b735-384">You perform standard activities during the migration project.</span></span> <span data-ttu-id="5b735-385">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="5b735-385">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="5b735-386">Sie führen außerdem die folgenden Aktivitäten speziell für SharePoint Online-Migrationen aus:</span><span class="sxs-lookup"><span data-stu-id="5b735-386">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="5b735-387">Bereitstellen aller SharePoint-Teamwebsites, die für Ihre Migrationsereignisse vorgesehen sind.</span><span class="sxs-lookup"><span data-stu-id="5b735-387">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="5b735-388">Migration zu OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="5b735-388">Migration to OneDrive for Business</span></span>

<span data-ttu-id="5b735-389">Wenn Sie sich für die Migration Ihrer Dateien zu OneDrive for Business mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit.</span><span class="sxs-lookup"><span data-stu-id="5b735-389">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="5b735-390">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des OneDrive for Business-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Dateien.</span><span class="sxs-lookup"><span data-stu-id="5b735-390">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="5b735-391">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="5b735-391">You create and schedule your migration events.</span></span> <span data-ttu-id="5b735-392">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="5b735-392">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="5b735-393">Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass Dateien von entsprechend geplanten und berechtigten Quellen ihrer Quellumgebungen zu OneDrive for Business migriert wurden.</span><span class="sxs-lookup"><span data-stu-id="5b735-393">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="5b735-394">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="5b735-394">Considerations</span></span>

  - <span data-ttu-id="5b735-395">Alle Migrationen unterliegen den OneDrive for Business-Kontingenten.</span><span class="sxs-lookup"><span data-stu-id="5b735-395">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="5b735-396">Weitere Informationen finden Sie unter [<span class="underline">SharePoint Online und OneDrive for Business: Softwarelimits und -beschränkungen</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="5b735-396">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="5b735-397">Der Gesamtbetrag sollte auf 75 Prozent der Daten des SharePoint Online-Gesamtspeicherkontingents, für das Sie berechtigt sind, beschränkt werden (einschließlich den zusätzlichen Speicher, den Sie möglicherweise separat gekauft haben).</span><span class="sxs-lookup"><span data-stu-id="5b735-397">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="5b735-398">FastTrack migriert nur zu aktiven OneDrive for Business-Laufwerken.</span><span class="sxs-lookup"><span data-stu-id="5b735-398">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="5b735-399">Detail der Quellumgebung</span><span class="sxs-lookup"><span data-stu-id="5b735-399">Source environment details</span></span>

<span data-ttu-id="5b735-400">Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:</span><span class="sxs-lookup"><span data-stu-id="5b735-400">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="5b735-401">Dateifreigaben (SMB-Dateifreigaben auf Geräten mit Unterstützung für SMB 2.0 und höher)</span><span class="sxs-lookup"><span data-stu-id="5b735-401">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="5b735-402">Einzelne G Suite-Umgebung (nur Google Drive).</span><span class="sxs-lookup"><span data-stu-id="5b735-402">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="5b735-403">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="5b735-403">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="5b735-404">Dropbox für Teams (Standard und Erweitert).</span><span class="sxs-lookup"><span data-stu-id="5b735-404">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="5b735-405">Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:</span><span class="sxs-lookup"><span data-stu-id="5b735-405">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="5b735-406"><strong>Quellumgebung</strong></span><span class="sxs-lookup"><span data-stu-id="5b735-406"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="5b735-407"><strong>Migrationstyp</strong></span><span class="sxs-lookup"><span data-stu-id="5b735-407"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="5b735-408"><strong>Was wird migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="5b735-408"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="5b735-409"><strong>Was wird nicht migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="5b735-409"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="5b735-410"><strong>Alle Dateifreigabegeräte mit Unterstützung für SMB 2.0 und höher</strong></span><span class="sxs-lookup"><span data-stu-id="5b735-410"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="5b735-411">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="5b735-411">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5b735-412">Dokumente</span><span class="sxs-lookup"><span data-stu-id="5b735-412">Documents</span></span> </li>
<li> <span data-ttu-id="5b735-413">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="5b735-413">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5b735-414">Datei- und Ordnerberechtigungen auf Benutzerebene\*</span><span class="sxs-lookup"><span data-stu-id="5b735-414">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="5b735-415">Datei- und Ordnerberechtigungen auf Gruppenebene\*</span><span class="sxs-lookup"><span data-stu-id="5b735-415">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="5b735-416">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="5b735-416">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5b735-417">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="5b735-417">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5b735-418">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="5b735-418">Created date</span></span> </li>
<li> <span data-ttu-id="5b735-419">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="5b735-419">Modified date</span></span> </li>
<li> <span data-ttu-id="5b735-420">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="5b735-420">Created by</span></span> </li>
<li> <span data-ttu-id="5b735-421">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="5b735-421">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="5b735-422">\* Setzt die Konfiguration der Verzeichnissynchronisierung voraus.</span><span class="sxs-lookup"><span data-stu-id="5b735-422">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="5b735-423">Es werden nur NTFS-Berechtigungen migriert, die für den Windows-Datei-Explorer verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="5b735-423">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="5b735-424">Berechtigungen, die direkt auf Dateifreigabegeräten verwaltet werden, werden nicht migriert.</span><span class="sxs-lookup"><span data-stu-id="5b735-424">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="5b735-425">Wenn Daten auf einem SMB 2.0-Gerät gespeichert werden, werden die NTFS-äquivalenten Berechtigungen, die vom SMB-Protokoll verfügbar gemacht werden, migriert.</span><span class="sxs-lookup"><span data-stu-id="5b735-425">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="5b735-426">Aufgezeichnete Eigentümerschaft und frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="5b735-426">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="5b735-427">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="5b735-427">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5b735-428">Frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="5b735-428">Previous versions</span></span> </li>
<li> <span data-ttu-id="5b735-429">Windows-Datei-/-Ordnerattribute (z. B. „Schreibgeschützt“ und „Ausgeblendet“) </span><span class="sxs-lookup"><span data-stu-id="5b735-429">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="5b735-430">Nicht-Windows-NTFS-Dateisystem (New Technology File System) und erweiterte NTFS-Berechtigungen sowie besondere Einstellungen:</span><span class="sxs-lookup"><span data-stu-id="5b735-430">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="5b735-431">Explizite Verweigerungsberechtigungen (werden nach der Migration entfernt, Inhalte unterliegen parallelen Berechtigungen oder Berechtigungen im übergeordneten Ordner).</span><span class="sxs-lookup"><span data-stu-id="5b735-431">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="5b735-432">Konfiguration der NTFS-Überwachung</span><span class="sxs-lookup"><span data-stu-id="5b735-432">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="5b735-433">Zusätzliche Dateimetadaten von der Dateiklassifizierungsinfrastruktur (File Classification Infrastructure, FCI)</span><span class="sxs-lookup"><span data-stu-id="5b735-433">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="5b735-434">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="5b735-434">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5b735-435">Ausgeblendete Freigaben</span><span class="sxs-lookup"><span data-stu-id="5b735-435">Hidden shares</span></span> </li>
<li> <span data-ttu-id="5b735-436">Freigabe (z. B. gewährte Berechtigungen auf Freigabeebene)</span><span class="sxs-lookup"><span data-stu-id="5b735-436">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="5b735-437">Dateien oder Ordner, die die aktuellen  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Einschränkungen und Begrenzen von SharePoint Online</span></a>  überschreiten</span><span class="sxs-lookup"><span data-stu-id="5b735-437">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b735-438"><strong>Einzelne G Suite-Umgebung (nur Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="5b735-438"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="5b735-439">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="5b735-439">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5b735-440">Google Docs, Google Tabellen und Google Präsentationen (Dateien werden in das entsprechende Office-Format konvertiert, einschließlich derjenigen über 10 MB)</span><span class="sxs-lookup"><span data-stu-id="5b735-440">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="5b735-441">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="5b735-441">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5b735-442">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5b735-442">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5b735-443">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5b735-443">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5b735-444">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="5b735-444">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5b735-445">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="5b735-445">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5b735-446">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="5b735-446">Created date</span></span> </li>
<li> <span data-ttu-id="5b735-447">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="5b735-447">Modified date</span></span> </li>
<li> <span data-ttu-id="5b735-448">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="5b735-448">Created by</span></span> </li>
<li> <span data-ttu-id="5b735-449">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="5b735-449">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="5b735-450">Freigegebene Laufwerke (Ordner und Dateien)</span><span class="sxs-lookup"><span data-stu-id="5b735-450">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="5b735-451">Geteilte Inhalte, die im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="5b735-451">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5b735-452">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="5b735-452">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="5b735-453">Beschreibungen von Dateien und Ordnern, Ordnerfarben</span><span class="sxs-lookup"><span data-stu-id="5b735-453">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="5b735-454">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5b735-454">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="5b735-455">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5b735-455">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="5b735-456">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="5b735-456">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="5b735-457">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="5b735-457">File lock attributes</span></span> </li>
<li> <span data-ttu-id="5b735-458">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="5b735-458">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5b735-459">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="5b735-459">Trashed items</span></span> </li>
<li> <span data-ttu-id="5b735-460">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="5b735-460">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5b735-461">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="5b735-461">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="5b735-462">Google Fotos, Google Formulare, Google Maps und andere verbundene Apps</span><span class="sxs-lookup"><span data-stu-id="5b735-462">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="5b735-463">Google Zeichnungen</span><span class="sxs-lookup"><span data-stu-id="5b735-463">Google Drawings</span></span> </li>
<li> <span data-ttu-id="5b735-464">Freigegebene Inhalte außerhalb Ihrer Organisation</span><span class="sxs-lookup"><span data-stu-id="5b735-464">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="5b735-465">Inhalte, die nicht im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="5b735-465">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="5b735-466">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Google Drive-Administratorberichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="5b735-466">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="5b735-467">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="5b735-467">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="5b735-468">Mitgliedschaftsberechtigungen für freigegebene Laufwerke (<strong>Hinweis</strong>: Verwenden Sie die Google Drive-Administratorberichte, um die Mitgliedschaften für freigegebene Laufwerke zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="5b735-468">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="5b735-469">Weisen Sie die Endbenutzer an, diese Mitgliedschaftseinstellungen auf dem Ziel vor der Migration zu konfigurieren.)</span><span class="sxs-lookup"><span data-stu-id="5b735-469">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="5b735-470">Dateien oder Ordner, die die aktuellen  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Einschränkungen und Begrenzen von SharePoint Online</span></a>  überschreiten</span><span class="sxs-lookup"><span data-stu-id="5b735-470">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="5b735-471"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="5b735-471"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="5b735-472">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="5b735-472">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5b735-473">Dokumente</span><span class="sxs-lookup"><span data-stu-id="5b735-473">Documents</span></span> </li>
<li> <span data-ttu-id="5b735-474">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="5b735-474">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5b735-475">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5b735-475">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5b735-476">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5b735-476">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5b735-477">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="5b735-477">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5b735-478">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="5b735-478">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5b735-479">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="5b735-479">Created date</span></span> </li>
<li> <span data-ttu-id="5b735-480">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="5b735-480">Modified date</span></span> </li>
<li> <span data-ttu-id="5b735-481">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="5b735-481">Created by</span></span> </li>
<li> <span data-ttu-id="5b735-482">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="5b735-482">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="5b735-483">Geteilte Inhalte, die im Besitz des Box-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="5b735-483">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5b735-484">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="5b735-484">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="5b735-485">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="5b735-485">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="5b735-486">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5b735-486">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="5b735-487">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5b735-487">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="5b735-488">Box-Tags und erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="5b735-488">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="5b735-489">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="5b735-489">File lock attributes</span></span> </li>
<li> <span data-ttu-id="5b735-490">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="5b735-490">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5b735-491">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="5b735-491">Trashed items</span></span> </li>
<li> <span data-ttu-id="5b735-492">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="5b735-492">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5b735-493">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="5b735-493">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="5b735-494">Box-Apps, Lesezeichen, Favoriten und Workflows</span><span class="sxs-lookup"><span data-stu-id="5b735-494">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="5b735-495">Inhalte, die nicht im Besitz des migrierten Box-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="5b735-495">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="5b735-496">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Box-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="5b735-496">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="5b735-497">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="5b735-497">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="5b735-498">Dateien oder Ordner, die die aktuellen  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Einschränkungen und Begrenzen von SharePoint Online</span></a>  überschreiten</span><span class="sxs-lookup"><span data-stu-id="5b735-498">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="5b735-499"><strong>Dropbox für Teams (Standard und Erweitert)</strong></span><span class="sxs-lookup"><span data-stu-id="5b735-499"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="5b735-500">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="5b735-500">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="5b735-501">Dokumente</span><span class="sxs-lookup"><span data-stu-id="5b735-501">Documents</span></span> </li>
<li> <span data-ttu-id="5b735-502">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="5b735-502">File and folder structure</span></span> </li>
<li> <span data-ttu-id="5b735-503">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5b735-503">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5b735-504">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5b735-504">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="5b735-505">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="5b735-505">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="5b735-506">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="5b735-506">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="5b735-507">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="5b735-507">Created date</span></span> </li>
<li> <span data-ttu-id="5b735-508">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="5b735-508">Modified date</span></span> </li>
<li> <span data-ttu-id="5b735-509">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="5b735-509">Created by</span></span> </li>
<li> <span data-ttu-id="5b735-510">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="5b735-510">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="5b735-511">Freigegebene Teamordner und -inhalte</span><span class="sxs-lookup"><span data-stu-id="5b735-511">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="5b735-512">Geteilte Inhalte, die im Besitz des Dropbox-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="5b735-512">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="5b735-513">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="5b735-513">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="5b735-514">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="5b735-514">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="5b735-515">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="5b735-515">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="5b735-516">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="5b735-516">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="5b735-517">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="5b735-517">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="5b735-518">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="5b735-518">File lock attributes</span></span> </li>
<li> <span data-ttu-id="5b735-519">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="5b735-519">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="5b735-520">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="5b735-520">Trashed items</span></span> </li>
<li> <span data-ttu-id="5b735-521">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="5b735-521">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="5b735-522">Nicht gemountete Dropbox-Ordner</span><span class="sxs-lookup"><span data-stu-id="5b735-522">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="5b735-523">Gelöschte oder getrennte Benutzer</span><span class="sxs-lookup"><span data-stu-id="5b735-523">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="5b735-524">Dropbox Paper, Showcases und Spaces</span><span class="sxs-lookup"><span data-stu-id="5b735-524">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="5b735-525">Dropbox-Apps und Favoriten (Pins/Sterne)</span><span class="sxs-lookup"><span data-stu-id="5b735-525">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="5b735-526">Inhalte, die nicht im Besitz des migrierten Dropbox-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="5b735-526">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="5b735-527">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Dropbox-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="5b735-527">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="5b735-528">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="5b735-528">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="5b735-529">Dateien oder Ordner, die die aktuellen  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Einschränkungen und Begrenzen von SharePoint Online</span></a>  überschreiten</span><span class="sxs-lookup"><span data-stu-id="5b735-529">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="5b735-530">FastTrack-Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="5b735-530">FastTrack responsibilities</span></span>

<span data-ttu-id="5b735-531">Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="5b735-531">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="5b735-532">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="5b735-532">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="5b735-533">Ihre Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="5b735-533">Your responsibilities</span></span>

<span data-ttu-id="5b735-534">Während des Migrationsprojekts führen Sie Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="5b735-534">You perform standard activities during the migration project.</span></span> <span data-ttu-id="5b735-535">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="5b735-535">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="5b735-536">Sie führen außerdem die folgenden Aktivitäten speziell für OneDrive for Business-Migrationen aus:</span><span class="sxs-lookup"><span data-stu-id="5b735-536">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="5b735-537">Bereitstellen aller OneDrive for Business-Websites, die für Ihre Migrationsereignisse bestimmt sind.</span><span class="sxs-lookup"><span data-stu-id="5b735-537">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
