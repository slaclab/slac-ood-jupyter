# Jupyter OnDemand Batch Connect for Jupyter at SLAC

This contains the deployment the OnDemand Jupyter that is used at SLAC.

# Features

Allows invocation of custom jupyterlab or jupyter notebook instance. One just needs to have either a local (i.e. files at SLAC), singularity container with the jupyter binary within its PATH, or an installed and activate-able conda environment with the jupyter bins installed.

We also accept pull requests to get common (ie shared) jupyter instances added to the drop down menu for users to quickly launch their jupyter environments. Please send pull requests with mods to the form.yml.erb.
