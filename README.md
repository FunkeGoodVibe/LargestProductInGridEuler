# LargestProductInGridEuler
# In the 20×20 grid below, four numbers along a diagonal line have been marked in red.

 08 02 22 97 38 15 00 40 00 75 04 05 07 78 52 12 50 77 91 08 <br/><br/>
 49 49 99 40 17 81 18 57 60 87 17 40 98 43 69 48 04 56 62 00<br/><br/>
 81 49 31 73 55 79 14 29 93 71 40 67 53 88 30 03 49 13 36 65<br/><br/>
52 70 95 23 04 60 11 42 69 24 68 56 01 32 56 71 37 02 36 91<br/><br/>
22 31 16 71 51 67 63 89 41 92 36 54 22 40 40 28 66 33 13 80<br/><br/>
24 47 32 60 99 03 45 02 44 75 33 53 78 36 84 20 35 17 12 50<br/><br/>
32 98 81 28 64 23 67 10 26 38 40 67 59 54 70 66 18 38 64 70<br/><br/>
67 26 20 68 02 62 12 20 95 63 94 39 63 08 40 91 66 49 94 21<br/><br/>
24 55 58 05 66 73 99 26 97 17 78 78 96 83 14 88 34 89 63 72<br/><br/>
21 36 23 09 75 00 76 44 20 45 35 14 00 61 33 97 34 31 33 95<br/><br/>
78 17 53 28 22 75 31 67 15 94 03 80 04 62 16 14 09 53 56 92<br/><br/>
16 39 05 42 96 35 31 47 55 58 88 24 00 17 54 24 36 29 85 57<br/><br/>
86 56 00 48 35 71 89 07 05 44 44 37 44 60 21 58 51 54 17 58<br/><br/>
19 80 81 68 05 94 47 69 28 73 92 13 86 52 17 77 04 89 55 40<br/><br/>
04 52 08 83 97 35 99 16 07 97 57 32 16 26 26 79 33 27 98 66<br/><br/>
88 36 68 87 57 62 20 72 03 46 33 67 46 55 12 32 63 93 53 69<br/><br/>
04 42 16 73 38 25 39 11 24 94 72 18 08 46 29 32 40 62 76 36<br/><br/>
20 69 36 41 72 30 23 88 34 62 99 69 82 67 59 85 74 04 36 16<br/><br/>
20 73 35 29 78 31 90 01 74 31 49 71 48 86 81 16 23 57 05 54<br/><br/>
01 70 54 71 83 51 54 69 16 92 33 48 61 43 52 01 89 19 67 48<br/><br/>

The product of these numbers is 26 × 63 × 78 × 14 = 1788696.

What is the greatest product of four adjacent numbers in the same direction (up, down, left, right, or diagonally) in the 20×20 grid?


### Testing by printing output to screen

HORIZONTAL 4 POINTS: 
Start: [0,0] 
Second:[0,1] 
Third: [0,2] 
Forth: [0,3]
Current result for starting position [0,0] (vertically) is: 34144
The values are 08 * 02 * 22 * 97 = 34144
The current maximum result is 34144 


HORIZONTAL 4 POINTS: 
Start: [0,1] 
Second:[0,2] 
Third: [0,3] 
Forth: [0,4]
Current result for starting position [0,1] (vertically) is: 162184
The values are 02 * 22 * 97 * 38 = 162184
The current maximum result is 162184 


HORIZONTAL 4 POINTS: 
Start: [0,2] 
Second:[0,3] 
Third: [0,4] 
Forth: [0,5]
Current result for starting position [0,2] (vertically) is: 1216380
The values are 22 * 97 * 38 * 15 = 1216380
The current maximum result is 1216380 


HORIZONTAL 4 POINTS: 
Start: [0,3] 
Second:[0,4] 
Third: [0,5] 
Forth: [0,6]
Current result for starting position [0,3] (vertically) is: 0
The values are 97 * 38 * 15 * 0 = 0
HORIZONTAL 4 POINTS: 
Start: [0,4] 
Second:[0,5] 
Third: [0,6] 
Forth: [0,7]
Current result for starting position [0,4] (vertically) is: 0
The values are 38 * 15 * 0 * 40 = 0
HORIZONTAL 4 POINTS: 
Start: [0,5] 
Second:[0,6] 
Third: [0,7] 
Forth: [0,8]
Current result for starting position [0,5] (vertically) is: 0
The values are 15 * 0 * 40 * 0 = 0
HORIZONTAL 4 POINTS: 
Start: [0,6] 
Second:[0,7] 
Third: [0,8] 
Forth: [0,9]
Current result for starting position [0,6] (vertically) is: 0
The values are 0 * 40 * 0 * 75 = 0
HORIZONTAL 4 POINTS: 
Start: [0,7] 
Second:[0,8] 
Third: [0,9] 
Forth: [0,10]
Current result for starting position [0,7] (vertically) is: 0
The values are 40 * 0 * 75 * 04 = 0
HORIZONTAL 4 POINTS: 
Start: [0,8] 
Second:[0,9] 
Third: [0,10] 
Forth: [0,11]
Current result for starting position [0,8] (vertically) is: 0
The values are 0 * 75 * 04 * 05 = 0
HORIZONTAL 4 POINTS: 
Start: [0,9] 
Second:[0,10] 
Third: [0,11] 
Forth: [0,12]
Current result for starting position [0,9] (vertically) is: 10500
The values are 75 * 04 * 05 * 07 = 10500
HORIZONTAL 4 POINTS: 
Start: [0,10] 
Second:[0,11] 
Third: [0,12] 
Forth: [0,13]
Current result for starting position [0,10] (vertically) is: 10920
The values are 04 * 05 * 07 * 78 = 10920
HORIZONTAL 4 POINTS: 
Start: [0,11] 
Second:[0,12] 
Third: [0,13] 
Forth: [0,14]
Current result for starting position [0,11] (vertically) is: 141960
The values are 05 * 07 * 78 * 52 = 141960
HORIZONTAL 4 POINTS: 
Start: [0,12] 
Second:[0,13] 
Third: [0,14] 
Forth: [0,15]
Current result for starting position [0,12] (vertically) is: 340704
The values are 07 * 78 * 52 * 12 = 340704
HORIZONTAL 4 POINTS: 
Start: [0,13] 
Second:[0,14] 
Third: [0,15] 
Forth: [0,16]
Current result for starting position [0,13] (vertically) is: 2433600
The values are 78 * 52 * 12 * 50 = 2433600
The current maximum result is 2433600 


HORIZONTAL 4 POINTS: 
Start: [0,14] 
Second:[0,15] 
Third: [0,16] 
Forth: [0,17]
Current result for starting position [0,14] (vertically) is: 2402400
The values are 52 * 12 * 50 * 77 = 2402400
HORIZONTAL 4 POINTS: 
Start: [0,15] 
Second:[0,16] 
Third: [0,17] 
Forth: [0,18]
Current result for starting position [0,15] (vertically) is: 4204200
The values are 12 * 50 * 77 * 91 = 4204200
The current maximum result is 4204200 


HORIZONTAL 4 POINTS: 
Start: [0,16] 
Second:[0,17] 
Third: [0,18] 
Forth: [0,19]
Current result for starting position [0,16] (vertically) is: 2802800
The values are 50 * 77 * 91 * 08 = 2802800
HORIZONTAL 4 POINTS: 
Start: [1,0] 
Second:[1,1] 
Third: [1,2] 
Forth: [1,3]
Current result for starting position [1,0] (vertically) is: 9507960
The values are 49 * 49 * 99 * 40 = 9507960
The current maximum result is 9507960 


HORIZONTAL 4 POINTS: 
Start: [1,1] 
Second:[1,2] 
Third: [1,3] 
Forth: [1,4]
Current result for starting position [1,1] (vertically) is: 3298680
The values are 49 * 99 * 40 * 17 = 3298680
HORIZONTAL 4 POINTS: 
Start: [1,2] 
Second:[1,3] 
Third: [1,4] 
Forth: [1,5]
Current result for starting position [1,2] (vertically) is: 5452920
The values are 99 * 40 * 17 * 81 = 5452920
HORIZONTAL 4 POINTS: 
Start: [1,3] 
Second:[1,4] 
Third: [1,5] 
Forth: [1,6]
Current result for starting position [1,3] (vertically) is: 991440
The values are 40 * 17 * 81 * 18 = 991440
HORIZONTAL 4 POINTS: 
Start: [1,4] 
Second:[1,5] 
Third: [1,6] 
Forth: [1,7]
Current result for starting position [1,4] (vertically) is: 1412802
The values are 17 * 81 * 18 * 57 = 1412802
HORIZONTAL 4 POINTS: 
Start: [1,5] 
Second:[1,6] 
Third: [1,7] 
Forth: [1,8]
Current result for starting position [1,5] (vertically) is: 4986360
The values are 81 * 18 * 57 * 60 = 4986360
HORIZONTAL 4 POINTS: 
Start: [1,6] 
Second:[1,7] 
Third: [1,8] 
Forth: [1,9]
Current result for starting position [1,6] (vertically) is: 5355720
The values are 18 * 57 * 60 * 87 = 5355720
HORIZONTAL 4 POINTS: 
Start: [1,7] 
Second:[1,8] 
Third: [1,9] 
Forth: [1,10]
Current result for starting position [1,7] (vertically) is: 5058180
The values are 57 * 60 * 87 * 17 = 5058180
HORIZONTAL 4 POINTS: 
Start: [1,8] 
Second:[1,9] 
Third: [1,10] 
Forth: [1,11]
Current result for starting position [1,8] (vertically) is: 3549600
The values are 60 * 87 * 17 * 40 = 3549600
HORIZONTAL 4 POINTS: 
Start: [1,9] 
Second:[1,10] 
Third: [1,11] 
Forth: [1,12]
Current result for starting position [1,9] (vertically) is: 5797680
The values are 87 * 17 * 40 * 98 = 5797680
HORIZONTAL 4 POINTS: 
Start: [1,10] 
Second:[1,11] 
Third: [1,12] 
Forth: [1,13]
Current result for starting position [1,10] (vertically) is: 2865520
The values are 17 * 40 * 98 * 43 = 2865520
HORIZONTAL 4 POINTS: 
Start: [1,11] 
Second:[1,12] 
Third: [1,13] 
Forth: [1,14]
Current result for starting position [1,11] (vertically) is: 11630640
The values are 40 * 98 * 43 * 69 = 11630640
The current maximum result is 11630640 


HORIZONTAL 4 POINTS: 
Start: [1,12] 
Second:[1,13] 
Third: [1,14] 
Forth: [1,15]
Current result for starting position [1,12] (vertically) is: 13956768
The values are 98 * 43 * 69 * 48 = 13956768
The current maximum result is 13956768 


