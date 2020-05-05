#Arrays

Arrays are a very simple data structure, and may be thought of as a list of a fixed length. Arrays are nice because of their simplicity, and are well suited for situations where the number of data items is known (or can be programmatically determined). Suppose you need a piece of code to calculate the average of several numbers. An array is a perfect data structure to hold the individual values, since they have no specific order, and the required computations do not require any special handling other than to iterate through all of the values. The other big strength of arrays is that they can be accessed randomly, by index. For instance, if you have an array containing a list of names of students seated in a classroom, where each seat is numbered 1 through n, then studentName[i] is a trivial way to read or store the name of the student in seat i.

An array might also be thought of as a pre-bound pad of paper. It has a fixed number of pages, each page holds information, and is in a predefined location that never changes.

Arrays are classified as Homogeneous Data Structures because they store elements of the same type and arrays elements are stored at contiguous memory locations. This makes it easier to calculate the position of each element by simply adding an offset to a base value, i.e., the memory location of the first element of the array (generally denoted by the name of the array).

## One Dimensional Arrays
An array is defined with the name arrayName and has an integer data type. The number below in the bold shows the memory address each container of an array is assigned to. The important thing here to remember is an array index always starts at 0 and ends at (total array size -1). So, let’s just say you defined an array of length 5, arrayName[5], then the indexes of this array would be arrayName[0], arrayName[1], arrayName[2], arrayName[3], arrayName[4].
![OneDimensionalArray](https://miro.medium.com/max/1400/1*pscP-dh0pfgbR9IaCgNXqQ.png)

## Multidimensional Arrays
A multidimensional array is just an extension of the normal array, where we define an array with a row of containers. In case of a multidimensional array, we have rows as well as columns. In order to access an index, we need two numbers to get there.
![MultiDimensionalArray](https://miro.medium.com/max/982/1*3xr9AK7euOlKCfZtVwRz2g.png)

## Dynamic Arrays
Most of the programming languages allow you to define dynamic arrays, which means the memory is allocated during program execution. Consider it this way, you defined an array with 10 indexes but, you only need 3 indexes, thus the remaining 7 indexes are laid to waste, thereby consuming extra memory. Dynamic arrays give you the flexibility to allocate memory according to the program requirement.

## Advantages of using arrays:

* Arrays allow random access of elements. This makes accessing elements by position faster.
* Arrays have better cache locality that can make a pretty big difference in performance.

## In Summary…
* Arrays are extremely powerful data structures that store elements of the same type. The type of elements and the size of the array are fixed and defined when you create it.
* Memory is allocated immediately after the array is created and it’s empty until you assign the values.
* Their elements are located in contiguous locations in memory, so they can be accessed very efficiently (random access, O(1) = constant time) using indices.
* Inserting elements at the beginning or in the middle of the array involves moving elements to the right. If the array is full, creating a new, larger array (which is not very efficient). Inserting at the end of the array is very efficient, constant time O(1).
* Removing elements from the beginning or from the middle of the array involves moving all the elements to the left to avoid leaving an empty space in memory. This guarantees that the elements are stored in contiguous spaces in memory. Removing at the end of the array is very efficient because you only delete the last element.
* To find an element, you need to check the entire array until you find it. If the data is sorted, you can use algorithms such as Binary Search to optimize the process.


#Coding Practice
[LeetCode](https://leetcode.com/explore/interview/card/top-interview-questions-medium/103/array-and-strings/)
[Hackerrank](https://www.hackerrank.com/domains/data-structures?filters%5Bsubdomains%5D%5B%5D=arrays)
[Medium](https://medium.com/@codingfreak/huge-collection-of-array-interview-questions-e87ac7c34e62)
[Leetcode-Arrays](https://leetcode.com/tag/array/)