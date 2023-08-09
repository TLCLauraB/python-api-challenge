# python-api-challenge
Homework Repo for Challenge 6

## Author: Laura Bishop

## Overview

I received help and support from my fellow Data Vis classmates via our Discord Server (both through voice chat and text), as well as our class-provided Slack Channel. I regularly attend both before- and after-class Office Hours to engage the materials with the Instructor and TAs.

I rewatched several of the classes from Module 5 using the Zoom recordings found at BSC > Zoom > Cloud Recordings. In conjunction with that, I re-reviewed the Module 5 Instructor Demos provided through GitLab.In particular, Module 5.1 Scaterplots and Module 5.3 Fits and Regression.

## Observations

* I can plot a Scatterplot, but I do not feel confident reading their results for analysis. 

* I found the provided starter code rather confusing, as it did not match what we had learned in class. It made me go out 'into the world' to find solutions, but I lost a considerable amount of time simply trying to figure pieces out before I could begin the lesson.

* At one point, a city in the Pitcairn Islands was registering at 300+ Degrees, which I do not believe is possible.

URL For Adamstown : `https://api.openweathermap.org/data/2.5/weather?q=adamstown&appid=cceeb529a494f7baa4f2cd5f4364bd8c`

`{"coord":{"lon":-130.1015,"lat":-25.066},"weather":[{"id":500,"main":"Rain","description":"light rain","icon":"10d"}],"base":"stations","main":{"temp":295.46,"feels_like":295.97,"temp_min":295.46,"temp_max":295.46,"pressure":1008,"humidity":85,"sea_level":1008,"grnd_level":999},"visibility":10000,"wind":{"speed":14.3,"deg":309,"gust":19.87},"rain":{"1h":0.64},"clouds":{"all":92},"dt":1691545752,"sys":{"country":"PN","sunrise":1691507600,"sunset":1691547531},"timezone":-28800,"id":4030723,"name":"Adamstown","cod":200}`

I am still genuinely confused.

Fellow student Alexandra Calametti suggested adding &units=imperial to the end of the base_url, and that seemed to help some.

What are:<br />
`# Test for Success`
These are milestone tests I use to make sure the functions I am building perform as desired before incorporating into the whole of the code.
<br />
`# DEBUGGING`
When something would break, I would go back and run alternative methods of a section until I found a solution that matched the example.

## Resources

### Web Sites Used

* Class Zoom Recordings 
    * https://courses.bootcampspot.com/courses/3876/external_tools/249

* GitLab: UofM-VIRT-DATA-PT-06-2023-U-LOLC
    * https://git.bootcampcontent.com/University-of-Minnesota/UofM-VIRT-DATA-PT-06-2023-U-LOLC

* General Documentation
    * https://www.toptal.com/developers/gitignore/
    * https://openweathermap.org/api/one-call-3
    * https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.scatter.html
    * https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.copy.html


* General Reference:
    * https://stackoverflow.com/questions/55507926/create-folders-dynamically-and-write-csv-files-to-that-folders
    * https://www.geeksforgeeks.org/ml-linear-regression/
    * https://stackoverflow.com/questions/68474856/making-a-list-of-coordinates-from-2-seperate-lists-that-display-latitude-and-lon
    