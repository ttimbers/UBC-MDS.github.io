---
layout: post
title: Designing MDS
---

Since launching the UBC MDS program in 2016, we've received a lot of questions on why we designed MDS the way we did. Although I hadn't yet joined UBC when the program was originally conceived and the initial plans laid out, I joined early enough that I can hopefully do justice to these questions. I will also discuss what we learned and changed since the launch. The post will address the following design decisions:

- Statistics and CS as the "home departments".
- The program length: 10 months.
- Dividing the curriculum into 4-week courses rather than the traditional quarter- or semester-long format.
- Creating all new courses from scratch.
- The program prerequisites: one course each in programming, statistics/probability, and calculus/linear algebra.
- Dividing the traditional instructor role into two pieces: lecture instructor and lab instructor.
- Setting a single deadline for all assignments each week.
- And, of course, a few words on the content that we decided to teach in the program.

### Stat-CS partnership
The UBC MDS program is an equal partnership between the [Department of Statistics](https://www.stat.ubc.ca/) and the [Department of Computer Science](https://www.cs.ubc.ca/). I have noticed that some other DS programs lack the statistics component, and I think that is a big loss. To us, data science is not just computer programming and machine learning (and certainly not just deep learning!); it is a broad field about how to ask and answer questions using data. As an aside, the collaboration between departments has been extremely productive and pleasant. When I heard that multiple departments would be involved, I was expecting some of the politics that universities are so famous for. While I found some of that in other places, the CS-Stat collaboration at UBC has been great.

### 10-month program
For many MDS students, the program's compact length is a major draw. For some, especially those leaving well-paying jobs to train in data science, a longer program simply would not be financially viable. (Of course, we also get many students who would prefer a longer program - it's hard to please everyone!) Fitting everything we wanted to teach into such a short window was a big challenge, but also an opportunity to reflect on what content we felt was truly essential. Some have also asked why we chose 10 months instead of 12. That is not for the students, but for us! The MDS team needs time to recharge every year, which is usually spent on a combination of vacation and improving the curriculum before the next cohort arrives. Overall, I am happy with this decision.

