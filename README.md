# Example project using statistics-resampling-online

This is an example project using [statistics-resampling-online](https://github.com/acpennlab/statistics-resampling-online/tree/jammy-docker). Click the `launch binder` button below to load the example project in your web browser.

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/acpennlab/statistics-resampling-online/jammy-docker?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Facpennlab%252Fstatistics-resampling-project%26urlpath%3Dlab%252Ftree%252Fstatistics-resampling-project%252Findex.ipynb%26branch%3Dmaster)

Note that using this resource requires an active internet connection and an internet browser with javascript enabled. (If you don't know what that means then it probably is already!)

🚧🔧 Parts of the documentation and example notebooks for this project are under construction 🔨🚧  

## How to use this template for your own data analysis projects

This binder loads a JupyterLab instance of the `statistics-resampling-project` repository. There are two possible methods that we recommend for using `statistics-resampling-online` for longer-term analysis projects, one that requires a local installation of GitHub Desktop (method 1) and one that is online-only (method 2).

### Method 1
Here follows a list of steps describing how you can set up a GitHub repository to use `statistics-resampling-online` for your own data analysis project.
1. If you don't already have a GitHub account, create one by following the instructions [here](https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account)
2. If you don't already have GitHub Desktop app, download and install it by following the instructions [here](https://docs.github.com/en/desktop/installing-and-authenticating-to-github-desktop/installing-github-desktop)
3. In your browser, go to the [acpennlab/statistics-resampling-project](https://github.com/acpennlab/statistics-resampling-project) and click the 'Use this template' button and 'Create a new repository' from the dropdown menu. In the settings for your new GitHub repository, give it a name and description and ensure that the visibility is set to `public`. (Further information about creating a GitHub repository from a template is available [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template).
4. In your new GitHub respoitory, edit the link in the Binder badge using a new URL created by the `Binder` tab form at [nbgitpuller](https://nbgitpuller.readthedocs.io/en/latest/link.html?tab=binder) using the following settings: 
  * BinderHub URL: `https://mybinder.org` 
  * Git Environment Repository URL: `https://github.com/acpennlab/statistics-resampling-online` 
  * Git Environment Repository Branch: `jammy-docker`  
  * Git Content Repository URL: `https://github.com/<owner>/<repository>`  
  * Git Environment Repository Branch: `master`  
  * File to open: `index.ipynb`
  * Application to Open: `JupyterLab`  
  *N.B Ensure that you replace \<owner\> and \<repository\> with your GitHub ID and the name that you gave to your repository upon creation*
5. Make a local copy of your repository by cloning your new statistics-resampling-project repository using the GitHub Desktop app by following the instructions [here](https://docs.github.com/en/desktop/adding-and-cloning-repositories/cloning-a-repository-from-github-to-github-desktop)
6. Edit the settings in your browser settings to prompt the user for the location of loaded files and ensure that java script is enabled. How to do this well depend on your browser. For Chrome, see the section on how to *'Change download location'* [here](https://support.google.com/chrome/answer/95759?hl=en-GB&co=GENIE.Platform%3DDesktop#zippy=%2Cchange-download-locations) 
7. On the GitHub repository page in your browser, click the updated Binder badge to launch your project
8. Edit or upload your data and create and edit your notebooks within the temporary instance of JupyterLab
9. From the file menu, save and then download your files to your local copy of the repository (replacing existing files if necessary). Note that if your instance of Binder times-out, use the Jupyter-Offline-Notebook toolbar to store the visible copy of the notebook (as described [here](https://github.com/manics/jupyter-offlinenotebook)). 
10. Finally, in GitHub desktop, enter a short commit summary and push the changes to the `master` branch of your online GitHub repository. Next time, simply return to your GitHub repo site and repeat the last four steps (7-10) of these instructions to continue with your project.

### Method 2
This method uses the Git extension in Jupyterlab to push changes (saved and stashed commits) directly to the GitHub reposiory online. In addition to creating a GitHub account and repository (steps 1, 3 and 4 of method 1), pushing commits requires you to enter your username (i.e. name of owner of the GitHub repository you created) and a personal access token (which you also need to create). To create a classic personal access token, follow the instructions [here](https://docs.github.com/en/enterprise-server@3.9/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens) - you will only need to include the `repo` scopes for this personal access token. More details to follow shortly...


## Links
If you use this resource, make it easier to find by giving the [acpennlab/statistics-resampling-project](https://github.com/acpennlab/statistics-resampling-project) repository a [star](https://docs.github.com/en/get-started/exploring-projects-on-github/saving-repositories-with-stars). 🌟

If you have any issues or suggestions for the [statistics-resampling-online environment](https://github.com/acpennlab/statistics-resampling-online), please post an issue [here](https://github.com/acpennlab/statistics-resampling-online/issues).

If you have any issues or suggestions for the example content at [statistics-resampling-project](https://github.com/acpennlab/statistics-resampling-project), please post an issue [here](https://github.com/acpennlab/statistics-resampling-project/issues).

Please cite the following in any publication that uses the [statistics-resampling](https://github.com/gnu-octave/statistics-resampling) package, which is included in this binder:

* Penn, Andrew Charles. (2020). Resampling methods for small samples or samples with complex dependence structures. *Zenodo*. [https://doi.org/10.5281/zenodo.3992392](https://doi.org/10.5281/zenodo.3992392)
  
  [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3992392.svg)](https://doi.org/10.5281/zenodo.3992392)

The documentation for the statistics-resampling package can be found at the following link: 

[![Documentation](https://img.shields.io/badge/docs-online-blue.svg)](https://gnu-octave.github.io/statistics-resampling/)
