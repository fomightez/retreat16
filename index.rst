.. contents::
   :depth: 3.0
..

Online Companion to Wayne's Poster for Retreat 2016
===================================================

Links and resources for Jupyter Notebook and how to launch shareable
active Jupyter Notebooks from a poster presented at Upstate Medical
University’s Biomedical Sciences Retreat 2016. Poster entitled:
**Biomedical Science on Jupyter: Comprehensible and Reproducible
Scientific Workflows with Shared, Active Jupyter Notebooks**

Launch Demo Binder
------------------

Go to an example repository by clicking
`HERE <https://github.com/fomightez/uscad16>`__.

Once there, click on the |Binder| button to launch the demo.

Give the notebook a minute to load and then press
``SHIFT+ENTER`` on your keyboard or press the play button in the toolbar
several times to step through and run cells.

The cells that should run will have the ``In [ ]`` on the left and they will
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
introducing the Jupyter Notebook system to some students that visited
Upstate.

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

-  `Ammonium Sulfate Precipitation Screen
   Calculator <https://github.com/fomightez/small_scale_ammonium_sulfate_precipitation_calculator>`__

-  `Cell Density
   Estimator <https://github.com/fomightez/methods_in_yeast_genetics/blob/master/cell_density_estimator/>`__

-  `Yeast Growth
   Planner <https://github.com/fomightez/methods_in_yeast_genetics/blob/master/yeast_growth_planner/>`__

-  `Notebook designed as an active computing exercise for young students
   visiting the lab <https://github.com/fomightez/uscad16>`__

Notable Notebooks
-----------------

See the penultimate page of this online documentation for `a list of
example scientific Jupyter
Notebooks <http://retreat16.readthedocs.io/en/latest/references%20by%20section/#a-sampling-of-scientific-notebooks-extensions>`__,
entitled ``A sampling of scientific notebooks & extensions``.

To get there, the easiest way is to click
`here <http://retreat16.readthedocs.io/en/latest/references%20by%20section/#a-sampling-of-scientific-notebooks-extensions>`__
press or ``Next`` in the bottom right of each page three times to get to the
page entitled ``References and Resources to Match Poster Sections``.

See that
page as well as for `the list of example notebooks using the
Github/Binder
approach <http://retreat16.readthedocs.io/en/latest/references%20by%20section/#other-noteable-notebooks-using-github-binder-approach>`__.

.. toctree::
   :maxdepth: 2
   :hidden:

   self
   essential resources
   poster
   references by section
   using tmpnb
   making binder

.. |Binder| image:: http://mybinder.org/badge.svg
