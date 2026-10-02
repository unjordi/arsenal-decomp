# Audio de ARSENAL V2, organizado IN SITU

> **Orden GENERADO — no editar a mano.** Regenerar: `python3 herramientas/organizar-sonidos.py`
> (es idempotente: si `sbk.py` vuelve a desempaquetar plano, los recoloca).

La FUENTE son los `.sbk` de `../source-audios/`; esto es su desempaquetado, ordenado por categoría. **No hay copias**: cada wav está en un solo lugar.

El nombre es el del banco (ya es semántico y es lo que indexa `docs/tabla-armas.csv`). Quién lo usa va en esta tabla, porque varios lo comparten.

| banco | categoría | wav | lo usa |
|---|---|---|---|
| game | armas | antiair | 3.5in-AntiAir-Gun |
| game | armas | antiair02 | 1in-GA-Mac-Gun |
| game | armas | artill01 | 4in-Artill-Gun, 5in-Artill-Gun, 4in-Navy-Gun |
| game | efectos | atomic | — |
| game | motores | boat1 | Fire Boat, Submarine, Destroyer, PT Boat |
| game | motores | boat2 | Tanker, Transport |
| game | motores | boat3 | Cruiser, Battleship, Carrier |
| game | armas | bombdrop | 25Lb-Bomb, 50Lb-Bomb, Fire-Bomb, Atomic-Bomb |
| game | motores | bomber | Air HvyBombr |
| game | motores | bomber2 | Air Fortress |
| game | motores | bomber3 | Air NavBombr |
| game | motores | bull | Bulldozer |
| game | efectos | divebomb | — |
| game | ambiente | eagle00 | — |
| game | efectos | explo00 | — |
| game | efectos | explo01 | — |
| game | efectos | explo02 | — |
| game | efectos | explo03 | — |
| game | efectos | explo04 | — |
| game | efectos | explo05 | — |
| game | efectos | explo06 | — |
| game | efectos | exploflk | — |
| game | efectos | explotoxic | — |
| game | motores | fighter01 | Air Plane, Air Fighter, Air NavFight, Air TacBombr, Air SupFight, Air Kamikaze |
| game | efectos | fire01 | — |
| game | efectos | fire02 | — |
| game | efectos | firesiren | — |
| game | efectos | flame | — |
| game | motores | gastruck | — |
| game | armas | gun01 | — |
| game | armas | gun02 | 3in-Gun |
| game | armas | gun03 | 1.5in-Gun, 2in-Gun |
| game | armas | gun04 | 3.5in-Gun |
| game | armas | gun05 | 6in-Navy-Gun |
| game | armas | gun06 | 12in-Navy-Gun, 24in-Artill-Gun |
| game | motores | jeep | Jeep, H Bomb, V2, V1, Cart |
| game | motores | jet | Air JetFight |
| game | motores | jetoff | — |
| game | armas | macgun01 | 0.5-GA-Mac-Gun |
| game | armas | macgun02 | 0.5-AG-Mac-Gun |
| game | armas | macgun03 | 0.5-AA-Mac-Gun, 1in-AG-Mac-Gun, 1in-AA-Mac-Gun |
| game | armas | macgun03__2 | — |
| game | vacios | nosound | — |
| game | ambiente | ocean | — |
| game | armas | rocket1 | Rocket-AirGnd, Rocket-AirAir |
| game | armas | rocket2 | Flying-Bomb, Toxic-Missile |
| game | armas | rocket4 | Rocket-GndGnd, Rocket-SeaGnd |
| game | alarmas | scream | — |
| game | alarmas | shiphorn | — |
| game | alarmas | siren2 | — |
| game | alarmas | sonar | — |
| game | alarmas | subalarm | — |
| game | motores | subunder | Sub dived |
| game | motores | takeoff01 | — |
| game | motores | tank1 | Lite Tank, Tank, Rocket Lnchr |
| game | motores | tank2 | Artillery, Medium Tank |
| game | motores | tank3 | Hv Artillery, Heavy Tank |
| game | motores | tank4 | Super Tank, Toxic Lnchr |
| game | motores | tarmac | — |
| game | motores | taxiing01 | Hovercraft, Plane, Fighter, Navy Fighter, Tac Bomber, SuperFighter, Navy Bomber, Heavy Bomber, Fortress, Kamikaze, Jet Fighter |
| game | armas | torpedo | Bow-Torpedo, Aft-Torpedo |
| game | motores | truck | Truck, Gas Truck, Fire Engine, DCA Truck |
| menus | interfaz | blam | — |
| menus | interfaz | blup03 | — |
| menus | interfaz | blup05 | — |
| menus | interfaz | blup08 | — |
| menus | interfaz | blup10 | — |
| menus | interfaz | blup12 | — |
| menus | interfaz | catapult | — |
| menus | interfaz | clic1 | — |
| menus | interfaz | clic2 | — |
| menus | interfaz | clic3 | — |
| menus | interfaz | eisenhower | — |
| menus | efectos | explo11 | — |
| menus | efectos | explo12 | — |
| menus | efectos | fff | — |
| menus | interfaz | london | — |
| menus | interfaz | morse | — |
| menus | vacios | no sound | — |
| menus | vacios | no sound__2 | — |
| menus | vacios | no sound__3 | — |
| menus | vacios | no sound__4 | — |
| menus | vacios | no sound__5 | — |
| menus | vacios | no sound__6 | — |
| menus | vacios | no sound__7 | — |
| menus | vacios | no sound__8 | — |
| menus | interfaz | paris | — |
| menus | efectos | pff01 | — |
| menus | efectos | pff02 | — |
| menus | interfaz | piup | — |
| menus | motores | tuning | — |
| menus | interfaz | typewriter | — |
| sound01 | interfaz | camera | — |
| sound01 | ambiente | crowdcheer | — |
| sound01 | ambiente | crowdmad | — |
| sound01 | ambiente | crowdooo | — |
| sound01 | interfaz | morse | — |
| sound01 | efectos | pneu02 | — |

## El mismo clip en varios bancos (duplicación del JUEGO, no del repo)

El original empaqueta estos clips en más de un `.sbk`. Se conservan ambos: son el desempaquetado fiel.

| wav | bancos | ¿contenido idéntico? | cómo quedan |
|---|---|---|---|
| morse | menus, sound01 | sí | se guardan como `morse--<banco>.wav` |
