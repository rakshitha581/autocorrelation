# autocorrelation
**AIM**
   Write a program for Autocorrelation and psd of signals in scilab and verify Weiner-khinchin relation

****APPARATUS REQUIRED:**
      . computer with i3 processor
      . scilab
      
**Theorey:**
 The Wiener-Khinchin theorem states that the power spectral density of a wide sense stationary random process is the Fourier transform of the corresponding autocorrelation function.

**Agorithm:**
1.  The Wiener-Khinchin theorem states that the power spectral density of a wide sense stationary random process is the Fourier transform of the corresponding autocorrelation function.
2.	Compute Autocorrelation: Calculate the autocorrelation 
3.	Plot Results: Visualize the autocorrelation function and PSD.

**PROCEDURE**
•	Refer Algorithms and write code for the experiment.
•	Open SCILAB in System
•	Type your code in New Editor
•	Save the file
•	Type your code in New Editor
•	Save the file

**PRPGRAM:**
```
t=0:0.01:2*pi;
x=sin(2*t);
subplot(3,2,1);
plot(x);
au=xcorr(x,x);
Subplot(3,2,2);
plot(au);
v=fft(au);
subplot(3,2,3);
plot(abs(v));
fw=fft(x);
subplot(3,2,4);
plot(fw);
```

**GRAPH:**
<img width="801" height="460" alt="image" src="https://github.com/user-attachments/assets/99edc4a8-faaa-4a8d-9b67-866d541738c8" />

**OUTPUT:**
![WhatsApp Image 2025-11-26 at 12 18 14_83328f39](https://github.com/user-attachments/assets/e83b3337-b4d2-4ace-a350-e6c24ffb6327)

****RESULT**
Thus the Autocorrelation and PSD are executed in Scilab and output is verified.
