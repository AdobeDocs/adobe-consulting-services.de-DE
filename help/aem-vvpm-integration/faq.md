---
title: Häufig gestellte Fragen zur Veeva Vault-Integration
description: Häufig gestellte Fragen zur Veeva Vault-Integration
exl-id: c308ebb3-7881-4094-9f35-c67a96fb5ab1
source-git-commit: b024e4295b5b37030c1524342832400c279c650a
workflow-type: tm+mt
source-wordcount: '322'
ht-degree: 1%

---

# Häufig gestellte Fragen

**Welche Metadaten sollten mit Veeva synchronisiert werden?**

Es ist wichtig, die Metadaten basierend auf dem Inhaltstyp (z. B. Werbeaktionen) im Veeva-Portal zu verstehen. Erstellen Sie nach der Überprüfung des Veeva-Portals das Metadatenschema für Inhalte in AEM, um alle relevanten Metadaten für jedes Asset/jede Seite zu speichern, und konfigurieren Sie die Integration so, dass die Metadaten zwischen den beiden Systemen zugeordnet werden.

**Unterstützt die Integration die mit Veeva verknüpften Dokumente? Falls nicht, welche Beziehungstypen werden unterstützt?**

Nein. Siehe [Veeva-](https://vaulthelp2.vod309.com/wordpress/admin-user-help/documents-admin-user-help/about-document-relationships/). Das verknüpfte Dokument (Referenzbeziehungstyp) ist einer der Standardbeziehungstypen, die nicht über die API erstellt oder gelöscht werden können, da sie ein spezielles Vault-Verhalten aufweisen. Komponenten, unterstützende Dokumente und alle anderen nicht in dieser Liste enthaltenen sollten über die AEM Veeva Cloud-Konfiguration konfiguriert werden können.

**Unterstützt die Integration den modularen Inhalt von AEM?**

Ja, die Integration unterstützt AEM-Inhaltsfragmente und Experience Fragments.

**Unterstützt die Integration den modularen Inhalt von Veeva?**

Nein, jetzt nicht.

**Synchronisiert die Integration visuelle Anmerkungen in Veeva mit AEM?**

Nein, jetzt nicht. Visuelle Anmerkungen sind nur über API as a PDF zugänglich.

**Wie legen wir Berechtigungen für VPM-Dokumente fest, die durch die Integration synchronisiert werden?**

Die Integration verwendet einen Dienstbenutzer, um Dokumente über die API hochzuladen.  Dokumentstandardwerte und -überschreibungen (Standardrollen für Dokumente) werden nur in der VPM-Benutzeroberfläche unterstützt und bei Verwendung der API nicht angewendet. Es wird empfohlen, DAC (Dynamic Access Control) für Rollenzuweisungen zu verwenden. DAC wird über alle Touchpoints einschließlich der -API erzwungen. [Siehe die Dokumentation hier.](http://vaulthelp2.vod309.com/wordpress/admin-user-help/ah-user-permissions-access-control/about-dynamic-access-control-for-documents/)

**Unterstützt die Integration mehrere VVPM-Instanzen?**

Die Integration verwendet einen Cloud-Konfigurationsansatz, der es ermöglicht, mehrere Veeva-Endpunkte von einer AEM-Instanz aus zu konfigurieren.

**Unterstützt die Integration die Veröffentlichung in AEM?**

Nein, diese Integration funktioniert nur mit AEM Author. Sie soll MLR-Prüfungszyklen vor der Veröffentlichung des Inhalts erleichtern.
