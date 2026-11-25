# Palmer penguins | Body mass and flipper length
2323 CIS · Introduction to Data Sciences · Group lab project

How do mass and flipper length differ among Adelie, Chinstrap and Gentoo, and how does the mass–length relationship change when species are analyzed separately?

## Reproduce the results
1. Extract the entire project, preserving its folders. Open a terminal in the folder containing this README.
2. Install the analysis packages with `python -m pip install -r requirements.txt` and install Jupyter with `python -m pip install jupyterlab`.
3. Run `python -m jupyterlab`, open `Palmer_Analysis.ipynb`, then select Restart Kernel and Run All Cells. The bundled source CSV supports an offline analysis after installation.
4. Inspect the regenerated files in outputs/. The notebook includes the data-quality audit, transformations, three figures, interpretations and limitations. The editable presentation includes speaker notes.

## Data source
Horst AM, Hill AP & Gorman KB (2020). palmerpenguins: Palmer Archipelago (Antarctica) penguin data. DOI: https://doi.org/10.5281/zenodo.3960218.
Source CSV: https://github.com/allisonhorst/palmerpenguins/blob/main/inst/extdata/penguins.csv
Field study: Gorman KB, Williams TD & Fraser WR (2014). https://doi.org/10.1371/journal.pone.0090081
The bundled CSV contains field observations from 2007–2009, distributed by palmerpenguins under CC0.

## Results
342 of 344 observations have the required measurements. Gentoo median mass is 5.0 kg versus 3.7 kg for each of the other species. Median flipper lengths are 216, 196 and 190 mm for Gentoo, Chinstrap and Adelie, respectively. The pooled correlation (0.87) exceeds the within-species correlations (0.47–0.70). Findings describe the sampled birds.

## Team contributions and peer review
Complete with actual names and work before submission. Each member should review another member’s section and record the check performed.

| Member | Contribution completed | Section reviewed / check performed |
|---|---|---|
| Waf Ibrahim | | |
| Fajr Hamadani | | |
| Noorah Assiri | | |
| Amjad Abdullah | | |
| Atheer Ali Alshehri | | |
