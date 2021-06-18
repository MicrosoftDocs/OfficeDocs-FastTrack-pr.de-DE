---
title: Datenmigration
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 6/16/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Sie können die Migration von E-Mail- und Dateidaten in ihrer Quellumgebung auf Office 365 (Exchange Online, SharePoint Online und OneDrive for Business) mithilfe von FastTrack migrieren. Die Art der von uns bereitgestellten Unterstützung hängt von der Anzahl der Office 365-Lizenzen ab.
ms.openlocfilehash: 7b9e48d802e0c33f72165f77b23680915c9c61eb
ms.sourcegitcommit: cff44abb4212a768ccdcfd00226793d4dc3b02d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/17/2021
ms.locfileid: "52994936"
---
# <a name="data-migration"></a>Datenmigration

Sie können die Migration von E-Mail- und Dateidaten in ihrer Quellumgebung auf Office 365 (Exchange Online, SharePoint Online und OneDrive for Business) mithilfe von FastTrack migrieren.

Die Art der von uns bereitgestellten Unterstützung hängt von der Anzahl der Office 365-Lizenzen ab:

  - **Für Office 365-Mandanten mit 150 bis 499-Lizenzen**: FastTrack bietet nur Migrationsanleitungen. Sie sind für die Durchführung der Datenmigration verantwortlich. Wir führen Sie durch die Dokumentation, die Ihnen hilft, ﻿kostenlose Tools für die Durchführung einer Self-Service-Migration zu planen und zu verwenden.
  - **Für Office 365-Mandanten mit 500 oder mehr Lizenzen**: FastTrack bietet Migrationsanleitungen und Datenmigrationsdienste. Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des Office 365-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Daten. Sie erstellen und planen Ihre Migrationsereignisse. Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit.

> [!NOTE]
> Wenn Sie einen kommerziellen Plan vor dem 1.9.2017 erworben oder verlängert haben, benötigen Sie nur 150 Lizenzen, um für Datenmigrationsdienste qualifiziert zu sein. Bei Plänen für Bildungseinrichtungen sind nur Lehrpersonal und Mitarbeiter für Migrationsdienste berechtigt.

### <a name="considerations"></a>Überlegungen

  - Ihre Quellumgebungen müssen bestimmte Erwartungen erfüllen, um Daten zu Office 365 zu migrieren. Weitere Informationen zu den Erwartungen bezüglich der Quellumgebung für Exchange, SharePoint und OneDrive for Business finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).
  - Für die Bereitstellung von Datenmigrationsdiensten benötigen wir einen geeigneten Zugriff auf Ihre Quellumgebungen und den Office 365-Mandanten.
  - Unsere Datenmigrationsdienste sind nicht für Daten vorgesehen, die besonderen rechtlichen oder behördlichen Vorschriften unterliegen. Wenn wir Ihre Daten migrieren, können sie an einen beliebigen Ort, an dem wir über Einrichtungen verfügen, übertragen, dort gespeichert und verarbeitet werden (sofern nicht anderweitig für Ihr FastTrack-Migrationsprojekt angegeben).
  - Wir übernehmen keine Garantie für die Geschwindigkeit der E-Mail- oder Dateimigration.
  - Unvorhergesehene Probleme (wie unlesbare oder fehlerhafte Elemente in der Quellumgebung) verhindern möglicherweise, dass einige ihrer Datenelemente migriert werden können.
  - Externe Faktoren, die außerhalb unserer Kontrolle stehen (z. B. Änderungen an den Programmierschnittstellen von Drittanbietern) können zu Änderungen, Verzögerungen oder der Sperrung unserer Datenmigrationsdienste führen.

### <a name="migration-service-availability"></a>Verfügbarkeit des Migrationsdiensts

  - **Für kommerzielle Kunden und britische Behörden:** Wir stellen Datenmigrationsdienste rund um die Uhr an sieben (7) Tagen pro Woche bereit.
  - **Für Kunden von US-amerikanischen Behörden/Verteidigungsministerium:** Wir stellen Datenmigrationsdienste rund um die Uhr an fünf (5) Werktagen pro Woche bereit.

## <a name="migration-to-exchange-online"></a>Migration zu Exchange Online

Wenn Sie sich für die Migration Ihrer E-Mails zu Exchange Online mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit. Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des Exchange Online-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Postfächer. Sie erstellen und planen Ihre Migrationsereignisse. Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit. Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass E-Mail-Nachrichten von entsprechend geplanten und berechtigten Quellpostfächern ihrer Quellumgebungen zu Exchange Online migriert wurden.

