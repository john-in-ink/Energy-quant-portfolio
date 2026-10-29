# Energy-quant-portfolio
Quantitative trading research portfolio focusing on fundamental weather-alpha models, power grid optimisation, and energy derivatives


german-eez-wind-yield-and-metocean-assessment/
├── LICENSE                     # MIT License specification text
├── main.py                     # Master orchestration driver script
├── requirements.txt            # Explicit dependency version locks
├── README.md                   # Primary portfolio documentation page
├── data/
│   └── german_bight_metocean_raw.nc # Downloaded raw NetCDF spatial array file
├── notebooks/
│   └── yield_and_metocean_plots.ipynb # Interactive verification plots
├── outputs/
│   ├── german_bight_asset_yield_metrics.csv # Sliced engineering data flat files
│   └── EXECUTIVE_YIELD_REPORT.md             # Pipeline-generated markdown report briefing
└── src/
    ├── __init__.py             # Namespace declaration
    ├── analytics.py            # Primary pipeline calculation engine
    ├── config.py               # Centralized site configurations and constants
    ├── download_metocean_data.py # Automated CDS data acquisition script
    ├── plots.py                  # 7-panel visual graphic plotting suite
    └── utils.py                # Core engineering mathematical library





energy-quant-portfolio/
│
├── data_pipeline/         # Scripts to pull weather & grid data
│   ├── __init__.py
│   └── ingest_eia_noaa.py
│
├── strategy/              # Your mathematical predictive models
│   ├── __init__.py
│   └── alpha_model.py
│
├── backtester/            # Vectorized backtesting engine
│   └── engine.py
│
├── research/              # Jupyter Notebooks for EDA & prototypes
│   └── exploration.ipynb
│
├── README.md              # The executive executive summary
└── requirements.txt       # Dependencies (pandas, numpy, scipy, etc.)

    
