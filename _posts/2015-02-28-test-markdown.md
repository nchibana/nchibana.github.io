---
layout: post
title: Test markdown
subtitle: Each post also has a subtitle
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---

For my first data science project, I analyzed the results of three different psychometric tests available online, with a total of 110,000 test results which were released with the consent of all test takers.

I found that there is a statistical relationship between different demographic characteristics and personality and behavioral traits.

For example, I found that there seems to be a statistical relationship between professed religion and stress scores.

<div>
    <a href="https://plot.ly/~keiko/0/?share_key=WghoakngNzWKufzp7IpggI" target="_blank" title="my-graph.html" style="display: block; text-align: center;"><img src="https://plot.ly/~keiko/0.png?share_key=WghoakngNzWKufzp7IpggI" alt="my-graph.html" style="max-width: 100%;width: 600px;"  width="600" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
</div>

Here you can see that those who labelled themselves as Mormons registered the highest stress scores, while Protestant register the lowest ones. I conducted a two-sample t-test to determine whether the difference in means was significant and it was. 

In terms of age and gender, I found that the older test takers registered higher levels of emotional stability compared to those who are younger. Also, males scored higher across all ages. The chi-squared results for this test also indicate that the variables of age and emotional stability are not independent of each other.

<div>
    <a href="https://plot.ly/~keiko/10/?share_key=GMeCaIWEDt29V0E7NCsPmc" target="_blank" title="emotional_stability_line_chart" style="display: block; text-align: center;"><img src="https://plot.ly/~keiko/10.png?share_key=GMeCaIWEDt29V0E7NCsPmc" alt="emotional_stability_line_chart" style="max-width: 100%;width: 600px;"  width="600" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
</div>


Regarding race, I also plotted the results and conducted a chi-squared test which also indicate that there is a relationship between race and different personality measures such as extroversion and conscientiousness.

<div>
    <a href="https://plot.ly/~keiko/14/?share_key=Hgd1N5LJqRreSCjgHovL4y" target="_blank" title="race-test-results" style="display: block; text-align: center;"><img src="https://plot.ly/~keiko/14.png?share_key=Hgd1N5LJqRreSCjgHovL4y" alt="race-test-results" style="max-width: 100%;width: 800px;"  width="800" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
</div>


As for sexual orientation, I found that those who labelled themselves heterosexuals registered higher levels of emotional stability and lower levels of depression and anxiety, while those who self-registered as bisexuals were on the other end of the spectrum.

<div>
    <a href="https://plot.ly/~keiko/12/?share_key=UFP4o8fx8orCd3xGUbBCGx" target="_blank" title="make-subplots-multiple-with-titles" style="display: block; text-align: center;"><img src="https://plot.ly/~keiko/12.png?share_key=UFP4o8fx8orCd3xGUbBCGx" alt="make-subplots-multiple-with-titles" style="max-width: 100%;width: 800px;"  width="800" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
</div>


Finally, regarding country of origin, I found that stress scores were higher for some Middle Eastern and African countries.

<div>
    <a href="https://plot.ly/~keiko/48/?share_key=80LGKcK36wBktoMpKM5KTA" target="_blank" title="plot from API (18)" style="display: block; text-align: center;"><img src="https://plot.ly/~keiko/48.png?share_key=80LGKcK36wBktoMpKM5KTA" alt="plot from API (18)" style="max-width: 100%;width: 600px;"  width="600" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
</div>

In conclusion, characteristics inherent to our identity are related to our personality and behavioural traits, but it is still to be investigated how this population of online test takers differs from the general population.

