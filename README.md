# EXPERIMENT-2-OPTICAL-COMMUNICATION
## 🔍 EX.NO: 2 – Verification of Fiber Losses

**Aim:**  
To measure propagation and bending losses for two wavelengths in plastic fiber.

**Equipments Required:**  
- Link-B Kit  
- Patch chords  
- Oscilloscope  
- Function Generator  
- Fiber cables  

**Theory:**  
- Optical Fibers are available in different variety of materials. These materials are usually selected by
taking into account their absorption characteristics for different wavelengths of light. In case of Optical
Fiber, since the signal is transmitted in the form of light which is completely different in nature as that
of electrons, one has to consider the interaction of matter the radiation to study the losses in fiber.
Losses are introduced in fiber due to various reasons. As light propagates from one end of Fiber to another
end, part of it is absorbed in the material exhibiting absorption loss. Also part of the light is reflected back
or in some other directions from the impurity particles present in the material contributing to the loss of
the signal at the other end of the Fiber. In general terms it is know as propagation loss. Plastic Fibers have
higher loss of the order of 180 dB/Km.
Whenever the condition for angel of incidence of the incident lights is violated the losses are introduced
due to refraction of light. This occurs when fiber is subjected to bending. Lower the radius of curvature
more is the loss. Other losses are due to the coupling of Fiber at LED and photo detector ends.

-  Connect the power supply with proper polarity to the kit link-B and switch it on.
-  Keep all Switch Faults in OFF position.
-  Keep switch SW8 towards TX position.
-  Keep switch SW9 towards TX1 position.
-  Keep Jumper JP5 towards +12V position.
-  Keep Jumpers JP6, JP9, JP10 shorted.
-  Keep Jumper JP8 towards sine position.
-  Keep Intensity control pot P2 towards minimum position.
-  Feed about 2Vpp sinusoidal signal of 1 KHz from the function generator to the IN post of Analog
Buffer.

<img width="292" height="120" alt="image" src="https://github.com/user-attachments/assets/156edcbd-98a2-498c-8df6-0fc5ba689699" />

- Connect the output post OUT of Analog Buffer to the post TX IN of Transmitter.
- Slightly unscrew the cap of SFH756V (660nm). Do not remove the cap from the connector. Once the cap is loosened, insert the one meter fiber into the cap. Now tighten the cap by screwing it back.
- Connect the other end of the Fiber to detector SFH350V (Photo Transistor Detector) very carefully.
- Observe the detected signal at post ANALOG OUT on oscilloscope. Adjust Intensity control pot P2.Optical Power control potentiometer so that you receive signal of 2Vpp amplitude.

- Measure the peak value of the received signal at ANALOG OUT terminal. Let this value be V1.
- Now replace 1 meter Fiber by 3 Meter Fiber. Do not disturb any settings. Again take the peak voltage reading and let it be V2.
<img width="270" height="121" alt="image" src="https://github.com/user-attachments/assets/b8318160-e66c-486d-ba8a-da1d285c9d5b" />

-  If a is the attenuation of the Fiber then we have. P1/P2 = V1/V2 = e [ -a (L1+L2 ) ]
Where
a = nepers/ Meter
L1 = Fiber Length for V1 L2 = Fiber Length for V2
This a is for peak wavelength of 660nm
-  Keep switch SW9 towards TX2 position.
- Keep Jumper JP7 towards +12V position.
- Remove fiber cable from SFH756V (660nm) & SFH350V and insert one meter fiber between SFH450V (950nm) & SFH350V.
- Observe the detected signal at post ANALOG OUT on oscilloscope

<img width="323" height="140" alt="image" src="https://github.com/user-attachments/assets/9083ec0a-7439-458b-bb69-4181696c37c5" />

- Measure the peak value of the received signal at ANALOG OUT terminal. Let this value be V1.
- Now replace 1 meter Fiber by 3 Meter Fiber. Do not disturb any settings. Again take the peak voltage reading and let it be V2.
- If a is the attenuation of the Fiber then we have. P1/P2 = V1/V2 = e [ -a (L1+L2 ) ]
Where
a = nepers/ Meter
L1 = Fiber Length for V1 ; L2 = Fiber Length for V2
This a is for peak wavelength of 950nm
- Compare the two a values.

MEASUREMENT OF BENDING LOSSES:
- Remove fiber cable from SFH450V (950nm) & SFH350V and insert one meter fiber between
SFH756V (660nm) & SFH350V.
- Bend the Fiber in a loop. Measure the amplitude of the received signal.
- Keep reducing the diameter of bend to about 2 cm & take corresponding out voltage readings. (Do
not reduce loop diameter less than 1 cm).
- Plot a graph of the received signal amplitude versus the loop diameter

**Diagram:**

<img width="934" height="489" alt="image" src="https://github.com/user-attachments/assets/e1aa3104-ce1a-4b4b-b257-49a58e6035f4" />

**Procedure:**  

- Refer to the block diagram and make the following connections.
- Keep all switch faults in OFF position.
- Slightly unscrew the cap of LED SFH756V (660nm). Do not remove the cap from the connector.
Once the cap is loosened, insert the 1-meter fiber into the cap. Now tighten the cap by screwing it
back.
- Slightly unscrew the cap of Photo Diode SFH250V. Do not remove the cap from the connector.
Once the cap is loosened, insert the other end of fiber into the cap. Now tighten the cap by
screwing it back.
- Keep the jumpers JP1 short for +12v, JP2 towards sine wave, JP3 short for
+12 v & JP4 towards TX1on FCL-01.
- Keep switch SW2 in VI position on FCL-01.
- Connect voltmeter and current meter as per the polarities shown in the block diagram.
- Switch on the power supply.
- Keep the potentiometer P3 in its maximum position (anti-clockwise rotation). P3 is used to control
current flowing through the LED.
- Keep the potentiometer P4 in its fully clockwise rotation.P4 is used to control bias voltage of the
LED.
- To get the IV characteristics of LED, rotate P3 slowly and measure forward current and
corresponding forward voltage. Take number of such readings for various current values and plot
IV characteristics graph for the LED.
- For each reading taken above, find out the power, which is product of I and
V. This is the electrical power supplied to the LED. Data sheets for the LED specify optical power coupled into
plastic fiber when forward current was 10 mA as 200 mW. This means that the electrical power at 10 mA
current is converted into 200 mW of optical energy. Hence the efficiency of the LED comes out to be approx.
1.15%.
- With this efficiency assumed, find out optical power coupled into plastic optical fiber for each of
- Similarly measure the current at the detector.
- Plot the graph of receiver current v/s output optical power of the LED.
- Perform the above procedure again for all the combinations of Transmitter & Receiver.  
the reading. Plot the graph of forward current v/s output optical power of the LED.

**Tabulation:**

### Propagation Loss
<img width="1280" height="475" alt="image" src="https://github.com/user-attachments/assets/faf6d99c-eb14-4e23-a8d8-0a0fcee8261c" />


### Bending Loss

<img width="1280" height="503" alt="image" src="https://github.com/user-attachments/assets/c93c263e-3095-43a0-b313-6bbff1e8d6b7" />


**Result:**  
Attenuation and bending loss characteristics verified.

---
