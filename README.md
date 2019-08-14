# Data-Analysis

I create this jupyter code for a small challenge project to detect vulnerable urls to Blind SQL Injection attack. 
The algorithm that I used is based on probability density function of regular response time of urls before attacking them. It means by finding the pdf of regular reponse time, with a proper confidence interval we can be sure than which url is vulnerable or not without having any false positive ulrs.

the challenge is to make the time of testing pool of urls reasonable and at the same time the false positive need to be zero. In order to send request for urls I made use of grequest module in python which is async version request module.
