# TriangularS
A Musical composition made with PureData based on mathmatical realtions

## Background 
The relationship in the work is determined by an arithmetic series called Triangular number.
N will be called triangular number if N can be arranged in the form of an equilateral triangle.
Therefore, most of the relationships at this project will be based on divisions in 3 and on the series of numbers mentioned above.
The first elements of the series:
n	1	2	3	4	4
f(n)	1	3	6	10	15

## Abstractions: 

###### Ntt.pd  
Converts each n number to be the nth element in the series. Ie- calculates f(n)<br>

###### Envelope.pd
Sound envelope utilities - Uses a random number which given in the object inlets. The attack and deacy always have a 1/3 or 1/6 relationship between them and the random number was selceted)<br>
###### MyAm.pd 
Am amplifier,3 inlets:<br>
1. n when the carry is the nth element in the series ie f(n)<br>
2. m when the emulator is f (n + m)<br>
3. The length of the sound we want: 1 for short, 2 for medium, 3 for long.<br>


###### MyFm.pd 
Fm amplifier , 4 inlets:<br>
1. n when the carry is the N element in the series ie f(n)<br>
2. Harmonicty will be - n<br>
3. Index will select Randomly from n/3 n/6 and n/9<br>
4. The length of the sound we want: 1 for short, 2 for medium, 3 for long.<br>


###### Main.pd
controls for the complete musical piece. <br>

## Usage:
 1) Raise the main volume 
			2) Press play





## More about the project
The work is a total length of one and a half minutes divided into 3 equal parts.
In the first part, the sounds will be short and relatively low, and the synthesizers will use medium-short sound envelops,  there will be no polyphony. The sound speed rate will be relatively slow.
In the second part we will use all the lengths of the envelopes and in addition we will support polyphony of 2 sounds at the same time.
In the third part we will use all the lengths of the envelopes and in addition we will support polyphony of 3 sounds simultaneously.

