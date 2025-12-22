---
product: adobe experience manager
solution: Experience Manager
description: Lesen der Dokumentation zu Experience Manager
type: Documentation
git-repo: https://github.com/Adobe-Enterprise-Docs/adobe-consulting-services.de-DE
index: y
hide: n
source-git-commit: d36298f9c8abf2859e2a8fc9be92d2fcae8d60cf
workflow-type: tm+mt
source-wordcount: '81'
ht-degree: 54%

---


# Metadaten für die interne Verwendung

Metadaten im GitHub-Authoring-System sind hierarchisch und werden in den folgenden zunehmenden Präzedenzfällen definiert.

1. metadata.md
1. IHV
1. Artikel

Die in der Datei „metadata.md“ definierten Metadaten gelten für den gesamten Bericht, können jedoch auf der IHV- (ToC) und der Artikelebene überschrieben werden. Das Überschreiben der Metadaten sollte auf der niedrigstmöglichen Ebene erfolgen.

metadata.md

* `product`
* `git-repo`
* `index: y`

IHVs

* `sub-product`
* `user-guide-title`

Artikel

* `title`
* `description`

Weitere Informationen zu den Metadaten finden Sie im [internen Authoring-Handbuch](https://experienceleague.adobe.com/docs/authoring-guide-exl/using/authoring/metadata.html).
