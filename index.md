# Oh look \<h1\> header is the biggest
## \<h2\> is smaller
#### So do \<h4\>
###### But \<h6\> is smallest

## Image exapmle

![Image of "Heisenberg" cat](https://octodex.github.com/images/heisencat.png)

## Code block example

### 🧪 Implementing bubble sort for Mr. Heisenberg
```python
def bubbleSort(arr):
    n = len(arr)
    # optimize code, so if the array is already sorted, it doesn't need
    # to go through the entire process
    # Traverse through all array elements
    for i in range(n-1):

        # range(n) also work but outer loop will
        # repeat one time more than needed.
        # Last i elements are already in place
        swapped = False
        for j in range(0, n-i-1):

            # traverse the array from 0 to n-i-1
            # Swap if the element found is greater
            # than the next element
            if arr[j] > arr[j + 1]:
                swapped = True
                arr[j], arr[j + 1] = arr[j + 1], arr[j]

        if not swapped:
            # if we haven't needed to make a single swap, we
            # can just exit the main loop.
            return
```

## Task lists example

- [ ] Turn on GitHub Pages
- [ ] Outline my portfolio
- [x] Introduce myself to the world
