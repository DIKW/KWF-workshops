# KWF-workshops
Voor datascience workshops bij KWF

## Howto setup the python environment

Goto extracted folder

Create virtual environment with conda

    conda create --name kwfworkshop

Source this environment

    conda activate kwfworkshop

(optionally) Add relevant libraries from the requirements.txt file if it exists in the repo

    pip3 install -r requirements.txt

## Install jupyter lab

We gebruiken dit commando om in onze nieuwe conda omgeving jupyter lab op te tuigen

    conda install -c conda-forge jupyterlab

Start de lab omgeving in de directory met 

    jupyter lab

## Extensions

Er zijn een aantal handige extensies beschikbaar in jupyter.
We gebruiken RISE voor slides.

And we need github integration

    conda install -c conda-forge jupyterlab jupyterlab-git

