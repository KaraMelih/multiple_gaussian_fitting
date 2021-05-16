# Multiple Gaussian Fitting

The [notebook](Simultanoues_fitting.ipynb) demonstrates a method to fit arbitrary number of gaussians to a given dataset. <br> One of the key points in fitting is setting the initial guess parameters, in this case, the initial guesses are estimated automatically by using `scipy.signal.find_peaks_cwt` function. <br>
The code does a good job to a first approximation and is only meant for quick and efficient multiple gaussian fitting simultaneously.
