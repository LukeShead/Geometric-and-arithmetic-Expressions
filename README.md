# Probability-and-Mathematic-Expressions


This repo will be covering probability and mathematic expressions on a basic level, these are meant for when programs are written, The process of researching these things can be greatly reduced.


### Probability,

Probability is the process of chance, and how it can affect the chances of certain events happening, for example if someone rolls a 6 sided dice, the probability of the dice landing on 1 is a 1/6 chance. If someone draws a card from full deck, the probability that their card will be red is an 27/54 chance to draw it. However these numbers are able to be simplified down to a 1/2 chance otherwise known as a half chance as they scale down accordingly.

### Deduce the conditional probability of different events occurring within independent trials

When looking at independent trials, I will be analysing a dice roll, the reason for this is that the dice can have multiple outcomes depending upon many different factors that cannot be controlled. For this trial I will be using two dice to throw.

#### What is the probability of the dice creating a value of 8 in total?

When looking at this trial, you have to find out how many outcomes are possible from this roll, there are 6 sides on each dice that are exactly the same. So the amount of outcomes can be equal to 6x6 which is 36, this is how many different outcomes can come from these rolls. Before calculating the exact probability you have to figure out how many different outcomes can make the value of 8, for example 1 and 7 can make 8 as well as two 4's, by factoring in these different parts of the roll you can now calculate the probability. 

so the amount of maximum outcomes is 36 which means that the probability will be */36, because of this all that is needed is the first part. The amount of outcomes for the total of 8 comes as follows, 2 and 6, 3 and 5, 4 and 4, 5 and 3, 6 and 2, in total there is a possability of 5 different outcomes that can make a total of 8. Because of this the probability of a total of 8 is 5/36. If the answer had been different the fraction would be simplified, for example if the answer was 6/36, it would be 1/6

![Equation for probability](https://github.com/LukeShead/Maths/blob/master/Probability%20equation.JPG) Taken from https://saylordotorg.github.io/text_introductory-statistics/s07-03-conditional-probability-and-in.html


### Identify the expectation of an event occurring from a discrete, random variable

First thing you have to make sure when doing this is that the amount that will be randomly selected is a finite amount, so to get results you choose a finite amount but do the task repeatedly, this means that there will be successful results.

![equation for random probability](https://github.com/LukeShead/Maths/blob/master/Random%20Inifite%20probability.JPG) Taken from https://www.cut-the-knot.org/m/Probability/InfiniteDiscrete.shtml

Above is the formula that can be used, the input can be any random variable. One example that I will use is to devide any amount by 5 and what is the probability of it being able to be divisible by 5. The answer to this question is 1/5, this is because the number 5 can only be divisible by any number that ends with the value 5 or 0. Because of the numbers we are given that can be the values which would be 1,2,3,4,5,6,7,8,9,0, there are only 2 numbers that can be used which is 5 and 0 which means the probability would be 2/10 however when simplifying the fraction we come to the answer of 1/5.

### Calculating the greatest common divisor.

The Greatest Common Divisor or otherwise known as the Highest Common Factor (HCF) of two numbers that aren't negative is the largest positive number that divides both numbers without a remainder, this excluded any form of decimal number. This method of maths is very useful for finding the simplist form for fractions as it allows the numbers to be reduced to a number that is easier to digest. For example, 

#### TWO NUMBERS 12 AND 15

The original fraction would be 12/15

The common factors of these numbers are,
1 and 3,
#### We pick the highest common factor which is 3 in this case

By multiplying the number 3 a certain amount of times we can get our lowest common divisor, 3 goes into 12, 4 times and 5 for 15. 
#### This means the new fraction is 4/5 instead of 12/15


### Calculating the lowest common multiple of two numbers

When calculating the lowest commmon multiple of two numbers, you have to follow a very simple process of addition. If i wanted to find the LCM of seven and eight, i would have to folow the muliples of both numbers, you start with adding the number by itself to get the multiples of the number. For example the multiples of seven are 7, 14, 21, 28, 35, 42, 29, 56 etc. By looking at these multiples of seven, we need to find the lowest common multiple with eight, so you would need to do the same with eight until a number appears that goes into the multiples of eight and seven. Multiples of 8 are 8, 16, 24, 32, 40, 48, 56 etc. From these multiples you can see that the LCM between 7 and 8 is 56 as it is a multiple of both numbers and is the first common multiple to appear. That is how you find the LCM to two numbers.

### Arithmetic and geometric progressions

In order to sum these progessions, first a number must be taken, after the value has been chosen it must be multiplied by itself, whilst doing this the number must then be added by itself. This will loop and won't stop until a set value appearsm this means it can go on for any amount of time. After this has been done it will just get the final values and display them presenting the progression of values. The only difference between Geometric and Arithmetic is that Geometric is times whereas Arithmetic is addition.

### Progression algorithm for Arithmetic and geometric.

#include <iostream>

#include <cstdlib>

using namespace std;

int main () {

int input;

cout<< "type a number: \n";

cin >> input; 

int loop = 0;


do{

 

int geometric = input * input;

int arithmetic = input + input;

int arithmetic2 = arithmetic + input;

int geometric2 = geometric * input;

int arithmetic3 = arithmetic2 + input;

int geometric3 = geometric2 * input;

//adds 1 to loop variable
loop++;

  cout<<"geometric value:";
  cout<<geometric;
  cout<<"\n";
  cout<<"arithmetic value:";
  cout<<arithmetic;
  cout<<"\n";
  cout<<"geometric value:";
  cout<<geometric2;
  cout<<"\n";
  cout<<"arithmetic value:";
  cout<<arithmetic2;
  cout<<"\n";
  cout<<"geometric value:";
  cout<<geometric3;
  cout<<"\n";
  cout<<"arithmetic value:";
  cout<<arithmetic3;
  cout<<"\n";
  
  
  
  
} while( loop < 0 );
return (0);

 
}

### Identifying simple shapes using co-ordiante geometry

When designing and developing softwares or algorithms that involves shapes, you must be sure that it is the correct shape that it is being used is the right shape and how each shape is defined through the algorithm. this can be done through co-ordinate geometry, this is the rules of which shapes are defined, for example, a square will must be four sided of an equal length with four right angles on it, following these rules will mean that the shape will be a square no matter what the size of the shape. 

There are properties to every shape, these properties can be summed up in a table that allows people to see what kind of shape it is, this is espiecially important for quadrilaterals as many shapes can be made by changing a property of it. 

![Quad properties](https://github.com/LukeShead/Maths/blob/master/Quad%20properties.JPG) Taken from https://www.sophia.org/tutorials/coordinate-geometry-of-quadrilaterals--2

Above is the table that shows the properties of quadrilaterals and how they differ depending on the properties that they have. 

These properties can be better shown when using co-ordinates, for example a square will have 4 equal sides and 4 right angles, with co-ordinates that can be shown by saying that on a graph the points will be: (2,2) (2,-2) (-2,2) (-2,-2), because all sides are equal and with the right angles, the sides are complete opposites which means the points must be too. 
Demonstrating this with a rectangle, the points would looks something more like this, (2,3) (2,-3) (-2,3) (-2,-3). A rectangle is required to have 2 equal sides, this means that there has to be longer horizontal lines than landscape, this means that the 2 horizontal lines will be equal and so will the 2 landscape lines. 



### Rate of change,

It is the average rate in which a function changes when regarding values. The it is the function result and the input result being different. For example the miles per hour is an example rate of change. 



