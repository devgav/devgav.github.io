---
layout: project
type: project
image: "images/bb_kk.png"
title: BestBot
permalink: projects/BestBot
# All dates must be YYYY-MM-DD format!
date: 2021-10-22
labels:
  - Javascript
  - Puppeteer
  - Web scraping
  - Automation
summary: A program created to buy any in demand item from the BestBuy website.
---

 <img class="ui image" src="https://i.pcmag.com/imagery/articles/06YHBxnn2kbrapAPhI5F2om-6.png">


The idea of this bot was to scrape the Bestbuy website for a GPU (Graphics Processing Unit) and when the bot could find a GPU within a reasonable price it will automatically check-out. Bestbuy regularly sells and restocks GPU's for MSRP (Manufacturer suggested retail price) which is why I specifically targeted the Bestbuy's website when creating this bot. The reason this bot was created was to compete with other self-checkout bots on the market that purchase these GPU's at a faster rate than most consumers can. 

During the creation of this bot I learned alot about working with a high-level API, primarily reading documentation. This was also the first time that I had used javascript in a real project and also learned about asyncs and awaits. There were lot's of complications while creating this project, such as BestBuy changing it's CSS classes to prevent bot's like the one that I made. To get around this issue I noticed a pattern with the CSS classes changing mainly that only the numbers at the end of the class changed. I used regex to check for these number's. While creating this project I also had to think of the most efficient ways to get to the Bestbuy item page to my checkout cart. 

Source: <a href="https://github.com/devgav/BestBot"><i class="large github icon"></i>devgav/BestBot</a>



