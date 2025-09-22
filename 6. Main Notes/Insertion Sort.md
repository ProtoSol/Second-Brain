
2025-03-23 17:12

Status: #complete

Tags: [[Algorithm]] [[Computer Science]]

# Insertion Sort

An algorithm that operates based on the left portion being sorted, where the current element is inserted into its appropriate position at the end, followed by moving to the next step.

> For me, It's also the most difficult one to Remember

## Pseudo Code

```
for j = 2 to n
	do key <- A[j]
	i <- j - 1
	while i >= 0 and A[i] > key
		do A[i+1] = A[i]
		i <- i - 1
	A[i+1] <- key
```

## Diagram

![[7. Drawings/Insertion Sort]]

## Code

```java
 private void sort(int[] arr) {
        int n = arr.length;
        for (int j = 1; j < n; j++) {
            int key = arr[j];
            int i = j - 1;
            while (i >= 0 && arr[i] > key) {
                arr[i + 1] = arr[i];
                i = i - 1;
            }
            arr[i + 1] = key;
        }
    }
```


## Time Complexity

- Worst Case — $O(n^{2})$