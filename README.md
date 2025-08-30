# FS25_extendedFunctions

aktuelle Version: **1.6.1**

Direkter Download: [FS25_extendedFunctions](https://github.com/inconspicuously007/FS25_extendedFunctions/releases/latest/download/FS25_extendedFunctions.zip)

**Wesentliche Funktionen des Mods**

* erweiterte Informationen in den Infos von Produktionen, Tierställen inkl. Futterroboter, Feldern, Silos, Mistlagern und Fahrzeugen
* Füllstände in Produktionen und Ställen werden farblich hinterlegt
* in Ställen wird der mögliche Lagerstand von Futtermitteln gemäß des Mischverhältnisses begrenzt (bei Tieren mit paralleler Fütterung: Schweine, Pferde) und das Überbefüllen ausgeschlossen
* in Produktionen wird der Modus der Ausgangsprodukte angepasst auf: Einlagern, Auslagern, Verteilen und Direktverkauf
* der Modus kann für alle Ausgangsprodukte gesammelt oder getrennt eingestellt werden
* Paletten in Produktionen können manuell mit Angabe der Anzahl ausgelagert werden, abhängig von der Definition des Palettenspawners
* in gefüllten Silos wird der Dialog angepasst, so dass nur noch die eingelagerten Filltypen beim Auslagern zur Auswahl stehen
* Öffnungszeiten können über die xml einer Produktion oder bequem im Spiel eingestellt und angepasst werden
* angepasste Verteilung zwischen den Produktionen
  * nur Produktionen mit aktiven Linien werden berücksichtigt
  * Lagerstände der empfangenden Produktionen werden berücksichtigt, Sortierung erfolgt nach freiem Platz aufsteigend
  * Validierung und ggf. Neuberechnung der zu verteilenden Menge nach jedem Verteilschritt   

durch den Mod werden folgende Limits anpassbar gemacht:
  * Produktionspunkte (60 - 9999)
  * Tierställe (15 - 64)
  * Paletten (300 - 9999)
  * Ballen (300 - 9999)
  * Filltypen (512)
 
Anpassungen können in der xml im Ordner ModSettings im Unterordner des Mods vorgenommen werden. Hierbei werden die Limits für Ballen und Paletten über die Einstellung objectLimit eingestellt.
