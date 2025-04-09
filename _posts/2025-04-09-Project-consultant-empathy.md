---
title: "Project consultant empathy"
date: 2025-04-09
---

I want to talk about empathy. In this post I'll be talking specifically about empathy for the consultant on the part of the client.

Broadly speaking, there are two types of statistical consultant. There are "talking consultants" - those that talk and discuss statistical problems with their clients, and there are "doing consultants" (or "project consultants") - those that primarily do an analysis for their clients. Of course "talking consultants" will often do some analysis and "doing consultants" will start by talking with their clients.

I'm going to focus on empathy for the "doing consultants" in this post.

Having empathy with the consultant will get you a better result every time.

When you ask someone to work on a project for you, you are collaborating. Don’t be duped into thinking that consulting is a service. Even if it is advertised, administered or charged as such.

<details>
<summary>The consultant is not your 'statistical bottle washer'</summary>
I met a senior consultant who colourfully described this service mindset as thinking of consultants as “statistical bottle washers”. An analogy to the lab technician who comes in to rinse out the bottles at the end of the day. I would argue that’s it’s worth respecting the bottle washers too, but the point being made is that all statistical analysis is thinking work, not rote labour. There are a myriad of choices to be made in even a simple analysis, and you need to truly collaborate in order to get a good result.
</details>

How do you collaborate effectively? You need to equip the consultant with everything they need to complete their job. The main way that you can do this is 

<details>
<summary>i) agree on a project brief</summary>

I really cringe at the number of job advertisements these days that mention "Data Insights". The old line about "if you torture the data long enough, it will confess" is quite apt.

There are two potential problems with the "data insights" approach which are quite different in nature, but I think stem from ignorance and a lack of empathy for the consultant:

* You want the consultant to go on a fishing expedition. But you won't just come right out and say it. The usual idea is that you have collected i) a massive amount of data ii) you have exclusive access to some valuable data, and you want the consultant to find some "insights" within it. The thing is, there is nothing wrong with a fishing expedition per se, but you need to accept and communicate the exploratory nature of the analysis with the consultant. It is better to use exploratory techniques that are specifically designed to identify relationships between multiple variables - typically some form of dimension reduction, rather than solely relying on a brute force approach of looking at the pairwise relationship between every variable that you have collected. Or looking at univariate relationships without regard for important confounding relationships.

* You want the consultant to find the result you want, not what they actually find. When you want the consultant to find the trend that you think is there in the data, and you don't accept that it is not in the data. Or a more general problem of not accepting the absence of evidence of any pattern. Or not accepting the evidence of a pattern, when you would prefer it to be absent. I'm fortunate that these types of behaviours are vanishingly rare amonst the academic researchers that I consult with. For consultants within private and government sectors, I can imagine that this is more frequent. Dr Karl describes his encounter with this early in his career, once in an academic lab, once in an engineering lab. This is probably the more egregious display of a lack of empathy and respect for the consultant. In the worst cases this is beyond not collaborating, it's a standover tactic.
</details>

<details>
<summary>ii) supply them with the right data.</summary>

In short, you need to give them the data, the whole data and nothing but the data.

There are plenty of considerations here. but let's just list a few:
* Are your variables (columns) labelled uniquely?
* Do you have relevant metadata - information like where the file came from, if it is a database extract what query was used to create it?
* Who can answer the consultants questions about your data, is it you, or some other data custodian?
* If the data came from a richer format, is all of the information from that richer format accessible somewhere? (e.g. if it is a .csv from a RedCAP database, can the factor level encoding be accessed?)

</details>

If you don't know how to do these things, it is important to try to know the answer instead of leaving it up to the consultant to ask questions. Doing so demonstrates your willingness to collaborate and your buy-in to the collaborative process.

When you hand over the data, the consultant should be able to understand and assure themselves that what they are working on is what you think they are working on. 

An ideal situation is that the project brief is so clear, and the data is well-documented enough that the consultant doesn't have any questions before the analysis begins Even if that ideal is rarely met, it is always a worthwhile goal to aim for. At the very least, the questions that the consultant asks will advance their understanding of your project goals, and not be some trivial or basic question through underdocumentation.

Good luck with your project. Understanding empathy, and the way that translates to how you collaborate with a consultant, will help everyone involved in the process.

