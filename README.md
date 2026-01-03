# hospital_los_regressor

**Academic, reproducible pipeline** for predicting hospital Length of Stay (LOS) and discharge disposition using SPARCS inpatient discharge data (NYC, Richmond County, 2023). 

**Purpose**: Emphasizes data quality assessment, feature engineering, and supervised learning models to **predict hospital length of stay (LOS)**. Evaluates model performance with out-of-sample metrics; interprets results under an **associational framework**, acknowledging observational/administrative data limitations. Assesses how well routinely collected administrative variables predict LOS (prediction, not causal inference).

## Project Structure
```bash
.
├── datasets/
│ ├── odbl-10.txt # ODbL 1.1 License (dataset)
│ └── HospitalInpatientDischargesSPARCSDe-IdentifiedNYCityRichmond2023
├── src/ 
│ └── hospital_los_regressor.ipynb # Complete executable pipeline
├── requirements.txt
├── LICENSE # MIT License (code)
└── README.md
```

## Copyright and License

- **© 2026 Isabel Bejerano Blazquez**
- **Notebook**: MIT License
- **Data**: ODbL 1.1 

Developed and tested on:

- **Python ≥ 3.10**  
- **Core dependencies:** see requirements.txt file

## Quick start

```bash
## Create and activate environment
python3.10 -m venv venv
source venv/bin/activate      # macOS/Linux
venv\Scripts\activate         # Windows

# Install dependencies
pip install -r requirements.txt  

# Run notebook
jupyter notebook src/hospital_los_regressor.ipynb
```

**Disclaimer**: Provided *as is*, for academic use only.

