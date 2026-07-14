# PyLadies workshop at EuroPython 2026

## Create your own musical instrument with custom gesture control

This repository contains code used to implement a standalone desktop application with a web UI that embeds an existing machine learning model for timbre transfer. It also uses interactive machine learning to train custom gestural control for sound generation, a method popularised by [Rebecca Fiebrink](https://researchers.arts.ac.uk/1594-rebecca-fiebrink) through [Wekinator](http://www.wekinator.org/).

This workshop aims to explain the steps leading to the creation of [Style Transfer Demo App](https://github.com/aniawsz/style-transfer-demo).

The workshop materials are based on a collaborative effort by [Dynamic Cast](https://github.com/dynamic-cast) in preparation for a workshop at Audio Developer Conference in 2024.

### About the app

This app loads a [RAVE](https://github.com/acids-ircam/RAVE) model and enables navigating its latent space with controls.

### Running the app

* Download one of the RAVE models from [here](https://acids-ircam.github.io/rave_models_download).
This app is tested with Darbouka_onnx
* Set the path to the model in `instance/application.cfg`
* Install the dependencies:
`pip install -r requirements.txt`
* Run the app:
`flask run`

In order to run the app in debug mode, run:
`flask run --debug`
