##TESS Light Curves!

Today was very productive. I recreated Figure 7 on page 11 of the Leiner paper. Went smoothly, just adding a color bar to my existing data.
<img width="1000" height="500" alt="figure 7 recreation" src="https://github.com/user-attachments/assets/a8020391-1f06-42ab-9a7d-cb273a080f2a" />
Next, I started playing with light curve data from TESS. This involved setting up lightkurve to access the data. Then in order to find the stars that have 2 min SPOC data I sifted through every star and created a list: 
Found SPOC 2-min: TIC 135085696 (1 sectors)
Found SPOC 2-min: TIC 112077128 (1 sectors)
Found SPOC 2-min: TIC 158066720 (1 sectors)
Found SPOC 2-min: TIC 139993838 (3 sectors)
Found SPOC 2-min: TIC 258781000 (2 sectors)
Found SPOC 2-min: TIC 188542320 (1 sectors)
So those are the stars that actually have the 2-minute SPOC data already done. 6/448
I also ran into the issue that 11 of the stars didn't have a TIC ID
GaiaID 2745853857410858496 — no TIC ID
GaiaID 239593139997785856 — no TIC ID
GaiaID 556446380800482944 — no TIC ID
GaiaID 1683510704814985856 — no TIC ID
GaiaID 3941285677002856576 — no TIC ID
GaiaID 1513099356131773312 — no TIC ID
GaiaID 4600918058678258304 — no TIC ID
GaiaID 4535031782898946944 — no TIC ID
GaiaID 6909188171089910912 — no TIC ID
GaiaID 6463546350186454144 — no TIC ID
GaiaID 1983128413664609792 — no TIC ID
So then I played around with getting the light curve from each of the 6 ones with SPOC 2-min data and got these






<img width="848" height="400" alt="258781000 SAP and PDCSAP" src="https://github.com/user-attachments/assets/e39a4874-b56b-431a-b613-b56e4792f5fa" />
<img width="848" height="400" alt="188542320 SAD AND PDCSAP" src="https://github.com/user-attachments/assets/e16e28c2-4968-49b8-b2f9-c8e9b22d48a6" />
<img width="848" height="400" alt="158066720 SAP and PDCSAP" src="https://github.com/user-attachments/assets/e3912372-79ed-4c84-a8da-432ea7702383" />
<img width="848" height="400" alt="112077128 SAP and PDCSAP" src="https://github.com/user-attachments/assets/0e294b98-fe55-4ad6-98d3-98af03fcf363" />

Compared to the sample in the tutorial

<img width="2364" height="1101" alt="Sample SAD AND PDCSAP" src="https://github.com/user-attachments/assets/19d16547-541a-4e20-8b16-c700cfb1875d" />

Then I did a little more processing on one of them


<img width="848" height="400" alt="flattened 158066720" src="https://github.com/user-attachments/assets/5244862d-30e7-4b1e-9122-12f5fb15714f" />
<img width="848" height="400" alt="folded 158066720" src="https://github.com/user-attachments/assets/ab755a8f-5cf1-4b20-aaa3-b1ff9f3977d9" />
<img width="848" height="400" alt="binned 158066720" src="https://github.com/user-attachments/assets/bfc2e591-1b0d-4173-9de9-3d5eeec0f46a" />

My overall reflection is that the sample doesn't look very similar, but I am wondering if that is because their example is a relatively inactive star, because they are looking for transiting exoplanets, whereas we are looking at very active stars with lots of sunspots rotating very fast. That is my thought on why they may be so different. I am feeling like I am doing things but without a great understanding as to why for everystep so I am excited to talk about this more tomorrow. One next step I have identified is learning how to extract a light curve from the FITs data.
