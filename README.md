# ICASA-Dictionary
This is the official location for the ICASA Data Dictionary (IDD), which was previously hosted as a Google Sheet. The IDD forms the core of the ICASA data standards. It provides a vocabulary for describing field experiments or farming practices with a focus on annual or short-lived annual crops (White et al., 2013). The IDD includes sections for:
1. Metadata - Basic descriptions, including persons involved, type of experiment, and experimental design.
2. Management - Detailed information on individual management practices including plantings, irrigations, fertilizer applications, tillage and harvests, among others. Most practices include a data, a method, and an amount of material add or removed.
3. Soils - Described properties of soil profiles including profile metadata, surface properties, and properties for different soil depth layers (e.g., texture, bulk density, water retention characteristics, and chemistry).
4. Weather - Daily weather including station metadata and individual variables such as solar radiation, maximum and minimum temperature, average wind speed, total precipitation, and dewpoint temperature.
5. Measurements - Variables used to describe crop or soil properties. These are grouped as summary, time series, and time series by soil layer. Summary includes dates of key development events (i.e., phenology), crop yield, yield components, and various summary growth or nutrient descriptors.
Additional sections describe codes used to simplify coding for different crops, agronomic inputs, application methods, etc.

Although the IDD was developed largely by researchers using crop simulation models, we emphasize that the IDD is a generic dictionary for agronomic research (Hunt et al., ). Many variables are included because they can help researchers understand how a given experiment was conducted or how the data can best be interpreted. This goal of generality is aligned with the increasing expectation that research datasets be made available in readily re-usable formats (White et al., 2025).

The IDD is accesible here in two formats:
1. XLSX - This is the full dictionary with all worksheets. The GitHub interface does not allow viewing the file contents, so if you want to use the workbook, you have to download to file. 
2. CSV - The CSV folder contains each worksheet. If you just need to search for individual terms, this may be an easier format to use since GitHub can display the content of each file.

The IDD is constantly evolving and has benefitted greatly from recent interest in organizing research datasets (e.g., Porter et al., 2014) and data mining using artificial intelligence (AI). We welcome feedback via the "Issues" section of this GitHub project. Future interests include:
1. Allowing users to describe protocols, especially when a single trait (variable) is measured in more than one way. Common examples include normalized diffence vegetation index (NDVI), specific leaf area (SLA).
2. Including more detailed definitions to improve processing with AI tools.
3. Including options for describing measurements at "sub-daily" intervals or specific times.
4. Develop tools to allow users to create datasets based on variables defined in the IDD.

As of 2025-07-11, we have introduced multiple changes. Most notably besides the CSV format, we have added a unique ID for each variable in the dictionary. For further information, please see the description of recent changes.
Included in the updates is implementation of a script using GitHub Actions that updates the XLSX version every time the CSV files are modified. This should ensure that the XLSX file is always synchronized with the CSV files.

## References
Hunt, L. A., White, J. W., & Hoogenboom, G. (2001). Agronomic data: Advances in documentation and protocols for exchange and use. Agricultural Systems, 70(2–3), 477–492. https://doi.org/10.1016/S0308-521X(01)00056-7

Porter, C. H., Villalobos, C., Holzworth, D., Nelson, R., White, J. W., Athanasiadis, I. N., Janssen, S., Ripoche, D., Cufi, J., Raes, D., Zhang, M., Knapen, R., Sahajpal, R., Boote, K., & Jones, J. W. (2014). Harmonization and translation of crop modeling data to ensure interoperability. Environmental Modelling & Software, 62, 495–508. https://doi.org/10.1016/j.envsoft.2014.09.004

White, J. W., Hunt, L. A., Boote, K. J., Jones, J. W., Koo, J., Kim, S., Porter, C. H., Wilkens, P. W., & Hoogenboom, G. (2013). Integrated description of agricultural field experiments and production: The ICASA Version 2.0 data standards. Computers and Electronics in Agriculture, 96, 1–12. https://doi.org/10.1016/j.compag.2013.04.003

White, J. W., Boote, K. J., Kimball, B. A., Porter, C., Salmeron, M., Shelia, V., Thorp, K. R., & Hoogenboom, G. (2025). From field to analysis: Strengthening reproducibility and confirmation in research for sustainable agriculture. Npj Sustainable Agriculture, 3(1), 1–8. https://doi.org/10.1038/s44264-025-00067-z


