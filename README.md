# delete_sort

This code takes in a given input of a string array and then it converts it into an integer array to check if they are in order. 
If it is sorted it will delete the char that has been converted into a integer.
If the entire array is sorted it will output an empty array ex. String[] A2 = {"a", "b"}; will output: { }
If it is partially sorted it will count the number and output the cell that the unsorted variable is located in ex. String[] A2 = {"ayz", "bvu", "csr"}; will output: {1, 2}
If the array is invalid it will output -1 into the array ex String[] A2 = {"This", "is", "a", "test"}; will output: {-1}

The runtime is O(n^2) and the space complexity is O(1)
