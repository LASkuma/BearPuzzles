#Tuples

This notes includes some information about the basic built-in tuples in SML.

##Pairs

###Syntax

####Build a pair
	val e = (e1, e2)
####Element access: 
	#1 e, #2 e
			
e1 and e2 **doesn't** have to be the same type.

Each pair have two elements, there's no way to add new element to a pair. 

##Lists

###Syntax

####Build a List: 
	val list = [e1, e2, e3]
####Element access 
	hd list
Would give you the head of the list.

	tl list
Would give you a new list contains all the elements in the original list without the first one.

####Status check
	null list
Have value of true if the list is empty. False if there are elements in it.

####Add elements
	e :: list
Would prepend the element e to the list. Notice that e should have the same type of the other elements in list.
	