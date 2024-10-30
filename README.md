# Galaxy-VAE
The application of variational autoencoders to galactic spectra. 

Spectroscopy has provided the foundation for our modern understanding of galaxy formation and
evolution. Deep, wide-field spectroscopic and imaging surveys are presenting us
with vast amounts of new data on the evolution of galaxies. Upcoming surveys will provide orders of magnitude more data than any
previous survey. With classical techniques becoming insufficient to handle this data, it is clear that
we have a need to expand our analysis tool kit. For this expansion we turn towards unsupervised machine learning, where insights can be drawn from data with no pre-existing labels.

We use a variational autoencoder (VAE) to create compressed representations of galaxy spectra. These spectra were synthetically generated using the Flexible Stellar Population Synthesis package (see Conroy et al. 2009 and Conroy and Gunn 2010) and have a number of physical parameters associated with them. However, the model never sees these parameters during training. What we are interested in is whether the model can learn notions of these parameters in the latent representations by just looking at the spectra.

Here, I share the code that was used to do this. I'm no computer scientist, so the code is at times sloppy. I hope that it can inspire more people to explore the application of VAEs to scientific discovery. A full discussion of the results for a previous training of the model, as well as a full reference list, can be found in the accompanying report. This work was carried out as part of my master's degree in astrophysics at the University of Cambridge.
