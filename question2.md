# Student 2's Answer to Question 2

**Q2.** Assign variables to the individual components of your favorite gene! 
(e.g. promoter, 5' UTR, start codon, exon1, intron, exon2, stop codon, 3'UTR)
. Print the entire gene by using the string concatenation operator on the
standart output! Note: Feel free to create a fictional gene sequence by
randomly filling in the components.

```
promoter = "TATTAAATTAAAATT"
5_prime_UTR = "GTAATGTTGGGGAAAA"
start_codon = "ATG"
exon1 = "ATCCCGGGTTCGAACTG"
intron = "AATTTTTAAGGGGGAAAAA"
exon2 = "GCATTAGTCCAATGAAG"
stop_codon = "TAG"
3_prime_UTR = "AAAATTAAAAAAAAAAA"

my_fav_gene = promoter + 5_prime_UTR + start_codon + exon1 + \
	      intron + exon2 + stop_codon + 3_prime_UTR

print("My favorite gene sequence is as follows:")
print(my_fav_gene)
```
