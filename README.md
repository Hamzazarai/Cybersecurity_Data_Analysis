# Cybersecurity Data Analysis

## Project Context
This project focuses on analyzing cybersecurity data with the goal of uncovering patterns, identifying vulnerabilities, and deriving actionable insights.<br> The dataset used contains detailed information about network traffic and security incidents.<br>
The project is part of a data analysis initiative for the Data Analysis course at the **FSS**  (Faculty of Sciences of Sfax).


### Authors:
- **Hamza ZARAI**  
  Email: [hamzazarai11@gmail.com](mailto:hamzazarai11@gmail.com)  
- **Ibrahim GHALI**  
  Email: [ghaliibrahim60@gmail.com](mailto:ghaliibrahim60@gmail.com)

## Repository Structure
The repository is organized as follows:

```
cybersecurity-data-analysis/
│
├── README.md               # Project overview (this file)
├── data/
│   ├── raw/                # Raw data (original files)
│   │   └── cybersecurity_attacks.csv
│   ├── processed/          # Processed/cleaned data
│       └── processed_cybersecurity_attacks.cs
├── notebooks/
│   ├── Cybersecurity Data Analysis.ipynb


├── results/
│   ├── figures/            # Saved visualizations
│  
│   └── tables/             # Tabular results
│      
└── .gitignore              
```


## Objectives and Key Questions

### General Objectives:
- Identify common patterns in cybersecurity incidents.
- Analyze the correlations between various factors (e.g., protocol, packet size, severity).
- Provide insights to improve detection and response mechanisms.

### Key Questions:
1. Which types of traffic and protocols are most frequently associated with high-severity incidents?
2. Which network segments or geographical zones are most vulnerable?
3. Are there correlations between packet size, traffic type, and severity level?
4. What temporal trends (e.g., time of day, month) can be observed in the incidents?
5. How are incidents distributed across platforms, browsers, and device types?
6. What measures were most effective in mitigating high-severity incidents?

## How to Use

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Hamzazarai/Cybersecurity_Data_Analysis.git
   cd Cybersecurity_Data_Analysis
   ```


2. **Explore Notebooks:**
   - Start Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Open and run the notebooks in the `notebooks/` directory.

3. **Analyze Results:**
   - Visualizations and tables are saved in the `results/` directory for easy access.

## Dependencies
The project requires the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn



## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.



