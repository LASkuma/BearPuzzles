#string

## Traits

C++ string is mutable.

### Convert C++ into C string

s.c_str();

## Member Functions

### erase

After `erase` has been invoked, the index of the string which received this message would change.
So, 

	for (int i = 0; i < text.length(); i++) {
        
        for (int j = 0; j < remove.length(); j++) {
            
            if (text[i] == remove[j]) {
                text.erase(i, 1);
                i--;
                break;
            }
        }
        
    }

This kind of iteration would cause an implicit bug, if we don't do `i--;` after the `erase`. Since the index has already change, it won't erase the next letter after the deleted one if it needs to be deleted.