HORIZONTAL 4 POINTS: 
Start: [1,13] 
Second:[1,14] 
Third: [1,15] 
Forth: [1,16]
Current result for starting position [1,13] (vertically) is: 569664
The values are 43 * 69 * 48 * 04 = 569664
HORIZONTAL 4 POINTS: 
Start: [1,14] 
Second:[1,15] 
Third: [1,16] 
Forth: [1,17]
Current result for starting position [1,14] (vertically) is: 741888
The values are 69 * 48 * 04 * 56 = 741888
HORIZONTAL 4 POINTS: 
Start: [1,15] 
Second:[1,16] 
Third: [1,17] 
Forth: [1,18]
Current result for starting position [1,15] (vertically) is: 666624
The values are 48 * 04 * 56 * 62 = 666624
HORIZONTAL 4 POINTS: 
Start: [1,16] 
Second:[1,17] 
Third: [1,18] 
Forth: [1,19]
Current result for starting position [1,16] (vertically) is: 0
The values are 04 * 56 * 62 * 0 = 0
HORIZONTAL 4 POINTS: 
Start: [2,0] 
Second:[2,1] 
Third: [2,2] 
Forth: [2,3]
Current result for starting position [2,0] (vertically) is: 8981847
The values are 81 * 49 * 31 * 73 = 8981847
HORIZONTAL 4 POINTS: 
Start: [2,1] 
Second:[2,2] 
Third: [2,3] 
Forth: [2,4]
Current result for starting position [2,1] (vertically) is: 6098785
The values are 49 * 31 * 73 * 55 = 6098785
HORIZONTAL 4 POINTS: 
Start: [2,2] 
Second:[2,3] 
Third: [2,4] 
Forth: [2,5]
Current result for starting position [2,2] (vertically) is: 9832735
The values are 31 * 73 * 55 * 79 = 9832735
HORIZONTAL 4 POINTS: 
Start: [2,3] 
Second:[2,4] 
Third: [2,5] 
Forth: [2,6]
Current result for starting position [2,3] (vertically) is: 4440590
The values are 73 * 55 * 79 * 14 = 4440590
HORIZONTAL 4 POINTS: 
Start: [2,4] 
Second:[2,5] 
Third: [2,6] 
Forth: [2,7]
Current result for starting position [2,4] (vertically) is: 1764070
The values are 55 * 79 * 14 * 29 = 1764070
HORIZONTAL 4 POINTS: 
Start: [2,5] 
Second:[2,6] 
Third: [2,7] 
Forth: [2,8]
Current result for starting position [2,5] (vertically) is: 2982882
The values are 79 * 14 * 29 * 93 = 2982882
HORIZONTAL 4 POINTS: 
Start: [2,6] 
Second:[2,7] 
Third: [2,8] 
Forth: [2,9]
Current result for starting position [2,6] (vertically) is: 2680818
The values are 14 * 29 * 93 * 71 = 2680818
HORIZONTAL 4 POINTS: 
Start: [2,7] 
Second:[2,8] 
Third: [2,9] 
Forth: [2,10]
Current result for starting position [2,7] (vertically) is: 7659480
The values are 29 * 93 * 71 * 40 = 7659480
HORIZONTAL 4 POINTS: 
Start: [2,8] 
Second:[2,9] 
Third: [2,10] 
Forth: [2,11]
Current result for starting position [2,8] (vertically) is: 17696040
The values are 93 * 71 * 40 * 67 = 17696040
The current maximum result is 17696040 


HORIZONTAL 4 POINTS: 
Start: [2,9] 
Second:[2,10] 
Third: [2,11] 
Forth: [2,12]
Current result for starting position [2,9] (vertically) is: 10084840
The values are 71 * 40 * 67 * 53 = 10084840
HORIZONTAL 4 POINTS: 
Start: [2,10] 
Second:[2,11] 
Third: [2,12] 
Forth: [2,13]
Current result for starting position [2,10] (vertically) is: 12499520
The values are 40 * 67 * 53 * 88 = 12499520
HORIZONTAL 4 POINTS: 
Start: [2,11] 
Second:[2,12] 
Third: [2,13] 
Forth: [2,14]
Current result for starting position [2,11] (vertically) is: 9374640
The values are 67 * 53 * 88 * 30 = 9374640
HORIZONTAL 4 POINTS: 
Start: [2,12] 
Second:[2,13] 
Third: [2,14] 
Forth: [2,15]
Current result for starting position [2,12] (vertically) is: 419760
The values are 53 * 88 * 30 * 03 = 419760
HORIZONTAL 4 POINTS: 
Start: [2,13] 
Second:[2,14] 
Third: [2,15] 
Forth: [2,16]
Current result for starting position [2,13] (vertically) is: 388080
The values are 88 * 30 * 03 * 49 = 388080
HORIZONTAL 4 POINTS: 
Start: [2,14] 
Second:[2,15] 
Third: [2,16] 
Forth: [2,17]
Current result for starting position [2,14] (vertically) is: 57330
The values are 30 * 03 * 49 * 13 = 57330
HORIZONTAL 4 POINTS: 
Start: [2,15] 
Second:[2,16] 
Third: [2,17] 
Forth: [2,18]
Current result for starting position [2,15] (vertically) is: 68796
The values are 03 * 49 * 13 * 36 = 68796
HORIZONTAL 4 POINTS: 
Start: [2,16] 
Second:[2,17] 
Third: [2,18] 
Forth: [2,19]
Current result for starting position [2,16] (vertically) is: 1490580
The values are 49 * 13 * 36 * 65 = 1490580
HORIZONTAL 4 POINTS: 
Start: [3,0] 
Second:[3,1] 
Third: [3,2] 
Forth: [3,3]
Current result for starting position [3,0] (vertically) is: 7953400
The values are 52 * 70 * 95 * 23 = 7953400
HORIZONTAL 4 POINTS: 
Start: [3,1] 
Second:[3,2] 
Third: [3,3] 
Forth: [3,4]
Current result for starting position [3,1] (vertically) is: 611800
The values are 70 * 95 * 23 * 04 = 611800
HORIZONTAL 4 POINTS: 
Start: [3,2] 
Second:[3,3] 
Third: [3,4] 
Forth: [3,5]
Current result for starting position [3,2] (vertically) is: 524400
The values are 95 * 23 * 04 * 60 = 524400
HORIZONTAL 4 POINTS: 
Start: [3,3] 
Second:[3,4] 
Third: [3,5] 
Forth: [3,6]
Current result for starting position [3,3] (vertically) is: 60720
The values are 23 * 04 * 60 * 11 = 60720
HORIZONTAL 4 POINTS: 
Start: [3,4] 
Second:[3,5] 
Third: [3,6] 
Forth: [3,7]
Current result for starting position [3,4] (vertically) is: 110880
The values are 04 * 60 * 11 * 42 = 110880
HORIZONTAL 4 POINTS: 
Start: [3,5] 
Second:[3,6] 
Third: [3,7] 
Forth: [3,8]
Current result for starting position [3,5] (vertically) is: 1912680
The values are 60 * 11 * 42 * 69 = 1912680
HORIZONTAL 4 POINTS: 
Start: [3,6] 
Second:[3,7] 
Third: [3,8] 
Forth: [3,9]
Current result for starting position [3,6] (vertically) is: 765072
The values are 11 * 42 * 69 * 24 = 765072
HORIZONTAL 4 POINTS: 
Start: [3,7] 
Second:[3,8] 
Third: [3,9] 
Forth: [3,10]
Current result for starting position [3,7] (vertically) is: 4729536
The values are 42 * 69 * 24 * 68 = 4729536
HORIZONTAL 4 POINTS: 
Start: [3,8] 
Second:[3,9] 
Third: [3,10] 
Forth: [3,11]
Current result for starting position [3,8] (vertically) is: 6306048
The values are 69 * 24 * 68 * 56 = 6306048
HORIZONTAL 4 POINTS: 
Start: [3,9] 
Second:[3,10] 
Third: [3,11] 
Forth: [3,12]
Current result for starting position [3,9] (vertically) is: 91392
The values are 24 * 68 * 56 * 01 = 91392
HORIZONTAL 4 POINTS: 
Start: [3,10] 
Second:[3,11] 
Third: [3,12] 
Forth: [3,13]
Current result for starting position [3,10] (vertically) is: 121856
The values are 68 * 56 * 01 * 32 = 121856
HORIZONTAL 4 POINTS: 
Start: [3,11] 
Second:[3,12] 
Third: [3,13] 
Forth: [3,14]
Current result for starting position [3,11] (vertically) is: 100352
The values are 56 * 01 * 32 * 56 = 100352
HORIZONTAL 4 POINTS: 
Start: [3,12] 
Second:[3,13] 
Third: [3,14] 
Forth: [3,15]
Current result for starting position [3,12] (vertically) is: 127232
The values are 01 * 32 * 56 * 71 = 127232
HORIZONTAL 4 POINTS: 
Start: [3,13] 
Second:[3,14] 
Third: [3,15] 
Forth: [3,16]
Current result for starting position [3,13] (vertically) is: 4707584
The values are 32 * 56 * 71 * 37 = 4707584
HORIZONTAL 4 POINTS: 
Start: [3,14] 
Second:[3,15] 
Third: [3,16] 
Forth: [3,17]
Current result for starting position [3,14] (vertically) is: 294224
The values are 56 * 71 * 37 * 02 = 294224
HORIZONTAL 4 POINTS: 
Start: [3,15] 
Second:[3,16] 
Third: [3,17] 
Forth: [3,18]
Current result for starting position [3,15] (vertically) is: 189144
The values are 71 * 37 * 02 * 36 = 189144
HORIZONTAL 4 POINTS: 
Start: [3,16] 
Second:[3,17] 
Third: [3,18] 
Forth: [3,19]
Current result for starting position [3,16] (vertically) is: 242424
The values are 37 * 02 * 36 * 91 = 242424
HORIZONTAL 4 POINTS: 
Start: [4,0] 
Second:[4,1] 
Third: [4,2] 
Forth: [4,3]
Current result for starting position [4,0] (vertically) is: 774752
The values are 22 * 31 * 16 * 71 = 774752
HORIZONTAL 4 POINTS: 
Start: [4,1] 
Second:[4,2] 
Third: [4,3] 
Forth: [4,4]
Current result for starting position [4,1] (vertically) is: 1796016
The values are 31 * 16 * 71 * 51 = 1796016
HORIZONTAL 4 POINTS: 
Start: [4,2] 
Second:[4,3] 
Third: [4,4] 
Forth: [4,5]
Current result for starting position [4,2] (vertically) is: 3881712
The values are 16 * 71 * 51 * 67 = 3881712
HORIZONTAL 4 POINTS: 
Start: [4,3] 
Second:[4,4] 
Third: [4,5] 
Forth: [4,6]
Current result for starting position [4,3] (vertically) is: 15284241
The values are 71 * 51 * 67 * 63 = 15284241
HORIZONTAL 4 POINTS: 
Start: [4,4] 
Second:[4,5] 
Third: [4,6] 
Forth: [4,7]
Current result for starting position [4,4] (vertically) is: 19159119
The values are 51 * 67 * 63 * 89 = 19159119
The current maximum result is 19159119 


HORIZONTAL 4 POINTS: 
Start: [4,5] 
Second:[4,6] 
Third: [4,7] 
Forth: [4,8]
Current result for starting position [4,5] (vertically) is: 15402429
The values are 67 * 63 * 89 * 41 = 15402429
HORIZONTAL 4 POINTS: 
Start: [4,6] 
Second:[4,7] 
Third: [4,8] 
Forth: [4,9]
Current result for starting position [4,6] (vertically) is: 21149604
The values are 63 * 89 * 41 * 92 = 21149604
The current maximum result is 21149604 


