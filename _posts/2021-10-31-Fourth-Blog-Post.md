---
layout: post
title: Fourth blog post
---

# Second project reflection - online news popularity

_The web page for this project may be found [here](https://mfaustin.github.io/ProjectTwo558/), and the GitHub repository is hosted [here](https://github.com/mfaustin/ProjectTwo558)._

Mark Austin and I collaborated to complete the second project. Mark's random forest model produced the lowest RMSE in five of the six channels, but my linear model performed relatively well in the "lifestyle" category. I had expected boosted tree models to fare better than random forest models, but my take-away is that boosted tree models are more difficult to tune. Next time, rather than ceding control of parameter selection to `caret` using `tuneLength = 5`, I will spend more time manually fine-tuning parameters and comparing model peformance. 

Since the `caret` package made building models a simple process, the most difficult part for me was identifying variables for interesting visualizations. I scoured sites such as [Top 50 ggplot2 Visualizations](http://r-statistics.co/Top50-Ggplot2-Visualizations-MasterList-R-Code.html) for inspiration and learned to produce treemaps and density contour plots. It is clear that `ggplot2` is incredibly versatile and, in the hands of experts, can produce a wide array of captivating plots. However, in my case, I settled with the more mundane trio of barplot, boxplot, and a plot of the ECDF. 

My final takeaway from this experience concerns the value of collaboration. Generally, I learn concepts best by working alone on projects. I enjoy figuring out how best to fulfill every requirement and I spend hours scrutinizing plot details and lines of code, knowing that I alone am responsible for the final product. In this case, however, Mark had valuable ideas that I would not have otherwise considered, such as implementing parallelization with caching. I am happy with our submission and I look forward to seeing the requirements for our third project. 
 

