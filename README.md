java cUniversity of Wollongong
Faculty of Engineering and Information Sciences

MECH201 Engineering Analysis
Spring Session – 2024

Assignment 2

Project Description: This project aims to solve the engineering ODE problems with the help of Matlab program. 
Project report due: 11 Oct 2024 (Friday in Session Week 11) 
. 
Rules:
1.The assignment may be completed individually or by a group up to 3 students. The group formation is your own responsibility. Members may be from the same or different tutorial groups.
2.No collaboration between groups is permitted. Any case of plagiarism will be penalized, and students should make themselves aware of the university policies regarding plagiarism.
3.The assignment should be submitted to Moodle. Late submission will incur a penalty as described in the subject outline. 
4.If the assignment is completed by the group, a statement indicating the effort or contribution to the assignment by each member and signed by all members must be included at the beginning of the report, or all students agree that they have contributed equally to the report –add a statement at the front of the report, signed by all members.
5.Please make sure your MATLAB code is well commented to ensure readability and that your variable and function names are understandable. Use the lecture and tutorial examples for guidance. Scripts without comments and badly named variables will be graded poorly.
6.The assignment must be submitted as a formal typed report. You need to include the analysis of the problem, the procedure for Matlab solution, and a discussion of the results.
7.All MATLAB code (script files and function files) must be uploaded into the Moodle as part of your report.

Question 1: Double integral (35 marks)
Evaluate the following double integral. Note that the x boundaries are a function of y

(a)Manually solve this question by using one Simpson 1/3 rule in the x-direction and two Simpson 1/3 rules in the y-direction.					(15 marks)
(It is requested to show the detailed calculation procedure in your report, including the intervals, meshing, function values at each node, and integral for x and y, etc)
(b)Develop a MATLAB M-file based on the Simpson 1/3 rules for evaluation of the double integral of the above function with any number of Simpson 1/3 rules in the x- and y-directions. Note the number of Simpson 1/3 can be different in the x- and y-directions

Then, use the developed code to calculate the above double integral by different numbers of Simpson 1/3 rules until an accurate result is achieved. 			(20 marks)

(The M-file must be well commented and included in the report, and the developed code must be submitted for checking. You need to try different numbers of Simpson 1/3 rules in x- and y-directions until an accurate result is achieved. And justify why the final result is acceptable).

(c)Choose a proper MATLAB built-in function and develop an M-file script to re-calculate the above Item (b). 	(This q代 写MECH201、MATLAB
代做程序编程语言uestion is not compulsory for the report. However, the bonus 5 marks will be awarded if your answer is correct)

Question 2: Initial value system of ODEs (35 marks)
Three linked bungee jumpers are depicted in the following Figure. If the bungee cords are idealized as linear springs (i.e., governed by Hooke’s law), the following differential equations based on force balances can be developed:
	
where mi = the mass of jumper i (kg), kj = the spring constant for cord j (N/m), xi = the displacement of jumper i measured downward from the jumper’s equilibrium position (m), and g = gravitational acceleration (9.81 m/s2). 

Solve the positions and velocities of the three jumpers given the initial conditions that all positions and velocities are zero at t = 0. Use the following parameters for your calculations: m1 = 60 kg, m2 = 80 kg, m3 = 100 kg, k1=80(N/m), k2 = 120 (N/m),  k3 = 80 (N/m).

(a)Manually convert the 2nd order ODE problems to the 1st order ODEs		(10 marks)
(It is requested to show the detailed equation deriving procedure, and the initial values in your report)
(b)Develop a script M-file to solve the above problem by 4th order Runge Kutta method. Matlab Build-in function is not allowed for this purpose. Choose a proper time step for an accurate solution up to 100 sec, and plot the positions and velocities of three jumpers into two figures. You are requested to add the proper title, axis labels and legend to the figures. 	(20 marks)
(The M-file must be well commented and included in the report, and the developed code must be submitted for checking).

(c)Choose a proper MATLAB built-in function and develop an M-file script to re-calculate the above Item (b). 									(5 marks)
(The M-file must be well commented and included in the report, and the developed code must be submitted for checking).

Question 3: Boundary value ODE  (30 marks)
The temperature distribution in a tapered conical cooling fin as shown in the following Figure is described by the following differential equation, which has been nondimensionalized,
	
where u = temperature (0 ≤ u ≤ 1), x = axial distance (0 ≤ x ≤ 1), and p is a nondimensional parameter that describes the heat transfer and geometry,
	
where h = a heat transfer coefficient, k = thermal conductivity, L = the length or height of the cone, and m = the slope of the cone wall. The equation has the boundary conditions

a)Manually derive the finite-difference formula with an interval of . 	(10 marks)
(It is requested to show the detailed calculation procedure in your report, including the intervals, meshing, equation of each node, matrix formation of system of equations, etc)
b)Write a script M-file to obtain the solution and plot temperature versus axial distance for various values of p = 6, 10, 30, and 70. Please choose a proper interval  for an accurate solution. The proper title, axis labels and legend are requested to be added into the figures.		(20 marks)

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