### <a name="considerations"></a>Überlegungen

  - Bevor Sie die Migration durchführen können, müssen Sie den FastTrack-Onboarding-Vorgang für Exchange Online durchführen.
      - Wenn Sie das Onboarding selbst durchgeführt haben, müssen Sie die erforderlichen Überprüfungen und Voraussetzungen erfüllen. Ausführliche Informationen finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).
  - FastTrack migriert nur zu aktiven Office 365-Postfächern.
  - Sie müssen bestimmte Anforderungen erfüllen, wenn Sie von einer lokalen Exchange-Umgebung migrieren möchten. Weitere Informationen finden Sie unter [Voraussetzungen für die Hybridbereitstellung](https://go.microsoft.com/fwlink/?LinkId=787528).
  - Sämtliche Quellumgebungen müssen über die neuesten Service Packs (SP) verfügen und auf der Rollup (RU)-/Kumulativen Update (KU)-Ebene für das entsprechende Produkt in der Quellumgebung vorhanden sein.
  - Verteilerlisten (*MailEnabledGroup*-Objekte) und externe Kontakte (*MailEnabledContact*-Objekte) im lokalen Active Directory befinden, sind nicht Bestandteil einer Postfachdatenmigration. Sie können Sie jedoch mithilfe von Azure Active Directory (Azure AD) Connect synchronisieren. 

## <a name="source-environments"></a>Quellumgebungen

Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:

  - aus einer einzelnen oder aus mehreren Active Directory-Gesamtstrukturen mit einer oder mehreren Exchange-Organisationen (jedes Exchange-E-Mail-System muss Exchange 2010 oder höher sein).
  - aus einer einzelnen IMAP-fähigen E-Mail-Umgebung.
  - aus einer G Suite-Umgebung (nur Gmail, Kontakte und Kalender).

Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:

<table>
<thead>
<tr class="header">
<th><strong>Quellumgebung</strong></th>
<th><strong>Migrationstyp</strong></th>
<th><strong>Was wird migriert?</strong></th>
<th><strong>Was wird nicht migriert?</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong><br />
<br />
<strong>Hinweis:</strong> Informationen zu lokalen Exchange Abhängigkeiten finden Sie unter "Voraussetzungen für die <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybridbereitstellung".</span></a></td>
<td>Migration mit Hybridbereitstellung</td>
<td><ul>
<li>E-Mails</li>
<li>Serverseitige Postfachregeln</li>
<li>Stellvertretungen</li>
<li>Postfachkontakte </li>
<li> Kalender </li>
<li> Aufgaben </li>
<li> E-Mails mit Rechteverwaltung </li>
<li> Verschlüsselte E-Mails </li>
<li> Signaturen </li>
<li> Persönliches Archiv, das mit dem Benutzerpostfach migriert wird </li>
<li> Wiederherstellbare Elemente </li>
</ul></td>
<td><ul>
<li> Öffentliche Ordner </li>
<li> E-Mail, die die zulässige Nachrichtengröße überschreitet. </li>
<li> Journalarchiv oder eine beliebige Archivlösung von Drittanbietern </li>
<li> Blockierte oder inaktive Benutzer </li>
<li> Archivdaten aus PST-Dateien </li>
<li> Beschädigte Elemente </li>
<li> Inaktive Postfächer </li>
<li> Clientseitige Postfachregeln</li>
</ul></td>
</tr>
<tr class="even">
<td><strong>G Suite-Umgebung (nur Gmail, Kontakte und Kalender)</strong><br />
<br />
<strong>Hinweis:</strong> Ihre G Suite-Umgebung muss die unter <a href="/exchange/mailbox-migration/perform-g-suite-migration">Ausführen einer G Suite-Migration</a>beschriebenen Voraussetzungen erfüllen.</td>
<td>Übernahmemigration oder mehrstufige Migration</td>
<td><ul>
<li> E-Mails </li>
<li> Postfachkontakte (es werden maximal drei E-Mail-Adressen pro Kontakt migriert) </li>
<li> Kalender </li>
<li> Bezeichnungen </li>
</ul></td>
<td><ul>
<li> Regeln </li>
<li> Stellvertretungen </li>
<li> Signaturen </li>
<li> Aufgaben </li>
<li> E-Mails oder Anhänge, die die zulässige Nachrichtengröße überschreiten </li>
<li> Blockierte oder inaktive Benutzer </li>
<li> Archivdaten aus PST-Dateien oder einer Drittanbieter-Archivlösung (z. B. Google Vault) </li>
<li> E-Mails mit Rechteverwaltung oder Verschlüsselung </li>
<li> Beschädigte Elemente </li>
<li> Google Hangouts** </li>
<li> Google-Gruppen </li>
<li> Ressourcenpostfächer </li>
<li> Inaktive Postfächer </li>
<li> Urlaubseinstellungen und Einstellungen für automatische Antworten </li>
<li> Freigegebene Kalender, Cloudanlagen, Google Hangout-Links und Ereignisfarben </li>
</ul>
**Hangout-Unterhaltungen, die als Beschriftungen gespeichert wurden, werden migriert. </td>
</tr>
<tr class="odd">
<td><strong>IMAP4-Quelle (wie Domino, GroupWise oder Zimbra)</strong></td>
<td>Migration mit systemeigenen IMAP4-Tools</td>
<td><li>E-Mails </li></td>
<td><ul>
<li> Regeln </li>
<li> Stellvertretungen </li>
<li> Verteilerlisten </li>
<li> Externe Kontakte </li>
<li> E-Mail-aktivierte Benutzer </li>
<li> Blockierte oder inaktive Benutzer </li>
<li> Postfachkontakte </li>
<li> Kalender </li>
<li> Signaturen </li>
<li> Aufgaben </li>
<li> E-Mails, die die zulässige Nachrichtengröße überschreiten </li>
<li> Archivdaten </li>
<li> Verschlüsselte E-Mail-Nachrichten </li>
<li> Beschädigte Elemente </li>
<li> Inaktive Postfächer </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-exchange-online-migrations"></a>FastTrack Zuständigkeiten für Exchange Online Migrationen

Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus. Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).

Unsere FastTrack-Spezialisten führen außerdem die folgenden Aktivitäten speziell für Exchange-Migrationen durch:

  -  Bereitstellen von Anleitungen, die Ihnen dabei helfen, die Koexistenz von SMTP-E-Mail-Routing zwischen Ihrer Quellumgebung und Exchange Online zu ermöglichen.

### <a name="your-responsibilities"></a>Ihre Zuständigkeiten

Während des Migrationsprojekts führen Sie Standardaktivitäten aus. Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).

