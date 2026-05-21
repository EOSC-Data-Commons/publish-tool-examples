# publish-tool-examples

A collection of Python Jupyter notebooks to showcase how to publish tools to the `tools-registry`.

## Notebooks

| Notebook                                                                 | Description                                                        |
| ------------------------------------------------------------------------ | ------------------------------------------------------------------ |
| [publish-simple-tool-example.ipynb](./publish-simple-tool-example.ipynb) | A simple example of how to publish a tool to the `tools-registry`. |

## Getting Started

The simplest way to run the notebook is to use an online service like Google colab. You can also use [EGI Notebooks](https://notebooks.egi.eu/)
or run the notebook locally using Jupyter Notebook or Jupyter Lab.

Using Google Colab:

1. Go to [colab.research.google.com](https://colab.research.google.com/).
2. In `Open notebook`, select the `GitHub` tab.
3. Paste the Github url `https://github.com/EOSC-Data-Commons/publish-tool-examples`. This load the list of notebooks in the repository.
4. Click on the notebook you want to run, for example `publish-simple-tool-example.ipynb`.
5. Follow the instructions in the notebook to publish your tool to the `tools-registry`.

Using EGI Notebooks:

Pre-requisites for the first time:
* Make sure you have an [EGI Check-in account](https://docs.egi.eu/users/check-in/signup).
* Using your EGI Check-in account, request access to the `vo.access.egi.eu` Virtual Organisation
  [using this link](https://aai.egi.eu/auth/realms/id/account/#/enroll?groupPath=/vo.access.egi.eu).
  In the `reason to join` field, please specify `Access to test tool-registry in EOSC Data Commons`.

Once your EGI Check-in account has been created and you have been granted access to the `vo.access.egi.eu` VO:

1. Go to [EGI Notebooks](https://notebooks.egi.eu/). First time you would need to create an EGI Check-in account
2. In `Git` choose `Clone a Repository` and enter `https://github.com/EOSC-Data-Commons/publish-tool-examples.git`
3. Navigate on the left-side panel to the cloned folder
4. Click on the notebook you want to run, for example `publish-simple-tool-example.ipynb`.
5. Follow the instructions in the notebook to publish your tool to the `tools-registry`.
