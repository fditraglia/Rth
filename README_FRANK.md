Here are the instructions for installing Rth on my work machine. From the home directory, do:

`R CMD build Rth`

Then do:

`R CMD INSTALL Rth_0.1-0.tar.gz --configure-args="with-backend=CUDA" --preclean`

where the preclean is only needed if you've already build it once.
