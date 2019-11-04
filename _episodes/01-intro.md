---
layout: episode
title: "About the project"
teaching: 30
exercises: 0
questions:
  - "What is CodeRefinery?"
  - "How does CodeRefinery relate to the Carpentries?"
  - "What are the main goals of CodeRefinery workshops?"
  - "Who is in our target audience?"
  - "What is our training philosophy?"
objectives:
  - "Discuss main goals of CodeRefinery"
  - "Understand that CodeRefinery workshops make a difference"
  - "Discuss differences between CodeRefinery and the Carpentries"
keypoints:
  - "Workshops have an impact - past participants report improved practices"
  - "CodeRefinery teaches best practices for research software development"
  - "CodeRefinery workshops benefit most those who already code"
---

# The CodeRefinery project

CodeRefinery is a [Nordic e-Infrastructure Collaboration (NeIC)](https://neic.no/) project that has started in October 2016 and is funded until October 2021.

---

## History

The CodeRefinery project idea grew out of two [SeSE](http://sese.nu) courses given at KTH Stockholm in 2014 and 2016:
- [http://sese.nu/scientific-software-development-toolbox/](http://sese.nu/scientific-software-development-toolbox/)
- [http://sese.nu/scientific-software-development-toolbox-2016/](http://sese.nu/scientific-software-development-toolbox-2016/)

The project proposal was submitted to NeIC in 2015, accepted in 2015, and started in 2016.

We have started by porting own lessons to the Carpentries teaching style and format, and collaboratively
and iteratively grew and improved the material to its present form.

---

## Main goals

- Develop and maintain **training material on software best practices** for researchers that already write code. Our material addresses all academic disciplines and tries to be as programming language-independent as possible.
- Provide a [code repository hosting service](https://coderefinery.org/repository/) that is open and free for all researchers based in universities and research institutes from Nordic countries.
- Provide **training opportunities** in the Nordics using Carpentries and CodeRefinery training materials.
- Articulate and implement the CodeRefinery **sustainability plan**.

---

## Impact

We collect feedback and survey results to measure our impact.

3-6 months after attending a workshop, past participants are asked to complete a short post-workshop survey.
The survey questions aim to establish what impact CodeRefinery workshops have on how past participants develop 
research software.

![post-workshop survey results](https://coderefinery.org/assets/img/heatmap_yesno.png)

- Overall quality of research software has improved: more reusable, modular, reproducible and documented.
- Collaboration on research software development has become easier
- Past participants share their new knowledge with colleagues
- Usage of several tools is improved, and new tools are adopted

[Free-form answers](https://coderefinery.org/#what-do-our-participants-say-after-attending-a-workshop) 
also suggest that workshops are having the intended effects on how people develop code. A common theme is:
> *I wish I had known this stuff already as a grad student 10+ years ago...*

We would love to get suggestions on how we can better quantify our impact. This
would make it easier for us to convince institutions to partner with us and
also open up funding opportunities.

---

## Carpentries membership

Since November 2018, [NeIC](https://neic.no) is a [Platinum Partner](https://carpentries.org/members/) to [The Carpentries](https://carpentries.org/).

The Carpentries is an international project that comprises Software Carpentry and Data Carpentry, communities of instructors, trainers, maintainers, helpers,
and supporters who share a mission to teach foundational computational and data science skills to researchers.
The Carpentries teach foundational coding and data science skills to researchers worldwide and as such are complementary to CodeRefinery.

Within the membership the Nordic research community has access to:

- 6 Carpentries workshops in the Nordics each year. The workshop fee is covered by the membership, only the instructor travel is on the host institution.
- 15 seats in the Carpentries instructor training each year. Carpentries train the trainer program aims at building partnerships with Research Software Engineers and researchers who are willing to lead skill transfer within their local communities in the Nordics.

---

## Target audience

### Carpentries audience


The Carpentries aims to teach computational **competence** to learners through an applied approach, avoiding the theoretical and general in favor of the practical and specific. 

**Learners do not need to have any prior experience in programming.**  One major goal of a Carpentry workshop is to raise awareness on the tools researchers can learn/use to speed up their research.

By showing learners how to solve specific problems with specific tools and providing hands-on practice, learners develops confidence for future learning.

> ## Novices
> We often qualify Carpentry learners as **novices**: they do not know what they need to learn yet. A typical example is the usage of version control: the Carpentry `git` lesson aims to give a very high level conceptual overview of Git but it does not explain how it can be used in research projects.
{: .callout}


### CodeRefinery audience

In that sense, CodeRefinery workshops differ from Carpentry workshops as we assume our audience already writes code and scripts and we aim at teaching them **best software practices**.

Our learners usually do not have a good overview of **best software practices** but are aware of the need to learn them. Very often, they know the tools (Git, Jupyter, etc.) we are teaching but have difficulties to make the best use of them in their software development workflow.

Whenever we can, we should direct learners that do not have sufficient coding experience to Carpentries workshops.

> ## Competent practitioners
> We often qualify CodeRefinery learners as **competent practitioners** because they already have an understanding of their needs.
> *Novices* and *competent practitioners* will be more clearly defined in the [next section](../02-teachingstyle).
{: .callout}

>## Best software practices for whom?
>It can be useful to ask the question: *best software practices for whom*? CodeRefinery teaches *best software practices* derived from producing and shipping software. These practices are also very good for sharing software, though our audience will probably not need to embrace *all* aspects of software engineering.
{: .callout}
---

## CodeRefinery training philosophies

Here CodeRefinery instructors share their training philosophy to show that we all have different teaching styles and how these differences are beneficial to CodeRefinery workshops.

It is important to explain how much we value individuals and that there is not one way to teach but as many ways as individuals. We want to help each other to find the way that is best for each of us.

> ## Anne Fouilloux
> 
> I regularly teach Carpentries workshops so I try to apply what I have learnt to CodeRefinery workshops. However, I know our target audience is very much different and that I need to adapt my teaching style. I am still trying to find what works best in which situations and this is why I like so much CodeRefinery workshops. We usually have a wider range of skills and very mixed backgrounds so we usually have to be more careful with the pace and time given for exercises.
> 
> Some considerations:
> - I spend quite a lot of time reading the CodeRefinery material and practising myself exercises. I particularly like to read the instructor notes just before teaching: they usually highlight important aspects both for preparing and teaching. 
> - I usually do not show too much in advance the material as I think it prevents asking questions. If you have less competent practitioners in the classroom, they can easily copy-paste to avoid slowing down the entire classroom.
> - Ideally, I'd like to give several exercises so anyone can work at its own pace. I find it is important that everybody gets something different from the workshop. 
> - I love breaks as it gives us an opportunity to discuss with attendees on their research topics. I am especially interested to understand what software they write and how they plan to use what they learn during our workshops.
{: .challenge}

> ## Bjørn Lindi
>
> My teaching style has changed a bit since I started with CodeRefinery. In the beginning I had this "BLOB" (Binary Large OBject) of knowledge and experience that I wanted to to convey to the participants. With experience and some help from the Carpentries Instructor training, I have realized I need to serialize the "BLOB", to be able to share it with others.
>
>In a similar fashion as you would do with a binary large object which you intend to send over the wire, you will need stop signals, check-sums and re-transmissions, when you give a lecture. I have come to appreciate the natural periods/breaks the lessons offers, the questions raised, the errors that appear during type-along and the re-transmission. Co-instructors are good to use for re-transmission or broadening a specific topic.
>
>When I started with CodeRefinery my inclination was to give a lecture. Today I am trying to be a guide during a learning experience, a learning experience which includes me as well. That may sound a bit self-centric, but is in fact the opposite, as I have to be more sensitive to what is going on in the room. The more conscious I am of being a guide, the better lesson.
>
>Tools that I find useful in preparing a lesson is concept maps and Learner Personas, though I have develop to few them.
>- [Concept Maps](https://teachtogether.tech/#s:memory-concept-maps)
>- [Learner Personas](https://teachtogether.tech/#s:process-personas)
{: .challenge}

> ## Thor Wikfeldt
> 
> I never want to leave any learner behind and I really don't like seeing confused, blank faces in the classroom. 
> At the same time I sometimes worry about some participants getting bored if a lesson is progressing slowly. 
> This is always a difficult compromise and something I struggle with!  
> 
> I try to focus on making concepts intuitive, to "make sense" to the learners. Of course this is usually 
> based on how I learned the topic myself and how it makes sense to me. 
> 
> I try to establish connections between topics: "this thing here is similar to what we saw in the previous 
> lesson where we learned about X...".
> 
> Before mastering a lesson by teaching in many times I try to "follow the script". After becoming very 
> familiar with a lesson I start to improvise more and react more dynamically to questions, e.g. by taking a
> detour to explain a confusing topic more clearly.
> 
> What I think I do too often: copy-paste code/text from lesson material. This can leave learners behind - 
> typing out the code and describing it is slower, but more learning takes place. More advanced learners 
> will hopefully "be compensated" by interesting advanced exercises which follow.
{: .challenge}

> ## Stefan Negru
> 
> A lesson is a conversation, it is useful if both the trainer and the trainee are engaged.
> For that reason I try to have, most of the time, a conversation with the classroom and
> after we finish parts of a lesson, step back and see how we might use what we learned.
>
> That brings me to another point I follow throughout the lessons, answering questions like:
> * How can we apply in practice what we just learned?
> * Do you see yourself (the trainee) using that in practice, why or why not?
>
> Most of the times those seem like open-ended questions to the trainees that just learned
> something new, so I try to find examples, most of the times from personal experience.
>
> Last thing is that analogies are important when I teach, I try to find analogies in order
> to simplify a convoluted part of a lesson.
{: .challenge}

> ## Radovan Bast
>
> My teaching changed by 180 degrees after taking the Carpentries instructor
> training.  Before that I used slides, 45 minute lecture blocks, and separate
> exercise sessions.  After the Carpentries instructor training I embraced the
> interaction, exercises, demos, and typos.
>
> My goal for a lesson is to spark curiosity to try things after the lesson,
> both for the novices ("This looks like a useful tool, I want to try using it
> after the workshop.") and the more experienced participants ("Aha - I did not
> know you could do this. I wonder whether I can make it work with X."). I like
> to start lessons with a question because this makes participants look up from
> their browsers.
>
> Keeping both the novices and the experts engaged during a lesson can be
> difficult and offering additional exercises seems to be a good compromise.
>
> For me it is a good sign if there are many questions. I like to encourage
> questions by asking questions to the participants. But I also try not to go
> into a rabbit hole when I get a question where only experts will appreciate
> the answer.
>
> I try to avoid jargon and "war stories" from the professional developers'
> perspective or the business world. Most researchers may not relate to them.
> For examples I always try to use the research context. Avoid "customer",
> "production", also a lot of Agile jargon is hard to relate to.
>
> Less and clear is better than more and unclear. Simple examples are better
> than complicated examples. Almost never I have felt or got the feedback that
> something was too simple. I am repeating in my head to not use the words
> "simply", "just", "easy". If participants take home one or two points from
> a lesson, that's for me success.
>
> I prepare for the lesson by reading the instructor guide and all issues and
> open pull requests. I might not be able to solve issues, but I don't want to
> be surprised by known issues.  I learn the material to a point where I know
> precisely what comes next and am never surprised by the next episode or
> slide. This allows me to skip and distill the essence and not read bullet
> point by bullet point.
>
> I try to never deviate from the script and if I do, be very explicit about
> it.
>
> A great exercise I can recommend is to watch a tutorial on a new programming
> language/tool you have never used. It can feel very overwhelming and fast to
> get all these new concepts and tools thrown at self. This can prepare me for
> how a participant might feel.
>
> I find it very helpful if there is somebody else in the room who helps me
> detecting when I go too fast or become too confusing. I like when two
> instructors complement each other during a lesson but when doing that to
> others, I am often worried of interrupting their flow and timing too much.
>
> A mistake I often do is to type too fast and in my mind I force myself
> to slow down.
{: .challenge}

> ## Sabry Razick
> My approach is to show it is fun to demystify concepts. Once a concept is
> not a mystery anymore, the learners will understand  is what it means, where
> it is coming from, why it is in place  and what it could it offer for their future.
> I try to relate concepts to real life with a twist of humour whenever possible if
> the outcome is certain not be offensive to any one. I use diagrams whenever possible,
> I have spent weeks creating diagrams that is sometime three or four sentences. That
> effort I consider  worthwhile as my intention is not to teach, but to demystify.
> Once that is achieved, learners will learn the nitty gritty on their own easily
> and with confidence, when they have the use-case.
>
>
{: .challenge}

> ## Juho Lehtonen
> I'm gradually realising the different ways to get a hint wheter the workshop 
> participants are still following or perhaps bored. I assume it's communicating
> with the class, with excercises and simply by asking now and then. I also try
> to remeber to observe how people look like (puzzled, bored) while I teach, not
> so obvious for me.
>
> I believe that learners communicating with each other, in addition to with
> instructors and helpers, really helps them to understand things faster. (At least
> it helps me). So I try to make sure that no one sits or works alone at the workshops.
{: .challenge}

> ## Richard Darst
>
> Like many people, I've often been teaching, but rarely a teacher.  I
> tend to teach like I am doing an informal mentorship.
> I've realized long ago that my most important lessons weren't
> learned in classes, but by a combination of seeing things done by
> friends and independent study after that.  I've realized that
> teaching (the things I teach) is trying to correct these differences
> in backgrounds.
>
> My main job is supporting computing infrastructure, so my teaching
> is very grounded in real-world problems.  I'm often start at the
> very basics, because this is what I see missing most often.
>
> When teaching, I like lots of audience questions and don't mind
> going off-script a bit (even though I know it should be minimized).
> I find that sufficient audience interest allows any lesson to be a
> success - you don't have to know everything perfectly, just show how
> you'd approach a problem.
>
{: .challenge}

> ## João M. da Silva
> 
> I've been a technical instructor for twenty years, and hence my perspective
> is perhaps more inclined towards the development of hands-on abilities and
> capability to solve problems, independently or in a team.
> 
> But the development of hands-on practical skills, requires some eseential
> knowledge about the domain and some willingness to try different approaches.
> Some call this the "KSA approach" ("Knowledge-Skills-Attitude). Hence, I
> try impart the essential knowledge (and where to find out more) at my
> trainings. And to encourage and challenge students in order to make them
> overcome their self-perceived limits (e.g. "I'm a Humanist, I can't use
> Python virtualenv").
>
> I've been trying to study more about the Cognitive aspects of learning over the years,
> and I should find out the time to return to that. There's very interesting
> research in Problem Solving, with Learning being a respective component.
>
> Storytelling: humans are neurologically made for paying attention to good
> stories, and that's something that I try to put into account: to give
> a lesson like it would be a relevant story for the students, one that they
> could relate to.
>
> I like to draw and be creative with that, but have to pay attention to
> my handwritting during my trainings. I reckon that Architectural diagrams
> help students undrstanding the big picture, so I should invest more on
> those when development training material. I would also like to start looking into
> Concept Maps and Semantic Trees in training.
{: .challenge}






{: .challenge}
---

# Goal of this workshop

- Give future instructors the tools and confidence to teach best software practices and tools.
- Increase visibility and exposure of the teaching material.
- Motivate new instructors to take up lessons, remix them, and to contribute.
- Get feedback to improve the material as well as our collaboration model.
- For us to learn how we can support related efforts and collaborate.
- Discuss how we can make this project sustainable beyond 2021.
- Catalyze and form new networks and collaborations of teachers and trainers of practical scientific computing.
