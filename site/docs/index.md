# SPARSE | Soil Plant Atmosphere Remote Sensing Evapotranspiration

SPARSE <a href="#article">(Boulet et al., 2015)</a> is a two source energy budget model meant to estimate turbulent fluxes at the land surface. 
By considering both the soil and vegetation, the dual-source algorithm disaggregates evapotranspiration into its separate components, i.e., 
evaporation and transpiration. The model is free to use and can be downloaded from <a href="http://tully.ups-tlse.fr/gilles.boulet/sparse" 
target="_blank">the SPARSE repository</a>.

## Requirements

### Tools
Matlab&copy; is needed to run SPARSE. A python-translated version is also available and will be added to the <a href=
"http://tully.ups-tlse.fr/gilles.boulet/sparse" target="_blank">repository</a> in due course.
### Data
* Meteorological data required include: incoming solar radiation, relative humidity, wind speed, air and surface temperature.
* Surface characteristics: Biophysical parameters (Leaf Area Index, vegetation height, minimum stomatal resistance, ..., a random LIDF is assumed),
 surface and vegetation albedo, soil and vegetation emissivity

## <div id="article">Main reference</div>

Boulet, G., Mougenot, B., Lhomme, J. P., Fanise, P., Lili-Chabaane, Z., Olioso, A., … Lagouarde, J. P. (2015). The SPARSE model for the prediction
 of water stress and evapotranspiration components from thermal infra-red data and its evaluation over irrigated and rainfed wheat. Hydrology and 
 Earth System Sciences, 19(11), 4653–4672. <a target="_blank" href="https://hess.copernicus.org/articles/19/4653/2015/hess-19-4653-2015.pdf">
 https://doi.org/10.5194/hess-19-4653-2015</a>

## Licence
* Respect the basic principles of the <a target="_blank" href="https://www.gnu.org/licenses/gpl-3.0-standalone.html">GNU GPL v3 licence</a>.
* Contact the author if bugs are found : <a target="_blank" href="mailto:gilles.boulet@ird.fr"> Gilles Boulet</a>

<!-- 
## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.


	tab
	tab again
	   
-->	