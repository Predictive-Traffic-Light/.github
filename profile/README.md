# Prädiktive KI-Ampelschaltung Konstanz

[![Smart Green City](https://img.shields.io/badge/Initiative-Smart%20Green%20City-green)](https://smart-green-city-konstanz.de/)
[![Status](https://img.shields.io/badge/Projektstatus-In%20Umsetzung-blue)](#projektstand-und-meilensteine)

Dieses Repository dient als zentrale Übersicht für das Gesamtprojekt zur **prädiktiven KI-gestützten Ampelsteuerung** in Konstanz. 

Das Projekt ist Teil der **Smart Green City Konstanz** Initiative. Es verbindet künstliche Intelligenz mit moderner Sensortechnik, um den Verkehr für Fußgängerinnen und Fußgänger, Radfahrende sowie den Kfz-Verkehr intelligenter, effizienter und komfortabler zu steuern.

> 🌐 **Offizielle Projektseite:** [smart-green-city-konstanz.de/KI_Ampelschaltung](https://smart-green-city-konstanz.de/KI_Ampelschaltung)

---

## Projektidee

Die KI-Ampelschaltung soll erkennen, ob eine Person voraussichtlich eine Straße überqueren möchte, **bevor** sie den Überweg erreicht. Dadurch kann die Ampel automatisch auf Grün schalten, ohne dass ein Tastendruck am Ampelknopf nötig ist.

### Wesentliche Ziele
* **Weniger Wartezeiten** für den Fußverkehr.
* **Höherer Komfort** und verbesserte Verkehrssicherheit.
* **Effizientere Koordination** verschiedener Verkehrsarten (ÖPNV, Rad, Auto, Fußgänger).
* **Situative Priorisierung**, zum Beispiel automatische Grünphasen-Verlängerung bei Schlechtwetter.

---

## Wie funktioniert die Lösung?

Die prädiktive KI-Ampelschaltung arbeitet in vier technologischen Kernschritten:

| Schritt | Phase | Beschreibung |
| :--- | :--- | :--- |
| **1** | **Erkennen von Personen** | LiDAR-Sensoren erfassen den Verkehrsraum als anonymisierte **3D-Punktwolke**. Die KI identifiziert daraus Personen. |
| **2** | **Tracking & Bewegungsanalyse** | Bewegungen werden in Echtzeit analysiert, inklusive Vorhersage von Richtung und Geschwindigkeit. |
| **3** | **Intentionserkennung** | Das System bewertet mathematisch, ob ein Überquerungswunsch wahrscheinlich ist. |
| **4** | **Ampelsteuerung** | Basierend auf der Prognose wird die Schaltung angepasst. Umgebungsbedingungen (z. B. Witterung) fließen direkt ein. |

### Datenschutz und Datensparsamkeit
Ein zentraler Baustein des Projekts ist die datenschutzkonforme Umsetzung nach DSGVO:
* **Keine Videoidentifikation:** Es kommen ausschließlich LiDAR-basierte Punktwolken zum Einsatz.
* **Anonymität ab Sensor:** Es werden keine unmittelbar rückschlussfähigen Personenbilder oder biometrischen Merkmale erzeugt oder gespeichert.
* *Ergänzende Informationen finden Sie auf der Projektseite unter den FAQ (u. a. zu Speicherung, Zugriff und Löschfristen).*

---

## Projektstand und Meilensteine

Das Förderprojekt erstreckt sich über folgende zeitliche Eckpunkte:

* **Mai 2025:** Erste Installation der Sensortechnik vor Ort
* **Okt 2025:** Offizieller Projektstart & Beginn der KI-Lernphase
* **Jul 2026:** Installation weiterer Sensortechnik & Systemerweiterung
* **2026:** Testbetrieb der KI-basierten Ampelsteuerung im Reallabor
* **2027:** Evaluation, datengestützte Optimierung und Feinjustierung
* **Dez 2027:** Projektabschluss und Transferphase

---

## Beteiligte und Kontext

Das Projekt wird im Rahmen von **Smart Green City Konstanz** umgesetzt. Es verbindet Partner aus kommunaler Praxis und Spitzenforschung, maßgeblich mit Beteiligung der **Hochschule Konstanz (HTWG)** im Bereich *Autonome Systeme*.

### Weiterführende Links
* [Projekt-Hauptseite](https://smart-green-city-konstanz.de/KI_Ampelschaltung)
* [Smart Green City Konstanz (Startseite)](https://smart-green-city-konstanz.de/)
* [Übersicht aller Smart-City-Projekte](https://smart-green-city-konstanz.de/projekte)
* [Datenschutzerklärung](https://smart-green-city-konstanz.de/datenschutz)

---

## Projektbeteiligte und Förderung

Das Projekt wird durch Bundesmittel gefördert und gemeinschaftlich umgesetzt.

<table align="center">
  <tr>
    <td align="center" bgcolor="#ffffff" width="260" height="120">
      <img src="https://smart-green-city-konstanz.de/themes/custom/konstanz/assets/Foerderlogo_BMWSB.png" alt="Förderlogo BMWSB" width="220" />
    </td>
    <td align="center" bgcolor="#ffffff" width="260" height="120">
      <img src="https://smart-green-city-konstanz.de/themes/custom/konstanz/assets/KfW_Bankengruppe_20xx_logo.svg.png" alt="KfW Bankengruppe" width="220" />
    </td>
    <td align="center" bgcolor="#ffffff" width="260" height="120">
      <img src="https://smart-green-city-konstanz.de/themes/custom/konstanz/assets/logo-konstanz.jpg" alt="Stadt Konstanz" width="220" />
    </td>
    <td align="center" bgcolor="#ffffff" width="260" height="120">
      <img src="https://www.htwg-konstanz.de/fileadmin/pub/allgemein/Grafiken/logo/logo_ei_pos.svg" alt="Hochschule Konstanz EI" width="220" />
    </td>
  </tr>
</table>

***

> **Hinweis zu diesem Repository:** Diese README dient als kompakte technische und organisatorische Übersicht für die GitHub-Organisation. Für rechtlich verbindliche, tagesaktuelle Inhalte gelten ausschließlich die offiziellen Informationen auf der [Projektseite der Stadt Konstanz](https://smart-green-city-konstanz.de/KI_Ampelschaltung).