Deprecations
------------

``dpi_cor`` property of `.FancyArrowPatch`
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
This parameter is considered internal and deprecated.


Colorbar docstrings
~~~~~~~~~~~~~~~~~~~
The following globals in :mod:`matplotlib.colorbar` are deprecated:
``colorbar_doc``, ``colormap_kw_doc``, ``make_axes_kw_doc``.

``FancyBboxPatch(..., boxstyle="custom", bbox_transmuter=...)``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In order to use a custom boxstyle, directly pass it as the *boxstyle* argument
to `.FancyBboxPatch`.  This was previously already possible, and is consistent
with custom arrow styles and connection styles.

``FigureCanvasBase.get_window_title`` and ``FigureCanvasBase.set_window_title``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
... are deprecated.  Use the corresponding methods on the FigureManager if
using pyplot, or GUI-specific methods if embedding.
