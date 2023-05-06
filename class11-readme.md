# class11
## What are the key features and benefits of Jupyter Lab, and how does it differ from Jupyter Notebook?
Jupyter Lab is an IDE for Jupyter notebooks, code files, and data files. It has a flexible interface, enhanced code editing and debugging tools, and supports various file formats. It can be integrated with other tools and services.

Jupyter Notebook, on the other hand, is a web-based application that allows you to create and share documents that contain live code, equations, visualizations, and narrative text. While Jupyter Notebook has many of the same features as Jupyter Lab, it is more limited in terms of its interface and functionality.


## What are the main functionalities provided by the NumPy library, and how can it be useful in Python programming, particularly for scientific computing and data manipulation tasks?

NumPy Library:
NumPy is a Python library that provides support for large, multi-dimensional arrays and matrices, as well as a wide range of mathematical functions for performing operations on these arrays. Some of the main functionalities provided by the NumPy library include:

Creating arrays and matrices: NumPy provides a range of functions for creating arrays and matrices, including ones, zeros, empty, and arange.
Manipulating arrays and matrices: NumPy provides a range of functions for manipulating arrays and matrices, such as reshape, transpose, concatenate, and split.
Performing mathematical operations: NumPy provides a wide range of mathematical functions for performing operations on arrays and matrices, such as addition, subtraction, multiplication, division, and more advanced operations like dot product and eigenvalues.
Reading and writing data: NumPy provides functions for reading and writing data from and to files, including CSV, TXT, and binary formats.

NumPy is particularly useful for scientific computing and data manipulation tasks, as it allows you to work with large datasets efficiently and perform complex mathematical operations easily.

## Explain the basic structure and properties of NumPy arrays, and provide examples of how to create, manipulate, and perform operations on them.
NumPy arrays are multi-dimensional and homogeneous, with a fixed size determined at creation. They support indexing and slicing, and can be efficiently manipulated using mathematical and scientific operations. Broadcasting allows for element-wise operations between arrays with different shapes and sizes. NumPy arrays are widely used in scientific computing and data analysis applications.

        import numpy as np

        # Creating arrays
        a = np.array([1, 2, 3])         # 1D array
        b = np.array([[1, 2], [3, 4]]) # 2D array

        a = np.array([1, 2, 3])
        b = np.array([4, 5, 6])
        c = a + b
        print(c)
        OUTPUT: array([5, 7, 9])

        a = np.array([1, 2, 3])
        mean = np.mean(a)
        print(mean)
        OUTPUT: 2.0