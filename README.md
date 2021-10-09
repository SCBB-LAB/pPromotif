# pPromotif
A novel and accurate algorithm to identify Transcription Factor Binding Sites on plant genomic sequences. 
pPromotif is a tool to find most significant transcription factor binding sites (TFBS) on plant genomic sequences. pPromotif, was extended and developed from its previous implementation for animal system (Shankar et al 2004). A total of 57 different transcription factors were modeled into this tool. The accuracy of the tool is found to be 90.91%.


1.System requirement
2.Input file format
3.Output file format
4.Command line
5.References

1.System requirement:
pPromotif requires Java Runtime Environment (JRE) to installed. As the program is developed in java, pPromotif can be run on any O.S having JRE. pPromotif is tested on ubuntu 12.04 and cent O.S 5.5.

2.Input file format
pPromotif requires input file in fasta format. Single or multiple sequences in batch can be submitted to the program

3.Output file format
pPromotif gives two output files first file contains all the TFBS on sequence(s) submitted while the other (final output) file gives the most significant TFBS on the sequence(s).

4.Command line
To run pPromotif open terminal and run the below given command 
“java -jar pPromotif input-file output-file-all final-output-file”

5.References:
If you use this tool please cite the following:
1. Jha A and ShankarR 2014 miRNAting control of DNA methylation, J Biosci.
2. Shankar R, Grover D, Brahmachari SK and Mukerji M 2004 Evolution and distribution of RNA polymerase II regulatory sites from RNA polymerase III dependent mobile Alu elements, BMC Evol. Biol. 4 4:37.
