# Reconstrucción técnica del alcance de Urda (LAV Madrid–Sevilla, PK 118,7)

Accidente ferroviario del 28 de octubre de 2026: un AVE de Renfe (2080) alcanzó por detrás a un Iryo (6076) detenido cerca de Urda (Toledo), con la protección LZB caída. En recuerdo de las víctimas.

Este repositorio reúne un análisis hecho **solo con información y datos públicos**: qué podía ver el maquinista desde la cabina, cuánto necesitaba para parar y qué indican el terreno, el sol y el satélite.

**Visor interactivo:** https://engimine.github.io/reconstruccion-urda-pk118/

## Contenido

| | |
|---|---|
| `index.html` | Visor interactivo con servicios en vivo (IGN PNOA y MDT, Catastro, OpenRailwayMap, OpenStreetMap, Open-Meteo, posición solar) y simulación de la marcha |
| `urda3d.html` | Visor 3D y análisis cinemático |
| `laminas/` | Láminas A3: L-01 situación, L-02 planta de detalle y marcha, L-03 hipótesis, sol e indicios, L-04 visibilidad con arbolado (PDF y PNG) |
| `img/` | Figuras de topografía, visibilidad y Sentinel-2 |
| `docs/INVESTIGACION.md` | Hechos, fuentes y datos que no coinciden entre fuentes |
| `datos/` | Eje de la vía con PK y resultados de visibilidad (JSON) |

## Resultados principales

- Contando solo el terreno (MDT05), la cola del Iryo era visible desde unos **1.810 m**.
- Con la altura del arbolado a 1 m, la visión continua empieza a unos **1.630 m** (árboles de 9–11 m en el interior de la curva, a ~700 m de la cabina).
- A 200 km/h, con 2,5 s de reacción y 1,0 m/s² de frenada, la parada exige unos **1.680 m**: con esa visibilidad solo se detiene un tren por debajo de unos 197 km/h.

## Límites

Es una reconstrucción con hipótesis editables. **No atribuye responsabilidades** ni sustituye a la investigación de la CIAF, a la judicial ni a un dictamen con registradores jurídicos, registros LZB y la planta oficial de Adif. El punto del alcance tiene un margen de ±150–200 m; las cotas del MDT05 vienen en metros enteros; la altura de copas tiene un error de 2–3 m.

## Fuentes de datos

IGN-CNIG (MDT05, PNOA; CC BY 4.0) · OpenStreetMap y OpenRailwayMap (ODbL) · Copernicus Sentinel-2 (ESA) · Meta & WRI, Global Canopy Height 1 m (Tolan et al., 2024) · Open-Meteo · Dirección General del Catastro · notas de la AITAT y prensa citada en `docs/INVESTIGACION.md`.

## Autora

**María Jesús Puerta Angulo** · Ingeniera de Minas (Col. NE-347C) · [mariajesuspuertaangulo.com](https://www.mariajesuspuertaangulo.com)

Textos, láminas y figuras © María Jesús Puerta Angulo. Los datos de terceros conservan sus licencias.
