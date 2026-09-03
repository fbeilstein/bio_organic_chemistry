
:::titlepage
[[title]]
Sound
[[subcaption]]
A Bit of Physics
:::

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

![](./lecture_14_hearing/images/slide_3_img_1.png) {left=21.00 top=33.58 width=20.48 height=32.83}

![](./lecture_14_hearing/images/slide_3_img_2.png) {left=48.99 top=31.66 width=29.46 height=32.83}

<div style="position: absolute; left: 14.93%; top: 1.98%; width: 46.49%; height: 35.01%;">

**Sound** is a vibration that propagates as an acoustic wave through a transmission medium such as a gas, liquid or solid. Sound is transmitted through gases, plasma, and liquids as longitudinal waves, also called **compression waves**. Through solids, however, it can be transmitted as both longitudinal waves and transverse waves

</div>

![](./lecture_14_hearing/images/slide_3_img_3.png) {left=61.88 top=5.87 width=34.97 height=20.72}

<div style="position: absolute; left: 15.81%; top: 70.66%; width: 79.61%; height: 10.77%;">

Sound that is perceptible by humans has frequencies from about 20 Hz to 20,000 Hz (wavelengths 17 m - 17 mm).

</div>

<div style="position: absolute; left: 83.33%; top: 36.99%; width: 16.33%; height: 14.37%;">

Density changes 
exaggerated for
“regular sounds”

</div>

<div style="position: absolute; left: 84.91%; top: 51.95%; width: 14.23%; height: 17.95%;">

3 orders of magnitude !
(compare to light perception)

</div>

![](./lecture_14_hearing/images/slide_3_img_4.png) {left=62.29 top=83.63 width=34.50 height=9.33}

![](./lecture_14_hearing/images/slide_3_img_5.png) {left=21.00 top=85.50 width=31.18 height=7.00}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

![youtube](px3oVGXr4mo) {left=19.03 top=11.58 width=76.83 height=76.83}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 16.07%; top: 3.81%; width: 80.35%; height: 16.51%;">

**Not Sound (Blast Wave)**

</div>

