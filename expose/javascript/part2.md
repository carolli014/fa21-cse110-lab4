1. It will print "3" at line 12 because the condition of the for loop is i < prices.length and array "prices" has length 3. i would increment by 1 in each round until i gets to the length of the array "prices".
2. It will print "150" at line 13 because in the last round of the for loop prices[i] would be the last element in array "prices". So discountedPrice = 300*(1-0.5)=150.
3. It will print "150" at line 13 because according to question 2, discountedPrice = 150. So finalPrice = Math.round(150*100)/100 = 150.
4. It will return "[ 50, 100, 150 ]" because in the first round of the for loop discountedPrice = 100*(1-0.5)=50 and finalPrice = Math.round(50*100)/100 = 50. So 50 is pushed to array "discounted". In the second round, discountedPrice = 200*(1-0.5)=100 and finalPrice = Math.round(100*100)/100 = 100. So 100 is pushed to array "discounted". In the last round, finalPrice = 150 according to question 3, so 150 is pushed to array "discounted".
5. It will return ReferenceError because i is declared in the scope of for loop so we cannot print i outside the for loop.
6. It will return ReferenceError because discountedPrice is declared in the scope of for loop so we cannot print discountedPrice outside the for loop.
7. It will return "150" because finalPrice is declared in the scope of the function so we can print it out. According to question 3, finalPrice = 150.
8. It will return "[ 50, 100, 150 ]" because discounted and finalPrice are declared in the scope of the function so we would not cause any errors when using these variables. According to question 4, discounted = [50,100,150].
9. It will return ReferenceError because i is declared in the scope of for loop so we cannot print i outside the for loop.
10. It will print "3" because length equals to the length of array "prices".
11. It will return "[ 50, 100, 150 ]" because in the first round of the for loop discountedPrice = 100*(1-0.5)=50. So 50 is pushed to array "discounted". In the second round, discountedPrice = 200*(1-0.5)=100. So 100 is pushed to array "discounted". In the last round, discountedPrice = 150 according to question 2, so 150 is pushed to array "discounted". Since each round of for loop it creates a new const called discountedPrice so it would not cause any errors.
12. A. student.name
    B. student['Grad Year']
    C. student.greeting();
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. A. ‘32’ since integers map to their exact string representation
    B. 1 since string is mapped to its integer representation
    C. 3 since null is converted to 0
    D. '3null' since null is converted to string 'null'
    E. 4 since true is converted to 1
    F. 0 since both false and null are converted to 0
    G. '3undefined' since 3 and undefined are mapped to their string representation
    H. NaN since undefined is converted to NaN for numeric conversion
14. A. true since string '2' becomes a number 2
    B. false since '2' is greater than the '1', '2' is greater than '12'
    C. true since string '2' becomes a number 2
    D. false since === considers operands of different types to be different, 2 is of type number and '2' is of type string
    E. false since true becomes 1 and 1 != 2
    F. true since Boolean(2) becomes boolean true and both sides are boolean true.
15. == attempts to convert and compare operands that are of different types but === considers operands of different types to be different.
17. The result will be "[ 2, 4, 6 ]". The for loop iterates through array and push each element which is multiplied by 2 using callback function to a new array. 
19. The output is 1 4 3 2. Line 2 and line 5 don't call setTimeout function so they get printed first. Then line 4 executes before line 3 because 0 millisecond is shorter than 1000 milliseconds.
