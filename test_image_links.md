# Appendix: Making your first Binder

## Preparation

- Obtain a Github account if you don't already have one

- Items to make in preparation

	- a Jupyter Notebook. Only absolute requirement.

	I suggest developing inside a notebook spawned from someone else's Github/Binder combination or tmpnb.org. Save often and local. Or simply copy an example notebook for testing. Notebooks end in the `.ipynb` extension.

	- requirements.txt file to specify dependencies.

	See step #2 at http://mybinder.org/. (Technically, not absolutely required if your needs don't extend beyond basic or mybinder.org already has the needed module installed, such as what happened when I looked into `bokeh`. They already had it. This can be confirmed by typing in Alternatively, there are other way to specify dependencies, see [the site](http://mybinder.org/).)

## Readying your Github Repository

- Upload the Jupyter Notebook file to a repository at Github.

- If needed, add the `requirements.txt` file to the repo to point at pypi modules needed. See step #2 at http://mybinder.org/

- Copy to your clipboard the address of your repository. It will resmble

	https://github.com/github_user_name/repository_name



## Point my binder at your Github Repository

- Go to mybinder.org and paste the address if your Github repository in the form next to the `submit` button.

![where to submit](images/mybinder.org%20page%20for%20making%20image.png)

<img src="images/mybinder.org%20page%20for%20making%20image.png" width="417" height="496" align="center" />

- Press `Submit` to start the build process.

It will then look something like this if it starts working.

![building](images/binder%20being%20built.png)

- Let it process. Only when all three dots on the left side turn green is it build.


Below is how the green lights on the side will look when it is done building the Binder from your repository.


![when done building](images/binder%20built.png)

- Grab the code for your launch button badge. They have markdown and restructured text versions available right there.

![badge code area](images/grab%20badge%20code%20area%20from%20mybinder.org%20build.png)

The launch badge button is just an image linked to an html link that will trigger deploying of your notebook immediately on-demand via mybinder.org. Because the link conforms to a certain convention, you can also build it yourself later. The link to trigger launching an active form of your notebook will look like:

http://mybinder.org/repo/fomightez/repo_name

-or-

http://mybinder.org/repo/fomightez/repo_name/notebooks/specific_notebook.ipynb

You can easily get the code for the badge button off the build page or edit someone else's links to point at yours. For example, you can use my text [here](https://github.com/fomightez/uscad16) to make badge buttons and/or links.

This is what the launch button badge looks like ---> ![Binder](http://mybinder.org/badge.svg)

- Paste the `launch binder` button code in your README.md at your repository or put the link elsewhere.



## Use your Binder

- Test by launching an active notebook using the links and/or `launch binder` button badge.

- Share the link with others or point them at the site of the button.

