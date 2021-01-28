---
title: Datenmigration
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/27/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Sie können die Migration von E-Mail- und Dateidaten in ihrer Quellumgebung auf Office 365 (Exchange Online, SharePoint Online und OneDrive for Business) mithilfe von FastTrack migrieren. Die Art der von uns bereitgestellten Unterstützung hängt von der Anzahl der Office 365-Lizenzen ab.
ms.openlocfilehash: 0ecfdfab7c7f7ae8879ea6374c3560dcaeb2f283
ms.sourcegitcommit: cd8426ce64dda56439933576e7da75b1c27f5de1
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 01/27/2021
ms.locfileid: "50016471"
---
# <a name="data-migration"></a><span data-ttu-id="df3b2-104">Datenmigration</span><span class="sxs-lookup"><span data-stu-id="df3b2-104">Data Migration</span></span>

<span data-ttu-id="df3b2-105">Sie können die Migration von E-Mail- und Dateidaten in ihrer Quellumgebung auf Office 365 (Exchange Online, SharePoint Online und OneDrive for Business) mithilfe von FastTrack migrieren.</span><span class="sxs-lookup"><span data-stu-id="df3b2-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="df3b2-106">Die Art der von uns bereitgestellten Unterstützung hängt von der Anzahl der Office 365-Lizenzen ab:</span><span class="sxs-lookup"><span data-stu-id="df3b2-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="df3b2-107">**Für Office 365-Mandanten mit 150 bis 499-Lizenzen**: FastTrack bietet nur Migrationsanleitungen. Sie sind für die Durchführung der Datenmigration verantwortlich.</span><span class="sxs-lookup"><span data-stu-id="df3b2-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="df3b2-108">Wir führen Sie durch die Dokumentation, die Ihnen hilft, ﻿kostenlose Tools für die Durchführung einer Self-Service-Migration zu planen und zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="df3b2-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="df3b2-109">**Für Office 365-Mandanten mit 500 oder mehr Lizenzen**: FastTrack bietet Migrationsanleitungen und Datenmigrationsdienste.</span><span class="sxs-lookup"><span data-stu-id="df3b2-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="df3b2-110">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des Office 365-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Daten.</span><span class="sxs-lookup"><span data-stu-id="df3b2-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="df3b2-111">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="df3b2-111">You create and schedule your migration events.</span></span> <span data-ttu-id="df3b2-112">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="df3b2-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="df3b2-113">Wenn Sie einen kommerziellen Plan vor dem 1.9.2017 erworben oder verlängert haben, benötigen Sie nur 150 Lizenzen, um für Datenmigrationsdienste qualifiziert zu sein.</span><span class="sxs-lookup"><span data-stu-id="df3b2-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="df3b2-114">Bei Plänen für Bildungseinrichtungen sind nur Lehrpersonal und Mitarbeiter für Migrationsdienste berechtigt.</span><span class="sxs-lookup"><span data-stu-id="df3b2-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="df3b2-115">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="df3b2-115">Considerations</span></span>

  - <span data-ttu-id="df3b2-116">Ihre Quellumgebungen müssen bestimmte Erwartungen erfüllen, um Daten zu Office 365 zu migrieren.</span><span class="sxs-lookup"><span data-stu-id="df3b2-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="df3b2-117">Weitere Informationen zu den Erwartungen bezüglich der Quellumgebung für Exchange, SharePoint und OneDrive for Business finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="df3b2-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="df3b2-118">Für die Bereitstellung von Datenmigrationsdiensten benötigen wir einen geeigneten Zugriff auf Ihre Quellumgebungen und den Office 365-Mandanten.</span><span class="sxs-lookup"><span data-stu-id="df3b2-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="df3b2-119">Unsere Datenmigrationsdienste sind nicht für Daten vorgesehen, die besonderen rechtlichen oder behördlichen Vorschriften unterliegen.</span><span class="sxs-lookup"><span data-stu-id="df3b2-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="df3b2-120">Wenn wir Ihre Daten migrieren, können sie an einen beliebigen Ort, an dem wir über Einrichtungen verfügen, übertragen, dort gespeichert und verarbeitet werden (sofern nicht anderweitig für Ihr FastTrack-Migrationsprojekt angegeben).</span><span class="sxs-lookup"><span data-stu-id="df3b2-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="df3b2-121">Wir übernehmen keine Garantie für die Geschwindigkeit der E-Mail- oder Dateimigration.</span><span class="sxs-lookup"><span data-stu-id="df3b2-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="df3b2-122">Unvorhergesehene Probleme (wie unlesbare oder fehlerhafte Elemente in der Quellumgebung) verhindern möglicherweise, dass einige ihrer Datenelemente migriert werden können.</span><span class="sxs-lookup"><span data-stu-id="df3b2-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="df3b2-123">Externe Faktoren, die außerhalb unserer Kontrolle stehen (z. B. Änderungen an den Programmierschnittstellen von Drittanbietern) können zu Änderungen, Verzögerungen oder der Sperrung unserer Datenmigrationsdienste führen.</span><span class="sxs-lookup"><span data-stu-id="df3b2-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="df3b2-124">Verfügbarkeit des Migrationsdiensts</span><span class="sxs-lookup"><span data-stu-id="df3b2-124">Migration service availability</span></span>

  - <span data-ttu-id="df3b2-125">**Für kommerzielle Kunden und britische Behörden:** Wir stellen Datenmigrationsdienste rund um die Uhr an sieben (7) Tagen pro Woche bereit.</span><span class="sxs-lookup"><span data-stu-id="df3b2-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="df3b2-126">**Für Kunden von US-amerikanischen Behörden/Verteidigungsministerium:** Wir stellen Datenmigrationsdienste rund um die Uhr an fünf (5) Werktagen pro Woche bereit.</span><span class="sxs-lookup"><span data-stu-id="df3b2-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="df3b2-127">Migration zu Exchange Online</span><span class="sxs-lookup"><span data-stu-id="df3b2-127">Migration to Exchange Online</span></span>