Sie führen außerdem die folgenden Aktivitäten speziell für Exchange-Migrationen aus:

  - Durchführen des FastTrack-Onboarding-Vorgangs für Exchange Online. Wenn Sie das Onboarding selbst durchgeführt haben, müssen Sie die erforderlichen Überprüfungen und Voraussetzungen erfüllen. Ausführliche Informationen finden Sie unter [Produkte und Funktionen](products-and-capabilities.md).
  -  Installieren der entsprechenden Clientsoftwareebene gemäß den Office 365-Richtlinien. Details finden Sie unter [Der moderne Arbeitsplatz](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).
  -  Erfüllen bestimmter Anforderungen, wenn Sie von einer lokalen Exchange-Umgebung migrieren möchten. Weitere Informationen finden Sie unter [Voraussetzungen für die Hybridbereitstellung](https://go.microsoft.com/fwlink/?LinkId=787528).
  -  Sicherstellen, dass jede Quellumgebung über das neueste Service Pack (SP) und Rollup (RU)/Cumulative Update (CU) verfügt, sofern zutreffend.
  -  Konfigurieren und Validieren der Koexistenz von SMTP-E-Mail-Routing zwischen Ihrer Quellumgebung und Exchange Online, sofern zutreffend.
  -  Sicherstellen, dass die Größe des Quellpostfachs das Zielpostfachkontingent nicht überschreitet. Abhängig von der Quellplattform müssen Sie möglicherweise Ihre Quelldaten auf 85 % des Zielpostfachkontingents beschränken.
  -  Ggf. Migrieren clientseitiger Daten. Dies umfasst unter anderem lokale Adressbücher, Daten in lokalen PST-Dateien, Outlook-Regeln und lokale Outlook-Einstellungen.
  -  Unterstützen Ihrer Endbenutzer bei der Behebung von Problemen bei der clientbasierten Migration.

## <a name="migration-to-sharepoint-online"></a>Migration zu SharePoint Online

Wenn Sie sich für die Migration Ihrer Dateien zu SharePoint Online mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit. Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des SharePoint Online-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Dateien. Sie erstellen und planen Ihre Migrationsereignisse. Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit. Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass Dateien von entsprechend geplanten und berechtigten Quellen ihrer Quellumgebungen zu SharePoint Online migriert wurden.

### <a name="considerations"></a>Überlegungen

 - Alle Migrationen unterliegen SharePoint Online-Kontingenten. Einzelheiten finden Sie unter <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint Grenzwerten.</a> 
  - Der Gesamtbetrag sollte auf 75 Prozent des SharePoint Online-Gesamtspeicherkontingents, für das Sie berechtigt sind, beschränkt werden (einschließlich den zusätzlichen Speicher, den Sie möglicherweise separat gekauft haben).

### <a name="source-environment-details"></a>Detail der Quellumgebung

Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:

  - Dateifreigaben (SMB [Server Message Block]-Dateifreigaben auf Geräten mit Unterstützung für SMB 2.0 und höher)
  - Eine einzelne G Suite-Umgebung (nur Google Drive).
  - Box (Starter, Business, Enterprise).
  - Dropbox für Teams (Standard und Erweitert).

Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:

<table>
<thead>
<tr class="header">
<th><strong>Quellumgebung</strong></th>
<th><strong>Migrationstyp</strong></th>
<th><strong>Was wird migriert?</strong></th>
 <th><strong>Was wird nicht migriert?</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Alle Dateifreigabegeräte mit Unterstützung für SMB 2.0 und höher</strong></td>
<td>Einzeln oder mehrstufig</td>
<td><ul>
<li> Dokumente </li>
<li> Datei- und Ordnerstruktur </li>
<li> Datei- und Ordnerberechtigungen auf Benutzerebene* </li>
<li> Datei- und Ordnerberechtigungen auf Gruppenebene* </li>
<li> Dateien unter 15 GB </li>
<li> Grundlegende Dokument- und Ordnermetadaten: 
<ul>
<li> Erstellungsdatum </li>
<li> Änderungsdatum </li>
<li> Erstellt von </li>
<li> Zuletzt geändert von </li>
</ul></li>
</ul>
* Setzt die Konfiguration der Verzeichnissynchronisierung voraus. Es werden nur NTFS-Berechtigungen migriert, die für den Windows-Datei-Explorer verfügbar sind. Berechtigungen, die direkt auf Dateifreigabegeräten verwaltet werden, werden nicht migriert. Wenn Daten auf einem SMB 2.0-Gerät gespeichert werden, werden die NTFS-äquivalenten Berechtigungen, die vom SMB-Protokoll verfügbar gemacht werden, migriert.</td>
<td><ul>
<li> Aufgezeichnete Eigentümerschaft und frühere Versionen </li>
<li> Konvertierung eingebetteter URLs im Inhalt </li>
<li> Frühere Versionen </li>
<li> Windows-Datei-/-Ordnerattribute (z. B. „Schreibgeschützt“ und „Ausgeblendet“)  </li>
<li> Nicht-Windows-NTFS-Dateisystem (New Technology File System) und erweiterte NTFS-Berechtigungen sowie besondere Einstellungen: </li>
<li> Explizite Verweigerungsberechtigungen (werden nach der Migration entfernt, Inhalte unterliegen parallelen Berechtigungen oder Berechtigungen im übergeordneten Ordner). </li>
<li> Konfiguration der NTFS-Überwachung </li>
<li> Zusätzliche Dateimetadaten von der Dateiklassifizierungsinfrastruktur (File Classification Infrastructure, FCI) </li>
<li> Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann </li>
<li> Ausgeblendete Freigaben </li>
<li> Freigabe (z. B. gewährte Berechtigungen auf Freigabeebene) </li>
<li> Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Onlineeinschränkungen und -einschränkungen</span> überschreiten</a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Einzelne G Suite-Umgebung (nur Google Drive)</strong></td>
<td>Einzeln oder mehrstufig</td>
<td><ul>
<li> Google Docs, Google Tabellen und Google Präsentationen (Dateien werden in das entsprechende Office-Format konvertiert), einschließlich derjenigen über 10 MB </li>
<li> Datei- und Ordnerstruktur </li>
<li> Berechtigungen für Ordner auf Benutzerebene </li>
<li> Berechtigungen für Ordner auf Gruppenebene </li>
<li> Dateien unter 15 GB </li>
<li> Grundlegende Dokument- und Ordnermetadaten: 
<ul>
<li> Erstellungsdatum </li>
<li> Änderungsdatum </li>
<li> Erstellt von </li>
<li> Zuletzt geändert von </li>
</ul></li>
<li> Freigegebene Laufwerke (Ordner und Dateien) </li>
<li> Geteilte Inhalte, die im Besitz des Google Drive-Kontos sind, das migriert wird </li>
</ul></td>
<td><ul>
<li> Besitzverlauf, frühere Versionen und Kommentare </li>
<li> Beschreibungen von Dateien und Ordnern, Ordnerfarben </li>
<li> Berechtigungen für Dateien auf Benutzerebene </li>
<li> Berechtigungen für Dateien auf Gruppenebene </li>
<li> Erweiterte Metadaten </li>
<li> Attribute für Dateisperre </li>
<li> Konvertierung eingebetteter URLs im Inhalt </li>
<li> Gelöschte Elemente </li>
<li> Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann </li>
<li> Blockierte oder inaktive Benutzer </li>
<li> Google Fotos, Google Formulare, Google Maps und andere verbundene Apps </li>
<li> Google Zeichnungen </li>
<li> Freigegebene Inhalte außerhalb Ihrer Organisation </li>
<li> Inhalte, die nicht im Besitz des Google Drive-Kontos sind, das migriert wird </li>
<li> Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Google Drive-Administratorberichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden. Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.) </li>
<li> Mitgliedschaftsberechtigungen für freigegebene Laufwerke (<strong>Hinweis</strong>: Verwenden Sie die Google Drive-Administratorberichte, um die Mitgliedschaften für freigegebene Laufwerke zu identifizieren. Weisen Sie die Endbenutzer an, diese Mitgliedschaftseinstellungen auf dem Ziel vor der Migration zu konfigurieren.) </li>
<li> Dateien, die als eingeschränkt oder nicht kopierbar gekennzeichnet sind </li>
<li> Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Onlineeinschränkungen und -einschränkungen</span> überschreiten</a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter, Business, Enterprise)</strong></td>
<td>Einzeln oder mehrstufig</td>
<td><ul>
<li> Dokumente </li>
<li> Datei- und Ordnerstruktur </li>
<li> Berechtigungen für Ordner auf Benutzerebene </li>
<li> Berechtigungen für Ordner auf Gruppenebene </li>
<li> Dateien unter 15 GB </li>
<li> Grundlegende Dokument- und Ordnermetadaten: 
<ul>
<li> Erstellungsdatum </li>
<li> Änderungsdatum </li>
<li> Erstellt von </li>
<li> Zuletzt geändert von </li>
</ul></li>
<li> Geteilte Inhalte, die im Besitz des Box-Kontos sind, das migriert wird </li>
<li> Feldnotizen (in Word-Dokumentformat konvertiert) </li>
</ul></td>
<td><ul>
<li> Besitzverlauf, frühere Versionen und Kommentare </li>
<li> Beschreibungen von Dateien und Ordnern </li>
<li> Berechtigungen für Dateien auf Benutzerebene </li>
<li> Berechtigungen für Dateien auf Gruppenebene </li>
<li> Box-Tags und erweiterte Metadaten </li>
<li> Attribute für Dateisperre </li>
<li> Konvertierung eingebetteter URLs im Inhalt </li>
<li> Gelöschte Elemente </li>
<li> Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann </li>
<li> Blockierte oder inaktive Benutzer </li>
<li> Box-Apps, Lesezeichen, Favoriten und Workflows </li>
<li> Inhalte, die nicht im Besitz des migrierten Box-Kontos sind </li>
<li> Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Box-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden. Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.) </li>
<li> Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Onlineeinschränkungen und -einschränkungen</span> überschreiten</a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Dropbox für Teams (Standard und Erweitert)</strong></td>
<td>Einzeln oder mehrstufig</td>
<td><ul>
<li> Dokumente </li>
<li> Datei- und Ordnerstruktur </li>
<li> Berechtigungen für Ordner auf Benutzerebene </li>
<li> Berechtigungen für Ordner auf Gruppenebene </li>
<li> Dateien unter 15 GB </li>
<li> Grundlegende Dokument- und Ordnermetadaten: 
<ul>
<li> Erstellungsdatum </li>
<li> Änderungsdatum </li>
<li> Erstellt von </li>
<li> Zuletzt geändert von </li>
</ul></li>
<li> Freigegebene Teamordner und -inhalte </li>
<li> Geteilte Inhalte, die im Besitz des Dropbox-Kontos sind, das migriert wird </li>
</ul></td>
<td><ul>
<li> Besitzverlauf, frühere Versionen und Kommentare </li>
<li> Beschreibungen von Dateien und Ordnern </li>
<li> Berechtigungen für Dateien auf Benutzerebene </li>
<li> Berechtigungen für Dateien auf Gruppenebene </li>
<li> Erweiterte Metadaten </li>
<li> Attribute für Dateisperre </li>
<li> Konvertierung eingebetteter URLs im Inhalt </li>
<li> Gelöschte Elemente </li>
<li> Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann </li>
<li> Nicht gemountete Dropbox-Ordner </li>
<li> Gelöschte oder getrennte Benutzer </li>
<li> Dropbox Paper, Showcases und Spaces </li>
<li> Dropbox-Apps und Favoriten (Pins/Sterne) </li>
<li> Inhalte, die nicht im Besitz des migrierten Dropbox-Kontos sind </li>
<li> Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Dropbox-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden. Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.) </li>
<li> Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Onlineeinschränkungen und -einschränkungen</span> überschreiten</a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-sharepoint-online-migrations"></a>FastTrack Zuständigkeiten für SharePoint Onlinemigrationen

Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus. Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).

