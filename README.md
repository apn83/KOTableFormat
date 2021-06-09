# KOTableFormat
Kegg orthology database in table format

KO database offers the annotation in text format and json format

It will be useful to have the level files as a table/data frame format for downstream analysis

1. ko00001.keg is the raw file downloaded from KEGG
2. Open the file in text editor
3. Remove #, comment lines
4. Replace 6 spaces in level D, 2 spaces between KO and Annotation to *tab*
5. Open the file in Excel
6. Create 3 new columns for level A, B & C
7. Filter first column and choose "Begins with A"
8. 8 top level will appear -> copy it to column in level A
9. Repeat the process for B & C
10. Use a language of your choice to forward fill
11. ko00001.leveled.tsv is the new level spread file.

Caution: Always cross-check output with number of entries with original file. Replaces in text file can cause unintended errors in huge files.

