(base) sigilwen@MacBook-Pro-87 FHE with lattigo % go run main
============================================
Homomorphic computations on batched integers
============================================

Parameters : N=8192, T=65929217, Q = 218 bits, sigma = 3.200000 

Generating 2048 driversData and 1 Rider randomly positioned on a grid of 8119 x 8119 units 

Encrypting 2048 driversData (x, y) and 1 Rider (5490, 4132) 

Computing encrypted distance = ((CtD1 + CtD2 + CtD3 + CtD4...) - CtR)^2 ...

Distance with Driver 0 :  7123010 = (3379 - 5490)^2 + (2499 - 4132)^2 --> correct: true
Distance with Driver 1 :  1948733 = (6877 - 5490)^2 + (3974 - 4132)^2 --> correct: true
Distance with Driver 2 : 14440153 = (3117 - 5490)^2 + (1164 - 4132)^2 --> correct: true
Distance with Driver 3 : 20454800 = (2306 - 5490)^2 + ( 920 - 4132)^2 --> correct: true
...
Distance with Driver 2044 :  7899257 = (3194 - 5490)^2 + (2511 - 4132)^2 --> correct: true
Distance with Driver 2045 : 17076361 = (1530 - 5490)^2 + (5313 - 4132)^2 --> correct: true
Distance with Driver 2046 : 31697609 = ( 943 - 5490)^2 + ( 812 - 4132)^2 --> correct: true
Distance with Driver 2047 : 16831252 = (4596 - 5490)^2 + ( 128 - 4132)^2 --> correct: true

Finished with 0.00% errors

Closest Driver to Rider is n°334 (5466, 4138) with a distance of 24 units