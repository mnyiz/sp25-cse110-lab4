1. The bug was that num1 and num2 are being taken and also treated as strings instead of numbers. So when we add them together num1 + num2 the addition is performed of strings, which would make result = "num1num2" instead.
2. I would convert the types of num1 and num2 to numbers before performing the addition, so that the calculation is treating the two as numbers instead of strings.
