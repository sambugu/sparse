<script type="text/javascript" id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
</script>
<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
# SPARSE | Theory

SPARSE partitions the available energy (Æ) into surface fluxes by analogously treating the soil-vegetation continuum as either 'series' 
or 'parallel', a rationale that is similar to <a title="Two Source Energy Balance model" target="_blank" href="https://doi.org/10.1016/0168-1923(95)02265-Y">TSEB</a>. The execution sequence is generally the same for both modes. However, only theoretical aspects of the 'series' mode are 
presented here (for description of the 'parallel' mode, please see <a target="_blank" href="https://doi.org/10.5194/hess-19-4653-2015">
Boulet et al. (2015)</a>)

## <div id="RadiativeB">Radiative balance ¦ net radiation</div>

#### Radiation partitioning
In dual-source models such as SPARSE, incoming radiation is paritioned between the soil and the vegetation for the net radiation terms: <br>

<p align="center">(RG<sub>s</sub> + RA<sub>s</sub> + &epsilon;<sub>TIRs</sub>)(1 - &xi;) = Rn<sub>s</sub>(1 - &xi;) = Æ<sub>s</sub> --soil</p>	
<p align="center">RG<sub>v</sub> + RA<sub>v</sub> + &epsilon;<sub>TIRv</sub> = Rn<sub>v</sub> = Æ<sub>v</sub>				--vegetation</p>
where RG<sub>s|v</sub> and RA<sub>s|v</sub> are the incoming short- and long-wave radiation for the soil (<sub>s</sub>) and vegetation 
(<sub>v</sub>), respectively. &epsilon;<sub>TIRs|v</sub> are the component thermal emissions. &xi; is the fraction of soil net radiation 
(Rn<sub>s</sub>) that is stored in the soil (G:&nbsp;ground heat flux)
 
#### Out-of-canopy radiation 
The link of component temperatures (soil - T<sub>s</sub> and vegetation - T<sub>v</sub>) to the thermal radiation (L<sub>out</sub>) observed in 
direction &theta;<sub>vza</sub> is:

<p align="center">L<sub>out</sub>(&theta;<sub>vza</sub>) = &epsilon;<sub>s</sub>b(&theta;<sub>vza</sub>)<strong>B</strong>(T<sub>s</sub>) 
+ &epsilon;<sub>v</sub>(1 - b(&theta;<sub>vza</sub>))<strong>B</strong>(T<sub>v</sub>) + (&epsilon;<sub>surf</sub>)L<sub>in</sub></p>

where 
## <div id="EnergyB">Energy balance</div>

The available energy (Æ) is then partitioned into turbulent heat fluxes as:

<p align="center">Æ<sub>s</sub> = &lambda;E<sub>s</sub> + H<sub>s</sub>		--soil</p>	
<p align="center">Æ<sub>v</sub> = &lambda;E<sub>v</sub> + H<sub>v</sub>		--vegetation</p>

Unlike TSEB, which uses a Priestley Taylor formulation to estimate the latent heat, SPARSE uses a Penmann Monteith approximation:
$$&lambda;E_s = {&rho;C_p \over &gamma;}&beta;_s{{{e_s}_a}_t(T_s)-e_0 \over {r_a}_s}$$
$$&lambda;E_v = {&rho;C_p \over &gamma;}&beta;_v{{{e_s}_a}_t(T_v)-e_0 \over {r_v}_v}$$

the component sensible heat fluxes are written as:
$$H_s = {&rho;C_p}{T_s-T_0 \over {r_a}_s}$$
$$H_v = {&rho;C_p}{T_v-T_0 \over {r_a}_v}$$
The temperature and partial vapor pressure at the aerodynamic level (T<sub>0</sub> and e<sub>0</sub>, respectively) can be derived from the 
aggregated (total) fluxes:
$$&lambda;E_s+&lambda;E_v=&lambda;E={&rho;C_p \over &gamma;}{e_0-e_a \over r_a}$$
$$H_s+H_v=H=&rho;C_p{T_0-T_a \over r_a}$$
## <div id="article">References</div>

Boulet, G., Mougenot, B., Lhomme, J. P., Fanise, P., Lili-Chabaane, Z., Olioso, A., … Lagouarde, J. P. (2015). The SPARSE model for the prediction
 of water stress and evapotranspiration components from thermal infra-red data and its evaluation over irrigated and rainfed wheat. Hydrology and 
 Earth System Sciences, 19(11), 4653–4672. <a target="_blank" href="https://hess.copernicus.org/articles/19/4653/2015/hess-19-4653-2015.pdf">
 https://doi.org/10.5194/hess-19-4653-2015</a>
<br><br>
Norman, J. M., Kustas, W. P., & Humes, K. S. (1995). Source approach for estimating soil and vegetation energy fluxes in observations of directional
 radiometric surface temperature. Agricultural and Forest Meteorology, 77(3–4), 263–293. 
 <a target="_blank" href="https://doi.org/10.1016/0168-1923(95)02265-Y">https://doi.org/10.1016/0168-1923(95)02265-Y</a>

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
-->
<!--
	tab
	tab again
	   
<math xmlns="http://www.w3.org/1998/Math/MathML">Æ<sub>v</sub> = &lambda;E<sub>v</sub> + H<sub>v</sub>		--vegetation</math>
$$&lambda;E_s = {&rho;C_p \over &gamma;}&beta;_s{{{e_s}_a}_t(T_s)-e_0 \over {r_a}_s}\text{	--soil}$$
$$&lambda;E_v = {&rho;C_p \over &gamma;}&beta;_v{{{e_s}_a}_t(T_v)-e_0 \over {r_v}_v}\text{	--veg.}$$
When \(a &ne; 0\), there are two solutions to \(ax^2 + bx + c = 0\) and they are
$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}\text{	asdfa}$$
-->	