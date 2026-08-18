# Write-a-program-to-input-three-numbers-and-find-the-largest-among-them-using-if-else.
#include <stdio.h>
main(){
int first_number,second_number,third_number;
printf("enter first number =");
scanf("%d",&first_number);

printf("\nenter second number =");
scanf("%d",&second_number);

printf("\nenter third number =");
scanf("%d",&third_number);

if (first_number > second_number)
{printf("\nfirst_number is greeatest ");}
else { if (third_number > first_number) {printf("\nthird_number is greatest ");}
else { printf("\nsecond_number is greatest");}
}}
