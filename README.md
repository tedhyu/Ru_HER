# Data for Ru-loaded pyrrolic-N-doped extensively graphitized porous carbon for high performance electrochemical hydrogen evolution

Archive of data.  The data is calculated from SeqQUEST and JDFTx ab-initio quantum software.  They are used to calculate energy efficiencies and geometries of Ru Hydrogen Evolution Reaction catalyst on N-graphene support.

<hr/>

##Folders:

I) Seqquest - DFT Calculations using QUEST:  https://dft.sandia.gov/quest/
	File types:
		.in - Input files
		.out - Output files
		.xyz - Coordinate files
	A)  Volmer
	B)  Heyrovsky
	C)  Tafel - File name notation:  XXX_Ru39_H#_&
			XXX = pyrr (pyrrolic), graphe (graphene), graphi (graphitic), pyri (pyridinic)
				describes the support underneath the Ru39 metal
			# = The number representing how many of the surface sites (coverage) are occupied by hydrogen
			& = Different configurational isotopes for the coverage from a-f

II)  JDFTx
	A)  Volmer
	B)  Heyrovsky
	C)  Tafel