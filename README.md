# Sorting Visualizer using DSA 
## Description
In order to sort the data/items given by the user by using the different sorting algorithms such as bubble sort, insertion sort, selection sort, heap sort, etc with the functionality of speed control and array size control and then visualizing the sorting process in different sorting algorithms and the final result on the screen in the form of sorted bar graphs and also displaying the time complexity and applications, used python 3.9 version and used python programming basic concepts for the coding in python in VS code platform.

The user interface is a basic graph layout which shows the dataset as a bar graph. There are buttons which ask from the users which type of sorting should be done.
We have used programming standards such as - name conventions for variables and functions, indentation, simple coding methodology, sorting of array, creating and generating window using Tkinter module in python. Visualising the sorting process by using animations.

In this sorting visualizer project, we have used python libraries such as Tkinter, random, time, math:
-  Tkinter is the standard GUI library for Python. 
-  Random module is an in-built module in python which is used to generate random numbers.
-  Time module in python provides many ways of representing time in code, such as the objects, numbers, and strings. It also provides functionality other than representing time, like waiting during code execution and measuring the efficiency of the code.
-  Math in python is a built-in module that provides standard mathematical constants and functions.

With use of these and coding concepts of python our project visualizes the sorting process of selection sort, insertion sort, bubble sort, quick sort, heap sort, cocktail sort, etc.
The workflow and thorough design processes for the proposed project are outlined below -

1. Taking inputs from the user as normal input (random dataset) or creative input (getting data by the distance of the line).

2. The dataset is converted into a bar graph and is shown to the user.

3. User selects a sorting algorithm provided by the buttons to sort the dataset.

4. After selecting the sorting method, users can see and understand how that sorting is working and also their time complexity and applications displayed on the screen.

5. Users can stop the program by selecting the stop button or pressing the shuffle button if the user wants to see another sorting method.
 
The following sorting algorithms have been used in the project –

1. Insertion Sort - The array is divided into sorted and unsorted parts. Values are chosen and assigned to the appropriate positions in the sorted part of the data from the unsorted part.

2. Bubble Sort - the simplest sorting algorithm, which continually switches nearby components if they are out of order. Large data sets should not be used with this approach due to its high average and worst-case time complexity.

3. Selection Sort - An array is sorted by continually selecting the lowest member from the unsorted portion and moving it to the beginning while taking ascending order into consideration.

4. QuickSort - It is a Divide and Conquer algorithm. It chooses an element to act as a pivot and divides the supplied array around it. There are numerous versions of Quick Sort that select pivot in various ways.

5. Cocktail Sort - It is a variation of Bubble sort.
The Bubble sort algorithm always transfers the largest element to its proper position in the first iteration, followed by the second-largest in the second iteration, and so forth. Cocktail Sort alternately moves through an array in both directions. Cocktail sort is effective for huge arrays since it skips the extra iterations.

6. ShellSort - For a high value of h, we use Shell sort to produce the array h-sorted. H is gradually decreased until it reaches a value of 1. If all subsists for every element in an array are sorted, the array is said to be h-sorted.

7. Heap Sort - A comparison-based sorting method based on the Binary Heap data structure is called heap sort. It is comparable to the selection sort in which the minimum element is initially located and placed at the start. For the remaining components, follow the same procedure.

8. Merge sort - It is a sorting algorithm based on the Divide and Conquer paradigm. This algorithm divides the array into two equal parts, which are then combined in a sorted way.

9. Pancake sort - Pancake sort is a sorting algorithm in which the only allowed operation is to "flip" one end of the list. It is in place but not stable.

10. Bitonic Sort - A parallel sorting method called bitonic sort performs comparisons in O (n2log n) time. The items are compared in a predetermined order that must not be dependent on the data being sorted, so even though there are more comparisons than in any other common sorting algorithm, it performs better for the parallel implementation. The predefined sequence is called the Bitonic sequence.

11. Gnome Sort - Gnome sort builds a sorted list one element at a time by swapping each item into its rightful position.

12. Comb Sort - Comb Sort primarily improves Bubble Sort. Always compare adjacent values when using a bubble sort. Thus, each inversion is eliminated one at a time. When compared to Bubble Sort, Comb Sort performs better since it uses gaps larger than 1. The gap has a high initial value and gets smaller by a factor of 1.3 with each iteration until it is equal to 1.

## Result
The result obtained from the code firstly allows the user to choose the input method if anyone wants to perform. On running the code, the user has a choice to either to input the array values randomly or by inputting each value manually. 

For the normal (randomised) input method, the output allows the user to firstly input the array size, secondly the set the range up to which the values have to be marked, and lastly there is an attribute where the user can set the speed of the sorting for the convenience of the user. For confirming that the user wants the randomized input option he has to enter 1 in the last option.
 
For the creative input we have allowed the user to enter the array elements manually. The user has the convenience to enter the elements according to the needs. For making it more interesting the input is fetched by using the Euclidean distance formula. The user has to use mouse clicks to make lines on the input window. The longer the line is drawn the larger the value is fetched. 

## Conclusion
All in all, the project focuses on one of the major aspects of the IT industry and helps in making and visualising the data sorted using several sorting algorithms. Also, this application can be used in various software domains which can be associated with banking sector, teaching sector, the finance sector, e-commerce sector, etc.

