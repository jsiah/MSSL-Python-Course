Python Course Material
======================


The course was held at Mullard Space Science Laboratory on 1st of October, 2012.

Presentation
------------

The presentation view graphs are available in PDF and Keynote formate and can be
found in the presentation folder.

Notebooks
---------

iPython (v. 0.13) Notebooks are available in the notebook folder.


Syllabus
--------


* Background Information and Tools
  * Why Python?
  * Syntax, basic types, standard libraries, exception handling, etc.
  * Interactive computing (ipython)
  * How to write documentation within the code (Sphinx)
  * Development tools and version control (PyCharm & GIT)
* Numerical Arrays
  * 1D and N-D arrays, arithmetics, masked arrays, manipulations, and generating random data (NumPy & numexpr)
* Astronomy Specific Packages
  * PyFITS & PyWCS:
	 * Reading, writing, and generating FITS tables and image arrays
	 * World Coordinate Systems
  * PyRAF:
	 * How to call IRAF from Python
* Data Access and Processing:
  * Reading in an ascii file and pickled data (NumPy, cPickle)
  * Database access (sqlite3)
* Scientific analysis:
  * optimisation, fitting, interpolation, and statistics (SciPy, statsmodels)
  * Bayesian MCMC sampler (PyMC, emcee)
* Generating publication quality plots:
  * 2D plotting (matplotlib)
  * Astronomy specific plotting e.g. different projections (Kapteyn)
* Image manipulation:
  * Smoothing and convolving (SciPy)
  * Object detection, segmentation and edge detection (scikits-image) 
* Speeding things up:
  * Parallel programming with multiprocessing
  * Calling C or Fortran code from Python
* Machine learning:
  * Principal Component Analysis (scikits-learn)
  * Supervised Learning, Clustering, etc. (scikits-learn)



Some Useful Packages
--------------------


A small selection of 3rd party packages I have found extremely useful:

* NumPy: a powerful N-dimensional array object, tools for integrating C/C++ and Fortran code, and useful linear algebra, Fourier transform, and random number capabilities.
* SciPy: open-source software for mathematics, science, and engineering.
* matplotlib: a python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments.
* PyFITS: provides an interface to FITS files.
* astropy:a common effort to develop a single core package for Astronomy (contains e.g. PyFITS, PyWCS, vo, asciitable…)
* Kapteyn: provide tools for the development of astronomical applications (WCS projections, non-linear least sq fitting, etc.)
* PyWCS: provides transformations following the SIP conventions and the core WCS functionality.
* SymPy: a Python library for symbolic mathematics
* scikits:add-on toolkits that complement SciPy (sub packages like image, learn, time series, etc.)
* RPy2: provides a low-level interface to R and R-like structures and functions.
* PyMC: Markov Chain Monte Carlo sampling toolkit.
* emcee: implementation of Goodman & Weare’s Affine Invariant Markov Chain Monte Carlo Ensemble sampler.
* PyIDL: python bindings to IDL.
* APLpy: the Astronomical Plotting Library in Python.
* astLib: a set of Python modules that provides e.g. coordinate conversions, manipulating WCS info, perform calculations on SEDs, etc.
* statsmodels: allows users to explore data, estimate statistical models, and perform statistical tests.
* MySQLdb: an thread-compatible interface to the MySQL database server.
* Python Imaging Library (PIL): adds image processing capabilities.
* PyCUDA: gives an easy access to Nvidia‘s CUDA parallel computation API.
* yt-project: provides a consistent, cross-code interface to analyzing and visualizing astrophysical simulation data from a physical perspective.
* mplstereonet: provides lower-hemisphere equal-area and equal-angle stereonets for matplotlib.
* h5py: a general-purpose interface to the Hierarchical Data Format library, version 5.
* Patsy: describing statistical models and building design matrices
* SfePy: software for solving systems of coupled partial differential equations by the finite element method.
* SQLAlchemy: an SQL toolkit and Object Relational Mapper that gives application developers the full power and flexibility of SQL.
* Tkinter: de-facto standard GUI (Graphical User Interface) package.
* PyGtk: a set of Python bindings to the GTK Toolkit.
* PyQt: bindings for the Qt cross-platform GUI/XML/SQL C++ framework.
* Mutagen: a module to handle audio metadata (MP3, Ogg FLAC, etc.).
* Django: a high-level Python Web framework that encourages rapid development and clean, pragmatic design.
* numexpr: evaluates multiple-operator array expressions many times faster than NumPy can.
* PyPy: a fast, compliant alternative implementation of the Python language (2.7.2).
* ATpy: a high-level Python package providing a way to manipulate tables of astronomical data in a uniform way.