### <a name="your-responsibilities"></a>Ihre Zuständigkeiten

Während des Migrationsprojekts führen Sie Standardaktivitäten aus. Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).

Sie führen außerdem die folgenden Aktivitäten speziell für SharePoint Online-Migrationen aus:

  - Bereitstellen aller SharePoint-Teamwebsites, die für Ihre Migrationsereignisse vorgesehen sind.

## <a name="migration-to-onedrive-for-business"></a>Migration zu OneDrive for Business

Wenn Sie sich für die Migration Ihrer Dateien zu OneDrive for Business mithilfe von FastTrack entscheiden, stellen wir Migrationsanleitungen und Datenmigrationsdienste bereit. Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren ihrer Quellumgebungen und des OneDrive for Business-Mandanten und beim Nutzen unsere Datenmigrationsdienste zum Migrieren Ihrer Dateien. Sie erstellen und planen Ihre Migrationsereignisse. Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit. Wenn Ihre Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass Dateien von entsprechend geplanten und berechtigten Quellen ihrer Quellumgebungen zu OneDrive for Business migriert wurden.

### <a name="considerations"></a>Überlegungen

  - Alle Migrationen unterliegen SharePoint Online-Kontingenten. Weitere Informationen finden Sie unter <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint Grenzwerten.</a> 
  - Der Gesamtbetrag sollte auf 75 Prozent der Daten des SharePoint Online-Gesamtspeicherkontingents, für das Sie berechtigt sind, beschränkt werden (einschließlich den zusätzlichen Speicher, den Sie möglicherweise separat gekauft haben).
  - FastTrack migriert nur zu aktiven OneDrive for Business-Laufwerken.

