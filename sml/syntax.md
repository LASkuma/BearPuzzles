#Syntax

##if Expression
###Syntax
	if a < b then c else d
Note that c and d should be the same type. This if expression is not like the ones in C or Java. It would simply return a value. Under this senarial, the expression would return c if the previous subexpression is true. Otherwise, it would return d.

##Functions
###Syntax 

fun x0 (x1 : t1, ... , xn : tn) = e

Example:

	fun pow (x : int, y : int) = 
		if y = 0
		then 1
		else x * pow(x, y - 1)
