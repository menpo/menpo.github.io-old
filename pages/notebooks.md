Title: Notebooks
url: notebooks.html
save_as: notebooks.html

As part of the project, we maintain a set of IPython notebooks that help
illustrate how Menpo should be used.

The notebooks are kept inside their
[own Github repository](http://www.github.com/menpo/menpo-notebooks).
If you wish to view the static output of the notebooks, feel free to browse
them online using the provided links. This gives a great way to passively read
the notebooks without needing a full Python environment. Note that these copies
of the notebook contain only static output and thus cannot be run.

To download the notebooks and use them within your copy of Menpo, use the
links provided.

### **(v0.3.0) - Latest Notebooks**
  - **[Browse Online](http://nbviewer.ipython.org/github/menpo/menpo-notebooks/tree/v0.3.0/notebooks/)**
  - **[Download](https://github.com/menpo/menpo-notebooks/archive/v0.3.0.zip)**

### Running The Notebooks Locally
In order to experiment with the Menpo codebase, we suggest you download the
notebooks and run them yourself. Before being able to run the notebooks you
**must install menpo**. Head to the
[installation instructions]({filename}/pages/installation/index.md) before
continuing.

 1. Start by downloading the notebooks and extracting the zip somewhere on your
    local disk. Please substitute **NOTEBOOKS_PATH** with this path in the
    following instructions.
 2. We then need to run the notebooks using the `ipython notebook` application.
    Begin by opening a command prompt/terminal and changing to the directory
    where you extracted the notebooks:

    **OSX/Linux**

        ::console
        $ cd NOTEBOOKS_PATH
        $ source activate menpo
        (menpo) $ ipython notebook

    **Windows**

        ::console
        C:\>cd NOTEBOOKS_PATH
        NOTEBOOKS_PATH>activate menpo
        [menpo] NOTEBOOKS_PATH>ipython notebook

 3. A browser should open and show the ipython notebook browser. Click a
    notebook to open it. You can now run the notebooks by executing each code
    cell and following the documentation provided inside the notebook. If you
    are unfamiliar with the IPython notebook environment, please consult
    their [documentation](http://ipython.org/notebook.html).

### Previous Notebooks
These notebooks are versioned in an identical manner
to the main Menpo project. Therefore, you should make sure to use the version
of the notebooks that matches the version of Menpo you are using.

To check which version of Menpo you are using, run:

    :::python
    >>> import menpo
    >>> print(menpo.__version__)


inside of a Python interpreter.

#### Versions
  - v0.2.5
    - [Browse](http://nbviewer.ipython.org/github/menpo/menpo-notebooks/tree/v0.2.5/notebooks/)
    - [Download](https://github.com/menpo/menpo-notebooks/archive/v0.2.5.zip)
  - v0.2.4
    - [Browse](http://nbviewer.ipython.org/github/menpo/menpo-notebooks/tree/v0.2.4/notebooks/)
    - [Download](https://github.com/menpo/menpo-notebooks/archive/v0.2.4.zip)
  - v0.2.3
    - [Browse](http://nbviewer.ipython.org/github/menpo/menpo-notebooks/tree/v0.2.3/notebooks/)
    - [Download](https://github.com/menpo/menpo-notebooks/archive/v0.2.3.zip)
  - v0.2.2
    - [Browse](http://nbviewer.ipython.org/github/menpo/menpo-notebooks/tree/v0.2.2/notebooks/)
    - [Download](https://github.com/menpo/menpo-notebooks/archive/v0.2.2.zip)