### <a name="source-environment-details"></a>Detail der Quellumgebung

Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen:

  - Dateifreigaben (SMB-Dateifreigaben auf Geräten mit Unterstützung für SMB 2.0 und höher)
  - Einzelne G Suite-Umgebung (nur Google Drive).
  - Box (Starter, Business, Enterprise).
  - Dropbox für Teams (Standard und Erweitert).

Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:

<table>
<thead>
<tr class="header">
 <th><strong>Quellumgebung</strong></th>
 <th><strong>Migrationstyp</strong></th>
 <th><strong>Was wird migriert?</strong></th>
 <th><strong>Was wird nicht migriert?</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Alle Dateifreigabegeräte mit Unterstützung für SMB 2.0 und höher</strong></td>
<td>Einzeln oder mehrstufig</td>
<td><ul>
<li> Dokumente </li>
<li> Datei- und Ordnerstruktur </li>
<li> Datei- und Ordnerberechtigungen auf Benutzerebene* </li>
<li> Datei- und Ordnerberechtigungen auf Gruppenebene* </li>
<li> Dateien unter 15 GB </li>
<li> Grundlegende Dokument- und Ordnermetadaten: 
<ul>
<li> Erstellungsdatum </li>
<li> Änderungsdatum </li>
<li> Erstellt von </li>
<li> Zuletzt geändert von </li>
</ul></li>
</ul>
<br>
* Setzt die Konfiguration der Verzeichnissynchronisierung voraus. Es werden nur NTFS-Berechtigungen migriert, die für den Windows-Datei-Explorer verfügbar sind. Berechtigungen, die direkt auf Dateifreigabegeräten verwaltet werden, werden nicht migriert. Wenn Daten auf einem SMB 2.0-Gerät gespeichert werden, werden die NTFS-äquivalenten Berechtigungen, die vom SMB-Protokoll verfügbar gemacht werden, migriert. </td>
<td><ul>
<li> Aufgezeichnete Eigentümerschaft und frühere Versionen </li>
<li> Konvertierung eingebetteter URLs im Inhalt </li>
<li> Frühere Versionen </li>
<li> Windows-Datei-/-Ordnerattribute (z. B. „Schreibgeschützt“ und „Ausgeblendet“)  </li>
<li> Nicht-Windows-NTFS-Dateisystem (New Technology File System) und erweiterte NTFS-Berechtigungen sowie besondere Einstellungen: </li>
<li> Explizite Verweigerungsberechtigungen (werden nach der Migration entfernt, Inhalte unterliegen parallelen Berechtigungen oder Berechtigungen im übergeordneten Ordner). </li>
<li> Konfiguration der NTFS-Überwachung </li>
<li> Zusätzliche Dateimetadaten von der Dateiklassifizierungsinfrastruktur (File Classification Infrastructure, FCI) </li>
<li> Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann </li>
<li> Ausgeblendete Freigaben </li>
<li> Freigabe (z. B. gewährte Berechtigungen auf Freigabeebene) </li>
<li> Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Onlineeinschränkungen und -einschränkungen</span> überschreiten</a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Einzelne G Suite-Umgebung (nur Google Drive)</strong></td>
<td>Einzeln oder mehrstufig</td>
<td><ul>
<li> Google Docs, Google Tabellen und Google Präsentationen (Dateien werden in das entsprechende Office-Format konvertiert, einschließlich derjenigen über 10 MB) </li>
<li> Datei- und Ordnerstruktur </li>
<li> Berechtigungen für Ordner auf Benutzerebene </li>
<li> Berechtigungen für Ordner auf Gruppenebene </li>
<li> Dateien unter 15 GB </li>
<li> Grundlegende Dokument- und Ordnermetadaten: 
<ul>
<li> Erstellungsdatum </li>
<li> Änderungsdatum </li>
<li> Erstellt von </li>
<li> Zuletzt geändert von </li>
</ul></li>
<li> Freigegebene Laufwerke (Ordner und Dateien) </li>
<li> Geteilte Inhalte, die im Besitz des Google Drive-Kontos sind, das migriert wird </li>
</ul></td>
<td><ul>
<li> Besitzverlauf, frühere Versionen und Kommentare </li>
<li> Beschreibungen von Dateien und Ordnern, Ordnerfarben </li>
<li> Berechtigungen für Dateien auf Benutzerebene </li>
<li> Berechtigungen für Dateien auf Gruppenebene </li>
<li> Erweiterte Metadaten </li>
<li> Attribute für Dateisperre </li>
<li> Konvertierung eingebetteter URLs im Inhalt </li>
<li> Gelöschte Elemente </li>
<li> Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann </li>
<li> Blockierte oder inaktive Benutzer </li>
<li> Google Fotos, Google Formulare, Google Maps und andere verbundene Apps </li>
<li> Google Zeichnungen </li>
<li> Freigegebene Inhalte außerhalb Ihrer Organisation </li>
<li> Inhalte, die nicht im Besitz des Google Drive-Kontos sind, das migriert wird </li>
<li> Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Google Drive-Administratorberichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden. Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.) </li>
<li> Mitgliedschaftsberechtigungen für freigegebene Laufwerke (<strong>Hinweis</strong>: Verwenden Sie die Google Drive-Administratorberichte, um die Mitgliedschaften für freigegebene Laufwerke zu identifizieren. Weisen Sie die Endbenutzer an, diese Mitgliedschaftseinstellungen auf dem Ziel vor der Migration zu konfigurieren.) </li>
<li> Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Onlineeinschränkungen und -einschränkungen</span> überschreiten</a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter, Business, Enterprise)</strong></td>
<td>Einzeln oder mehrstufig</td>
<td><ul>
<li> Dokumente </li>
<li> Datei- und Ordnerstruktur </li>
<li> Berechtigungen für Ordner auf Benutzerebene </li>
<li> Berechtigungen für Ordner auf Gruppenebene </li>
<li> Dateien unter 15 GB </li>
<li> Grundlegende Dokument- und Ordnermetadaten: 
<ul>
<li> Erstellungsdatum </li>
<li> Änderungsdatum </li>
<li> Erstellt von </li>
<li> Zuletzt geändert von </li>
</ul></li>
<li> Geteilte Inhalte, die im Besitz des Box-Kontos sind, das migriert wird </li>
</ul></td>
<td><ul>
<li> Besitzverlauf, frühere Versionen und Kommentare </li>
<li> Beschreibungen von Dateien und Ordnern </li>
<li> Berechtigungen für Dateien auf Benutzerebene </li>
<li> Berechtigungen für Dateien auf Gruppenebene </li>
<li> Box-Tags und erweiterte Metadaten </li>
<li> Attribute für Dateisperre </li>
<li> Konvertierung eingebetteter URLs im Inhalt </li>
<li> Gelöschte Elemente </li>
<li> Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann </li>
<li> Blockierte oder inaktive Benutzer </li>
<li> Box-Apps, Lesezeichen, Favoriten und Workflows </li>
<li> Inhalte, die nicht im Besitz des migrierten Box-Kontos sind </li>
<li> Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Box-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden. Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.) </li>
<li> Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Onlineeinschränkungen und -einschränkungen</span> überschreiten</a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Dropbox für Teams (Standard und Erweitert)</strong></td>
<td>Einzeln oder mehrstufig</td>
<td><ul>
<li> Dokumente </li>
<li> Datei- und Ordnerstruktur </li>
<li> Berechtigungen für Ordner auf Benutzerebene </li>
<li> Berechtigungen für Ordner auf Gruppenebene </li>
<li> Dateien unter 15 GB </li>
<li> Grundlegende Dokument- und Ordnermetadaten: 
<ul>
<li> Erstellungsdatum </li>
<li> Änderungsdatum </li>
<li> Erstellt von </li>
<li> Zuletzt geändert von </li>
</ul></li>
<li> Freigegebene Teamordner und -inhalte </li>
<li> Geteilte Inhalte, die im Besitz des Dropbox-Kontos sind, das migriert wird </li>
</ul></td>
<td><ul>
<li> Besitzverlauf, frühere Versionen und Kommentare </li>
<li> Beschreibungen von Dateien und Ordnern </li>
<li> Berechtigungen für Dateien auf Benutzerebene </li>
<li> Berechtigungen für Dateien auf Gruppenebene </li>
<li> Erweiterte Metadaten </li>
<li> Attribute für Dateisperre </li>
<li> Konvertierung eingebetteter URLs im Inhalt </li>
<li> Gelöschte Elemente </li>
<li> Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann </li>
<li> Nicht gemountete Dropbox-Ordner </li>
<li> Gelöschte oder getrennte Benutzer </li>
<li> Dropbox Paper, Showcases und Spaces </li>
<li> Dropbox-Apps und Favoriten (Pins/Sterne) </li>
<li> Inhalte, die nicht im Besitz des migrierten Dropbox-Kontos sind </li>
<li> Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Dropbox-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden. Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.) </li>
<li> Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Onlineeinschränkungen und -einschränkungen</span> überschreiten</a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-onedrive-for-business-migrations"></a>FastTrack Zuständigkeiten für OneDrive for Business Migrationen

Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus. Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).