<span data-ttu-id="df3b2-128">Wenn Sie sich für die Migration Ihrer E-Mails zu Exchange Online mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit.</span><span class="sxs-lookup"><span data-stu-id="df3b2-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="df3b2-129">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des Exchange Online-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Postfächer.</span><span class="sxs-lookup"><span data-stu-id="df3b2-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="df3b2-130">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="df3b2-130">You create and schedule your migration events.</span></span> <span data-ttu-id="df3b2-131">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="df3b2-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="df3b2-132">Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass E-Mail-Nachrichten von entsprechend geplanten und berechtigten Quellpostfächern ihrer Quellumgebungen zu Exchange Online migriert wurden.</span><span class="sxs-lookup"><span data-stu-id="df3b2-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="df3b2-133">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="df3b2-133">Considerations</span></span>

  - <span data-ttu-id="df3b2-134">Bevor Sie die Migration durchführen können, müssen Sie den FastTrack-Onboarding-Vorgang für Exchange Online durchführen.</span><span class="sxs-lookup"><span data-stu-id="df3b2-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="df3b2-135">Wenn Sie das Onboarding selbst durchgeführt haben, müssen Sie die erforderlichen Überprüfungen und Voraussetzungen erfüllen.</span><span class="sxs-lookup"><span data-stu-id="df3b2-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="df3b2-136">Ausführliche Informationen finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="df3b2-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="df3b2-137">FastTrack migriert nur zu aktiven Office 365-Postfächern.</span><span class="sxs-lookup"><span data-stu-id="df3b2-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="df3b2-138">Sie müssen bestimmte Anforderungen erfüllen, wenn Sie von einer lokalen Exchange-Umgebung migrieren möchten.</span><span class="sxs-lookup"><span data-stu-id="df3b2-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="df3b2-139">Weitere Informationen finden Sie unter [Voraussetzungen für die Hybridbereitstellung](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="df3b2-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="df3b2-140">Sämtliche Quellumgebungen müssen über die neuesten Service Packs (SP) verfügen und auf der Rollup (RU)-/Kumulativen Update (KU)-Ebene für das entsprechende Produkt in der Quellumgebung vorhanden sein.</span><span class="sxs-lookup"><span data-stu-id="df3b2-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="df3b2-141">Verteilerlisten (*MailEnabledGroup*-Objekte) und externe Kontakte (*MailEnabledContact*-Objekte) im lokalen Active Directory befinden, sind nicht Bestandteil einer Postfachdatenmigration.</span><span class="sxs-lookup"><span data-stu-id="df3b2-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="df3b2-142">Sie können Sie jedoch mithilfe von Azure Active Directory (Azure AD) Connect synchronisieren.</span><span class="sxs-lookup"><span data-stu-id="df3b2-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="df3b2-143">Quellumgebungen</span><span class="sxs-lookup"><span data-stu-id="df3b2-143">Source environments</span></span>

