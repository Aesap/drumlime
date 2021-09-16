# ![Drumlime Logo](https://github.com/Aesap/drumlime/blob/main/drumlimelogo1.png?raw=true) Live Preview: https://aesap.github.io/drumlime/
The purpose of this project is to scrape reddit and then add any links that make the subreddit's top 10 to your own website. The scraper is built using PYTHON.

There are 3 main scraping scripts in this project and they all scrape from the https://reddit.com/r/drumkits subreddit. The scripts pull data using the reddit API (PAWS python library) and then transforms such data using (PANDAS python library). It also has code included for creating timely backups of data, just in case.

The first version of the site did not look this good. After implementing bootstrap 4, a website building framework, I was able to make the site prettier and more responsive. All the code was put on a AWS Lightsail instance, and hosted on a Windows 2016 server. It used IIS on Windows 2016 server to display the site to the public. I also made bat files for the python scripts that were executed every 3 hours by Window's Task Manager. This way the site would be fully automated. The site/aws instance is no longer online. 
