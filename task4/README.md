# Task 4

Here we will be looking at experimental data from the CLAS detector at JLAB. We will be looking at is an electron scattering experiment with a beam energy of 4.8 GeV, along the Z axis, on a liquid hydrogen (proton) target.
![reaction](reaction.png)

The csv file has the information from the scattered electron stored in 4 banks. The momentum is stored in "p" and the cosine of the angle from the beam line is gives in the x, y, and z are given by the "cx", "cy", and "cz" banks respectively. Therefore to get the momentum of the electron in the x direction, Px = P * Cx.

In this section, we will look at calculating W and Q^2 values from the scattered electrons.

# TO DO:
Download data from:[here](http://boson.physics.sc.edu/~nick/electron-scattering-data.html)

 - [1] Practice how you can create 4-vector and use the methods in class LorentzVector using given 4-vectors (Fill in the blanks).
 - [2] Practice by creating your own 4-vector and use all the methods in class LorentzVector, print all of your method's outputs.
 - [3] Create a 4 vector for the Electron beam, e_mu.
 - [4] Create a 4 vector for the Proton target, p_mu.
 - [5] Create a 4 vector for the scattered Electron beam, e_mu_prime.
 - [6] Make 1-d histograms for P, Px, Py, Pz, Energy and 2-d hist for P vs Energy using 4 vector e_mu in the given 6 subplots
 - [7] Calculate q_mu, W Q2 and plot 1-d W and Q^2 and W vs Q^2  histograms.
