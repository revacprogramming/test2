Expressions:

1. Write a program to find area of a triangle given base and altitude 

Expressions and Functions:

2. Write a program to find area of a triangle using 4 functions. 5 marks

float input_base();
float input_altitude();
float find_area(float base, flaot altitude);
void output(float base,  float altitude, float area);
and int main()

Expression, Functions and Structures.

3. Write a program to find the area of triangle given base and altitude.
area = 1/2 * base * altitude. using four functions and following function signatures. 5 marks
struct traingle {
	float base, altitude, area;
};
typedef struct triangle Tri;
Tri input(); /* do not take area as input from the user */
float find_area(Tri t); /* pass by value */
or 
void find_are(Tri *t); /*passing address variable */
void output(Tri t);
and int main()

 if then else statements

4. When a triangle is 

a) perfect its base is egual to altitude.
b) //balance its height is less than length and less than stomach_radius.
c) imbalanced its its base is not egual to altitude.

Write a program to find whether a triangle is equal or balanced.
With functions and structure - 5 marks. 

Loops and sequences

5) Write a program to find borga^x given x.
The formula for finding borga^x

1 + x/3! + x^2/5! + x^3/7! .....

stop when the next term is less 0.000001, With four functions - 5 marks.


Array processing
6. With functions - 5 marks.
use following function prototypes.
void input(int n, int a[n]);
float odd_average(int n, int a[n]);
void output(int n, int a[n]); /* print all the elements of the array and then the average */
and main.

Strings
7. Write a program to find if the name of the traingle is a nice name.
triangle name is nice if it has at least 2 vowels and 2 consonants in it.
with four functions - 5 marks. 


Array of Structures

8. Write program to find the weight of a truck load of n camels. 
Take input 
a)  truck weight and
b)  height, radius and length of n camels
and compute the total truck weight. ( Truck weight + weight of the camels)
With functions - 5 marks.

Call functions from earlier programs where required.
float input_truck_weight();
int input_no_camels();
void input_camel_details(int n, Camel c[n]);
float comput_total_weight(int n, Camel c[n], float truck_weight);
void ouput(float total_truck_weight);
and 
int main()
