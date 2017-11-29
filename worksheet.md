### MCQ

1. What is the asymptotic complexity of `2n log n + 7n -14 log2n`?
    1. O(logn)
    2. O(nlogn)
    3. O(n)
    4. O(n^2)

--- 
```
    for(int i = 0; i < n; i++) {
        for(int j = 0; j < n; j *= 2) {
            System.out.println("WHY IS THIS A QUESTION?");
        }
    }
```
2. How many times will the print statement be executed (in the asymptotic sense)
    1. O(logn)
    2. O(nlogn)
    3. O(n)
    4. O(n^2)

---
```
    public power(long x, intn) {
        double pow = 1;
        if(n==0)
            return 1;
        if (n == 1)
            return x;
        if(n%2==0){
            pow = power(x, n/2);
            return pow * pow; 
        }
        else{
            pow = power(x, n/2);
            return pow * pow * x;
        }
    }
```
3. The code above computes the nth power of x. How many multiplications are performed (in the asymptotic sense)?
    1. O(logn)
    2. O(nlogn)
    3. O(n)
    4. O(nx)

---
4. A binary tree is traversed and the key at each node visited is printed. Which property holds for each tree traversal (preorder, postorder, inorder)?
    1. The root is printed before the nodes in the right subtree.
    2. The nodes in the left subtree are printed before the nodes in the right subtree.
    3. The root is printed after all the nodes in the left subtree.
    4. None of the above.

---
5. Given n elements, what is the best time in which a min-heap can be built?
    1. O(n)
    3. O(nlogn)
    4. O(n^2)
    5. O(logn)

---
![Question](images/q6.png "min heap tree")
6. 