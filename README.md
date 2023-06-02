# Raw_Material_Selectivity
## Title: Investigating Early Human Ancestors' Cognitive Abilities Through Raw Material Selection for Stone Tools

**Project Description:** Modern humans possess remarkable cognitive abilities that enable us to create a wide range of complex tools, from stone implements to advanced AI software. However, determining the timeline of the emergence of more sophisticated cognitive capacities in early humans is difficult.

Studying the raw material selection for stone tool creation provides valuable insights into the cognitive abilities of early hominins, our human ancestors. Many early hominin sites exhibit a consistent pattern of selecting specific rock types for stone tools, suggesting a cognitive grasp of the mechanical properties inherent in the stones. 

This project analyzes the frequency of rock selectivity by comparing artifact quantities to rock availability at each early hominin site, enhancing our understanding of early human cognition and shedding light on the development of complex cognitive abilities in our ancestors.

## Data

The data for this project was compiled from multiple peer-reviewed research publications and transformed into a cohesive dataset. 

The dataset includes, site name, raw material names, artifact raw material totals, local raw material totals, artifact raw material site frequency, and raw material local frequency. 

For artifact raw material totals and local raw material totals for sites AL894 and AL-666 were extrapolated from Goldman-Neuman and Hovers (2012), calculating the totals from the reported frequencies and sample totals in Google Sheets (see Figure 1 for formula). 

The artifcat raw material totals and local raw material totals for sites OGS-7,	OGS-6a,	EG-13, DAN-1, DAS-7,	and DAN-2d were extrapolated from Stout et al. (2005), calculating the totals from the reported frequencies and sample totals in Google Sheets (see Figure 1 for formula). 

**Note: Artifact raw material totals and local raw material totals are not need for selectivity analysis but were generated for a larger project, but are included in the dataset.  

![stonetoolproject](https://github.com/ktuosto/Raw_Material_Selectivity/assets/49923281/c1f1a9c2-2a3f-4a90-abd0-cbe281bf1de0)
*Figure 1: Formula (frequency * sample total) used to calculate artifact raw material totals and local raw material totals.*

Kanjera South's (Kenjera in dataset) raw material totals and local raw material totals were from Braun et al. (2008), and artifact raw material site frequency and raw material local frequency was calculated in Google Sheets (see Figure 2 for formula). 

LA2C site data is from a presentation by Tuosto et al. (2017). 

![stonetoolproject2](https://github.com/ktuosto/Raw_Material_Selectivity/assets/49923281/3eabad40-8934-48fe-b874-8f5bc761abf0)
*Figure 2: Formula (artifact total / sample total) used to calculate artifact raw material frequencies and local raw material frequencies.*

For this project only artifact raw material frequencies and local raw material frequencies are needed to calculation raw material selectivity.

## Code

Calculating initial sample totals and frequencies was done in Google Sheets (see Figure 1), the selectivity analysis and data visualization was done in R, and the dashboard creation was done in R Shiny. 

The code provided here is for the selectivity analysis, data visualization, and the dashboard creation. 

## Results



## References 

Braun, D. R., Plummer, T., Ditchfield, P., Ferraro, J. V., Maina, D., Bishop, L. C., & Potts, R. (2008). Oldowan behavior and raw material transport: perspectives from the Kanjera Formation. Journal of Archaeological Science, 35(8), 2329-2345.

Goldman-Neuman, T., & Hovers, E. (2012). Raw material selectivity in late Pliocene Oldowan sites in the Makaamitalu Basin, Hadar, Ethiopia. Journal of Human Evolution, 62(3), 353-366.

Stout, D., Quade, J., Semaw, S., Rogers, M. J., & Levin, N. E. (2005). Raw material selectivity of the earliest stone toolmakers at Gona, Afar, Ethiopia. Journal of Human Evolution, 48(4), 365-380.
