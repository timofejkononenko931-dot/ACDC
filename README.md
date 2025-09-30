ACDC this is CDosCompiler, ACDC - AsmCDosCompiler
all syntax in uppercase
main write ACDC MAIN(){} 
example:
|**************|
|ACDC MAIN() {}|
|**************|
this comipiler has got a inline assembly
example
|********************************|
|.AS  ;ASSEMBLY SEGMENT          |
| MOV   AH,09H                   |
| MOV   DX,OFFSET MSG            |
| INT   21H                      |
|.ASE  ;ASSEMBLY SEGMENT END     |
|********************************|
