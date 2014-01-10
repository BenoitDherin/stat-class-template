This is a vagrant configuration to set up a virtual box running an ipython notebook server accessible from an host browser at http://localhost:8888.

The notebook server started by the execution of "vagrant up" reads and writes its ipython notebooks in the ipynb directory. 

The initial vagrant configuration was spawned from the github repository [Mining the Social Web](https://github.com/ptwobrussell/Mining-the-Social-Web-2nd-Edition).

We add to this initial VB vagrant configuration the following:

* the dependencies needed to convert ipython notebooks into latex files and to compile them into pdf files


* the dependencies needed to run R from within the notebook (%load_ext rmagic) cells


* the standard scientific computing and data analysis package in Python (essentially: numpy, scipy, and pandas)

