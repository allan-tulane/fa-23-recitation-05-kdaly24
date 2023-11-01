# CMPS 2200 Recitation 6
## Answers

**Name:**______Killian Daly______


Place all written answers from `recitation-06.md` here for easier grading.



- **d.**

File            | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
---------------------------------------------------------------------------------
f1.txt          |       1340          |     826        |  1.6223
alice29.txt     |       1039367       |     676374     |  1.5367
asyoulik.txt    |       876253        |     606448     |  1.4449
grammar.lsp     |       26047         |     17356      |  1.5007
fields.c        |       78050         |     56206      |  1.3886

This ratio tells us that the Fixed Length Coding is about 1.4 / 1.5 times the cost of Huffman coding. This is a trend that occurs with multiple files in different coding languages and sizes of text. With this, we can assume that Huffman coding has about a 33% cost reduction from fixed length coding, and that most of the the time, Huffman coding is more efficient.


- **e.**

If we assume that each character has the same frequency, that will mean that the tree is balanced.
With this in mind, we can then take the cost per level as n, which will be consistent as its the same frequency, and depth of tree logn. 
As a balanced cost is depth of tree * cost per level, we can find it to be $n \log n $.

