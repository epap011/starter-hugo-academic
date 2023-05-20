---
title: Ad Provider | AWS Event-Driven Serverless application
summary: An example of using the in-built project page.
tags:
  - All
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

This project focuses on developing a service system for search advertisements that involves a publisher (such as Google) and advertisers competing for high positions on an ad ranking list. Advertisers participate in an auction, publishing their maximum price for a click. Based on statistics from previous rounds, the provider decides which ads to show and in what order to maximize revenues. Clients click on ads based on a probability distribution and may make a purchase based on another probability distribution. At the end of each round, the provider shares statistics with advertisers, who then make improved bids for the next round to increase profit.

The development of this service system involves the utilization of various AWS services. These services include AWS Lambda, Amazon SNS, Amazon SQS, Amazon DynamoDB, and Amazon EC2.
