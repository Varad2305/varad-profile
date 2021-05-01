---
title: Automated intraday trading application
summary: A python based application that could enter and exit equity intraday positions in the Indian Stock Market by itself to create profits
tags:
- FinTech
date: "20-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Proposed framework
  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: 
#url_code: ""
#url_pdf: ""
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

This was my first project in the fintech space. I learned about technical analysis in the stock market and realised that a lot of it could be automated with proper risk management strategies. I implemented several strategies and scanners and deployed three strategies.

1. Renko + MACD
2. RSI + Pivot points
3. Super Trend

I also implemented candlestick pattern scanners which could detect the following patterns and used them alongside pivot points: 
1. Doji
2. Maru Bozu
3. Shooting Star
4. Harami pattern
5. Engulfing patterns

I automated trades from my personal account for a few days but stopped that as I did not have a lot of funds and a significant portion of the generated profits would be taken up by the brokerage. I incurred some losses as the strategies implemented were not perfect. I also wanted to utilise my funds to understand other parts of the market. All the code is publicly available on my GitHub.