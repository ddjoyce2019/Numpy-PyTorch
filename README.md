## Introduction to NumPy

For those who are new to Numpy, here's a concise overview of the key aspects of the framework:

Numpy is a fundamental library for numerical computations in Python, offering a versatile set of tools for working with arrays and matrices. Its main features include:

- **Efficient Array Operations**: Numpy provides an array-like data structure that enables efficient manipulation of large datasets with support for various mathematical operations.

- **Multi-dimensional Arrays**: Numpy introduces the concept of multi-dimensional arrays, allowing you to work with matrices and arrays of any dimension.

- **Broad Range of Functions**: The library offers an extensive collection of mathematical functions, ranging from basic arithmetic to advanced linear algebra and statistical operations.

- **Indexing and Slicing**: Numpy provides flexible indexing and slicing capabilities that enable you to extract and manipulate subsets of data arrays easily.

- **Broadcasting**: Numpy's broadcasting feature simplifies operations on arrays with different shapes, making it more intuitive to perform element-wise computations.

- **Integration with Other Libraries**: Numpy is often used as a foundation for other scientific and machine learning libraries due to its efficiency and versatility.

In the upcoming sections of this assignment, we will delve into the realm of Numpy and focus on its core functionalities, demonstrating how to harness its capabilities to process data and perform various numerical tasks efficiently. Just as in the case of PyTorch, gaining a solid understanding of Numpy is essential for effectively working with data and implementing algorithms in the context of this course.

Few Resources which would be useful to get started with:

https://numpy.org/doc/stable/ (Official Documentation)

https://www.w3schools.com/python/numpy/numpy_intro.asp

https://www.youtube.com/watch?v=QUT1VHiLmmI

## Brief introduction to PyTorch


For anyone who is new to PyTorch, here is a quick glance of the features of the framework:   
- Numpy-like API with GPU support
- Pythonic object-oriented programming paradigm
- Dynamic computation graph generation and execution
- Automatic differentiation

We will be using PyTorch for the programming assignments of this course. Thus, it is crucial to have clarity on how to build and train networks using torch.

There are three main components to any deep learning pipeline:
1. **Data loading and preprocessing**: PyTorch provides `torch.utils.data.Dataset` and `torch.utils.data.DataLoader` utilities to facilitate data fetching and batch collation.
2.  **Model creation**: Most models can be created by subclassing `nn.Module` and overriding the `forward` method. The user does not need to implement the backprop, as it is handled by PyTorch's autograd system.
3. **Model training**: Torch provides optimizers and losses through the `torch.optim` and `torch.nn` modules to be used during model training.

