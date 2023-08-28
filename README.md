# Generate SSH Keys on [Commjhub](https://commjhub.asc.upenn.edu/) for GitHub 🚀🔑⚡

Etienne P Jacquot - [etienne.jacquot@asc.upenn.edu](mailto:etienne.jacquot@asc.upenn.edu)
_________

## Getting Started

Please run the following in a blank notebook on [Commjhub](https://commjhub.asc.upenn.edu/):

### Clone this repo

``` python
%%bash
git clone https://github.com/atnjqt/ssh-keygen-jhub
```

### Run the notebook

Proceed to run the configurations python cells in the included [ssh-keygen.ipynb](./ssh-keygen.ipynb) notebook

- Be sure to set for *your specific configurations*!


### Confirms your connectivity to Github!

```python
%%bash
ssh -T git@github.com
```

> 🧐 *Note: This example python notebook is for generating SSH keys to then use via the Git Extension with SSH remote origins (though you can use HTTPs remote origins with a [Personal Access Key](https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token). ASC Commjhub uses JupyterLab with the Git Extension, configured via ssh key*)
__________