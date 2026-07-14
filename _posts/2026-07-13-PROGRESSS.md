I had a super successful day. I was struggling because the graphs were close, but just not good enough. My code was cutting out some of the modulation, and there was noise that was just not getting cut out. The first thing I did was make a function I was running a running MAD instead of comparing to the global mean which solved the issue of the bottom being cut off. And then I had a huge huge breakthrough. I had thought we had used quality masks, but I guess not. Anyways, I followed the quality masks done by Seli Et al in "Stellar flare morphology with TESS across the main sequence"
<img width="1617" height="861" alt="image" src="https://github.com/user-attachments/assets/e187bf24-ab0f-4c3a-a8ee-abfb2219bdd6" />

Quote from the paper:
"This bitmask includes the following quality flags (Twicken et al. 2020): Attitude tweak, Safe mode, Coarse point, Earth point, Argabrightening, Desaturation event, Manual exclude, Discontinuity corrected, Straylight and Straylight2. We did not use the following quality flags, as they would sometimes remove real flare peaks, as also noted by Feinstein et al. (2020b): Impulsive outlier, Cosmic ray in collateral data, Cosmic ray in optimal aperture."
This improved my graphs SO much. Below is an example of a complex one.
<img width="3600" height="1500" alt="image" src="https://github.com/user-attachments/assets/8d5cc65f-1816-4457-b411-b60ade55df44" />
<img width="2544" height="1200" alt="image" src="https://github.com/user-attachments/assets/49c82ec9-de6c-489b-9137-c297c04b220d" />

Below here is an example of one that just wasn't working the way I wanted it to before the quality mask and then was after the quality mask was used.

<img width="2544" height="1200" alt="image" src="https://github.com/user-attachments/assets/6cd11fa7-2063-4d20-8ae3-649188113e53" />
<img width="3600" height="1500" alt="image" src="https://github.com/user-attachments/assets/c32d8da6-aeba-4a48-be6e-a6bf04a8c960" />

<img width="3600" height="1500" alt="image" src="https://github.com/user-attachments/assets/b6780a3b-c337-45d3-9a57-539e21009c18" />

I also finished putting together my catalog of the whole variety of subtyped I wanted to focus on! So huge huge progress today, feels like a big break through!



