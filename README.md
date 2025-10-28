# Pion-resonance-analysis
Jupyter Notebook for analysing pion resonance data using Python, SciPy curve fitting, and simulation.

This Jupyter Notebook analyses experimental data of pion scattering to estimate the resonance width (w) of a particle.

Overview:
This notebook unpacks and processes data files including:
- Energy Values (p_e)
- Number of pions (p_n)
- Error in number of pions (p_err)

I illustrated this data alongside a theoretical curve and then carried out a comparison using a discrepancy function.

Methods:
- Data loading and arranging with NumPy
- Plotting with Matplotlib
- Curve fitting and returning optimal values using SciPy's curve_fit
- Simulation based estimation of resonance width
- Using a gaussian distribution to compute values and their respective uncertainties

Results:
The notebook shows:
- A plot of experimental data vs theoretical curve
- Best-fit from the model
- Estimated resonance width with uncertainty
- A histogram plot of frequency vs ensemble values of w

  
