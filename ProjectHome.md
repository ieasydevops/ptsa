ptsa (pronounced pizza) is a Python module for performing time series analysis.  Although it is specifically designed with neural data in mind (EEG, MEG, fMRI, etc...), the code should be applicable to almost any type of time series.

At the foundation of ptsa is a subclass of the NumPy ndarray called DimArray, that allows for tracking dimension information as part of a ndarray.