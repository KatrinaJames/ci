# CI Investments
Analysis of Canadian All-Cap Equity and CI Select Global Equity funds

## How to run locally
- Build the conda environment with `conda env create --file environment.yaml`
- Activate the environment with `conda activate ci`
- Launch either `jupyter lab` or `jupyter notebook`

## Deployed web apps
### CI Canadian All Cap Equity
- View on mybinder [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/KatrinaJames/ci/HEAD?urlpath=voila%2Frender%2Fcan_app%2Fcanadian_app.ipynb)
- Or run locally using `python -m voila canadian_app.ipynb` from the `can_app` directory

### CI Select Global Equity
- View on mybinder [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/KatrinaJames/ci/HEAD?urlpath=voila%2Frender%2Fglobal_app%2Fglobal_app.ipynb)
- Or run locally using `python -m voila global_app.ipynb` from the `global_app` directory

## Conventions and Layout
- Front end of apps are stored in `*_app` folders
- Data from CI is stored in the `data` folder
- Fetching data via public APIs and general data manipulation and number crunching contained in the `analysis` folder
