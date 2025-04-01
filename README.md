# happyvariantcall
Parsing vcf output from hap.py 

- parse through vcf output from hap.py to collect information on false positives and false negatives (chr, pos, SNP/INDEL)
- With false positive/negative information, return to Clair3 output to collect read depth and variant quality scores.
- comparison of variant quality score and depth of true & false positives in order to find a threshold for filtering false positives. 
