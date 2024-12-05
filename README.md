# ASTR 3400 astrophysics coding project 2024

NEED TO DO NEXT:      

Put a *** at the front of the bullet point when you have completed it

- ***make graph of pp and cno chain against radius 
- ***figure out how to copy/download folders in Scorpius and send them to someone else
- *analysis of the graphs using graphs of pp and cno processes
- ***outline refinment and presentation completion
- try and make a graph of the mass against time (Can't be done)
- animation of the graphs
- why are there patterns inbetween elements in the big graph and why do the changes places for more mass accreted onto the star
- *why is there a peak in he3 for certain masses because of the pp chain
- there are also peaks in the cno chain and constituent elements for certain radiuses
- plot graphs again but for radius on the x axis instead of the y axis as this may reveal something that wasn't obvious before
- look at notes for astr3400 to see examples of project and bullet points of what we need in the outline and presentation
- look at the classes in MESA to see what to do next in order to next or to see if there is anything that may be useful in further explaining the data we have
- graph ratios of CNO and PP chain against each other

ANALYSIS
The chemical composition profiles of the accreting star reveal key features of stellar nucleosynthesis and structural evolution under the influence of mass accretion. 
The direct reflection observed between the hydrogen (H1) and helium-4 (He4) mass fractions underscores the efficiency of nuclear fusion processes, where hydrogen is 
systematically converted into helium-4. This symmetry further becomes prominent with increased accreted mass, and it points to the role that accretion plays in enhancing 
core pressure and temperature and thus hastens hydrogen depletion. This He3 abundance peak migrates outward, taking on a somewhat Gaussian profile, reflecting 
accretion-induced thermal redistribution, or the fact that the conditions for optimum He3 production migrate to lower-density, outer layers as the stellar mass increases.

The interplay in the abundances of carbon, C12, nitrogen, N14, and oxygen, O16, reflects the dynamics of the CNO cycle, with the accumulation of nitrogen owing to its
bottleneck function in this reaction chain. Smooth profiles of the CNO process for the lower-mass accretion cases 1M and 1.1M indicate stable core and shell burning. 
In contrast, the appearance of a higher peak for higher accreted masses (1.2M, 1.3M ) indicates the presence of secondary burning zones, probably related to stronger 
shell burning and convective mixing. Oxygen (O16) and magnesium (Mg24) show flat profiles since they are products of deeper burning stages, which do not interfere with 
the hydrogen-burning processes dominating the accreted layers.

NOW NEED
Further plots are needed to properly explain the details of the mechanisms generating these phenomena. Temperature and density profiles will help in 
correlating the He3 peak migration andidentifying the conditions favorable for secondary burning. Energy generation rates (eps_pp, eps_CNO, eps_nuc) will be plotted to 
determine the dominant nucleosynthetic pathways at different mass coordinates. Further, analyzing the convective boundaries and their interaction with chemical composition
gradients shall provide insights into the role of mixing in such profile determination. Finally, the time evolution plots of key abundances will show how accretion changes
with time the nuclear burning rates and the chemical stratification.

AFTER TESTING
may not be convective zones
there is a definite relationship between the cno cycle graphs the n14 and c12 changes.

We think that the reason that there are different amounts of he3 and there is a change in the relationship between n14 and c12 may be caused by the fact that there is a 
switch between the dominancy of the pp chain and the cno chain. Using a graph, which is on the github, it can clearly be shown that the temperature dependence of the of 
pp chain is different to the cno chain so depending on the temperature of the star in certain areas pp may overtake the cno process. Need to plot these graphs AND MAYBE 
ALSO THE PP CHAIN AND CNO CHAIN RATIOS in order to try and explain these anomalies.




### Graph Description

The graph depicts the radial profile of an unspecified quantity, likely the **energy generation rate** or **density**, as a function of the logarithm of radius (in solar radii) for different stellar core masses (\( M_c = 1.0, 1.1, 1.2, 1.3, 1.35 \)). 
The x-axis represents the logarithm of radius, spanning from the core (\( \log(\text{Radius}) \approx 0 \)) outward, while the y-axis (in cgs units) shows the value of the plotted quantity. 
Each curve corresponds to a specific \( M_c \), with the sharp peak near the origin reflecting the central concentration of the quantity, likely in the stellar core.
The height of the peak increases with \( M_c \), indicating stronger activity or higher density in more massive cores. 
The smaller variations further out along the x-axis suggest additional structural features, possibly shell-burning regions, as the radius increases.
Overall, the graph highlights how the radial distribution of this physical quantity depends on core mass, with significant changes occurring as \( M_c \) increases.

---

### Energy Generation in Stars

Energy generation in stars is governed by nuclear fusion, primarily in the stellar core where temperatures and pressures are highest. 
Two main processes drive fusion: the proton-proton (PP) chain, which dominates in lower-mass stars, and the carbon-nitrogen-oxygen (CNO) cycle, which dominates in stars with central temperatures exceeding \( 15 \times 10^6 \) K.
The CNO cycle is highly temperature-sensitive, with energy generation rates scaling roughly as \( T^{15-20} \). 
Given this, the graph likely represents the energy generation rate (in cgs units, such as erg/g/s) for stars dominated by the CNO cycle.

---

### Dependence on Core Mass (\( M_c \))

The parameter \( M_c \), likely representing stellar core
