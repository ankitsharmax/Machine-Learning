## Numpy

<b>NumPy</b> (Numerical Python) is an open source Python library that’s used in almost every field of science and engineering. It’s the universal standard for working with numerical data in Python, and it’s at the core of the scientific Python.

NumPy API is used widely in Pandas, SciPy, Matplotlib, scikit-learn, scikit-image and most other data science and scientific Python packages.

- The NumPy library contains multidimensional array and matrix data structures 
- It provides ndarray, a homogeneous n-dimensional array object
- NumPy is used to perform a wide variety of mathematical operations on arrays basically for ndarray.
- guarantee efficient calculations with arrays and matrices and it supplies an enormous library of high-level mathematical functions

## Content:

### Day 1 Numpy:
- 1. Installing Numpy 
- 2. Why to choose numpy
- 3. Applications of Numpy
- 4. Basics of NumPy
- 5. Datatypes in NumPy
- 6. Range in numpy 	```np.arange()  |   np.linspace()   ```
- 7. Array with all zeros and ones
- 8. Reshaping array
- 9. Resizing array 	```Difference between reshape and resize```
- 10. Array Indexind and Slicing

### Day 2 Numpy:
- 1. Indexing and Slices with 3D arrays
- 2. Different types of array in numpy
	- zeros
	- ones
	- full
	- full_like
	- random.rand
	- random.randint
	- random.random_sample
	- identity
	- repeat (copying)
	- copy (copying)
	
- 3. Difference between rand and randn
	- Explanation with visualization
	- ```np.random.rand``` is for Uniform distribution (in the half-open interval ```[0.0, 1.0)```)
	- ```np.random.randn``` is for Standard Normal (aka. Gaussian) distribution (mean 0 and variance 1)
	
- 4. Solving a basic problem
<b><center>Create a Numpy matrix like this</center><br>

<table>
    <tr>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
    </tr>
    <tr>
        <td>1</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
    </tr>
    <tr>
        <td>1</td>
        <td>0</td>
        <td>9</td>
        <td>0</td>
        <td>1</td>
    </tr>
    <tr>
        <td>1</td>
        <td>0</td>
        <td>0</td>
        <td>0</td>
        <td>1</td>
    </tr>
    <tr>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
    </tr>
</table>