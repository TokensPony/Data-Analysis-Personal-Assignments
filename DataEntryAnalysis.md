# Data Entry Analysis

## Data Organization Issues

1. Plotted charts feature no legend or labeling as to the meaning of their axes
2. Inconsistent Column names (z = depth, ColonySize = Colony Diameter, Density = Species #/L)
3. Missing data cells in files with no explanation for missing data or what to count it as. (Null, zero, etc)
4. No time information given as to when samples were observed/collected.
5. Unclear as to what the significance of "main" is in the file "zoop - temp-main" . This is does not seem to be the same data as seen in the "zoop - temp" file, but little info is given as to it's significance.  
6. File "zoop - temp" has a few meter(?) measures in the top left corner but I don't see clear indicators of their meaning or context.
7. "zoop - temp" has a small area where averages are being calculated with the plankton size. The calculations are split between the first and second halves of the data, with the only context being the "7th" and "9th" labels. Unclear as to their meaning? I think it's dates, but it's unclear.  

## Proposed Fixes
To address the issues with data set I put forth the following propositions for reorganization:
  
* Set better standard for column titles (Pick a name and stick with it)
* Include units of measurements in column titles
* Pick a designated description for empty cells (i.e. NULL) or provide some context on the page explaining the empty values.
* 
