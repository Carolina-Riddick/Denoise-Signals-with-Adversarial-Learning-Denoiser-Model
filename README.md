## Denoise-Signals-with-Adversarial-Learning-Denoiser-Model
## SignalDenoiser

This example shows how to denoise noisy signals using an adversarial learning denoiser model [1]. The model is wrapped as an object that can be trained with any data set of real 1-D signals. After training, the object is ready to denoise test signals that have similar characteristics as those in the training set. 
This example shows the efficacy of the model on noisy electrocardiogram (ECG) and electroencephalogram (EEG) signals. Denoising these types of signals is a challenging problem because they are nonstationary and have spectral content of interest that overlaps with the noise spectrum. 
In the example, after you denoise the signals using the adversarial learning model, you compare the results to those of a conventional wavelet denoising technique and of an LSTM network denoiser model.

This is a simple example

<img width="1536" height="1024" alt="DenoiseRepresentation" src="https://github.com/user-attachments/assets/be977e61-acfb-417e-af21-5371d5f16c0b" />
