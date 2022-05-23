# SNOMED-CT MTP Validation
Supplementary Material of MIE conference paper _Validation of Multiple Path Translation (MTP)  for SNOMED CT localisation_  A. Prunotto, S. Schulz, and M. Boeker, IMBI Freiburg.

Upset Plots showing that a significant fraction of the terms matching the benchmarks are found only through TPs, but not by any DT. 

How to read these plots: The bottom-left panel (horizontal histogram) simply shows how many matches each TP has found. The big bottom panel shows all the possible combinations in which a matching term can be found: e.g. only by en-deepl-de,  MTP rank 1 and en-google-de  and so on. The central barplot displays the number of matches found in each combination (red bars indicate that those terms were found only by MTP at the related rank, but not by any DT ). Finally, the top boxplot shows how many words compose the terms that were found by that combination of TPs. Here I also include the result with Orphanet, which is a very big set and completely independent of the work made so far on MTP.


![image](https://user-images.githubusercontent.com/35369144/169818363-880d1b22-c89c-46d1-a911-0bfd3f6d5dcc.png)


![image](https://user-images.githubusercontent.com/35369144/169818408-d6052b1e-9fde-46d7-8372-bdae111d699b.png)
