# age-calculator
age calculator
<br>
// Online C compiler to run C program online
#include <stdio.h>

int main() {
    // Write C code here
    printf("HELLO WORLD\n");
    //age calculator and compliment generator
    int birthyear,age;
    printf("Enter your birth year :");
    scanf("%d",&birthyear);
    age = 2025 - birthyear;
    printf("Your age is %d \n",age);
    printf("You are becoming a fantastic coder\n");
// age calculator with if statements
    if (age<=12){
        printf("You're a budding genius with wild potential! 🌱\n");
    }else if (age<=19){
        printf("Teen coder energy detected-hack the planet!🔥\n ");
    }else if (age <=30){
        printf("You're a brainy powerhouse with sleek ambition!💼\n");
    }else {
        printf("Wise, experienced, and coding with fitness!🧠✨\n ");
    }
    
    return 0;
}
