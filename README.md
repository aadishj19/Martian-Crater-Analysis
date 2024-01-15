# Mars Crater Analysis

This repository contains the data analysis and visualization code for a dataset on Mars craters. The code explores the characteristics of craters such as diameter, depth, morphology, and the number of layers. It includes a variety of plots to help in the understanding of these features.

## Plot Descriptions

### Diameter Distribution (Histogram)
![Diameter Distribution](attachment:diameter_hist.png)
This histogram shows the distribution of crater diameters in the dataset on a logarithmic scale. The number of craters decreases as the diameter increases, indicating that smaller craters are far more common than larger ones.

### Empirical CDF of Diameter
![Empirical CDF](attachment:empirical_cdf.png)
The empirical cumulative distribution function (CDF) plot illustrates the proportion of craters that have a diameter less than or equal to a given size. As the diameter increases, the CDF approaches 1, which signifies that almost all craters are smaller than the largest diameters observed.

### Log-Log Plot of 1-CDF
![Log-Log Plot](attachment:log_log_cdf.png)
This log-log plot shows the complementary CDF on a logarithmic scale for both the x and y-axis. The linear trend in this plot on a logarithmic scale suggests a power-law-like distribution of crater diameters.

### Depth Distribution (Histogram)
![Depth Distribution](attachment:depth_hist.png)
The histogram for depth distribution shows that the majority of craters have zero or near-zero depth measurements, with very few craters displaying significant depth.

### Depth Distribution - Positive Values
![Depth Distribution Positive](attachment:depth_positive_hist.png)
When considering only positive depth values, the histogram still shows that shallow craters predominate, yet there is a noticeable tail of craters that have greater depths.

### Depth vs. Diameter (Scatter Plot)
![Depth vs Diameter](attachment:depth_vs_diameter.png)
The scatter plot of depth versus diameter indicates that larger craters tend to have greater depths. However, there is a considerable amount of variation, particularly for smaller craters.

### Depth vs. Log10(Diameter) (Scatter Plot)
![Depth vs Log Diameter](attachment:depth_vs_log_diameter.png)
When the diameter is log-transformed, the scatter plot shows a clearer trend between crater diameter and depth. Larger craters (on a log scale) still show a tendency to be deeper, but the variability is highlighted.

### Number of Layers (Bar Chart)
![Number of Layers](attachment:number_layers.png)
The bar chart of the number of layers displays that the vast majority of craters have no identified layers, while a small fraction has one or more layers.

### Morphology Ejecta 1 - Top 20 (Bar Chart)
![Morphology Ejecta](attachment:morphology_ejecta.png)
The bar chart for the top 20 morphologies of the first ejecta type (MORPHOLOGY_EJECTA_1) reveals that one category overwhelmingly dominates, with other morphologies being less frequent.

### Morphology Ejecta 1 - Top 20 Ignoring Blanks (Bar Chart)
![Morphology Ejecta Ignoring Blanks](attachment:morphology_ejecta_ignore_blanks.png)
When blank entries are ignored, the bar chart indicating the top morphological features of ejecta displays a more varied distribution, although one category still remains the most common by a significant margin.

## Getting Started

To run this analysis, ensure you have Python and the required libraries (numpy, pandas, matplotlib, plotly, seaborn, folium) installed. Clone the repository and execute the Jupyter notebook to regenerate the plots and explore the data.

To clone the repository, use:

```bash
git clone https://github.com/your-username/mars-crater-analysis.git
```

Navigate to the cloned directory and open the Jupyter notebook:

```bash
cd mars-crater-analysis
jupyter notebook Mars_Crater_Analysis.ipynb
```

## Additional Notes

When recreating the plots or analyzing the dataset, be attentive to any warning messages and ensure that appropriate data cleaning steps are taken to handle missing or anomalous data.

Please remember to cite the source of the Mars crater dataset if used in academic or research contexts.
