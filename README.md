# Ontologie einer Rechnerarchitektur
## Grundgedanke
Diese Ontologie soll eine praktische, wiederverwendbare und erweiterbare Abbildung einer Rechnerarchitektur sein. 
Grundlegend unterteilt sich dabei ein Rechner (hier gleichzusetzen mit Computer) in viele einzelne Computer-Teile, die stets als „Teil“, veranschaulichend für eine Sache und gleichzeitig Untergruppe des komplexen Systems, benannt sind.
## Grundlegender Aufbau
Da jede Untergruppe des Computers ein Teil des Computers ist, entspringen die sekundären Gruppen „Hardware-Teil“, „Software-Teil“ und „Peripherie-Teil“ der primären Übergruppe „Computer-Teil“.

**Beispiel eines Voll-Addierers (VA) in der Rechnerarchitektur (inkl. Abhängigkeiten und Parentklassen:**
![image](https://github.com/user-attachments/assets/9ab00ee7-ff40-49b7-9236-4ea93e2a0176)


## Nutzen
Mit grafischer Oberfläche: Auf Website webprotege.stanford.edu gehen und Schritte in der file "owl_webprotege_link.txt" folgen.

Als OWL-file: Datei "urn_webprotege_ontology_96477fc3-2e59-4b1d-b1fb-b5b0680971c2.owl" öffnen (z.B. in VS Code)

## Inhalt
### Hardware-Teil
In der Hardware werden die einzelnen Komponenten eines Computers behandelt. 
### Software-Teil
Die Software gliedert sich in Anwendungssoftware und Systemsoftware auf. Hierauf lassen sich viele der Data-Properties anwenden.
### Peripherie-Teil
Die Peripherie ist nach Eingabe-, Ausgabe- und Hybrid-Teil gebündelt, die über die Richtung des Datenflusses Auskunft geben.
## Individuals
Als Individuen wurde folgendes Szenario nachgestellt:
Für einen Endverbraucher-PC wurden alle benötigten Hardware-Komponenten, Software-Programme und Peripherie-Geräte verwendet.

**Individuen im Szenario:**

![image](https://github.com/user-attachments/assets/f28bab63-b2d7-46e7-a981-92d2b9d2e9bc)


**Beispielhaftes Individuum des 3D-Druckers:**

![image](https://github.com/user-attachments/assets/cfeff9f7-3dab-402a-a251-d5daaa603c2e)


## Properties
Neben dem Object-Property „benötigt-Teil“ für Subsumptionen beinhaltet die Ontologie auch weitere Data-Properties mit Eigenschaften für die wichtigsten Klassen.

## Weiterführung 
Das Projekt ist dafür aufgebaut, weiter von außen erweiterbar zu sein.

Die Klassen Ontologie_Besitzer, Ontologie_Ortsabhängigkeit, Ontologie_Aktivität und Ontologie_Zeitanhängigkeit sind vom DFKI Ubisworld inspiriert, haben jedoch noch keine Anwendung gefunden.

Verwendete Quellen sind in der Ontologie selbst im "rdfs:seealso" vorhanden. Inhalte (wie "rdfs:description") können teils KI-generiert sein.
Dieses Projekt entstand für ein Projekt während des Studiums. Keine Garantie für Richtigkeit oder Vollständigkeit.
