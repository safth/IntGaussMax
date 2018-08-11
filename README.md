# IntGaussMax
This function fit gaussian on optical emission spectra and yields emission line intensities

you need to provided it a list of the emission line you want to fit, if thoses lines are doublet or triplet and the spectra.

ex:<br />
E = [750.39 751.47 866.79]<br />
Doublet = [1 1 0]<br />
lambda = [...] vector or wavelength (nm)<br />
Int = [...] vector of associated intensity at those wavelengths<br />

[I_exp,sig_I_exp,Fit] = IntensiteGaussMax_TRG(E,lambda,Int,Doublet,GraphAll=0,GraphExp = 0);

I_exp is a vector of the intensity fitted <br />
sig_I_exp is a vector of the uncerntainty on each fit <br />
Fit is a vector of boul that give a value of 0 if the function was not able to fit a line


GraphAll = 1 yield a figure of all the fit on each lines.

<img width="551" alt="screen shot 2018-08-11 at 1 54 41 pm" src="https://user-images.githubusercontent.com/33142211/43994663-d7829a2e-9d6e-11e8-88c2-6243d283da4e.png">

As we can see on the next figure, even small emission line are well fitted.

<img width="545" alt="screen shot 2018-08-11 at 1 55 48 pm" src="https://user-images.githubusercontent.com/33142211/43994710-abe27212-9d6f-11e8-8635-ec72b9aa1c8a.png">


The next figure gives an exemple of the variable GraphExp. if GraphExp=1, every fit is display on a figure. This give an exemple of a doublet where 2 gaussian are fitted

<img width="536" alt="screen shot 2018-08-11 at 1 57 18 pm" src="https://user-images.githubusercontent.com/33142211/43994711-ae1c9d96-9d6f-11e8-9874-c8c07950e5aa.png">
