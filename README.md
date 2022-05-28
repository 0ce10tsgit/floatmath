Just take the file copy pasta it and include it in < script>
and then\
"let namethiswhatever = new F()"\
Methods are \
.subtract(num1,num2) \
.add(num1,num2)\
.multiply(num1,num2)\
.divide(num1,num2)\
mod is wip cus Idk if the error happens there
\
how it works:
\
Any decimal operation can be recreated with non decimals eg 0.1 + 0.1 = 0.2 and 1 + 1 = 2\
so the library calculates scalar that will turn both digits into whole numbers if they arent already whole numbers\
then it just does the operation with the scaled up version and uses the scalar to bring the result down to a decimal\
however this entire solution uses division and multiplication which is where the problem is at in the first place\
so I used strings to solve that, the number is turned to a string then an array and then the numbers are scaled up by anaylizing the location of the '.'\ 
the same process is used to lower the scaled up product to the true product.\


