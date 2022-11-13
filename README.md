## Physics informed machine learning for AEM forward modeling

Code for 4 machine learning techniques is available (in the corresponding folders):
- Simple auto-encoder
- Auto-encoder combined with Fourier transform
- CNN
- CNN combined with RNN
- basic code for CNN + auto-encoder combined with Fourier transform

Each folder contains a general code for the technique (_gen) and an example code (without transformations, removal of large angles, optimization, etc. and therefore not very good models) in the AEM context (_ex).
The data used in the example codes is also available (Data_used_ex).
For CNN, there is also a basic optimization code available (_opt), here each parameter is optimized individually, improvement might be found if the optimization is performed simultaneously for all parameters, however a low-RAM usage code should be written for this.
The code for CNN + auto-encoder combined with Fourier transform is still very basic and needs improvement.
