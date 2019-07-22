# market-color-map
This SW creates and display colormap of the historical market prices autocorrelation-

* Use WEB site https://leonidmtertitski.github.io/ or copy all files to a local folder and then open index.html with Google Chrome.

* When you start it first time from local folder you need to use "Choose a file..." button and select local csv file with Open, High, Low and Close values (you can use provided TEST.csv file as example).

You can select your own csv file with historical Open, High, Low, Close data: use Yahoo (https://help.yahoo.com/kb/SLN2311.html) to download historical data.

SGraph calculates autocorrelation and potential profit (for one market share) by using autocorrelation, historical data and the following strategy: 
1. If you do not have shares, then buy when market open. 
2. Set "sell limit" to: "Price at Open" x "Calculated by SGraph recommendation".

The X, Y color of colormap calculated on the basis of Time (X) and time difference between correlation intervals (Y). Red color - "good" correlation, Blue - "bad".

The following screen shot show autocorrelation colormap and graphic of profit (caculated on the bases of the maximum correlation):

<img src="https://user-images.githubusercontent.com/31733278/61602600-dbb95800-ac57-11e9-9934-eb8e8b0e62f3.png" alt="Image 1"  />

<hr>


<img src="https://user-images.githubusercontent.com/31733278/61602635-03a8bb80-ac58-11e9-8027-70a3bb4a6781.png" alt="Image 2"  />
