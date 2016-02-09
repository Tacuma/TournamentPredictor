#Tournament Predictor

#Data Structurs/Concepts Used:
Computer Architecture; Branch Prediction
File Parsing, 
Local Predictor, Global Predictors, Tournament Predictors

#Output:
My Report can be found at the link:
https://github.com/Tacuma/TournamentPredictor/files/122539/Report.docx


	
####inp.txt
##### Each pair of letters represents an edge between two vertices



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





 

