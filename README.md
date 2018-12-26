# SysTarPKCTool

Detailed protocol for usage of tool is as following (Figure 4):

1.	Prepare 3D structure of query molecule, and save it as .sdf file.
2.	Download SysTarPKC_Tool.zip from https://www.github.com/undwivedi/SysTarPKCTool  
3.	Extract the .zip file and double click the executable ‘Run_SysTarPKC_Tool.jar’.
4.	Click ‘Step1 button’, to open a file browser for selection of .sdf file of query molecule. This process will provide input value for SBML simulator, which is a value from PKC domain derived for query structure. This float value is input for SBMLsimulator.
5.	Now click ‘Step2 button’, and load the ‘PKC_Model.xml’ model. 
6.	To configure SBMLsimulator, set two variables as cell = 1.0 ml and Q = “float value from Step 1”. Make sure that you have selected ‘Euler method for differential equation solver’ for End time = 100 and Number of steps = 1000. Now run the process.
7.	After completion of process, go to ‘Computed Data’ tab, and pick the value for R1_0 variable at Time = 50. 
8.	Put the Collected R1_0 value into Text box before ‘Step 3 button’ and calculate value of ‘Selectivity Score’.

