# Pokemon card prices data story
This project is my fourth story for a class I have taken in Columbia Journalism School's data journalism program called **"Data Studio"**, instructed by Jonathan Soma. This project includes a line chart visualization and scrolly telling techniques, as long as a little "guess the card's price" game.

## _What I want to accomplish_
This story meant to tell the readers that how a Pokemon card could be extremely expensive and not accessible to general buyers. It is a new business right now, not only among the collectors.  

## _Skills and approaches_

### 1. Pitching 
In the early stage of this project, I had a few ideas of what dataset I should play with. I also thought about the k-pop photo cards because those are super expensive and an interesting dataset to visualize too. But I just feel like general public might be more interested in knowing more about Pokemon cards anyway, so I found a database called Price charting: https://www.pricecharting.com/, which is easy for me to scrape. <br>

Because I have zero knowledge of Pokemon cards and how the prices are going up and down by years myself, I then reached out to Keiji Umehara, a Youtuber creating content about Pokemon cards based in Singapore. Thanks to my friend PT for the connection there so I can find him to interview.<br>

### 2. Refining

I scraped through Playwright at first, but it wasn't able to find the data I want from the page. So I did a view page source and found how the price of the timeline is hold through "VGPC.chart_data", and I asked Claude to scrape this data for me.<br>

I then decided to narrow it down to nine cards where Keiji said it will be interesting to look at. They are all fan favorite, and ditto is growing popularity since the release of the game "Pokopia". So I have a D3 chart looking at how the cards' prices changed over time.

### 3. Big change!
This project was totally a different one at first. I used ggplot in R to plot the chart at first, refined it with ai2html, put it in Adobe Illustrator... and the chart was a trash and I didn't like it at the end. Also, I learned D3 recently so I wanted to try it out, and I want to make something animated and interactive, that's why I changed this whole project. 

### 4. Technical skills 
Scraping through PlayWright, writing and designing html, css, chart made by D3.js, workflow on GitHub.

### 5. What I grew the most
1. Better scraping, better html building, use D3 to make a chart.
2. Web design! Insert a little interactive game for the first time!
3. Adding Keiji's character too!

## _What I can do better_
1. Make something cool? But honestly I don't know how to make this page cooler.
2. Better in refining the story angle, and writing the story with the chart.
3. Make cooler viz. -_-
