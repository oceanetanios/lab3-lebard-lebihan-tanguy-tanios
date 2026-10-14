# Lab 3: Bottom-Up Steel Emissions with Uncertainty

Ines Lebard, Charlotte Le Bihan, Camille Tanguy, Oceane Tanios

## How to run

1. Install the packages:

   ```
   pip install pandas numpy matplotlib scipy openpyxl jupyter
   ```

2. Get the data: download the plant-level Global Iron and Steel Tracker from Global Energy Monitor (globalenergymonitor.org, free after a short form). We used the September 2026 (V1) release because we didn't find the 2025 version.

3. Put the file here, next to the notebook:

   ```
   gem-download/Plant-level data - Global Iron and Steel Tracker - September 2026 (V1).xlsx
   ```

   Or keep it anywhere and point to it with the `GIST_PATH` environment variable.

4. Open `lab3.ipynb` and run Kernel -> Restart & Run All.

## Notes

- The lab was written for the September 2025 release, so some column names differ (`GEM plant ID`, `Country/area`, `Parent (English)`) and our numbers won't exactly match the ones quoted in the questions.
- Official China production figures in B1 come from worldsteel (World Steel in Figures).
