Medium Article Link - https://medium.com/@dhshah1112/a-market-based-approach-to-social-cost-in-multi-agent-reinforcement-learning-61e0f720be05

Video Link : https://drive.google.com/drive/folders/1FBa9UrAMEfdtviSSChKySCeVAbbb6xw-?usp=sharing

# A Market-Based Approach to Social Cost in Multi-Agent Reinforcement Learning

This repository contains a Medium article and a LaTeX Beamer presentation exploring the application of market-based mechanisms, specifically Vickrey-Clarke-Groves (VCG) auctions, to address social costs in multi-agent reinforcement learning (MARL) systems. The work is based on the survey paper "[The Problem of Social Cost in Multi-Agent General Reinforcement Learning: Survey and Synthesis]" by Ng, Yang-Zhao, and Cadogan-Cowper.

## Contents

* **`presentation.tex`**:  LaTeX source code for the Beamer presentation.  Compile this file with a LaTeX distribution (like TeX Live or MiKTeX) to generate the PDF slides (`presentation.pdf`).
* **`presentation.pdf`**: The compiled presentation slides.
* **`medium_article.md`**: Markdown source for the Medium article.  This file can be copied directly into Medium's editor or converted to other formats (e.g., PDF) as needed.
* **`medium_article.pdf`**: (Optional)  A PDF version of the Medium article.


## Overview

Multi-agent reinforcement learning involves multiple AI agents learning simultaneously in a shared environment. This interaction can lead to *social costs* or *negative externalities* where an individual agent's actions negatively impact other agents without the acting agent bearing the full consequences. This project explores how mechanism design, specifically VCG auctions, can be integrated into MARL systems to internalize these social costs and promote more cooperative and socially beneficial outcomes.

The presentation and Medium article provide a summarized and accessible explanation of the following key concepts:

* **Multi-agent Reinforcement Learning (MARL):**  Challenges and the problem of social cost.
* **Mechanism Design and VCG Auctions:**  How VCG auctions incentivize truthful reporting and efficient outcomes.
* **The Proposed Framework:** Integrating VCG mechanisms into the MARL loop.
* **Learning in the Presence of Social Cost:**  Addressing the exploration-exploitation dilemma and adapting learning algorithms.
* **Applications:**  Examples of how the framework can be applied to various domains like AI safety, resource allocation, and cybersecurity.
* **Limitations and Future Work:**  Open questions and potential research directions.


## Usage

1. **Presentation:**  To view the presentation, simply open `presentation.pdf`.  To modify the presentation, edit `presentation.tex` and recompile it using a LaTeX distribution.
2. **Medium Article:** To read the article, open `medium_article.md` or `medium_article.pdf`. The `.md` file can be copied into a Medium editor for publishing.

## Dependencies (for the presentation)

* A LaTeX distribution (e.g., TeX Live, MiKTeX)
* The Beamer package (usually included with LaTeX distributions)
* The `xcolor` package (for colored text)


## Acknowledgements

This project is based on the research paper:

* Ng, K. S., Yang-Zhao, S., & Cadogan-Cowper, T. (2024). The Problem of Social Cost in Multi-Agent General Reinforcement Learning: Survey and Synthesis. *arXiv preprint arXiv:2412.02091*.

## License

[Choose a license - e.g., MIT License](LICENSE)  (Create a LICENSE file with the license text).
