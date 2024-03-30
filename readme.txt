This Assignment has been completed by Virendra Kumar Gautam - Howrah, India.

1. In project, the well know searching algorithms Binary Search and Fibonacci search have been studied, implemented (in C).
2. There comparative study both theoratical and experimal has also been done
3. The report of critical analysis and observation of the study has been compiled 
	into the "results_assignment_01.pdf" which is into the both docx and parent folder

4. The Environment used to complete this assignment is described as below

	HP – 2000
	RAM – 2GB
	Processor - Intel® Core™ i3-3110M CPU @ 2.40GHz × 4
	OS – Ubuntu 16.04 (64 bit)
------------------------------------------------------------------------------------------------------------------------------------------------------------

Details about how to run the program

1. The compiled file and dataset file should be in the same folder
2. If not, then you must input the path of the data file as mentioned below.
3. Open terminal
4. input the object file name of the searching algorithm together with the name of a datafile contained in the same folder

	e.g. gautam@Gautam:~$ ./bsearch data_1x10_5.dat

5. On execution, it will display the size of the dataset
6. Then, ask you to enter the key to be search into the dataset

7. The program after execution, will print the summary as below
	Found	Index	Key		Elapsed_time
	Y		1		3		3.000
	or
	Found	Index	Key		Elapsed_time
	N		None	-1		5.000

8. This summary will also be written and saved into a file in a format mention below

	BS_RES_data_1x10_5.dat, OR
	FS_RES_data_1x10_5.dat
	
	where, BS = Binary Search, FS = Fibonacci Search, RES = Result
		   In data_1x10_5.dat, the 1x10_5 stands for 1*10^5 
		   which is the size of the sorted dataset written in this file.

-------------------------------------------------------------------------------------------------------------------------------------------------------------

Details about the directories and folders

1. images 	- The folder contains the screenshots of the results obtained on the terminal during the experiments
2. docx		- The folde contains the following important files
				(i). results_assignment_01.pdf
				(ii). readme.txt
				(iii). results.ods   --- libreOffice calc file.
3. graphs-pictires
			- contains three pictures of the graphical representation of the results.
4.datasets	- contains the sorted datasets which have been utilized to perform the experiment.
5.source	- contains the source .c files, object files of the same, the result files e.g. (BS_RES_data_1x10_5.dat).
