Today I ran into quite a few snags. My main goal of the day was to work in the previously sawtooth TGLC data into my workflow. The first snag that I ran into was that when processing the sawtooths McKenzie and Aidan used different naming conventions. 
I was then able to generate the graphs I needed. However, the snag I ran into here was that it was over flagging flares as seen below:
<img width="3600" height="1500" alt="image" src="https://github.com/user-attachments/assets/89024e87-7206-4733-ad25-78def637cf02" />

<img width="3600" height="1500" alt="image" src="https://github.com/user-attachments/assets/e51e5b62-d41a-44f2-a08c-fa43bd0435d2" />

I discovered that the reason for this was because the excel sheet that was generated in the TGLC process only has Time and Flux, no Flux Error. Which essentially means any deviation is essentially flagged as a flare. So then I had to essentially find a way to get flux error from what I have. I used MAD again on the already detrended data. This seemed to work much better. As seen below: 
<img width="3600" height="1500" alt="image" src="https://github.com/user-attachments/assets/a2e0f4f0-9cf2-446e-af59-73ad21602b1a" />

<img width="3600" height="1500" alt="image" src="https://github.com/user-attachments/assets/539f574e-2b7c-4bd2-9d4c-570e6a63c389" />


My next steps is:
1. I am going to do is pull together my sampler pack of all of the types of Light curves I want to be able to analyze. I really want to look at more sawtooth curves to make sure my methods still pick up flares. So my categories are Sawtooth fixed with TGLC, large flares, eclipsing binaries, big noise regions, noise before and after downlink.
	2. From there I want to tweak any parameters I still need to in order to make every light curve look as good as possible.
	3. Write down every parameter/decision I made to do this cleaning
OVERALL, I think with some slight tweaking and documentation my flare detection code is ready to run on the whole sample!
