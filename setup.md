---
layout: page
title: Setup
permalink: /setup/
root: ..
---

## Installing Python

In this lesson, we will be using Python 3.
Although one can install a plain-vanilla Python and all required libraries by hand,
we recommend installing [Anaconda][anaconda-website],
a Python distribution that comes with everything we need for the lesson.
Detailed installation instructions for various operating systems can be found
on The Carpentries [template website for workshops][anaconda-instructions]
and in [Anaconda documentation][anaconda-install].

## Launch Python interface

To start working with Python, we need to launch a program that will interpret and execute our
Python commands. Below we list several options. If you don't have a preference, proceed with the
top option in the list that is available on your machine which should generally be Jupyter through the
Anaconda installation. Otherwise, you may use any interface you like.

## Option A: Jupyter Notebook

A Jupyter Notebook provides a browser-based interface for working with Python.
If you installed Anaconda, you can launch a notebook in two ways:

> ## Anaconda Navigator
>
> 1. Launch Anaconda Navigator.
> It might ask you if you'd like to send anonymized usage information to Anaconda developers:
> ![Anaconda Navigator first launch](
{{ page.root }}{% link fig/anaconda-navigator-first-launch.png %})
> Make your choice and click "Ok, and don't show again" button.
> 2. Find the "Notebook" tab and click on the "Launch" button:
> ![Anaconda Navigator Notebook launch](
{{ page.root }}{% link fig/anaconda-navigator-notebook-launch.png %})
> Anaconda will open a new browser window or tab with a Notebook Dashboard showing you the
> contents of your Home (or User) folder.
> 3. Launch the notebook by clicking on the "New" button and then selecting "Python 3":
> ![Anaconda Navigator Notebook directory](
{{ page.root }}{% link fig/jupyter-notebook-launch-notebook.png %})
{: .solution}

> ## Command line (Terminal)
>
> 1\. Start Jupyter server
>
> > ## Unix shell
> > ~~~
> > jupyter notebook
> > ~~~
> > {: .language-bash}
> {: .solution}
>
> > ## Command Prompt (Windows)
> > ~~~
> > python -m notebook
> > ~~~
> > {: .source}
> {: .solution}
>
> 2\. Launch the notebook by clicking on the "New" button on the right and selecting "Python 3"
> from the drop-down menu:
> ![Anaconda Navigator Notebook directory](
{{ page.root }}{% link fig/jupyter-notebook-launch-notebook2.png %})
{: .solution}

&nbsp; <!-- vertical spacer -->

## Option B: IPython interpreter

IPython is an alternative solution situated somewhere in between the plain-vanilla Python
interpreter and Jupyter Notebook. It provides an interactive command-line based interpreter with
various convenience features and commands.  You should have IPython on your system if you installed
[Anaconda][anaconda-instructions].

To start using IPython, execute:
~~~
ipython
~~~
{: .source}

&nbsp; <!-- vertical spacer -->

## Option C: plain-vanilla Python interpreter

To launch a plain-vanilla Python interpreter, execute:
~~~
python
~~~
{: .source}

If you are using [Git Bash on Windows][gitbash], you have to call Python _via_ `winpty`:
~~~
winpty python
~~~
{: .source}

[anaconda-install]: https://docs.anaconda.com/anaconda/install
[anaconda-instructions]: https://carpentries.github.io/workshop-template/#python
[anaconda-website]: https://www.anaconda.com/
[gitbash]: https://gitforwindows.org



