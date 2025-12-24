# emreucar
#include <stdio.h>
int factorial(int x){
    if(x<=0){
        return 1;}
        else{
            return x * factorial(x-1);
        }
    
}
int main() {
    int x = 4;
if(x > 0) {
        int result = factorial(x);
        printf("The Factorial is : %d", result);
    }
    else {
        printf("Enter positive value");
    }
    
    return 0;
}
