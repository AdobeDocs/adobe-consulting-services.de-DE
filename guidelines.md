---
source-git-commit: bdc8e76125282ab294e34c5216311524e015c175
workflow-type: tm+mt
source-wordcount: '763'
ht-degree: 2%
---
# Richtlinien für Beiträge zur Adobe Consulting Services-Dokumentation

## Dokumentationsphilosophie

Wir wissen, dass Adobe Experience Manager-Anwender in einem hart umkämpften Umfeld arbeiten und sich bemühen, digitale Erlebnisse zu schaffen, die sie von ihren Mitbewerbern unterscheiden. Wenn ACS fortschrittliche neue Tools für AEM bereitstellt, müssen diese unbedingt durch genaue und klare Dokumentation ergänzt werden, damit der Kunde sofort seine AEM-Investition nutzen und den ROI maximieren kann.

Ziel der ACS-Dokumentation ist es, AEM-Anwendern die Dokumentation so schnell wie möglich zugänglich zu machen. Deshalb setzen wir auf genaue, brauchbare Dokumentation und bemühen uns, sie kontinuierlich zu aktualisieren und zu verbessern.

## Dokumentationsbeiträge

Zur stetigen Verbesserung der ACS-Dokumentation ist die gesamte Community von AEM-Anwendern herzlich eingeladen, zur Dokumentation beizutragen. Sei es durch Pull-Anfragen oder -Probleme, Verbesserungen an der Dokumentation können Korrekturen, Klarstellungen, Erweiterungen und zusätzliche Beispiele sein.

## Dokumentationsstandards

Auch wenn wir Beiträge zu unserer Dokumentation begrüßen, sollte jeder Beitrag zur AEM-Dokumentation, entweder in Form einer Pull-Anfrage oder eines Problems, unseren Beitrags- und Dokumentationsstandards entsprechen.

Beiträge, die diese Standards nicht erfüllen, können abgelehnt werden.

### Wir dokumentieren Standard-Anwendungsfälle.

Die ACS-Dokumentation deckt Standard-Anwendungsfälle ab. Anwendungsfälle, die über den Umfang der standardmäßigen Installation und Verwendung des Produkts hinausgehen, sind nicht Teil der ACS-Dokumentation.

### Generell dokumentieren wir keine Fehler oder Problemumgehungen.

Die ACS-Dokumentation deckt Standard-Anwendungsfälle ab. Aus diesem Grund werden Fehler, durch Bugs verursachte Auswirkungen und Problemumgehungen für Bugs im Allgemeinen nicht dokumentiert.

Ausnahmen von dieser Regel gelten für die Versionshinweise, in denen bekannte Probleme mit möglichen Lösungen aufgelistet werden können, die vom AEM-Produktmanagement genehmigt wurden.

### Dokumentationsbeiträge dienen nicht zur Beantwortung technischer Fragen.

Alle Ideen zur Verbesserung der ACS-Dokumentation sind als Beiträge willkommen. Kommentare, Probleme und Pull-Anfragen sind jedoch nur für *Beiträge* vorgesehen. Sie sind nicht zur Beantwortung Ihrer Fragen über die Verwendung von AEM, Implementierung Ihres AEM-Projekts oder zur Lösung technischer Probleme vorgesehen.

Fragen zur Verwendung von AEM oder zu technischen Fehlern, die möglicherweise bei Ihnen auftreten, sollten entsprechend dem herkömmlichen Support-Vorgang über das [Enterprise-Support-Portal für Experience Cloud](https://helpx.adobe.com/de/contact/enterprise-support.ec.html) gemeldet oder in der [Experience Manager-Community diskutiert &#x200B;](https://forums.adobe.com/community/experience-cloud/marketing-cloud/experience-manager).

***ACS-Dokumentationsbeiträge sind kein Ersatz für die Adobe-Kundenunterstützung*** und Beiträge, die um Antwort auf Support-Fragen bitten, werden abgelehnt.

### Die Beiträge müssen klar auf die betroffenen Dokumentationsseiten verweisen.

Wenn Sie ein Problem erstellen, um Verbesserungen an der Dokumentation vorzuschlagen, müssen Sie Links zu den betroffenen Seiten einfügen. Wenn Sie ein Problem über den Link **Diese Seite bearbeiten** auf einer Dokumentationsseite erstellen, wird das Problem automatisch mit einem Link zur Seite erstellt.

Dies gilt nicht für Pull-Anforderungen, da Pull-Anforderungen ihrer Art nach auf die betroffene(n) Seite(n) verweisen.

## Dokumentationsrichtlinien

Wir bitten darum, dass alle Beiträge zu unserer Dokumentation bestimmten Stilrichtlinien entsprechen.

Die Befolgung dieser Richtlinien erleichtert die Überprüfung Ihres Beitrags und ermöglicht eine schnellere Integration in unsere Dokumentation.

### Sprache und Stil

#### Sprache

* Die ACS-Dokumentation wird in englischer Sprache verfasst und gepflegt.
* Halten Sie Sätze so einfach wie möglich.
* Halten Sie die Sprache klar und prägnant.

Denken Sie daran, dass die Leser der ACS-Dokumentation auf der ganzen Welt zu finden sind und von ihnen nicht erwartet werden kann, dass sie fließend Englisch beherrschen oder Muttersprachler sind. Umgangssprachliche Formulierungen vermeiden und die Sprache so klar und einfach wie möglich halten.

#### Folgen Sie dem Microsoft Manual of Style

[Das Manual of Style von Microsoft](https://docs.microsoft.com/en-us/style-guide/welcome/) ist ein kostenloses Stil-Handbuch zur Dokumentation von Software. Die AEM-Dokumentation folgt soweit möglich diesem Modell.

### Formatierung

| Element | Stil |
|---|---|
| Element oder Option der Benutzeroberfläche | **fett** |
| Dateiname, Pfad, Benutzereingabe, Parameterwerte | `monospaced` |
| Code, Befehlszeile | ```Code Block``` |

### Screenshots

Screenshots sind umsichtig und nur dann zu verwenden, wenn eine textliche Beschreibung nicht ausreicht.

Markierungen oder andere Anmerkungen in Screenshots (wie rote Rahmen, Pfeile oder Text) sollten nicht verwendet werden. Auf diese Weise sind die Screenshots in lokalisierten Versionen der Dokumentation einfacher wiederzuverwenden oder zu replizieren.

### Versionsspezifische Verweise

Versuchen Sie möglichst im gesamten Dokumentationsinhalt direkte Verweise auf eine bestimmte Version zu vermeiden. Dies macht die Dokumentation flexibler und erweiterbar für zukünftige Versionen.

### Verwendung von Day, AEM, CQ, CRX

Das Produkt sollte in einem Artikel zum ersten Mal immer mit dem vollständigen Namen **Adobe Experience Manager** genannt und anschließend als **AEM** bezeichnet werden.

Day, Day-Software, CQ und CRX sollten nur verwendet werden, wenn dies unvermeidlich ist, z. B. bei Klassennamen oder bei Verweisen auf die Historie von AEM.