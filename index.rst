Welcome to Introduction to GIS using Python!
================================

**Introduction to GIS using Python** is a short, self-paced course that teaches you how to do different GIS-related tasks in Python programming language.
This 'course <https://automating-gis-processes.github.io/2018/index.html>'_ was originally developed by **Henrikki Tenkanen** and **Vuokko Heikinheimo**
from the University of Helsinki, and here I acknowledge their excellent contribution. I have changed some of the lessons, materials and aims from the
original course to suit specific needs.

Each lesson is a tutorial with specific topic(s) where the aim is to learn how to solve common GIS-related problems and
tasks using Free and Open Source Software (FOSS) and Python tools. In this course we only use publicly available data which can be used and downloaded by anyone anywhere.

.. warning:: we assume that you know the basics of Python programming. If Python is not familiar to you, I recommend to start with
learning the basics of Python.


Course format
-------------

The majority of this course will be spent in front of a computer learning to program with Python and doing practical exercises.
The computer exercises will focus on developing basic programming skills using Python and applying those skills to various GIS related problems.
Typical exercises will involve a brief introduction, followed by topical computer-based tasks and exercises. At the end of the exercises, you can compare
your plots and the Python codes you have written with ours.

.. admonition:: Open Access!

    The course is **open for everyone**. The aim of this course is to share the knowledge and help people to get started with their journey for doing GIS more efficiently and in a reproducible manner
    using Python programming.

.. admonition:: Step by step instructions

    The materials are written in a way that you can follow them step by step exactly as they are written, however **you need to adjust the file paths to the data** to your specific file paths.


Course topics
--------------


+----------------+---------------------------------+
| Lesson         | Theme                           |
+================+=================================+
| **Lesson 1**   | GIS in Python;                  |
|                | Spatial data model;             |
|                | Geometric Objects; Shapely      |
|                |                                 |
+----------------+---------------------------------+
| **Lesson 2**   | Working with GeoDataFrames;     |
|                | Managing projections;           |
|                | Table join;                     |
|                |                                 |
+----------------+---------------------------------+
| **Lesson 3**   | Geocoding and making spatial    |
|                | queries                         |
|                |                                 |
|                |                                 |
+----------------+---------------------------------+
| **Lesson 4**   | Geometric operations;           |
|                | Reclassifying data with Pysal   |
|                |                                 |
+----------------+---------------------------------+
| **Lesson 5**   | Visualization, making static    |
|                | and interactive maps            |
|                |                                 |
+----------------+---------------------------------+
| **Lesson 6**   | Network analysis and routing    |
|                | in Python (transport modelling) |
|                |                                 |
+----------------+---------------------------------+
| **Lesson 7**   | Using Python programming in     |
|                | QGIS                            |
|                |                                 |
+----------------+---------------------------------+

|

Contents
--------
*Lesson contents are subject to change*

.. toctree::
   :maxdepth: 2
   :caption: Course information

   course-info/course-info
   course-info/course-environment-components
   course-info/grading
   course-info/learning-goals
   course-info/Installing_Anacondas_GIS
   course-info/resources
   course-info/License-terms

.. toctree::
   :maxdepth: 2
   :caption: Lesson 1

   lessons/L1/Intro-Python-GIS
   lessons/L1/overview
   notebooks/L1/geometric-objects.ipynb
   lessons/L1/exercise-1

.. toctree::
   :maxdepth: 2
   :caption: Lesson 2

   lessons/L2/overview
   notebooks/L2/geopandas-basics.ipynb
   notebooks/L2/projections.ipynb
   lessons/L2/exercise-2

.. toctree::
   :maxdepth: 2
   :caption: Lesson 3

   lessons/L3/overview
   lessons/L3/geocoding
   notebooks/L3/geocoding_in_geopandas.ipynb
   notebooks/L3/point-in-polygon.ipynb
   notebooks/L3/spatial-join.ipynb
   notebooks/L3/nearest-neighbour.ipynb
   lessons/L3/exercise-3

.. toctree::
   :maxdepth: 2
   :caption: Lesson 4

   lessons/L4/overview
   notebooks/L4/reclassify.ipynb
   notebooks/L4/geometric-operations.ipynb
   lessons/L4/exercise-4

.. toctree::
   :maxdepth: 2
   :caption: Lesson 5

   lessons/L5/overview
   notebooks/L5/static_maps.ipynb
   notebooks/L5/interactive-map-folium.ipynb
   lessons/L5/share-on-github
   lessons/L5/exercise-5

.. toctree::
   :maxdepth: 2
   :caption: Lesson 6

   lessons/L6/overview
   notebooks/L6/retrieve_osm_data.ipynb
   notebooks/L6/network-analysis.ipynb
   lessons/L6/exercise-6

.. toctree::
   :maxdepth: 2
   :caption: Lesson 7

   lessons/L7/overview
   lessons/L7/pyqgis
   lessons/L7/processing-toolbox
   lessons/L7/processing-script
   lessons/L7/exercise-7

.. toctree::
   :maxdepth: 2
   :caption: Final Assignment

   lessons/FA/final-assignment
