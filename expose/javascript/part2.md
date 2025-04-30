1. It will print out 3. Since i is declared with var, it will be accessible anywhere inside the function; the length of prices is 3, so the for loop will loop 3 times, and i will be incremented from 0 to 3, exiting the for loop then.
2. It will print out 150. In the for loop disountedPrice is updated continuously with each price. The last price 300 after calculations with the discount: 300 * 0.5 = 150.
3. It will print 150. In the for loop finalPrice is updated continuously with each price. The last price 300 after calculations with the discount: 300 * 0.5 and the rounding: Math.round(300 * 100 / 100) is 150, which is what is stored in finalPrice.
4. It will return the array discounted, which in the end would be [50, 100, 150].
5. It will cause an error. Since i is declared with let, it is not accessible outside of the for loop and therefore line 12 would be an error.
6. It will cause an error. Since discountedPrice is declared with let, it is not accessible outside of the for loop and therefore line 13 would be an error.
7. It will print 150. In the for loop finalPrice is updated continuously with each price. The last price 300 after calculations with the discount: 300 * 0.5 and the rounding: Math.round(300 * 100 / 100) is 150, which is what is stored in finalPrice. finalPrice is defined within the function so there is no issue accessing it.
8. It will return the array discounted, which in the end would be [50, 100, 150].
9. It will cause an error. Since i is declared with let, it is not accessible outside of the for loop and therefore line 12 would be an error.
10. It will print out 3. There are no errors because the const variables are not reassigned any values, so the code runs normally.
11. It will return the array discounted, which in the end would be [50, 100, 150].
12. A. student.name\
    B. student['Grad Year']\
    C. student.greeting()\
    D. student['Favorite Teacher'].name\
    E. student.courseLoad[0]
13. A. '32'\   
    B. 1\
    C. 3\
    D. '3null'\
    E. 4\
    F. 0\
    G. '3undefined'
14. A. true\
    B. false\
    C. true\
    D. false\
    E. false\
    F. true
15. The == operator is a loose equal operator that will convert everything to numbers before doing the comparison, while === is more strict. The === operator will not perform any conversions before comparison.
16. in js file
17. The result is [2, 4, 6]. The function takes in the array [1, 2, 3] and the callback function doSomething, then loops through each element of the array and calling the callback. The callback function doSomething multiplies the number by 2, and then we store it into newArr, which is returned at the end. Therefore, we get 1, 2, 3 multiplied by 2 respectively, hence the array [2, 4, 6].
18. in js file
19. 1 4 3 2