### <a name="your-responsibilities"></a>Ihre Zuständigkeiten

Während des Migrationsprojekts führen Sie Standardaktivitäten aus. Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).

Sie führen außerdem die folgenden Aktivitäten speziell für OneDrive for Business-Migrationen aus:

  - Bereitstellen aller OneDrive for Business-Websites, die für Ihre Migrationsereignisse bestimmt sind.

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a>Migration zu Microsoft Teams und Microsoft 365-Gruppen

Wenn Sie FastTrack verwenden, um Ihre Dateien zu Microsoft Teams und Microsoft 365-Gruppen zu migrieren, stellen wir Migrationsleitfäden und Datenmigrationsdienste bereit. Wir unterstützen Sie bei der Planung Ihrer Migration, beim Konfigurieren Ihrer Quellumgebungen und Teams und Microsoft 365-Gruppen und bei der Nutzung unserer Datenmigrationsdienste für die Migration Ihrer Dateien. Sie erstellen und planen Ihre Migrationsereignisse. Wir führen Migrationsereignisse gemäß Ihrem Zeitplan aus, überwachen deren Status und stellen Statusberichte bereit. Wenn Die Migrationsereignisse abgeschlossen sind, können Sie davon ausgehen, dass Dateien aus entsprechend geplanten und berechtigten Quellen Ihrer Quellumgebungen zu Teams und Microsoft 365 Gruppen migriert wurden. Teams Kanäle und Microsoft 365 Gruppen müssen vom Kunden vorab bereitgestellt werden, bevor sie Daten in diese Zieltypen migrieren können. Teams und Microsoft 365-Gruppen wirken sich auf Ihre Berechtigungen auf den Speicherort des Dateiziels aus. Teams und Microsoft 365 Gruppen werden erstellt, um die Zusammenarbeit zu ermöglichen. Die Teams Kanal oder Microsoft 365 Gruppe bestimmen, wer bei der Migration zu diesen Zielen Zugriff auf diese Dateien hat. FastTrack fügt während der Migration keine Endbenutzer oder Gruppen zu Teams Kanal oder Microsoft 365 Gruppenberechtigung hinzu.

### <a name="considerations"></a>Überlegungen

- Alle Migrationen unterliegen SharePoint Online-Kontingenten. Einzelheiten finden Sie unter <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint Grenzwerten.</a> 
- Der Gesamtbetrag sollte auf 75 Prozent des SharePoint Online-Gesamtspeicherkontingents, für das Sie berechtigt sind, beschränkt werden (einschließlich den zusätzlichen Speicher, den Sie möglicherweise separat gekauft haben). 


### <a name="source-environment-details"></a>Detail der Quellumgebung

Unsere Datenmigrationsdienste migrieren Daten aus diesen Quellumgebungen: 

- Dateifreigaben (SMB [Server Message Block]-Dateifreigaben auf Geräten mit Unterstützung für SMB 2.0 und höher)
-  Eine einzelne G Suite-Umgebung (nur Google Drive). 
- Box (Starter, Business, Enterprise). 
- Dropbox für Teams (Standard und Erweitert). 

Die folgende Tabelle enthält die Migrationsdetails, die für die einzelnen Quellumgebungen gelten:

<table>
<thead>
<tr class="header">
 <th><strong>Quellumgebung</strong></th>
 <th><strong>Migrationstyp</strong></th>
 <th><strong>Was wird migriert?</strong></th>
 <th><strong>Was wird nicht migriert?</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Alle Dateifreigabegeräte mit Unterstützung für SMB 2.0 und höher</strong></td>
