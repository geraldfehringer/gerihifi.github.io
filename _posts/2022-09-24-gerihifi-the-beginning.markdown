---
layout: post
title:  "ADC - Digital dream or epic flaw?"
date:   2022-09-22 01:00:01
categories: hifi start dac
tags: featured
image: /assets/article_images/2022-09-24-gerihifi-the-beginning/dac1.png
---

>**_"Brain needs noise."_** \
>&nbsp; &nbsp; **_"Without noise, it's artificial!"_** \
>&nbsp; &nbsp; &nbsp; _"...welcome to the world of digital."_

**My journey with ADC or is it D/A :thinking:** .

20+Y, I got rid of my large CD collection. I was never the Vinyl-guy and a big CD-chaser, before as many of us, I'd recorded anything what came closely to music on casette-deck (previously used by my C64 datassette).... you can assume, I'm not from the Z-Generation, more on the side of _'**I-AM-OLDER-THAN-THE-INTERNET**'_ :speak_no_evil:

Than I'd a long pause and started with more serious, dedicated listening HiFi gear again in 2009 (concerning my budget I'd back than). Of course, far away from getting crazy and bought the usual consumer speakers, solid state integrated amp and cheap digital streamer (who cares about digital source, right, it's just streaming, buffering & bit-shifting 00111000). Of course, as a computer nerd, played around with several different DIY audio servers. This has changed on 2019 and especially in 2021, when I changed my complete HiFi chain to the next maturity-level.

>>**:notes: Milestone #1: Choosing the right DAC, needs some basic architecture knowledge!**

>**Bit's are not bits in the audio world! WHY? We do need voltages for analogue and therefore digital 00001111 (binary code) must be converted into 5V range.**

[^1] While analogue signals can be continuous and provide an infinite number different voltage values, digital circuits on the other hand work with binary signal which have only two discrete states, a logic "1" (HIGH) or a logic "0" (LOW). [^2] Most observations are coming from the **great mentoring by Janos from [Real World Audio](/videos/)!**

So it is necessary to have an electronic circuit which can convert between the two different domains of continuously changing analogue signals and discrete digital signals, and this is where Analogue-to-Digital Converters (A/D) come in.

![]({{ "/assets/article_images/2022-09-24-gerihifi-the-beginning/adc-voltage.png" | prepend: site.baseurl }} "input-output tolerances")

As you see in the picture, there are several 'nuances/blur', because there are much more voltage values and  can't be mapped directly to 0 (low, leakage like 14bit/1mV 16bit/300uV or 24bit/3uV) or 1 (high, means 50% blur), as you may think! Therefore we always have some kind of 'noise/leakage' in digital which is added - **no DAC vendor is publishing this**. So even there you can imagine some 'manipulation' is added and **there is not 100% perfect conversation!** Therefore you will see a lot of different design approaches to address this issue, but can't be removed! So know I understood why power-supply is so important in DAC as well and implementation design. Therefore some clever ideas went into newer DAC designs in the past 3 years, to improve that and to move conversations into non-audible range.

**WHAT kind of [DAC-Designs](https://samplerateconverter.com/educational/r2r-ladder-dac-vs-sigma-delta) are available?**

| DAC Type | Format | Notes |
| :--- | :--- | :--- |
| R2R Ladder - NOS | complex design, non-oversampling PCM | |
| R2R Ladder | complex design, oversampling PCM (filters) | |
| Sigma-Delta PCM | Single-bit or multi-bit, simpler design | |
| DSD | Single-bit | complex design, initially introduced by SACD, can be native edited without interm. conversation |

---

>>**:notes: Milestone #2: Understand the processes involved in recoding audio tracks!**

There are so many processes in place, you can imagine, the master engineer is taking care of the source record and we all rely on his expertise and what kind of tooling he is using. The picture below shows the high-levels steps involved.

![]({{ "/assets/article_images/2022-09-24-gerihifi-the-beginning/recording.png" | prepend: site.baseurl }} "recording staging")

**As always: shit in, shit out!** - so test several recordings and **yes, different file formats make a difference** as well,  non-hires WAV, WMA or OGG or hires like FLAC,MQA or DSD. **Also test CD versus good streaming services, like Qobuz or Tidal - also try out downloading tracks to local disc/offline**.

---

>>**:notes: Milestone #3: Realizing, digital source for sure matters!**


[^1]: Source: [electronics-tutorials.ws](https://www.electronics-tutorials.ws/combination/analogue-to-digital-converter.html)