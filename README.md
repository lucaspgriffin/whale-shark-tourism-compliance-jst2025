# 2025 Whale Shark Tourism Compliance Analysis

[![DOI](https://img.shields.io/badge/DOI-10.1080%2F09669582.2025.2593421-blue)](https://doi.org/10.1080/09669582.2025.2593421)

## Publication

**Compliance challenges with tourism at the world's largest whale shark aggregation site**

*Hoa T. T. Ninh¹, Curtice R. Griffin¹, Rafael de la Para-Venegas², Kimberly L. Ovitz³, Andy J. Danylchuk¹, Lucas P. Griffin⁴*

Published in *Journal of Sustainable Tourism* (2025)

¹ Department of Environmental Conservation, University of Massachusetts Amherst, Amherst, MA 01003, USA  
² Ch'ooj Ajuail AC, Cancún, Quintana Roo 77509, México  
³ Centre for Earth Observation Sciences and Department of Environment and Geography, University of Manitoba, Winnipeg, R3T 2N2, Canada  
⁴ Department of Integrative Biology, University of South Florida, FL 33620, USA

## Abstract

This repository contains the data analysis code and supplementary materials for the published research on whale shark tourism compliance at Isla Mujeres, Mexico. The study compares tourism compliance patterns between 2016 and 2022 using aerial video surveys.

## Repository Contents

- `whale_shark_analysis.Rmd` - Main R Markdown analysis script
- `whale_shark_analysis.html` - Compiled HTML analysis report
- `whale_shark_data/` - Data files (CSV format)
- `outputs/` - Generated analysis outputs and figures

## Key Findings

- 96% increase in total video surveillance time between study periods
- Significant increases in swimmer density and violations
- Limited effectiveness of patrol boat enforcement
- Predictive models for violation frequency based on encounter characteristics

## Requirements

### R and RStudio
- R version 4.0 or higher
- RStudio (recommended for viewing R Markdown files)

### Required R Packages
```r
install.packages(c("mgcv", "mgcViz", "dplyr", "ggplot2", 
                   "cowplot", "lubridate", "viridis", "knitr"))
```

## Reproducibility

1. Clone this repository:
   ```bash
   git clone https://github.com/lucaspgriffin/whale-shark-tourism-compliance-jst2025.git
   ```

2. Open `whale_shark_analysis.Rmd` in RStudio

3. Knit to HTML to reproduce all analyses and figures

## Repository URL

This repository is available at: https://github.com/lucaspgriffin/whale-shark-tourism-compliance-jst2025

## Citation

```bibtex
@article{ninh2025whale,
  title={Compliance challenges with tourism at the world's largest whale shark aggregation site},
  author={Ninh, Hoa TT and Griffin, Curtice R and de la Para-Venegas, Rafael and Ovitz, Kimberly L and Danylchuk, Andy J and Griffin, Lucas P},
  journal={Journal of Sustainable Tourism},
  year={2025},
  publisher={Taylor \& Francis},
  doi={10.1080/09669582.2025.2593421}
}
```

## Contact

For questions about the analysis or data, please contact:
- Lucas P. Griffin: lpgriffin@usf.edu
- Hoa T. T. Ninh: [email]

## License

Code is available under MIT License. Data usage should cite the original publication.

