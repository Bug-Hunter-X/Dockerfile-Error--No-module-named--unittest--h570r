This repository demonstrates a common error encountered when building Docker images for Python projects that utilize unit testing. The initial Dockerfile attempts to run unit tests using the `unittest` module without installing the necessary testing framework or project dependencies. This results in a `ModuleNotFoundError`. The solution demonstrates how to install required packages and resolve the error using a `requirements.txt` file.