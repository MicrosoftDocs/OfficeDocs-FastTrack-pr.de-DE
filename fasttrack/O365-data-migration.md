---
title: Datenmigration
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack-Spezialisten bieten Anleitung zu Schritten für die Datenmigration in Office 365. Dies steht für alle berechtigten Kunden mit Office 365-Diensten für Exchange Online, OneDrive for Business und SharePoint Online zur Verfügung.
ms.openlocfilehash: 7780af3d5edcdbdf21acba1d421bf379967305fa
ms.sourcegitcommit: 850211891e549e582e649a1dacdc2aa79b520b39
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/01/2020
ms.locfileid: "45011309"
---
# <a name="data-migration"></a>Datenmigration

Sie verfügen möglicherweise über Daten in Ihrer Quellumgebung, die Sie zu Office 365 migrieren möchten.

**Für Office 365-Mandanten mit 150–499 Lizenzen:** Wir unterstützen Sie mit einer Kombination aus Tools und Dokumentation, damit Ihre Migration reibungslos und effizient verläuft. 

**Für Office 365-Mandanten mit 500 oder mehr Lizenzen\*:** Datenmigrationsdienste sind für Exchange Online, SharePoint Online und OneDrive for Business verfügbar. Zu Ihren FastTrack-Vorteilen gehört, dass wir Sie bei der Integration der Quellumgebung und bei der Datenmigration unterstützen.
  
\*Wenn Sie einen kommerziellen Plan vor dem 01.09.2017 erworben oder verlängert haben, sind 150 Lizenzen die Mindestanforderung für die gesamte Laufzeit Ihres aktuellen Abonnements, um die Vorteile der Migration zu erhalten. Bei Plänen für Bildungseinrichtungen sind nur bezahlte Lizenzen  für Lehrpersonal und Mitarbeiter für Migrationsdienste berechtigt. 
  
> [!NOTE]
> Daten, die mit den FastTrack-Diensten migriert wurden,werden möglicherweise in Länder übermittelt, in denen Microsoft Einrichtungen unterhält, und dort gespeichert und verarbeitet (sofern nicht anders für das FastTrack-Angebot festgelegt). Die FastTrack-Dienste sind nicht für Daten vorgesehen, die besonderen rechtlichen oder behördlichen Vorschriften unterliegen. 
  
> [!NOTE]
> Unvorhergesehene Probleme (einschließlich, jedoch nicht beschränkt auf nicht lesbare oder beschädigte Elemente in der Quellumgebung) können verhindern, dass einige Elemente migriert werden. 
  
> [!NOTE]
> Migrationsunterstützung ist in den folgenden Sprachen verfügbar: Deutsch, traditionelles und vereinfachtes Chinesisch (Ressourcen sprechen nur Man), Englisch, Französisch, Italienisch, Japanisch, Portugiesisch (Brasilien) und Spanisch. 
  
> [!NOTE]
> Falls eine Integration erforderlich ist, muss sich Ihre Quellumgebung auf der Mindeststufe für die jeweilige Anwendung befinden. 
  
