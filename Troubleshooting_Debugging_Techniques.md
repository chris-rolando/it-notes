# Troubleshooting Debugging

## troubleshooting?

- The process of identifying, analyzing, and **solving problems**.

## debugging?

- The process of identifying, analyzing, and **removing bugs**.

## Problem Solving Steps:

1. **First: is getting information**:
   Gathering as much information as we need.
   One resource is the reproduction case, which is a clear description of how and when the problem appears.
2. **Second step is finding the root cause**
3. **Finally step is performing the necessary remediation**
4. Document the problem and the solution.

## Linear search?

- An **unordered list!**
- Going through the elements one by one from the beginning to the end.

## Binary search?

- An **sorted list!**
- It divides the list in half repeatedly using the search value as a parameter until it is found.

### 🧑‍💻

    ```
    # python code:
    def linear_search(list, key):
        """If key is in the list returns its position in the list,
        otherwise returns -1."""
        for i, item in enumerate(list):
            if item == key:
                return i
        return -1

    def binary_search(list, key):
        """Returns the position of key in the list if found, -1 otherwise.
        List must be sorted.
        """
        left = 0
        right = len(list) - 1
        while left <= right:
            middle = (left + right) // 2

            if list[middle] == key:
                return middle
            if list[middle] > key:
                right = middle - 1
            if list[middle] < key:
                left = middle + 1
        return -1
    ```
    ```
    //JS code:
        function linearSearch(list, key) {
            for (let i = 0; i < list.length; i++) {
                if (list[i] === key) {
                    return i;
                }
            }
            return -1;
        }

        function binarySearch(list, key) {
            let left = 0;
            let right = list.length - 1;

            while (left <= right) {
                let middle = Math.floor((left + right) / 2);

                if (list[middle] === key) {
                return middle;
                }
                if (list[middle] > key) {
                    right = middle - 1;
                }
                if (list[middle] < key) {
                    left = middle + 1;
                }
            }
        return -1;
        }
```
