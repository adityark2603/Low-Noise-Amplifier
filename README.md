# Low-Noise-Amplifier
A Low Noise Amplifier designed using Cadence Virtuoso tool

A Low Noise Amplifier (LNA) is an electronic amplifier designed to amplify very weak signals (usually in the RF/microwave range) without adding significant noise. It is typically the first stage in a receiver chain (like in radios, satellite, or radar systems).

![image](https://github.com/user-attachments/assets/971298ff-c2ad-4cdd-9639-2b5b3cf83df5)

## Applications of LNA:
1. Wireless communication systems (WiFi, 5G, Bluetooth)
2. Satellite receivers
3. Radar systems
4. Radio telescopes
5. IoT and sensor-based systems

## Working Principle
When a signal is received by an antenna, it's often very weak—sometimes just a few microvolts. Before this signal can be processed (filtered, demodulated, or digitized), it needs to be amplified without degrading the quality. The LNA performs this task by providing:

1. High gain: Boosts the amplitude of the incoming signal.
2. Low noise figure (NF): Ensures minimal noise is added during amplification.
3. Input/output matching: Matches impedance with the antenna and following circuits to minimize reflection losses.


## Specific Values I used for making this LNA:
1. PORT 0 (INPUT SIDE): R = 50 ohms, Frequency 1 = 2.4GHz, Source Type = sine
2. PORT 1 (OUTPUT SIDE): R = 50 ohms, Source Type = sine
3. C0 = 1n F, C1 = 10p F, C2 = 345f F, C3 = 680f F
4. L0 = 200p H, L1 = 32.5n H, L2 = 1n H, 5 ohms
5. R0 = 50k ohms
6. V0 = 600mV, V1 = 1.2 v
7. NMOS (gpdk 90nm):

   (I) length = 100n M
   (II) total width = 60u M
   
   (III) finger width = 6u 
   
   (IV) threshold = 120n M

