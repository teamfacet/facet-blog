---
title: "I Cheated on My Microsoft Interview"
date: 2019-05-21T00:00:00-07:00
authors: ["Robert Sweeney"]
categories: ["Hiring", "Developer Interviews"]
tags: ["Hiring"]
---

![Microsoft sign](/blog/uploads/microsoft-sign.jpg)

In 2004 I was a senior majoring in Computer Engineering at Brigham Young University. The tech industry hadn’t yet fully recovered from the bubble bursting, so programming jobs were pretty hard to come by. I was applying for jobs everywhere, but just couldn’t seem to get an interview.

One day, I saw a flyer pinned to the mostly empty job board in the Computer Science department. It said that Microsoft would be coming to the campus for a job fair. I immediately sent my resume to the email address on the flyer, not expecting to hear anything back. 

A few days later, to my surprise, I got an email from a recruiter at Microsoft. She invited me to a 15 minute interview with a Microsoft representative during the career fair. I was thrilled! This would be my first real job interview ever. 

I immediately called my good friend Eli who had just started a new job at Microsoft. I asked him what the on campus interviews were like and how I should prepare for them. He explained that they would ask a random programming question that I would need to solve on a sheet of paper. If you did well, then they would fly you out for a full day of interviews at the Microsoft headquarters in Redmond, Washington. He had been asked to write a function that, when given an array of length n + 1 containing integers 1 through n, find the duplicate integer in an array.

I wasn’t sure how to prepare for answering a “random programming question”, so I decided to just use the question Eli had been asked as practice and hope for the best. Over the next few days I thought about different ways to implement the function. At one point I had a flash of insight: there is probably a mathematical formula for calculating the sum of 1 to n. So I looked it up and sure enough, there is:

  > ```sum(1 to n)  = n(n + 1) / 2```

If I used the formula to calculate the expected sum, then summed all the integers in the array, the difference between the two values would be the duplicate number. Cool!

A few weeks later I’m about to go in for my interview and I’m so nervous I can barely think straight. I finally got a job interview and I didn’t want to blow it. There are dozens of developers interviewing today and only a few of us will be invited to fly out for a full round of interviews. It’s finally my turn. Most of the interview is a blur, but I remember the interviewer being nice and I remember the programming question he asked me. I’ll never forget the programming question: 

> ```Write a function that, when given an array of length n + 1 containing integers 1 through n, find the duplicate integer in an array.```

I couldn’t believe it. He asked me the exact same question as Eli. Should I tell him? I hesitated for a moment, pretending to be thinking about how to solve the problem. In reality I was having an intense internal debate on the ethics of interviewing. He didn’t ask me if I had *heard* the question before, he just asked me to solve it. So I decided to just answer the question.

I casually explained how I could simply use a mathematical formula to calculate the sum of 1 to n (like, who doesn’t know the sum(1 to n) formula?) and compare that to the sum of the integers in the array. I slowly wrote out the solution I had come up with over days of thinking about the problem, being sure to pause periodically as if I was figuring it out for the first time. I talked through my thinking and made sure I had all the proper error checking in place.  I double and triple checked my syntax. My handwritten code was perfect.

He seemed impressed as he reviewed by code. When he was done, he told me that the interview was over and thanked me for coming in. I walked out of the interview room feeling pretty good...until I saw all the other students waiting outside for their turn to interview. I felt like I had an unfair advantage. My preparation, plus a crazy coincidence, made me feel like I had cheated on my interview. 

A few days later I received an invite to fly out to the Microsoft main offices. I interviewed with two teams over a period of 6+ hours. I didn’t get asked any questions I had heard before this time, but I did my best. During my final interview of the day I was asked which team I would want to work for. I took that as a very good sign!

Sure enough, that next week I had a job offer from Microsoft from both teams. I ended up joining the Windows Shell (UX) team and working with some absolute legends like Raymond Chen and Chris Guzak. Within a couple of years of graduating from college, I had shipped software that was being used by nearly a billion people. It was surreal seeing people everywhere using something I had made.

I’ve struggled with this a lot over the years, but I finally decided to share my story. I don’t think I would have made it past the first round of interviews at Microsoft if I hadn’t gotten so lucky. So pretty much, my entire career is built on one amazing stroke of luck. 

I also think my experience is a great example of one of the many reasons why the coding problems we use in developer interviews are so problematic: on the spot coding is just not a good way to judge technical ability. While it may have worked in my case, it definitely didn’t work the way Microsoft had intended. Ironically, because I had several days to think about the problem and work out a solution, my on-campus interview might have been a better measure of my ability. Today you could just Google the programming problem I was asked and find a dozen solutions, but that didn’t exist back in 2004. I had to draw on years of learning and consult external resources like a math textbook, just like I do every day at work. I think a better interview format would give the candidate time to work out a creative solution to a problem on their own without requiring an exorbitant amount of their time. (I’m not a fan of take home coding projects.)

I’m working on a follow up blog post with some ideas on better ways to do programming interviews. Stay tuned.

