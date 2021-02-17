# Visualization of in-vitro Blood Vessels in Contrast Images Based on Discrete Wavelet Transform Decomposition 

This repository has the functions to implement the methods described in the conference article: 
[*"Visualization of in-vitro Blood Vessels in Contrast Images Based on Discrete Wavelet Transform Decomposition"*](https://ieeexplore.ieee.org/document/8827144), developed as part of the project *"Visualization and localization of blood vessels"* at [INAOE](https://www.inaoep.mx). 

## Abstract 

Visualization of blood vessels in speckle images is an important task as it is used to analyze the dynamics of the blood flow and the health status of biological tissue. However, this task becomes difficult due to the noise in the image, mainly at high depths. This work proposes a methodology based on the Discrete Wavelet Transform to improve *in-vitro* blood vessels visualization.

[[Paper]](https://ieeexplore.ieee.org/document/8827144)
[[Poster]](https://www.researchgate.net/publication/333146308_Visualization_of_in-vitro_Blood_Vessels_in_Contrast_Images_Based_on_Discrete_Wavelet_Transform_Decomposition)



## Contents

* [`f_i2mtc2019.m`](https://github.com/friscolt/i2mtc-2019/blob/master/f_i2mtc2019.m) -  Matlab script. The script  `f_i2mtc2019.m` contains 1 main function (`f_i2mtc2019`) and four auxiliary functions (`f_sk`, `f_denoising`, `f_binarize`, `f_mapping`) to implement the methods described in [this paper](https://ieeexplore.ieee.org/document/8827144). 

* [`data.mat`](https://github.com/friscolt/i2mtc-2019/blob/master/data.mat) - MAT file. It contains an *in-vitro* speckle image of a bifurcated blood vessel at a depth of 300 µm. The image is stored as a variable with the name 'img' and is an array of 288x280 pixels in grayscale. 

* [`demo.mlx`](https://github.com/friscolt/i2mtc-2019/blob/master/main.mlx) - Matlab live script. It contains an example of the image processing available in [`data.mat`](https://github.com/friscolt/i2mtc-2019/blob/master/data.mat). This live script describes step by step the use of the auxiliary functions described in [`f_i2mtc2019.m`](https://github.com/friscolt/i2mtc-2019/blob/master/f_i2mtc2019.m) 

## Organization

No additional content directories are declared. 


## Contributors

Code for algorithms, applications and tools contributed by:

F. Lopez-Tiro, H. Peregrina-Barreto, J. Rangel-Magdaleno, J. C. Ramirez-San-Juan

Please email us your comments, criticism, and questions at [`francisco.lopez@inaoe.mx`](mailto:francisco.lopez@inaoe.com?subject=[GitHub]%20i2mtc2019%20repository)

## Reference

If you use functions from this script in your work, please use the BibTex entry below for citation.

[[Paper]](https://ieeexplore.ieee.org/document/8827144)

```
@INPROCEEDINGS{8827144,
    author={F. {Lopez-Tiro} and H. {Peregrina-Barreto} and J. {Rangel-Magdaleno} and J. C. {Ramirez-San-Juan}},
    booktitle={2019 IEEE International Instrumentation and Measurement Technology Conference (I2MTC)}, 
    title={Visualization of in-vitro Blood Vessels in Contrast Images Based on Discrete Wavelet Transform Decomposition}, 
    year={2019},
    volume={},
    number={},
    pages={1-6},
    doi={10.1109/I2MTC.2019.8827144}}
```
