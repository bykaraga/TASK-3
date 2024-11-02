"# TASK-3" 
Creating Array Search Functions:

First, I developed linearSearch functions for both std::array and std::vector. These functions iterate through the array to search for the given target element, returning the corresponding index when the target is found. If the element is not found, they return -1.
Designing Binary Search Functions:

Next, I defined binarySearch functions for both std::array and std::vector. These functions operate under the assumption that the array is sorted, using the binary search algorithm to locate the target element. When the target element is found, the index is returned; if not, -1 is returned.
Searching for the First Occurrence:

After that, I created the binarySearchFirst functions. These functions utilize the binarySearch function to return the index of the first occurrence of the target. After finding the target element, I checked for previous identical values by decrementing the index to find the first valid index.
Developing a Test Application:

To test all these search functions, I created a file named SearchingApp.cpp. In this file, I called linearSearch, binarySearch, and binarySearchFirst on both std::vector and std::array, checking the indices of the target element received from the user. I printed the results to the console to verify that each function was working correctly.
Through these steps, I successfully developed and tested search algorithms. I worked diligently to ensure the efficiency and accuracy of my functions and was pleased with the results.
