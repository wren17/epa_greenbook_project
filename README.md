# EPA Greenbook Nonattainment Status, Pollution, and Economic Activities
*Wuyang Ren and Kitty Wu*
## Summary

Our paper (see **`report.pdf`**) examines how more stringent environmental regulation affects
both **economic activity** and **pollution**, using an EPA **nonattainment designation** as the policy shock. We study the Rust Belt with a focus on **Wayne County, Michigan (2001–2010)**, treating **2005** (Wayne’s first appearance on the nonattainment list) as the treatment year. Using **TWFE** and **synthetic control** approaches, we find a significant decline in **overall GDP**, but limited evidence that the decline is driven by the manufacturing industry or that measured emissions fall meaningfully over the sample period.

This repository provides the **code and data** used for the analysis in the paper.

1. **Run the data cleaning notebook first**
   - Location: `data/cleaning.ipynb`
   - This notebook cleans/prepares the raw inputs.
   - **All data used in this project are stored in the `data/` folder.**

2. **Run the main analysis**
   - Notebook: `analysis.ipynb`
   - This contains the core analysis, results, and figures.

