# Mapping premodern small war: The case of the Thirty Years War (1618-48) - Online appendix

<ins>Abstract:</ins> The example of the Thirty Years War (1618–48) demonstrates that small war was already integral to the conduct of premodern hostilities. Commanders employed these methods with a purpose and generally tried to limit the accompanying violence to preserve discipline and effectiveness, as well as their claims to be waging a just war. We explain why conventional histories have neglected the presence of small war in premodernity, and show how its importance, methods, and wider impact can be reconstructed through innovative digital mapping techniques, which have the potential to be applied to conflicts in other times and places.

<ins>Cite:</ins> Peter H. Wilson, Katerina Tkacova & Thomas Pert (2023) Mapping premodern small war: The case of the Thirty Years War (1618-48), Small Wars & Insurgencies, DOI: [10.1080/09592318.2023.2220503](https://doi.org/10.1080/09592318.2023.2220503)

## Data
Historical roads, rivers and settlements data come from Holterman et al., [‘Viabundus Map of Premodern European Transport and Mobility’](http://www.landesgeschichte.uni-goettingen.de/handelsstrassen/index.php). We obtained the information on garrisons from Salm, Armeefinanzierung, as well as archival data. Both data sources are used to create Figures 2, 3 and 4.

Data on garrisons is available upon request.

## Spatial network analysis
Our approach to calculating the garrisons' reach uses information on the location of garrisons, historical roads and rivers and slope maps to carry out spatial network analysis. We consider that a mounted soldier could ride approximately 50 km roundtrip a day, so we identify locations in a 25 km radius (1-way). We add adjustments for the effect of the slope of the roads on the travelled distance, as well as rivers and other topographical features. A steeper slope decreases the speed of travelling horsemen and thus shortens the distance they can travel within a day (see a similar approach in Tao et al., 'A Hybrid Approach to Modelling Territorial Control in Violent Armed Conflicts'). To obtain the distance deduction caused by slope, we calculated the average slope (in degrees) for each road and assigned weights to the travelled distance, loosely based on Tobler's model, as follows:

* slope <= 1, weight = 1
* 1 < slope <= 3, weight = 0.9
* 3 < slope <= 5, weight = 0.8
* 5 < slope <= 10, weight = 0.6
* slope > 10, weight = 0.5

We used UTM 32N equidistant projection for mapping and spatial network analysis.

## Bibiliography
Holterman, Bart. ed. Viabundus Pre-Modern Street Map 1.2 (Released 21-9-2022). https://www.viabundus.eu

Salm, Hubert. Armeefinanzierung im Dreißigjährigen Krieg. Der Niederrheinisch-Westfälischen Reichskreis 1635-1650. Münster: Aschendorff, 1990.

Tao, Ran, Daniel Strandow, Michael Findley, Jean-Claude Thill, and James Walsh. “A Hybrid Approach to Modelling Territorial Control in Violent Armed Conflicts.” Transactions in GIS 20, no. 3 (June 2016): 413–425. doi:10.1111/tgis.12228.

Tobler, Waldo. “Three Presentations on Geographical Analysis and Modeling.“ National Center for Geographic Information and Analysis, no. 93 (1993): 1–25.
