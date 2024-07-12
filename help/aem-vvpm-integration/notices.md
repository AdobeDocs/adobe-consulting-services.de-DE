---
title: Veva Vault-Integrationshinweise
description: Veva Vault-Integrationshinweise
exl-id: 1a188671-d123-4475-a607-65743ba0dadd
source-git-commit: 07eab1e439626bd3bb3416c9e7d0c1666927a7aa
workflow-type: tm+mt
source-wordcount: '254'
ht-degree: 1%

---

# Best Practices, Limits und Hinweise

## Versionen

Für diese Integration sind die folgenden Mindestversionen von Software erforderlich:

* Adobe Experience Manager, 6.5.5+
* Veeva Vault PromoMats, 20R3.2+

## Datenschutz

Diese Integration wurde entwickelt, um Inhalte zwischen Adobe Experience Manager und Veeva Vault PromoMats zu übertragen. Als Datenverantwortlicher ist Ihr Unternehmen für die Einhaltung der Datenschutzgesetze und -vorschriften für Ihre Datenerfassung und -nutzung verantwortlich.

## Häufigkeit der Inhaltssynchronisierung

AEM Inhalte und Metadaten werden von AEM mit VVPN synchronisiert, wenn der Integrations-Workflow ausgelöst wurde. Dies kann automatisch oder manuell erfolgen. VVPM-Metadaten werden von VPM mit AEM synchronisiert. Dies kann automatisch über einen Planer oder manuell über einen Schaltflächenklick erfolgen.

## Integrationsbeschränkungen und Best Practices und Limits

Beachten Sie bei der Verwendung dieser Integration die folgenden Einschränkungen:

* Beim Synchronisieren von Metadaten werden nur die folgenden Datentypen unterstützt: &quot;Text&quot;und &quot;Mehrzeiliger Text&quot;.
* Die Integration unterstützt zwar AEM modularen Inhalt (Inhaltsfragmente und Experience Fragments), unterstützt jedoch keine modularen VVPM-Inhalte.
* VVPM-verknüpfte Dokumente werden nicht unterstützt.
* Die Synchronisierung visueller VVPM-Anmerkungen von VVPM mit AEM wird nicht unterstützt.
* Die Integration importiert keine Inhalte von VPM in AEM.
* Die Metadatenvalidierung wird nicht unterstützt.
* Die Anzahl der Dokumente ist auf der Grundlage der Veeva-Lizenz begrenzt. Siehe [Lizenzbeschränkungen](#veeva-license-limitations).
* Die Anzahl der API-Aufrufe ist auf der Grundlage der Veeva-Lizenz begrenzt. Weitere Informationen finden Sie unter [API-Beschränkungen](https://developer.veevavault.com/docs/#what-are-rate-limits). Siehe [Lizenzbeschränkungen](#veeva-license-limitations).

## VEE-Lizenzbeschränkungen

Sie können die Instanzbeschränkungen überwachen, indem Sie zu den allgemeinen VVPM-Einstellungen navigieren.

![Veeva-Beschränkungen](assets/veeva-limits.png)