HORIZONTAL 4 POINTS: 
Start: [4,7] 
Second:[4,8] 
Third: [4,9] 
Forth: [4,10]
Current result for starting position [4,7] (vertically) is: 12085488
The values are 89 * 41 * 92 * 36 = 12085488
HORIZONTAL 4 POINTS: 
Start: [4,8] 
Second:[4,9] 
Third: [4,10] 
Forth: [4,11]
Current result for starting position [4,8] (vertically) is: 7332768
The values are 41 * 92 * 36 * 54 = 7332768
HORIZONTAL 4 POINTS: 
Start: [4,9] 
Second:[4,10] 
Third: [4,11] 
Forth: [4,12]
Current result for starting position [4,9] (vertically) is: 3934656
The values are 92 * 36 * 54 * 22 = 3934656
HORIZONTAL 4 POINTS: 
Start: [4,10] 
Second:[4,11] 
Third: [4,12] 
Forth: [4,13]
Current result for starting position [4,10] (vertically) is: 1710720
The values are 36 * 54 * 22 * 40 = 1710720
HORIZONTAL 4 POINTS: 
Start: [4,11] 
Second:[4,12] 
Third: [4,13] 
Forth: [4,14]
Current result for starting position [4,11] (vertically) is: 1900800
The values are 54 * 22 * 40 * 40 = 1900800
HORIZONTAL 4 POINTS: 
Start: [4,12] 
Second:[4,13] 
Third: [4,14] 
Forth: [4,15]
Current result for starting position [4,12] (vertically) is: 985600
The values are 22 * 40 * 40 * 28 = 985600
HORIZONTAL 4 POINTS: 
Start: [4,13] 
Second:[4,14] 
Third: [4,15] 
Forth: [4,16]
Current result for starting position [4,13] (vertically) is: 2956800
The values are 40 * 40 * 28 * 66 = 2956800
HORIZONTAL 4 POINTS: 
Start: [4,14] 
Second:[4,15] 
Third: [4,16] 
Forth: [4,17]
Current result for starting position [4,14] (vertically) is: 2439360
The values are 40 * 28 * 66 * 33 = 2439360
HORIZONTAL 4 POINTS: 
Start: [4,15] 
Second:[4,16] 
Third: [4,17] 
Forth: [4,18]
Current result for starting position [4,15] (vertically) is: 792792
The values are 28 * 66 * 33 * 13 = 792792
HORIZONTAL 4 POINTS: 
Start: [4,16] 
Second:[4,17] 
Third: [4,18] 
Forth: [4,19]
Current result for starting position [4,16] (vertically) is: 2265120
The values are 66 * 33 * 13 * 80 = 2265120
HORIZONTAL 4 POINTS: 
Start: [5,0] 
Second:[5,1] 
Third: [5,2] 
Forth: [5,3]
Current result for starting position [5,0] (vertically) is: 2165760
The values are 24 * 47 * 32 * 60 = 2165760
HORIZONTAL 4 POINTS: 
Start: [5,1] 
Second:[5,2] 
Third: [5,3] 
Forth: [5,4]
Current result for starting position [5,1] (vertically) is: 8933760
The values are 47 * 32 * 60 * 99 = 8933760
HORIZONTAL 4 POINTS: 
Start: [5,2] 
Second:[5,3] 
Third: [5,4] 
Forth: [5,5]
Current result for starting position [5,2] (vertically) is: 570240
The values are 32 * 60 * 99 * 03 = 570240
HORIZONTAL 4 POINTS: 
Start: [5,3] 
Second:[5,4] 
Third: [5,5] 
Forth: [5,6]
Current result for starting position [5,3] (vertically) is: 801900
The values are 60 * 99 * 03 * 45 = 801900
HORIZONTAL 4 POINTS: 
Start: [5,4] 
Second:[5,5] 
Third: [5,6] 
Forth: [5,7]
Current result for starting position [5,4] (vertically) is: 26730
The values are 99 * 03 * 45 * 02 = 26730
HORIZONTAL 4 POINTS: 
Start: [5,5] 
Second:[5,6] 
Third: [5,7] 
Forth: [5,8]
Current result for starting position [5,5] (vertically) is: 11880
The values are 03 * 45 * 02 * 44 = 11880
HORIZONTAL 4 POINTS: 
Start: [5,6] 
Second:[5,7] 
Third: [5,8] 
Forth: [5,9]
Current result for starting position [5,6] (vertically) is: 297000
The values are 45 * 02 * 44 * 75 = 297000
HORIZONTAL 4 POINTS: 
Start: [5,7] 
Second:[5,8] 
Third: [5,9] 
Forth: [5,10]
Current result for starting position [5,7] (vertically) is: 217800
The values are 02 * 44 * 75 * 33 = 217800
HORIZONTAL 4 POINTS: 
Start: [5,8] 
Second:[5,9] 
Third: [5,10] 
Forth: [5,11]
Current result for starting position [5,8] (vertically) is: 5771700
The values are 44 * 75 * 33 * 53 = 5771700
HORIZONTAL 4 POINTS: 
Start: [5,9] 
Second:[5,10] 
Third: [5,11] 
Forth: [5,12]
Current result for starting position [5,9] (vertically) is: 10231650
The values are 75 * 33 * 53 * 78 = 10231650
HORIZONTAL 4 POINTS: 
Start: [5,10] 
Second:[5,11] 
Third: [5,12] 
Forth: [5,13]
Current result for starting position [5,10] (vertically) is: 4911192
The values are 33 * 53 * 78 * 36 = 4911192
HORIZONTAL 4 POINTS: 
Start: [5,11] 
Second:[5,12] 
Third: [5,13] 
Forth: [5,14]
Current result for starting position [5,11] (vertically) is: 12501216
The values are 53 * 78 * 36 * 84 = 12501216
HORIZONTAL 4 POINTS: 
Start: [5,12] 
Second:[5,13] 
Third: [5,14] 
Forth: [5,15]
Current result for starting position [5,12] (vertically) is: 4717440
The values are 78 * 36 * 84 * 20 = 4717440
HORIZONTAL 4 POINTS: 
Start: [5,13] 
Second:[5,14] 
Third: [5,15] 
Forth: [5,16]
Current result for starting position [5,13] (vertically) is: 2116800
The values are 36 * 84 * 20 * 35 = 2116800
HORIZONTAL 4 POINTS: 
Start: [5,14] 
Second:[5,15] 
Third: [5,16] 
Forth: [5,17]
Current result for starting position [5,14] (vertically) is: 999600
The values are 84 * 20 * 35 * 17 = 999600
HORIZONTAL 4 POINTS: 
Start: [5,15] 
Second:[5,16] 
Third: [5,17] 
Forth: [5,18]
Current result for starting position [5,15] (vertically) is: 142800
The values are 20 * 35 * 17 * 12 = 142800
HORIZONTAL 4 POINTS: 
Start: [5,16] 
Second:[5,17] 
Third: [5,18] 
Forth: [5,19]
Current result for starting position [5,16] (vertically) is: 357000
The values are 35 * 17 * 12 * 50 = 357000
HORIZONTAL 4 POINTS: 
Start: [6,0] 
Second:[6,1] 
Third: [6,2] 
Forth: [6,3]
Current result for starting position [6,0] (vertically) is: 7112448
The values are 32 * 98 * 81 * 28 = 7112448
HORIZONTAL 4 POINTS: 
Start: [6,1] 
Second:[6,2] 
Third: [6,3] 
Forth: [6,4]
Current result for starting position [6,1] (vertically) is: 14224896
The values are 98 * 81 * 28 * 64 = 14224896
HORIZONTAL 4 POINTS: 
Start: [6,2] 
Second:[6,3] 
Third: [6,4] 
Forth: [6,5]
Current result for starting position [6,2] (vertically) is: 3338496
The values are 81 * 28 * 64 * 23 = 3338496
HORIZONTAL 4 POINTS: 
Start: [6,3] 
Second:[6,4] 
Third: [6,5] 
Forth: [6,6]
Current result for starting position [6,3] (vertically) is: 2761472
The values are 28 * 64 * 23 * 67 = 2761472
HORIZONTAL 4 POINTS: 
Start: [6,4] 
Second:[6,5] 
Third: [6,6] 
Forth: [6,7]
Current result for starting position [6,4] (vertically) is: 986240
The values are 64 * 23 * 67 * 10 = 986240
HORIZONTAL 4 POINTS: 
Start: [6,5] 
Second:[6,6] 
Third: [6,7] 
Forth: [6,8]
Current result for starting position [6,5] (vertically) is: 400660
The values are 23 * 67 * 10 * 26 = 400660
HORIZONTAL 4 POINTS: 
Start: [6,6] 
Second:[6,7] 
Third: [6,8] 
Forth: [6,9]
Current result for starting position [6,6] (vertically) is: 661960
The values are 67 * 10 * 26 * 38 = 661960
HORIZONTAL 4 POINTS: 
Start: [6,7] 
Second:[6,8] 
Third: [6,9] 
Forth: [6,10]
Current result for starting position [6,7] (vertically) is: 395200
The values are 10 * 26 * 38 * 40 = 395200
HORIZONTAL 4 POINTS: 
Start: [6,8] 
Second:[6,9] 
Third: [6,10] 
Forth: [6,11]
Current result for starting position [6,8] (vertically) is: 2647840
The values are 26 * 38 * 40 * 67 = 2647840
HORIZONTAL 4 POINTS: 
Start: [6,9] 
Second:[6,10] 
Third: [6,11] 
Forth: [6,12]
Current result for starting position [6,9] (vertically) is: 6008560
The values are 38 * 40 * 67 * 59 = 6008560
HORIZONTAL 4 POINTS: 
Start: [6,10] 
Second:[6,11] 
Third: [6,12] 
Forth: [6,13]
Current result for starting position [6,10] (vertically) is: 8538480
The values are 40 * 67 * 59 * 54 = 8538480
HORIZONTAL 4 POINTS: 
Start: [6,11] 
Second:[6,12] 
Third: [6,13] 
Forth: [6,14]
Current result for starting position [6,11] (vertically) is: 14942340
The values are 67 * 59 * 54 * 70 = 14942340
HORIZONTAL 4 POINTS: 
Start: [6,12] 
Second:[6,13] 
Third: [6,14] 
Forth: [6,15]
Current result for starting position [6,12] (vertically) is: 14719320
The values are 59 * 54 * 70 * 66 = 14719320
HORIZONTAL 4 POINTS: 
Start: [6,13] 
Second:[6,14] 
Third: [6,15] 
Forth: [6,16]
Current result for starting position [6,13] (vertically) is: 4490640
The values are 54 * 70 * 66 * 18 = 4490640
HORIZONTAL 4 POINTS: 
Start: [6,14] 
Second:[6,15] 
Third: [6,16] 
Forth: [6,17]
Current result for starting position [6,14] (vertically) is: 3160080
The values are 70 * 66 * 18 * 38 = 3160080
HORIZONTAL 4 POINTS: 
Start: [6,15] 
Second:[6,16] 
Third: [6,17] 
Forth: [6,18]
Current result for starting position [6,15] (vertically) is: 2889216
The values are 66 * 18 * 38 * 64 = 2889216
HORIZONTAL 4 POINTS: 
Start: [6,16] 
Second:[6,17] 
Third: [6,18] 
Forth: [6,19]
Current result for starting position [6,16] (vertically) is: 3064320
The values are 18 * 38 * 64 * 70 = 3064320
HORIZONTAL 4 POINTS: 
Start: [7,0] 
Second:[7,1] 
Third: [7,2] 
Forth: [7,3]
Current result for starting position [7,0] (vertically) is: 2369120
The values are 67 * 26 * 20 * 68 = 2369120
HORIZONTAL 4 POINTS: 
Start: [7,1] 
Second:[7,2] 
Third: [7,3] 
Forth: [7,4]
Current result for starting position [7,1] (vertically) is: 70720
The values are 26 * 20 * 68 * 02 = 70720
HORIZONTAL 4 POINTS: 
Start: [7,2] 
Second:[7,3] 
Third: [7,4] 
Forth: [7,5]
Current result for starting position [7,2] (vertically) is: 168640
The values are 20 * 68 * 02 * 62 = 168640
HORIZONTAL 4 POINTS: 
Start: [7,3] 
Second:[7,4] 
Third: [7,5] 
Forth: [7,6]
Current result for starting position [7,3] (vertically) is: 101184
The values are 68 * 02 * 62 * 12 = 101184
HORIZONTAL 4 POINTS: 
Start: [7,4] 
Second:[7,5] 
Third: [7,6] 
Forth: [7,7]
Current result for starting position [7,4] (vertically) is: 29760
The values are 02 * 62 * 12 * 20 = 29760
HORIZONTAL 4 POINTS: 
Start: [7,5] 
Second:[7,6] 
Third: [7,7] 
Forth: [7,8]
Current result for starting position [7,5] (vertically) is: 1413600
The values are 62 * 12 * 20 * 95 = 1413600
HORIZONTAL 4 POINTS: 
Start: [7,6] 
Second:[7,7] 
Third: [7,8] 
Forth: [7,9]
Current result for starting position [7,6] (vertically) is: 1436400
The values are 12 * 20 * 95 * 63 = 1436400
HORIZONTAL 4 POINTS: 
Start: [7,7] 
Second:[7,8] 
Third: [7,9] 
Forth: [7,10]
Current result for starting position [7,7] (vertically) is: 11251800
The values are 20 * 95 * 63 * 94 = 11251800
HORIZONTAL 4 POINTS: 
Start: [7,8] 
Second:[7,9] 
Third: [7,10] 
Forth: [7,11]
Current result for starting position [7,8] (vertically) is: 21941010
The values are 95 * 63 * 94 * 39 = 21941010
The current maximum result is 21941010 


