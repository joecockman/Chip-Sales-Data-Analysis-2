# Chip-Sales-Data-Analysis-2

Part 2 of the Quantium virtual internship. The task was to investigate the success of a new trial layout in 3 of the stores from February to the end of April.

To best assess the impact of the new layout on store performance, I selected a control store for each of the three trial stores using Euclidean distance analysis.

I created a function named 'find_best_control_distance()' that compared each of the trial stores against each of the nearly 300 other stores across 6 key metrics. The store with the smallest Euclidean distance store to the trial store was deemed the most similar and thus was selected to be the control store.

Having a control store helped us to confirm if any notable change in trial store performance was due to chance.

I used python to complete this project.

My work can be found in the file repository in both ipynb form and PDF form. the dataset can also be found there.

![Crisps](crisps.jpg)
