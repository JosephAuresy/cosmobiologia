# El cosmos que habitamos · Invesciencias

Página web del artículo científico **"El cosmos que habitamos: cosmobiología, grandes bases de datos y una propuesta de investigación abierta a todas las ciencias"** — David Serrano, Fundación Invesciencias. Publicado en la Circular Astronómica de la Red de Astronomía de Colombia (RAC), 2026.

## Contenido de la página

* **Fundamento físico verificado** — mareas terrestres sólidas, sismicidad lunar, actividad solar y atmosférica
* **Cosmos y biología humana** — criptocromos, campo geomagnético como zeitgeber, efectos cardiovasculares
* **Metodología estadística interactiva** — tres capas de análisis con fórmulas y demo de Fourier en tiempo real
* **Conexiones con grandes bases de datos** — USGS, NASA HORIZONS, IDEAM, SGC Colombia, NOAA, Lichess
* **Referencias completas** con DOI verificado

## Cómo ver la página

### Localmente

```bash
git clone https://github.com/TU-USUARIO/cosmobiologia-invesciencias.git
cd cosmobiologia-invesciencias
# Abrir index.html en cualquier navegador moderno
open index.html
```

### GitHub Pages (recomendado)

1. Sube el repositorio a GitHub
2. Ve a **Settings → Pages**
3. En **Source**, selecciona `main` branch y carpeta `/ (root)`
4. Guarda — en 1-2 minutos la página estará en `https://TU-USUARIO.github.io/cosmobiologia-invesciencias`

## Bases de datos utilizadas / referenciadas

|Base de datos|Organismo|Acceso|URL|
|-|-|-|-|
|Earthquake Catalog|USGS|Abierto + API REST|earthquake.usgs.gov|
|HORIZONS Ephemerides|NASA JPL|API gratuita|ssd.jpl.nasa.gov/horizons|
|Series hidrológicas|IDEAM Colombia|Abierto|dhime.ideam.gov.co|
|Catálogo sísmico|SGC Colombia|Abierto|sgc.gov.co|
|Índice geomagnético Kp|NOAA|API gratuita|swpc.noaa.gov|
|Partidas de ajedrez|Lichess|Abierto (CC0)|database.lichess.org|

## Referencias principales

* Tanaka, Ohtake \& Sato (2002) — *Journal of Geophysical Research* — [doi](https://doi.org/10.1029/2001JB001577)
* Métivier et al. (2009) — *Earth and Planetary Science Letters* — [doi](https://doi.org/10.1016/j.epsl.2008.12.020)
* Zürcher et al. (1998) — *Nature*, 392, 665–666
* Zürcher (1999) — *Earth, Moon, and Planets* — [doi](https://doi.org/10.1023/A:1017018821490)
* Xue et al. (2021) — *Frontiers in Physiology* — [doi](https://doi.org/10.3389/fphys.2021.643943)
* Raposio et al. (2017) — *Acta Chirurgica Belgica* — [doi](https://doi.org/10.1080/00015458.2017.1310480)
* Joswig et al. (2016) — *Acta Neurochirurgica* — [doi](https://doi.org/10.1007/s00701-016-2802-8)
* Hung (2007) — NASA/TM-2007-214813
* Ferriz Olivares (1976) — *Teoría Científica de la Cosmobiología* — Fundación Invesciencias / U. Nacional de Trujillo

## Tecnología

* HTML5 + CSS3 + JavaScript vanilla — sin dependencias de servidor
* [Chart.js 4.4](https://chartjs.org) para las visualizaciones
* Google Fonts: Cormorant Garamond + DM Mono + Outfit
* Compatible con cualquier navegador moderno

## Licencia

Contenido científico © Fundación Invesciencias 2026. Código de la página: MIT.

