# data
demonstration data repo for Modern Agronomy


- `era5_grid.csv` is a keyed-mapping of era5 grid points to geohash7 keys for easy lookup in other applications
  - this particular table should cover most of the data set referenced below...
    
- `county_era5_grid.csv` is a `|GEOID|latitude|longitude|geohash7|` mapping of era5 points to GEOID's for fips lookup.
  - merged tables via geopandas and a "contains" left join.
    
- Planting Date Maps (Low Resolution) and County Data for the US Corn Belt as found at: https://zenodo.org/records/7790257
  - Field-scale dynamics of planting dates in the US Corn Belt from 2000 to 2020: https://www.sciencedirect.com/science/article/pii/S0034425723001025
