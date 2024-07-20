# nc-beach-nourishment

Visualizations and context using data from the Program for the Study of Developed Shorelines at Western Carolina University

By Daniel Moul

## Acknowledgements

Thanks to the people and organizations that made data available

- [Program for the Study of Developed Shorelines](https://beachnourishment.wcu.edu) at Western Carolina University
- NOAA shoreline GIS data from the [Global Self-consistent, Hierarchical, High-resolution Geography Database (GSHHG)](https://www.ngdc.noaa.gov/mgg/shorelines/)
- U.S. Census TIGRIS database (accessed via the tidycensus packaga)
- [GeoNames](https://www.geonames.org) lookup service
- Hat tip to Jeremy Signer-Vine for Data Is Plural [2024.07.03 edition](https://www.data-is-plural.com/archive/2024-07-03-edition/), where I learned about the beach nourishment data.

## Licenses

The text is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) meaning you can share and adapt its content as long as you provide attribution. The source code that generates the text is licensed under the MIT License.

## Replicating this document

1.  Clone this GitHub repo (dmoul/finnish-vehicle-insights)

2.  Download the data and put it in the right place
    - In the project root directory create ./data/raw and related subdirectories. See nourishment-episdoes.qmd for exact directory names needed.
    - Download data from sources noted in notes.qmd.

3.  Install [quarto](https://quarto.org) if it's not already installed.

4.  In a terminal window, run this: quatro render