<span data-ttu-id="df3b2-144">Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:</span><span class="sxs-lookup"><span data-stu-id="df3b2-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="df3b2-145">aus einer einzelnen oder aus mehreren Active Directory-Gesamtstrukturen mit einer oder mehreren Exchange-Organisationen (jedes Exchange-E-Mail-System muss Exchange 2010 oder höher sein).</span><span class="sxs-lookup"><span data-stu-id="df3b2-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="df3b2-146">aus einer einzelnen IMAP-fähigen E-Mail-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="df3b2-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="df3b2-147">aus einer G Suite-Umgebung (nur Gmail, Kontakte und Kalender).</span><span class="sxs-lookup"><span data-stu-id="df3b2-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="df3b2-148">Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:</span><span class="sxs-lookup"><span data-stu-id="df3b2-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="df3b2-149"><strong>Quellumgebung</strong></span><span class="sxs-lookup"><span data-stu-id="df3b2-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="df3b2-150"><strong>Migrationstyp</strong></span><span class="sxs-lookup"><span data-stu-id="df3b2-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="df3b2-151"><strong>Was wird migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="df3b2-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="df3b2-152"><strong>Was wird nicht migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="df3b2-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="df3b2-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="df3b2-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="df3b2-154">
<strong>Hinweis:</strong> Informationen zu lokalen Exchange-Abhängigkeiten finden Sie unter <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Voraussetzungen für die Hybridbereitstellung.</span></a></span><span class="sxs-lookup"><span data-stu-id="df3b2-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="df3b2-155">Migration mit Hybridbereitstellung</span><span class="sxs-lookup"><span data-stu-id="df3b2-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="df3b2-156">E-Mails</span><span class="sxs-lookup"><span data-stu-id="df3b2-156">Emails</span></span></li>
<li><span data-ttu-id="df3b2-157">Serverseitige Postfachregeln</span><span class="sxs-lookup"><span data-stu-id="df3b2-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="df3b2-158">Stellvertretungen</span><span class="sxs-lookup"><span data-stu-id="df3b2-158">Delegates</span></span></li>
<li><span data-ttu-id="df3b2-159">Postfachkontakte</span><span class="sxs-lookup"><span data-stu-id="df3b2-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="df3b2-160">Kalender</span><span class="sxs-lookup"><span data-stu-id="df3b2-160">Calendar</span></span> </li>
<li> <span data-ttu-id="df3b2-161">Aufgaben</span><span class="sxs-lookup"><span data-stu-id="df3b2-161">Tasks</span></span> </li>
<li> <span data-ttu-id="df3b2-162">E-Mails mit Rechteverwaltung</span><span class="sxs-lookup"><span data-stu-id="df3b2-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="df3b2-163">Verschlüsselte E-Mails</span><span class="sxs-lookup"><span data-stu-id="df3b2-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="df3b2-164">Signaturen</span><span class="sxs-lookup"><span data-stu-id="df3b2-164">Signatures</span></span> </li>
<li> <span data-ttu-id="df3b2-165">Persönliches Archiv, das mit dem Benutzerpostfach migriert wird</span><span class="sxs-lookup"><span data-stu-id="df3b2-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="df3b2-166">Wiederherstellbare Elemente</span><span class="sxs-lookup"><span data-stu-id="df3b2-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="df3b2-167">Öffentliche Ordner</span><span class="sxs-lookup"><span data-stu-id="df3b2-167">Public folders</span></span> </li>
<li> <span data-ttu-id="df3b2-168">E-Mail, die die zulässige Nachrichtengröße überschreitet.</span><span class="sxs-lookup"><span data-stu-id="df3b2-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="df3b2-169">Journalarchiv oder eine beliebige Archivlösung von Drittanbietern</span><span class="sxs-lookup"><span data-stu-id="df3b2-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="df3b2-170">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="df3b2-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="df3b2-171">Archivdaten aus PST-Dateien</span><span class="sxs-lookup"><span data-stu-id="df3b2-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="df3b2-172">Beschädigte Elemente</span><span class="sxs-lookup"><span data-stu-id="df3b2-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="df3b2-173">Inaktive Postfächer</span><span class="sxs-lookup"><span data-stu-id="df3b2-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="df3b2-174">Clientseitige Postfachregeln</span><span class="sxs-lookup"><span data-stu-id="df3b2-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="df3b2-175"><strong>G Suite-Umgebung (nur Gmail, Kontakte und Kalender)</strong></span><span class="sxs-lookup"><span data-stu-id="df3b2-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="df3b2-176">
<strong>Hinweis:</strong> Ihre G Suite-Umgebung muss die unter "Ausführen einer <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">G Suite-Migration" beschriebenen Voraussetzungen erfüllen.</a></span><span class="sxs-lookup"><span data-stu-id="df3b2-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="df3b2-177">Übernahmemigration oder mehrstufige Migration</span><span class="sxs-lookup"><span data-stu-id="df3b2-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="df3b2-178">E-Mails</span><span class="sxs-lookup"><span data-stu-id="df3b2-178">Emails</span></span> </li>
<li> <span data-ttu-id="df3b2-179">Postfachkontakte (es werden maximal drei E-Mail-Adressen pro Kontakt migriert)</span><span class="sxs-lookup"><span data-stu-id="df3b2-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="df3b2-180">Kalender</span><span class="sxs-lookup"><span data-stu-id="df3b2-180">Calendar</span></span> </li>
<li> <span data-ttu-id="df3b2-181">Bezeichnungen</span><span class="sxs-lookup"><span data-stu-id="df3b2-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="df3b2-182">Regeln</span><span class="sxs-lookup"><span data-stu-id="df3b2-182">Rules</span></span> </li>
<li> <span data-ttu-id="df3b2-183">Stellvertretungen</span><span class="sxs-lookup"><span data-stu-id="df3b2-183">Delegates</span></span> </li>
<li> <span data-ttu-id="df3b2-184">Signaturen</span><span class="sxs-lookup"><span data-stu-id="df3b2-184">Signatures</span></span> </li>
<li> <span data-ttu-id="df3b2-185">Aufgaben</span><span class="sxs-lookup"><span data-stu-id="df3b2-185">Tasks</span></span> </li>
<li> <span data-ttu-id="df3b2-186">E-Mails oder Anhänge, die die zulässige Nachrichtengröße überschreiten</span><span class="sxs-lookup"><span data-stu-id="df3b2-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="df3b2-187">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="df3b2-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="df3b2-188">Archivdaten aus PST-Dateien oder einer Drittanbieter-Archivlösung (z. B. Google Vault)</span><span class="sxs-lookup"><span data-stu-id="df3b2-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="df3b2-189">E-Mails mit Rechteverwaltung oder Verschlüsselung</span><span class="sxs-lookup"><span data-stu-id="df3b2-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="df3b2-190">Beschädigte Elemente</span><span class="sxs-lookup"><span data-stu-id="df3b2-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="df3b2-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="df3b2-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="df3b2-192">Google-Gruppen</span><span class="sxs-lookup"><span data-stu-id="df3b2-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="df3b2-193">Ressourcenpostfächer</span><span class="sxs-lookup"><span data-stu-id="df3b2-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="df3b2-194">Inaktive Postfächer</span><span class="sxs-lookup"><span data-stu-id="df3b2-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="df3b2-195">Urlaubseinstellungen und Einstellungen für automatische Antworten</span><span class="sxs-lookup"><span data-stu-id="df3b2-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="df3b2-196">Freigegebene Kalender, Cloudanlagen, Google Hangout-Links und Ereignisfarben</span><span class="sxs-lookup"><span data-stu-id="df3b2-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="df3b2-197">\*\*Hangout-Unterhaltungen, die als Beschriftungen gespeichert wurden, werden migriert.</span><span class="sxs-lookup"><span data-stu-id="df3b2-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="df3b2-198"><strong>IMAP4-Quelle (wie Domino, GroupWise oder Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="df3b2-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="df3b2-199">Migration mit systemeigenen IMAP4-Tools</span><span class="sxs-lookup"><span data-stu-id="df3b2-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="df3b2-200">E-Mails</span><span class="sxs-lookup"><span data-stu-id="df3b2-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="df3b2-201">Regeln</span><span class="sxs-lookup"><span data-stu-id="df3b2-201">Rules</span></span> </li>
<li> <span data-ttu-id="df3b2-202">Stellvertretungen</span><span class="sxs-lookup"><span data-stu-id="df3b2-202">Delegates</span></span> </li>
<li> <span data-ttu-id="df3b2-203">Verteilerlisten</span><span class="sxs-lookup"><span data-stu-id="df3b2-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="df3b2-204">Externe Kontakte</span><span class="sxs-lookup"><span data-stu-id="df3b2-204">External contacts</span></span> </li>
<li> <span data-ttu-id="df3b2-205">E-Mail-aktivierte Benutzer</span><span class="sxs-lookup"><span data-stu-id="df3b2-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="df3b2-206">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="df3b2-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="df3b2-207">Postfachkontakte</span><span class="sxs-lookup"><span data-stu-id="df3b2-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="df3b2-208">Kalender</span><span class="sxs-lookup"><span data-stu-id="df3b2-208">Calendar</span></span> </li>
<li> <span data-ttu-id="df3b2-209">Signaturen</span><span class="sxs-lookup"><span data-stu-id="df3b2-209">Signatures</span></span> </li>
<li> <span data-ttu-id="df3b2-210">Aufgaben</span><span class="sxs-lookup"><span data-stu-id="df3b2-210">Tasks</span></span> </li>
<li> <span data-ttu-id="df3b2-211">E-Mails, die die zulässige Nachrichtengröße überschreiten</span><span class="sxs-lookup"><span data-stu-id="df3b2-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="df3b2-212">Archivdaten</span><span class="sxs-lookup"><span data-stu-id="df3b2-212">Archive data</span></span> </li>
<li> <span data-ttu-id="df3b2-213">Verschlüsselte E-Mail-Nachrichten</span><span class="sxs-lookup"><span data-stu-id="df3b2-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="df3b2-214">Beschädigte Elemente</span><span class="sxs-lookup"><span data-stu-id="df3b2-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="df3b2-215">Inaktive Postfächer</span><span class="sxs-lookup"><span data-stu-id="df3b2-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="df3b2-216">FastTrack-Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="df3b2-216">FastTrack responsibilities</span></span>

<span data-ttu-id="df3b2-217">Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="df3b2-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="df3b2-218">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="df3b2-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="df3b2-219">Unsere FastTrack-Spezialisten führen außerdem die folgenden Aktivitäten speziell für Exchange-Migrationen durch:</span><span class="sxs-lookup"><span data-stu-id="df3b2-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="df3b2-220">Bereitstellen von Anleitungen, die Ihnen dabei helfen, die Koexistenz von SMTP-E-Mail-Routing zwischen Ihrer Quellumgebung und Exchange Online zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="df3b2-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="df3b2-221">Ihre Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="df3b2-221">Your responsibilities</span></span>

