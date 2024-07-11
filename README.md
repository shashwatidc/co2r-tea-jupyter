### Physics-informed technoeconomic assessment for CO<sub>2</sub>R

**Cite this work** : 
> Da Cunha, S.; Resasco, J. Insights from Techno-Economic Analysis Can Guide the Design of Low-Temperature CO₂ Electrolyzers towards Industrial Scaleup; preprint; ChemRxiv, 2024. DOI: [10.26434/chemrxiv-2024-g76xl](https://chemrxiv.org/engage/chemrxiv/article-details/668eaa4c01103d79c59ceaf6). 
         

This tool generates the capital and operating cost for a CO₂ reduction process converting captured CO₂ into either CO or ethylene. It generates all figures in our [2024 paper](https://chemrxiv.org/engage/chemrxiv/article-details/668eaa4c01103d79c59ceaf6).

For a more interactive version of this backend, check out the [CO<sub>2</sub>R Costing Dashboard web app](https://co2r-dashboard.streamlit.app/).You only need this repository if you want to see and run the raw model. Fork or download/clone the entire repository - none of these notebooks run independendtly. Get started by running all of `<version>_4_TEA_Integrated.ipynb` - it will prompt you to interact and set up the figures you want.

**Figure generation and analysis**

"Front end" notebook for figure generation, data analysis, saving results to Excel files: `<version>_4_TEA_Integrated.ipynb`

**Models**

Electrolyzer: `<version>_0_ElectrolyzerModel.ipynb`

Mass and energy balances: `<version>_1_DownstreamProcessModel.ipynb`

Technoeconomics: `<version>_2_ProcessEconomics.ipynb`

Single run execution: `<version>_3_TEA_SingleRun.ipynb`

**Data**

Data for constants, utilities and products: `Supplementary Workbook.xlsx`


**Other**

License: `LICENSE.md`

Readme: `README.md`
