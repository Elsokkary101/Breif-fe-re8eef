# Lecture 2 : B+ Trees and R Trees
- __B+ Trees__ : It's a tree that has root and going down to some leaves 
- it's a secondary storage data structure ___That is partially stored in disk and the other part is on the memory .___
- All nodes except the root are saved on a hard-disk
- __Self-balanced data strusture__ --> which means that it's being searched in ___O(Log n)___.
- we have some rules we should obey :
  - all leaves are at the same lowest level
  - pointers in leaves point to records except for __"Sequence pointer"__.
  
![alt text](image/1.png.png)

- the leaf node will consist of number of values. each of these values is associated with a reference pointing to a particular row in the page. 
- _for example value 52 has an arrow below it which is referring to a row which has a column (index) of value 52_
-  notice here that there is a neighbour refernce pointing to the next leaf. 

![alt text](image/2.png.png)
