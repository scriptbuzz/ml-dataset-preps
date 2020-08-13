# tabular data exploration and preperations
This is a collection of tools and code snippets I employ frequently as part of my data preparation workflow. 

I frequently prep structured and semi-structured tabular data for various target consumers be it training machine learning models, ad-hoc data analysis and visualization, ETL, importing into other data stores, and so on. Over the years, I have become dependent on a core set of Python tools, libraries, and techniques for my data prep pipeline. 

Why data preparations? More often than not, when I work with raw tabular data, it's  rarely ready for consumption. Common issues include missing data values, inconsistent data formats such as non-standard date/time values, outliers, columns that don't contribute to training a machine learning model, string-formatted categorical data that needs to be transformed into numeric data for number crunching, data that should be one-hot encoded, etc.

Before we start, let me introduce my core tools and packages for data preparations and visualization. Depending on the use case, I might import additional libraries to augment the capabilities of my core set of tools:

- **Python:** this is one of a number of programming languages with a rich ecosystem of data processing libraries and tools. It's also one of the easiest to learn. As of August 2020, Python ranked 3rd on the TIOBE index of programming languages. https://www.python.org/

- **Jupyter Notebooks:** If I am not using a classic IDE to program in Python, I am using Jupyter notebooks. The ability to embed code and code execution results in one live web document that can be saved, shared, and re-edited turns out to be a boost to productivity. https://jupyter.org/

- **NumPy:** a library for the Python programming language with support for large multi-dimensional arrays. NumPy also includes a vast collection of mathematical functions to operate on tabular data. NumPy is a foundational library for other higher-level libraries such as Pandas. https://numpy.org/

- **Pandas:** a high-performance, easy-to-use data analysis and manipulation library. Pandas is the by far the most popular Python library for data preparation. https://pandas.pydata.org/

- **matplotlib:** a library for creating static or interactive visualizations of tabular data. https://matplotlib.org/

- **seaborn:** a data visualization library based on matplotlib. It simplifies the generation of colorful graphics for statistical analysis. https://seaborn.pydata.org/

- **sklearn:** a general machine learning library build on NymPy and matplotlib with a rich set of general ML models but also supports data prep routines. For Deep Learning data prep, frameworks like TensorFlow and PyTorch have their own data prep routines. https://scikit-learn.org/

# Data Exploration With Pandas

This link will open a Jupyter notebook listing Pandas operations I use frequently to explore tabular datasets:

https://github.com/scriptbuzz/tabular-data-preps/blob/master/ml_data_prep.ipynb

Coming next...

- Data visualization with matplotlib and seaborn
- Data preperations with pandas
- Feature selection and engineering with sklearn
