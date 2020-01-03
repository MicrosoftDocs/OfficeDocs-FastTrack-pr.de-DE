---
title: Anhang A Migration aus IBM Domino zu Exchange Online
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 1/03/2020
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: 'Die Migration aus IBM Domino zu Exchange Online umfasst mehrere wichtige Aspekte, einschließlich der Schritte in den folgenden Phasen:'
ms.openlocfilehash: 17d7b6669dbd5f8647ee7dcf7218f898ddac59fc
ms.sourcegitcommit: d7f4c9eafe7855c6ae02c2bd0fe3b700c458007c
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/02/2020
ms.locfileid: "40929269"
---
# <a name="appendix-a---migration-from-ibm-domino-to-exchange-online"></a><span data-ttu-id="fa6a4-103">Anhang A: Migration aus IBM Domino zu Exchange Online</span><span class="sxs-lookup"><span data-stu-id="fa6a4-103">Appendix A - Migration from IBM Domino to Exchange Online</span></span>

<span data-ttu-id="fa6a4-104">Die Migration aus IBM Domino zu Exchange Online umfasst mehrere wichtige Aspekte, einschließlich der Schritte in den folgenden Phasen:</span><span class="sxs-lookup"><span data-stu-id="fa6a4-104">Migration from IBM Domino to Exchange Online includes several important aspects, including what happens during the following phases:</span></span> 
- [<span data-ttu-id="fa6a4-105">Einleitungsphase</span><span class="sxs-lookup"><span data-stu-id="fa6a4-105">Initiate phase</span></span>](#initiate-phase)   
- [<span data-ttu-id="fa6a4-106">Analysephase</span><span class="sxs-lookup"><span data-stu-id="fa6a4-106">Assess phase</span></span>](#assess-phase)
- [<span data-ttu-id="fa6a4-107">Korrekturphase</span><span class="sxs-lookup"><span data-stu-id="fa6a4-107">Remediate phase</span></span>](#remediate-phase)  
- [<span data-ttu-id="fa6a4-108">Aktivierungsphase</span><span class="sxs-lookup"><span data-stu-id="fa6a4-108">Enable phase</span></span>](#enable-phase)  
- [<span data-ttu-id="fa6a4-109">Migrationsphase</span><span class="sxs-lookup"><span data-stu-id="fa6a4-109">Migrate phase</span></span>](#migrate-phase)
    
## <a name="identities"></a><span data-ttu-id="fa6a4-110">Identitäten</span><span class="sxs-lookup"><span data-stu-id="fa6a4-110">Identities</span></span>

<span data-ttu-id="fa6a4-111">Sie sind für das Erstellen und Verwalten von Identitäten zuständig (nur Cloud synchronisiert oder mit ihrer lokalen Active Directory-Umgebung verbunden).</span><span class="sxs-lookup"><span data-stu-id="fa6a4-111">You are responsible for creating and managing the identities (cloud only, synchronized, or federated with their on-premises Active Directory).</span></span> <span data-ttu-id="fa6a4-112">Sie müssen die Zuordnung der Identitäten (wenn noch nicht vorhanden) zwischen Domino und der lokalen Active Directory-Umgebung oder Azure Active Directory in den frühen Phasen des Onboardings abschließen.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-112">You must complete the mapping of identities (if not already present) between Domino and the on-premises Active Directory or Azure Active Directory during the early stages of onboarding.</span></span>
  
## <a name="coexistence"></a><span data-ttu-id="fa6a4-113">Koexistenz</span><span class="sxs-lookup"><span data-stu-id="fa6a4-113">Coexistence</span></span>

<span data-ttu-id="fa6a4-114">Der FastTrack Center-Vorteil für Office 365 stellt einen bidirektionalen E-Mail-Fluss zwischen der lokalen Domino-Umgebung und Exchange Online für alle Kunden bereit.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-114">The FastTrack Center Benefit for Office 365 provides bidirectional mail flow between the on-premises Domino environment and Exchange Online to all customers.</span></span>
  
## <a name="migration"></a><span data-ttu-id="fa6a4-115">Migration</span><span class="sxs-lookup"><span data-stu-id="fa6a4-115">Migration</span></span>

<span data-ttu-id="fa6a4-p102">Der FastTrack Center-Standardprozess für die Migration aus Domino zu Exchange Online umfasst die Vorabbereitstellung von Domino-Daten für Azure vor der Migration zu Exchange Online-Postfächern. Im Rahmen der FastTrack-Migrationen müssen bestimmte Aktivitäten in verschiedenen Phasen des Onboardings von FastTrack Center-Mitarbeitern und von Ihnen durchgeführt werden. Diese Aktivitäten werden in den folgenden Abschnitten behandelt.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-p102">The standard FastTrack Center process for migration from Domino to Exchange Online involves pre-staging Domino data to Azure before migration to Exchange Online mailboxes. FastTrack migrations require activities to be performed at different stages of onboarding by FastTrack Center personnel and you. We cover these activities in the following sections.</span></span>
  
> [!NOTE]
> <span data-ttu-id="fa6a4-p103">Daten, die mit den FastTrack-Diensten migriert wurden,werden möglicherweise in die USA übermittelt und dort oder in einem anderen Land, in dem Microsoft Einrichtungen unterhält, gespeichert und verarbeitet. Die FastTrack-Dienste sind nicht für Daten vorgesehen, die besonderen rechtlichen oder behördlichen Vorschriften unterliegen.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-p103">Data migrated through the FastTrack services may be transferred to, stored, and processed in the United States or anywhere that Microsoft maintains facilities. The FastTrack services aren't designed or intended for data subject to special legal or regulatory requirements.</span></span> 
  
## <a name="initiate-phase"></a><span data-ttu-id="fa6a4-121">Einleitungsphase</span><span class="sxs-lookup"><span data-stu-id="fa6a4-121">Initiate phase</span></span>

 <span data-ttu-id="fa6a4-122">**Wichtige Aktionen**</span><span class="sxs-lookup"><span data-stu-id="fa6a4-122">**Key actions**</span></span>
  
- <span data-ttu-id="fa6a4-123">Identifizieren von Domino als Quell-E-Mail-Plattform</span><span class="sxs-lookup"><span data-stu-id="fa6a4-123">Identify Domino as the source mail platform.</span></span>   
- <span data-ttu-id="fa6a4-124">Bestimmen, ob FastTrack Center die Migration durchführt.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-124">Determine whether the FastTrack Center performs the migration.</span></span>
    
 <span data-ttu-id="fa6a4-125">**Verantwortlichkeiten des Kunden**</span><span class="sxs-lookup"><span data-stu-id="fa6a4-125">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="fa6a4-126">Bereitstellen grundlegender Informationen über die Quellmessagingplattform und Bestätigen der Migrationsabsicht über das FastTrack Center</span><span class="sxs-lookup"><span data-stu-id="fa6a4-126">Provide basic information about the source messaging platform, and confirm the migration intent with the FastTrack Center.</span></span> 
- <span data-ttu-id="fa6a4-127">Befolgen von exemplarischen Vorgehensweisen der FastTrack Center-Leistungsangebotsprozesse</span><span class="sxs-lookup"><span data-stu-id="fa6a4-127">Participate in a walkthrough of the FastTrack Center Benefit processes.</span></span>  
- <span data-ttu-id="fa6a4-128">Unterzeichnen des FastTrack-Leistungsvertrags</span><span class="sxs-lookup"><span data-stu-id="fa6a4-128">Sign the FastTrack Services Agreement.</span></span>
    
## <a name="assess-phase"></a><span data-ttu-id="fa6a4-129">Analysephase</span><span class="sxs-lookup"><span data-stu-id="fa6a4-129">Assess phase</span></span>

 <span data-ttu-id="fa6a4-130">**Wichtige Aktionen**</span><span class="sxs-lookup"><span data-stu-id="fa6a4-130">**Key actions**</span></span>
  
- <span data-ttu-id="fa6a4-131">Das FastTrack Center führt einen Workshop zur Migration mit dem Kunden durch.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-131">The FastTrack Center conducts a migration workshop with the customer.</span></span> 
- <span data-ttu-id="fa6a4-132">Sie schließen die erforderlichen Migrationsschritte ab, z. B. Migrationsfragebogen und Bereitstellen von Admin-Arbeitsstationen.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-132">You complete the migration prerequisites, like the migration questionnaire and the provisioning of admin workstations.</span></span>    
- <span data-ttu-id="fa6a4-133">Die Migrationsanalyse für Domino erfolgt in Ihrer lokalen Umgebung.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-133">Migration assessment for Domino is performed in your on-premises environment.</span></span>
    
 <span data-ttu-id="fa6a4-134">**Verantwortlichkeiten des Kunden**</span><span class="sxs-lookup"><span data-stu-id="fa6a4-134">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="fa6a4-135">Bereitstellen von Admin-Arbeitsstationen, die das FastTrack Center zum Verwalten der Onboarding- und Migrationsschritte wie Analysieren, Erstellen von Replikaten, Überwachen, Weiterleiten von Einstellungen während der Migration usw. verwendet.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-135">Provision admin workstations that the FastTrack Center uses to administer onboarding and migration tasks, like assessment, replica creation, auditing, setting forwarding during migration, and so on.</span></span>
    > [!NOTE]
    > <span data-ttu-id="fa6a4-p104">Die Analyse ist für die erfolgreiche Planung und schnelle Durchführung der Migration entscheidend. Sie wird von einem Migrationsarchitekten durchgeführt, der speziellen Zugriff auf die Domino-Umgebung benötigt. Erforderliche Admin-Arbeitsstationskomponenten umfassen einen für den Zugriff auf alle Domino-E-Mail-Quellserver und auf den Azure-Domino-Replikat-Staging-Server konfigurierten Notes-Client.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-p104">Assessment is critical for successful planning and execution of velocity migrations. It's performed by a migration architect who needs specific access to the Domino environment. Required admin workstation components include a Notes client configured to access all source Domino mail servers and the Azure Domino replica staging server.</span></span> 
- <span data-ttu-id="fa6a4-p105">Bereitstellen des Remotezugriffs auf die Admin-Arbeitsstationen, Konten und Berechtigungen für die Durchführung von Analyse- und Migrationsaktivitäten für das Migrationsteam. Dies umfasst die Bereitstellung mehrerer lokaler Konten und Administatorberechtigungen in Exchange Online für die Migration.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-p105">Provide the migration team remote access to the admin workstations, accounts, and permissions for performing assessment and migration activities. This includes provisioning multiple accounts on-premises and in Exchange Online with administrative permissions needed for migration.</span></span>    
- <span data-ttu-id="fa6a4-p106">Öffnen von Firewallports Ausgehende Ports müssen zwischen den Domino-E-Mail-Quellservern und dem Azure-Staging-Server geöffnet werden. Andere Ports für die Kommunikation (z. B. Admin-Arbeitsstationen,Domino-Quellserver und lokale Exchange-Server (sofern vorhanden)) müssen auch geöffnet sein.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-p106">Open firewall ports. Outbound ports must be opened between the source Domino mail servers and the Azure staging server. Other ports for communication (like admin workstations, source Domino servers, and Exchange servers on-premises (if present)) must also must be opened.</span></span> 
- <span data-ttu-id="fa6a4-p107">Aktivieren der übergreifenden Zertifizierung zwischen der Domino-Quellumgebung und dem Azure Domino-Staging-Server zur Erleichterung der Replikation. Übergreifende Zertifizierungsaufgaben vom Domino-Administrator des Kunden und dem FastTrack Center koordiniert.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-p107">Enable cross-certification between the source Domino environment and the Azure Domino staging server to facilitate replication. Cross-certification tasks are coordinated between the customer's Domino admin and the FastTrack Center.</span></span>  
- <span data-ttu-id="fa6a4-146">Ausfüllen des Migrationsfragebogens, in dem die für die Konfiguration der Migrationsumgebung in Azure erforderlichen Informationen gesammelt werden (z. B. Tools, Skripts und Migrationsserver).</span><span class="sxs-lookup"><span data-stu-id="fa6a4-146">Complete the migration questionnaire, which captures information required to configure the migration environment in Azure (like tools, scripts, and migration servers).</span></span>   
- <span data-ttu-id="fa6a4-147">Sicherstellen, dass auf Zielpostfächern in Office 365 das MAPI-Protokoll (Messaging Application Program Interface) aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-147">Ensure target mailboxes in Office 365 have Messaging Application Program Interface (MAPI) protocol enabled.</span></span>  
> [!NOTE]
> <span data-ttu-id="fa6a4-p108">Einige Office 365-Pläne unterstützen das MAPI-Protokoll nicht. Zum Migrieren von Daten müssen Postfächer aus diesen Plänen in einen Plan konvertiert werden, die MAPI vor dem Migrationsereignis unterstützt. Nach der Migration können diese Pläne wieder zurückgeändert werden.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-p108">Some Office 365 plans don't support MAPI protocol. In order to migrate data, mailboxes from these plans need to be converted to a plan that supports MAPI ahead of the migration event. Following migration, these plans can be changed back.</span></span> 
  
## <a name="remediate-phase"></a><span data-ttu-id="fa6a4-151">Korrekturphase</span><span class="sxs-lookup"><span data-stu-id="fa6a4-151">Remediate phase</span></span>

 <span data-ttu-id="fa6a4-152">**Wichtige Aktionen**</span><span class="sxs-lookup"><span data-stu-id="fa6a4-152">**Key actions**</span></span>
  
- <span data-ttu-id="fa6a4-153">FastTrack Center prüft den Migrationsanalysebericht und Ihre detaillierten Angaben im Fragebogen.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-153">The FastTrack Center reviews the migration assessment report and tests the details that you supply using the questionnaire.</span></span>   
- <span data-ttu-id="fa6a4-154">Die vom FastTrack Center vorgeschlagenen Korrekturen müssen von Ihnen durchgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-154">Remediation items suggested by the FastTrack Center must be completed by you.</span></span>
    
 <span data-ttu-id="fa6a4-155">**Verantwortlichkeiten des Kunden**</span><span class="sxs-lookup"><span data-stu-id="fa6a4-155">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="fa6a4-156">Korrigieren der Domino-Umgebung auf Grundlage der Vorgaben des FastTrack Centers (z. B. Festlegen der erforderlichen Berechtigungen, die in den E-Mail-Dateien fehlen).</span><span class="sxs-lookup"><span data-stu-id="fa6a4-156">Remediate the Domino environment based on guidelines that the FastTrack Center provides (for example, setting any required permissions that are identified as missing in the mail files).</span></span>  
- <span data-ttu-id="fa6a4-157">Sicherstellen, dass Größe der Domino-Postfächer unter der maximalen für die Migration zulässigen Größe liegt.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-157">Ensure that Domino mailboxes are below the maximum size allowed through migration.</span></span>
    > [!NOTE]
    >  <span data-ttu-id="fa6a4-158">Obwohl FastTrack Postfächer mit bis zu 85 % der maximal zulässigen Zielgröße migriert, birgt die Migration von Postfächern, die größer als 2 GB sind, weitere Risiken, u. a.:</span><span class="sxs-lookup"><span data-stu-id="fa6a4-158">Although FastTrack migrates mailboxes up to 85% of the total allowable target size, attempting to migrate mailboxes larger than 2 GB carries additional risks like:</span></span>    <br/> <span data-ttu-id="fa6a4-p109">Verlängerte Migrationsdauer    </span><span class="sxs-lookup"><span data-stu-id="fa6a4-p109">Lengthened duration of migrations.    </span></span><br/> <span data-ttu-id="fa6a4-p110">Verwenden von Ressourcen, die andernfalls für die Migration anderer Postfächer verwendet werden.    </span><span class="sxs-lookup"><span data-stu-id="fa6a4-p110">Using resources otherwise used for migrating other mailboxes.    </span></span><br/> <span data-ttu-id="fa6a4-161">Deutlich höhere Fehlerraten</span><span class="sxs-lookup"><span data-stu-id="fa6a4-161">A considerable increase in error rates.</span></span> 
- <span data-ttu-id="fa6a4-p111">Vorbereiten der E-Mail-Eingangsdatenbanken und ihrer Zugriffssteuerungslisten (Access Control Lists, ACLs) für die Migration. Sie müssen einige Korrekturaktivitäten abschließen, um E-Mail-Eingangsdatenbanken und die zugehörigen Berechtigungen zu einem freigegebenen Postfach in Exchange Online erfolgreich zu migrieren. Einige diese Schritte lauten wie folgt:</span><span class="sxs-lookup"><span data-stu-id="fa6a4-p111">Prepare the mail-in databases and their access control lists (ACLs) for migration. You must perform some remediation steps to successfully migrate mail-in databases and their permissions to a shared mailbox in Exchange Online. A few of these steps are as follows:</span></span> 
  - <span data-ttu-id="fa6a4-165">Entfernen vorhandener E-Mail-Eingangsdatenbankeinträge aus dem Domino-Verzeichnis und Erstellen neuer Personendatensätze.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-165">Remove existing mail-in database entries in the Domino directory and create new Person records.</span></span>
  - <span data-ttu-id="fa6a4-166">Erstellen E-Mail-aktivierter universeller Sicherheitsgruppen in der lokalen Active Directory-Bereitstellung, die mit Office 365 Azure Active Directory synchronisiert und zum Konfigurieren von Berechtigungen im freigegebenen Postfach in Exchange Online verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-166">Create mail-enabled universal security groups in the on-premises Active Directory that are synchronized to Office 365 Azure Active Directory and used to configure permissions on the shared mailbox in Exchange Online.</span></span> <span data-ttu-id="fa6a4-167">So werden die in der E-Mail-Eingangsdatenbank festgelegten Berechtigungen an das freigegebene Postfach in Exchange Online übergeben.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-167">This transfers the permissions set on the mail-in database over to the shared mailbox in Exchange Online.</span></span>
    
> [!NOTE]
> <span data-ttu-id="fa6a4-168">Es kann nun mit der Endbenutzervorbereitung und Schulungen für das neue Messagingsystem und den Client begonnen werden.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-168">End-user readiness and training for the new messaging system and client can be started now.</span></span> 
  
## <a name="enable-phase"></a><span data-ttu-id="fa6a4-169">Aktivierungsphase</span><span class="sxs-lookup"><span data-stu-id="fa6a4-169">Enable phase</span></span>

 <span data-ttu-id="fa6a4-170">**Wichtige Aktionen**</span><span class="sxs-lookup"><span data-stu-id="fa6a4-170">**Key actions**</span></span>
  
- <span data-ttu-id="fa6a4-171">FastTrack Center:</span><span class="sxs-lookup"><span data-stu-id="fa6a4-171">The FastTrack Center:</span></span> 
    - <span data-ttu-id="fa6a4-172">Richtet die Migrationsumgebung in Azure ein.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-172">Sets up the migration environment in Azure.</span></span>  
    - <span data-ttu-id="fa6a4-173">Konfiguriert die Migrationstools in den lokalen Admin-Arbeitsstationen.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-173">Configures the migration tools on the on-premises admin workstations.</span></span> 
    - <span data-ttu-id="fa6a4-174">Konfiguriert das Tool für den automatischen Import und veranschaulicht die Verwendung von diesem.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-174">Configures and demonstrates how to use the Auto-Import tool.</span></span>  
    - <span data-ttu-id="fa6a4-175">Führt die Überprüfung aller Migrationskomponenten und Migrationstests durch.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-175">Conducts validation of all migration components and performs test migrations.</span></span>
    
 <span data-ttu-id="fa6a4-176">**Verantwortlichkeiten des Kunden**</span><span class="sxs-lookup"><span data-stu-id="fa6a4-176">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="fa6a4-p113">Ihre für die Planung der Postfachmigration zuständigen Mitarbeiter müssen verstehen, wie das Tool für den automatischen Import zu verwenden ist. Sie verwenden dieses Tool für den Import des Migrationszeitplans in die Planungsdatenbank, die das FastTrack Center zum Durchführen von Aktivitäten vor der eigentlichen Migration verwendet.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-p113">Your personnel in charge of scheduling mailbox migration must understand how to use the Auto-Import tool. You use this tool to import the migration schedule into the scheduling database which the FastTrack Center uses to perform pre-migration activities.</span></span> 
- <span data-ttu-id="fa6a4-179">Durchführen von Aktivitäten vor der eigentlichen Migration, z. B. Importieren von Benutzerzeitplänen, Analysieren von Überwachungsberichten, Beheben von Problemen und erneutes Importieren von Benutzerkonten mit Problemen.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-179">Perform pre-migration activities like importing user schedules, analyzing audit reports, remediating any issues, and reimporting user accounts with problems.</span></span>
    
<span data-ttu-id="fa6a4-p114">Aktivitäten vor der eigentlichen Migration werden von Ihnen und dem FastTrack Center koordiniert. Die Replikation auf Azure beginnt nach dem Import des Migrationszeitplans für den Benutzer. </span><span class="sxs-lookup"><span data-stu-id="fa6a4-p114">Pre-migration activities are coordinated between you and the FastTrack Center. Replication to Azure begins after the user migration schedule is imported.</span></span> 
    
> [!NOTE]
> <span data-ttu-id="fa6a4-p115">Die für die Replikation erforderliche Zeit ist von der Datenmenge abhängig. Das FastTrack Center führt dann eine Überwachung durch, um die Migrationsbereitschaft zu bestimmen. Die Ergebnisse werden Ihnen zur Verfügung gestellt. Gewisse Korrekturen sind in der Regel erforderlich. Alle diese Schritte werden „T-Minus"-Aktivitäten genannt, da Sie vor Beginn der geplanten Benutzermigration ausgeführt werden müssen.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-p115">The time required to replicate depends on the amount of data. The FastTrack Center then performs auditing to determine migration readiness. Audit results are provided to you with the understanding that subsequent remediation is normally required. All of these steps are called "T-minus" activities because they must begin in advance of the users' scheduled migration.</span></span> 
  
## <a name="migrate-phase"></a><span data-ttu-id="fa6a4-186">Migrationsphase</span><span class="sxs-lookup"><span data-stu-id="fa6a4-186">Migrate phase</span></span>

 <span data-ttu-id="fa6a4-187">**Wichtige Aktionen**</span><span class="sxs-lookup"><span data-stu-id="fa6a4-187">**Key actions**</span></span>
  
- <span data-ttu-id="fa6a4-188">FastTrack Center:</span><span class="sxs-lookup"><span data-stu-id="fa6a4-188">The FastTrack Center:</span></span>
    - <span data-ttu-id="fa6a4-189">Führt Pilot- und schnelle Migrationen aus. </span><span class="sxs-lookup"><span data-stu-id="fa6a4-189">Performs pilot and velocity migrations.</span></span>  
    - <span data-ttu-id="fa6a4-190">Führt Migrationsereignisse und T-Minus-Aktivitäten durch.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-190">Performs migration events and T-minus activities.</span></span>
    - <span data-ttu-id="fa6a4-191">Bietet Unterstützung nach der Migration.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-191">Provides post-migration assistance.</span></span>
    
 <span data-ttu-id="fa6a4-192">**Verantwortlichkeiten des Kunden**</span><span class="sxs-lookup"><span data-stu-id="fa6a4-192">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="fa6a4-193">Identifizieren und Importieren der Migrationszeitpläne 21 Tage vor der Migration.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-193">Identify and import migration schedules 21 days prior to migration.</span></span>
    > [!NOTE]
    > <span data-ttu-id="fa6a4-p116">Diese Aufgabe ist wichtig, da die Aktivitäten, die vor der eigentlichen Migration durchgeführt werden müssen, Korrekturen und ggf. die wiederholte Replikaterstellung in verschiedenen Phasen vor Beginn der eigentlichen Migration (T-0) umfassen. Während der Migration einiger Postfächer werden an anderen Postfächern T-Minus-Aktivitäten durchgeführt. Eine sorgfältige Planung und Koordination ist daher unabdingbar.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-p116">This task is critical because the pre-migration activities involve remediation and possible retries of replica creation at different stages before the actual migration day (T-0). While some mailboxes are migrating, T-minus activities are being performed on others. This makes proper planning and coordination a must.</span></span> 
- <span data-ttu-id="fa6a4-197">Beheben von Problemen, die während der T-Minus-Aktivitäten festgestellt wurden.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-197">Fix issues identified during T-minus activities.</span></span>
- <span data-ttu-id="fa6a4-198">Ermitteln und Beheben von Domino-Serverproblemen, die sich auf die Migrationsaktivitäten auswirken können.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-198">Address and fix any Domino server issues that impact migration activities.</span></span> 
- <span data-ttu-id="fa6a4-199">Kommunizieren des anstehenden Migrationsdatums für die Endbenutzer.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-199">Conduct end-user communications about the upcoming migration date.</span></span>
- <span data-ttu-id="fa6a4-200">Endbenutzervorbereitung und Schulungen für das neue Messagingsystem und den Client.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-200">Conduct end-user readiness activities and training for the new messaging system and client.</span></span>   
- <span data-ttu-id="fa6a4-p117">Identifizieren und Melden von Problemen nach der Migration. Das FastTrack Center bietet bis zu 5 Tage nach der Migration Unterstützung. Danach liegt dies in Ihrer Verantwortung. Sie können nach der Migration Tickets zu Problemen senden, z. B. fehlende E-Mails, Kalenderelemente und Kontakte oder Duplikate im Postfach.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-p117">Identify and report post-migration issues. The FastTrack Center provides post-migration assistance until T+5 days after migration, after which it becomes your responsibility. You can log post-migration tickets for issues like missing emails, calendar items, and contacts, or for duplicates in the mailbox.</span></span>
    
<span data-ttu-id="fa6a4-204">Das FastTrack Center deckt weder Bereitstellung, noch Lizenzgebühren noch Support ab, der mit der Verzeichnisvorbereitung (einschließlich Synchronisierung von Domino mit dem Active Directory-Verzeichnis), Software für Koexistenz für Notes-Anwendungsinteroperabilität, Self-Service-Migration oder der Migration von Archiven zusammenhängt.</span><span class="sxs-lookup"><span data-stu-id="fa6a4-204">The FastTrack Center doesn't cover deployment, license fees, or assistance related to directory preparation (including Domino-to-Active Directory directory synchronization), coexistence software add-ons for Notes application interoperability, self-service migration, or archive migration.</span></span>
  

  

