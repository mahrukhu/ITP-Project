This program takes single letter aminoacid sequence as input and produces a hydropathy plot based on the Kyte Doolittle values assigned 
to amino acids. The idea of a window size is to make the analysis more flexible. The user will enter a number which is an integer, say, n
and the program will consider the first n amino acids compute an average value for hydrophobicity in that area using the amino acids
included in the window and assign it to the ‘middle’ amino acid. The window will then move by one amino acid (in this case the second)
and the program will execute the same steps for the next window which now contains one new amino acid, a new ‘middle’ amino acid but is
of the same size, n. The finer details of this process are described in the following paragraphs, but it should be noted that typically
for Kyte Doolittle plots window sizes of around 19 to 22 are considered for the determination of possible transmembrane regions and smaller
window sizes such as 5-7 can be used to determine surface exposed regions of proteins.

No installation is required. To use this run the jupyter notebook or any text editor such as atom or sublime text.
