# Mars Crater Analysis

This repository contains the data analysis and visualization code for a dataset on Mars craters. The code explores the characteristics of craters such as diameter, depth, morphology, and the number of layers. It includes a variety of plots to help in the understanding of these features.

## Plot Descriptions

### Diameter Distribution (Histogram)
[image](https://github.com/aadishj19/Martian-Crater-Analysis/assets/84670503/c99d9f78-df11-42d0-a9aa-57b7e01744c2)
This histogram shows the distribution of crater diameters in the dataset on a logarithmic scale. The number of craters decreases as the diameter increases, indicating that smaller craters are far more common than larger ones.

### Depth Distribution - Positive Values
[image](https://github.com/aadishj19/Martian-Crater-Analysis/assets/84670503/50efef6b-b7a7-47ca-9a10-0b0d28f353e0)

When considering only positive depth values, the histogram still shows that shallow craters predominate, yet there is a noticeable tail of craters that have greater depths.

### Depth vs. Diameter (Scatter Plot)
[image](https://github.com/aadishj19/Martian-Crater-Analysis/assets/84670503/a63358db-0db0-47ae-8aa8-aa112f5d62f4)
The scatter plot of depth versus diameter indicates that larger craters tend to have greater depths. However, there is a considerable amount of variation, particularly for smaller craters.

### Depth vs. Log10(Diameter) (Scatter Plot)
[image](https://github.com/aadishj19/Martian-Crater-Analysis/assets/84670503/e823b541-cd30-4d8f-acf9-fd359c208c25)

When the diameter is log-transformed, the scatter plot shows a clearer trend between crater diameter and depth. Larger craters (on a log scale) still show a tendency to be deeper, but the variability is highlighted.

### Morphology Ejecta 1 - Top 20 (Bar Chart)
[image](https://github.com/aadishj19/Martian-Crater-Analysis/assets/84670503/ed1a56c7-c855-4e24-ab7e-e05ade7a7562)
The bar chart for the top 20 morphologies of the first ejecta type (MORPHOLOGY_EJECTA_1) reveals that one category overwhelmingly dominates, with other morphologies being less frequent.

### Morphology Ejecta 1 - Top 20 Ignoring Blanks (Bar Chart)
[image](https://github.com/aadishj19/Martian-Crater-Analysis/assets/84670503/8311118b-f081-4375-95c7-640e78055086)
When blank entries are ignored, the bar chart indicating the top morphological features of ejecta displays a more varied distribution, although one category still remains the most common by a significant margin.

### Static Plot of All Mars Craters
[image](https://github.com/aadishj19/Martian-Crater-Analysis/assets/84670503/32987f4d-dccf-4d89-bbc4-6c53b02d7214)
This plot maps the location of all craters on Mars, represented by dots, with their diameter indicated by the dot size. The density of craters varies across different regions, and the plot highlights areas with a higher concentration of craters.

### Density and Marginal Distributions of Latitude/Longitude for Mars Craters
[image](https://github.com/aadishj19/Martian-Crater-Analysis/assets/84670503/ba621d2b-8fb5-4533-9c06-98976a769e07)
The hexbin plot combined with bar charts on the top and right represents the density of craters on Mars by latitude and longitude. Darker hexbins indicate areas with a higher density of craters. The marginal histograms show the distribution of latitudes (top) and longitudes (right) where craters are more commonly found.

### Mars Craters Larger Than 50km in Diameter
[image](https://github.com/aadishj19/Martian-Crater-Analysis/assets/84670503/5e7fe379-3c4f-40f6-b9e5-3a96c5c3c9c1)
This scatter plot focuses on craters larger than 50 kilometers in diameter, with crater sizes still indicated by dot size. This visualization emphasizes the distribution of larger craters across Mars, showcasing their spread and how they are present across various geographical regions.

### Static Plot of Named Mars Craters
[image](https://github.com/aadishj19/Martian-Crater-Analysis/assets/84670503/0dc86270-d6ea-49b4-9c3e-eee7dde7d69b)
The plot specifically highlights named Mars craters, differentiating them from unnamed ones. The diameters of these craters are represented by the sizes of the dots. This plot provides a clear view of notable craters that have been studied more thoroughly and assigned names.

### Number of Layers - Named Craters Only
[image](https://github.com/aadishj19/Martian-Crater-Analysis/assets/84670503/3a6ba477-77bb-4761-b91d-57b3efceee91)
This bar chart presents the distribution of the number of layers observed in named craters. It shows that most named craters do not have identified layers, while a few have up to four distinct layers, which may provide insights into their formation and geological history.

### Top Morphologies in Craters by Size
[image](https://github.com/aadishj19/Martian-Crater-Analysis/assets/84670503/3ec637a5-0666-494b-aa88-ba9b79d51093)
These bar plots display the most common morphology types for small, medium, and large craters. Each plot reveals that certain morphologies are more prevalent in craters of different sizes. For instance, the "Rd" (Rampart) morphology appears to be a dominant feature across all size categories.

