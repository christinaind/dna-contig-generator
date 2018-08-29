# Contig Generation

This is the repository for mapping the set of overlapping DNA sequences. Program first reads the list of k-mers from the file, create the de brujin graph and generate contigs through finding maximal non-branching paths.

Generated contigs are written in contigs.txt file, no libraries required.

An example run: python create_contig.py test-input.txt
