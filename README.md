# IntGaussMax
This function fit gaussian on optical emission spectras and yields the emission line intensity

you need to provided it a list of the line you want to fit, if thoses lines are doublet or triplet and the spectra.
ex:
E = [750.39 751.47 866.79]
Doublet = [1 1 0]
lambda = [] vector or wavelength (nm)
Int = [] vector of associated intensity at those wavelengths

GraphAll = 1 yield a figure of all the fit on each lines.

<img width="551" alt="screen shot 2018-08-11 at 1 54 41 pm" src="https://user-images.githubusercontent.com/33142211/43994663-d7829a2e-9d6e-11e8-88c2-6243d283da4e.png">

As we can see on the next figure, even small emission line are well fitted.
