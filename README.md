# DAA-Miniproject
Robin Karp Algorithm and Naive String Matching Algorithm

Difference between Robin Karp and Naive string matching:
The Rabin-Karp algorithm slides the pattern one by one. But unlike the Naive algorithm, the
Rabin Karp algorithm matches the hash value of the pattern with the hash value of the current
substring of text, and if the hash values match then only it starts matching individual characters. So
the Rabin Karp algorithm needs to calculate hash values for the following strings.
1. Pattern itself
2. All the substrings of the text of length m
