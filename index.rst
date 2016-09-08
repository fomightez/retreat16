.. contents::
   :depth: 3.0
..

Online Companion to Wayne's Poster for Retreat 2016
===================================================

Links and resources for Jupyter Notebook and how to link active
notebooks to Github from poster at Upstate Medical University's
Biomedical Sciences Retreat 2016. \*\* Poster entitled: Biomedical
Science on Jupyter: Comprehensible and Reproducible Scientific Workflows
with Shared, Active Jupyter Notebooks \*\*

Launch Demo Binder
------------------

Go to an example repository by clicking
`HERE <https://github.com/fomightez/uscad16>`__.

Click on the ``launch binder`` button that will look like below:

.. figure:: http://mybinder.org/badge.svg
   :alt: Binder

   Binder

    The button badge above one above doesn't work since it is meant to
    show the typical steps. However, to save you a step, you can click
    the button badge below to launch an active demo notebook.

|Binder|

Give the notebook a minute to load and then press ``SHIFT+ENTER`` on
your keyboard or press the play button (

.. raw:: html

   <button class="fa fa-play icon-play btn btn-xs btn-default">

.. raw:: html

   </button>

) in the toolbar several times to step through and run cells.

Those that should run will have the ``In [ ]`` on the left and they will
become filled with numbers when complete. Several will have viewable
output.

Go back to the repository main page. Once there, click the blue text
that says ``Decoding translation in the cloud and at...``.

This will open a rendering of the notebook, but you see all the
``In [ ]`` on the left have nothing between the brackets and none of the
output cells are present.

This is a static rendering of the notebook. We cannot interact with it.
If I had saved the completely run notebook, the output would be there
but we still would not be able to interact with it. (And so it is
useful, but not as useful as an active Jupyter Notebook.)

(A richer version of the static version of the notebook can be viewed
`here <http://nbviewer.jupyter.org/github/fomightez/uscad16/blob/master/Decoding%20translation%20in%20the%20cloud%20and%20at%20NCBI.ipynb>`__
via the `nbviewer <http://nbviewer.jupyter.org/>`__ that will render any
Github-hosted Jupyter Notebook. Often this works better for notebooks
that have fancy plots embedded that the default Github rendering doesn't
handle.)

This was a very simple notebook that has a good mix of the features as
it was meant to touch casually on some molecular biology aspects while
introducing the Jupyter Notebook system to some high school students
that visited Upstate.

The repository hosting that Jupyter Notebook can be found
`here <https://github.com/fomightez/uscad16>`__. To get the
``launch binder`` button to work I had to previously tell the Freeman
Lab's Binder system found at `mybinder.org <http://mybinder.org/>`__ to
build a ``binder`` from that repository at Github. That ``binder`` then
becomes available for users to spin up notebooks on-demand, essentially
instantaneously.

Basic Notebooks to Illustrate Use in the Lab
--------------------------------------------

These links will take you to the Github page where you'll see links to
the static notebooks as well as |Binder| buttons to launch the notebooks
as active notebooks using the Freeman Lab's Binder system found at
`mybinder.org <http://mybinder.org/>`__.

Click the |Binder| button at any of the following repositories for an
active notebook:

-  `ammonium sulfate precipitation screen
   calculator <https://github.com/fomightez/small_scale_ammonium_sulfate_precipitation_calculator>`__

-  `Cell Density
   Estimator <https://github.com/fomightez/methods_in_yeast_genetics/blob/master/cell_density_estimator/>`__

-  `Yeast Growth
   Planner <https://github.com/fomightez/methods_in_yeast_genetics/blob/master/yeast_growth_planner/>`__

-  `Notebook designed as an active computing exercise for young students
   visiting the lab <https://github.com/fomightez/uscad16>`__

Notable Notebooks
-----------------

See the final page of this online documentation for the list of example
scientific Jupyter Notebooks mentioned on the poster. See that page as
well as for the list of those notebooks using the Github/Binder
approach.

To get there, the easiest way is to press ``Next`` in the bottom right
of each page until there isn't a ``Next`` button or click :ref:`#a-sampling-of-scientific-notebooks-extensions`

.. toctree::
   :hidden:
   :maxdepth: 2

   essential resources
   references by poster sections
   making binder

.. |Binder| image:: http://mybinder.org/badge.svg
   :target: http://mybinder.org/repo/fomightez/uscad16/notebooks/Decoding%20translation%20in%20the%20cloud%20and%20at%20NCBI.ipynb
.. |Binder| image:: http://mybinder.org/badge.svg