<span data-ttu-id="df3b2-222">Während des Migrationsprojekts führen Sie Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="df3b2-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="df3b2-223">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="df3b2-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="df3b2-224">Sie führen außerdem die folgenden Aktivitäten speziell für Exchange-Migrationen aus:</span><span class="sxs-lookup"><span data-stu-id="df3b2-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="df3b2-225">Durchführen des FastTrack-Onboarding-Vorgangs für Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="df3b2-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="df3b2-226">Wenn Sie das Onboarding selbst durchgeführt haben, müssen Sie die erforderlichen Überprüfungen und Voraussetzungen erfüllen.</span><span class="sxs-lookup"><span data-stu-id="df3b2-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="df3b2-227">Ausführliche Informationen finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="df3b2-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="df3b2-228">Installieren der entsprechenden Clientsoftwareebene gemäß den Office 365-Richtlinien.</span><span class="sxs-lookup"><span data-stu-id="df3b2-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="df3b2-229">Details finden Sie unter [Der moderne Arbeitsplatz](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="df3b2-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="df3b2-230">Erfüllen bestimmter Anforderungen, wenn Sie von einer lokalen Exchange-Umgebung migrieren möchten.</span><span class="sxs-lookup"><span data-stu-id="df3b2-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="df3b2-231">Weitere Informationen finden Sie unter [Voraussetzungen für die Hybridbereitstellung](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="df3b2-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="df3b2-232">Sicherstellen, dass jede Quellumgebung über das neueste Service Pack (SP) und Rollup (RU)/Cumulative Update (CU) verfügt, sofern zutreffend.</span><span class="sxs-lookup"><span data-stu-id="df3b2-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="df3b2-233">Konfigurieren und Validieren der Koexistenz von SMTP-E-Mail-Routing zwischen Ihrer Quellumgebung und Exchange Online, sofern zutreffend.</span><span class="sxs-lookup"><span data-stu-id="df3b2-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="df3b2-234">Sicherstellen, dass die Größe des Quellpostfachs das Zielpostfachkontingent nicht überschreitet.</span><span class="sxs-lookup"><span data-stu-id="df3b2-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="df3b2-235">Abhängig von der Quellplattform müssen Sie möglicherweise Ihre Quelldaten auf 85 % des Zielpostfachkontingents beschränken.</span><span class="sxs-lookup"><span data-stu-id="df3b2-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="df3b2-236">Ggf. Migrieren clientseitiger Daten.</span><span class="sxs-lookup"><span data-stu-id="df3b2-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="df3b2-237">Dies umfasst unter anderem lokale Adressbücher, Daten in lokalen PST-Dateien, Outlook-Regeln und lokale Outlook-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="df3b2-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="df3b2-238">Unterstützen Ihrer Endbenutzer bei der Behebung von Problemen bei der clientbasierten Migration.</span><span class="sxs-lookup"><span data-stu-id="df3b2-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="df3b2-239">Migration zu SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="df3b2-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="df3b2-240">Wenn Sie sich für die Migration Ihrer Dateien zu SharePoint Online mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit.</span><span class="sxs-lookup"><span data-stu-id="df3b2-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="df3b2-241">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des SharePoint Online-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Dateien.</span><span class="sxs-lookup"><span data-stu-id="df3b2-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="df3b2-242">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="df3b2-242">You create and schedule your migration events.</span></span> <span data-ttu-id="df3b2-243">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="df3b2-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="df3b2-244">Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass Dateien von entsprechend geplanten und berechtigten Quellen ihrer Quellumgebungen zu SharePoint Online migriert wurden.</span><span class="sxs-lookup"><span data-stu-id="df3b2-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="df3b2-245">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="df3b2-245">Considerations</span></span>

  - <span data-ttu-id="df3b2-246">Alle Migrationen unterliegen SharePoint Online-Kontingenten.</span><span class="sxs-lookup"><span data-stu-id="df3b2-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="df3b2-247">Weitere Informationen finden Sie unter [<span class="underline">SharePoint Online und OneDrive for Business: Softwarelimits und -beschränkungen</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="df3b2-247">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="df3b2-248">Der Gesamtbetrag sollte auf 75 Prozent des SharePoint Online-Gesamtspeicherkontingents, für das Sie berechtigt sind, beschränkt werden (einschließlich den zusätzlichen Speicher, den Sie möglicherweise separat gekauft haben).</span><span class="sxs-lookup"><span data-stu-id="df3b2-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="df3b2-249">Detail der Quellumgebung</span><span class="sxs-lookup"><span data-stu-id="df3b2-249">Source environment details</span></span>

