1. 2 since i will be less than the length of the prices array which was 3

2. 150 discountedPrice should return half of the final price value adjusted in the loop which was 300

3. 150 finalPrice should return the last discountedPrice that was rounded to an integer which was 150

4. [50, 100, 150] since the discount is 0.5, the function takes the original prices 
   and halves all of them to return it.

5. i is not defined in the scope, since it is declared in the for loop with keyword let.

6. discountedPrice is not defined in the scope, since it is declared in the loop body with keyword let.

7. 150 since finalPrice is declared within the same block scope, it will correctly store information and be accessible

8. [50, 100, 150] since the discount is 0.5, the function takes the original prices 
   and halves all of them to return it.

9. i is not defined in this scope, so there will be an error trying to access it.

10. 3 since the const length is declared and set to prices.length which is three. 

11. [50, 100, 150] even with the addition of all the const declarations, you can still change the properities of a constant
    array, you just cannot reassign it. Therefore, it'll be the same return value as the other scenarios.

12. a. student.name;
    b. student['Grad Year'];
    c. student.greeting();
    d. student['Favorite Teacher'].name;
    e. student.courseLoad[0];

13. a. '32', directly takes string representation of the integer
    b. 1, no concatenation since its subtracting, thus take the weak typing of ints
    c. 3, as a number, null is 0
    d. '3null', as a string, null is just 'null'
    e. 4, true is 1 as a number
    f. 0, false and null are both 0 as integers
    g. '3undefined', undefined is just 'undefined' as a string
    h. NaN, undefined has no integer value

14. a. true, '2' becomes the number 2
    b. false, taken as string values, the first number '2' is greater than that of '1' from '12'
    c. true, taken as a number 2 == 2.
    d. false, the types are different in a strict equality check
    e. false, true as a number is 1
    f. true, both values are of the boolean type true, so it is true.

15. === is a strict equality check meaning that if the types of the two objects being compared is different, then
    it will return false. Compartively, the == will attempt to convert the type of the objects if they are different. 

16. in file part2-question16.js

17. newArr: [2, 4, 6]
    When the function is called, a for loop runs to iterate through the entirety of the input array. Each iteration,
    the element of the input array is accessed and called as a parameter to the callback function or doSomething as 
    called in the original function call. There, the element of the input array is doubled and returned. After its returned,
    it is added to the output array. Repeating this three times for the three elements of the input array, the function 
    ultimately ends up doubling the values inside the array. 

18. in file part2-question18.js