# Software Interview Prep

## Algorithms

### Tree traversal
- Pre-order traversal
- In-order traversal
- Post-order traversal
- Breadth first search
- Depth first search
- **Know how to do recursively and iteratively**
- **Use bfs to find nearest node to match some criteria**

### Binary search
- Traverse tree to look for some node

### Data structures to represent a tree
- Left & right
- A node with an array of children nodes

### Recursion
- Commonly recursive functions call helper functions
- Think about the base case
- Not used much in tech because it is limited to stack space
- Every recursive function can be converted into iterative (stacks or queues)

### Stacks & Queues


### Objected-oriented programming
- Class (e.g. making a 2D array class)
- Method
- Private/public variables

### Hashmaps
- Used very commonly
- Understand time/space complexity

### Sorting
- Bubble
- Merge
- Quick

### Strings
- Iterate

### Dynamic programming
- Caching

### Interview
- How well can you analyze the problem?
- Design alternatives
- Trade-offs (Time vs. space)

## Big O
- Time complexity (asymptotic runtime)
  - Best case, worst case, expected case
- Space complexity (memory)
  - Array of size n => O(n)
  - Array of size n^2^ => O(n^2^)
  - In recursion, each successive call could add level to stack space
- Amortized time when adding to arrays
  - add(), or "append", is:
    - O(1) for add-without-increasing-capacity, and
    - O(n) for add-with-increasing-capacity
    - amortized time complexity of a single add operation is O(1)
    - rare O(n) gets diluted with more O(1)'s
    - therefore, on average, a single add is O(1)
  - add(index, E), or "insert", is:
    - single operation O(n)
    - if triggers array-grow, then it's
    - O(n) + O(n) [grow + insert]
    - which is O(n)
