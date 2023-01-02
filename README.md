## Python pdf compress and merge

This repository contains python notebook to compress and merge PDF files using *pylovepdf* library. This *pylovepdf* library allows to manipulate pdf using the API of http://www.ilovepdf.com. 
PDF (portable document format) is a platform independent file format which can be used to store data like documents and images. It is a widely used format for data sharing. In this repo there is a notebook *pdf_handling.ipynb* which has functions to compress and merge pdf files. It can be used to compress and merge your personal PDF documents.


There are some pre-requisites to use pypdflove. Please ensure those are followed before using the notebook in this repo.

### Prerequisites:
* [developer account] (https://developer.ilovepdf.com) to get a public key to use the API.
* [Python 3.x.x]
* [Requests] (http://it.python-requests.org/it/latest/)
* create venv before installing package using requirement.txt `python3 -m venv pypdf`. venv name can be per your liking. Its always good practice to provide a meaningful name.

### Limitations:

The ilovepdf API has a free version with limitations. The free account can process only 250 files per month for any API action.

### Size reduction after compressing pdf:

![Compress](compress_size_reduction.png)