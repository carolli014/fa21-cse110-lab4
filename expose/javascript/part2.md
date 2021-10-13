1. It will print "3" at line 12 because the condition of the for loop is i < prices.length and array "prices" has length 3. i would increment by 1 in each round until i gets to the length of the array "prices".
2. It will print "150" at line 13 because in the last round of the for loop prices[i] would be the last element in array "prices". So discountedPrice = 300*(1-0.5)=150.
3. It will print "150" at line 13 because according to question 2, discountedPrice = 150. So finalPrice = Math.round(150*100)/100 = 150.
4. It will return "[ 50, 100, 150 ]" because in the first round of the for loop discountedPrice = 100*(1-0.5)=50 and finalPrice = Math.round(50*100)/100 = 50. So 50 is pushed to array "discounted". In the second round, discountedPrice = 200*(1-0.5)=100 and finalPrice = Math.round(100*100)/100 = 100. So 100 is pushed to array "discounted". In the last round, finalPrice = 150 according to question 3, so 150 is pushed to array "discounted".
5. It returns ReferenceError because 
