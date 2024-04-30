## Part 2. A Little More of a Challenge... ##

1. 3 will be printed to the console because "i" gets incremented to 3 before the last loop iteration.
2. 150 will be printed to the console because in the last iteration of the loop "discountedPrice" get set to 150.
3. 150 will be printed to the console because in the last iteration of the loop "finalPrice" get set to 150.
4. The array [50, 100, 150] will be returned because those are the values that get pushed to the "discounted" array in each iteration of the loop.
5. An error is returned because "i" is declared with let and the function call on line 12 is outside of the code block where "i" was declared.
6. An error is returned because "discountedPrice" is declared with let and the function call on line 13 is outside of the code block where "discountedPrice" was declared.
7. 150 will be returned because "finalPrice" is declared with let and the function call on line 14 is inside of the code block where "finalPrice" was declared.
8. The array [50, 100, 150] will be returned because "discounted" is declared with let and the return call is inside of the code block where "discounted" was declared.
9. An error is returned because "i" is declared with const and the function call on line 12 is outside of the code block where "i" was declared.
10. 3 will be printed to the console because "length" is declared with const and the function call on line 13 is inside of the code block where "length: was declared.
11. The array [50, 100, 150] will be returned because "discounted" is declared with const and the return call is inside of the code block where "discounted" was declared. Also the variable identifier is not being reassigned.

12A. student.name  
12B. student['Grad Year']  
12C. student.greeting()  
12D. student['Favorite Teacher'].name  
12E. student.courseLoad[0]  

13A. '32' was the output because '3' is a string and gets concatenated to 2.  
13B. 1 was the output because '3' gets converted to a number due to the -.  
13C. 3 was the output because null gets converted to 0 due to the +.  
13D. '3null' was the output because null gets converted to a string because '3' is a string.  
13E. 4 was the output because true gets converted to 1 due to the +.  
13F. 0 was the output because false and null get converted to 0 due to the +.  
13G. '3undefined' was the output because undefined gets converted to a string because '3' is a string.  
13H. Nan was the output because undefined cannot be converted to a number.  

14A. true was the output because '2' gets converted to a number.  
14B. false was the output because strings are being compared and '1' is less than '2'.  
14C. true was the output because == changes both operands to the same type before comparison.  
14D. false was the output because === does not change both operands to the same type before comparison.  
14E. false was the output because true gets converted to 1 and 1 =/= 2.  
14F. true was the output because boolean(2) is true.  

15. == changes both operands to the same type before comparison and === does not change both operands to the same type before comparison.
16. [part2-question16.js](part2-question16.js)
17. [2, 4, 6] will be returned. Each iteration of the loop goes through each element in the array. In the body of the for loop, each element is taken from array, doubled (this is what doSomething does), then pushed to newArr. Then newArr is returned
18. [part2-question18.js](part2-question18.js)
