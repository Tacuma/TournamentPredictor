#Tournament Predictor

#Data Structurs/Concepts Used:
Computer Architecture; Branch Prediction
File Parsing, 
Local Predictor, Global Predictors, Tournament Predictors

The Tournament predictor helps 

#Output:
My Report can be found at the link:
https://github.com/Tacuma/TournamentPredictor/files/122539/Report.docx


	
####inp.txt
##### This represents a sample of the entirety of the input found here:
##### https://github.com/Tacuma/TournamentPredictor/files/122548/trace.txt

	0 : fe58 : C : 0
	1 : fe5c : L : 8179e55
	2 : fe60 : C : 0
	3 : fe64 : C : 0
	4 : fe68 : C : 0
	5 : fe6c : S : 8179e55
	6 : fe70 : L : 8167158
	7 : fe74 : C : 0
	8 : fe78 : C : 0
	9 : fe7c : L : 8167158
	10 : fe80 : C : 0
	11 : fe84 : B : 0
	12 : fe88 : C : 0
	13 : fe8c : B : 0
	14 : fe90 : C : 0
	15 : fe94 : C : 0
	16 : fe98 : C : 0
	17 : fe9c : C : 0
	18 : fea0 : L : 8179e54
	19 : fea4 : C : 0
	20 : fea8 : C : 0
	
Each line of the input approximates an assembly language instruction eg. MIPS. 
We only concern ourselves with the instructions labeled B. The Tournament predictor's purpose is help reduce
branch penalties in Instruction Level Parallism by predicting whether an assembly language branch instruction is taken or not taken.
For more on Branch Prediction: https://en.wikipedia.org/wiki/Branch_predictor


#Description:
####MAINTENANCE  PROJECT.pdf
https://github.com/Tacuma/Explosion/files/122505/MAINTENANCE.PROJECT.pdf

Branch Predictor

In this project, you will implement the simulator of a tournament branch predictor and execute it with various parameters on a program trace. Your goal is to find out the prediction accuracy for various combinations of predictor parameters.
The following paramaters should be considered:

•	Total amount of storage used for predictors (4/16/64/256/1024/4096Kbits). The global predictor and 2-level local predictor should share the storage evenly.

•	Number of bits per predictor (2/3).

•	Length of tracked branch history (2/4/8). Use the same numer fo both the global and local predictor.
The format of each line in the trac files is as follow:
    Instruction # : PC (in Hex) : Instruction type : Execution 
You only need to consider instruction type of 'B' (branches), for which 'Execution' is 0 (not taken) or 1 (taken).
The following items should be included in your submission in a single zipped file:
1.	Source code
2.	A readme file with instructions to compile and execute your program
3.	A document that presents prediction accuracy for the parameter combinations. Figures are expected.
Due: November 6th, 5PM.
Trace files:
•	Small trace for test (4.4K)
•	Large trace for full study (11M)


https://cloud.githubusercontent.com/assets/2325736/12906778/99777864-ceb1-11e5-9a50-3ceadae99ea8.jpg


 