HORIZONTAL 4 POINTS: 
Start: [7,9] 
Second:[7,10] 
Third: [7,11] 
Forth: [7,12]
Current result for starting position [7,9] (vertically) is: 14550354
The values are 63 * 94 * 39 * 63 = 14550354
HORIZONTAL 4 POINTS: 
Start: [7,10] 
Second:[7,11] 
Third: [7,12] 
Forth: [7,13]
Current result for starting position [7,10] (vertically) is: 1847664
The values are 94 * 39 * 63 * 08 = 1847664
HORIZONTAL 4 POINTS: 
Start: [7,11] 
Second:[7,12] 
Third: [7,13] 
Forth: [7,14]
Current result for starting position [7,11] (vertically) is: 786240
The values are 39 * 63 * 08 * 40 = 786240
HORIZONTAL 4 POINTS: 
Start: [7,12] 
Second:[7,13] 
Third: [7,14] 
Forth: [7,15]
Current result for starting position [7,12] (vertically) is: 1834560
The values are 63 * 08 * 40 * 91 = 1834560
HORIZONTAL 4 POINTS: 
Start: [7,13] 
Second:[7,14] 
Third: [7,15] 
Forth: [7,16]
Current result for starting position [7,13] (vertically) is: 1921920
The values are 08 * 40 * 91 * 66 = 1921920
HORIZONTAL 4 POINTS: 
Start: [7,14] 
Second:[7,15] 
Third: [7,16] 
Forth: [7,17]
Current result for starting position [7,14] (vertically) is: 11771760
The values are 40 * 91 * 66 * 49 = 11771760
HORIZONTAL 4 POINTS: 
Start: [7,15] 
Second:[7,16] 
Third: [7,17] 
Forth: [7,18]
Current result for starting position [7,15] (vertically) is: 27663636
The values are 91 * 66 * 49 * 94 = 27663636
The current maximum result is 27663636 


HORIZONTAL 4 POINTS: 
Start: [7,16] 
Second:[7,17] 
Third: [7,18] 
Forth: [7,19]
Current result for starting position [7,16] (vertically) is: 6383916
The values are 66 * 49 * 94 * 21 = 6383916
HORIZONTAL 4 POINTS: 
Start: [8,0] 
Second:[8,1] 
Third: [8,2] 
Forth: [8,3]
Current result for starting position [8,0] (vertically) is: 382800
The values are 24 * 55 * 58 * 05 = 382800
HORIZONTAL 4 POINTS: 
Start: [8,1] 
Second:[8,2] 
Third: [8,3] 
Forth: [8,4]
Current result for starting position [8,1] (vertically) is: 1052700
The values are 55 * 58 * 05 * 66 = 1052700
HORIZONTAL 4 POINTS: 
Start: [8,2] 
Second:[8,3] 
Third: [8,4] 
Forth: [8,5]
Current result for starting position [8,2] (vertically) is: 1397220
The values are 58 * 05 * 66 * 73 = 1397220
HORIZONTAL 4 POINTS: 
Start: [8,3] 
Second:[8,4] 
Third: [8,5] 
Forth: [8,6]
Current result for starting position [8,3] (vertically) is: 2384910
The values are 05 * 66 * 73 * 99 = 2384910
HORIZONTAL 4 POINTS: 
Start: [8,4] 
Second:[8,5] 
Third: [8,6] 
Forth: [8,7]
Current result for starting position [8,4] (vertically) is: 12401532
The values are 66 * 73 * 99 * 26 = 12401532
HORIZONTAL 4 POINTS: 
Start: [8,5] 
Second:[8,6] 
Third: [8,7] 
Forth: [8,8]
Current result for starting position [8,5] (vertically) is: 18226494
The values are 73 * 99 * 26 * 97 = 18226494
HORIZONTAL 4 POINTS: 
Start: [8,6] 
Second:[8,7] 
Third: [8,8] 
Forth: [8,9]
Current result for starting position [8,6] (vertically) is: 4244526
The values are 99 * 26 * 97 * 17 = 4244526
HORIZONTAL 4 POINTS: 
Start: [8,7] 
Second:[8,8] 
Third: [8,9] 
Forth: [8,10]
Current result for starting position [8,7] (vertically) is: 3344172
The values are 26 * 97 * 17 * 78 = 3344172
HORIZONTAL 4 POINTS: 
Start: [8,8] 
Second:[8,9] 
Third: [8,10] 
Forth: [8,11]
Current result for starting position [8,8] (vertically) is: 10032516
The values are 97 * 17 * 78 * 78 = 10032516
HORIZONTAL 4 POINTS: 
Start: [8,9] 
Second:[8,10] 
Third: [8,11] 
Forth: [8,12]
Current result for starting position [8,9] (vertically) is: 9929088
The values are 17 * 78 * 78 * 96 = 9929088
HORIZONTAL 4 POINTS: 
Start: [8,10] 
Second:[8,11] 
Third: [8,12] 
Forth: [8,13]
Current result for starting position [8,10] (vertically) is: 48477312
The values are 78 * 78 * 96 * 83 = 48477312
The current maximum result is 48477312 


