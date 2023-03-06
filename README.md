# Project on the course "Theoretical Bioinformatics", MIPT 2021
## Authors:
* Marfa Zakirova
* Julia Dmitrieva
* Petr  Shatrov

## Introduction 
The Needleman–Wunsch algorithm is used in bioinformatics to align protein or nucleotide sequences. It was one of the first applications of dynamic programming to compare biological sequences. It is sometimes called the optimal matching algorithm and the global alignment technique. The Needleman–Wunsch algorithm is still widely used for optimal global alignment, mainly when the quality of the global alignment is paramount.  The algorithm assigns a score to every possible alignment, aiming to find all possible alignments with the highest score.

## Aim
We aim to implement one of the classical bioinformatics approaches for any two nucleotide or protein sequences. For protein sequence alignment, we use PAM 250 substitution matrix. As input, we use sequences in fasta format.

## Workflow
1. Constructing the grid
2. Choosing the scoring system
3. Filling in the matrix
4. Tracing arrows back to origin

## Results
The algorithm outputs one of the optimal alignment options in stdout.

