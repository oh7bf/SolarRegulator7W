
VOLTAGE LIMITER FOR 7 W SOLAR PANEL
===================================

The LM358 works as a comparator. When the panel voltage becomes high enough 
about 15 V, the power transistor Q1 starts to conduct. Thus the extra power
that can not be stored to the SLAB is dissipated by Q1 and R2. 

Parts
-----

CONN1   screw terminal
CONN2   screw terminal	
D1	1N5158
D2      LED 3 mm	
Q1	TIP29 
R1	500	
R2	33 7W	
R3	1k	
R4	5k1	
R5	1k	
R6	5k	
U1	LM358
U2	LM336-2.5

Files
-----

attribs                - used by 'gnetlist -g bom -o bom.txt file.sch'
board_component.pdf    - PCB component placement
board_mirror.pdf       - PCB for toner transfer production
board.pcb              - PCB file
board.png              
board_silk_mirror.pdf  - silk screen for toner transfer printing
board_silk.pdf         - silk screen
README.txt             - this file
solar7Wreg.pdf         - circuit diagram
solar7Wreg.png
solar7Wreg.sch
solreg7w

