---
product: adobe experience manager
solution: Experience Manager
product_v2:
  - id: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
usetq: true
description: Lesen der Dokumentation zu Experience Manager
type: Documentation
git-repo: https://github.com/AdobeDocs/adobe-consulting-services.de-DE
index: true
source-git-commit: e0159a3db7c79d12ee150be018ee5d005975b95a
workflow-type: tm+mt
source-wordcount: 94
ht-degree: 2%

---


# Metadaten für die interne Verwendung

Metadaten im GitHub-Authoring-System sind hierarchisch und werden in den folgenden zunehmenden Präzedenzfällen definiert.

1. metadata.md
1. toC
1. Artikel

Metadaten, die in der Datei „metadata.md“ definiert sind, gelten für das gesamte Repository, können jedoch auf der Inhaltsverzeichnis- und Artikelebene überschrieben werden. Jede Überschreibung der Metadaten sollte auf der niedrigstmöglichen Ebene erfolgen.

metadata.md

* `product`
* `git-repo`
* `index: y`

toCS

* `sub-product`
* `user-guide-title`

Artikel

* `title`
* `description`

Weitere Informationen zu den Metadaten finden Sie im [internen Authoring-Handbuch](https://experienceleague.adobe.com/docs/authoring-guide-exl/using/authoring/metadata.html).
