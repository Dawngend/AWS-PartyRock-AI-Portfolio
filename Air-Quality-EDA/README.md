# Air Quality Exploratory Data Analysis (EDA)

  ## 📊 Project Overview
  In this project, I utilized generative AI data ingestion pipelines to process and analyze a large-scale, 4,200+ row time-series environmental dataset containing telemetry on atmospheric pollutants.

  ## 🤖 Prompt Constraints & Analytical Execution
  To ensure absolute mathematical accuracy and prevent LLM hallucinations, I engineered rigid functional prompts:
  1. **Data Ingestion Constraint:** Forced the model to strictly isolate missing values (`NaN`) before executing descriptive statistics.
  2. **Mathematical Extraction:** Iteratively extracted the exact mathematical minimums, maximums, and rolling means for six distinct chemical variables ($CO$, $NO_2$, $O_3$, etc.).
  3. **Pattern Recognition:** Prompted the engine to cross-reference peaks with time-stamps to identify diurnal traffic emission fluctuations.
