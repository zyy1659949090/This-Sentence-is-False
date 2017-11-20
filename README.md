# This-Sentence-is-False

This Sentence is False

Description

The court of King Xeon 2.4 is plagued with intrigue and conspiracy. A document recently discovered by the King's Secret Service is thought to be part of some mischievous scheme. The document contains simply a set of sentences which state the truth or falsehood of each other. Sentences have the form "Sentence X is true/false" where X identifies one sentence in the set. The King's Secret Service suspects the sentences in fact refer to another, yet uncovered, document. 
While they try to establish the origin and purpose of the document, the King ordered you to find whether the set of sentences it contains is consistent, that is, if there is a valid truth assignment for the sentences. If the set is consistent, the King wants you to determine the maximum number of sentences which can be made true in a valid truth assignment for the document.

Input

The input contains several instances of documents. Each document starts with a line containing a single integer, 
N, which indicates the number of sentences in the document (1 <= N <= 1000). The following N lines contain each a sentence. Sentences are numbered sequentially, in the order they appear in the input (the first is sentence 1, the second is sentence 2, and so on). Each sentence has the form "Sentence X is true." or "Sentence X is false.", where 1 <= X <= N. The value N = 0 indicates the end of input.

Output

For each document in the input your program should output one line. If the document is consistent,your program should print the maximum number of sentences in a valid truth assignment for the document.Otherwise your program should print the word 'Inconsistent'.

Sample Input

1
Sentence 1 is false.
1
Sentence 1 is true.
5
Sentence 2 is false.
Sentence 1 is false.
Sentence 3 is true.
Sentence 3 is true.
Sentence 4 is false.
0

Sample Output

Inconsistent
1
3
