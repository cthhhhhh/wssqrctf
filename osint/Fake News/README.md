# Fake News ?
Author: [Xiaozhi](https://github.com/xiaoxiao69)

## Description

Knowledge of OSINT knowledge online.

## Requirements 
- Google Search Engine



## Sources

- [railway.zip](https://github.com/ChanTingHui/wssqrctf/blob/main/osint/Fake%20News/bin/railway.zip)


```
We've just received a report of The WSSQR NEWs publishing an article that is causing a lot of concern and fear in the public. Given its wording and theme, I am sure it's fake news generated by some TP student. However, WSSQR will not disclose their source. Here's a part of the article, you will need to find the exact number of people that went through Southern Cross Station at the exact time referenced so we can determine if the article is fake. The railway station has released a statement saying that all footage of that night has been deleted so I can't provude you with it.

Article text: "Wild scenes as 40 people confirmed to be infected with COVID-19 ran through a railway station at 5:00am on Monday, the 16th of June 2020. The frightening witness account has caused panic buying at stores around the country as people prepare to stay indoors. Our source confirms they were the only witness and that this infectious routine could be happening at other major transport venues through the country without the public's knowledge."

Find the exact number of pedestrians that walked on that station during the exact day and time.

Flag format: wwssqrctf{x} (where x is the digit only)
```


## Exploit

Candidates are required to highlight some of the key information. To identify the exact location to start on, google search the railway.jpeg and it will show a railway station named Southern Cross Station. To view where is the station located in the world, Google the station name and it will show us a lot of hints leading to it being located in Melborne.

From there , candidates can search up Melborne pedestrain counter on google and there will be a site that shows the amount of pedestrain in a street of Melborne during a specific day and time. Enter the key values in the news article such as 28th of February 2020 and 5:00am , it will show that there were only 37 pedestrain on the station during that time. A link of how the output with the correct input is shown below.
http://www.pedestrian.melbourne.vic.gov.au/#date=16-06-2020&sensor=Col700_T&time=5




The flag is:

```
wssqrctf{37}
```