### 4-week courses
Our [schedule](https://github.com/UBC-MDS/UBC-MDS.github.io/blob/master/img/schedule.pdf) is typical in the sense of students taking 4 courses at a time, but atypical in that courses only last for 4 weeks. The benefit of short courses is that we can have more fine-grained control of how much we teach in a given area. For example, we have one course in algorithms and data structures, two courses in visualization, and three courses in supervised learning (depending on how you count). While we would love to have three courses (equal to a standard length UBC course) in every area, there simply isn't time in 10 months. The difficulty is a potential lack of continuity between courses and instructors (more in this below), but overall I'm very happy with this structure.

### 24 new courses
The MDS program is structured as 6 "blocks", each containing 4 of these short courses, for a total of 24 courses. All of these courses were designed and created from scratch for the MDS program. As you can imagine, 24 formal UBC course proposals amounted to a lot of paperwork -- the whole package was over 200 pages -- but it was worth it! We ([and others!](https://twitter.com/hadleywickham/status/901055932901281792?lang=en)) feel that creating new courses is essential: because data science is such a rapidly evolving field, existing courses often weren't relevant or sufficiently up-to-date. Furthermore, in the interests of time we needed to select just the parts we needed (see above). 

How did we organize this large-scale course creation process? Once the rough course titles were chosen, we set up a "first reading" for each course, in which the committee would review the overall course learning goals, and a short title for each lecture and lab. Later, we would have a "second reading" which contained lecture-by-lecture learning goals and rough drafts for all of the lab assignments. This process took place mainly over the summer in 2016, with a large group of people involved in various ways: [Alex Bouchard-Côté](https://www.stat.ubc.ca/~bouchard/), [Jenny Bryan](https://jennybryan.org/), [Giuseppe Carenini](https://www.cs.ubc.ca/~carenini/), [Paul Gustafson](http://www.paulgstf.com/), [Ed Knorr](https://www.cs.ubc.ca/~knorr/), [Ed Kroc](https://ekroc.weebly.com/), [Gail Murphy](https://blogs.ubc.ca/gailcmurphy/), [Raymond Ng](https://www.cs.ubc.ca/~rng/), [Matías Salibián-Barrera](https://www.stat.ubc.ca/users/matias-salibian-barrera), [Tiffany Timbers](http://tiffanytimbers.com/), and myself.

(Note: all of this development was done with GitHub, and we would [tag a release](https://help.github.com/articles/about-releases/) after each "reading", which makes it easy to go back and view the development history of our courses. For more on how we use GitHub in MDS, see [here](https://ubc-mds.github.io/2017-08-24-teaching-with-github/).)


### Instructor roles
When MDS started out, the core teaching team consisted of two people: [Tiffany Timbers](http://tiffanytimbers.com/) (my fellow Option Co-Director) and myself. The program was set up with existing faculty members delivering the lectures and Tiffany/Mike teaching the labs. The idea was to bring in experts in each field from the pool of faculty members in the home departments, but without requiring an infeasibly large time commitment from these people; this way, we could bootstrap the program with only a small number of new hires (i.e., me and Tiffany). The lab instructors were meant to provide a consistent presence across all MDS courses so that the experience wouldn't feel "choppy" across so many small courses. 

Of all the decisions described here, this one feels like the most notable failure. With two instructors sharing each course, the potential for miscommunication was/is high, often resulting in frustrations for the students. Furthermore, we have a specific teaching style in MDS -- very applied and hands-on -- and it was not reasonable for new instructors to immerse themselves in our methodologies for just 4 weeks' worth of teaching. As the program grows, we are building up a core teaching team and moving away from this model. We have been very fortunate to add [Vincenzo Coia](https://vincenzocoia.github.io/), [Giulio Valentino Dalla Riva](https://www.gvdallariva.net/) (now at the University of Canterbury), [Varada Kolhatkar](http://www.cs.toronto.edu/~varada/VaradaHomePage/Home.html), and [Rodolfo Lourenzutti](https://www.linkedin.com/in/rodolfo-lourenzutti/?originalSubdomain=ca) to the team. We also continue to benefit from the ideas and course materials created by the original set of instructors, and we continue to pick their brains for new developments in their respective fields.

### Program prerequisites
The prerequisite courses for entering the MDS program [are listed online](https://masterdatascience.ubc.ca/admissions), but here is the summary:

- One university course in programming
- One university course in probability and/or statistics
- One university course in calculus or linear algebra (completion of both strongly recommended)

On the one hand, we wanted to keep the prerequsites light to encourage applicants from a variety of academic backgrounds. This has worked out well; for example, see [here](https://ubc-mds.github.io/2017-09-01-introducing-the-second-cohort/) and [here](https://ubc-mds.github.io/2018-09-17-welcome-2018-19/) for some demographic information about our 2nd and 3rd cohorts. It sounds like the students really benefit from being part of a diverse cohort.

On the other hand, if the prerequisites are too light, we might end up admitting students who aren't ready to tackle the program. As one strategy for helping prospective students calibrate their background knowledge, we created a [self-test](https://nbviewer.jupyter.org/github/UBC-MDS/UBC-MDS.github.io/blob/master/selftest/mds_self_test.pdf) (answers [here](https://nbviewer.jupyter.org/github/UBC-MDS/UBC-MDS.github.io/blob/master/selftest/mds_self_test_answers.pdf)) for students to self-assess their readiness. We also posted a [list of MOOCs](https://ubc-mds.github.io/resources_pages/prep_moocs/) that might help them prepare.

One tricky issue we've encountered is "over-qualified" students. Recently, our strategy has been to admit these students but add an extra paragraph in their offer letters explaining that their might be insufficient new content in the program, and that they should carefully consider whether MDS is right for them. As a rule of thumb, I have found students claiming proficiency in ~1/3 of the courses tend to thrive in the program, whereas ~1/2 of the courses starts to be too much for a fruitful experience. 

We are constantly evaluting our list of prerequisites, and may well change them in the future (lightly by increasing them slightly). For example, regarding calculus and linear algebra, we added the "completion of both strongly recommended" note after the first year. 

### A unified assignment deadline
In the first year of the program (2016-17), each lab assignment was due at the start of the next lab a week later. As a result, students had four lab deadlines per week, plus quizzes. We found that students struggled with the large number of deadlines and with always having four assignments hanging over them. Another problem was that the students always had something "due tomorrow", and we often found them working on these more urgent assignments rather than making good use of instructional time for the other three courses. For example, in a DSCI 571 lab on a Wednesday, students would often be working on a DSCI 532 lab due Thursday, instead of getting help from the DSCI 571 instructor and TAs who were available to help them with DSCI 571 content due the following Wednesday. (No judgement here -- I may well have done the same thing in their shoes!)

As a result of these difficulties, we switched to a single, unified deadline. This year, all the weekly lab assignments are due on Saturday at 6pm. We noticed a marked improvement in how lab sessions are used. This system has another major advantage: the students have no assigned work from Saturday 6pm until Monday morning. We feel that free time is extremely important for student wellbeing and productivity, especially within 10 months of intense study. 

While this all may seem like a trivial matter of scheduling, I think it's actually very important and would encourage other programs to deliberately carve out free time for the students. 

### The content
Rather than bloat an already-bloated blog post with a discussion of our curriulum, I will instead direct the reader to [this blog post](https://ubc-mds.github.io/2018-06-04-curriculum-CS-ML/) on the CS / machine learning stream of our curriculum. We are planning two more blog posts, on the statistics stream and "data science" stream, and I will add links here when they are posted. Beyond these 3 streams of MDS courses, the 2-month capstone course is also a critical part of our program. For more information of our capstone course, see our [capstone homepage](https://ubc-mds.github.io/capstone/about/), our [partners page](https://masterdatascience.ubc.ca/why-ubc/partners) and various posts on [this blog](https://ubc-mds.github.io/).

--------

[Mike Gelbart](https://www.mikegelbart.com/) is Option Co-Director of the MDS Vancouver program and an Instructor in the UBC Department of Computer Science.
