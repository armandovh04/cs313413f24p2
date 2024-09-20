// TODO also try with a LinkedList - does it make any difference?
Well while yes having used a LinkedList could be efficient, however we are really just removing element and such. However ArrayList feels more dynamic as you can literally just change the array, whereas the linkedlist use pointers to point to each element, while I would argue more efficient it is not needed here.

// TODO what happens if you use list.remove(Integer.valueOf(77))?
Using "list.remove(Integer.valueOf(77))?" would only remove the first sight of 77.

list.remove(5); // what does this method do?
This removes the element from index 5 which here is 77.

list.remove(Integer.valueOf(5)); // what does this one do?
Compared to the other this deletes the first sight of 5. 
