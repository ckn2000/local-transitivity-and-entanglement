# local-transitivity-and-entanglement

Code associated to the paper "Local Transitivity and Entanglement Obstructions for Primitive Points" by Chi Nguyen, Arman Yagci, and Yunchuan Zhou.

## System requirements:
SageMath 10.4+.

## Dependencies:
David Roe's modified version of David Zywina's repository: https://github.com/roed314/OpenImage.git & https://github.com/davidzywina/OpenImage.git
Abbey Bourdon, Sachi Hashimoto, Timo Keller, Zev Klagsbrun, David Lowry-Duda, Travis Morrison, Filip Najman, and Himanshu Shukla's https://github.com/davidlowryduda/isolated_points.git.

The main file is ```sufficient_criteria.ipynb``` in ```src/primitive_points```.

Input is the image of the adelic Galois representation (can be computed using Zywina's algorithm and the level of the m-adic Galois representation) and the level of the m-adlic Galois representation (can be computed using Bourdon et al's algorithm).

## Specs:
These computations were done on an Apple Macbook Air (2022), with an M2 chip and 8GB of RAM.