<td>Einzeln oder mehrstufig</td>
<td><ul>
<li> Dokumente </li>
<li> Datei- und Ordnerstruktur </li>
<li> Datei- und Ordnerberechtigungen auf Benutzerebene* </li>
<li> Datei- und Ordnerberechtigungen auf Gruppenebene* </li>
<li> Dateien unter 15 GB </li>
<li> Grundlegende Dokument- und Ordnermetadaten: 
<ul>
<li> Erstellungsdatum </li>
<li> Änderungsdatum </li>
<li> Erstellt von </li>
<li> Zuletzt geändert von </li>
</ul></li>
</ul>
<br>
* Setzt die Konfiguration der Verzeichnissynchronisierung voraus. Es werden nur NTFS-Berechtigungen migriert, die für den Windows-Datei-Explorer verfügbar sind. Berechtigungen, die direkt auf Dateifreigabegeräten verwaltet werden, werden nicht migriert. Wenn Daten auf einem SMB 2.0-Gerät gespeichert werden, werden die NTFS-äquivalenten Berechtigungen, die vom SMB-Protokoll verfügbar gemacht werden, migriert. Berechtigungen werden durch den Microsoft 365-Gruppen- und/oder Microsoft Teams-Kanal beeinflusst. Wenn es sich bei dem Ziel um einen Microsoft 365-Gruppen- oder Microsoft Teams-Kanal handelt, bestimmt die Gruppe oder der Kanal das endgültige Berechtigungsprofil für migrierte Dateien. Es wird empfohlen, keine Berechtigungen für Dateien zu migrieren, die zu einem Microsoft 365-Gruppen- oder Microsoft Teams-Kanal migriert werden.</td>
<td><ul>
<li> Besitzverlauf und frühere Versionen </li>
<li> Konvertierung eingebetteter URLs im Inhalt </li>
<li> Frühere Versionen </li>
<li> Windows-Datei-/-Ordnerattribute (z. B. „Schreibgeschützt“ und „Ausgeblendet“)  </li>
<li> Nicht-Windows-NTFS-Dateisystem (New Technology File System) und erweiterte NTFS-Berechtigungen sowie besondere Einstellungen: </li>
<li> Explizite Verweigerungsberechtigungen (werden nach der Migration entfernt, Inhalte unterliegen parallelen Berechtigungen oder Berechtigungen im übergeordneten Ordner). </li>
<li> Konfiguration der NTFS-Überwachung </li>
<li> Zusätzliche Dateimetadaten von der Dateiklassifizierungsinfrastruktur (File Classification Infrastructure, FCI) </li>
<li> Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann </li>
<li> Ausgeblendete Freigaben </li>
<li> Freigabe (z. B. gewährte Berechtigungen auf Freigabeebene) </li>
<li> Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Onlineeinschränkungen und -einschränkungen</span> überschreiten</a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Einzelne G Suite-Umgebung (nur Google Drive)</strong></td>
<td>Einzeln oder mehrstufig</td>
<td><ul>
<li> Google Docs, Google Tabellen und Google Präsentationen (Dateien werden in das entsprechende Office-Format konvertiert, einschließlich derjenigen über 10 MB) </li>
<li> Datei- und Ordnerstruktur </li>
<li> Ordnerberechtigungen auf Benutzerebene* </li>
<li> Ordnerberechtigungen auf Gruppenebene* </li>
<li> Dateien unter 15 GB </li>
<li> Grundlegende Dokument- und Ordnermetadaten: 
<ul>
<li> Erstellungsdatum </li>
<li> Änderungsdatum </li>
<li> Erstellt von </li>
<li> Zuletzt geändert von </li>
</ul></li>
<li> Freigegebene Laufwerke (Ordner und Dateien) </li>
<li> Geteilte Inhalte, die im Besitz des Google Drive-Kontos sind, das migriert wird </li>
</ul>
<br>
*Berechtigungen sind von der Microsoft 365 Gruppe und/oder Microsoft Teams Kanal betroffen. Wenn es sich bei dem Ziel um einen Microsoft 365-Gruppen- oder Microsoft Teams-Kanal handelt, bestimmt die Gruppe oder der Kanal das endgültige Berechtigungsprofil für migrierte Dateien. Es wird empfohlen, keine Berechtigungen für Dateien zu migrieren, die zu einem Microsoft 365-Gruppen- oder Microsoft Teams-Kanal migriert werden. 
</td>
<td><ul>
<li> Besitzverlauf, frühere Versionen und Kommentare </li>
<li> Beschreibungen von Dateien und Ordnern, Ordnerfarben </li>
<li> Berechtigungen für Dateien auf Benutzerebene </li>
<li> Berechtigungen für Dateien auf Gruppenebene </li>
<li> Erweiterte Metadaten </li>
<li> Attribute für Dateisperre </li>
<li> Konvertierung eingebetteter URLs im Inhalt </li>
<li> Gelöschte Elemente </li>
<li> Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann </li>
<li> Blockierte oder inaktive Benutzer </li>
<li> Google Fotos, Google Formulare, Google Maps und andere verbundene Apps </li>
<li> Google Zeichnungen </li>
<li> Freigegebene Inhalte außerhalb Ihrer Organisation </li>
<li> Inhalte, die nicht im Besitz des Google Drive-Kontos sind, das migriert wird </li>
<li> Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Google Drive-Administratorberichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden. Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.) </li>
<li> Mitgliedschaftsberechtigungen für freigegebene Laufwerke (<strong>Hinweis</strong>: Verwenden Sie die Google Drive-Administratorberichte, um die Mitgliedschaften für freigegebene Laufwerke zu identifizieren. Weisen Sie die Endbenutzer an, diese Mitgliedschaftseinstellungen auf dem Ziel vor der Migration zu konfigurieren.) </li>
<li> Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Onlineeinschränkungen und -einschränkungen</span> überschreiten</a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter, Business, Enterprise)</strong></td>
<td>Einzeln oder mehrstufig</td>
<td><ul>
<li> Dokumente </li>
<li> Datei- und Ordnerstruktur </li>
<li> Ordnerberechtigungen auf Benutzerebene* </li>
<li> Ordnerberechtigungen auf Gruppenebene* </li>
<li> Dateien unter 15 GB </li>
<li> Grundlegende Dokument- und Ordnermetadaten: 
<ul>
<li> Erstellungsdatum </li>
<li> Änderungsdatum </li>
<li> Erstellt von </li>
<li> Zuletzt geändert von </li>
</ul></li>
<li> Geteilte Inhalte, die im Besitz des Box-Kontos sind, das migriert wird </li>
<li> Feldnotizen (in Word-Dokumentformat konvertiert) </li>
</ul>
<br>
*Berechtigungen sind von der Microsoft 365 Gruppe und/oder Microsoft Teams Kanal betroffen. Wenn es sich bei dem Ziel um einen Microsoft 365-Gruppen- oder Microsoft Teams-Kanal handelt, bestimmt die Gruppe oder der Kanal das endgültige Berechtigungsprofil für migrierte Dateien. Es wird empfohlen, keine Berechtigungen für Dateien zu migrieren, die zu einem Microsoft 365-Gruppen- oder Microsoft Teams-Kanal migriert werden. </td>
<td><ul>
<li> Besitzverlauf, frühere Versionen und Kommentare </li>
<li> Beschreibungen von Dateien und Ordnern </li>
<li> Berechtigungen für Dateien auf Benutzerebene </li>
<li> Berechtigungen für Dateien auf Gruppenebene </li>
<li> Box-Tags und erweiterte Metadaten </li>
<li> Attribute für Dateisperre </li>
<li> Konvertierung eingebetteter URLs im Inhalt </li>
<li> Gelöschte Elemente </li>
<li> Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann </li>
<li> Blockierte oder inaktive Benutzer </li>
<li> Box-Apps, Lesezeichen, Favoriten und Workflows </li>
<li> Inhalte, die nicht im Besitz des migrierten Box-Kontos sind </li>
<li> Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Box-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden. Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.) </li>
<li> Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Onlineeinschränkungen und -einschränkungen</span> überschreiten</a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Dropbox für Teams (Standard und Erweitert)</strong></td>
<td>Einzeln oder mehrstufig</td>
<td><ul>
<li> Dokumente </li>
<li> Datei- und Ordnerstruktur </li>
<li> Ordnerberechtigungen auf Benutzerebene* </li>
<li> Ordnerberechtigungen auf Gruppenebene* </li>
<li> Dateien unter 15 GB </li>
<li> Grundlegende Dokument- und Ordnermetadaten: 
<ul>
<li> Erstellungsdatum </li>
<li> Änderungsdatum </li>
<li> Erstellt von </li>
<li> Zuletzt geändert von </li>
</ul></li>
<li> Freigegebene Teamordner und -inhalte </li>
<li> Geteilte Inhalte, die im Besitz des Dropbox-Kontos sind, das migriert wird </li>
</ul>
<br>
*Berechtigungen sind von der Microsoft 365 Gruppe und/oder Microsoft Teams Kanal betroffen. Wenn es sich bei dem Ziel um einen Microsoft 365-Gruppen- oder Microsoft Teams-Kanal handelt, bestimmt die Gruppe oder der Kanal das endgültige Berechtigungsprofil für migrierte Dateien. Es wird empfohlen, keine Berechtigungen für Dateien zu migrieren, die zu einem Microsoft 365-Gruppen- oder Microsoft Teams-Kanal migriert werden.
</td>
<td><ul>
<li> Besitzverlauf, frühere Versionen und Kommentare </li>
<li> Beschreibungen von Dateien und Ordnern </li>
<li> Berechtigungen für Dateien auf Benutzerebene </li>
<li> Berechtigungen für Dateien auf Gruppenebene </li>
<li> Erweiterte Metadaten </li>
<li> Attribute für Dateisperre </li>
<li> Konvertierung eingebetteter URLs im Inhalt </li>
<li> Gelöschte Elemente </li>
<li> Beschädigte Dokumente und Dokumente, auf die nicht zugegriffen werden kann </li>
<li> Nicht gemountete Dropbox-Ordner </li>
<li> Gelöschte oder getrennte Benutzer </li>
<li> Dropbox Paper, Showcases und Spaces </li>
<li> Dropbox-Apps und Favoriten (Pins/Sterne) </li>
<li> Inhalte, die nicht im Besitz des migrierten Dropbox-Kontos sind </li>
<li> Berechtigungen und grundlegende Metadaten von externen Benutzern (<strong>Hinweis</strong>: Verwenden Sie Dropbox-Berichte zum Identifizieren von Inhalten, die für externe Benutzer freigegeben wurden. Weisen Sie Endbenutzer an, Inhalte nach der Migration erneut für externe Benutzer freizugeben.) </li>
<li> Dateien oder Ordner, die aktuelle <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Onlineeinschränkungen und -einschränkungen</span> überschreiten</a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-microsoft-teams-and-microsoft-365-groups-migrations"></a>FastTrack Zuständigkeiten für Microsoft Teams- und Microsoft 365-Gruppenmigrationen

