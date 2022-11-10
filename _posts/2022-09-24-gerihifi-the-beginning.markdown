---
layout: post
title:  "ADC - Digital dream or epic flaw - PT.1?"
date:   2022-09-22 01:00:01
categories: hifi start dac
image: /assets/article_images/2022-09-24-gerihifi-the-beginning/dac1.png
---

>**_"Brain needs noise."_** \
>&nbsp; &nbsp; **_"Without noise, it's artificial!"_** \
>&nbsp; &nbsp; &nbsp; _...welcome to the world of digital._

`LANGUAGE:` `English`

**My journey with ADC or is it D/A :thinking:**

**PART 1.**

20+Y, I got rid of my large CD collection. I was never the Vinyl-guy and a big CD-chaser, before as many of us, I'd recorded anything what came closely to music on casette-deck (previously used by my C64 datassette).... you can assume, I'm not from the Z-Generation, more on the side of _'**I-AM-OLDER-THAN-THE-INTERNET**'_ :speak_no_evil:

Than I'd a long pause and started with more serious, dedicated listening HiFi gear again in 2009 (concerning my budget I'd back than). Of course, far away from getting crazy and bought the usual consumer speakers, solid state integrated amp and cheap digital streamer (who cares about digital source, right, it's just streaming, buffering & bit-shifting 00111000). Of course, as a computer nerd, played around with several different DIY audio servers. This has changed on 2019 and especially in 2021, when I changed my complete HiFi chain to the next maturity-level.

>>**:notes: Milestone #1: Choosing the right DAC, needs some basic architecture knowledge!**

>**Bit's are not bits in the audio world! WHY? We do need voltages for analogue and therefore digital 00001111 (binary code) must be converted into voltage.**

[^1] While analogue signals can be continuous and provide an infinite number different voltage values, digital circuits on the other hand work with binary signal which have only two discrete states, a logic "1" (HIGH) or a logic "0" (LOW). [^2] Most observations are coming from the **great mentoring by Janos from [Real World Audio](/videos/)!**

So it is necessary to have an electronic circuit which can convert between the two different domains of continuously changing analogue signals and discrete digital signals, and this is where Analogue-to-Digital Converters (A/D) come in.

![]({{ "/assets/article_images/2022-09-24-gerihifi-the-beginning/adc-voltage.png" | prepend: site.baseurl }} "input-output tolerances")

As you see in the picture, there are several 'nuances/blur', because there are much more voltage values and  can't be mapped directly to 0 (low, leakage like 14bit/1mV 16bit/300uV or 24bit/3uV) or 1 (high, means 50% blur), as you may think! Therefore we always have some kind of 'noise/leakage' in digital which is added - **no DAC vendor is publishing this**. So even there you can imagine some 'manipulation' is added and **there is not 100% perfect conversation!** Therefore you will see a lot of different design approaches to address this issue, but can't be removed!

So now I understood why DAC power-supplies are so important as well implementation design. Also some clever ideas went into newer DAC designs in the past 3 years (of course chips have improved as well!) - to move conversations into non-audible range.

**WHAT kind of [DAC-Designs](https://samplerateconverter.com/educational/r2r-ladder-dac-vs-sigma-delta) are available?**

| DAC Type | Format | Notes |
| :--- | :--- | :--- |
| R2R Ladder - NOS | Complex design, non-oversampling PCM | Very popular, even it is an old design approach. Used by Denafrips or HoloAudio and many others. |
| R2R Ladder | Complex design, oversampling PCM (filters) | Also many vendors available  |
| Sigma-Delta PCM | Single-bit or multi-bit, simpler design | Long tradition and many High End vendors still using that approach, like Weiss, Audio Note or Lampizator  |
| DSD | Single-bit | Simpler design (e.g. FPGA) | initially introduced by SACD, can be native edited without interm. conversation |

The very High-end DAC vendors, like MSB, dCS, Playback Design, Nagra, Chord or Mola Mola show the latest techniques.

**Others like Lampizator, Nagra or Audio Note use tubes for the input / output stages and not just FPGA-fanciness and filtering all over the place.**

On the other hand, there are traditional designers who have a different approach and to integrate vintage-based components, as well focusing on well-balanced tube integrations. Like [Abbas Audio](https://www.abbasaudio.com/), [SW1x](https://sw1xad.co.uk/) or [Audio Note](https://www.audionote.co.uk/dacs).


**Are there any difference?**

- YES, massive difference if you have a good HiFi chain (doesn't mean expensive!!) with sensitive speakers
- R2R & Tube-based DAC's, many time not so 'harsh' and 'analytical'. Of course High-End vendors like Playback Design or MSB, dCS do quiet some perfection on their filtering.
- There are definitely price ranges where you get some improvement, like <€5k / <€10k / <€25k
- Do you really get anything audible 'better' over €25k - **I personally would say: NO, it's just a matter of brand/reputation you wanna own**. Much more you can archive with Pre-AMP/AMP/Interconnects/Power supplies/Absorbers and most important: **room acoustic treatments**!
- **Never, ever trust DAC-reviews or at usual HiFi store listening rooms - **your need to test them in your chain, in your room & environment!**
- New DAC needs burn-in time, don't underestimate & how much it can change after 100h+!

---

>>**:notes: Milestone #2: Understand the processes involved in recoding audio tracks!**

There are so many processes in place, you can imagine, the master engineer is taking care of the source record and we all rely on his expertise and what kind of tooling he is using. The picture below shows the high-levels steps involved.

![]({{ "/assets/article_images/2022-09-24-gerihifi-the-beginning/recording.png" | prepend: site.baseurl }} "recording staging")

**As always: shit in, shit out!** - so test several recordings and **yes, different file formats make a difference** as well,  non-hires WAV, WMA or OGG or hires like FLAC, MQA or DSD.

**Also test CD versus good streaming services, like Qobuz or Tidal - also try out downloading tracks to local disc/offline. You will hear differences!**.

---

>>**:notes: Milestone #3: Realizing, digital source for sure matters!**

Yes, you can for sure start with simple streamer/bridge, like [HifiBerry](https://www.hifiberry.com/) or Bluesound [Node](https://bluesound-deutschland.de/products/node/), but once you have a good DAC, you should have a matching (all about synergy) Streamer or also called streaming bridge.

**Important note:** of course, if you go into the really expensive DAC-ranges, many of those vendors do have streaming bridge in one device or offer 'matching' devices. My personal experience has shown, to separate this two functions it will improve sonics.

This is another topic which you need to carefully think about, because it can get quiet expensive, if you wanna really get on the top-levels, like Antipodes [Oladra](https://antipodes.audio/oladra/) / K50, Taiko [Audio Extreme](https://taikoaudio.com/taiko-2020/product/extreme-high-end-music-server/) or Grimm [Audio MU1](https://www.grimmaudio.com/hifi-products/music-players/mu1/).

**I personally don't like and need Roon, Audirvana or HQPlayer - I prefer a simple and straight forward network bridge.** I use at the moment an Lumin Mini U2 and replaced the internal PSU with an external [Ferrum Hypsos](https://ferrum.audio/hypsos/). 

It is always important to mention, there are many time some serious difference using SPDIF/AES-EBU/USB or Coaxial RCA (don't use TOSLINK!). So play around with high-quality cables (yes, this is another topic I'll share my personal experience ;-)

---

>>**:notes: My current setup (29/10/2022)**:

Rotel Michi X5 --XLR--> WEISS DAC 501 (upgraded model: MkII-4ch/ESS9038-PRO) <--S/PDIF-- Lumin Mini U2 (with Ferrum Hypsos PSU) <--LAN-- Paul Pang Dual-OXCO

Rotel Michi X5--RCA-->Pioneer PD-93 CD with BurrBrown PCM63 DAC


![]({{ "/assets/article_images/2022-09-24-gerihifi-the-beginning/20221029_142019.jpg" | prepend: site.baseurl }} "gerihifi chain")

---

[^1]: Source: [electronics-tutorials.ws](https://www.electronics-tutorials.ws/combination/analogue-to-digital-converter.html)