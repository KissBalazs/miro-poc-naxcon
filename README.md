# MIRO Serious Game Webapp – 2.5D Isometrischer Apfelplantage-Prototyp (PoC)

> **Forschungsprojekt MIRO** (*Mitteldeutsche Innovationsregion Obstbau*)  
> **Auftraggeber:** Fraunhofer-Institut für System- und Innovationsforschung ISI (Leipzig / Karlsruhe)  
> **Ausschreibungsreferenz:** PR1286183-9940  
> **Bieter:** NAXCON GmbH (Generalunternehmer, Deutschland) mit Senior Engineering Kernteam (Malik, Módly, Kiss)  
> **Live-Demo:** [https://kissbalazs.github.io/miro-poc-naxcon/](https://kissbalazs.github.io/miro-poc-naxcon/)

---

## 🎯 Zweck des Prototyps (Proof of Concept)

Dieser leichtgewichtige, browserbasierte Demonstrator weist die **technische Machbarkeit der geforderten 2.5D-Isometrie** und einer immersiven Vegetations- und Windsimulation gemäß **Anlage 2 (Leistungsbeschreibung, AP 2 & AP 3)** vorab nach:

1. **Plattformunabhängige WebGL-Grafik**:
   - Realisiert mit **Pixi.js v7** für maximale Performance bei konstanten **60 FPS** selbst auf mobilen Endgeräten und Kiosk-Systemen.
   - Kein schwerfälliges 3D-Framework, vollständige Scale-to-Zero- und ressourcenschonende Bereitstellung.
2. **Harmonische Wind- und Vegetationsdynamik**:
   - Räumlich fortschreitende Wellenfront (Phasenverzögerung entlang der Baumreihen).
   - Physikalisch nachempfundene Biegung des Stammes (`skew` & `rotation` an der Stammbasis) sowie elastische Sekundärbewegung der Baumkrone.
   - Mikrobewegungen der Äpfel und schwebende Blattpartikel im Wind.
3. **Interaktivität & Inspektion**:
   - Parametrisierbare Windstärken (*Sanfte Brise*, *Frischer Wind*, *Stürmisch*).
   - Interaktive Bauminspektion (Ertragsphase, Reifegrad, Rüttel- und Apfelfall-Animation).
   - Vorbereitung für die Anbindung an die MIRO-Szenario-Karten und Telemetrieparameter (Wasser, Technologie, Wirtschaft).

---

## 🚀 Lokale Ausführung

Die Datei `index.html` ist vollständig eigenständig und kann direkt im Browser geöffnet werden (offlinefähig dank lokal mitgeliefertem `pixi.min.js` sowie CDN-Fallback).
