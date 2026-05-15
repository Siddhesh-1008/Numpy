# Numpy
# NumPy Learning Journey 🚀

This repository contains my practice and learning notes for NumPy.
I explored array creation, indexing, slicing, broadcasting, matrix operations, and many important NumPy concepts used in Data Science and Machine Learning.

---

# Topics Covered

## 1. Creating Arrays

* `np.array()`
* 1D and 2D arrays
* Difference between Python lists and NumPy arrays

```python
np.array([1,2,3])
```

---

## 2. Array Generation Functions

* `np.zeros()`
* `np.ones()`
* `np.arange()`
* `np.linspace()`

```python
np.zeros((2,3))
np.ones((2,3))
np.arange(1,10,2)
np.linspace(1,5,5)
```

---

## 3. Random Functions

* `np.random.rand()`
* `np.random.randn()`
* `np.random.randint()`

```python
np.random.randint(1,10,5)
```

---

## 4. Array Attributes

* `shape`
* `size`
* `dtype`
* `ndim`

```python
arr.shape
arr.size
arr.dtype
```

---

## 5. Reshaping Arrays

* `reshape()`
* Converting 1D arrays into 2D arrays

```python
arr.reshape(2,3)
```

---

## 6. Indexing and Slicing

* Accessing elements
* Row and column selection
* Array slicing

```python
arr[0]
arr[1:5]
arr[:,1]
arr[0:2,1:3]
```

---

## 7. Boolean Indexing

* Filtering data using conditions

```python
arr[arr > 50]
arr[arr % 2 == 0]
```

---

## 8. Updating Values Conditionally

* Replacing values based on conditions

```python
arr[arr < 75] = 0
```

Using `np.where()`:

```python
np.where(arr < 75, 0, arr)
```

---

## 9. Array Operations

* Addition
* Subtraction
* Multiplication
* Division
* Power operations

```python
a + b
a - b
a * b
a / b
a ** 2
```

---

## 10. Broadcasting

Applying a single operation to the entire array.

```python
arr + 10
arr * 2
```

---

## 11. Statistical Operations

* `sum()`
* `mean()`
* `min()`
* `max()`
* `std()`

```python
arr.sum()
arr.mean()
arr.max()
```

---

## 12. Axis Operations

* `axis=0` → Column-wise operation
* `axis=1` → Row-wise operation

```python
np.sum(arr, axis=0)
np.sum(arr, axis=1)
```

---

## 13. Copying Arrays

* Shallow Copy
* Deep Copy using `.copy()`

```python
copy_arr = arr.copy()
```

---

## 14. Matrix Operations

* Matrix multiplication
* Transpose

```python
A @ B
A.T
```

---

## 15. Stacking Arrays

* `vstack()`
* `hstack()`
* `column_stack()`

```python
np.vstack((a,b))
np.hstack((a,b))
np.column_stack((a,b))
```

---

## 16. Splitting Arrays

* `vsplit()`
* `hsplit()`

```python
np.vsplit(arr,2)
np.hsplit(arr,2)
```

---

# Key Learnings

* NumPy arrays are faster than Python lists
* Arrays support vectorized operations
* Boolean indexing helps in filtering data efficiently
* Broadcasting simplifies array operations
* NumPy is widely used in Data Science, AI, and Machine Learning

---

# Skills Practiced

✅ Array Creation
✅ Array Indexing
✅ Array Slicing
✅ Boolean Masking
✅ Array Operations
✅ Matrix Operations
✅ Data Filtering
✅ Conditional Replacement
✅ Reshaping Arrays
✅ Statistical Calculations

---

⭐ Learning NumPy step by step with hands-on practice.
