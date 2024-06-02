# Signal-Filtering-and-Denoising-MATLAB- 
I made this app using MATLAB's app designer. It basically takes an input file from the user and outputs a file that has the noise removed from it. 
It does this by first finding the Discrete Fourier Transform (DFT) of the signal using the Fast Fourier Transform formula. 
It then calculates the Power Spectral Density (PSD) and displays it to the user. Using this, our user can indentify the frequency he wants to eliminate. 
The user can then eliminate this frequency using our Filter Input Field, then it filters out all frequencies lower than the inputted frequency 
Now we can perform an Inverse FFT to get our ouput signal without the noise, which the user can save 
