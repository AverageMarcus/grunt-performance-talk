# Grunt Performance Talk
A talk about improving web page load performance using Grunt

## Before (GitHub Pages):
*WebPageTest*
http://www.webpagetest.org/result/150201_Z5_H34/
* Speed Index: 2522
* Load time: 8.568s

*PageSpeed Insights*
https://developers.google.com/speed/pagespeed/insights/?url=http%3A%2F%2Fjsoxford.com
* Mobile: 50/100
* Desktop: 63/100


## Before (my server):

*WebPageTest*
http://www.webpagetest.org/result/150130_DH_13R0/
* Speed Index: 1500
* Load time: 8.743s

*PageSpeed Insights*
https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fjsoxford1.marcusnoble.co.uk%2F
* Mobile: 48/100
* Desktop: 60/100

## After (without gzip + cache):
*WebPageTest*
http://www.webpagetest.org/result/150201_V5_HBV/
* Speed Index: 922
* Load time: 7.947s

*PageSpeed Insights*
https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fjsoxford2.marcusnoble.co.uk%2F
* Mobile: 58/100
* Desktop: 69/100

## After:
*WebPageTest*
http://www.webpagetest.org/result/150201_QM_GWC/
* Speed Index: 900
* Load time: 7.870s

*PageSpeed Insights*
https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fjsoxford2.marcusnoble.co.uk%2F
* Mobile: 59/100
* Desktop: 70/100