![youtube](http://www.youtube.com/watch?v=2llGTUvjEgI&t=5) {left=16.67 top=18.23 width=80.35 height=80.35}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 16.57%; top: 1.66%; width: 79.96%; height: 17.95%;">

The waveforms of the most sounds have a more complex shape than a sine wave; nevertheless, as proved by Joseph Fourier, all such waveforms can be decomposed into a collection of sine waves with various frequencies and amplitudes (called the frequency components of the complex wave) by applying a mathematical procedure now known as **Fourier analysis**.

</div>

![](./lecture_14_hearing/images/slide_6_img_6.png) {left=20.66 top=48.82 width=38.90 height=49.47}

![](./lecture_14_hearing/images/slide_6_img_7.png) {left=69.44 top=23.33 width=28.42 height=73.25}

<div style="position: absolute; left: 16.19%; top: 21.09%; width: 52.38%; height: 28.73%;">

Periodic sounds (like musical notes) could be decomposed into **fundamental frequency (pitch) **and** overtones **(frequencies that are multiples of the pitch). Two complex sounds that have the same pitch and the same loudness but that don’t sound the same are said to differ in **timbre **mainly due to differences in the relative amplitudes of the various overtones.

</div>

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 16.06%; top: 3.87%; width: 80.47%; height: 28.73%;">

A **spectrogram **(usually depicted as a heat map) is a visual representation of the spectrum of frequencies of a signal as it varies with time. When applied to an audio signal, spectrograms are sometimes called **sonograms**.
Digitally sampled data, in the time domain, is broken up into chunks, which usually overlap, and **Fourier transformed** to calculate the magnitude of the frequency spectrum for each chunk. Each chunk then corresponds to a vertical line in the image; a measurement of magnitude versus frequency for a specific moment in time (the midpoint of the chunk).

</div>

![](./lecture_14_hearing/images/slide_7_img_8.png) {left=18.68 top=37.00 width=39.11 height=53.64}

<div style="position: absolute; left: 22.50%; top: 91.61%; width: 32.81%; height: 7.18%;">

Spectrogram of dolphin vocalizations

</div>

![](./lecture_14_hearing/images/slide_7_img_9.png) {left=58.82 top=38.95 width=38.87 height=39.70}

<div style="position: absolute; left: 66.50%; top: 89.97%; width: 27.04%; height: 7.03%;">

3D surface spectrogram.

</div>

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

![](./lecture_14_hearing/images/slide_8_img_10.png) {left=64.93 top=3.72 width=30.46 height=55.45}

<div style="position: absolute; left: 15.88%; top: 2.45%; width: 50.60%; height: 71.82%;">

But what happens if only the fundamental frequency is removed, without removing any of the other harmonics? The surprising result is that, although there is a difference in the sound quality, the pitch of the sound seems to be the same as before, even though the fundamental frequency, which determines the pitch of a complex periodic sound, is not actually present! This is called the** illusion of the missing fundamental**. It shows that the auditory system uses the pattern of frequencies in a sound’s harmonics as part of the perception of pitch. 

One practical application of our susceptibility to this illusion is the production of audio recordings that sound like they contain very low frequency sounds even when played through speakers that are incapable of emitting sounds at such low frequencies. For example, a complex sound made up of three pure tones with frequencies of 160 Hz, 240 Hz, and 320 Hz will be perceived as having a low pitch corresponding to a frequency of 80 Hz (the missing fundamental) even if played through a speaker incapable of emitting sounds with frequencies of less than 100 Hz.

</div>

<div style="position: absolute; left: 16.54%; top: 77.86%; width: 49.29%; height: 21.55%;">

Vogler, an 18th-century organist, applied this to create the illusion of deep bass notes on a portable organ by playing only the higher harmonics, allowing smaller pipes to sound like much larger ones, fooling listeners into hearing the low fundamental frequency.

</div>

![](./lecture_14_hearing/images/slide_8_img_11.png) {left=69.86 top=60.07 width=23.47 height=37.84}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 15.98%; top: 2.81%; width: 78.23%; height: 15.26%;">

For ordinary conditions (near STP, ordinary temperatures and frequencies) treating air as an **ideal gas** is an excellent approximation for calculating the speed of sound. The sound process is assumed **adiabatic **(no heat exchange during compression).

</div>

![](./lecture_14_hearing/images/slide_9_img_12.png) {left=56.64 top=47.80 width=41.11 height=28.46}

![](./lecture_14_hearing/images/slide_9_img_13.png) {left=17.01 top=46.89 width=35.95 height=40.10}

<div style="position: absolute; left: 56.64%; top: 80.52%; width: 41.11%; height: 17.95%;">

**Even at painful, nearly damaging sound levels, the density of air changes by 1%.**

**Human hearing is very sensitive!**

</div>

![](./lecture_14_hearing/images/slide_9_img_14.png) {left=16.63 top=22.56 width=36.71 height=12.61}

![](./lecture_14_hearing/images/slide_9_img_15.png) {left=56.64 top=18.65 width=42.89 height=20.44}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

![](./lecture_14_hearing/images/slide_10_img_16.png) {left=30.38 top=20.95 width=23.46 height=8.44}

<div style="position: absolute; left: 14.42%; top: 7.61%; width: 54.59%; height: 10.77%;">

The speed of sound in meters per second can be estimated using the formula, where *T**C* is the temperature in degrees Celsius.

</div>

![](./lecture_14_hearing/images/slide_10_img_17.png) {left=69.56 top=4.86 width=26.06 height=48.38}

![](./lecture_14_hearing/images/slide_10_img_18.png) {left=23.91 top=31.69 width=33.38 height=18.31}

<div style="position: absolute; left: 16.65%; top: 58.70%; width: 79.52%; height: 21.55%;">

The speed of sound is **faster **in** humid air** than in dry air because water vapor molecules are lighter than the nitrogen and oxygen molecules they replace, which makes the humid air less dense. This lower density allows sound waves to travel more quickly, with the speed increasing by about 0.1% to 0.6% at room temperature for a 100% change in humidity. For example, at *20**o**C*, the speed of sound is approximately *343 m/s* in dry air, but *346 m/s* in very humid air.

</div>

<div style="position: absolute; left: 71.05%; top: 82.51%; width: 25.12%; height: 16.16%;">

<u>Speed of sound calculator</u> (The National Physical Laboratory (NPL)   )

</div>

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

![youtube](FvvSIAqOkIw) {left=16.65 top=47.70 width=42.69 height=42.69}

<div style="position: absolute; left: 16.65%; top: 1.28%; width: 46.55%; height: 10.77%;">

The resonant frequency of a resonator:

</div>

![](./lecture_14_hearing/images/slide_11_img_19.png) {left=17.73 top=24.19 width=36.52 height=12.02}

![](./lecture_14_hearing/images/slide_11_img_20.png) {left=17.73 top=8.97 width=11.33 height=5.41}

![](./lecture_14_hearing/images/slide_11_img_21.png) {left=17.29 top=15.23 width=35.76 height=9.62}

![](./lecture_14_hearing/images/slide_11_img_22.png) {left=68.67 top=1.28 width=27.39 height=10.77}

![](./lecture_14_hearing/images/slide_11_img_23.png) {left=51.20 top=2.57 width=7.56 height=8.18}

![](./lecture_14_hearing/images/slide_11_img_24.png) {left=61.00 top=15.01 width=37.33 height=46.27}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 16.05%; top: 51.38%; width: 82.31%; height: 21.55%;">

*I**0**** ***- auditory threshold approximately the quietest sound a young human with undamaged hearing can detect at 1 kHz. Note though that the threshold of hearing is frequency-dependent and it has been shown that the ear's sensitivity is best at frequencies between 2 kHz and 5 kHz. The proper notations for sound intensity level using this reference are LI /(1 pW/m2) or LI(re 1 pW/m2), but the notations dB SIL, dB(SIL), dBSIL, or dBSIL are very common.

</div>

![](./lecture_14_hearing/images/slide_12_img_25.png) {left=37.50 top=45.51 width=19.88 height=4.71}

<div style="position: absolute; left: 15.22%; top: 21.06%; width: 81.24%; height: 10.77%;">

**Sound intensity level (SIL)** or **acoustic intensity level** is the level (a logarithmic quantity expressed *nepers, bels, or decibels*) of the intensity of a sound relative to a reference value.

</div>

<div style="position: absolute; left: 15.22%; top: 5.23%; width: 79.66%; height: 14.37%;">

**Sound intensity (**acoustic intensity, sound power density and the sound energy flux density) is a power carried by sound waves per unit area in a direction perpendicular to that area, also called the sound power density and the sound energy flux density measured in watt per square meter (W/m2).

</div>

![](./lecture_14_hearing/images/slide_12_img_26.png) {left=34.85 top=33.17 width=42.66 height=10.95}

![](./lecture_14_hearing/images/slide_12_img_27.png) {left=35.87 top=78.69 width=42.66 height=16.91}

<div style="position: absolute; left: 16.01%; top: 71.51%; width: 62.88%; height: 7.18%;">

Acoustic intensity is proportional to acoustic pressure (effective) squared.

</div>

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 14.70%; top: 2.27%; width: 82.77%; height: 10.77%;">

**Sound pressure level (SPL) **or **acoustic pressure level (APL) **is a logarithmic measure of the effective pressure of a sound relative to a reference value.

</div>

![](./lecture_14_hearing/images/slide_13_img_28.png) {left=34.22 top=25.29 width=11.80 height=5.14}

![](./lecture_14_hearing/images/slide_13_img_29.png) {left=34.22 top=14.27 width=47.49 height=9.41}

<div style="position: absolute; left: 15.71%; top: 32.58%; width: 62.25%; height: 7.18%;">

*p**RMS **-* *root-mean-square pressure (effective pressure)*.

</div>

<div style="position: absolute; left: 15.71%; top: 63.95%; width: 42.98%; height: 17.95%;">

The proper notations for sound pressure level using this reference are Lp/(20 μPa) or  Lp(re 20 μPa), but the suffix notations dB SPL, dB(SPL), dBSPL, and dBSPL are very common.

</div>

![](./lecture_14_hearing/images/slide_13_img_30.png) {left=58.23 top=33.90 width=40.75 height=63.31}

![](./lecture_14_hearing/images/slide_13_img_31.png) {left=28.55 top=44.54 width=20.39 height=14.63}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 15.46%; top: 4.08%; width: 81.06%; height: 17.95%;">

As sound waves spread out from a point source, their energy is distributed over a larger and larger area (the surface of an expanding sphere). The area of a sphere is proportional to the square of its radius *r**2*, so the intensity of the sound, which is power per unit area, is inversely proportional to the square of the distance *I~1/r**2*.

</div>

<div style="position: absolute; left: 16.31%; top: 24.47%; width: 79.70%; height: 10.77%;">

This means that if you double the distance from a sound source, the sound intensity becomes one-fourth as strong. In terms of sound pressure level (SPL), **doubling the distance results in a 6 dB drop**.

</div>

![](./lecture_14_hearing/images/slide_14_img_32.png) {left=23.75 top=37.68 width=61.73 height=54.21}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

![](./lecture_14_hearing/images/slide_15_img_33.png) {left=56.23 top=13.44 width=9.79 height=24.62}

<div style="position: absolute; left: 15.54%; top: 0.00%; width: 80.84%; height: 14.37%;">

A **sound level meter (**sound pressure level meter**) **- diaphragm of the microphone responds to changes in air pressure caused by sound waves converting the sound pressure (Pa), is converted into an electrical signal (V).

</div>

![](./lecture_14_hearing/images/slide_15_img_34.png) {left=20.52 top=13.02 width=24.77 height=25.46}

<div style="position: absolute; left: 17.76%; top: 39.54%; width: 37.43%; height: 14.37%;">

Type 2203 (1962) - arguably the first portable sound measurement device (weight 5kg, although the level recorder was another 25 kg)

</div>

![](./lecture_14_hearing/images/slide_15_img_35.png) {left=68.09 top=12.64 width=13.74 height=26.22}

<div style="position: absolute; left: 66.02%; top: 39.54%; width: 19.44%; height: 14.37%;">

Most sound level measuring apps are not very accurate

</div>

![](./lecture_14_hearing/images/slide_15_img_36.png) {left=19.06 top=55.91 width=38.66 height=43.11}

![](./lecture_14_hearing/images/slide_15_img_37.png) {left=58.81 top=53.91 width=39.26 height=32.09}

<div style="position: absolute; left: 59.32%; top: 87.04%; width: 38.36%; height: 10.77%;">

* according to *The National Institute for Occupational Safety and Health (NIOSH)*

</div>

![](./lecture_14_hearing/images/slide_15_img_38.png) {left=82.64 top=10.70 width=13.74 height=32.45}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 15.36%; top: 1.01%; width: 83.32%; height: 10.77%;">

**The loudest sound that has ever been measured by humanity - explosion during 1883 eruption of Krakatoa.**

</div>

<div style="position: absolute; left: 14.87%; top: 13.37%; width: 60.94%; height: 64.64%;">

Between 20 May and 21 October 1883, the volcanic island of Krakatau, located in the Sunda Strait (Indonesia), erupted. On 27 August, the island had its most significant eruption, which destroyed over 70% of the island and its surrounding archipelago and left 36,000 people dead.

An explosion was so powerful that it was heard 3,110 km away in Perth, Western Australia, and the Indian Ocean island of Rodrigues 4,800 km away, where the blast was thought to have been cannon fire from a nearby ship. The pressure wave was recorded on barographs worldwide. The wave rounded the globe three and a half times. It was so powerful that the sound it produced ruptured the eardrums of sailors on RMS Norham Castle which was hove to off Sumatra roughly 64 km away. At Jakarta 160 km away, the air waves burst windows and cracked walls.

</div>

![](./lecture_14_hearing/images/slide_16_img_39.png) {left=76.31 top=12.51 width=19.37 height=46.95}

<div style="position: absolute; left: 14.87%; top: 65.24%; width: 81.22%; height: 46.68%;">

The loudness of the blast heard **160 km** from the volcano has been calculated to have been **180 dBSPL**. Some claim that this corresponds to 310 dBSPL at the epicenter but sound pressure level (SPL) in air has a theoretical limit: around **191 dB** (SPL) at sea level (it corresponds to respective pressure amplitude equal to atmospheric pressure). At or above this, the rarefaction phase of the wave would drop pressure to zero (vacuum), so you don’t get a “normal” sound wave — you instead get a shock wave / blast wave (a pressure wave) rather than a sustained sound.  So “310 dB” claim likely reflects a misunderstanding or misapplication of decibel scales — mixing regular sound pressure (SPL) with a shock-wave overpressure (which is a different physical regime).

</div>

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 17.95%; top: 4.67%; width: 80.79%; height: 10.77%;">

The **phon **is a logarithmic unit of **loudness **level, that is equal to the sound pressure level (in dB SPL) of a 1 kHz pure tone that is *judged *as having the same loudness.

</div>

<div style="position: absolute; left: 65.94%; top: 20.44%; width: 32.81%; height: 46.68%;">

**An equal-loudness contour **is a measure of sound pressure level, over the frequency spectrum, for which a listener perceives a constant loudness when presented with pure steady tones.

**The Fletcher–Munson curves** are one of many sets of equal-loudness contours for the human ear, determined experimentally by Harvey Fletcher and Wilden A. Munson, and reported in a 1933.

</div>

![](./lecture_14_hearing/images/slide_17_img_40.png) {left=15.56 top=19.91 width=48.29 height=78.63}

<div style="position: absolute; left: 65.94%; top: 70.13%; width: 32.21%; height: 17.95%;">

If you listen to a music with vocals, bases and high pitch instruments and you lower the volume, the vocals will  become relatively more audible.

</div>

<div style="position: absolute; left: 40.36%; top: 16.45%; width: 6.87%; height: 6.28%;">

speech

</div>

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 16.06%; top: 2.90%; width: 84.56%; height: 17.95%;">

Audiologists test people’s hearing with an instrument called an **audiometer**, which presents pure tones with known frequency and amplitude to the right or left ear using high quality headphones, when the person is in a quiet environment. In effect, the audiologist uses the staircase method to estimate the person’s absolute threshold for each of six to eight frequencies, ranging from 250 to 8,000 Hz.

</div>

<div style="position: absolute; left: 16.06%; top: 22.25%; width: 80.74%; height: 25.14%;">

The result of such a test is an **audiogram**, a graphical depiction of auditory sensitivity (expressed as hearing level) compared to that of a standard listener at each of the tested frequencies for each ear. By convention, the hearing level is measured relative to the audibility curve of the standard listener; so the standard listener would have a hearing level of 0 dB SPL at every frequency. If the listener can detect the tone only if it’s 50 dB louder than the level required by the standard listener, then the person is said to have a 50 dB hearing loss in the tested ear at 4,000 Hz (as in the impaired left ear in Figure).

</div>

![](./lecture_14_hearing/images/slide_18_img_41.png) {left=17.27 top=46.29 width=35.23 height=49.74}

![](./lecture_14_hearing/images/slide_18_img_42.png) {left=56.45 top=53.06 width=34.65 height=41.26}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

![](./lecture_14_hearing/images/slide_19_img_43.png) {left=39.90 top=15.06 width=58.95 height=59.81}

![](./lecture_14_hearing/images/slide_19_img_44.png) {left=62.09 top=76.85 width=12.86 height=19.48}

<div style="position: absolute; left: 77.37%; top: 74.86%; width: 21.48%; height: 25.14%;">

The first "dog whistle" (1876) invented by sir Francis Galton (Galton board, regression toward the mean) for cat/dog training.

</div>

![](./lecture_14_hearing/images/slide_19_img_45.png) {left=33.85 top=72.01 width=5.56 height=27.21}

<div style="position: absolute; left: 18.95%; top: 89.69%; width: 36.88%; height: 10.77%;">

A dog ultrasonic whistle (silent whistle / Galton's whistle)

</div>

![](./lecture_14_hearing/images/slide_19_img_46.png) {left=56.32 top=1.56 width=27.59 height=11.52}

<div style="position: absolute; left: 18.67%; top: 17.25%; width: 19.21%; height: 33.51%;">

Many insects (moths, beetles) have good ultrasonic hearing, and most of these are nocturnal insects listening for echolocating bats. Upon hearing a bat, some insects will make evasive manoeuvres to escape being caught.

</div>

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

![](./lecture_14_hearing/images/slide_20_img_47.png) {left=17.50 top=6.74 width=21.46 height=25.94}

![](./lecture_14_hearing/images/slide_20_img_48.png) {left=40.77 top=6.74 width=18.85 height=24.75}

<div style="position: absolute; left: 39.84%; top: 36.40%; width: 32.81%; height: 14.37%;">

Obstetric ultrasonography 
(prenatal ultrasound)
2-10 MHz

</div>

<div style="position: absolute; left: 17.87%; top: 35.68%; width: 19.60%; height: 10.77%;">

Echolocation (bats)
20 kHz – 120 kHz

</div>

![](./lecture_14_hearing/images/slide_20_img_49.png) {left=61.43 top=5.45 width=36.70 height=28.52}

<div style="position: absolute; left: 68.80%; top: 36.40%; width: 18.85%; height: 10.77%;">

Echolocation (whales)
20 kHz – 150 kHz

</div>

<div style="position: absolute; left: 19.65%; top: 88.48%; width: 27.65%; height: 10.77%;">

Whale communication (100 km)
10 Hz - 31 kHz

</div>

![](./lecture_14_hearing/images/slide_20_img_50.png) {left=18.29 top=52.09 width=30.00 height=30.45}

![](./lecture_14_hearing/images/slide_20_img_51.png) {left=63.88 top=51.83 width=24.65 height=31.99}

<div style="position: absolute; left: 62.16%; top: 88.48%; width: 32.81%; height: 10.77%;">

Elephant communication (10 km)
15 Hz - 35 Hz.

</div>

</div>

