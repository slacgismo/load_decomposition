# Load Decomposition Analysis

This project tests the application of Bennet Meyers' signal decomposition to the residential end-use load decomposition problem.

To run the notebooks in this repository on your local system you will need to install [GridLAB-D](https://github.com/slacgismo/gridlabd).

Alternative, you can download [Docker](https://www.docker.org), pull the [GridLAB-D image](https://dockerhub.com/slacgismo/gridlabd), and create an alias to run the docker image from your local shell, e.g.,

~~~
alias gridlabd="docker run -it -v $PWD:$PWD slacgismo/gridlabd:latest gridlabd"
~~~

Add this command to you `~/.bashrc` file will make this available to all notebooks.