> [!NOTE]
> Neu im März 2020: Microsoft stellt sechsmonatige [Office 365 E1](https://docs.microsoft.com/microsoftteams/e1-trial-license)- und [Office 365 G1](https://docs.microsoft.com/microsoftteams/g1-trial-license)-Testlizenzen zur Verfügung, um Kunden bei Remotearbeit und Fernunterricht im Zuge des Ausbruchs von COVID-19 zu unterstützen. Ausnahmsweise stellt FastTrack von März 2020 bis August 2020 Datenmigrationsdienste für Mandanten mit 500 oder mehr Lizenzen dieser Testversionen sowie für [Office 365 A1](https://www.microsoft.com/microsoft-365/academic/compare-office-365-education-plans?activetab=tab:primaryr1) für Schüler und Studenten zur Verfügung. Microsoft behält sich das Recht vor, dieses Angebot jederzeit ohne vorherige Ankündigung zu kündigen, zu ändern oder auszusetzen.

In der folgenden Tabelle werden die Anforderungen an Ihre vorhandene Quellumgebung für die Migration beschrieben.
  

|**Aktivität**|**Anforderung an die Quellumgebung**|
|:-----|:-----|
|**Exchange Online-Migration**  <br/> | Microsoft migriert jede beliebige Kombination der unten aufgeführten Quellumgebungen, wobei die Umgebungen jeweils nacheinander migriert werden. Wir können das Onboarding-Messagingsystem über FastTrack Center migrieren, oder nachdem es die FastTrack Center-Überprüfungen erfolgreich abgeschlossen hat. Dies umfasst:  <br/>  Eine einzelne oder mehrere Active Directory-Gesamtstrukturen mit einer einzelnen oder mehreren Exchange-Organisationen, wenn Exchange 2010 Hybrid und implementiert ist und die Exchange-E-Mail-Systeme von 2003 oder höher sind.  <br/>  Eine einzelne IMAP-fähige E-Mail-Umgebung.  <br/>  G Suite-Umgebungen (nur Gmail, Kontakte und Kalender) <br/> <br/> **Hinweis** *Das Exchange Online-Onboarding muss vor der Migration abgeschlossen sein.* <br/> <br/> **Hinweis** *FastTrack migriert nur zu aktiven Office 365-Postfächern.* <br/> <br/> **Hinweis** *Informationen zu lokalen Exchange-Abhängigkeiten finden Sie unter [Voraussetzungen für die Hybridbereitstellung](https://go.microsoft.com/fwlink/?LinkId=787528).* <br/><br/> **Hinweis** *Bei der Migration mehrerer Quellmessagingumgebungen (z. B. mehrere Exchange-Organisationen oder mehrere Domino-Domänen) finden diese Migrationen sequenziell statt.*| 
|**SharePoint Online-Migration**  <br/> | Dateifreigaben (SMB [Server Message Block]-Dateifreigaben auf Geräten mit Unterstützung für SMB 2.0 und höher) <br/> Einzelne G Suite-Umgebung (nur Google Drive).<br/>  Box (Starter, Business, Enterprise).  <br/> Dropbox für Teams (Standard und Erweitert).<br/> |
|**OneDrive for Business-Migration**  <br/> | Dateifreigaben (SMB-Dateifreigaben auf Geräten mit Unterstützung für SMB 2.0 und höher)  <br/>  Einzelne G Suite-Umgebung (nur Google Drive).  <br/>  Box (Starter, Business, Enterprise). <br/> Dropbox für Teams (Standard und Erweitert).<br/><br/> **Hinweis** *FastTrack migriert nur zu aktiven Office 365-Laufwerken.*|
   
## <a name="migration-to-exchange-online"></a>Migration zu Exchange Online
''
### <a name="enable-to-migrate"></a>Aktivieren der Migration
  
Wenn Sie Microsoft zum Migrieren Ihrer E-Mails verwenden, wird eine Anleitung bereitgestellt, um sowohl Exchange Online als auch die Quellumgebung für die Migration zu aktivieren. Abhängig von der Quellumgebung werden möglicherweise verschiedene Schritte für die Aktivierung ausgeführt. Wir bieten Anleitung durch eine Kombination von Tools und Dokumentationen und führen gegebenenfalls Konfigurationsaufgaben aus. Bei zutreffenden Parametern migrieren wir die Postfächer, überwachen Aufträge und stellen Statusberichte bereit.
"Microsoft benötigt für die Durchführung von Migrationsaktivitäten entsprechenden Zugriff und Berechtigungen zu Ihrem E-Mail-System.
  
### <a name="migration-policy-and-steps"></a>Migrationsrichtlinie und -schritte
  
> [!NOTE]
> Ein Migrationszeitraum ist ein Migrationsbatch.

#### <a name="commercial-and-uk-government"></a>Commercial und UK Government

Migrationen werden anhand einer standardisierten und vorher festgelegten 24x7-Basis in vordefinierten Migrationszeiträumen durchgeführt. Es gibt drei Migrationsbatches pro Migrationstag.

#### <a name="us-governmentdod"></a>US Government/DOD

Migrationen werden anhand einer standardisierten und vorher festgelegten 24x5-Basis in vordefinierten Migrationszeiträumen durchgeführt. Es gibt drei Migrationsbatches pro Migrationstag.Es gibt fünf Migrationstage in der Woche von Montag 2:00 Uhr (Koordinierte Weltzeit, UTC) bis Freitag um Mitternacht (UTC), d. h., dass die letzte geplante Migration am Freitag 20:00 Uhr (UTC) stattfindet.
    
 ### <a name="end-state"></a>Endzustand
  
Im Folgenden finden Sie den erwarteten Endzustand nach einem Migrationsbatch:
- Daten aus entsprechend festgelegten und berechtigten Quellpostfächern in der Quellumgebung werden zu Office 365 migriert. 
- Ein Bericht nach der Migration für den Migrationsbatch wird von Microsoft bereitgestellt.
    
Im Folgenden finden Sie den erwarteten Endzustand, nachdem alle Migrationen abgeschlossen sind:
- Die in der folgenden Tabelle definierten Daten aus berechtigten Quellpostfächern werden zu Office 365 migriert.
- Der zu migrierende Datentyp hängt, wie in der folgenden Tabelle beschrieben, von der Quellumgebung ab.
    
> [!NOTE]
> Sämtliche Quellumgebungen müssen über die neuesten Service Packs (SP) verfügen und die aktuelle Rollup (RU)-/Kumulativen Update (KU)-Ebene für das entsprechende Produkt in der Quellumgebung am Ende der Aktivierungsphase aufweisen. Datenmigrationsdienste unterliegen externen Faktoren, die außerhalb der Kontrolle von Microsoft liegen, z. B. Änderungen an Drittanbieter-APIs, die Änderungen, Verzögerungen oder Unterbrechungen dieser Dienste nach sich ziehen können. Während der Migration mit den FastTrack-Diensten können Sie auf die Daten, die Sie Microsoft zur Verfügung stellen, von einem beliebigen Standort aus zugreifen bzw. sie dort speichern, wo Microsoft oder seine Dienstanbieter Einrichtungen unterhalten. 
  
|||||
|:-----|:-----|:-----|:-----|
|**Quellumgebung**|**Migrationstyp**|**Was wird aus dem Quellpostfach migriert?**|**Was wird nicht migriert?**|
|**Exchange 2003 und höher**|Übernahmemigration| E-Mails <br/> Postfachregeln <br/> Stellvertretungen <br/> Postfachkontakte <br/> Kalender <br/> Aufgaben <br/> E-Mails mit Rechteverwaltung <br/> Verschlüsselte E-Mails| Öffentliche Ordner <br/> Persönliche Kontakte <br/> E-Mail-aktivierte Benutzer <br/> Blockierte oder inaktive Benutzer <br/> Signaturen <br/> Postfachpapierkorb <br/>  E-Mails, die die zulässige Nachrichtengröße überschreiten <br/> Archivdaten <br/> Beschädigte Elemente <br/>  Inaktive Postfächer |
|**Exchange 2003 und Exchange 2007**|Mehrstufige Migration| E-Mails <br/> Postfachregeln <br/> Stellvertretungen <br/> Postfachkontakte <br/> Kalender <br/> Aufgaben <br/> E-Mails mit Rechteverwaltung <br/> Verschlüsselte E-Mails| Öffentliche Ordner <br/> Persönliche Kontakte <br/> E-Mail-aktivierte Benutzer <br/> Blockierte oder inaktive Benutzer <br/> Signaturen <br/> Postfachpapierkorb <br/> E-Mails, die die zulässige Nachrichtengröße überschreiten <br/> Archivdaten <br/> Beschädigte Elemente <br/> Inaktive Postfächer |
|**Exchange 2010, Exchange 2013, Exchange 2016 und Exchange 2019** <br/><br/> **Hinweis** *Informationen zu lokalen Exchange-Abhängigkeiten finden Sie unter [Voraussetzungen für die Hybridbereitstellung](https://go.microsoft.com/fwlink/?LinkId=787528).*           |Migration mit Hybridbereitstellung| E-Mails <br/> Postfachregeln <br/> Stellvertretungen <br/> Postfachkontakte <br/> Kalender <br/> Aufgaben <br/> Signaturen <br/> Persönliches Archiv, das mit dem Benutzerpostfach migriert wird <br/> Wiederherstellbare Elemente <br/> E-Mails mit Rechteverwaltung <br/> Verschlüsselte E-Mails| Öffentliche Ordner <br/> E-Mail, die die zulässige Nachrichtengröße überschreitet. <br/> Journalarchiv oder eine beliebige Archivlösung von Drittanbietern <br/> Blockierte oder inaktive Benutzer <br/> Archivdaten aus PST-Dateien <br/> Beschädigte Elemente <br/> Inaktive Postfächer |
|**G Suite-Umgebung (nur Gmail, Kontakte und Kalender)** <br/> <br/> **Hinweis** *Ihre G Suite-Umgebung muss über Google-APIs verfügen, und das Google Admin SDK muss zur Erweiterung der Funktionalität aktiviert sein.* <br/>          |Übernahmemigration oder mehrstufige Migration| E-Mails <br/> Postfachkontakte\*  <br/> Kalender <br/> Bezeichnungen <br/> \*Es werden maximal drei E-Mail-Adressen pro Kontakt migriert.| Regeln <br/> Stellvertretungen <br/> Signaturen <br/> Aufgaben <br/> E-Mails oder Anhänge, die die zulässige Nachrichtengröße überschreiten <br/> Blockierte oder inaktive Benutzer <br/> Archivdaten aus PST-Dateien oder einer Drittanbieter-Archivlösung (z. B. Google Vault) <br/> E-Mails mit Rechteverwaltung oder Verschlüsselung <br/> Beschädigte Elemente <br/> Google Hangouts\*\* <br/> Google-Gruppen <br/> Ressourcenpostfächer <br/> Inaktive Postfächer <br/> Urlaubseinstellungen und Einstellungen für automatische Antworten <br/> Freigegebene Kalender, Cloudanlagen, Google Hangout-Links und Ereignisfarben <br/>\*\*Hangout-Unterhaltungen, die als Beschriftungen gespeichert wurden, werden migriert. |
|**IMAP4-Quelle (wie Domino, GroupWise und Zimbra)** |Migration mit systemeigenen IMAP4-Tools| E-Mails | Regeln <br/> Stellvertretungen <br/> Verteilerlisten <br/> Externe Kontakte <br/> E-Mail-aktivierte Benutzer <br/> Blockierte oder inaktive Benutzer <br/> Postfachkontakte <br/> Kalender <br/> Signaturen <br/> Aufgaben <br/> E-Mails, die die zulässige Nachrichtengröße überschreiten <br/> Archivdaten <br/> Verschlüsselte E-Mail-Nachrichten <br/> Beschädigte Elemente <br/> Inaktive Postfächer |
   
> [!NOTE]
> Wenn sich Verteilerlisten (MailEnabledGroup-Objekte) und externe Kontakte (MailEnabledContact-Objekte) im lokalen Active Directory befinden, können sie mit Azure AD Connect synchronisiert werden. Sie sind jedoch kein Bestandteil der Postfachdatenmigration. Weitere Informationen finden Sie im Beispiel **Identitätsintegration** unter [Core](O365-onboarding-and-migration.md#core). 
  
FastTrack-Experten führen während einer Migration die folgenden Aufgaben aus:
- Bereitstellen einer Standardvorlage für die Planung von Postfachmigrationen
- Bereitstellen von Informationen über die erforderlichen Berechtigungen für FastTrack-Experten. 
- Erstellen eines vordefinierten Postfachmigrationsplans im vordefinierten Format
- Ausführen der Migration eines einzelnen Postfachs bis zu zweimal in einem Migrationsbatch, bevor die Migration dieses Postfachs als fehlerhafte Migration gemeldet wird.
- Migrieren der Postfachinhalte bei Exchange- und IMAP4-basierten Quellumgebungen bis zu 85 % des Speichergrenzwerts für das Benutzerpostfach (wenn der Speichergrenzwert für Postfächer beispielsweise bei 50 GB liegt, migriert Microsoft bis zu 85 % des 50-GB-Speichergrenzwerts). 
- Aktivieren der SMTP-E-Mail-Weiterleitungskoexistenz zwischen der Quellmessagingumgebung und Office 365 Exchange Online, wenn die Übernahmemigration nicht verwendet wird.
- Bereitstellen von Berichten nach der Migration.
- Bereitstellen von Unterstützung nach der Migration bei kritischen Problemen. Die folgenden Probleme werden als kritisch betrachtet:
  - Datenverlust während der Migration
  - Die Quellumgebung, die während der Migration nicht mehr verfügbar ist
  - Migrationsaktivitäten, die zu Problemen in der Quellumgebung führen
    
Sie führen die folgenden erforderlichen Aufgaben für Migrationen aus:
- Abschließen des Exchange Online-Onboardings oder Ausführen der Überprüfungen über das FastTrack Center.
- Abwickeln der gesamten Kommunikation mit den Endbenutzern.  
- Installieren der entsprechenden Clientsoftwareebene gemäß den Office 365-Richtlinien. Weitere Informationen finden Sie unter [Der moderne Arbeitsplatz](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg). 
- Überprüfen der SMTP-E-Mail-Weiterleitungskoexistenz zwischen der Quellmessagingumgebung und Office 365 Exchange Online, sofern zutreffend.
- Bereitstellen eines Plans in einer definierten Methode und Auflisten der zu migrierenden speziellen Postfächer bei jedem Migrationsereignis.
- Löschen von Postfächern aus dem Plan bis zu 24 Stunden vor dem Migrationsbatch. 
- Planen einer durchschnittlichen maximalen Anzahl von Postfächern in einem Zeitraum von 24 Stunden, wie in der folgenden Tabelle aufgeführt.
    
|||
|:-----|:-----|
|**Anzahl der für die Migration berechtigten Postfächer** <br/> |**Durchschnittliche minimale Anzahl von Postfächern in einem Zeitraum von 24 Stunden** <br/> |
|150-1000  <br/> |25 % der gesamten Anzahl  <br/> |
|1001-5000  <br/> |20 % der gesamten Anzahl  <br/> |
|5001-10000  <br/> |15 % der gesamten Anzahl  <br/> |
|\>10000  <br/> |1500  <br/> |
   
   > [!NOTE]
   > Diese Zahlen basieren auf bewährten Methoden. Die Anzahl der Postfächer, die pro Tag migriert werden, variiert jedoch je nach Umgebung, Bereitstellung und Betriebseinschränkungen. Microsoft kann die Geschwindigkeit der Postfachmigration nicht garantieren. 
  
- Planen von mindestens 35 Postfächern in einem Migrationsbatch 
- Beheben von Fehlern vor der Migration, falls zutreffend  
- Bereitstellen von Zugriff und Berechtigungen für die Quellumgebung für FastTrack-Experten, sodass Migrationsaktivitäten durchgeführt werden können 
- Beschaffen und/oder Bereitstellen lizenzierter Administratorkonten in Office 365, sodass Migrationsaktivitäten ausgeführt werden können (sofern zutreffend) 
- Unterstützen bei clientseitigen Migrationsproblemen und bei Bedarf Ausführen von Vorgängen nach der Migration 
- Migrieren von clientseitigen Daten bei Bedarf. Dies umfasst unter anderem lokale Adressbücher, Daten in lokalen PST-Dateien, Outlook-Regeln und lokale Outlook-Einstellungen.   
- Verringern der Postfachgröße unter 85 % der Office 365-Zielpostfachgröße (falls erforderlich)   
- Durchführen von Aktionen aus dem Migrationsabschlussbericht, einschließlich der Postfächer, die nicht verschoben wurden  
- Beheben von Fehlern nach der Migration und erneutes Planen der Postfächer, falls erforderlich   
- Unterstützung nach der Migration bei kritischen Problemen. Die folgenden Probleme werden als kritisch betrachtet:
  - Datenverlust während der Migration
  - Die Quellumgebung, die während der Migration nicht mehr verfügbar ist
  - Migrationsaktivitäten, die zu Problemen in der Quellumgebung führen
    
Sie müssen den standardmäßigen Migrationsprozess befolgen und sich mit Microsoft entsprechend in Verbindung setzen, indem Sie den Zugriff und die Berechtigungen für die Quelle und die Office 365-Umgebungen gewähren, Migrationspläne bereitstellen, alle Ursachen für Fehler bei der Migration beseitigen usw. Außerdem müssen Sie sich mit den Endbenutzern hinsichtlich der Kommunikation, des Postfachmigrationsplans und des Behebens von Migrationsproblemen bei Endbenutzern in Verbindung setzen.
  
> [!NOTE]
> Migrationen verwenden nur Konten, die den beim Onboarding definierten Sicherheitsanforderungen entsprechen. Wenn Sie nicht solche Konten verwenden, können möglicherweise Verzögerungen bei der Migration auftreten. 
  
## <a name="migration-to-sharepoint-online"></a>Migration zu SharePoint Online

### <a name="enable-to-migrate"></a>Aktivieren der Migration
  
Wenn Sie Microsoft zum Migrieren Ihrer Daten verwenden, wird eine Anleitung bereitgestellt, um sowohl SharePoint Online als auch die Quellumgebung für die Migration zu aktivieren. Abhängig von der Quelle werden möglicherweise verschiedene Schritte für die Aktivierung ausgeführt. Wir bieten Anleitung durch eine Kombination von Tools und Dokumentationen und führen gegebenenfalls Konfigurationsaufgaben aus.
  
Sie müssen Microsoft den entsprechenden Zugriff und die entsprechenden Berechtigungen zum Ausführen einiger Aktivitäten bereitstellen.
  
### <a name="migration-policy-and-steps"></a>Migrationsrichtlinie und -schritte
  
> [!NOTE]
> Ein Migrationszeitraum ist ein Migrationsbatch.

#### <a name="commercial-and-uk-government"></a>Commercial und UK Government

Migrationen werden anhand einer standardisierten und vorher festgelegten 24x7-Basis in vordefinierten Migrationszeiträumen durchgeführt. Es gibt drei Migrationsbatches pro Migrationstag.

#### <a name="us-governmentdod"></a>US Government/DOD

Migrationen werden anhand einer standardisierten und vorher festgelegten 24x5-Basis in vordefinierten Migrationszeiträumen durchgeführt. Es gibt drei Migrationsbatches pro Migrationstag.Es gibt fünf Migrationstage in der Woche von Montag 2:00 Uhr (Koordinierte Weltzeit, UTC) bis Freitag um Mitternacht (UTC), d. h., dass die letzte geplante Migration am Freitag 20:00 Uhr (UTC) stattfindet.

- Alle Migrationen unterliegen den SharePoint Online-Kontingenten, die unter [SharePoint Online und OneDrive for Business: Softwarebeschränkungen und-Grenzen](https://go.microsoft.com/fwlink/?LinkID=616612) erläutert werden.   
- Der Gesamtbetrag der migrierten Daten ist auf 75 % des SharePoint Online-Gesamtspeicherkontingents, für das Sie berechtigt sind, beschränkt (einschließlich den zusätzlichen Speicher, den Sie möglicherweise separat gekauft haben).
    
 ### <a name="end-state"></a>Endzustand
  
Im Folgenden finden Sie den erwarteten Endzustand nach einem Migrationsbatch: 
- Daten aus entsprechend festgelegten und berechtigten Quellen in der Quellumgebung werden zu SharePoint Online migriert.   
- Ein Bericht nach der Migration für den Migrationsbatch wird von Microsoft bereitgestellt.
    
Im Folgenden finden Sie den erwarteten Endzustand, nachdem alle Migrationen abgeschlossen sind: 
- Die in der folgenden Tabelle definierten Daten aus berechtigten Quellen werden zu Office 365 migriert.  
- Der zu migrierende Datentyp hängt, wie in der folgenden Tabelle beschrieben, von der Quellumgebung ab:
    
|||||
|:-----|:-----|:-----|:-----|
|**Quellumgebung** <br/> |**Migrationstyp** <br/> |**Was wird migriert?** <br/> |**Was wird nicht migriert?** <br/> |
|**Alle Dateifreigabegeräte mit Unterstützung für SMB 2.0 und höher**  <br/> |Einzeln oder mehrstufig  <br/> | Dokumente  <br/>  Datei- und Ordnerstruktur  <br/>  Datei- und Ordnerberechtigungen auf Benutzerebene\*  <br/>  Datei- und Ordnerberechtigungen auf Gruppenebene\*  <br/>  Dateien unter 15 GB  <br/>  Grundlegende Dokument- und Ordnermetadaten:   <br/>  Erstellungsdatum  <br/>  Änderungsdatum  <br/>  Erstellt von  <br/>  Zuletzt geändert von  <br/><br/> \**Setzt die Konfiguration der Verzeichnissynchronisierung voraus. Es werden nur NTFS-Berechtigungen migriert, die für den Windows-Datei-Explorer verfügbar sind. Berechtigungen, die direkt auf Dateifreigabegeräten verwaltet werden, werden nicht migriert. Wenn Daten auf einem SMB 2.0-Gerät gespeichert werden, werden die NTFS-äquivalenten Berechtigungen, die vom SMB-Protokoll verfügbar gemacht werden, migriert.* <br/> | Besitzverlauf und frühere Versionen  <br/>  Konvertierung eingebetteter URLs im Inhalt  <br/>  Frühere Versionen  <br/>  Windows-Datei-/-Ordnerattribute (z. B. „Schreibgeschützt“ und „Ausgeblendet“)   <br/>  Nicht-Windows-NTFS-Dateisystem (New Technology File System) und erweiterte NTFS-Berechtigungen sowie besondere Einstellungen:  <br/>  Explizite Verweigerungsberechtigungen (werden nach der Migration entfernt, Inhalte unterliegen parallelen Berechtigungen oder Berechtigungen im übergeordneten Ordner).  <br/>  Konfiguration der NTFS-Überwachung  <br/>  Zusätzliche Dateimetadaten von der Dateiklassifizierungsinfrastruktur (File Classification Infrastructure, FCI)  <br/>  Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann  <br/>  Ausgeblendete Freigaben  <br/>  Freigabe (z. B. gewährte Berechtigungen auf Freigabeebene)  <br/>  Dateien oder Ordner, die die aktuellen [Einschränkungen und Begrenzen von SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) überschreiten <br/> |
|**Einzelne G Suite-Umgebung (nur Google Drive)**  <br/> |Einzeln oder mehrstufig  <br/> | <br/>  Google Docs, Google Tabellen und Google Präsentationen (Dateien werden in das entsprechende Office-Format konvertiert), einschließlich derjenigen über 10 MB <br/>  Datei- und Ordnerstruktur  <br/>  Berechtigungen für Ordner auf Benutzerebene  <br/>  Berechtigungen für Ordner auf Gruppenebene <br/>  Dateien unter 15 GB  <br/> Grundlegende Dokument- und Ordnermetadaten:  <br/> Erstellungsdatum  <br/>  Änderungsdatum  <br/>  Erstellt von  <br/>  Zuletzt geändert von  <br/> Freigegebene Laufwerke (Ordner und Dateien) <br/>  Freigegebene Inhalte im Besitz des Google Drive-Kontos, das migriert wird (wenn explizit für Benutzer oder Gruppen freigegeben)\*  <br/><br/> \**Verwenden Sie Google Drive Admin, um die externen Konten zu identifizieren. Weisen Sie Endbenutzer an, ihre Inhalte nach der Migration erneut freizugeben.* <br/> | Besitzverlauf, frühere Versionen und Kommentare <br/>  Beschreibungen von Dateien und Ordnern, Ordnerfarben  <br/>  Berechtigungen für Dateien auf Benutzerebene  <br/>  Berechtigungen für Dateien auf Gruppenebene  <br/>  Erweiterte Metadaten  <br/>  Attribute für Dateisperre  <br/>  Konvertierung eingebetteter URLs im Inhalt  <br/>  Gelöschte Elemente  <br/>  Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann  <br/>  Blockierte oder inaktive Benutzer  <br/>  Google Fotos, Google Formulare, Google Maps und andere verbundene Apps  <br/>  Google Zeichnungen  <br/>  Freigegebene Inhalte außerhalb Ihrer Organisation  <br/> Inhalte, die nicht im Besitz des Google Drive-Kontos sind, das migriert wird <br/>Berechtigungen und grundlegende Metadaten externer Benutzer  <br/> Mitgliedsberechtigungen für freigegebene Laufwerke\* <br/> Dateien oder Ordner, die die aktuellen [Einschränkungen und Begrenzen von SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) überschreiten <br/> <br/> \**Verwenden Sie Google Drive Admin, um die externen Konten zu identifizieren. Weisen Sie Endbenutzer an, ihre Inhalte nach der Migration erneut freizugeben.* <br/>|
|**Box (Starter, Business, Enterprise)**  <br/> |Einzeln oder mehrstufig  <br/> | Dokumente  <br/>  Datei- und Ordnerstruktur  <br/>  Berechtigungen für Ordner auf Benutzerebene  <br/>  Berechtigungen für Ordner auf Gruppenebene  <br/>  Dateien unter 15 GB  <br/>  Grundlegende Dokument- und Ordnermetadaten:   <br/>  Erstellungsdatum  <br/>  Änderungsdatum  <br/>  Erstellt von  <br/>  Zuletzt geändert von  <br/>  Freigegebene Inhalte im Besitz des Box-Kontos, das migriert wird (wenn explizit für Benutzer oder Gruppen freigegeben)\*  <br/><br/> \**Verwenden Sie Box-Berichte, um die externen Konten zu identifizieren. Weisen Sie Endbenutzer an, ihre Inhalte nach der Migration erneut freizugeben.* <br/> | Besitzverlauf, frühere Versionen und Kommentare <br/>  Berechtigungen für Dateien auf Benutzerebene  <br/>  Berechtigungen für Dateien auf Gruppenebene  <br/>  Beschreibungen von Dateien und Ordnern  <br/>  Box-Tags und erweiterte Metadaten  <br/>  Attribute für Dateisperre  <br/>  Konvertierung eingebetteter URLs im Inhalt  <br/>  Gelöschte Elemente  <br/>  Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann  <br/>  Blockierte oder inaktive Benutzer  <br/>  Box-Hinweise (nicht funktional, da diese ohne Konvertierung migriert werden)  <br/>  Box-Apps, Lesezeichen, Favoriten und Workflows  <br/>  Inhalte, die nicht im Besitz des migrierten Box-Kontos sind (freigegebene Ordner)  <br/>  Berechtigungen und grundlegende Metadaten externer Benutzer\*  <br/>  Dateien oder Ordner, die die aktuellen [Einschränkungen und Begrenzen von SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) überschreiten <br/> <br/>\**Verwenden Sie Google Drive Admin, um die Mitgliedschaft für das freigegebene Laufwerk zu identifizieren. Weisen Sie Endbenutzer an, die Mitgliedschaftseinstellungen vor der Migration auf dem Ziel zu konfigurieren.* |
|**Dropbox für Teams (Standard und Erweitert)**  <br/> |Einzeln oder mehrstufig  <br/> | Dokumente  <br/>  Datei- und Ordnerstruktur  <br/>  Berechtigungen für Ordner auf Benutzerebene  <br/>  Berechtigungen für Ordner auf Gruppenebene  <br/>  Dateien unter 15 GB  <br/>  Grundlegende Dokument- und Ordnermetadaten:   <br/>  Erstellungsdatum  <br/>  Änderungsdatum  <br/>  Erstellt von  <br/>  Zuletzt geändert von  <br/> Freigegebene Teamordner und -inhalte <br/>  Freigegebene Inhalte im Besitz des Dropbox-Kontos, das migriert wird (wenn explizit für Benutzer oder Gruppen freigegeben)\*  <br/> <br/> \**Verwenden Sie Dropbox-Berichte, um die externen Konten zu identifizieren. Weisen Sie Endbenutzer an, ihre Inhalte nach der Migration erneut freizugeben.* <br/> | Besitzverlauf, frühere Versionen und Kommentare <br/>  Beschreibungen von Dateien und Ordnern <br/>  Berechtigungen für Dateien auf Benutzerebene  <br/>  Berechtigungen für Dateien auf Gruppenebene    <br/> Erweiterte Metadaten  <br/>  Attribute für Dateisperre  <br/>  Konvertierung eingebetteter URLs im Inhalt  <br/>  Gelöschte Elemente  <br/>  Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann  <br/>  Nicht gemountete Dropbox-Ordner <br/>  Gelöschte oder getrennte Benutzer <br/>  Dropbox Paper, Showcases und Spaces  <br/> Dropbox-Apps und Favoriten (Pins/Sterne) <br/> Inhalte, die nicht im Besitz des migrierten Dropbox-Kontos sind  <br/>  Berechtigungen und grundlegende Metadaten externer Benutzer\*  <br/>  Dateien oder Ordner, die die aktuellen [Einschränkungen und Begrenzen von SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) überschreiten <br/> <br/> \**Verwenden Sie Dropbox-Berichte, um die externen Konten zu identifizieren. Weisen Sie Endbenutzer an, ihre Inhalte nach der Migration erneut freizugeben.* <br/> |
   
FastTrack-Spezialisten führen die folgenden erforderlichen Aufgaben für Migrationen aus: 
- Durchführen eines Workshops zur exemplarischen Vorgehensweise bei der Migration, bei dem der Migrationsprozess und der Ansatz für das ausgewählte Migrationsszenario erläutert werden.
- Bereitstellen der erforderlichen Komponenten für Analyse- und Migrationstools, sofern für das Szenario zutreffend.   
- Bereitstellen der erforderlichen Komponenten für den Zugriff auf die Quell- und Zielumgebung für das Durchführen der Analyse und der Migration für das Migrationsteam 
- Bereitstellen von Analysetools zum Durchführen der Analyse der Quell- und Zielumgebung oder Bereitstellen von Anleitungen zur Verwendung systemeigener Quellplattformfunktionen zum Erstellen von Analyseberichten   
- Unterstützung beim Bereitstellen und Ausführen von Analyse- und Migrationstools (sofern zutreffend)   
- Konfigurieren der Migrationsinfrastruktur als Vorbereitung auf die Inhaltsmigration (sofern zutreffend)    
- Durchführen einer Testmigration zur Überprüfung der Migrationsinfrastruktur und der erforderlichen Komponenten   
- Bereitstellen vordefinierter SharePoint Online-Zielwebsites im Rahmen der Migration    
- Durchführen einer Pilotmigration vor Beginn der Migration   
- Bereitstellen einer Anleitung für die Migrationsplanung für das ausgewählte Szenario 
- Durchführen der einzelnen Inhaltsmigrationsstufen gemäß dem Migrationszeitplan, der vom Kunden bereitgestellt und von FastTrack-Ressourcen überprüft wurde   
- Bereitstellen der Migrationsergebnisse nach jedem Migrationsfenster   
- Unterstützung bei Selektierung von Migrationsfehlern und möglichen Lösungen   
- Bereitstellen eines endgültigen Migrationsberichts für jedes Migrationsfenster   
- Unterstützung nach der Migration während Benutzerakzeptanztests bis zu fünf Tage nach Abschluss der Migration
    
Sie führen die folgenden erforderlichen Aufgaben für Migrationen aus: 
- Bereitstellen der für die Analyse- und Migrationsaktivitäten empfohlenen Projektressourcen Zu diesen zählen: 
  - Projektmanagement 
  - Benutzerakzeptanztests (User Acceptance Testing, UAT)  
  - Für die Quell- und Zielinhaltsplattformen verantwortlichen Administratoren.  
- Bereitstellen der Infrastrukturvoraussetzungen für die Analyse- und Migrationsaktivitäten (falls erforderlich)  
- Bereitstellen von Zugriff und Berechtigungen für die Quell- und Zielumgebungen für FastTrack-Experten, sodass Migrationsaktivitäten durchgeführt werden können (falls erforderlich)
    > [!NOTE]
    > Migrationen verwenden nur Konten, die den beim Onboarding definierten Sicherheitsanforderungen entsprechen. Wenn Sie nicht solche Konten verwenden, können möglicherweise Verzögerungen bei der Migration auftreten. 
- Bereitstellen von erforderlichen Komponenten und Durchführen von Aktivitäten, die zur Unterstützung der Analyse und Migration erforderlich sind.   
- Installieren der FastTrack-Analysetools und Ausführen der Analysedatensammlungs-Aktivitäten (sofern zutreffend)   
- Lokale Installation der bereitgestellten FastTrack-Migrationssoftware (sofern zutreffend)   
- Ausführen von Korrekturaktivitäten, die im von FastTrack bereitgestellten Wartungsbericht beschrieben sind (sofern zutreffend).  
- Bereitstellen eines Migrationszeitplans mithilfe von FastTrack-Vorlagen und -Anleitungen   
- Durchführen der Qualitätssicherung für die Migration und der Benutzerakzeptanztests   
- Durchführen von Korrekturen nach der Migration (sofern zutreffend)
- Planen und Implementieren der Änderungsverwaltung und Endbenutzerkommunikation (sofern zutreffend)   
- Verwalten und Konfigurieren aller für eine erfolgreiche Durchführung der Analyse- und Migrationsaktivitäten erforderlichen Änderungen am Quellsystem bzw. an den Quellgeräten
- Bereitstellen eines Plans in einer definierten Methode und Auflisten der zu migrierenden speziellen Benutzerdaten bei jedem Migrationsereignis (mindestens drei (3) Tage im Voraus).
- Löschen von Benutzerdaten aus dem Plan bis zu 24 Stunden vor dem Migrationsbatch. Zu diesem Zeitpunkt ist dies der Plan für den letzten Migrationsbatch.
> [!NOTE]
> Microsoft übernimmt keine Garantie für die Geschwindigkeit der Dateimigration.
    
## <a name="migration-to-onedrive-for-business"></a>Migration zu OneDrive for Business

 ### <a name="enable-to-migrate"></a>Aktivieren der Migration
  
Wenn Sie Microsoft zum Migrieren Ihrer Daten verwenden, wird eine Anleitung bereitgestellt, sodass Sie sowohl OneDrive for Business als auch die Quellumgebung für die Migration aktivieren können. Abhängig von der Quelle werden möglicherweise verschiedene Schritte für die Aktivierung ausgeführt. Wir helfen Ihnen bei einigen Aktivitäten mit einer Kombination von Tools, Dokumentationen und Anleitungen und führen gegebenenfalls Konfigurationsaufgaben aus.
  
Sie können Microsoft ggf. den entsprechenden Zugriff und die jeweiligen Berechtigungen zur Verfügung stellen, sodass bestimmte Aktivitäten durchgeführt werden können. Wenn Sie keinen Zugriff und/oder keine Berechtigungen gewähren, müssen Sie bestimmte definierte Aufgaben selbst unter der Anleitung von Microsoft durchführen. 
  
### <a name="migration-policy-and-steps"></a>Migrationsrichtlinie und -schritte
  
> [!NOTE]
> Ein Migrationszeitraum ist ein Migrationsbatch.

#### <a name="commercial-and-uk-government"></a>Commercial und UK Government

Migrationen werden anhand einer standardisierten und vorher festgelegten 24x7-Basis in vordefinierten Migrationszeiträumen durchgeführt. Es gibt drei Migrationsbatches pro Migrationstag.

#### <a name="us-governmentdod"></a>US Government/DOD

Migrationen werden anhand einer standardisierten und vorher festgelegten 24x5-Basis in vordefinierten Migrationszeiträumen durchgeführt. Es gibt drei Migrationsbatches pro Migrationstag.Es gibt fünf Migrationstage in der Woche von Montag 2:00 Uhr (Koordinierte Weltzeit, UTC) bis Freitag um Mitternacht (UTC), d. h., dass die letzte geplante Migration am Freitag 20:00 Uhr (UTC) stattfindet.
    
- Für alle Migrationen sind der entsprechende Zugriff und die jeweiligen Berechtigungen für die Quellumgebung erforderlich.   
- Alle Migrationen unterliegen den OneDrive for Business-Kontingenten, die in [SharePoint Online und OneDrive for Business: Softwarebeschränkungen und-Grenzen](https://go.microsoft.com/fwlink/?LinkId=698855) erläutert werden.
    
 ### <a name="end-state"></a>Endzustand
  
Im Folgenden finden Sie den erwarteten Endzustand nach einem Migrationsbatch:  
- Daten aus entsprechend festgelegten und berechtigten Quellen in der Quellumgebung werden zu OneDrive for Business migriert.  
- Ein Bericht nach der Migration für den Migrationsbatch wird von Microsoft bereitgestellt.
    
Im Folgenden finden Sie den erwarteten Endzustand, nachdem alle Migrationen abgeschlossen sind:
- Die in der folgenden Tabelle definierten Daten aus berechtigten Quellen werden zu Office 365 migriert.  
- Der zu migrierende Datentyp hängt, wie in der folgenden Tabelle beschrieben, von der Quellumgebung ab.
    
|||||
|:-----|:-----|:-----|:-----|
|**Quellumgebung**|**Migrationstyp**|**Was wird migriert?**|**Was wird nicht migriert?**|
|**Alle Dateifreigabegeräte mit Unterstützung für SMB 2.0 und höher**  <br/> |Einzeln oder mehrstufig  <br/> | Dokumente  <br/>  Datei- und Ordnerstruktur  <br/>  Datei- und Ordnerberechtigungen auf Benutzerebene\*  <br/>  Datei- und Ordnerberechtigungen auf Gruppenebene\*  <br/>  Dateien unter 15 GB  <br/>  Grundlegende Dokument- und Ordnermetadaten:   <br/>  Erstellungsdatum  <br/>  Änderungsdatum  <br/>  Erstellt von  <br/>  Zuletzt geändert von  <br/> <br/>\**Setzt die Konfiguration der Verzeichnissynchronisierung voraus. Es werden nur NTFS-Berechtigungen migriert, die für den Windows-Datei-Explorer verfügbar sind. Berechtigungen, die direkt auf Dateifreigabegeräten verwaltet werden, werden nicht migriert. Wenn Daten auf einem SMB 2.0-Gerät gespeichert werden, werden die NTFS-äquivalenten Berechtigungen, die vom SMB-Protokoll verfügbar gemacht werden, migriert.* <br/> | Besitzverlauf und frühere Versionen  <br/>  Konvertierung eingebetteter URLs im Inhalt  <br/>  Frühere Versionen  <br/>  Windows-Datei-/-Ordnerattribute (z. B. „Schreibgeschützt“ und „Ausgeblendet“)   <br/>  Nicht-Windows-NTFS-Dateisystem (New Technology File System) und erweiterte NTFS-Berechtigungen sowie besondere Einstellungen:  <br/>  Explizite Verweigerungsberechtigungen (werden nach der Migration entfernt, Inhalte unterliegen parallelen Berechtigungen oder Berechtigungen im übergeordneten Ordner).  <br/>  Konfiguration der NTFS-Überwachung  <br/>  Zusätzliche Dateimetadaten von der Dateiklassifizierungsinfrastruktur (FCI)  <br/>  Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann  <br/>  Ausgeblendete Freigaben  <br/>  Freigabe (z. B. gewährte Berechtigungen auf Freigabeebene)  <br/>  Dateien oder Ordner, die die aktuellen [Einschränkungen und Begrenzen von SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) überschreiten <br/> |
|**Einzelne G Suite-Umgebung (nur Google Drive)**  <br/> |Einzeln oder mehrstufig  <br/> | Google Docs, Google Tabellen und Google Präsentationen (Dateien werden in das entsprechende Office-Format konvertiert, einschließlich derjenigen über 10 MB)  <br/>  Datei- und Ordnerstruktur  <br/>  Berechtigungen für Ordner auf Benutzerebene  <br/>  Berechtigungen für Ordner auf Gruppenebene  <br/>  Dateien unter 15 GB  <br/>  Grundlegende Dokument- und Ordnermetadaten:   <br/>  Erstellungsdatum  <br/>  Änderungsdatum  <br/>  Erstellt von  <br/>  Zuletzt geändert von  <br/> Freigegebene Laufwerke (Ordner und Dateien) <br/> Freigegebene Inhalte im Besitz des Google Drive-Kontos, das migriert wird (wenn explizit für Benutzer oder Gruppen freigegeben)\* <br/> <br/>\**Verwenden Sie Google Drive Admin, um die externen Konten zu identifizieren. Weisen Sie Endbenutzer an, ihre Inhalte nach der Migration erneut freizugeben.* <br/> | Besitzverlauf, frühere Versionen und Kommentare  <br/>  Beschreibungen von Dateien und Ordnern, Ordnerfarben  <br/>   Berechtigungen für Dateien auf Benutzerebene  <br/>  Berechtigungen für Dateien auf Gruppenebene  <br/> Erweiterte Metadaten <br/>  Attribute für Dateisperre <br/> Konvertierung eingebetteter URLs im Inhalt  <br/> Gelöschte Elemente <br/> Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann <br/> Blockierte oder inaktive Benutzer <br/> Google Fotos <br/> Google Formulare, Google Maps und andere verbundene Apps <br/> Google Zeichnungen <br/> Freigegebene Inhalte außerhalb Ihrer Organisation <br/> Inhalte, die nicht im Besitz des Google Drive-Kontos sind, das migriert wird <br/> Berechtigungen und grundlegende Metadaten externer Benutzer<br/> Mitgliedsberechtigungen für freigegebene Laufwerke\*<br/> Dateien oder Ordner, die die aktuellen [Einschränkungen und Begrenzen von SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) überschreiten <br/><br/> \**Verwenden Sie Google Drive Admin, um die Mitgliedschaft für das freigegebene Laufwerk zu identifizieren. Weisen Sie die Endbenutzer an, die Mitgliedschaftseinstellungen vor der Migration auf dem Ziel zu konfigurieren.* <br/> |
|**Box (Starter, Business, Enterprise)**  <br/> |Einzeln oder mehrstufig  <br/> | Dokumente  <br/>  Datei- und Ordnerstruktur  <br/>  Berechtigungen für Ordner auf Benutzerebene  <br/>  Berechtigungen für Ordner auf Gruppenebene  <br/>  Dateien unter 15 GB  <br/>  Grundlegende Dokument- und Ordnermetadaten:   <br/>  Erstellungsdatum  <br/>  Änderungsdatum  <br/>  Erstellt von  <br/>  Zuletzt geändert von  <br/>  Freigegebene Inhalte im Besitz des Box-Kontos, das migriert wird (wenn explizit für Benutzer oder Gruppen freigegeben)\*  <br/><br/> \**Verwenden Sie Box-Berichte, um die externen Konten zu identifizieren. Weisen Sie Endbenutzer an, ihre Inhalte nach der Migration erneut freizugeben.* <br/> | Besitzverlauf, frühere Versionen und Kommentare  <br/>  Beschreibungen von Dateien und Ordnern  <br/>  Berechtigungen für Dateien auf Benutzerebene  <br/>  Berechtigungen für Dateien auf Gruppenebene  <br/>  Box-Tags und erweiterte Metadaten  <br/>  Attribute für Dateisperre  <br/>  Konvertierung eingebetteter URLs im Inhalt  <br/>  Gelöschte Elemente  <br/>  Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann  <br/>  Blockierte oder inaktive Benutzer  <br/>  Box-Hinweise (nicht funktional, da diese ohne Konvertierung migriert werden)  <br/>  Box-Apps, Lesezeichen, Favoriten und Workflows  <br/>  Inhalte, die nicht im Besitz des migrierten Box-Kontos sind (freigegebene Ordner)  <br/>  Berechtigungen und grundlegende Metadaten externer Benutzer\*  <br/>  Dateien oder Ordner, die die aktuellen [Einschränkungen und Begrenzen von SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) überschreiten <br/> |
|**Dropbox für Teams (Standard und Erweitert)**  <br/> |Einzeln oder mehrstufig  <br/> | Dokumente  <br/>  Datei- und Ordnerstruktur  <br/>  Berechtigungen für Ordner auf Benutzerebene  <br/>  Berechtigungen für Ordner auf Gruppenebene  <br/>  Dateien unter 15 GB  <br/>  Grundlegende Dokument- und Ordnermetadaten:   <br/>  Erstellungsdatum  <br/>  Änderungsdatum  <br/>  Erstellt von  <br/>  Zuletzt geändert von  <br/> Freigegebene Teamordner und -inhalte <br/> Freigegebene Inhalte im Besitz des Dropbox-Kontos, das migriert wird (wenn explizit für Benutzer oder Gruppen freigegeben)\*  <br/> <br/> \**Verwenden Sie Dropbox-Berichte, um die externen Konten zu identifizieren. Weisen Sie Endbenutzer an, ihre Inhalte nach der Migration erneut freizugeben.* <br/> | Besitzverlauf, frühere Versionen und Kommentare <br/>  Beschreibungen von Dateien und Ordnern <br/>  Berechtigungen für Dateien auf Benutzerebene  <br/>  Berechtigungen für Dateien auf Gruppenebene    <br/> Erweiterte Metadaten  <br/>  Attribute für Dateisperre  <br/>  Konvertierung eingebetteter URLs im Inhalt  <br/>  Gelöschte Elemente  <br/>  Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann  <br/>  Nicht gemountete Dropbox-Ordner <br/>  Gelöschte oder getrennte Benutzer <br/>  Dropbox Paper, Showcases und Spaces  <br/> Dropbox-Apps und Favoriten (Pins/Sterne) <br/> Inhalte, die nicht im Besitz des migrierten Dropbox-Kontos sind  <br/>  Berechtigungen und grundlegende Metadaten externer Benutzer\*  <br/>  Dateien oder Ordner, die die aktuellen [Einschränkungen und Begrenzen von SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) überschreiten <br/> <br/> \**Verwenden Sie Dropbox-Berichte, um die externen Konten zu identifizieren. Weisen Sie Endbenutzer an, ihre Inhalte nach der Migration erneut freizugeben.* <br/> |
   
FastTrack-Spezialisten führen die folgenden erforderlichen Aufgaben für Migrationen aus:  
- Durchführen eines Workshops zur exemplarischen Vorgehensweise bei der Migration, bei dem der Migrationsprozess und der Ansatz für das ausgewählte Migrationsszenario erläutert werden.   
- Bereitstellen der erforderlichen Komponenten für Analyse- und Migrationstools, sofern für das Szenario zutreffend.  
- Bereitstellen der erforderlichen Komponenten für den Zugriff auf die Quell- und Zielumgebung für das Durchführen der Analyse und der Migration für das Migrationsteam   
- Bereitstellen von Analysetools zum Durchführen der Analyse der Quell- und Zielumgebung oder Bereitstellen von Anleitungen zur Verwendung systemeigener Quellplattformfunktionen zum Erstellen von Analyseberichten    
- Unterstützung beim Bereitstellen und Ausführen von Analyse- und Migrationstools (sofern zutreffend)   
- Konfigurieren der Migrationsinfrastruktur als Vorbereitung auf die Inhaltsmigration (sofern zutreffend)    
- Durchführen einer Testmigration zur Überprüfung der Migrationsinfrastruktur und der erforderlichen Komponenten    
- Bereitstellen vordefinierter OneDrive for Business-Zielwebsites im Rahmen der Migration    
- Durchführen einer Pilotmigration vor Beginn der Migration
- Bereitstellen einer Anleitung für die Migrationsplanung für das ausgewählte Szenario   
- Durchführen der einzelnen Inhaltsmigrationsstufen gemäß dem Migrationszeitplan, der vom Kunden bereitgestellt und von FastTrack-Ressourcen überprüft wurde   
- Bereitstellen der Migrationsergebnisse nach jedem Migrationsfenster   
- Unterstützung bei Selektierung von Migrationsfehlern und möglichen Lösungen 
- Bereitstellen eines endgültigen Migrationsberichts für jedes Migrationsfenster   
- Unterstützung nach der Migration während Benutzerakzeptanztests bis zu fünf Tage nach Abschluss der Migration
   
Sie führen die folgenden erforderlichen Aufgaben für Migrationen aus:
- Bereitstellen der für die Analyse- und Migrationsaktivitäten empfohlenen Projektressourcen Zu diesen zählen:
  - Projektmanagement
  - Benutzerakzeptanztests
  - Für die Quell- und Zielinhaltsplattformen verantwortlichen Administratoren.
- Bereitstellen der Infrastrukturvoraussetzungen für die Analyse- und Migrationsaktivitäten (falls erforderlich)   
- Bereitstellen von Zugriff und Berechtigungen für die Quell- und Zielumgebungen für FastTrack-Experten, sodass Migrationsaktivitäten durchgeführt werden können (falls erforderlich)  
    > [!NOTE]
    > Migrationen verwenden nur Konten, die den beim Onboarding definierten Sicherheitsanforderungen entsprechen. Wenn Sie nicht solche Konten verwenden, können möglicherweise Verzögerungen bei der Migration auftreten. 
- Installieren der FastTrack-Analysetools und Ausführen der Analysedatensammlungs-Aktivitäten (sofern zutreffend)
- Lokale Installation der bereitgestellten FastTrack-Migrationssoftware (sofern zutreffend)  
- Ausführen von Korrekturaktivitäten, die im von FastTrack bereitgestellten Wartungsbericht beschrieben sind (sofern zutreffend).   
- Bereitstellen eines Migrationszeitplans mithilfe von FastTrack-Vorlagen und -Anleitungen 
- Bereitstellen eines Plans in einer definierten Methode und Auflisten der zu migrierenden speziellen Benutzerdaten bei jedem Migrationsereignis.
- Löschen von Benutzerdaten aus dem Plan bis zu 24 Stunden vor dem Migrationsbatch. Zu diesem Zeitpunkt ist dies der Plan für den letzten Migrationsbatch.
- Durchführen der Qualitätssicherung für die Migration und der Benutzerakzeptanztests   
- Durchführen von Korrekturen nach der Migration (sofern zutreffend)  
- Planen und Implementieren der Änderungsverwaltung und Endbenutzerkommunikation (sofern zutreffend)  
- Verwalten und Konfigurieren aller für eine erfolgreiche Durchführung der Analyse- und Migrationsaktivitäten erforderlichen Änderungen am Quellsystem bzw. an den Quellgeräten
    
> [!NOTE]
> Microsoft übernimmt keine Garantie für die Geschwindigkeit der Dateimigration. 


