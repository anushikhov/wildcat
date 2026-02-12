**Collation** is the assembly of written information into a standard order.  

Many systems of collation are based on numerical order or alphabetical order, or extensions and combinations thereof.   

Collation differs from classification in that the classes themselves are not necessarily ordered.   

However, even if the order of the classes is irrelevant, the identifiers of the classes may be members of an ordered set, allowing a sorting algorithm to arrange the items by class.  

Formally speaking, a collation method typically defines a total order on a set of possible identifiers, called sort keys, which consequently produces a total preorder on the set of items of information (items with the same identifier are not placed in any defined order).  

A collation algorithm such as the Unicode collation algorithm defines an order through the process of comparing two given character strings and deciding which should come before the other. When an order has been defined in this way, a sorting algorithm can be used to put a list of any number of items into that order.   

The main advantage of collation is that it makes it fast and easy for a user to find an element in the list, or to confirm that it is absent from the list.    

In automatic systems this can be done using a binary search algorithm or interpolation search.  


