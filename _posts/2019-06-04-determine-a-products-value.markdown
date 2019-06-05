---
layout: post
author: Jacob Sansbury
title: "Determining a Product's Value"
categories: money decisions life
---

I'm on a journey to crack the nut of personal finance. Personal finance isn't just for aspiring millionaires, it's for anyone who wants to build their life on a solid foundation. It's amazing to realize how understanding your money will give you the freedom you've always wanted.

Over the course of my journey, I've stubbed my toe many times. I've made tons of mistakes and reflected on my mishaps time and time again. Through my toils, I've come to understand that personal finance requires you hear your logic over your emotions.

In order to manage your money well you must make the best decision you can. A good decision is one that maximizes gains and minimizes losses for the individual and society as a whole. Its rare to find a human that consistently deflects their emotions and makes logical decisions. After realizing this shortcoming it made more sense to reframe the problem. How can I make decisions quickly and logically regardless of my emotions.

After framing the problem in this way, it was just a few days before I concluded this was a task destined to run on a computer. Computers have a significant advantage over humans, they are not affected by their emotions. This makes them much better at making logical decisions. Given a computer with algorithms that reflected my logic it could more effectively make decisions that achieve my goals. The next challenge was building algorithms that reflected my logic.

First I need to record my decision making criteria for various situations. In order to workout my process I recorded my logic for choosing between items that solve the same problem. I decided that the basic building blocks of my logic were `cost`, `durability` and `effectiveness`.

-  `cost` — the dollar value of the item
-  `durability` — the number of months the item will solve the problem
-  `effectiveness` — how well the product solves the problem from 0-2

After I had defined the basic building blocks I began to search for the relationship between them. I had the inputs for my algorithms and I knew the desired output. In order to determine the formula, I recorded my thinking about the value of an item.

-  Sloppy or ineffective solutions are less valuable
-  A more durable item is more valuable
-  Increasing effectiveness quickly diminishes in value

Ultimately, I built the following formula to compute a score based on my logic.

![Score Formula](/images/posts/pf-cost-score.png){:class="post-image"}

In practice, this formula can be applied to rank multiple items. Given a set of choices the highest score is most valuable. Take for example, trying to pick between different pairs of shoes:

| Name              | Cost | Durability | Effectiveness | Score |
| ----------------- | ---- | ---------- | ------------- | ----- |
| Nike Tanjun       | 49   | 10         | 0.5           | 30.61 |
| Addias Ultraboost | 106  | 10         | 0.85          | 17.45 |
| Walmart Sneakers  | 10.5 | 4          | -0.6          | 15.24 |
| Gucci Sneakers    | 650  | 12         | 0.9           | 3.51  |

In this scenario, the Nike's are the best value. They solve the problem for the lowest cost per month and effectiveness.