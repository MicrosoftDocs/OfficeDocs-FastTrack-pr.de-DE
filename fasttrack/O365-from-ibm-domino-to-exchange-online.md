---
title: Anhang A Migration aus IBM Domino zu Exchange Online
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 11/2/2018
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 7519ee6f-67e6-4064-b1b2-a26f35cdba0b
description: 'Die Migration aus IBM Domino zu Exchange Online umfasst mehrere wichtige Aspekte, einschließlich der Schritte in den folgenden Phasen:'
ms.openlocfilehash: ed901d469d699f081f2ee2726b9e9b94e94cb3df
ms.sourcegitcommit: a8717ee240040292872bc0231f1fb2a22b846806
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 11/01/2018
ms.locfileid: "25895678"
---
# <a name="appendix-a---migration-from-ibm-domino-to-exchange-online"></a>Anhang A: Migration aus IBM Domino zu Exchange Online

Die Migration aus IBM Domino zu Exchange Online umfasst mehrere wichtige Aspekte, einschließlich der Schritte in den folgenden Phasen: 
- [Einleitungsphase](#initiate-phase)   
- [Analysephase](#assess-phase)
- [Korrekturphase](#remediate-phase)  
- [Aktivierungsphase](#enable-phase)  
- [Migrationsphase](#migrate-phase)
    
## <a name="identities"></a>Identitäten

Sie sind für das Erstellen und Verwalten von Identitäten zuständig (nur Cloud, synchronisiert oder mit ihrer lokalen Active Directory-Umgebung verbunden). Sie müssen die Zuordnung der Identitäten (wenn noch nicht vorhanden) zwischen Domino und der lokalen Active Directory-Umgebung oder Azure AD in den frühen Phasen des Onboardings abschließen.
  
## <a name="coexistence"></a>Koexistenz

Der FastTrack Center-Vorteil für Office 365 stellt einen bidirektionalen E-Mail-Fluss zwischen der lokalen Domino-Umgebung und Exchange Online für alle Kunden bereit.
  
## <a name="migration"></a>Migration

Der FastTrack Center-Standardprozess für die Migration aus Domino zu Exchange Online umfasst die Vorabbereitstellung von Domino-Daten für Azure vor der Migration zu Exchange Online-Postfächern. Im Rahmen der FastTrack-Migrationen müssen bestimmte Aktivitäten in verschiedenen Phasen des Onboardings von FastTrack Center-Mitarbeitern und von Ihnen durchgeführt werden. Diese Aktivitäten werden in den folgenden Abschnitten behandelt.
  
> [!NOTE]
> Daten, die mit den FastTrack-Diensten migriert wurden,werden möglicherweise in die USA übermittelt und dort oder in einem anderen Land, in dem Microsoft Einrichtungen unterhält, gespeichert und verarbeitet. Die FastTrack-Dienste sind nicht für Daten vorgesehen, die besonderen rechtlichen oder behördlichen Vorschriften unterliegen. 
  
## <a name="initiate-phase"></a>Einleitungsphase

 **Wichtige Aktionen**
  
- Identifizieren von Domino als Quell-E-Mail-Plattform   
- Bestimmen, ob FastTrack Center die Migration durchführt.
    
 **Verantwortlichkeiten des Kunden**
  
- Bereitstellen grundlegender Informationen über die Quellmessagingplattform und Bestätigen der Migrationsabsicht über das FastTrack Center 
- Befolgen von exemplarischen Vorgehensweisen der FastTrack Center-Leistungsangebotsprozesse  
- Unterzeichnen des FastTrack-Leistungsvertrags
    
## <a name="assess-phase"></a>Analysephase

 **Wichtige Aktionen**
  
- Das FastTrack Center führt einen Workshop zur Migration mit dem Kunden durch. 
- Sie schließen die erforderlichen Migrationsschritte ab, z. B. Migrationsfragebogen und Bereitstellen von Admin-Arbeitsstationen.    
- Die Migrationsanalyse für Domino erfolgt in Ihrer lokalen Umgebung.
    
 **Verantwortlichkeiten des Kunden**
  
- Bereitstellen von Admin-Arbeitsstationen, die das FastTrack Center zum Verwalten der Onboarding- und Migrationsschritte wie Analysieren, Erstellen von Replikaten, Überwachen, Weiterleiten von Einstellungen während der Migration usw. verwendet.
    > [!NOTE]
    > Die Analyse ist für die erfolgreiche Planung und schnelle Durchführung der Migration entscheidend. Sie wird von einem Migrationsarchitekten durchgeführt, der speziellen Zugriff auf die Domino-Umgebung benötigt. Erforderliche Admin-Arbeitsstationskomponenten umfassen einen für den Zugriff auf alle Domino-E-Mail-Quellserver und auf den Azure-Domino-Replikat-Staging-Server konfigurierten Notes-Client. 
- Bereitstellen des Remotezugriffs auf die Admin-Arbeitsstationen, Konten und Berechtigungen für die Durchführung von Analyse- und Migrationsaktivitäten für das Migrationsteam. Dies umfasst die Bereitstellung mehrerer lokaler Konten und Administatorberechtigungen in Exchange Online für die Migration.    
- Öffnen von Firewallports Ausgehende Ports müssen zwischen den Domino-E-Mail-Quellservern und dem Azure-Staging-Server geöffnet werden. Andere Ports für die Kommunikation (z. B. Admin-Arbeitsstationen,Domino-Quellserver und lokale Exchange-Server (sofern vorhanden)) müssen auch geöffnet sein. 
- Aktivieren der übergreifenden Zertifizierung zwischen der Domino-Quellumgebung und dem Azure Domino-Staging-Server zur Erleichterung der Replikation. Übergreifende Zertifizierungsaufgaben vom Domino-Administrator des Kunden und dem FastTrack Center koordiniert.  
- Ausfüllen des Migrationsfragebogens, in dem die für die Konfiguration der Migrationsumgebung in Azure erforderlichen Informationen gesammelt werden (z. B. Tools, Skripts und Migrationsserver).   
- Sicherstellen, dass auf Zielpostfächern in Office 365 das MAPI-Protokoll (Messaging Application Program Interface) aktiviert ist.  
> [!NOTE]
> Einige Office 365-Pläne unterstützen das MAPI-Protokoll nicht. Zum Migrieren von Daten müssen Postfächer aus diesen Plänen in einen Plan konvertiert werden, die MAPI vor dem Migrationsereignis unterstützt. Nach der Migration können diese Pläne wieder zurückgeändert werden. 
  
## <a name="remediate-phase"></a>Korrekturphase

 **Wichtige Aktionen**
  
- FastTrack Center prüft den Migrationsanalysebericht und Ihre detaillierten Angaben im Fragebogen.   
- Die vom FastTrack Center vorgeschlagenen Korrekturen müssen von Ihnen durchgeführt werden.
    
 **Verantwortlichkeiten des Kunden**
  
- Korrigieren der Domino-Umgebung auf Grundlage der Vorgaben des FastTrack Centers (z. B. Festlegen der erforderlichen Berechtigungen, die in den E-Mail-Dateien fehlen).  
- Sicherstellen, dass Größe der Domino-Postfächer unter der maximalen für die Migration zulässigen Größe liegt.
    > [!NOTE]
    >  Obwohl FastTrack Postfächer mit bis zu 85 % der maximal zulässigen Zielgröße migriert, birgt die Migration von Postfächern, die größer als 2 GB sind, weitere Risiken, u. a.:    <br/> Verlängerte Migrationsdauer    <br/> Verwenden von Ressourcen, die andernfalls für die Migration anderer Postfächer verwendet werden.    <br/> Deutlich höhere Fehlerraten 
- Vorbereiten der E-Mail-Eingangsdatenbanken und ihrer Zugriffssteuerungslisten (Access Control Lists, ACLs) für die Migration. Sie müssen einige Korrekturaktivitäten abschließen, um E-Mail-Eingangsdatenbanken und die zugehörigen Berechtigungen zu einem freigegebenen Postfach in Exchange Online erfolgreich zu migrieren. Einige diese Schritte lauten wie folgt: 
  - Entfernen vorhandener E-Mail-Eingangsdatenbankeinträge aus dem Domino-Verzeichnis und Erstellen neuer Personendatensätze.
  - Erstellen E-Mail-aktivierter universeller Sicherheitsgruppen in der lokalen Active Directory-Bereitstellung, die mit Office 365 Azure AD synchronisiert und zum Konfigurieren von Berechtigungen im freigegebenen Postfach in Exchange Online verwendet werden. So werden die in der E-Mail-Eingangsdatenbank festgelegten Berechtigungen an das freigegebene Postfach in Exchange Online übergeben.
    
> [!NOTE]
> Es kann nun mit der Endbenutzervorbereitung und Schulungen für das neue Messagingsystem und den Client begonnen werden. 
  
## <a name="enable-phase"></a>Aktivierungsphase

 **Wichtige Aktionen**
  
- FastTrack Center: 
    - Richtet die Migrationsumgebung in Azure ein.  
    - Konfiguriert die Migrationstools in den lokalen Admin-Arbeitsstationen. 
    - Konfiguriert das Tool für den automatischen Import und veranschaulicht die Verwendung von diesem.  
    - Führt die Überprüfung aller Migrationskomponenten und Migrationstests durch.
    
 **Verantwortlichkeiten des Kunden**
  
- Ihre für die Planung der Postfachmigration zuständigen Mitarbeiter müssen verstehen, wie das Tool für den automatischen Import zu verwenden ist. Sie verwenden dieses Tool für den Import des Migrationszeitplans in die Planungsdatenbank, die das FastTrack Center zum Durchführen von Aktivitäten vor der eigentlichen Migration verwendet. 
- Durchführen von Aktivitäten vor der eigentlichen Migration, z. B. Importieren von Benutzerzeitplänen, Analysieren von Überwachungsberichten, Beheben von Problemen und erneutes Importieren von Benutzerkonten mit Problemen.
    
Aktivitäten vor der eigentlichen Migration werden von Ihnen und dem FastTrack Center koordiniert. Die Replikation auf Azure beginnt nach dem Import des Migrationszeitplans für den Benutzer.  
    
> [!NOTE]
> Die für die Replikation erforderliche Zeit ist von der Datenmenge abhängig. Das FastTrack Center führt dann eine Überwachung durch, um die Migrationsbereitschaft zu bestimmen. Die Ergebnisse werden Ihnen zur Verfügung gestellt. Gewisse Korrekturen sind in der Regel erforderlich. Alle diese Schritte werden „T-Minus"-Aktivitäten genannt, da Sie vor Beginn der geplanten Benutzermigration ausgeführt werden müssen. 
  
## <a name="migrate-phase"></a>Migrationsphase

 **Wichtige Aktionen**
  
- FastTrack Center:
    - Führt Pilot- und schnelle Migrationen aus.   
    - Führt Migrationsereignisse und T-Minus-Aktivitäten durch.
    - Bietet Unterstützung nach der Migration.
    
 **Verantwortlichkeiten des Kunden**
  
- Identifizieren und Importieren der Migrationszeitpläne 21 Tage vor der Migration.
    > [!NOTE]
    > Diese Aufgabe ist wichtig, da die Aktivitäten, die vor der eigentlichen Migration durchgeführt werden müssen, Korrekturen und ggf. die wiederholte Replikaterstellung in verschiedenen Phasen vor Beginn der eigentlichen Migration (T-0) umfassen. Während der Migration einiger Postfächer werden an anderen Postfächern T-Minus-Aktivitäten durchgeführt. Eine sorgfältige Planung und Koordination ist daher unabdingbar. 
- Beheben von Problemen, die während der T-Minus-Aktivitäten festgestellt wurden.
- Ermitteln und Beheben von Domino-Serverproblemen, die sich auf die Migrationsaktivitäten auswirken können. 
- Kommunizieren des anstehenden Migrationsdatums für die Endbenutzer.
- Endbenutzervorbereitung und Schulungen für das neue Messagingsystem und den Client.   
- Identifizieren und Melden von Problemen nach der Migration. Das FastTrack Center bietet bis zu 5 Tage nach der Migration Unterstützung. Danach liegt dies in Ihrer Verantwortung. Sie können nach der Migration Tickets zu Problemen senden, z. B. fehlende E-Mails, Kalenderelemente und Kontakte oder Duplikate im Postfach.
    
Das FastTrack Center deckt weder Bereitstellung, noch Lizenzgebühren noch Support ab, der mit der Verzeichnisvorbereitung (einschließlich Synchronisierung von Domino mit dem Active Directory-Verzeichnis), Software für Koexistenz für Notes-Anwendungsinteroperabilität, Self-Service-Migration oder der Migration von Archiven zusammenhängt.
  

  

