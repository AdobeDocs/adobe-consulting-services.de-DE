---
product: adobe experience manager
solution: Experience Manager
description: Experience Manager-Dokumentation besuchen
type: Documentation
git-repo: https://github.com/AdobeDocs/adobe-consulting-services.de-DE
index: y
source-git-commit: e2dac4b36fb94d72b72ef6f73a77e3f566539444
workflow-type: tm+mt
source-wordcount: '81'
ht-degree: 54%

---


# Metadaten für die interne Verwendung

Metadaten im GitHub-Authoring-System sind hierarchisch aufgebaut und werden in den folgenden zunehmenden Präzedenzebenen definiert.

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

Weitere Informationen zu den Metadaten finden Sie im Abschnitt [Internes Authoring-Handbuch](https://experienceleague.adobe.com/docs/authoring-guide-exl/using/authoring/metadata.html).
