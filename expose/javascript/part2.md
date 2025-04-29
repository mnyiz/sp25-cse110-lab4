1. It will print out 3. Since i is declared with var, it will be accessible anywhere inside the function; the length of prices is 3, so the for loop will loop 3 times, and i will be incremented from 0 to 3, exiting the for loop then.
2. It will print [Function: discountPrices], because without the parameters you are not calling the function but just the function object. Therefore the console will print infornation about the function instead.
3. It will print 150. In the for loop finalPrice is updated continuously with each price. The last price 300 after calculations with the discount: 300 * 0.5 and the rounding: Math.round(300 * 100 / 100) is 150, which is what is stored in finalPrice.
4. It will return the array discounted, which in the end would be [50, 100, 150].
5. It will cause an error. Since i is declared with let, it is not accessible outside of the for loop and therefore line 12 would be an error.
6. It will print [Function: discountPrices], because without the parameters you are not calling the function but just the function object. Therefore the console will print infornation about the function instead.
7. It will print 150. In the for loop finalPrice is updated continuously with each price. The last price 300 after calculations with the discount: 300 * 0.5 and the rounding: Math.round(300 * 100 / 100) is 150, which is what is stored in finalPrice.
8. It will return the array discounted, which in the end would be [50, 100, 150].
9. It will cause an error before reaching line 11. Because discounted has been declared as a const and hence we cannot modify it, therefore trying to modify the values of discounted at line 8 would throw an error.
10. It will cause an error before reaching line 11. Because discounted has been declared as a const and hence we cannot modify it, therefore trying to modify the values of discounted at line 8 would throw an error.
11. It will cause an error before reaching line 11. Because discounted has been declared as a const and hence we cannot modify it, therefore trying to modify the values of discounted at line 8 would throw an error.
12. 
