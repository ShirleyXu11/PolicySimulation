# Bangladesh Youth Unemployment Policy Simulator

An interactive research tool developed to simulate and analyze policy impacts on youth unemployment and economic outcomes in Bangladesh. This simulator is built using Python and Jupyter Notebook and designed for academic research purposes.

## 🚀 Key Features

- **Interactive Policy Analysis:** Easily simulate the effects of various policy interventions such as educational reforms, rural technology adoption, and gender equity initiatives.
- **Data Integration:** Automated retrieval and parsing of data from authoritative sources, including BBS Labour Statistics and CEIC Wage Index.
- **Real-time Visualization:** Clear and intuitive visual representation of policy effects.
- **Policy Recommendations:** AI-driven expert recommendations based on simulated outcomes.

## 📂 Project Files

```
PolicySimulation/
├── Part3_Policy_simulation.ipynb    # Main Jupyter Notebook for simulation
├── requirements.txt                 # Python dependencies
└── README.md                        # Project documentation
```

## ⚙️ Setup and Installation

To run this project locally or on platforms like Google Colab:

### Install Dependencies

```bash
pip install -r requirements.txt
jupyter nbextension enable --py widgetsnbextension
```

### Run Jupyter Notebook

```bash
jupyter notebook Part3_Policy_simulation.ipynb
```

Or open directly in [Google Colab](https://colab.research.google.com).

## 📖 Data Sources

- [BBS Labour Force Survey](https://bbs.portal.gov.bd)
- [CEIC Economic Database](https://www.ceicdata.com)

## 📊 Policy Elasticities

| Policy Intervention       | Elasticity | Source |
|---------------------------|------------|--------|
| Vocational Training       | -0.35      | BBS Labour Survey |
| Rural AgriTech Adoption   | +0.51      | CEIC Economic Database |
| Childcare Subsidies       | +0.68      | World Bank |

## 📝 Academic References

- Bangladesh Bureau of Statistics. (2021). *Labour Force Survey Report.*
- Ministry of Agriculture. (2023). *Rangpur District Economic Profile.*
- CEIC Data. (2023). *Bangladesh Wage Rate Index.*
- World Bank. (