<span data-ttu-id="df3b2-250">Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:</span><span class="sxs-lookup"><span data-stu-id="df3b2-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="df3b2-251">Dateifreigaben (SMB [Server Message Block]-Dateifreigaben auf Geräten mit Unterstützung für SMB 2.0 und höher)</span><span class="sxs-lookup"><span data-stu-id="df3b2-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="df3b2-252">Eine einzelne G Suite-Umgebung (nur Google Drive).</span><span class="sxs-lookup"><span data-stu-id="df3b2-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="df3b2-253">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="df3b2-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="df3b2-254">Dropbox für Teams (Standard und Erweitert).</span><span class="sxs-lookup"><span data-stu-id="df3b2-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="df3b2-255">Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:</span><span class="sxs-lookup"><span data-stu-id="df3b2-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="df3b2-256"><strong>Quellumgebung</strong></span><span class="sxs-lookup"><span data-stu-id="df3b2-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="df3b2-257"><strong>Migrationstyp</strong></span><span class="sxs-lookup"><span data-stu-id="df3b2-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="df3b2-258"><strong>Was wird migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="df3b2-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="df3b2-259"><strong>Was wird nicht migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="df3b2-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="df3b2-260"><strong>Alle Dateifreigabegeräte mit Unterstützung für SMB 2.0 und höher</strong></span><span class="sxs-lookup"><span data-stu-id="df3b2-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="df3b2-261">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="df3b2-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="df3b2-262">Dokumente</span><span class="sxs-lookup"><span data-stu-id="df3b2-262">Documents</span></span> </li>
<li> <span data-ttu-id="df3b2-263">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="df3b2-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="df3b2-264">Datei- und Ordnerberechtigungen auf Benutzerebene\*</span><span class="sxs-lookup"><span data-stu-id="df3b2-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="df3b2-265">Datei- und Ordnerberechtigungen auf Gruppenebene\*</span><span class="sxs-lookup"><span data-stu-id="df3b2-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="df3b2-266">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="df3b2-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="df3b2-267">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="df3b2-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="df3b2-268">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="df3b2-268">Created date</span></span> </li>
<li> <span data-ttu-id="df3b2-269">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="df3b2-269">Modified date</span></span> </li>
<li> <span data-ttu-id="df3b2-270">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="df3b2-270">Created by</span></span> </li>
<li> <span data-ttu-id="df3b2-271">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="df3b2-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="df3b2-272">\* Setzt die Konfiguration der Verzeichnissynchronisierung voraus.</span><span class="sxs-lookup"><span data-stu-id="df3b2-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="df3b2-273">Es werden nur NTFS-Berechtigungen migriert, die für den Windows-Datei-Explorer verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="df3b2-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="df3b2-274">Berechtigungen, die direkt auf Dateifreigabegeräten verwaltet werden, werden nicht migriert.</span><span class="sxs-lookup"><span data-stu-id="df3b2-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="df3b2-275">Wenn Daten auf einem SMB 2.0-Gerät gespeichert werden, werden die NTFS-äquivalenten Berechtigungen, die vom SMB-Protokoll verfügbar gemacht werden, migriert.</span><span class="sxs-lookup"><span data-stu-id="df3b2-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="df3b2-276">Aufgezeichnete Eigentümerschaft und frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="df3b2-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="df3b2-277">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="df3b2-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="df3b2-278">Frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="df3b2-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="df3b2-279">Windows-Datei-/-Ordnerattribute (z. B. „Schreibgeschützt“ und „Ausgeblendet“) </span><span class="sxs-lookup"><span data-stu-id="df3b2-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="df3b2-280">Nicht-Windows-NTFS-Dateisystem (New Technology File System) und erweiterte NTFS-Berechtigungen sowie besondere Einstellungen:</span><span class="sxs-lookup"><span data-stu-id="df3b2-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="df3b2-281">Explizite Verweigerungsberechtigungen (werden nach der Migration entfernt, Inhalte unterliegen parallelen Berechtigungen oder Berechtigungen im übergeordneten Ordner).</span><span class="sxs-lookup"><span data-stu-id="df3b2-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="df3b2-282">Konfiguration der NTFS-Überwachung</span><span class="sxs-lookup"><span data-stu-id="df3b2-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="df3b2-283">Zusätzliche Dateimetadaten von der Dateiklassifizierungsinfrastruktur (File Classification Infrastructure, FCI)</span><span class="sxs-lookup"><span data-stu-id="df3b2-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="df3b2-284">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="df3b2-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="df3b2-285">Ausgeblendete Freigaben</span><span class="sxs-lookup"><span data-stu-id="df3b2-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="df3b2-286">Freigabe (z. B. gewährte Berechtigungen auf Freigabeebene)</span><span class="sxs-lookup"><span data-stu-id="df3b2-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="df3b2-287">Dateien oder Ordner, die die aktuellen <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">Einschränkungen und Einschränkungen für SharePoint Online überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="df3b2-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="df3b2-288"><strong>Einzelne G Suite-Umgebung (nur Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="df3b2-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="df3b2-289">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="df3b2-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="df3b2-290">Google Docs, Google Tabellen und Google Präsentationen (Dateien werden in das entsprechende Office-Format konvertiert), einschließlich derjenigen über 10 MB</span><span class="sxs-lookup"><span data-stu-id="df3b2-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="df3b2-291">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="df3b2-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="df3b2-292">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-293">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-294">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="df3b2-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="df3b2-295">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="df3b2-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="df3b2-296">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="df3b2-296">Created date</span></span> </li>
<li> <span data-ttu-id="df3b2-297">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="df3b2-297">Modified date</span></span> </li>
<li> <span data-ttu-id="df3b2-298">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="df3b2-298">Created by</span></span> </li>
<li> <span data-ttu-id="df3b2-299">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="df3b2-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="df3b2-300">Freigegebene Laufwerke (Ordner und Dateien)</span><span class="sxs-lookup"><span data-stu-id="df3b2-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="df3b2-301">Geteilte Inhalte, die im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="df3b2-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="df3b2-302">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="df3b2-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="df3b2-303">Beschreibungen von Dateien und Ordnern, Ordnerfarben</span><span class="sxs-lookup"><span data-stu-id="df3b2-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="df3b2-304">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-305">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-306">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="df3b2-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="df3b2-307">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="df3b2-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="df3b2-308">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="df3b2-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="df3b2-309">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="df3b2-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="df3b2-310">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="df3b2-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="df3b2-311">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="df3b2-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="df3b2-312">Google Fotos, Google Formulare, Google Maps und andere verbundene Apps</span><span class="sxs-lookup"><span data-stu-id="df3b2-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="df3b2-313">Google Zeichnungen</span><span class="sxs-lookup"><span data-stu-id="df3b2-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="df3b2-314">Freigegebene Inhalte außerhalb Ihrer Organisation</span><span class="sxs-lookup"><span data-stu-id="df3b2-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="df3b2-315">Inhalte, die nicht im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="df3b2-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="df3b2-316">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Google Drive-Administratorberichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="df3b2-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="df3b2-317">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="df3b2-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="df3b2-318">Mitgliedschaftsberechtigungen für freigegebene Laufwerke (<strong>Hinweis</strong>: Verwenden Sie die Google Drive-Administratorberichte, um die Mitgliedschaften für freigegebene Laufwerke zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="df3b2-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="df3b2-319">Weisen Sie die Endbenutzer an, diese Mitgliedschaftseinstellungen auf dem Ziel vor der Migration zu konfigurieren.)</span><span class="sxs-lookup"><span data-stu-id="df3b2-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="df3b2-320">Dateien, die als eingeschränkt oder nicht kopiert werden können</span><span class="sxs-lookup"><span data-stu-id="df3b2-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="df3b2-321">Dateien oder Ordner, die die aktuellen <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">Einschränkungen und Einschränkungen für SharePoint Online überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="df3b2-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="df3b2-322"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="df3b2-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="df3b2-323">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="df3b2-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="df3b2-324">Dokumente</span><span class="sxs-lookup"><span data-stu-id="df3b2-324">Documents</span></span> </li>
<li> <span data-ttu-id="df3b2-325">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="df3b2-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="df3b2-326">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-327">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-328">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="df3b2-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="df3b2-329">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="df3b2-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="df3b2-330">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="df3b2-330">Created date</span></span> </li>
<li> <span data-ttu-id="df3b2-331">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="df3b2-331">Modified date</span></span> </li>
<li> <span data-ttu-id="df3b2-332">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="df3b2-332">Created by</span></span> </li>
<li> <span data-ttu-id="df3b2-333">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="df3b2-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="df3b2-334">Geteilte Inhalte, die im Besitz des Box-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="df3b2-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="df3b2-335">Box Notes (konvertiert in Word-Dokumentformat)</span><span class="sxs-lookup"><span data-stu-id="df3b2-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="df3b2-336">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="df3b2-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="df3b2-337">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="df3b2-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="df3b2-338">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-339">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-340">Box-Tags und erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="df3b2-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="df3b2-341">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="df3b2-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="df3b2-342">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="df3b2-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="df3b2-343">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="df3b2-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="df3b2-344">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="df3b2-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="df3b2-345">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="df3b2-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="df3b2-346">Box-Apps, Lesezeichen, Favoriten und Workflows</span><span class="sxs-lookup"><span data-stu-id="df3b2-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="df3b2-347">Inhalte, die nicht im Besitz des migrierten Box-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="df3b2-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="df3b2-348">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Box-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="df3b2-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="df3b2-349">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="df3b2-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="df3b2-350">Dateien oder Ordner, die die aktuellen <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">Einschränkungen und Einschränkungen für SharePoint Online überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="df3b2-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="df3b2-351"><strong>Dropbox für Teams (Standard und Erweitert)</strong></span><span class="sxs-lookup"><span data-stu-id="df3b2-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="df3b2-352">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="df3b2-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="df3b2-353">Dokumente</span><span class="sxs-lookup"><span data-stu-id="df3b2-353">Documents</span></span> </li>
<li> <span data-ttu-id="df3b2-354">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="df3b2-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="df3b2-355">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-356">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-357">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="df3b2-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="df3b2-358">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="df3b2-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="df3b2-359">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="df3b2-359">Created date</span></span> </li>
<li> <span data-ttu-id="df3b2-360">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="df3b2-360">Modified date</span></span> </li>
<li> <span data-ttu-id="df3b2-361">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="df3b2-361">Created by</span></span> </li>
<li> <span data-ttu-id="df3b2-362">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="df3b2-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="df3b2-363">Freigegebene Teamordner und -inhalte</span><span class="sxs-lookup"><span data-stu-id="df3b2-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="df3b2-364">Geteilte Inhalte, die im Besitz des Dropbox-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="df3b2-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="df3b2-365">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="df3b2-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="df3b2-366">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="df3b2-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="df3b2-367">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-368">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-369">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="df3b2-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="df3b2-370">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="df3b2-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="df3b2-371">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="df3b2-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="df3b2-372">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="df3b2-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="df3b2-373">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="df3b2-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="df3b2-374">Nicht gemountete Dropbox-Ordner</span><span class="sxs-lookup"><span data-stu-id="df3b2-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="df3b2-375">Gelöschte oder getrennte Benutzer</span><span class="sxs-lookup"><span data-stu-id="df3b2-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="df3b2-376">Dropbox Paper, Showcases und Spaces</span><span class="sxs-lookup"><span data-stu-id="df3b2-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="df3b2-377">Dropbox-Apps und Favoriten (Pins/Sterne)</span><span class="sxs-lookup"><span data-stu-id="df3b2-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="df3b2-378">Inhalte, die nicht im Besitz des migrierten Dropbox-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="df3b2-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="df3b2-379">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Dropbox-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="df3b2-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="df3b2-380">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="df3b2-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="df3b2-381">Dateien oder Ordner, die die aktuellen <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">Einschränkungen und Einschränkungen für SharePoint Online überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="df3b2-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="df3b2-382">FastTrack-Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="df3b2-382">FastTrack responsibilities</span></span>

