# godot-project-box-physics-game

Ein Godot-4.1-Projekt, das ich beim Nachbauen eines Tutorials angelegt habe. In der `project.godot` heißt es noch "2d Survivors Style Game Tutorial", weiter als bis zum Physik-Setup bin ich aber nicht gekommen.

## Was drin ist

- `level.tscn`: die Hauptszene, ein Spieler mit Kamera und zwei Blöcken.
- `player.tscn`: ein `RigidBody2D` aus Körper-Sprite, Gesicht und Kollisionsform. Das zugehörige `player.gd` ist leer, es gibt also keine Steuerung.
- `block.tscn`: ein `StaticBody2D` mit Kachel-Textur, das zum Drauffallen.
- `assets/`: ein Satz Grafiken mit Körpern, Händen, Gesichtern und Gesichtsteilen in mehreren Farben.

## Stand

Wegwerf-Projekt zum Ausprobieren. Man kann es in Godot 4.1 öffnen und starten, dann fällt ein Würfel mit Gesicht auf ein paar Blöcke. Mehr passiert nicht.
