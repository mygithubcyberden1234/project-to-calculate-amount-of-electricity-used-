# project-to-calculate-amount-of-electricity-used-
#include &lt;stdio.h>  int main() {     float units, rate, amount;    printf("Enter the rate per unit: ");     scanf("%f", &amp;rate);          printf("Enter the number of units consumed: ");     scanf("%f", &amp;units);         amount = units * rate;      printf("Amount of electricity used: %.2f\n", amount);      return 0; }
