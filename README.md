<div align="center">

# 👋 Cyril BOURGEOIS

### Data Scientist · MLOps — Détection d'anomalies temps réel

[![Portfolio](https://img.shields.io/badge/Portfolio-visiter%20le%20site-2563eb?style=for-the-badge&logo=quarto)](https://cyril-bgs-dev-tech.github.io/Portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/cyril-bourgeois-65a739150/)
[![Kaggle](https://img.shields.io/badge/Kaggle-Top%201%25-20BEFF?style=for-the-badge&logo=kaggle)](https://www.kaggle.com/cyrilbourgeois)

</div>

Reconversion armée → commerce → data science. Je construis des systèmes ML **de bout en bout** : de la reproduction rigoureuse de l'état de l'art jusqu'à la mise en production observable.

## 🔭 En ce moment

- 🌍 **Correction des prévisions de qualité de l'air** — post-traitement de **CAMS Europe** aux stations françaises : 36 mois, 28 M d'enregistrements, 4 polluants. Le modèle corrige **là où il n'y a aucune station**, et c'est ainsi qu'il est évalué — station *et* mois cachés ensemble : **39,6 % d'erreur en moins sur le NO₂**. Brut, le produit européen ne passe le critère réglementaire **FAIRMODE** que sur 41,4 % des stations NO₂ ; corrigé, **96,2 %** — [code](https://github.com/cyril-bgs-dev-tech/correction-previsions-qualite-air) · [dossier, 63 pages](https://github.com/cyril-bgs-dev-tech/correction-previsions-qualite-air/blob/main/reports/figures/presentation_atmo.pdf)
- ⚙️ **Vigilance** — plateforme de détection d'anomalies temps réel : DAG event-driven 9 workers (Redis, Docker), 3 canaux de détection décorrélés, cycle de vie d'alarme en épisode unique, cockpit Streamlit 49 pages, code privé sur demande · [fiche projet](https://cyril-bgs-dev-tech.github.io/Portfolio/vigilance/)
- 🧪 **Multi-Agent-Lab** : laboratoire d'évaluation d'agents LLM 100 % locaux (RTX 5090). Mesurer ce que chaque brique d'un agent apporte vraiment face à une baseline, sous protocole préenregistré : **116 objectifs sur 200 clos**. Dernier résultat : pour choisir le bon skill, une décision typée du modèle bat un routeur classique (**84 sur 107 contre 41**) ; les résultats négatifs sont publiés comme tels. Code privé · [vitrine](https://github.com/cyril-bgs-dev-tech/multi-agent-lab) · [fiche projet](https://cyril-bgs-dev-tech.github.io/Portfolio/multi-agent-lab/)
- 🕵️ **Aegis-RCA** — agent LLM local de diagnostic de causes racines pour Vigilance : RAG sur procédures, sandbox d'auto-correction, décisions d'architecture mesurées (pas juste supposées) — [code](https://github.com/cyril-bgs-dev-tech/aegis-rca) · [fiche projet](https://cyril-bgs-dev-tech.github.io/Portfolio/aegis-rca/)
- 🔬 **Benchmarks de reproduction AD** — ADBench (tabulaire) & TSB-AD (séries temporelles) : reproduire exactement les scores publiés avant de prétendre les battre — VUS-PR, point-adjust banni, validation LODO — [anomaly_tabular](https://github.com/cyril-bgs-dev-tech/anomaly_tabular) · [anomaly_tsad](https://github.com/cyril-bgs-dev-tech/anomaly_tsad) (PaAno ICLR'26 certifié **#1 TSB-AD**)
- 🏆 **Kaggle** — 35+ compétitions, 3 top 1% mondial (meilleur rang : #14/3022)


## 📌 Où j'en suis

| projet | état | ce qui bouge |
|---|---|---|
| **Qualité de l'air** | ✅ visible | dossier de 63 pages, protocole en double aveugle, horizon réglementaire 2030 |
| **Vigilance** | ✅ fiche publique, code privé | plateforme MLOps temps réel, 9 workers, cockpit 49 pages |
| **Multi-Agent-Lab** | 🚧 en cours | 116/200 objectifs, forge de skills (lot F11) |
| **Aegis-RCA** | ✅ visible | agent LLM local de diagnostic, RAG sur procédures |
| **anomaly_tabular / anomaly_tsad** | ✅ visible | reproductions ADBench et TSB-AD |
| **Portfolio** | ✅ visible | [fiches projet détaillées](https://cyril-bgs-dev-tech.github.io/Portfolio/) |

## 🛠️ Stack

`Python` `Scikit-learn` `XGBoost` `PyTorch` `Polars` `Redis` `Docker` `Prometheus` `Grafana` `Streamlit` `SHAP`

---

<div align="center">

📫 **cyril.bgs.dev@gmail.com** · 🌐 [cyril-bgs-dev-tech.github.io/Portfolio](https://cyril-bgs-dev-tech.github.io/Portfolio/)

</div>
