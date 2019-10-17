This is (was) an attempt to create a standalone html page of the RaDMaX webapp using [nbinteract](https://www.nbinteract.com/). Under the hood nbinteract uses nbviewer for the html conversion and mybinder to host a jupyter server and update the widgets.
For some reason it doesn't ssem to work. Not sure if this comes from:
	- mybinder failing to build the image when using a requirements.txt file (as imposed by nbinteract), whereas it works fine with an environment.yml file. More speifically the issue arises when trying to install the xrayutilities package via pip (requirements.txt), whereas it works with conda (environment.yml)
	- compatibility issue with bqplot ?