HORIZONTAL 4 POINTS: 
Start: [8,11] 
Second:[8,12] 
Third: [8,13] 
Forth: [8,14]
Current result for starting position [8,11] (vertically) is: 8701056
The values are 78 * 96 * 83 * 14 = 8701056
HORIZONTAL 4 POINTS: 
Start: [8,12] 
Second:[8,13] 
Third: [8,14] 
Forth: [8,15]
Current result for starting position [8,12] (vertically) is: 9816576
The values are 96 * 83 * 14 * 88 = 9816576
HORIZONTAL 4 POINTS: 
Start: [8,13] 
Second:[8,14] 
Third: [8,15] 
Forth: [8,16]
Current result for starting position [8,13] (vertically) is: 3476704
The values are 83 * 14 * 88 * 34 = 3476704
HORIZONTAL 4 POINTS: 
Start: [8,14] 
Second:[8,15] 
Third: [8,16] 
Forth: [8,17]
Current result for starting position [8,14] (vertically) is: 3728032
The values are 14 * 88 * 34 * 89 = 3728032
HORIZONTAL 4 POINTS: 
Start: [8,15] 
Second:[8,16] 
Third: [8,17] 
Forth: [8,18]
Current result for starting position [8,15] (vertically) is: 16776144
The values are 88 * 34 * 89 * 63 = 16776144
HORIZONTAL 4 POINTS: 
Start: [8,16] 
Second:[8,17] 
Third: [8,18] 
Forth: [8,19]
Current result for starting position [8,16] (vertically) is: 13725936
The values are 34 * 89 * 63 * 72 = 13725936
HORIZONTAL 4 POINTS: 
Start: [9,0] 
Second:[9,1] 
Third: [9,2] 
Forth: [9,3]
Current result for starting position [9,0] (vertically) is: 156492
The values are 21 * 36 * 23 * 09 = 156492
HORIZONTAL 4 POINTS: 
Start: [9,1] 
Second:[9,2] 
Third: [9,3] 
Forth: [9,4]
Current result for starting position [9,1] (vertically) is: 558900
The values are 36 * 23 * 09 * 75 = 558900
HORIZONTAL 4 POINTS: 
Start: [9,2] 
Second:[9,3] 
Third: [9,4] 
Forth: [9,5]
Current result for starting position [9,2] (vertically) is: 0
The values are 23 * 09 * 75 * 0 = 0
HORIZONTAL 4 POINTS: 
Start: [9,3] 
Second:[9,4] 
Third: [9,5] 
Forth: [9,6]
Current result for starting position [9,3] (vertically) is: 0
The values are 09 * 75 * 0 * 76 = 0
HORIZONTAL 4 POINTS: 
Start: [9,4] 
Second:[9,5] 
Third: [9,6] 
Forth: [9,7]
Current result for starting position [9,4] (vertically) is: 0
The values are 75 * 0 * 76 * 44 = 0
HORIZONTAL 4 POINTS: 
Start: [9,5] 
Second:[9,6] 
Third: [9,7] 
Forth: [9,8]
Current result for starting position [9,5] (vertically) is: 0
The values are 0 * 76 * 44 * 20 = 0
HORIZONTAL 4 POINTS: 
Start: [9,6] 
Second:[9,7] 
Third: [9,8] 
Forth: [9,9]
Current result for starting position [9,6] (vertically) is: 3009600
The values are 76 * 44 * 20 * 45 = 3009600
HORIZONTAL 4 POINTS: 
Start: [9,7] 
Second:[9,8] 
Third: [9,9] 
Forth: [9,10]
Current result for starting position [9,7] (vertically) is: 1386000
The values are 44 * 20 * 45 * 35 = 1386000
HORIZONTAL 4 POINTS: 
Start: [9,8] 
Second:[9,9] 
Third: [9,10] 
Forth: [9,11]
Current result for starting position [9,8] (vertically) is: 441000
The values are 20 * 45 * 35 * 14 = 441000
HORIZONTAL 4 POINTS: 
Start: [9,9] 
Second:[9,10] 
Third: [9,11] 
Forth: [9,12]
Current result for starting position [9,9] (vertically) is: 0
The values are 45 * 35 * 14 * 0 = 0
HORIZONTAL 4 POINTS: 
Start: [9,10] 
Second:[9,11] 
Third: [9,12] 
Forth: [9,13]
Current result for starting position [9,10] (vertically) is: 0
The values are 35 * 14 * 0 * 61 = 0
HORIZONTAL 4 POINTS: 
Start: [9,11] 
Second:[9,12] 
Third: [9,13] 
Forth: [9,14]
Current result for starting position [9,11] (vertically) is: 0
The values are 14 * 0 * 61 * 33 = 0
HORIZONTAL 4 POINTS: 
Start: [9,12] 
Second:[9,13] 
Third: [9,14] 
Forth: [9,15]
Current result for starting position [9,12] (vertically) is: 0
The values are 0 * 61 * 33 * 97 = 0
HORIZONTAL 4 POINTS: 
Start: [9,13] 
Second:[9,14] 
Third: [9,15] 
Forth: [9,16]
Current result for starting position [9,13] (vertically) is: 6638874
The values are 61 * 33 * 97 * 34 = 6638874
HORIZONTAL 4 POINTS: 
Start: [9,14] 
Second:[9,15] 
Third: [9,16] 
Forth: [9,17]
Current result for starting position [9,14] (vertically) is: 3373854
The values are 33 * 97 * 34 * 31 = 3373854
HORIZONTAL 4 POINTS: 
Start: [9,15] 
Second:[9,16] 
Third: [9,17] 
Forth: [9,18]
Current result for starting position [9,15] (vertically) is: 3373854
The values are 97 * 34 * 31 * 33 = 3373854
HORIZONTAL 4 POINTS: 
Start: [9,16] 
Second:[9,17] 
Third: [9,18] 
Forth: [9,19]
Current result for starting position [9,16] (vertically) is: 3304290
The values are 34 * 31 * 33 * 95 = 3304290
HORIZONTAL 4 POINTS: 
Start: [10,0] 
Second:[10,1] 
Third: [10,2] 
Forth: [10,3]
Current result for starting position [10,0] (vertically) is: 1967784
The values are 78 * 17 * 53 * 28 = 1967784
HORIZONTAL 4 POINTS: 
Start: [10,1] 
Second:[10,2] 
Third: [10,3] 
Forth: [10,4]
Current result for starting position [10,1] (vertically) is: 555016
The values are 17 * 53 * 28 * 22 = 555016
HORIZONTAL 4 POINTS: 
Start: [10,2] 
Second:[10,3] 
Third: [10,4] 
Forth: [10,5]
Current result for starting position [10,2] (vertically) is: 2448600
The values are 53 * 28 * 22 * 75 = 2448600
HORIZONTAL 4 POINTS: 
Start: [10,3] 
Second:[10,4] 
Third: [10,5] 
Forth: [10,6]
Current result for starting position [10,3] (vertically) is: 1432200
The values are 28 * 22 * 75 * 31 = 1432200
HORIZONTAL 4 POINTS: 
Start: [10,4] 
Second:[10,5] 
Third: [10,6] 
Forth: [10,7]
Current result for starting position [10,4] (vertically) is: 3427050
The values are 22 * 75 * 31 * 67 = 3427050
HORIZONTAL 4 POINTS: 
Start: [10,5] 
Second:[10,6] 
Third: [10,7] 
Forth: [10,8]
Current result for starting position [10,5] (vertically) is: 2336625
The values are 75 * 31 * 67 * 15 = 2336625
HORIZONTAL 4 POINTS: 
Start: [10,6] 
Second:[10,7] 
Third: [10,8] 
Forth: [10,9]
Current result for starting position [10,6] (vertically) is: 2928570
The values are 31 * 67 * 15 * 94 = 2928570
HORIZONTAL 4 POINTS: 
Start: [10,7] 
Second:[10,8] 
Third: [10,9] 
Forth: [10,10]
Current result for starting position [10,7] (vertically) is: 283410
The values are 67 * 15 * 94 * 03 = 283410
HORIZONTAL 4 POINTS: 
Start: [10,8] 
Second:[10,9] 
Third: [10,10] 
Forth: [10,11]
Current result for starting position [10,8] (vertically) is: 338400
The values are 15 * 94 * 03 * 80 = 338400
HORIZONTAL 4 POINTS: 
Start: [10,9] 
Second:[10,10] 
Third: [10,11] 
Forth: [10,12]
Current result for starting position [10,9] (vertically) is: 90240
The values are 94 * 03 * 80 * 04 = 90240
HORIZONTAL 4 POINTS: 
Start: [10,10] 
Second:[10,11] 
Third: [10,12] 
Forth: [10,13]
Current result for starting position [10,10] (vertically) is: 59520
The values are 03 * 80 * 04 * 62 = 59520
HORIZONTAL 4 POINTS: 
Start: [10,11] 
Second:[10,12] 
Third: [10,13] 
Forth: [10,14]
Current result for starting position [10,11] (vertically) is: 317440
The values are 80 * 04 * 62 * 16 = 317440
HORIZONTAL 4 POINTS: 
Start: [10,12] 
Second:[10,13] 
Third: [10,14] 
Forth: [10,15]
Current result for starting position [10,12] (vertically) is: 55552
The values are 04 * 62 * 16 * 14 = 55552
HORIZONTAL 4 POINTS: 
Start: [10,13] 
Second:[10,14] 
Third: [10,15] 
Forth: [10,16]
Current result for starting position [10,13] (vertically) is: 124992
The values are 62 * 16 * 14 * 09 = 124992
HORIZONTAL 4 POINTS: 
Start: [10,14] 
Second:[10,15] 
Third: [10,16] 
Forth: [10,17]
Current result for starting position [10,14] (vertically) is: 106848
The values are 16 * 14 * 09 * 53 = 106848
HORIZONTAL 4 POINTS: 
Start: [10,15] 
Second:[10,16] 
Third: [10,17] 
Forth: [10,18]
Current result for starting position [10,15] (vertically) is: 373968
The values are 14 * 09 * 53 * 56 = 373968
HORIZONTAL 4 POINTS: 
Start: [10,16] 
Second:[10,17] 
Third: [10,18] 
Forth: [10,19]
Current result for starting position [10,16] (vertically) is: 2457504
The values are 09 * 53 * 56 * 92 = 2457504
HORIZONTAL 4 POINTS: 
Start: [11,0] 
Second:[11,1] 
Third: [11,2] 
Forth: [11,3]
Current result for starting position [11,0] (vertically) is: 131040
The values are 16 * 39 * 05 * 42 = 131040
HORIZONTAL 4 POINTS: 
Start: [11,1] 
Second:[11,2] 
Third: [11,3] 
Forth: [11,4]
Current result for starting position [11,1] (vertically) is: 786240
The values are 39 * 05 * 42 * 96 = 786240
HORIZONTAL 4 POINTS: 
Start: [11,2] 
Second:[11,3] 
Third: [11,4] 
Forth: [11,5]
Current result for starting position [11,2] (vertically) is: 705600
The values are 05 * 42 * 96 * 35 = 705600
HORIZONTAL 4 POINTS: 
Start: [11,3] 
Second:[11,4] 
Third: [11,5] 
Forth: [11,6]
Current result for starting position [11,3] (vertically) is: 4374720
The values are 42 * 96 * 35 * 31 = 4374720
HORIZONTAL 4 POINTS: 
Start: [11,4] 
Second:[11,5] 
Third: [11,6] 
Forth: [11,7]
Current result for starting position [11,4] (vertically) is: 4895520
The values are 96 * 35 * 31 * 47 = 4895520
HORIZONTAL 4 POINTS: 
Start: [11,5] 
Second:[11,6] 
Third: [11,7] 
Forth: [11,8]
Current result for starting position [11,5] (vertically) is: 2804725
The values are 35 * 31 * 47 * 55 = 2804725
HORIZONTAL 4 POINTS: 
Start: [11,6] 
Second:[11,7] 
Third: [11,8] 
Forth: [11,9]
Current result for starting position [11,6] (vertically) is: 4647830
The values are 31 * 47 * 55 * 58 = 4647830
HORIZONTAL 4 POINTS: 
Start: [11,7] 
Second:[11,8] 
Third: [11,9] 
Forth: [11,10]
Current result for starting position [11,7] (vertically) is: 13193840
The values are 47 * 55 * 58 * 88 = 13193840
HORIZONTAL 4 POINTS: 
Start: [11,8] 
Second:[11,9] 
Third: [11,10] 
Forth: [11,11]
Current result for starting position [11,8] (vertically) is: 6737280
The values are 55 * 58 * 88 * 24 = 6737280
HORIZONTAL 4 POINTS: 
Start: [11,9] 
Second:[11,10] 
Third: [11,11] 
Forth: [11,12]
Current result for starting position [11,9] (vertically) is: 0
The values are 58 * 88 * 24 * 0 = 0
HORIZONTAL 4 POINTS: 
Start: [11,10] 
Second:[11,11] 
Third: [11,12] 
Forth: [11,13]
Current result for starting position [11,10] (vertically) is: 0
The values are 88 * 24 * 0 * 17 = 0
HORIZONTAL 4 POINTS: 
Start: [11,11] 
Second:[11,12] 
Third: [11,13] 
Forth: [11,14]
Current result for starting position [11,11] (vertically) is: 0
The values are 24 * 0 * 17 * 54 = 0
HORIZONTAL 4 POINTS: 
Start: [11,12] 
Second:[11,13] 
Third: [11,14] 
Forth: [11,15]
Current result for starting position [11,12] (vertically) is: 0
The values are 0 * 17 * 54 * 24 = 0
HORIZONTAL 4 POINTS: 
Start: [11,13] 
Second:[11,14] 
Third: [11,15] 
Forth: [11,16]
Current result for starting position [11,13] (vertically) is: 793152
The values are 17 * 54 * 24 * 36 = 793152
HORIZONTAL 4 POINTS: 
Start: [11,14] 
Second:[11,15] 
Third: [11,16] 
Forth: [11,17]
Current result for starting position [11,14] (vertically) is: 1353024
The values are 54 * 24 * 36 * 29 = 1353024
HORIZONTAL 4 POINTS: 
Start: [11,15] 
Second:[11,16] 
Third: [11,17] 
Forth: [11,18]
Current result for starting position [11,15] (vertically) is: 2129760
The values are 24 * 36 * 29 * 85 = 2129760
HORIZONTAL 4 POINTS: 
Start: [11,16] 
Second:[11,17] 
Third: [11,18] 
Forth: [11,19]
Current result for starting position [11,16] (vertically) is: 5058180
The values are 36 * 29 * 85 * 57 = 5058180
HORIZONTAL 4 POINTS: 
Start: [12,0] 
Second:[12,1] 
Third: [12,2] 
Forth: [12,3]
Current result for starting position [12,0] (vertically) is: 0
The values are 86 * 56 * 0 * 48 = 0
HORIZONTAL 4 POINTS: 
Start: [12,1] 
Second:[12,2] 
Third: [12,3] 
Forth: [12,4]
Current result for starting position [12,1] (vertically) is: 0
The values are 56 * 0 * 48 * 35 = 0
HORIZONTAL 4 POINTS: 
Start: [12,2] 
Second:[12,3] 
Third: [12,4] 
Forth: [12,5]
Current result for starting position [12,2] (vertically) is: 0
The values are 0 * 48 * 35 * 71 = 0
HORIZONTAL 4 POINTS: 
Start: [12,3] 
Second:[12,4] 
Third: [12,5] 
Forth: [12,6]
Current result for starting position [12,3] (vertically) is: 10615920
The values are 48 * 35 * 71 * 89 = 10615920
HORIZONTAL 4 POINTS: 
Start: [12,4] 
Second:[12,5] 
Third: [12,6] 
Forth: [12,7]
Current result for starting position [12,4] (vertically) is: 1548155
The values are 35 * 71 * 89 * 07 = 1548155
HORIZONTAL 4 POINTS: 
Start: [12,5] 
Second:[12,6] 
Third: [12,7] 
Forth: [12,8]
Current result for starting position [12,5] (vertically) is: 221165
The values are 71 * 89 * 07 * 05 = 221165
HORIZONTAL 4 POINTS: 
Start: [12,6] 
Second:[12,7] 
Third: [12,8] 
Forth: [12,9]
Current result for starting position [12,6] (vertically) is: 137060
The values are 89 * 07 * 05 * 44 = 137060
HORIZONTAL 4 POINTS: 
Start: [12,7] 
Second:[12,8] 
Third: [12,9] 
Forth: [12,10]
Current result for starting position [12,7] (vertically) is: 67760
The values are 07 * 05 * 44 * 44 = 67760
HORIZONTAL 4 POINTS: 
Start: [12,8] 
Second:[12,9] 
Third: [12,10] 
Forth: [12,11]
Current result for starting position [12,8] (vertically) is: 358160
The values are 05 * 44 * 44 * 37 = 358160
HORIZONTAL 4 POINTS: 
Start: [12,9] 
Second:[12,10] 
Third: [12,11] 
Forth: [12,12]
Current result for starting position [12,9] (vertically) is: 3151808
The values are 44 * 44 * 37 * 44 = 3151808
HORIZONTAL 4 POINTS: 
Start: [12,10] 
Second:[12,11] 
Third: [12,12] 
Forth: [12,13]
Current result for starting position [12,10] (vertically) is: 4297920
The values are 44 * 37 * 44 * 60 = 4297920
HORIZONTAL 4 POINTS: 
Start: [12,11] 
Second:[12,12] 
Third: [12,13] 
Forth: [12,14]
Current result for starting position [12,11] (vertically) is: 2051280
The values are 37 * 44 * 60 * 21 = 2051280
HORIZONTAL 4 POINTS: 
Start: [12,12] 
Second:[12,13] 
Third: [12,14] 
Forth: [12,15]
Current result for starting position [12,12] (vertically) is: 3215520
The values are 44 * 60 * 21 * 58 = 3215520
HORIZONTAL 4 POINTS: 
Start: [12,13] 
Second:[12,14] 
Third: [12,15] 
Forth: [12,16]
Current result for starting position [12,13] (vertically) is: 3727080
The values are 60 * 21 * 58 * 51 = 3727080
HORIZONTAL 4 POINTS: 
Start: [12,14] 
Second:[12,15] 
Third: [12,16] 
Forth: [12,17]
Current result for starting position [12,14] (vertically) is: 3354372
The values are 21 * 58 * 51 * 54 = 3354372
HORIZONTAL 4 POINTS: 
Start: [12,15] 
Second:[12,16] 
Third: [12,17] 
Forth: [12,18]
Current result for starting position [12,15] (vertically) is: 2715444
The values are 58 * 51 * 54 * 17 = 2715444
HORIZONTAL 4 POINTS: 
Start: [12,16] 
Second:[12,17] 
Third: [12,18] 
Forth: [12,19]
Current result for starting position [12,16] (vertically) is: 2715444
The values are 51 * 54 * 17 * 58 = 2715444
HORIZONTAL 4 POINTS: 
Start: [13,0] 
Second:[13,1] 
Third: [13,2] 
Forth: [13,3]
Current result for starting position [13,0] (vertically) is: 8372160
The values are 19 * 80 * 81 * 68 = 8372160
HORIZONTAL 4 POINTS: 
Start: [13,1] 
Second:[13,2] 
Third: [13,3] 
Forth: [13,4]
Current result for starting position [13,1] (vertically) is: 2203200
The values are 80 * 81 * 68 * 05 = 2203200
HORIZONTAL 4 POINTS: 
Start: [13,2] 
Second:[13,3] 
Third: [13,4] 
Forth: [13,5]
Current result for starting position [13,2] (vertically) is: 2588760
The values are 81 * 68 * 05 * 94 = 2588760
HORIZONTAL 4 POINTS: 
Start: [13,3] 
Second:[13,4] 
Third: [13,5] 
Forth: [13,6]
Current result for starting position [13,3] (vertically) is: 1502120
The values are 68 * 05 * 94 * 47 = 1502120
HORIZONTAL 4 POINTS: 
Start: [13,4] 
Second:[13,5] 
Third: [13,6] 
Forth: [13,7]
Current result for starting position [13,4] (vertically) is: 1524210
The values are 05 * 94 * 47 * 69 = 1524210
HORIZONTAL 4 POINTS: 
Start: [13,5] 
Second:[13,6] 
Third: [13,7] 
Forth: [13,8]
Current result for starting position [13,5] (vertically) is: 8535576
The values are 94 * 47 * 69 * 28 = 8535576
HORIZONTAL 4 POINTS: 
Start: [13,6] 
Second:[13,7] 
Third: [13,8] 
Forth: [13,9]
Current result for starting position [13,6] (vertically) is: 6628692
The values are 47 * 69 * 28 * 73 = 6628692
HORIZONTAL 4 POINTS: 
Start: [13,7] 
Second:[13,8] 
Third: [13,9] 
Forth: [13,10]
Current result for starting position [13,7] (vertically) is: 12975312
The values are 69 * 28 * 73 * 92 = 12975312
HORIZONTAL 4 POINTS: 
Start: [13,8] 
Second:[13,9] 
Third: [13,10] 
Forth: [13,11]
Current result for starting position [13,8] (vertically) is: 2444624
The values are 28 * 73 * 92 * 13 = 2444624
HORIZONTAL 4 POINTS: 
Start: [13,9] 
Second:[13,10] 
Third: [13,11] 
Forth: [13,12]
Current result for starting position [13,9] (vertically) is: 7508488
The values are 73 * 92 * 13 * 86 = 7508488
HORIZONTAL 4 POINTS: 
Start: [13,10] 
Second:[13,11] 
Third: [13,12] 
Forth: [13,13]
Current result for starting position [13,10] (vertically) is: 5348512
The values are 92 * 13 * 86 * 52 = 5348512
HORIZONTAL 4 POINTS: 
Start: [13,11] 
Second:[13,12] 
Third: [13,13] 
Forth: [13,14]
Current result for starting position [13,11] (vertically) is: 988312
The values are 13 * 86 * 52 * 17 = 988312
HORIZONTAL 4 POINTS: 
Start: [13,12] 
Second:[13,13] 
Third: [13,14] 
Forth: [13,15]
Current result for starting position [13,12] (vertically) is: 5853848
The values are 86 * 52 * 17 * 77 = 5853848
HORIZONTAL 4 POINTS: 
Start: [13,13] 
Second:[13,14] 
Third: [13,15] 
Forth: [13,16]
Current result for starting position [13,13] (vertically) is: 272272
The values are 52 * 17 * 77 * 04 = 272272
HORIZONTAL 4 POINTS: 
Start: [13,14] 
Second:[13,15] 
Third: [13,16] 
Forth: [13,17]
Current result for starting position [13,14] (vertically) is: 466004
The values are 17 * 77 * 04 * 89 = 466004
HORIZONTAL 4 POINTS: 
Start: [13,15] 
Second:[13,16] 
Third: [13,17] 
Forth: [13,18]
Current result for starting position [13,15] (vertically) is: 1507660
The values are 77 * 04 * 89 * 55 = 1507660
HORIZONTAL 4 POINTS: 
Start: [13,16] 
Second:[13,17] 
Third: [13,18] 
Forth: [13,19]
Current result for starting position [13,16] (vertically) is: 783200
The values are 04 * 89 * 55 * 40 = 783200
HORIZONTAL 4 POINTS: 
Start: [14,0] 
Second:[14,1] 
Third: [14,2] 
Forth: [14,3]
Current result for starting position [14,0] (vertically) is: 138112
The values are 04 * 52 * 08 * 83 = 138112
HORIZONTAL 4 POINTS: 
Start: [14,1] 
Second:[14,2] 
Third: [14,3] 
Forth: [14,4]
Current result for starting position [14,1] (vertically) is: 3349216
The values are 52 * 08 * 83 * 97 = 3349216
HORIZONTAL 4 POINTS: 
Start: [14,2] 
Second:[14,3] 
Third: [14,4] 
Forth: [14,5]
Current result for starting position [14,2] (vertically) is: 2254280
The values are 08 * 83 * 97 * 35 = 2254280
HORIZONTAL 4 POINTS: 
Start: [14,3] 
Second:[14,4] 
Third: [14,5] 
Forth: [14,6]
Current result for starting position [14,3] (vertically) is: 27896715
The values are 83 * 97 * 35 * 99 = 27896715
HORIZONTAL 4 POINTS: 
Start: [14,4] 
Second:[14,5] 
Third: [14,6] 
Forth: [14,7]
Current result for starting position [14,4] (vertically) is: 5377680
The values are 97 * 35 * 99 * 16 = 5377680
HORIZONTAL 4 POINTS: 
Start: [14,5] 
Second:[14,6] 
Third: [14,7] 
Forth: [14,8]
Current result for starting position [14,5] (vertically) is: 388080
The values are 35 * 99 * 16 * 07 = 388080
HORIZONTAL 4 POINTS: 
Start: [14,6] 
Second:[14,7] 
Third: [14,8] 
Forth: [14,9]
Current result for starting position [14,6] (vertically) is: 1075536
The values are 99 * 16 * 07 * 97 = 1075536
HORIZONTAL 4 POINTS: 
Start: [14,7] 
Second:[14,8] 
Third: [14,9] 
Forth: [14,10]
Current result for starting position [14,7] (vertically) is: 619248
The values are 16 * 07 * 97 * 57 = 619248
HORIZONTAL 4 POINTS: 
Start: [14,8] 
Second:[14,9] 
Third: [14,10] 
Forth: [14,11]
Current result for starting position [14,8] (vertically) is: 1238496
The values are 07 * 97 * 57 * 32 = 1238496
HORIZONTAL 4 POINTS: 
Start: [14,9] 
Second:[14,10] 
Third: [14,11] 
Forth: [14,12]
Current result for starting position [14,9] (vertically) is: 2830848
The values are 97 * 57 * 32 * 16 = 2830848
HORIZONTAL 4 POINTS: 
Start: [14,10] 
Second:[14,11] 
Third: [14,12] 
Forth: [14,13]
Current result for starting position [14,10] (vertically) is: 758784
The values are 57 * 32 * 16 * 26 = 758784
HORIZONTAL 4 POINTS: 
Start: [14,11] 
Second:[14,12] 
Third: [14,13] 
Forth: [14,14]
Current result for starting position [14,11] (vertically) is: 346112
The values are 32 * 16 * 26 * 26 = 346112
HORIZONTAL 4 POINTS: 
Start: [14,12] 
Second:[14,13] 
Third: [14,14] 
Forth: [14,15]
Current result for starting position [14,12] (vertically) is: 854464
The values are 16 * 26 * 26 * 79 = 854464
HORIZONTAL 4 POINTS: 
Start: [14,13] 
Second:[14,14] 
Third: [14,15] 
Forth: [14,16]
Current result for starting position [14,13] (vertically) is: 1762332
The values are 26 * 26 * 79 * 33 = 1762332
HORIZONTAL 4 POINTS: 
Start: [14,14] 
Second:[14,15] 
Third: [14,16] 
Forth: [14,17]
Current result for starting position [14,14] (vertically) is: 1830114
The values are 26 * 79 * 33 * 27 = 1830114
HORIZONTAL 4 POINTS: 
Start: [14,15] 
Second:[14,16] 
Third: [14,17] 
Forth: [14,18]
Current result for starting position [14,15] (vertically) is: 6898122
The values are 79 * 33 * 27 * 98 = 6898122
HORIZONTAL 4 POINTS: 
Start: [14,16] 
Second:[14,17] 
Third: [14,18] 
Forth: [14,19]
Current result for starting position [14,16] (vertically) is: 5762988
The values are 33 * 27 * 98 * 66 = 5762988
HORIZONTAL 4 POINTS: 
Start: [15,0] 
Second:[15,1] 
Third: [15,2] 
Forth: [15,3]
Current result for starting position [15,0] (vertically) is: 18741888
The values are 88 * 36 * 68 * 87 = 18741888
HORIZONTAL 4 POINTS: 
Start: [15,1] 
Second:[15,2] 
Third: [15,3] 
Forth: [15,4]
Current result for starting position [15,1] (vertically) is: 12139632
The values are 36 * 68 * 87 * 57 = 12139632
HORIZONTAL 4 POINTS: 
Start: [15,2] 
Second:[15,3] 
Third: [15,4] 
Forth: [15,5]
Current result for starting position [15,2] (vertically) is: 20907144
The values are 68 * 87 * 57 * 62 = 20907144
HORIZONTAL 4 POINTS: 
Start: [15,3] 
Second:[15,4] 
Third: [15,5] 
Forth: [15,6]
Current result for starting position [15,3] (vertically) is: 6149160
The values are 87 * 57 * 62 * 20 = 6149160
HORIZONTAL 4 POINTS: 
Start: [15,4] 
Second:[15,5] 
Third: [15,6] 
Forth: [15,7]
Current result for starting position [15,4] (vertically) is: 5088960
The values are 57 * 62 * 20 * 72 = 5088960
HORIZONTAL 4 POINTS: 
Start: [15,5] 
Second:[15,6] 
Third: [15,7] 
Forth: [15,8]
Current result for starting position [15,5] (vertically) is: 267840
The values are 62 * 20 * 72 * 03 = 267840
HORIZONTAL 4 POINTS: 
Start: [15,6] 
Second:[15,7] 
Third: [15,8] 
Forth: [15,9]
Current result for starting position [15,6] (vertically) is: 198720
The values are 20 * 72 * 03 * 46 = 198720
HORIZONTAL 4 POINTS: 
Start: [15,7] 
Second:[15,8] 
Third: [15,9] 
Forth: [15,10]
Current result for starting position [15,7] (vertically) is: 327888
The values are 72 * 03 * 46 * 33 = 327888
HORIZONTAL 4 POINTS: 
Start: [15,8] 
Second:[15,9] 
Third: [15,10] 
Forth: [15,11]
Current result for starting position [15,8] (vertically) is: 305118
The values are 03 * 46 * 33 * 67 = 305118
HORIZONTAL 4 POINTS: 
Start: [15,9] 
Second:[15,10] 
Third: [15,11] 
Forth: [15,12]
Current result for starting position [15,9] (vertically) is: 4678476
The values are 46 * 33 * 67 * 46 = 4678476
HORIZONTAL 4 POINTS: 
Start: [15,10] 
Second:[15,11] 
Third: [15,12] 
Forth: [15,13]
Current result for starting position [15,10] (vertically) is: 5593830
The values are 33 * 67 * 46 * 55 = 5593830
HORIZONTAL 4 POINTS: 
Start: [15,11] 
Second:[15,12] 
Third: [15,13] 
Forth: [15,14]
Current result for starting position [15,11] (vertically) is: 2034120
The values are 67 * 46 * 55 * 12 = 2034120
HORIZONTAL 4 POINTS: 
Start: [15,12] 
Second:[15,13] 
Third: [15,14] 
Forth: [15,15]
Current result for starting position [15,12] (vertically) is: 971520
The values are 46 * 55 * 12 * 32 = 971520
HORIZONTAL 4 POINTS: 
Start: [15,13] 
Second:[15,14] 
Third: [15,15] 
Forth: [15,16]
Current result for starting position [15,13] (vertically) is: 1330560
The values are 55 * 12 * 32 * 63 = 1330560
HORIZONTAL 4 POINTS: 
Start: [15,14] 
Second:[15,15] 
Third: [15,16] 
Forth: [15,17]
Current result for starting position [15,14] (vertically) is: 2249856
The values are 12 * 32 * 63 * 93 = 2249856
HORIZONTAL 4 POINTS: 
Start: [15,15] 
Second:[15,16] 
Third: [15,17] 
Forth: [15,18]
Current result for starting position [15,15] (vertically) is: 9936864
The values are 32 * 63 * 93 * 53 = 9936864
HORIZONTAL 4 POINTS: 
Start: [15,16] 
Second:[15,17] 
Third: [15,18] 
Forth: [15,19]
Current result for starting position [15,16] (vertically) is: 21426363
The values are 63 * 93 * 53 * 69 = 21426363
HORIZONTAL 4 POINTS: 
Start: [16,0] 
Second:[16,1] 
Third: [16,2] 
Forth: [16,3]
Current result for starting position [16,0] (vertically) is: 196224
The values are 04 * 42 * 16 * 73 = 196224
HORIZONTAL 4 POINTS: 
Start: [16,1] 
Second:[16,2] 
Third: [16,3] 
Forth: [16,4]
Current result for starting position [16,1] (vertically) is: 1864128
The values are 42 * 16 * 73 * 38 = 1864128
HORIZONTAL 4 POINTS: 
Start: [16,2] 
Second:[16,3] 
Third: [16,4] 
Forth: [16,5]
Current result for starting position [16,2] (vertically) is: 1109600
The values are 16 * 73 * 38 * 25 = 1109600
HORIZONTAL 4 POINTS: 
Start: [16,3] 
Second:[16,4] 
Third: [16,5] 
Forth: [16,6]
Current result for starting position [16,3] (vertically) is: 2704650
The values are 73 * 38 * 25 * 39 = 2704650
HORIZONTAL 4 POINTS: 
Start: [16,4] 
Second:[16,5] 
Third: [16,6] 
Forth: [16,7]
Current result for starting position [16,4] (vertically) is: 407550
The values are 38 * 25 * 39 * 11 = 407550
HORIZONTAL 4 POINTS: 
Start: [16,5] 
Second:[16,6] 
Third: [16,7] 
Forth: [16,8]
Current result for starting position [16,5] (vertically) is: 257400
The values are 25 * 39 * 11 * 24 = 257400
HORIZONTAL 4 POINTS: 
Start: [16,6] 
Second:[16,7] 
Third: [16,8] 
Forth: [16,9]
Current result for starting position [16,6] (vertically) is: 967824
The values are 39 * 11 * 24 * 94 = 967824
HORIZONTAL 4 POINTS: 
Start: [16,7] 
Second:[16,8] 
Third: [16,9] 
Forth: [16,10]
Current result for starting position [16,7] (vertically) is: 1786752
The values are 11 * 24 * 94 * 72 = 1786752
HORIZONTAL 4 POINTS: 
Start: [16,8] 
Second:[16,9] 
Third: [16,10] 
Forth: [16,11]
Current result for starting position [16,8] (vertically) is: 2923776
The values are 24 * 94 * 72 * 18 = 2923776
HORIZONTAL 4 POINTS: 
Start: [16,9] 
Second:[16,10] 
Third: [16,11] 
Forth: [16,12]
Current result for starting position [16,9] (vertically) is: 974592
The values are 94 * 72 * 18 * 08 = 974592
HORIZONTAL 4 POINTS: 
Start: [16,10] 
Second:[16,11] 
Third: [16,12] 
Forth: [16,13]
Current result for starting position [16,10] (vertically) is: 476928
The values are 72 * 18 * 08 * 46 = 476928
HORIZONTAL 4 POINTS: 
Start: [16,11] 
Second:[16,12] 
Third: [16,13] 
Forth: [16,14]
Current result for starting position [16,11] (vertically) is: 192096
The values are 18 * 08 * 46 * 29 = 192096
HORIZONTAL 4 POINTS: 
Start: [16,12] 
Second:[16,13] 
Third: [16,14] 
Forth: [16,15]
Current result for starting position [16,12] (vertically) is: 341504
The values are 08 * 46 * 29 * 32 = 341504
HORIZONTAL 4 POINTS: 
Start: [16,13] 
Second:[16,14] 
Third: [16,15] 
Forth: [16,16]
Current result for starting position [16,13] (vertically) is: 1707520
The values are 46 * 29 * 32 * 40 = 1707520
HORIZONTAL 4 POINTS: 
Start: [16,14] 
Second:[16,15] 
Third: [16,16] 
Forth: [16,17]
Current result for starting position [16,14] (vertically) is: 2301440
The values are 29 * 32 * 40 * 62 = 2301440
HORIZONTAL 4 POINTS: 
Start: [16,15] 
Second:[16,16] 
Third: [16,17] 
Forth: [16,18]
Current result for starting position [16,15] (vertically) is: 6031360
The values are 32 * 40 * 62 * 76 = 6031360
HORIZONTAL 4 POINTS: 
Start: [16,16] 
Second:[16,17] 
Third: [16,18] 
Forth: [16,19]
Current result for starting position [16,16] (vertically) is: 6785280
The values are 40 * 62 * 76 * 36 = 6785280
HORIZONTAL 4 POINTS: 
Start: [17,0] 
Second:[17,1] 
Third: [17,2] 
Forth: [17,3]
Current result for starting position [17,0] (vertically) is: 2036880
The values are 20 * 69 * 36 * 41 = 2036880
HORIZONTAL 4 POINTS: 
Start: [17,1] 
Second:[17,2] 
Third: [17,3] 
Forth: [17,4]
Current result for starting position [17,1] (vertically) is: 7332768
The values are 69 * 36 * 41 * 72 = 7332768
HORIZONTAL 4 POINTS: 
Start: [17,2] 
Second:[17,3] 
Third: [17,4] 
Forth: [17,5]
Current result for starting position [17,2] (vertically) is: 3188160
The values are 36 * 41 * 72 * 30 = 3188160
HORIZONTAL 4 POINTS: 
Start: [17,3] 
Second:[17,4] 
Third: [17,5] 
Forth: [17,6]
Current result for starting position [17,3] (vertically) is: 2036880
The values are 41 * 72 * 30 * 23 = 2036880
HORIZONTAL 4 POINTS: 
Start: [17,4] 
Second:[17,5] 
Third: [17,6] 
Forth: [17,7]
Current result for starting position [17,4] (vertically) is: 4371840
The values are 72 * 30 * 23 * 88 = 4371840
HORIZONTAL 4 POINTS: 
Start: [17,5] 
Second:[17,6] 
Third: [17,7] 
Forth: [17,8]
Current result for starting position [17,5] (vertically) is: 2064480
The values are 30 * 23 * 88 * 34 = 2064480
HORIZONTAL 4 POINTS: 
Start: [17,6] 
Second:[17,7] 
Third: [17,8] 
Forth: [17,9]
Current result for starting position [17,6] (vertically) is: 4266592
The values are 23 * 88 * 34 * 62 = 4266592
HORIZONTAL 4 POINTS: 
Start: [17,7] 
Second:[17,8] 
Third: [17,9] 
Forth: [17,10]
Current result for starting position [17,7] (vertically) is: 18364896
The values are 88 * 34 * 62 * 99 = 18364896
HORIZONTAL 4 POINTS: 
Start: [17,8] 
Second:[17,9] 
Third: [17,10] 
Forth: [17,11]
Current result for starting position [17,8] (vertically) is: 14399748
The values are 34 * 62 * 99 * 69 = 14399748
HORIZONTAL 4 POINTS: 
Start: [17,9] 
Second:[17,10] 
Third: [17,11] 
Forth: [17,12]
Current result for starting position [17,9] (vertically) is: 34728804
The values are 62 * 99 * 69 * 82 = 34728804
HORIZONTAL 4 POINTS: 
Start: [17,10] 
Second:[17,11] 
Third: [17,12] 
Forth: [17,13]
Current result for starting position [17,10] (vertically) is: 37529514
The values are 99 * 69 * 82 * 67 = 37529514
HORIZONTAL 4 POINTS: 
Start: [17,11] 
Second:[17,12] 
Third: [17,13] 
Forth: [17,14]
Current result for starting position [17,11] (vertically) is: 22366074
The values are 69 * 82 * 67 * 59 = 22366074
HORIZONTAL 4 POINTS: 
Start: [17,12] 
Second:[17,13] 
Third: [17,14] 
Forth: [17,15]
Current result for starting position [17,12] (vertically) is: 27552410
The values are 82 * 67 * 59 * 85 = 27552410
HORIZONTAL 4 POINTS: 
Start: [17,13] 
Second:[17,14] 
Third: [17,15] 
Forth: [17,16]
Current result for starting position [17,13] (vertically) is: 24864370
The values are 67 * 59 * 85 * 74 = 24864370
HORIZONTAL 4 POINTS: 
Start: [17,14] 
Second:[17,15] 
Third: [17,16] 
Forth: [17,17]
Current result for starting position [17,14] (vertically) is: 1484440
The values are 59 * 85 * 74 * 04 = 1484440
HORIZONTAL 4 POINTS: 
Start: [17,15] 
Second:[17,16] 
Third: [17,17] 
Forth: [17,18]
Current result for starting position [17,15] (vertically) is: 905760
The values are 85 * 74 * 04 * 36 = 905760
HORIZONTAL 4 POINTS: 
Start: [17,16] 
Second:[17,17] 
Third: [17,18] 
Forth: [17,19]
Current result for starting position [17,16] (vertically) is: 170496
The values are 74 * 04 * 36 * 16 = 170496
HORIZONTAL 4 POINTS: 
Start: [18,0] 
Second:[18,1] 
Third: [18,2] 
Forth: [18,3]
Current result for starting position [18,0] (vertically) is: 1481900
The values are 20 * 73 * 35 * 29 = 1481900
HORIZONTAL 4 POINTS: 
Start: [18,1] 
Second:[18,2] 
Third: [18,3] 
Forth: [18,4]
Current result for starting position [18,1] (vertically) is: 5779410
The values are 73 * 35 * 29 * 78 = 5779410
HORIZONTAL 4 POINTS: 
Start: [18,2] 
Second:[18,3] 
Third: [18,4] 
Forth: [18,5]
Current result for starting position [18,2] (vertically) is: 2454270
The values are 35 * 29 * 78 * 31 = 2454270
HORIZONTAL 4 POINTS: 
Start: [18,3] 
Second:[18,4] 
Third: [18,5] 
Forth: [18,6]
Current result for starting position [18,3] (vertically) is: 6310980
The values are 29 * 78 * 31 * 90 = 6310980
HORIZONTAL 4 POINTS: 
Start: [18,4] 
Second:[18,5] 
Third: [18,6] 
Forth: [18,7]
Current result for starting position [18,4] (vertically) is: 217620
The values are 78 * 31 * 90 * 01 = 217620
HORIZONTAL 4 POINTS: 
Start: [18,5] 
Second:[18,6] 
Third: [18,7] 
Forth: [18,8]
Current result for starting position [18,5] (vertically) is: 206460
The values are 31 * 90 * 01 * 74 = 206460
HORIZONTAL 4 POINTS: 
Start: [18,6] 
Second:[18,7] 
Third: [18,8] 
Forth: [18,9]
Current result for starting position [18,6] (vertically) is: 206460
The values are 90 * 01 * 74 * 31 = 206460
HORIZONTAL 4 POINTS: 
Start: [18,7] 
Second:[18,8] 
Third: [18,9] 
Forth: [18,10]
Current result for starting position [18,7] (vertically) is: 112406
The values are 01 * 74 * 31 * 49 = 112406
HORIZONTAL 4 POINTS: 
Start: [18,8] 
Second:[18,9] 
Third: [18,10] 
Forth: [18,11]
Current result for starting position [18,8] (vertically) is: 7980826
The values are 74 * 31 * 49 * 71 = 7980826
HORIZONTAL 4 POINTS: 
Start: [18,9] 
Second:[18,10] 
Third: [18,11] 
Forth: [18,12]
Current result for starting position [18,9] (vertically) is: 5176752
The values are 31 * 49 * 71 * 48 = 5176752
HORIZONTAL 4 POINTS: 
Start: [18,10] 
Second:[18,11] 
Third: [18,12] 
Forth: [18,13]
Current result for starting position [18,10] (vertically) is: 14361312
The values are 49 * 71 * 48 * 86 = 14361312
HORIZONTAL 4 POINTS: 
Start: [18,11] 
Second:[18,12] 
Third: [18,13] 
Forth: [18,14]
Current result for starting position [18,11] (vertically) is: 23740128
The values are 71 * 48 * 86 * 81 = 23740128
HORIZONTAL 4 POINTS: 
Start: [18,12] 
Second:[18,13] 
Third: [18,14] 
Forth: [18,15]
Current result for starting position [18,12] (vertically) is: 5349888
The values are 48 * 86 * 81 * 16 = 5349888
HORIZONTAL 4 POINTS: 
Start: [18,13] 
Second:[18,14] 
Third: [18,15] 
Forth: [18,16]
Current result for starting position [18,13] (vertically) is: 2563488
The values are 86 * 81 * 16 * 23 = 2563488
HORIZONTAL 4 POINTS: 
Start: [18,14] 
Second:[18,15] 
Third: [18,16] 
Forth: [18,17]
Current result for starting position [18,14] (vertically) is: 1699056
The values are 81 * 16 * 23 * 57 = 1699056
HORIZONTAL 4 POINTS: 
Start: [18,15] 
Second:[18,16] 
Third: [18,17] 
Forth: [18,18]
Current result for starting position [18,15] (vertically) is: 104880
The values are 16 * 23 * 57 * 05 = 104880
HORIZONTAL 4 POINTS: 
Start: [18,16] 
Second:[18,17] 
Third: [18,18] 
Forth: [18,19]
Current result for starting position [18,16] (vertically) is: 353970
The values are 23 * 57 * 05 * 54 = 353970
HORIZONTAL 4 POINTS: 
Start: [19,0] 
Second:[19,1] 
Third: [19,2] 
Forth: [19,3]
Current result for starting position [19,0] (vertically) is: 268380
The values are 01 * 70 * 54 * 71 = 268380
HORIZONTAL 4 POINTS: 
Start: [19,1] 
Second:[19,2] 
Third: [19,3] 
Forth: [19,4]
Current result for starting position [19,1] (vertically) is: 22275540
The values are 70 * 54 * 71 * 83 = 22275540
HORIZONTAL 4 POINTS: 
Start: [19,2] 
Second:[19,3] 
Third: [19,4] 
Forth: [19,5]
Current result for starting position [19,2] (vertically) is: 16229322
The values are 54 * 71 * 83 * 51 = 16229322
HORIZONTAL 4 POINTS: 
Start: [19,3] 
Second:[19,4] 
Third: [19,5] 
Forth: [19,6]
Current result for starting position [19,3] (vertically) is: 16229322
The values are 71 * 83 * 51 * 54 = 16229322
HORIZONTAL 4 POINTS: 
Start: [19,4] 
Second:[19,5] 
Third: [19,6] 
Forth: [19,7]
Current result for starting position [19,4] (vertically) is: 15772158
The values are 83 * 51 * 54 * 69 = 15772158
HORIZONTAL 4 POINTS: 
Start: [19,5] 
Second:[19,6] 
Third: [19,7] 
Forth: [19,8]
Current result for starting position [19,5] (vertically) is: 3040416
The values are 51 * 54 * 69 * 16 = 3040416
HORIZONTAL 4 POINTS: 
Start: [19,6] 
Second:[19,7] 
Third: [19,8] 
Forth: [19,9]
Current result for starting position [19,6] (vertically) is: 5484672
The values are 54 * 69 * 16 * 92 = 5484672
HORIZONTAL 4 POINTS: 
Start: [19,7] 
Second:[19,8] 
Third: [19,9] 
Forth: [19,10]
Current result for starting position [19,7] (vertically) is: 3351744
The values are 69 * 16 * 92 * 33 = 3351744
HORIZONTAL 4 POINTS: 
Start: [19,8] 
Second:[19,9] 
Third: [19,10] 
Forth: [19,11]
Current result for starting position [19,8] (vertically) is: 2331648
The values are 16 * 92 * 33 * 48 = 2331648
HORIZONTAL 4 POINTS: 
Start: [19,9] 
Second:[19,10] 
Third: [19,11] 
Forth: [19,12]
Current result for starting position [19,9] (vertically) is: 8889408
The values are 92 * 33 * 48 * 61 = 8889408
HORIZONTAL 4 POINTS: 
Start: [19,10] 
Second:[19,11] 
Third: [19,12] 
Forth: [19,13]
Current result for starting position [19,10] (vertically) is: 4154832
The values are 33 * 48 * 61 * 43 = 4154832
HORIZONTAL 4 POINTS: 
Start: [19,11] 
Second:[19,12] 
Third: [19,13] 
Forth: [19,14]
Current result for starting position [19,11] (vertically) is: 6547008
The values are 48 * 61 * 43 * 52 = 6547008
HORIZONTAL 4 POINTS: 
Start: [19,12] 
Second:[19,13] 
Third: [19,14] 
Forth: [19,15]
Current result for starting position [19,12] (vertically) is: 136396
The values are 61 * 43 * 52 * 01 = 136396
HORIZONTAL 4 POINTS: 
Start: [19,13] 
Second:[19,14] 
Third: [19,15] 
Forth: [19,16]
Current result for starting position [19,13] (vertically) is: 199004
The values are 43 * 52 * 01 * 89 = 199004
HORIZONTAL 4 POINTS: 
Start: [19,14] 
Second:[19,15] 
Third: [19,16] 
Forth: [19,17]
Current result for starting position [19,14] (vertically) is: 87932
The values are 52 * 01 * 89 * 19 = 87932
HORIZONTAL 4 POINTS: 
Start: [19,15] 
Second:[19,16] 
Third: [19,17] 
Forth: [19,18]
Current result for starting position [19,15] (vertically) is: 113297
The values are 01 * 89 * 19 * 67 = 113297
HORIZONTAL 4 POINTS: 
Start: [19,16] 
Second:[19,17] 
Third: [19,18] 
Forth: [19,19]
Current result for starting position [19,16] (vertically) is: 5438256
The values are 89 * 19 * 67 * 48 = 5438256

Process finished with exit code 0
