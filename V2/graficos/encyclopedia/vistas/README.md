# Vistas ortográficas de las láminas de la enciclopedia

> **Árbol GENERADO — no editar a mano.** La fuente son las láminas de `../` (`<id>_<nombre>.png`).
> Regenerar: `python3 herramientas/encyclopedia-vistas.py recursos/V2/graficos/encyclopedia --csv docs/encyclopedia-vistas.csv`

Una carpeta por lámina de unidad (39; las de botones y los 3 charts no tienen vistas). Cada vista es un
recorte PNG RGBA nombrado por su rol: `lateral`, `frontal`, `planta`, `tres-cuartos`; cuando la lámina no
trae el trío ortográfico completo (27 de 39), la más ancha sale como `lateral?` y el resto como
`sin-rol-<i>`. Coordenadas de cada recorte en `docs/encyclopedia-vistas.csv` (150 vistas).

`00230_bulldozer/malla.obj` es la malla del visual hull de `herramientas/lamina-a-malla.py` (primer
resultado del pipeline 3D, NO fiel: ver `estado-proyecto.md` §"3D desde las láminas").
