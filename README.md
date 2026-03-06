---

# **Experiment No. 9: Study of NumPy Library**

## **Aim**

To study and implement various features of the NumPy library in Python, including array creation, array attributes, arithmetic operations, and commonly used built-in functions.

---

## **Theory**

NumPy (Numerical Python) is a fundamental Python library used for numerical computations. It provides support for multi-dimensional arrays, matrices, and mathematical functions that operate efficiently on these data structures.

### 1. **Importing NumPy**




This statement imports the NumPy library and assigns it the alias `np`.
**Importance:**
Using an alias improves code readability and reduces typing effort, which is a standard practice in scientific programming.

---

### 2. **Array Creation**



`np.array()` is used to create NumPy arrays.

* `a` is a 1-D array.
* `b` is a 2-D array (matrix).

**Importance:**
NumPy arrays are faster and more memory-efficient than Python lists. They allow vectorized operations, which are essential in engineering computations, data analysis, and machine learning.

---

### 3. **Array Attributes**

#### (a) `ndim`



Returns the number of dimensions of the array.

**Importance:**
Helps determine whether the array is 1D, 2D, or higher dimensional. This is critical when performing matrix operations or reshaping data.

---

#### (b) `shape`



Returns the dimensions of the array in tuple form.

**Importance:**
Used to understand array structure and is essential in matrix multiplication, reshaping, and broadcasting.

---

#### (c) `dtype`


Returns the data type of array elements.

**Importance:**
Ensures correct numerical precision and memory usage. For example, `int32`, `float64`, etc., affect computational performance and storage.

---

### 4. **Arithmetic Operations**


Performs element-wise operations.

**Importance:**
NumPy allows vectorized arithmetic without using loops, making computations faster and more efficient compared to standard Python lists.

---

### 5. **Built-in NumPy Functions**

#### (a) `np.zeros((2,3))`

Creates a 2×3 array filled with zeros.

**Importance:**
Used for initializing arrays before computation, especially in matrix operations and simulations.

---

#### (b) `np.ones((3,3))`

Creates a 3×3 array filled with ones.

**Importance:**
Useful for initializing weights, masks, or identity-like structures in algorithms.

---

#### (c) `np.eye(3)`

Creates a 3×3 identity matrix.

**Importance:**
Identity matrices are fundamental in linear algebra, especially in matrix multiplication and solving systems of equations.

---

#### (d) `np.arange(1,10,2)`

Generates numbers from 1 to 9 with step size 2.

**Importance:**
Used for generating sequences efficiently, often for indexing or iterative computations.

---

#### (e) `np.linspace(0,1,4)`

Generates 4 equally spaced numbers between 0 and 1.

**Importance:**
Very useful in signal processing, plotting graphs, and numerical simulations where evenly spaced values are required.

---

#### (f) `np.mean(a)`

Calculates the average of array elements.

**Importance:**
Used in statistical analysis, data preprocessing, and signal analysis.

---

#### (g) `np.median(a)`

Calculates the median of array elements.

---

#### (h) `np.max(a)`

Calculates the maximum of matrix a.

---

#### (i) `np.min(a)`

Calculates the minimum of matrix a.

---

#### (j) `np.sum(a)`

Calculates the sum of matrix a.

---

## **Conclusion**

Thus, the experiment successfully demonstrates the basic features of the NumPy library including array creation, attribute inspection, arithmetic operations, and commonly used built-in functions. NumPy provides efficient memory management and faster numerical computation compared to standard Python lists. It is widely used in engineering applications, data science, machine learning, and scientific computing due to its high performance and powerful array manipulation capabilities.

---
