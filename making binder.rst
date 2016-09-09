.. contents::
   :depth: 3.0
..

Appendix: Making your first Binder
==================================

Preparation
-----------

-  Obtain a Github account if you don't already have one

-  Items to make in preparation

   -  a Jupyter Notebook. Only absolute requirement.

       I suggest developing inside a notebook spawned from someone
       else's Github/Binder combination or tmpnb.org. Save often and
       local. Or simply copy an example notebook for testing. Notebooks
       end in the ``.ipynb`` extension.

   -  requirements.txt file to specify dependencies.

       See step #2 at http://mybinder.org/. (Technically, not absolutely
       required if your needs don't extend beyond basic or mybinder.org
       already has the needed module installed, such as what happened
       when I looked into ``bokeh``. They already had it. This can be
       confirmed by typing in Alternatively, there are other way to
       specify dependencies, see `the site <http://mybinder.org/>`__.)

Readying your Github Repository
-------------------------------

-  Upload the Jupyter Notebook file to a repository at Github.

-  If needed, add the ``requirements.txt`` file to the repo to point at
   pypi modules needed. See step #2 at http://mybinder.org/

-  Copy to your clipboard the URL address of your repository. It will
   resmble

   https://github.com/github\_user\_name/repository\_name

Point my binder at your Github Repository
-----------------------------------------

-  Go to the `mybinder.org site <mybinder.org>`__.

.. figure:: https://raw.githubusercontent.com/fomightez/retreat16/master/images/mybinder.org%20page%20for%20making%20image.png
   :alt: The MyBinder site

-  Paste the address if your Github repository in the space next to the
   ``submit`` button.

.. figure:: https://raw.githubusercontent.com/fomightez/retreat16/master/images/mybinder.org%20page%20submit%20slot%20highlight.png
   :alt: paste next to the submit button

-  Press ``Submit`` to initiate the build process.

\*\* It will then look something like this as it starts building the
launchable Binder version of your repository.\*\*

.. figure:: https://raw.githubusercontent.com/fomightez/retreat16/master/images/binder%20being%20built.png
   :alt: building

-  Let it process. Only when all three dots on the left side turn green
   is it built, like below.

.. figure:: https://raw.githubusercontent.com/fomightez/retreat16/master/images/binder%20built.png
   :alt: when done building

-  Grab the code for your launch button badge. They have markdown and
   restructured text versions available right there.

.. figure:: https://raw.githubusercontent.com/fomightez/retreat16/master/images/grab%20badge%20code%20area%20from%20mybinder.org%20build.png
   :alt: badge code area

The launch badge button is just an image linked to an html link that
will trigger deploying of your notebook immediately on-demand via
mybinder.org. Because the link conforms to a certain convention, you can
also build it yourself later. The link to trigger launching an active
form of your notebook will look like:

http://mybinder.org/repo/user\_name/repo\_name

-or-

http://mybinder.org/repo/user\_name/repo\_name/notebooks/specific\_notebook.ipynb

You can easily get the code for the badge button off the build page or
edit someone else's links to point at yours. For example, you can use my
text `here <https://github.com/fomightez/uscad16/blob/master/README.md>`__ to make badge
buttons and/or links to your launchable notebooks. (Click the ``raw`` button to see the raw code for copying.)

This is what the launch button badge looks like ---> |Binder|

-  Paste the ``launch binder`` button code in your README.md at your
   repository or put the link elsewhere.

Use your Binder
---------------

-  Test by launching an active notebook using the links and/or
   ``launch binder`` button badge.

    The active notebook should launch close to immediately (within
    several seconds) and you'll be ready to go.

-  Share the link with others or point them at the site of the button.

.. |Binder| image:: http://mybinder.org/badge.svg
