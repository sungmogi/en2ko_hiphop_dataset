# en2ko_hiphop_dataset

This is a English-to-Korean translation dataset crawled and scraped by me in July-August 2023.

I found a Korean Hiphop community [website](https://hiphople.com/lyrics) where users have been uploading Korean translations of American Hiphop lyrics. I thought fine-tuning on data from this website would help MT models better capture slang within the context of Hiphop culture and African-American Vernacular English (AAVE).

Since HIPHOPLE is a community based website, all the different users who have been posting have been posting with different styles: someone might write one line in English followed by another in Korean while some other person might write the entire English lyrics followed by the entire Korean translation. 

I chose to crawl (using Scrapy) over the website to pick and choose posts written by one user DanceD, who generously gave me permission to scrape his contents and to use them. 

I have [uploaded the collected dataset on Huggingface](https://huggingface.co/datasets/sungmogi/en2ko_hiphop) (courtesy of DanceD :D).
The csv file of the dataset can be found in this GitHub repository. 

The collected lyrics were from artists from various regions and eras, including Wu-Tang Clan, Young Thug, Denzel Curry, 2Pac, and Kendrick Lamar.
