# Raw_Material_Selectivity
## Title: Investigating Early Human Ancestors' Cognitive Abilities Through Raw Material Selection for Stone Tools

**Project Description:** Modern humans possess remarkable cognitive abilities that enable us to create a wide range of complex tools, from stone implements to advanced AI software. However, determining the timeline of the emergence of more sophisticated cognitive capacities in early humans is difficult.

Studying the raw material selection for stone tool creation provides valuable insights into the cognitive abilities of early hominins, our human ancestors. Many early hominin sites exhibit a consistent pattern of selecting specific rock types for stone tools, suggesting a cognitive grasp of the mechanical properties inherent in the stones. 

This project analyzes the frequency of rock selectivity by comparing artifact quantities to rock availability at each early hominin site, enhancing our understanding of early human cognition and shedding light on the development of complex cognitive abilities in our ancestors.

## Data

The data for this project was compiled from multiple peer-reviewed research publications and transformed into two cohesive datasets, Combined_Sites and Simplified_Combined_Sites. 

Both datasets include site names, raw material names, artifact raw material totals, local raw material totals, adjusted local raw material totals, artifact raw material site frequency, raw material local frequency, and adjusted raw material local frequency. 

The Simplified_Combined_Sites simplified the raw material names and grouped the raw materials together by rock type, while the Combined_Sites keeps the original raw material names. 

For the purpose of this code, we used the Simplified_Combined_Sites dataset.

**Note: Artifact raw material totals and local raw material totals were used to generate adjusted local raw material totals, adjusted raw material local frequency, and create the simplified dataset.

For artifact raw material totals and local raw material totals for sites AL894 and AL-666 were extrapolated from Goldman-Neuman and Hovers (2012), calculating the totals from the reported frequencies and sample totals in Google Sheets (see Figure 1 for formula). 

The artifact raw material totals and local raw material totals for sites OGS-7,	OGS-6a,	EG-13, DAN-1, DAS-7,	and DAN-2d were extrapolated from Stout et al. (2005), calculating the totals from the reported frequencies and sample totals in Google Sheets (see Figure 1 for formula). 

![stonetoolproject](https://github.com/ktuosto/Raw_Material_Selectivity/assets/49923281/c1f1a9c2-2a3f-4a90-abd0-cbe281bf1de0)
*Figure 1: Formula (frequency * sample total) used to calculate artifact raw material totals and local raw material totals.*

Kanjera South's (Kenjera in dataset) raw material totals and local raw material totals were from Braun et al. (2008), and artifact raw material site frequency and raw material local frequency was calculated in Google Sheets. 

LA2C site data is from a presentation by Tuosto et al. (2017). 

## Code

Calculating initial sample totals was done in Google Sheets (see Figure 1), the frequencies, selectivity analysis, and data visualization was done in R, and the dashboard creation was done in R Shiny. 

The first code file provided here is for the frequencies, selectivity analysis, and data visualization. The second code file is for the dashboard creation. 

## Usage

While the code provided is currently being used to look at early human ancestors' cognitive abilities, the analysis can also provide valuable insights for decision-making and strategy development in various business contexts. 

For example:

- **Market research:** Analyzing selectivity can help us understand customer preferences and behaviors. By examining the selectivity of customers for different products or features, businesses can identify patterns and tailor their marketing strategies, product offerings, or customer segmentation to better meet customer needs and improve market competitiveness.

- **Product development:** Understanding the selectivity of customers for various product attributes can guide product development efforts. By analyzing selectivity, businesses can identify which features or characteristics are more preferred or influential in driving customer choice, allowing them to prioritize resources and design products that align with customer preferences.

- **Pricing strategies:** Selectivity analysis can inform us of pricing strategies by examining how customers select products or services at different price points. By understanding selectivity patterns, businesses can optimize their pricing structures, discounts, or bundling strategies to maximize revenue and profitability.

- **Resource allocation:** Selectivity analysis can help businesses allocate resources effectively. By identifying the selectivity of different market segments or customer groups, businesses can allocate their marketing, advertising, and sales efforts toward the segments that show higher selectivity or are more likely to convert, resulting in improved resource utilization and return on investment.

## Results

- Evidence from numerous Early Pleistocene sites suggests hominins consistently select rock types for artifact manufacture at levels that exceed their availability in local gravels.

Meaning our early human ancestors 2.5 million years ago were consciously selecting specific stones for tool making and not randomly picking up just any stone, suggesting they had the cognitive ability to understand stone properties needed for making a stone tool. 

- The variance in selectivity between Early Pleistocene localities is great. But the selection pressures on the behaviors associated with rock selectivity for different sites are dependent on the context of the archaeological sites

Meaning there are a lot of differences in what stone is being selected at each individual site due to the type of raw material variable in the geographic area. 

![PaleoPoster2017Result on the side Done_resized](https://github.com/ktuosto/Raw_Material_Selectivity/assets/49923281/1b15105a-ae81-4bc5-b6e9-aa5094c1db5a)
*Figure 2: Poster presentation presented at the 2017 annual Paleoanthropology Society conference in Vancouver, Canada.*

## References 

Braun, D. R., Plummer, T., Ditchfield, P., Ferraro, J. V., Maina, D., Bishop, L. C., & Potts, R. (2008). Oldowan behavior and raw material transport: perspectives from the Kanjera Formation. Journal of Archaeological Science, 35(8), 2329-2345.

Goldman-Neuman, T., & Hovers, E. (2012). Raw material selectivity in late Pliocene Oldowan sites in the Makaamitalu Basin, Hadar, Ethiopia. Journal of Human Evolution, 62(3), 353-366.

Stout, D., Quade, J., Semaw, S., Rogers, M. J., & Levin, N. E. (2005). Raw material selectivity of the earliest stone toolmakers at Gona, Afar, Ethiopia. Journal of Human Evolution, 48(4), 365-380.
