#Calculator using reverse polish notation

##Accepted input:
*   number literals
*   +/-*
*   =
*   quit

##Sample calculation in UPN
*   In well-known infix: (2 + 3) * 4
*   In UPN: 2 3 + 4 *

##Compilation
* gcc upn\_calc.c int\_stack.c -o upn_calc

##Sample session:
* ./upn_calc
*  Input: 2 [return] 3 [return] + [return] 4 [return] * [return] = [return] quit [return]
*  Output: 20
