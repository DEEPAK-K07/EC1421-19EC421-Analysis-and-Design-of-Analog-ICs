# EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
# DESIGN OF ACTIVE LOW PASS,HIGH PASS AND BAND PASS FILTERS USING OP-AMP 

## AIM: 

To design and obtain the frequency response of 
i) First order Low Pass Filter (LPF) 
ii) First order High Pass Filter (HPF) 
iii) Band pass filter
 
## APPARATUS REQUIRED

<img width="625" height="170" alt="image" src="https://github.com/user-attachments/assets/900fc8b3-3a8c-4208-bf52-98cc9e281e21" />

## THEORY
## LOW PASS FILTER 
 A LPF allows frequencies from 0 to higher cut of frequency, fH.  At fH the gain is 0.707 
Amax, and after fH gain decreases at a constant rate with an increase in frequency.  The gain 
decreases 20dB each time the frequency is increased by 10.  Hence the rate at which the gain 
rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in 
frequency.  The frequency f=fH is called the cut off frequency because the gain of the filter at this 
frequency is down by 3 dB from 0 Hz.  Other equivalent terms for cut-off frequency are -3dB 
frequency, break frequency, or corner frequency.
# HIGH PASS FILTER 
The frequency at which the magnitude of the gain is 0.707 times the maximum value of 
gain is called low cut off frequency.  Obviously, all frequencies higher than fL are pass band 
frequencies with the highest frequency determined by the closed –loop band width all of the op
amp. 
# BAND PASS FILTER 
A band pass filter has a pass band between two cutoff frequencies fH and fL such that fH > 
fL.  Any input frequency outside this pass band is attenuated.  There are two types of band-pass 
filters.  Wide band pass and Narrow band pass filters.  We can define a filter as wide band pass if 
its quality factor Q <10.  If Q>10, then we call the filter a narrow band pass filter.  A wide band 
pass filter can be formed by simply cascading high-pass and low-pass sections.  The order of 
band pass filter depends on the order of high pass and low pass sections.

## CIRCUIT DIAGRAM: 

## LOW_PASS

![WhatsApp Image 2025-12-02 at 13 21 07_386b3dec](https://github.com/user-attachments/assets/ff6c4aff-af92-4ee3-986d-d8e86b0fc039)


## HIGH-PASS

![WhatsApp Image 2025-12-02 at 13 21 07_3a3b448a](https://github.com/user-attachments/assets/378a02fd-86ac-49d6-8ad8-0fe8cf52f612)

## BAND-PASS

![WhatsApp Image 2025-12-02 at 13 21 07_25b95a2c](https://github.com/user-attachments/assets/c5486a68-71fa-40bb-ad56-f292afe49a7e)

## MODEL GRAPH:

## LOW_PASS

![WhatsApp Image 2025-12-02 at 13 21 08_32d1a694](https://github.com/user-attachments/assets/7f3052a1-3305-4282-8dcf-ce99fc4d4154)


## HIGH-PASS

![WhatsApp Image 2025-12-02 at 13 21 08_1b462e87](https://github.com/user-attachments/assets/8b3cffab-cb46-45a7-832e-1e33b6acc8d1)


## BAND-PASS

![WhatsApp Image 2025-12-02 at 13 22 40_fae2d0a6](https://github.com/user-attachments/assets/513d76c7-1506-4ebb-bf75-ea7303b19ac8)

## PROCEDURE - (LPF & HPF): 
1. Connect the circuit as shown in the circuit diagram. 
2. Select the corresponding cut-off frequency (higher or lower) and determine the value of C&R. 
select the value of R1 & Rf depending on desired passband gain Af.. 
3. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
4. Tabulate the output voltage Vo with respect to different values of input frequency. 
5. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to  get approximately the same characteristic as shown in the model graph. 
# PROCEDURE:BAND PASS FILTER 
1. Select the lower and higher cut-off frequency and calculate the value of R & C for the given 
frequencies. 
2. Design for LPF & HPF separately and then combine the circuit by first placing the HPF 
followed by a LPF (i.e) HPF in series with LPF. 
3. Connect the circuit as shown in the circuit diagram. 
4. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
5. Tabulate the output voltage Vo with respect to different values of input frequency. 
6. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to get approximately the same characteristic as shown in the model graph

## DESIGN:LPF & HPF:

<img width="429" height="324" alt="image" src="https://github.com/user-attachments/assets/b0f0ac0a-3006-494c-9096-e91ae2d6e87c" />

# DESIGN: BAND PASS FILTER
Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.  
1. Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency 
of HPF as fL = 1 KHz.  
2. Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf.  
Let C = 0.1μf.  
3. Calculate R from the expression.  
Given: fH = 2KHz  = 1/ (2πR1C1) 
   Let C1 = 0.1 µF, R1 = 7.9 KΩ 
Given: fL = 400Hz  = 1/ (2πR2C2) 
   Let C2 = 0.1 µF, R2 = 39.8 KΩ 
  Pass band Gain=4 
   Now   Ao = 1 + (Rf / R1)  
               2-1=(Rf / Ri) 
                Ri = Rf 
                 Let  Ri = Rf = 10 KΩ

## TABULATION:

## LOW_PASS

![WhatsApp Image 2025-12-02 at 13 24 48_e00f72c2](https://github.com/user-attachments/assets/54cb91ab-8b5a-4faa-a909-e6aaf4ead9ad)


## HIGH-PASS

![WhatsApp Image 2025-12-02 at 13 24 48_c77a6bf0](https://github.com/user-attachments/assets/27efa3b0-5fd3-4445-9de0-41b1652a25f7)


## BAND-PASS

![WhatsApp Image 2025-12-02 at 13 24 48_bbef4348](https://github.com/user-attachments/assets/02be9164-4deb-4ac2-897c-5c264d209a57)


## GRAPH:

## LOW_PASS

![WhatsApp Image 2025-12-02 at 13 27 09_4746713d](https://github.com/user-attachments/assets/57d59225-13db-4de5-be49-a76ff837a8cb)


## HIGH-PASS

![WhatsApp Image 2025-12-02 at 13 25 41_3d458d60](https://github.com/user-attachments/assets/337b0c7b-9ba8-4f46-989b-1dc659b37d00)


## BAND-PASS

![WhatsApp Image 2025-12-02 at 13 25 41_eba11af5](https://github.com/user-attachments/assets/d2721793-48d6-4400-8547-48c649d74928)

## RESULTS:
Thus an Active Low pass, High pass and Band Pass Filters are designed and 
tested using op-amp IC 741. 

