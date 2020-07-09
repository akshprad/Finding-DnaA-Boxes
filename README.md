# Finding-DnaA-Boxes
Finding DnaA Boxes in Salmonella Typhimunium

To find DnaA Boxes in E.Coli, we start off by finding the most frequent 9-mers with mismatches and reverse complements in the region suggested by the minimum skew as the Ori. 
Similarly, for Salmonella Typhimunium, we will

1. Use Minimum Skew to find the approximate location of OriC.
2. Use MostFreqWithMismatches&ReverseComplement to find the most frequent 9-mers in the area returned by MinimumSkew.
3. Compare these with DnaA boxes found in E.Coli to see which one looks closest.
