# Conti Ransomware - IOC Dataset (MITRE ATT&CK Classification)

This repository contains structured data extracted from Conti ransomware operations, specifically related to indicators of compromise (IOCs) discovered through leaked internal communications and victim reports.

## 📁 Folder: `data/`

The `data/` folder contains the cleaned and structured IOC dataset (`IOCs_Conti.csv`) used in the analysis for the Master's Thesis titled:

> “Strategic and Relational Analysis of Conti Ransomware Operations Based on Leaked Data and MITRE ATT&CK Framework”

The CSV file includes the following columns:

- `MITRE Tactic/Technique`: Categorization of the IOC under MITRE ATT&CK
- `Date`: Timestamp of the event or observation
- `From`: Actor/source involved in the communication
- `To`: Recipient/target of the communication
- `IOC Summary`: A short description of the detected indicator

This dataset was prepared using Python, cleaned to remove irrelevant or duplicate entries, and manually reviewed to ensure alignment with the MITRE ATT&CK framework. Only indicators with real analytical value were retained.

## ⚠️ Ethical & Legal Considerations

All data included in this repository originates from publicly leaked sources released by the Conti group itself during 2021–2022. The dataset is provided exclusively for academic and research purposes and does not contain personally identifiable information (PII). Use responsibly.

## 📚 Citation

If you use this dataset or refer to this repository, please cite:

**Ramonfure (2024). Strategic and Relational Analysis of Conti Ransomware Operations Based on Leaked Data and MITRE ATT&CK Framework. GitHub Repository.**

