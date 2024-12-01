# -vegetation-loss-across-Kenya-due-to-locusts-using-Sentinel-2

Kenya Boundary: The boundary is used to clip Sentinel-2 data.
NDVI Calculation: Computes NDVI for pre- and post-invasion periods.
NDVI Difference: Highlights vegetation loss (negative values indicate loss).
Visualization: Displays pre/post NDVI and changes with color maps.
Export: Saves the NDVI difference map for further analysis.

Kenya Boundary:
The country boundary is used to define the area of interest.
Time Periods:
The script calculates pre-invasion NDVI for January–June 2019 and post-invasion NDVI for June–December 2020.
Visualization:
Separate maps are created for each period with NDVI values represented in shades of green (white for no vegetation, green for high vegetation).
Exporting Maps:
Pre- and post-invasion NDVI maps are exported as GeoTIFF files for use in other GIS tools.

Red Areas (Negative NDVI Difference):
Significant vegetation loss, likely caused by locust invasion or other factors.
White Areas (Near Zero Difference):
No significant change in vegetation.
Green Areas (Positive NDVI Difference):
Vegetation recovery or growth during the post-invasion period.

![before](https://github.com/user-attachments/assets/89ab8344-96cd-40e6-8a91-ac99e53d5516)


![after](https://github.com/user-attachments/assets/a6175420-52ad-418f-bf80-2d7f978fc948)


![difference](https://github.com/user-attachments/assets/d22f9d6c-a748-4bd6-8762-cffbfd0deac0)
