# EX-06-6d-EMPLOYEE-STRUCTURE-SALARY-CALCULATION
## AIM 
To write a C Program to read and store the data of 3 employees and calculate their Gross Salary using the concept of structure. 
## ALGORITHM 
1. Start the program. 
2. Create an employee structure with name, id and salary details as members. 
3. Using structure variable read the structure members. 
4. Calculate the gross salary and print the details. 
5. Stop the program. 
## PROGRAM
```
#include<stdio.h> 
struct emp 
{ 
 int eid; 
 char en[50]; 
 struct sal 
 { 
 int bp; 
 int da; 
 int hra; 
 float gp; 
 }s[10]; 
}; 
int main() 
{ 
 struct emp e[10]; 
 int i; 
 for(i=0;i<3;i++) 
 { 
 scanf("%d",&e[i].eid); 
 scanf("%s",e[i].en); 
 scanf("%d",&e[i].s[i].bp); 
 } 
 printf("Details of the Employee:\n"); 
 for(i=0;i<3;i++) 
 { 
28 | P a g e
 e[i].s[i].hra = e[i].s[i].bp*0.3; 
 e[i].s[i].da = e[i].s[i].bp*0.1; 
 e[i].s[i].gp = e[i].s[i].bp+e[i].s[i].hra + e[i].s[i].da; 
 printf("%d %s %d %d %d %.2f\n", 
e[i].eid,e[i].en,e[i].s[i].bp,e[i].s[i].da,e[i].s[i].hra,e[i].s[i].gp); 
 } 
 return 0; 
 }
```
## OUTPUT
![image](https://github.com/Yogabharathi3/EX-06-6d-EMPLOYEE-STRUCTURE-SALARY-CALCULATION/assets/118899387/5bfbc4b0-4635-4df0-b331-84f3e8c3c77d)
## RESULT 
Thus the program to read and store the data of 3 employees and calculate their Gross Salary using the concept of structure has been executed successfully. 

