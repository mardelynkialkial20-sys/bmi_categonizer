#include <stdio.h>

int main() {
    float weight, height, bmi;

    printf("Enter your weight: ");
    scanf("%f", &weight);

    printf("Enter your height: ");
    scanf("%f", &height);

    bmi= weight / (height * height);

    if(bmi >= 30.0){
        printf("BMI: %.2f\n", bmi);
        printf("Category: Obese");
    }    
    
    else if (bmi >= 25.0){
        bmiprintf("BMI: %.2f\n", bmi);
        printf("Category: Overweight");
    }
     else if (bmi >= 18.5){
        printf("BMI: %.2f\n", bmi);
        printf("Category: Normal");
    }
     else {
        printf("BMI: %.2f\n", bmi);
        printf("Category: Underweight");
    }

return 0;

}

    

    
