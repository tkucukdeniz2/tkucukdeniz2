# Tarık Küçükdeniz

**Professor of Industrial Engineering · İstanbul University-Cerrahpaşa**\
Operations research · metaheuristic optimization · machine learning · open research software

[![ORCID](https://img.shields.io/badge/ORCID-0000--0002--6670--1809-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0000-0002-6670-1809)
[![Email](https://img.shields.io/badge/Email-tkdeniz%40iuc.edu.tr-0A66C2?logo=maildotru&logoColor=white)](mailto:tkdeniz@iuc.edu.tr)
![Location](https://img.shields.io/badge/İstanbul-Türkiye-E30A17)

I build optimization and machine-learning tools that turn messy operational data into decisions:
facility location and routing, workforce scheduling, demand and energy forecasting, and
ML-assisted electrochemical sensing. I head the Department of Industrial Engineering and direct
the university's Institutional Data Management Office, and I have worked as a part-time R&D
consultant to the software industry since 2004.

## Research software

| Project | What it does | Publication or use |
|---|---|---|
| [**CurricuMap**](https://github.com/tkucukdeniz2/curricumap) | Turns registrar transcript exports into auditable student-by-competency matrices. Declarative YAML taxonomies, rule-level provenance for every course, reliability audit (Cronbach's α). CLI, tests, CI. | *SoftwareX*, accepted 2026 · [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22140689.svg)](https://doi.org/10.5281/zenodo.22140689) |
| [**ElectroML**](https://github.com/tkucukdeniz2/ElectroML) | Web platform for analyte concentration prediction from cyclic and differential pulse voltammetry: signal preprocessing, 47 engineered features, 14 regressors with Optuna tuning, leakage-safe cross-validation. | *SoftwareX* 34 (2026) 102640 · [doi:10.1016/j.softx.2026.102640](https://doi.org/10.1016/j.softx.2026.102640) |
| [**University course timetabling**](https://github.com/tkucukdeniz2/university-course-timetabling) | CP-SAT model that schedules a whole department: classrooms, a shared lab and faculty-granted amphitheatres, instructor availability, elective groups with solver-chosen pairing and a guaranteed free day for every cohort. Independent constraint checker, Excel output, anonymised example instance, tests, CI. | Developed for the department's 2026–27 timetable |

## Other projects

- [**Dubber**](https://github.com/tkucukdeniz2/dubber): dubs English YouTube videos into Turkish on a Mac. A Chrome extension reads the captions; a local server translates whole sentences with a local LLM (llama.cpp), speaks them in a designed voice (VoxCPM2) and keeps the voice in step with the video. 1,100+ tests, CI.

## Research focus

- **Location and routing.** Hybrids of fuzzy c-means with Nelder–Mead, Weiszfeld, convex programming and simulated annealing for multi-facility location, location-routing and multi-robot task allocation.
- **Metaheuristics and learning-augmented search.** Particle swarm optimization, tabu search with Q-learning, differential evolution, simulated annealing.
- **Forecasting.** Electricity load, retail demand (foundation models and LLM-based methods), traffic event duration.
- **Workforce scheduling.** Machine-learning demand forecasts combined with constraint programming for retail shift planning.
- **Machine learning for sensing and materials.** Regression and deep-learning models for electrochemical sensors, with chemistry collaborators.
- **Higher-education analytics.** Rankings, institutional data supply chains and data governance.

## Selected publications

- A novel hybrid tabu search and Q-learning algorithm for optimizing complex container loading problems. *INFOR: Information Systems and Operational Research*, 2026. [doi:10.1080/03155986.2026.2657134](https://doi.org/10.1080/03155986.2026.2657134)
- Survival probability-weighted clustering for UAV-based multi-robot task allocation in disaster response. *Evolutionary Intelligence*, 2026. [doi:10.1007/s12065-026-01257-5](https://doi.org/10.1007/s12065-026-01257-5)
- ElectroML: an open-source web platform for machine learning-based analyte concentration prediction in electrochemical sensing. *SoftwareX*, 2026. [doi:10.1016/j.softx.2026.102640](https://doi.org/10.1016/j.softx.2026.102640)
- Optimizing harvest planning in perishable agricultural production: a data-driven approach leveraging weather conditions and clustering analysis. *Food and Energy Security*, 2025. [doi:10.1002/fes3.70107](https://doi.org/10.1002/fes3.70107)
- Optimizing retail workforce management: integrating machine learning forecasting with constraint programming for dynamic shift planning. *IEOM Conference*, 2025. [doi:10.46254/EU08.20250258](https://doi.org/10.46254/EU08.20250258)
- Dynamic forecasting of traffic event duration in Istanbul: a classification approach with real-time data integration. *Computers, Materials & Continua*, 2024. [doi:10.32604/cmc.2024.052323](https://doi.org/10.32604/cmc.2024.052323)
- Fuzzy c-means and simulated annealing for planar location-routing problem. *Journal of Intelligent & Fuzzy Systems*, 2022. [doi:10.3233/JIFS-221168](https://doi.org/10.3233/JIFS-221168)
- Hybrid revised weighted fuzzy c-means clustering with Nelder–Mead simplex algorithm for generalized multisource Weber problem. *Journal of Enterprise Information Management*, 2018. [doi:10.1108/JEIM-01-2018-0002](https://doi.org/10.1108/JEIM-01-2018-0002)
- Integrated use of fuzzy c-means and convex programming for capacitated multi-facility location problem. *Expert Systems with Applications*, 2012. [doi:10.1016/j.eswa.2011.09.102](https://doi.org/10.1016/j.eswa.2011.09.102)
- A fuzzy clustering-based hybrid method for a multi-facility location problem. *Journal of Intelligent Manufacturing*, 2009. [doi:10.1007/s10845-008-0233-y](https://doi.org/10.1007/s10845-008-0233-y)

The full list of 40+ publications is on [ORCID](https://orcid.org/0000-0002-6670-1809).

## Tools

Python · pandas · NumPy · scikit-learn · XGBoost · LightGBM · Optuna · Flask · Streamlit · constraint programming · metaheuristics

## Teaching and supervision

Operations research, heuristic optimization and machine learning in the Industrial Engineering
programme; supervisor of 20+ MSc and PhD theses.

The department I head publishes its students' capstone projects as open source at
[**github.com/iuc-ie**](https://github.com/iuc-ie): 18 industry-oriented projects from the 2026 cohort
in demand forecasting, routing, cutting-stock and timetabling optimization, anomaly detection and
customer analytics, built on a shared [project template](https://github.com/iuc-ie/capstone-template).

## Work with me

I am open to collaboration on optimization and machine-learning problems in logistics,
manufacturing, retail and energy, and to technical evaluation of R&D projects.
Reach me at [tkdeniz@iuc.edu.tr](mailto:tkdeniz@iuc.edu.tr).
