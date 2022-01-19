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

The idea of this bot was to scrape the BestBuy website in order to find a GPU (Graphics Processing Unit) within MSRP. Bestbuy regularly sells and restocks GPUs for MSRP (Manufacturer suggested retail price), which is why I specifically targeted Bestbuy's website when creating this bot. The reason this bot was created was to compete with other self-checkout bots on the market that purchase these GPUs at a faster rate than most consumers can. 

This was a sole creater of this project. This project utilized Googles Puppeteer API, which is a API that allows users to automate browser tasks among other things. To store the users location I utlizied a seperate JSON file so that I can cleanly organize a user info along with the web URL they are searching for.

During the creation of this bot, I learned a lot about working with a high-level API, primarily by reading documentation. This was also the first time that I used JavaScript in a real project and I also learned about asyncs and awaits. There were a lot of complications while creating this project, such as BestBuy changing its CSS classes to prevent bots like the one that I made and the websites' security to counteract web scraping bots. To get around this issue, I noticed that every item has an identification number associated with it, which is changed whenever you reload the page, so it didn't matter what these numbers were as long as I could associate the id with the product that it was attached to. This overcoming this challenge taught me much more about the DOM. While creating this project, I also had to think of the most efficient ways to get from the Best Buy item page to my checkout cart and fill out my credit card information. 

Source: <a href="https://github.com/devgav/BestBot"><i class="large github icon"></i>devgav/BestBot</a>



