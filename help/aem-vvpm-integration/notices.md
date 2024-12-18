---
title: Veeva Vault-Integrationshinweise
description: Veeva Vault-Integrationshinweise
exl-id: 1a188671-d123-4475-a607-65743ba0dadd
source-git-commit: 07eab1e439626bd3bb3416c9e7d0c1666927a7aa
workflow-type: tm+mt
source-wordcount: '254'
ht-degree: 1%

---

# Best Practices, Leitplanken und Hinweise

## Versionen

Für diese Integration sind mindestens die folgenden Softwareversionen erforderlich:

* Adobe Experience Manager, 6.5.5+
* Veeva Vault PromoMats, 20R3.2+

## Datenschutz

Diese Integration dient der Übertragung von Inhalten zwischen Adobe Experience Manager und Veeva Vault PromoMats. Als Datenverantwortlicher ist Ihr Unternehmen dafür verantwortlich, alle Datenschutzgesetze und -vorschriften einzuhalten, die für Ihre Datenerfassung und -nutzung gelten.

## Häufigkeit der Inhaltssynchronisierung

AEM-Inhalte und Metadaten werden von AEM zu VPN synchronisiert, wenn der Integrations-Workflow ausgelöst wurde. Dies kann automatisch oder manuell erfolgen. VPM-Metadaten werden von VPM mit AEM synchronisiert. Dies kann automatisch über eine Planung oder manuell über einen Schaltflächen-Klick erfolgen.

## Integrationsbeschränkungen und Best Practices und Leitlinien

Beachten Sie die folgenden Einschränkungen bei der Verwendung dieser Integration:

* Beim Synchronisieren von Metadaten werden nur die folgenden Datentypen unterstützt: „Text“ und „Mehrzeiliger Text“.
* Die Integration unterstützt zwar modulare AEM-Inhalte (Inhaltsfragmente und Experience Fragments), jedoch keine modularen VPM-Inhalte.
* Verknüpfte VPM-Dokumente werden nicht unterstützt.
* Das Synchronisieren visueller VVPM-Anmerkungen von VPM zu AEM wird nicht unterstützt.
* Die Integration importiert keine Inhalte von VPM in AEM.
* Die Metadatenvalidierung wird nicht unterstützt.
* Die Anzahl der Dokumente ist aufgrund der Veeva-Lizenz begrenzt. Siehe [Lizenzbeschränkungen](#veeva-license-limitations).
* Die Anzahl der API-Aufrufe ist aufgrund der Veeva-Lizenz begrenzt. Weitere Informationen finden Sie unter [API-Einschränkungen](https://developer.veevavault.com/docs/#what-are-rate-limits). Siehe [Lizenzbeschränkungen](#veeva-license-limitations).

## Veeva-Lizenzbeschränkungen

Sie können die Beschränkungen Ihrer Instanzen überwachen, indem Sie zu den allgemeinen VPM-Einstellungen navigieren.

![Veeva-Beschränkungen](assets/veeva-limits.png)
