---
layout: essay
type: essay
title: "The etiquette and strategies for not just asking questions but to getting a solution"
# All dates must be YYYY-MM-DD format!
date: 2026-09-10
published: true
labels:
  - Stack Overflow
  - Communications
---

More likely than not you have come across at least one problem that you just did not know how to tackle and you decided to throw the question into Google. Currently with AI, those questions can get a fairly detailed answer that may or may not be the solution you were looking for. Before the advent of artificial intelligence and models like Gemini or ChatGPT, people had to pray that someone in the past decade had the exact same problem and asked in a Reddit thread or Stack Overflow that got a solution in the replies. If you were not blessed to have such coincidences, the next best thing was to ask the question yourself and hope for a swift and helpful response. You do so but none show.

<div> 
  <img width="300px" class="rounded float-start pe-4" src="../img/essay_imgs/questioning_img.jpg">
</div>


## What went wrong?

One must remember that forums like Reddit or Stack Overflow are composed of other people who are generous enough to spend their time sharing their expertise on difficult subject matters to assist others lacking such knowledge. To ask a question that, in their mind, wastes their time or effort could likely be the reason why no helpful response has arrived. This is where knowing the etiquette and strategies to asking a question on sites like Stack Overflow becomes a vital toolkit. 


<img width="250px" class="rounded float-start pe-4" src="../img/essay_imgs/stackoverflow.png">

## A Smart Question

As outlined in the article, How To Ask Questions The Smart Way, by Eric Raymond, the best way to find a solution to your problem is to first exhaust all ways to solve it yourself, and only after doing so, should you pose a question, ensuring that your problem or inquiry can be answered by the people you are reaching out to. In such a question, you should give as much pertinent detail as possible while not trying to get others to write your entire codebase for you. When looking at Stack Overflow questions, and sorting by score, the highest rated post asks for an explanation on why [condition processing of an array is faster in a sorted array as compared to an unsorted array](https://stackoverflow.com/questions/11227809/why-is-conditional-processing-of-a-sorted-array-faster-than-of-an-unsorted-array) 

The title provides a concise description of the subject and in the post, the author provides the code they wrote to demonstrate the phenomena, as well as the same code written in a different language to check if it was a language dependent occurrence. The original poster provided the runtime duration for each instance, shared their own thoughts on what may be happening after investigating it on their own, and at the end focused the question on what underlying processes are responsible for the differences in runtime. 

The highest scored answer to this post gives a concise reply stating that it is the result of branch prediction where a program will attempt to guess which conditional statement will be true or false ahead of time, and if the guess was incorrect, the program takes more time to rollback its processes and correct its course. The answer itself is detailed with images, analogies to better express the concept of branch prediction, and a visualization of how the array is handled by the conditional statement. Both the inquiry and response for this post demonstrate smart ways to ask and answer a question.

## A Not so Smart Question

On the opposite end of the spectrum with a score of -22, this user posted an [error that occurred while running Android app, citing a failure to gain read and write permissions](https://stackoverflow.com/questions/76641553/errno-13-permission-denied-storage-emulated-0-download-site-html) 

In their post title they only provided the error code and not a question or description on what exactly they needed help with. Inside the post itself they display their code and at the bottom, go on to explain that they are having issues gaining file access permissions with their app on the Android 11 system. Although they do provide a snippet of the code where the issue appears to occur, they also go on to plead for help and ask for a solution to achieve a read-write permission prompt similar to other apps that they linked to in their post. In the replies, they are informed that Android 11 cannot achieve their specific result and given alternatives, to which the original poster responds with requests for people to look more carefully at their code. 

In terms of "smart" questions, this post showcases pleading for a specific solution, improper grammar in some sentences, an unclear description of the problem they are trying to solve. Moreover, when some users give them an answer, the original poster is insistent for someone to give them a specific solution. In the replies of an answer, some people are simply poking fun by commenting nonsense such as “VvvvvvvvvvVivek“ which may be a sign of frustration with the user asking for help. 

### Study First!

The main takeaway from knowing how to ask a question on Q&A forums is to try solving it yourself before running for help. Searching through publicly available resources before asking a forum, shows not only investment and care in solving the problem but respect for other people’s time, especially in the case where the answer was nestled deep inside documentation or a user manual. Above all, showing a decent level of respect for the people providing the answers to hundreds if not thousands of questions a day can go a long way towards ensuring the response is productive to your goals.

<hr>

<h3>AI Usage</h3>

Gemini was used to find and fix any capitalization errors, misspellings, and improper grammar. All content was authored by Au Quang.
