---
title: Übersicht zur Veva Vault-Integration
description: Übersicht zur Veva Vault-Integration
exl-id: 52cc7290-b7e1-4476-877f-48934e6daf68
source-git-commit: 2e47baa4a255c34b3ca0b8631650dd5d8960fea8
workflow-type: tm+mt
source-wordcount: '692'
ht-degree: 0%

---

# Erste Schritte mit der Integration von Veva Vault PromoMats und Adobe Experience Manager

Diese Integration verwaltet Ihre Inhalte, erzwingt Rechte und Konformität und nutzt gleichzeitig die ersten Funktionen bei der Bereitstellung von Erlebnissen.

Für diese Integration sind die folgenden Mindestversionen von Software erforderlich:

* Adobe Experience Manager, 6.5.5+
* Veeva Vault PromoMats, 20R3.2+

>[!NOTE]
>
>Dienstbenutzer und entsprechende Berechtigungen sind in beiden Systemen für die Integration erforderlich.
>

>[!IMPORTANT]
>
>Diese Funktion ist nicht standardmäßig als Teil des Produkts verfügbar. Für die Implementierung ist ein Adobe Consulting-Wartungsvertrag erforderlich. Wenden Sie sich an Ihren Adobe-Support-Mitarbeiter, um mehr zu erfahren.
>

## Grundsätze und Funktionen

Diese Integration unterstützt zwei Hauptanwendungsfälle:

1. Inhaltsvalidierung - Wenn neue Inhalte erstellt wurden oder vorhandene Inhalte in AEM bearbeitet wurden, muss der Inhalt für die Verwendung in VVPM genehmigt werden, das den Genehmigungsprozess für Medical, Legal, Regulatory (MLR) für Life Sciences unterstützt.
1. Content Management - Stellen Sie die Sichtbarkeit der Asset-Nutzung bereit, indem Sie in PromoMats Beziehungen zwischen digitalen Taktiken (z. B. E-Mail, Präsentationen, Websites) und deren Elementen (z. B. Logos, Fotografie, Grafiken) herstellen, die in AEM für Dokumente aus AEM erstellt wurden.

Zu den Vorteilen zählen:

* Sicherstellen einer einzigen Quelle der Wahrheit für Assets und Inhalte ohne Duplizierung in digitalen Repositorys.
* Nutzen Sie sowohl Veeva Vault für Rechte- und Compliance-Management als auch AEM für die beste Klasse- und Asset- und Inhaltserstellung/-bereitstellung.
* Hilft bei der Automatisierung des Verschieben von Inhalten und Metadaten zwischen AEM und Veeva Vault.
* Verringert den manuellen Aufwand beim Senden von Inhalten an Veeva für Genehmigungs-Workflows.
* Jedes System wird für seine Stärken eingesetzt und der Connector unterstützt die automatische Verschiebung von Inhalten zwischen den Systemen, um die Time-to-Market zu beschleunigen.

Was bewirkt die Integration?

* Unterstützt das Senden AEM Site-Seiten, Assets, Inhaltsfragmente und Experience Fragments an VPM. AEM Seiten, Inhaltsfragmente und Experience Fragments können als Screenshot-PDF oder Bilder gesendet werden. AEM Assets-Binärdateien werden unverändert gesendet.
* Unterstützt die manuelle und automatisierte Synchronisierung ausgewählter Metadatenelemente, die von AEM zu VVPM konfigurierbar sind.
* Unterstützt die manuelle und automatisierte Synchronisierung ausgewählter Metadatenelemente, die von VPM zu AEM konfigurierbar sind.
* Unterstützt Beziehungen zwischen AEM Site-Seiten, Assets, Inhaltsfragmenten und Experience Fragments in VVPM, um Inhaltsbeziehungen zu automatisieren.
* Unterstützt die Ausgabegenerierung für mehrere Gerätetypen.

>[!NOTE]
>
>Weitere Informationen zu Konfigurationsoptionen finden Sie in der Dokumentation zur Integrationsnutzung .
>

Was macht der Connector NICHT?

* Repliziert keine AEM Prozesse und Funktionen in Veeva oder umgekehrt.
* Führt keine MLRs allein aus. Es unterstützt die Automatisierung des Versands von Inhalten an Veeva, wo MLRs auftreten.
* Nicht für die Erstellung einer identischen Einrichtung zwischen AEM und Veeva vorgesehen. Nicht alle Inhalte müssen zwischen den beiden Plattformen verschoben werden.


>[!IMPORTANT]
>
>Diese Integration betrachtet AEM derzeit als &quot;Source of Truth&quot; für die Synchronisierung von Inhalten.

## Abrufen der Integration

Um diese Integration bereitzustellen, müssen Sie die folgenden Schritte ausführen.

Befolgen Sie das unten stehende Flussdiagramm und die Details des Flussdiagramms, um die Integration anzufordern und zu konfigurieren.

![Zugriff anfordern](assets/integration-request.png)

Flussdiagrammdetails (sind den oben genannten Schritten zugeordnet):

* **Schritt 1** - Es wird davon ausgegangen, dass Sie bereits über eine Lizenz für Veeva Vault PromoMats und für Adobe Experience Manager verfügen oder diese gerade erwerben.
* **Schritt 2** - Ein neuer Auftrag (SO), in dem ein Wartungsvertrag mit Adobe Consulting beschrieben wird, muss unterzeichnet werden, um die Integration nutzen zu können.
* **Schritt 3** - Installieren, Aktivieren und Konfigurieren des Integrationspakets.

## Support

Im Folgenden wird beschrieben, wie Sie ein Problem beim Support-Team melden und kontaktieren können.

### Anfordern der Integration oder Adobe Experience Manager-Unterstützung

Support-Tickets können bei der Adobe-Kundenunterstützung protokolliert werden. Ihr Adobe Experience Cloud-Administrator muss sich bei [Adobe Admin Console](https://adminconsole.adobe.com/) anmelden, auf die Registerkarte &quot;Support&quot;klicken und eine Groß-/Kleinschreibung erstellen. Achten Sie bei Integrationsproblemen darauf, die folgenden Informationen einzuschließen:

* **Prozesstitel**: `AEM - Veeva Vault Integration`
* **Prozesseigentümer**: `Data Engineering`
* **Beschreibung**: `Description of the issue`
* **Kontaktpunkt**: `The email address(es) for relavant AEM point of contacts for your organization.`
* **AEM Instanz-URL**: `Place the Adobe Experience Manager instance url here.`
* **VEC-Instanz-URL**: `Place the Veeva Vault PromoMats instance url here.`

### Anfordern der Unterstützung von Vevar Vault PromoMats

Manchmal handelt es sich bei dem aufgetretenen Problem um ein Problem mit dem Betrieb der Veva Vault PromoMats-Instanz. Sollte dies der Fall sein, kann Ihr Veva Vault PromoMats-Administrator angewiesen werden, ein Support-Ticket mit dem [VEE-Support](http://support.veeva.com/) zu erstellen. Der Status der VEE-Instanz kann durch Navigieren zu [VEA-Vertrauen](http://trust.veeva.com/) angezeigt werden.

