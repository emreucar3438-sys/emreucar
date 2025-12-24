[# emreucar
#include <stdio.h>
int factorial(int x){
    if(x<=0){  //we are checking the variable wheather is a negative figue or not
        return 1;}
        else{
            return x * factorial(x-1);
        }
    
}
int main() {
    int x = 4;
if(x > 0) {
        int result = factorial(x); // we call the function in the main function
        printf("The Factorial is : %d", result);
    }
    else {
        printf("Enter positive value");
    }
    
    return 0;
}
](https://github.com/emreucar3438-sys/emreucar.git)
