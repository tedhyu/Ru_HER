#Data for Ru-loaded pyrrolic-N-doped extensively graphitized porous carbon for high performance electrochemical hydrogen evolution

Archive of data.  The data is calculated from SeqQUEST and JDFTx ab-initio quantum software.  They are used to calculate energy efficiencies and geometries of Ru Hydrogen Evolution Reaction catalyst on N-graphene support.

<hr/>

##Folders:

I) Seqquest - DFT Calculations using QUEST:  https://dft.sandia.gov/quest/
<br>	File types:
<br>		.in - Input files
<br>		.out - Output files
<br>        .neb_out - NEB Output files
<br>		.xyz - Coordinate files
<br>	A)  Volmer
<br>	B)  Heyrovsky
<br>	C)  Tafel 

<br>File name notation:  XXX_Ru39_H#_&
			<br>XXX = pyrr (pyrrolic), graphe (graphene), graphi (graphitic), pyri (pyridinic)
				describes the support underneath the Ru39 metal
			<br># = The number representing how many of the surface sites (coverage) are occupied by hydrogen
			<br>& = Different configurational isotopes for the coverage from a-f

II)  JDFTx - DFT Calculation using JDFTx:  https://jdftx.org/
<br>	A)  Volmer
<br>	B)  Heyrovsky
<br>	C)  Tafel

<br>File name notation:  XXX_Ru39_H#_&_%_*
<br>	File types:
<br>		.in - Input files
<br>		.out - Output files
			<br>XXX = pyrr (pyrrolic), graphe (graphene), graphi (graphitic), pyri (pyridinic)
				describes the support underneath the Ru39 metal
			<br># = The number representing how many of the surface sites (coverage) are occupied by hydrogen
			<br>& = Different configurational isotopes for the coverage from a-f
			<br>% = Charge of the calculation (0, +1/2, +1, +2)
			<br>* = for rx files, the NEB step (1,2,3,4,or 5)


III)  Excel Spreadsheet data analysis:
<br>  Pourbaix pyridinic - data for Ru-pyridinic and GC-QM Analysis 
<br>  Pourbaix pyrrolic - data for Ru-pyrrolic and GC-QM Analysis 
<br>  Pourbaix graphitic - data for Ru-graphitic and GC-QM Analysis 
<br>  Pourbaix graphene- data for Ru-graphene and GC-QM Analysis 
<br>  Fig 6C
<br>  Fig 7A-D
