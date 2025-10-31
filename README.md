## Combinational Digital Lock System



-Objective:

The primary goal of this circuit is to function as a digital lock that:

Unlocks:(Unlock LED lights up) only upon entering one of two specific secret codes

Activates a Warning light in all other incorrect entry attempts



-System Components and Logic:

Inputs:M.D2,D1,D0

Outputs:Unlock(Green LED),Warning(Red LED)

Logic Gates: The circuit uses two AND gates, one OR gate connecting the two AND gate outputs, and NOT gates (inverters) on specific inputs



-Secret Unlock Combinations:

The circuit is designed to activate the Unlock output (Green LED = 1)  when  any of the following two combinations are entered:



M=0,D2=1,D1=0,D0=1

M=1.D2=0.D1=1,D0=1

