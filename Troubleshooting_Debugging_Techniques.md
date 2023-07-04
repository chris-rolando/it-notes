# Troubleshooting Debugging

- Apuntes y notas personales para **identificar y resolver problemas** de IT.
- Requisitos: Python y Linux. 

# 🤘 Base

## Troubleshooting?

- The process of identifying, analyzing, and **solving problems**.

## Debugging?

- The process of identifying, analyzing, and **removing bugs**.

## Problem Solving Steps:

1. First: **Getting information**:
   Gathering as much information as we need.
   One resource is the reproduction case, which is a clear description of how and when the problem appears.
2. Second: **Finding the root cause**
3. Finally: **Performing the necessary remediation**
4. Extra step: **Document** the problem and the solution.

## Linear search?

- Only if we have an **unordered list!**
- Going through the elements one by one from the beginning to the end.

## Binary search?

- Only if we have an **sorted list!**
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
