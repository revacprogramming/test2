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

a) equilateral its three sides are equal.
b) isoceles its two sides are equal.
c) scalene its sides are not egual.

Write a program to find whether a triangle is equilateral or isoceles or scalene.
With functions and structure using following signatures - 5 marks.

struct traingle {
	float base, side1, side2;
};
typedef struct triangle Tri;
Tri input(); 
int find_trianlge_type(Tri t); 
void output(int n);
and int main()

Loops and sequences

5) Write a program to find sum of series given x.
The formula for finding sum^x

1 + 1/2^2 + 1/3^2 + 1/4^2 .....

stop when the next term is less 0.000001, With four functions - 5 marks.


Array processing
6. With functions - 5 marks.
use following function prototypes.
void input(int n, int a[n]);
float sum(int n, int a[n]);
void output(int n, int a[n]); /* print all the elements of the array and then the sum */
and main.

Strings
7. Write a program to compare two strings and display the result with four functions - 5 marks. 

void input(char str1[], char str2[]);
int strcon(char str1[], char str2[]) 
void output(int n);
int main() 



Array of Structures

8. Write program to find the total area of n triangles. 
With following function signatures - 5 marks.

struct side
{
	float base, altitude;
}
struct triangle
{
int n;
struct side s[100];
}

void input_triangle (struct triangle *t);
float find_area(struct triangle t);
void output(struct triangle t, float area);
and 
int main()