<span data-ttu-id="df3b2-383">Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="df3b2-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="df3b2-384">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="df3b2-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="df3b2-385">Ihre Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="df3b2-385">Your responsibilities</span></span>

<span data-ttu-id="df3b2-386">Während des Migrationsprojekts führen Sie Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="df3b2-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="df3b2-387">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="df3b2-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="df3b2-388">Sie führen außerdem die folgenden Aktivitäten speziell für SharePoint Online-Migrationen aus:</span><span class="sxs-lookup"><span data-stu-id="df3b2-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="df3b2-389">Bereitstellen aller SharePoint-Teamwebsites, die für Ihre Migrationsereignisse vorgesehen sind.</span><span class="sxs-lookup"><span data-stu-id="df3b2-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="df3b2-390">Migration zu OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="df3b2-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="df3b2-391">Wenn Sie sich für die Migration Ihrer Dateien zu OneDrive for Business mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit.</span><span class="sxs-lookup"><span data-stu-id="df3b2-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="df3b2-392">Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des OneDrive for Business-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Dateien.</span><span class="sxs-lookup"><span data-stu-id="df3b2-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="df3b2-393">Sie erstellen und planen Ihre Migrationsereignisse.</span><span class="sxs-lookup"><span data-stu-id="df3b2-393">You create and schedule your migration events.</span></span> <span data-ttu-id="df3b2-394">Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.</span><span class="sxs-lookup"><span data-stu-id="df3b2-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="df3b2-395">Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass Dateien von entsprechend geplanten und berechtigten Quellen ihrer Quellumgebungen zu OneDrive for Business migriert wurden.</span><span class="sxs-lookup"><span data-stu-id="df3b2-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="df3b2-396">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="df3b2-396">Considerations</span></span>

  - <span data-ttu-id="df3b2-397">Alle Migrationen unterliegen den OneDrive for Business-Kontingenten.</span><span class="sxs-lookup"><span data-stu-id="df3b2-397">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="df3b2-398">Weitere Informationen finden Sie unter [<span class="underline">SharePoint Online und OneDrive for Business: Softwarelimits und -beschränkungen</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="df3b2-398">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="df3b2-399">Der Gesamtbetrag sollte auf 75 Prozent der Daten des SharePoint Online-Gesamtspeicherkontingents, für das Sie berechtigt sind, beschränkt werden (einschließlich den zusätzlichen Speicher, den Sie möglicherweise separat gekauft haben).</span><span class="sxs-lookup"><span data-stu-id="df3b2-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="df3b2-400">FastTrack migriert nur zu aktiven OneDrive for Business-Laufwerken.</span><span class="sxs-lookup"><span data-stu-id="df3b2-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="df3b2-401">Detail der Quellumgebung</span><span class="sxs-lookup"><span data-stu-id="df3b2-401">Source environment details</span></span>

<span data-ttu-id="df3b2-402">Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:</span><span class="sxs-lookup"><span data-stu-id="df3b2-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="df3b2-403">Dateifreigaben (SMB-Dateifreigaben auf Geräten mit Unterstützung für SMB 2.0 und höher)</span><span class="sxs-lookup"><span data-stu-id="df3b2-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="df3b2-404">Einzelne G Suite-Umgebung (nur Google Drive).</span><span class="sxs-lookup"><span data-stu-id="df3b2-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="df3b2-405">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="df3b2-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="df3b2-406">Dropbox für Teams (Standard und Erweitert).</span><span class="sxs-lookup"><span data-stu-id="df3b2-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="df3b2-407">Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:</span><span class="sxs-lookup"><span data-stu-id="df3b2-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="df3b2-408"><strong>Quellumgebung</strong></span><span class="sxs-lookup"><span data-stu-id="df3b2-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="df3b2-409"><strong>Migrationstyp</strong></span><span class="sxs-lookup"><span data-stu-id="df3b2-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="df3b2-410"><strong>Was wird migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="df3b2-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="df3b2-411"><strong>Was wird nicht migriert?</strong></span><span class="sxs-lookup"><span data-stu-id="df3b2-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="df3b2-412"><strong>Alle Dateifreigabegeräte mit Unterstützung für SMB 2.0 und höher</strong></span><span class="sxs-lookup"><span data-stu-id="df3b2-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="df3b2-413">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="df3b2-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="df3b2-414">Dokumente</span><span class="sxs-lookup"><span data-stu-id="df3b2-414">Documents</span></span> </li>
<li> <span data-ttu-id="df3b2-415">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="df3b2-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="df3b2-416">Datei- und Ordnerberechtigungen auf Benutzerebene\*</span><span class="sxs-lookup"><span data-stu-id="df3b2-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="df3b2-417">Datei- und Ordnerberechtigungen auf Gruppenebene\*</span><span class="sxs-lookup"><span data-stu-id="df3b2-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="df3b2-418">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="df3b2-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="df3b2-419">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="df3b2-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="df3b2-420">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="df3b2-420">Created date</span></span> </li>
<li> <span data-ttu-id="df3b2-421">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="df3b2-421">Modified date</span></span> </li>
<li> <span data-ttu-id="df3b2-422">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="df3b2-422">Created by</span></span> </li>
<li> <span data-ttu-id="df3b2-423">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="df3b2-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="df3b2-424">\* Setzt die Konfiguration der Verzeichnissynchronisierung voraus.</span><span class="sxs-lookup"><span data-stu-id="df3b2-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="df3b2-425">Es werden nur NTFS-Berechtigungen migriert, die für den Windows-Datei-Explorer verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="df3b2-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="df3b2-426">Berechtigungen, die direkt auf Dateifreigabegeräten verwaltet werden, werden nicht migriert.</span><span class="sxs-lookup"><span data-stu-id="df3b2-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="df3b2-427">Wenn Daten auf einem SMB 2.0-Gerät gespeichert werden, werden die NTFS-äquivalenten Berechtigungen, die vom SMB-Protokoll verfügbar gemacht werden, migriert.</span><span class="sxs-lookup"><span data-stu-id="df3b2-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="df3b2-428">Aufgezeichnete Eigentümerschaft und frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="df3b2-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="df3b2-429">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="df3b2-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="df3b2-430">Frühere Versionen</span><span class="sxs-lookup"><span data-stu-id="df3b2-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="df3b2-431">Windows-Datei-/-Ordnerattribute (z. B. „Schreibgeschützt“ und „Ausgeblendet“) </span><span class="sxs-lookup"><span data-stu-id="df3b2-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="df3b2-432">Nicht-Windows-NTFS-Dateisystem (New Technology File System) und erweiterte NTFS-Berechtigungen sowie besondere Einstellungen:</span><span class="sxs-lookup"><span data-stu-id="df3b2-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="df3b2-433">Explizite Verweigerungsberechtigungen (werden nach der Migration entfernt, Inhalte unterliegen parallelen Berechtigungen oder Berechtigungen im übergeordneten Ordner).</span><span class="sxs-lookup"><span data-stu-id="df3b2-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="df3b2-434">Konfiguration der NTFS-Überwachung</span><span class="sxs-lookup"><span data-stu-id="df3b2-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="df3b2-435">Zusätzliche Dateimetadaten von der Dateiklassifizierungsinfrastruktur (File Classification Infrastructure, FCI)</span><span class="sxs-lookup"><span data-stu-id="df3b2-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="df3b2-436">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="df3b2-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="df3b2-437">Ausgeblendete Freigaben</span><span class="sxs-lookup"><span data-stu-id="df3b2-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="df3b2-438">Freigabe (z. B. gewährte Berechtigungen auf Freigabeebene)</span><span class="sxs-lookup"><span data-stu-id="df3b2-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="df3b2-439">Dateien oder Ordner, die die aktuellen <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">Einschränkungen und Einschränkungen für SharePoint Online überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="df3b2-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="df3b2-440"><strong>Einzelne G Suite-Umgebung (nur Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="df3b2-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="df3b2-441">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="df3b2-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="df3b2-442">Google Docs, Google Tabellen und Google Präsentationen (Dateien werden in das entsprechende Office-Format konvertiert, einschließlich derjenigen über 10 MB)</span><span class="sxs-lookup"><span data-stu-id="df3b2-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="df3b2-443">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="df3b2-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="df3b2-444">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-445">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-446">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="df3b2-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="df3b2-447">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="df3b2-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="df3b2-448">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="df3b2-448">Created date</span></span> </li>
<li> <span data-ttu-id="df3b2-449">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="df3b2-449">Modified date</span></span> </li>
<li> <span data-ttu-id="df3b2-450">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="df3b2-450">Created by</span></span> </li>
<li> <span data-ttu-id="df3b2-451">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="df3b2-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="df3b2-452">Freigegebene Laufwerke (Ordner und Dateien)</span><span class="sxs-lookup"><span data-stu-id="df3b2-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="df3b2-453">Geteilte Inhalte, die im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="df3b2-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="df3b2-454">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="df3b2-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="df3b2-455">Beschreibungen von Dateien und Ordnern, Ordnerfarben</span><span class="sxs-lookup"><span data-stu-id="df3b2-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="df3b2-456">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-457">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-458">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="df3b2-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="df3b2-459">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="df3b2-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="df3b2-460">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="df3b2-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="df3b2-461">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="df3b2-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="df3b2-462">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="df3b2-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="df3b2-463">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="df3b2-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="df3b2-464">Google Fotos, Google Formulare, Google Maps und andere verbundene Apps</span><span class="sxs-lookup"><span data-stu-id="df3b2-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="df3b2-465">Google Zeichnungen</span><span class="sxs-lookup"><span data-stu-id="df3b2-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="df3b2-466">Freigegebene Inhalte außerhalb Ihrer Organisation</span><span class="sxs-lookup"><span data-stu-id="df3b2-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="df3b2-467">Inhalte, die nicht im Besitz des Google Drive-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="df3b2-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="df3b2-468">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Google Drive-Administratorberichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="df3b2-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="df3b2-469">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="df3b2-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="df3b2-470">Mitgliedschaftsberechtigungen für freigegebene Laufwerke (<strong>Hinweis</strong>: Verwenden Sie die Google Drive-Administratorberichte, um die Mitgliedschaften für freigegebene Laufwerke zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="df3b2-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="df3b2-471">Weisen Sie die Endbenutzer an, diese Mitgliedschaftseinstellungen auf dem Ziel vor der Migration zu konfigurieren.)</span><span class="sxs-lookup"><span data-stu-id="df3b2-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="df3b2-472">Dateien oder Ordner, die die aktuellen <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">Einschränkungen und Einschränkungen für SharePoint Online überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="df3b2-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="df3b2-473"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="df3b2-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="df3b2-474">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="df3b2-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="df3b2-475">Dokumente</span><span class="sxs-lookup"><span data-stu-id="df3b2-475">Documents</span></span> </li>
<li> <span data-ttu-id="df3b2-476">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="df3b2-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="df3b2-477">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-478">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-479">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="df3b2-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="df3b2-480">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="df3b2-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="df3b2-481">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="df3b2-481">Created date</span></span> </li>
<li> <span data-ttu-id="df3b2-482">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="df3b2-482">Modified date</span></span> </li>
<li> <span data-ttu-id="df3b2-483">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="df3b2-483">Created by</span></span> </li>
<li> <span data-ttu-id="df3b2-484">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="df3b2-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="df3b2-485">Geteilte Inhalte, die im Besitz des Box-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="df3b2-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="df3b2-486">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="df3b2-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="df3b2-487">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="df3b2-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="df3b2-488">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-489">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-490">Box-Tags und erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="df3b2-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="df3b2-491">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="df3b2-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="df3b2-492">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="df3b2-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="df3b2-493">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="df3b2-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="df3b2-494">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="df3b2-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="df3b2-495">Blockierte oder inaktive Benutzer</span><span class="sxs-lookup"><span data-stu-id="df3b2-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="df3b2-496">Box-Apps, Lesezeichen, Favoriten und Workflows</span><span class="sxs-lookup"><span data-stu-id="df3b2-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="df3b2-497">Inhalte, die nicht im Besitz des migrierten Box-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="df3b2-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="df3b2-498">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Box-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="df3b2-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="df3b2-499">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="df3b2-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="df3b2-500">Dateien oder Ordner, die die aktuellen <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">Einschränkungen und Einschränkungen für SharePoint Online überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="df3b2-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="df3b2-501"><strong>Dropbox für Teams (Standard und Erweitert)</strong></span><span class="sxs-lookup"><span data-stu-id="df3b2-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="df3b2-502">Einzeln oder mehrstufig</span><span class="sxs-lookup"><span data-stu-id="df3b2-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="df3b2-503">Dokumente</span><span class="sxs-lookup"><span data-stu-id="df3b2-503">Documents</span></span> </li>
<li> <span data-ttu-id="df3b2-504">Datei- und Ordnerstruktur</span><span class="sxs-lookup"><span data-stu-id="df3b2-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="df3b2-505">Berechtigungen für Ordner auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-506">Berechtigungen für Ordner auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-507">Dateien unter 15 GB</span><span class="sxs-lookup"><span data-stu-id="df3b2-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="df3b2-508">Grundlegende Dokument- und Ordnermetadaten: </span><span class="sxs-lookup"><span data-stu-id="df3b2-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="df3b2-509">Erstellungsdatum</span><span class="sxs-lookup"><span data-stu-id="df3b2-509">Created date</span></span> </li>
<li> <span data-ttu-id="df3b2-510">Änderungsdatum</span><span class="sxs-lookup"><span data-stu-id="df3b2-510">Modified date</span></span> </li>
<li> <span data-ttu-id="df3b2-511">Erstellt von</span><span class="sxs-lookup"><span data-stu-id="df3b2-511">Created by</span></span> </li>
<li> <span data-ttu-id="df3b2-512">Zuletzt geändert von</span><span class="sxs-lookup"><span data-stu-id="df3b2-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="df3b2-513">Freigegebene Teamordner und -inhalte</span><span class="sxs-lookup"><span data-stu-id="df3b2-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="df3b2-514">Geteilte Inhalte, die im Besitz des Dropbox-Kontos sind, das migriert wird</span><span class="sxs-lookup"><span data-stu-id="df3b2-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="df3b2-515">Besitzverlauf, frühere Versionen und Kommentare</span><span class="sxs-lookup"><span data-stu-id="df3b2-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="df3b2-516">Beschreibungen von Dateien und Ordnern</span><span class="sxs-lookup"><span data-stu-id="df3b2-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="df3b2-517">Berechtigungen für Dateien auf Benutzerebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-518">Berechtigungen für Dateien auf Gruppenebene</span><span class="sxs-lookup"><span data-stu-id="df3b2-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="df3b2-519">Erweiterte Metadaten</span><span class="sxs-lookup"><span data-stu-id="df3b2-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="df3b2-520">Attribute für Dateisperre</span><span class="sxs-lookup"><span data-stu-id="df3b2-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="df3b2-521">Konvertierung eingebetteter URLs im Inhalt</span><span class="sxs-lookup"><span data-stu-id="df3b2-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="df3b2-522">Gelöschte Elemente</span><span class="sxs-lookup"><span data-stu-id="df3b2-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="df3b2-523">Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann</span><span class="sxs-lookup"><span data-stu-id="df3b2-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="df3b2-524">Nicht gemountete Dropbox-Ordner</span><span class="sxs-lookup"><span data-stu-id="df3b2-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="df3b2-525">Gelöschte oder getrennte Benutzer</span><span class="sxs-lookup"><span data-stu-id="df3b2-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="df3b2-526">Dropbox Paper, Showcases und Spaces</span><span class="sxs-lookup"><span data-stu-id="df3b2-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="df3b2-527">Dropbox-Apps und Favoriten (Pins/Sterne)</span><span class="sxs-lookup"><span data-stu-id="df3b2-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="df3b2-528">Inhalte, die nicht im Besitz des migrierten Dropbox-Kontos sind</span><span class="sxs-lookup"><span data-stu-id="df3b2-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="df3b2-529">Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Dropbox-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="df3b2-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="df3b2-530">Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.)</span><span class="sxs-lookup"><span data-stu-id="df3b2-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="df3b2-531">Dateien oder Ordner, die die aktuellen <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">Einschränkungen und Einschränkungen für SharePoint Online überschreiten</span></a> </span><span class="sxs-lookup"><span data-stu-id="df3b2-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="df3b2-532">FastTrack-Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="df3b2-532">FastTrack responsibilities</span></span>

<span data-ttu-id="df3b2-533">Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="df3b2-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="df3b2-534">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="df3b2-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="df3b2-535">Ihre Zuständigkeiten</span><span class="sxs-lookup"><span data-stu-id="df3b2-535">Your responsibilities</span></span>

<span data-ttu-id="df3b2-536">Während des Migrationsprojekts führen Sie Standardaktivitäten aus.</span><span class="sxs-lookup"><span data-stu-id="df3b2-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="df3b2-537">Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="df3b2-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="df3b2-538">Sie führen außerdem die folgenden Aktivitäten speziell für OneDrive for Business-Migrationen aus:</span><span class="sxs-lookup"><span data-stu-id="df3b2-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="df3b2-539">Bereitstellen aller OneDrive for Business-Websites, die für Ihre Migrationsereignisse bestimmt sind.</span><span class="sxs-lookup"><span data-stu-id="df3b2-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
