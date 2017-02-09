================================================================================
                            Graphics algorithms
================================================================================

Various graphics algorithms I learned. Mostly Python program using either
Tkinter or Python Imaging Library (PIL).


Tkinter events serializer
--------------------------------------------------

Most Tkinter-based script relies on ``tk.py``, it's my attempt to express
interactive tasks in an imperative way.


BSP tree demo (tkinter)
--------------------------------------------------------------------------------

**BSP-tree-tkdemo.py** allows to edit a polygon and represents it as
a BSP tree. Then a user may check if a point lies inside or outside
the drawn polygon using the tree.

.. image:: img/BSP-tree-tkdemo.png


Approximation of a Bezier curve (tkinter)
--------------------------------------------------------------------------------

**cbezier-as-tkdemo.py** use different metrics to approximate
a Bezier curve with polyline.

.. image:: img/cbezier-as-tkdemo.png


Intersection of Bezier curves (tkinter)
--------------------------------------------------------------------------------

**cbezier-cc-tkdemo.py** approximates curves with polylines,
then check intersection of polylines.

.. image:: img/cbezier-cc-tkdemo.png


Find a convex hull using Graham algorithm (tkinter)
--------------------------------------------------------------------------------

**graham-tkdemo.py** calculates convex hull of point using Graham algorithm.

.. image:: img/graham-tkdemo.png

.. image