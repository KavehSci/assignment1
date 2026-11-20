# Kemal's Answer to Question 2

**Q2.** Assign variables to the individual components of your favourite gene (e.g promoter, 5' UTR, start codon, exon1, intron, exon2, stop codon, 3' UTR). Print the entire gene by using the string concatenation operator on the standard output! Note: Feel free to create a fictional gene sequence by randomly filling in the components.

**Answer:**

```
promoter = "CCGTATAAAGGC"
five_prime_UTR = "ACTGCCACC"
start_codon = "ATG"
exon1 = "GACCTC"
intron = "GTAAGTGCTAGACTCAG"
exon2 = "GGTTGG"
stop_codon = "TAA"
three_prime_UTR = "CGCAATAAAGGC"

my_favorite_gene = promoter + five_prime_UTR + start_codon + exon1 + intron + exon2 + stop_codon + three_prime_UTR
print("my_favorite_gene sequence is as follows")
print(my_favorite_gene)
```
