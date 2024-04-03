---
title: Häufig gestellte Fragen zur VEC Vault-Integration
description: Häufig gestellte Fragen zur VEC Vault-Integration
exl-id: c308ebb3-7881-4094-9f35-c67a96fb5ab1
source-git-commit: e4a5e55ac9b79a8de7dfa8ddd3d0ad99560917b8
workflow-type: tm+mt
source-wordcount: '322'
ht-degree: 1%

---

# Häufig gestellte Fragen

**Welche Metadaten sollten mit Veeva synchronisiert werden?**

Es ist wichtig, die Metadaten basierend auf dem Inhaltstyp (z. B. Promotions) im Veva Portal zu verstehen. Erstellen Sie nach der Überprüfung des eVeva-Portals das Metadatenschema des Inhalts in AEM, um alle relevanten Metadaten für jedes Asset/jede Seite zu speichern, und konfigurieren Sie die Integration, um die Metadaten zwischen den beiden Systemen zuzuordnen.

**Unterstützt die Integration die verlinkten Dokumente von Veeva? Wenn nicht, welche Beziehungstypen werden unterstützt?**

Nein. Siehe [Veeva documentations](https://vaulthelp2.vod309.com/wordpress/admin-user-help/documents-admin-user-help/about-document-relationships/). Das verknüpfte Dokument (Referenzbeziehungstyp) ist einer der standardmäßigen Beziehungstypen, die nicht über API erstellt oder gelöscht werden können, da sie ein spezielles Vault-Verhalten aufweisen. Komponenten, unterstützende Dokumente und alle anderen, die nicht in dieser Liste aufgeführt sind, sollten über die Konfiguration AEM Veeva Cloud konfiguriert werden können.

**Unterstützt die Integration den modularen AEM Inhalt?**

Ja, die Integration unterstützt AEM Inhaltsfragmente und Experience Fragments.

**Unterstützt die Integration den modularen Inhalt von Veeva?**

Nein, jetzt nicht.

**Synchronisiert die Integration visuelle Anmerkungen von Veeva mit AEM?**

Nein, jetzt nicht. Visuelle Anmerkungen sind nur über API als PDF verfügbar.

**Wie werden Berechtigungen für VPM-Dokumente festgelegt, die von der Integration synchronisiert werden?**

Die Integration verwendet einen Dienstbenutzer, um Dokumente über die API hochzuladen.  Dokumentstandardregeln und Überschreibungsregeln (Standardrollen für Dokumente) werden nur in der VVPM-Benutzeroberfläche unterstützt und nicht bei der Verwendung der API. Es wird empfohlen, DAC (Dynamic Access Control) für Rollenzuweisungen zu verwenden. DAC wird über alle Touchpoints erzwungen, einschließlich der API. [Die Dokumentation finden Sie hier.](http://vaulthelp2.vod309.com/wordpress/admin-user-help/ah-user-permissions-access-control/about-dynamic-access-control-for-documents/)

**Unterstützt die Integration mehrere VPM-Instanzen?**

Die Integration verwendet einen Cloud-Konfigurationsansatz, der die Konfiguration mehrerer Veeva-Endpunkte von einer AEM Instanz aus ermöglicht.

**Unterstützt die Integration AEM Veröffentlichung?**

Nein, diese Integration funktioniert nur mit AEM Autor. Sie soll MLR-Überprüfungszyklen vor der Veröffentlichung des Inhalts erleichtern.
