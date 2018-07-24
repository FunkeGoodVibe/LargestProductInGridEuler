# LargestProductInGridEuler
# In the 20×20 grid below, four numbers along a diagonal line have been marked in red.

 08 02 22 97 38 15 00 40 00 75 04 05 07 78 52 12 50 77 91 08 <br/>
 49 49 99 40 17 81 18 57 60 87 17 40 98 43 69 48 04 56 62 00<br/>
 81 49 31 73 55 79 14 29 93 71 40 67 53 88 30 03 49 13 36 65<br/>
52 70 95 23 04 60 11 42 69 24 68 56 01 32 56 71 37 02 36 91<br/>
22 31 16 71 51 67 63 89 41 92 36 54 22 40 40 28 66 33 13 80<br/>
24 47 32 60 99 03 45 02 44 75 33 53 78 36 84 20 35 17 12 50<br/>
32 98 81 28 64 23 67 10 <b>26</b> 38 40 67 59 54 70 66 18 38 64 70<br/>
67 26 20 68 02 62 12 20 95 <b>63</b> 94 39 63 08 40 91 66 49 94 21<br/>
24 55 58 05 66 73 99 26 97 17 <b>78</b> 78 96 83 14 88 34 89 63 72<br/>
21 36 23 09 75 00 76 44 20 45 35 <b>14</b> 00 61 33 97 34 31 33 95<br/>
78 17 53 28 22 75 31 67 15 94 03 80 04 62 16 14 09 53 56 92<br/>
16 39 05 42 96 35 31 47 55 58 88 24 00 17 54 24 36 29 85 57<br/>
86 56 00 48 35 71 89 07 05 44 44 37 44 60 21 58 51 54 17 58<br/>
19 80 81 68 05 94 47 69 28 73 92 13 86 52 17 77 04 89 55 40<br/>
04 52 08 83 97 35 99 16 07 97 57 32 16 26 26 79 33 27 98 66<br/>
88 36 68 87 57 62 20 72 03 46 33 67 46 55 12 32 63 93 53 69<br/>
04 42 16 73 38 25 39 11 24 94 72 18 08 46 29 32 40 62 76 36<br/>
20 69 36 41 72 30 23 88 34 62 99 69 82 67 59 85 74 04 36 16<br/>
20 73 35 29 78 31 90 01 74 31 49 71 48 86 81 16 23 57 05 54<br/>
01 70 54 71 83 51 54 69 16 92 33 48 61 43 52 01 89 19 67 48<br/>
<br/>
<br/>
The product of these numbers is 26 × 63 × 78 × 14 = 1788696.
<br/>
What is the greatest product of four adjacent numbers in the same direction (up, down, left, right, or diagonally) in the 20×20 grid?
<br/>
<br/>

### Testing by printing output to screen
<br/>
<br/>
HORIZONTAL 4 POINTS: <br/>
Start: [0,0] <br/>
Second:[0,1] <br/>
Third: [0,2] <br/>
Forth: [0,3]<br/>
<br/>
Current result for starting position [0,0] (vertically) is: 34144<br/>
The values are 08 * 02 * 22 * 97 = 34144<br/>
The current maximum result is 34144 <br/>
<br/>
<br/>

HORIZONTAL 4 POINTS: <br/>
Start: [0,1] <br/>
Second:[0,2] <br/>
Third: [0,3] <br/>
Forth: [0,4]<br/>
Current result for starting position [0,1] (vertically) is: 162184<br/>
The values are 02 * 22 * 97 * 38 = 162184<br/>
The current maximum result is 162184 <br/>
<br/>
<br/>

HORIZONTAL 4 POINTS: <br/>
Start: [0,2] <br/>
Second:[0,3] <br/>
Third: [0,4] <br/>
Forth: [0,5]<br/>
Current result for starting position [0,2] (vertically) is: 1216380<br/>
The values are 22 * 97 * 38 * 15 = 1216380<br/>
The current maximum result is 1216380 <br/>

<br/>
<br/>

<br/>etc ..... etc......<br/><br/>
HORIZONTAL 4 POINTS: <br/>
Start: [0,3] <br/>
Second:[0,4] <br/>
Third: [0,5] <br/>
Forth: [0,6]<br/>

Current result for starting position [19,12] (vertically) is: 136396<br/>
The values are 61 * 43 * 52 * 01 = 136396<br/>
HORIZONTAL 4 POINTS: <br/>
Start: [19,13] <br/>
Second:[19,14] <br/>
Third: [19,15] <br/>
Forth: [19,16]<br/>
<br/>
Current result for starting position [19,13] (vertically) is: 199004<br/>
The values are 43 * 52 * 01 * 89 = 199004<br/>
<br/>
<br/>

HORIZONTAL 4 POINTS: <br/>
Start: [19,14] <br/>
Second:[19,15] <br/>
Third: [19,16] <br/>
Forth: [19,17]<br/>
Current result for starting position [19,14] (vertically) is: 87932<br/>
The values are 52 * 01 * 89 * 19 = 87932<br/>
<br/>
<br/>
HORIZONTAL 4 POINTS: <br/>
Start: [19,15] <br/>
Second:[19,16] <br/>
Third: [19,17] <br/>
Forth: [19,18]<br/>
Current result for starting position [19,15] (vertically) is: 113297<br/>
The values are 01 * 89 * 19 * 67 = 113297<br/>
<br/>

HORIZONTAL 4 POINTS: <br/>
Start: [19,16] <br/>
Second:[19,17] <br/>
Third: [19,18] <br/>
Forth: [19,19]<br/>
Current result for starting position [19,16] (vertically) is: 5438256<br/>
The values are 89 * 19 * 67 * 48 = 5438256<br/>
<br/>

Process finished with exit code 0 
