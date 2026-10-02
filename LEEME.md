# arsenal-decomp (PRIVADO)

Contenido del juego original ARSENAL (Eric Mathiauth / Tacticalsoft) y su decompilado. **Nunca se hace público** (LFDA art. 106 fr. IV y V;
ver `.claude/skills/escena-decomp-recomp/06-aplicacion-arsenal.md` y `legal/` en el repo principal `arsenal_powerRebuilt`). Se monta como
submódulo en `recursos/`: `git submodule update --init`.

- `V1/`, `V2/` — archivos extraídos y catalogados de cada versión.
- `arsenal1_full_decomp.c`, `arsenal2_game_decomp.c` — decompilado vanilla (Ghidra); `arsenal1_full.c`, `arsenal2_game.c` — anotado,
  GENERADO por `herramientas/decomp-annotate.py` del repo principal (no editar a mano).

Fuera de este repo (Google Drive, `$JUEGOS/ARSENAL/_taller/`): `referencias/` (videos de gameplay) y `otras-versiones/` (variantes
únicas de V2h y versiones anteriores + `equivalencias.csv`).

## Sprites (V2)
Los sprites decodificados viven ORGANIZADOS en `V2/graficos/sprites-organizados/` (por categoría del propio juego:
unidades-tierra/mar/aire/carga, defensas, edificios, efectos; lo no identificado en `sin-identificar/<banco>/<bloque>/`,
cada carpeta con su `_hoja.png` de contactos). Lo genera `herramientas/organizar-sprites.py` del repo padre.
El árbol plano numerado `V2/graficos/png/sprites/` se retiró (2026-10-02): eran 5847 PNG sin nombre, imposibles de navegar;
se regenera cuando haga falta con `herramientas/sprites.py V2/graficos/sprites/sprites.rgb <destino>`.
