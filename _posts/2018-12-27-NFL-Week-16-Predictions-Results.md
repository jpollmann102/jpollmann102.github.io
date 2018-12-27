---
layout: post
excerpt: My machine learning program's predictions and results for the NFL week 16 games, and what I've learned
---

I've been working on a program to predict NFL scores as a project to better my understanding of ML (not to mention add to my portfolio.) Overall it was a successful weekend, however I have learned a lot and will need to make changes to how things work moving forward.

Overall, my algorithm went 10-6 on the weekend. Some of the bolder predictions ended up *almost* happening, the Jets were predicted to win, in addition to the Giants, both of which ran it down to the wire when they probably shouldn't have. Some other notable stats include the Browns and Patriots scores. The Browns were predicted to win over the Bengals 23-17, and the actual score was 26-18. The Patriots were predicted to win over the Bills 25-13, and the actual score here was 24-12.

So, predicting scores is hard. The predicted point spread was only right four times, and the games were over six times, under ten. What I learned here though through some analysis today was that, interestingly enough, some of the statistics you may *think* would correlate to a team's score, actually don't (at least not linearly.) Namely, a team's rushing and passing yards do not linearly correlate to the team's points in the weekend. Even further, each team's defense doesn't linearly correlate either. By this I mean that each team's defensive scoring percentage (the percent of drives that the other team scores on them) doesn't seem to matter when predicting scores. You would think that this would matter at least a little bit, logically.

Despite these facts though, the model for last weekend still did pretty decent. In training, it can predict the winners of the 2017 games with 82% accuracy. But, moving further, I will be implementing a neural network to work on this, in the hopes to better predict a winner. Hopefull this weekend is even more successful.
