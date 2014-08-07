Title: Installation
url: installation/index.html
save_as: installation/index.html

We provide detailed guides for installing Menpo on each of the 3 major operating
systems. Menpo is designed to provide a suite of tools to solve a complex
problem and therefore has a complex set of dependencies. In order to make
things as simple as possible for new Python developers, we advocate the use
of [Conda](http://conda.pydata.org/). Therefore, our installation instructions
focus on getting Conda installed on each of the platforms.

**Before we begin, please choose an operating system:**

  - [Windows]({filename}/pages/installation/windows/index.md)
  - [OS X]({filename}/pages/installation/osx/index.md)
  - [Linux]({filename}/pages/installation/linux/index.md)

### Upgrading
Assuming you have followed the installation instructions above, you may need
to upgrade your version of Menpo to that latest. You can check if you
have the latest version by running the following commands within a Python
interpreter:

    ::python
    >>> import menpo
    >>> print(menpo.__version__)

If you need to upgrade, you can do this using `conda` using the command **(make
the sure the `menpo` environment is activated)**:

**OSX/Linux**

    ::console
    $ source activate menpo
    (menpo) $ conda update -c menpo menpo

**Windows**

    ::console
    C:\>activate menpo
    [menpo] C:\>conda update -c menpo menpo
