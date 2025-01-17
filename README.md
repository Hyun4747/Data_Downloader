# DefiLlama

- Source code

  - Collect dataset from "Download .csv" button
    - `extractTvl.ipynb`
  - Generate meta file `final_tvl.csv` of dataset and save to `final_tvl` folder
    - `metaTvl.ipynb`
  - [Not used] Merge protocol or chain dataset
    - `mergeTvl.ipynb`

- Limitation
  - `web_crawling` folder contains source code that gathers data directly from web pages. (`sample\_~~.json` is the example file) While this method provides more data compared to using "Download .csv" button, defillama does not clarify how to calculates TVL(USD). Additionally, the data obtained through web crawling has inconsistent timestamps with some records at daily interval but others at hour even minute interval. Therefore, we decided not to include the dataset obtained through web crawling.
