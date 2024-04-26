# Forest interior species: how long do they exhibit edge avoidance?

**Filtering protocol:**
1. Exclude points that are in harvest polygons (form the ABMI harvest regeneration gdb)
2. Identify locations in the Boreal and Foothills ecoregions
3. Identify the nearest harvest polygon for each site
4. Keep sites where the nearest harvest was logged between 1980 and 2023
5. Keep locations that have recordings
6. Filter out locations not within breeding bird season or during dawn chant
7. Exclude points that have more than 1 harvest edge within 500m
8. Get the proportion of tree species within 150m radius for each point

### Locations that satisfy the sampling protocol:

#### Distance to nearest (and only) harvest, within 250m
![distance to harvest](2.%20Output/interior%20BU%20points%20and%20distance%20nearest%20harvest%20within%20250%20m.png)

#### Age of nearest (and only) harvest, within 250m
![age nearest harvest](2.%20Output/interior%20BU%20points%20and%20time%20since%20harvest%20within%20250%20m.png)
