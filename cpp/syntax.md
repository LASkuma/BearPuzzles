#Syntax

##Function pointers in C++

###As a parameter
	Plot(int start, int stop, double (functionName) (double))

**return type** (functionName) **(signature)**

##Generic Types

###Functional templates

	template <typename Type>
	void Swap(Type & a, Type & b)
	{
		Type tmp = a;
		a = b;
		b = tmp;
	}

template <**typename Type**>
