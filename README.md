# root-rubber-seal
An assignment for school — in Java — to explore merkle trees, and their application in checking data integrity.

<sup>If you’re here looking for a way to hash/get-the-checksum-of directories, you should check out my C++ library [*“sealdir”*](https://github.com/mavenor/sealdir), which is also based on **Merkle trees**</sup>

## Contents
- [root-rubber-seal](#root-rubber-seal)
  - [Contents](#contents)
  - [Introduction](#introduction)
  - [Algorithmically Maintaining a Merkle Tree](#algorithmically-maintaining-a-merkle-tree)
  - [Illustrations](#illustrations)
  - [References](#references)

## Introduction
If one takes all tree data structures for comparison, **Merkle trees are rather unique**; their **leaves differ from all internal nodes**, in structure.
As a matter of fact, Merkle trees are data structures hold hashes of data, and the main focus is not the data itself — thus arises the difference; they **only hold actual data at their leaf nodes.**  
In fact, the principle of the Merkle tree is to hierarchically hash data, such that **every node** (except all leaf nodes) **is labelled with a hash of its children.**

## Algorithmically Maintaining a Merkle Tree
## Illustrations
## References
- Ralph C. Merkle’s 1979 whitepaper — [“A Certified Digital Signature”](http://www.merkle.com/papers/Certified1979.pdf)
- [Szydlo, M. (2004). Merkle Tree Traversal in Log Space and Time.](https://rdcu.be/cMAe3) In: Cachin, C., Camenisch, J.L. (eds) Advances in Cryptology - EUROCRYPT 2004. EUROCRYPT 2004. Lecture Notes in Computer Science, vol 3027. Springer, Berlin, Heidelberg. https://doi.org/10.1007/978-3-540-24676-3_32
