# FairFace: Face Attribute Dataset for Balanced Race, Gender, and Age

The paper: https://arxiv.org/abs/1908.04913
Kärkkäinen, K., & Joo, J. (2019). FairFace: Face Attribute Dataset for Balanced Race, Gender, and Age. arXiv preprint arXiv:1908.04913.

## Code & model

https://github.com/dchen236/FairFace

## Data

Images (train + validation set): 
[\[Padding=0.25\]](https://drive.google.com/file/d/1Z1RqRo0_JiavaZw2yzZG6WETdZQ8qX86/view?usp=sharing), 
[\[Padding=1.25\]](https://drive.google.com/file/d/1g7qNOZz9wC7OfOhcPqH1EZ5bk1UFGmlL/view?usp=sharing)

* We used dlib's [get_face_chip()](http://dlib.net/python/index.html#dlib.get_face_chip) to crop and align faces with padding = 0.25 in the main experiments (less margin) and padding = 1.25 for the bias measument experiment for commercial APIs. 


Labels: 
[Train](https://drive.google.com/file/d/1i1L3Yqwaio7YSOCj7ftgk8ZZchPG7dmH/view?usp=sharing)
[Validation](https://drive.google.com/file/d/1wOdja-ezstMEp81tX1a-EYkFebev4h7D/view?usp=sharing)


License: CC BY 4.0
