# SSPI-remove-unwated-texture
Project for SSPI at Master TAID
Remove unwanted texture from photos 
Steps:
1. Open image in OpenCV
2. Use FFT and FFTSHIFT in order to get the magnitude spectrum
3. Modify the result of 2. to get rid of high frequencies(except the DC component from the center of the magnitude)
4. Use IFFTSHIFT and IFFT to get back to grayscale image
5. Show original and modified image
