# Operating-system-project
This project can includes two phases of OS ,
phase1 contains the single programmed job loaded into CPU and access that data.
phase 1 includes 7 instruction sets(GD,PD,LR,SR,CR,BT,H)
In phase 2 error handling should be done and loaded program into cpu and access the data
phase 2 includes SI(system inturrupts), PI(programmed inturrept), TI(Time Inturrupt).
SI =1(GD)
SI=2(PD)
SI=3(H)
PI=1(opcode error)
PI=2(operand error)
PI=3(Page Hault)
TI=0(No error)
TI=2 (Time exceeded)
In phase 2 address mapping and paging concept also introduced.
Error Handling can be done using 7 error set
0 == No error
1 ==out of data
2 ==line limit exceeded
3 ==Time limit exceeded
4 ==operation code error
5 == operand error
6 ==Invalid page fault

