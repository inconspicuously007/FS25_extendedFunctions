# FS25_extendedFunctions

aktuelle Version / latest version: **1.6.1**

Direkter Download / direct download: [FS25_extendedFunctions](https://github.com/inconspicuously007/FS25_extendedFunctions/releases/latest/download/FS25_extendedFunctions.zip)

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

english Version

**Key features of this mod**

* extended information in the info panels for production points, animal pens (including feeding robots), fields, storages, manure heap and vehicles
* productions and pens get colored fill level displays
* the possible storage capacity of feed is limited according to the mixing ratio (only for animals with the behavior of parallel feeding, e.g. pigs, horses) to prevent overfilling and always have the correct ratio
* production points get adjusted output modes: store, spawn pallets, distribute and direct sell
* these modes can be set for all output products overall or individual
* products that will spawn as pallets, depending on the pallet spawner definition, can be manually dispatched by specifing the quantity
* opening times at production points can be set and adjusted in their xml file or conveniently in game
* distribution of products between production points adjusted and based on individual requirement
  * only production points with active production lines are considered
  * storage levels of receiving production points are taken into account; sorting is done by available space in ascending order
  * validation and, if necessary, recalculation of the quantity to distribute after each step / receiving production point

the following limits are adjustable through this mod:
  * production points (60 - 9999)
  * animal pens (15 - 64)
  * pallets (300 - 9999)
  * bales (300 - 9999)
  * fill types (512)

These adjustments, except the filltype limitation, are made by changing the values in the xml file located in the modSettings folder within the subfolder for the mod. The limits for pallets and bales are set by using the objectLimit attribute.