Während des Migrationsprojekts führen unsere FastTrack-Spezialisten Standardaktivitäten aus. Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).

### <a name="your-responsibilities"></a>Ihre Zuständigkeiten 

Während des Migrationsprojekts führen Sie Standardaktivitäten aus. Einzelheiten hierzu finden Sie in den Informationen zu Datenmigrationszuständigkeiten unter [Prozess und Erwartungen](process-and-expectations.md).
Außerdem führen Sie die folgenden Aktivitäten speziell für Microsoft Teams- und Microsoft 365-Gruppenmigrationen aus: 

- Stellen Sie alle Microsoft Teams Kanäle und Microsoft 365 Gruppen entsprechend Ihren Migrationsereignissen bereit.

> [!NOTE]
>FastTrack stellt Microsoft Teams Kanäle oder Microsoft 365 Gruppen nicht vorab bereit. FastTrack fügt keine Endbenutzer oder Gruppen zu Microsoft Teams Kanälen oder Microsoft 365 Gruppen hinzu. Sie müssen Ihre Endbenutzer oder Gruppen allen Microsoft Teams Kanälen und Microsoft 365 Gruppen hinzufügen, bevor Sie Daten zu diesen Zielen migrieren, damit diese Endbenutzer Zugriff auf diese neu migrierten Dokumente haben.