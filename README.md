# RCAN Prediction

This project focuses on predicting **recurrent child abuse and neglect (RCAN)**.

## Repository Contents

This repository currently contains **agent evaluation results** from the project. It includes processed experimental outputs only. **Raw source data are not included in this repository; access to the original data requires a separate application and approval through the relevant data provider.**

For a concise public description, the result groups can be viewed as:

```text
rl/evalResults/
├── ethicalBalance/
├── ethicalBonus/
└── ethicalPenalty/
```

### Folder Descriptions

- **ethicalBalance** — agent evaluation results from configurations that jointly consider predictive performance and ethical criteria.
- **ethicalBonus** — agent evaluation results from an ethics-emphasizing configuration.
- **ethicalPenalty** — agent evaluation results from an ethics-safeguarding configuration designed to protect a minimum ethical baseline.

Each CSV file contains evaluation results for a particular agent configuration and parameter setting.
