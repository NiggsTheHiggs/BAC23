# BAC23
Bachelor's thesis repository

This repository contains the files necessary for recreating the simulations performed in the bachelor's thesis. The Latex-file associated with the document as well as figures and other items can also be found here.

## Simulations
In order to run the simulations, an Openlab account is needed. This can be created on live.openlive.app. 
Before simulations can start, a configuration is needed. This configuration represents the well and formation to be used in the simulations. Elements such as length of the well, drilling fluid used, and the possibility of incidents can be adjusted, in adition to much more. The specific settings used for the simulations in the thesis can be viewed in part B of the Appendix in the thesis.

In order to run simulations through Python, the program must be installed on the computer, a configuration must be set up, and a valid user account created. The Openlab package must then be installed, details about the installation as well as the files can be found on the tutorials page on the Openlab page: https://openlab.app/tutorial/new-install-and-authenticate-python/.

Once the package is installed, simulations can be run through the "DEVsketch.py" file. Here, the users credentials are entered in order to connect to the Openlab client. The name of the configuration, as well as depth and the name of the simulation must also be put in here. Kp- and Ki-values are entered below. Launching the script should then start a simulation in Openlab.

Performing the flow sweep tests requires much of the same approach. Using Python, the "sweep.py"-file is opened. Once opened, user credentials are put in the required fields. The name of the configuration, as well as simulation name and depth is also filled in. Launching the script should start a flow sweep test in Openlab simulating roughly 15 minutes of pressure variations.
