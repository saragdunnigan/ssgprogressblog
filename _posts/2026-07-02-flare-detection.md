Today's work was super satisfying, and I feel like I made a lot of progress. I have finished making a setup for running flare detection!! Essentially, it grabs the light curve, flattens it, runs flare detection, and then creates a graph and appends the data into two CSV files, which I can look at in Excel. So far I have just run the first ten TIC numbers to see if it works and it seems to be working so far. I have two spreadsheets one collects what I have testing and keeps track of everything including the ones with 0 flares and errors. The other just keeps track of the flare data. Alas everytime I open the excel spreadsheet it puts the tic numbers into scientific notation lol, even if I change the settings it reverts.
<img width="1314" height="1347" alt="image" src="https://github.com/user-attachments/assets/83bbbe0c-be40-4d29-8c12-7c6b69fffdd8" />
<img width="1524" height="1506" alt="image" src="https://github.com/user-attachments/assets/b4e6ffa6-a2fb-455e-817e-7fcfc8b1ccd7" />

I have also been graphing them just as like a sanity check for verification that it is doing what I think it is. From this I think I maybe wanna tweak the settings a little bit more, I want it to pick up a couple more flares I think.Below is an example where I think it might have missed some flares. 
<img width="3777" height="1560" alt="image" src="https://github.com/user-attachments/assets/fa78c3e1-3844-4944-8bb7-ca3940975a23" />

I also want to mask something like super out of flare possibility such as the graph below
<img width="3819" height="1563" alt="image" src="https://github.com/user-attachments/assets/9158a0ab-96c2-4560-827c-8c47d3de4393" />

Overall I think this is working but I want to fine tune it so it does exaclty what I want it to and to make it easier to work with. Tran and song did a lot of flare exclusion after detection and after getting their synthetic injection recovery. I also want to do more of the data set because I don't think these first ten TIC numbers have particularly good light curves. So super great day!
