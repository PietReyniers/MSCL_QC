# MSCL_QC
A little piece of software to check the quality and completeness of the data measured with the GeoTEK MSCL at the RCMG at Ghent University.
Additionally, blank lines introduced in error during export from the MSCL software are removed. 

## Input
In the MSCL_QC.py, change the paths in the input file location section:
- source_path: location of the text-based file, as exported from the MSCL software
- output_path: folder to store processed files
- sections_path: text file with the order in which the sections have been measured, each section on a new line. See scan_order.txt as an example.
  
## Output
For each section:
- *.csv with the MSCL data without blank lines
- *.png with an overview of the data, to verify if the dataset is complete. 
