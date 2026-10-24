# ZombieHunterGo

GPS-Zombiespiel für den Handy-Browser. Lootorte erscheinen in deiner echten Umgebung, beim Laufen passieren Events, und Gebäude plünderst du in einer begehbaren Comic-Seitenansicht.

## Spielen

- Über GitHub Pages öffnen (Settings → Pages → Branch `main`, Ordner `/root`). GPS funktioniert nur über HTTPS.
- „Demo ohne GPS“: auf die Karte tippen, um zu laufen.

## Spielprinzip

- **Lootorte** mit drei Risikostufen: mehr Risiko = mehr Etagen, bessere Beute, härtere Zombies, schneller zu laut.
- **Gebäude & Straßen** als 2D-Seitenansicht mit 5 Parallax-Ebenen (Außenwelt, Wand, Möbel, Action, unscharfer Vordergrund), Licht und Dunkelheit, prozedural pro Ort.
- **Steuerung**: virtueller Joystick (halb gedrückt = schleichen, hoch/runter im Aufzug), Buttons für linke und rechte Hand (beidhändige Waffen verschmelzen zu einem Button), Inventar oben rechts. Am PC: A/D, J/K, W/S, E, I.
- **Kampf direkt in der Szene**: Pistole, Messer (lautlose Kills an schlafenden Zombies), Taschenlampe, Granaten, Nagelschläger und Schrotflinte (beidhändig). Lärm lockt eine Horde an. Beute gibt es nur, wenn du lebend durch den Eingang rauskommst.
- **Überlebende** in manchen Gebäuden: ansprechen, tauschen, Tipps bekommen.
- **Hoch- und Querformat**: quer gehalten siehst du mehr vom Gebäude.
- **Events unterwegs** (alle 80–200 m): Verstecke, Überfälle, Händler, Autos, Fallen.
- **Werkbank**: Schrott und Teile zu Patronen, Granaten und Verbänden verarbeiten.

Der Spielstand wird im Browser gespeichert. Alles steckt in einer einzigen `index.html`.
