# ARRAY-AND-COLLECTIONS

Arrays vs Collections : In Java an Array represents group of elements and a Collection also represents group of elements, then if already Arrays have the same feature why collections ? let’s see what is an Array exactly.

What is an Array in Java ?

An Array is collection of indexed and fixed number of homogeneous (same type) elements.
Indexed : Arrays are stored elements in index based. The stored element position starts from ‘zero’ and second element position ‘1′ and so on.
For example if we take String array to represent Student names [“Satish”, ”Sunil”, ”Suresh”, ”Ravi”] position of “Satish” element is ‘0‘ , position of “Sunil” is 1, position of “Ravi” is 3.
Fixed : When we are defining array we have to specify the size of array. Example : String[] students = new String[10]; . Once we created an Array we can’t increase the size, size is fixed in arrays.
Homogeneous : Arrays elements are homogeneous, it means once we created array we can store same type of elements. For example in point 4 student array allow to store only String type elements, because the array type is String.
Arrays vs Collections :
Arrays	Collections
1. Size is fixed	1. Size is not fixed, size is growable
2. Can hold both primitive types(boolean, byte, short, int, long …etc) and object types.	2. Can hold only object types
3. There is no underlying data structures in arrays. The array itself used as data structure in java.	3. Every Collection class there is underlying data structure.
4. There is no utility methods in arrays	4. Every Collection provides utility methods
Why collections ?

Arrays are fixed in size, in development always it’s not possible to define size of an array. We need to increase size based on requirement. Collections are not fixed in size, they are growable (size will be increased when it’s reached max size).
Arrays can only holds one type of elements. Collections can hold different type of elements.
There is no default method support from arrays for sorting, searching, retrieving etc… but collections have default utility method support, it’s handy for for developer. It will reduce the coding time.
