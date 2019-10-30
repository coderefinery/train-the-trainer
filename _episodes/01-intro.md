---
layout: episode
title: "CodeRefinery project and teaching style"
teaching: 60
exercises: 30
questions:
  - "What is CodeRefinery?"
  - "How does CodeRefinery relate to the Carpentries?"
  - "What pedagogical concepts underpin both CodeRefinery and Carpentry workshop?"
  - "What are the main goals of CodeRefinery workshops?"
  - "What is the target audience?"
  - "What is our training philosophy?"
  - "What is usually taught in a CodeRefinery workshop?"
objectives:
  - "Explain and practice important pedagogical concepts"
  - "Discuss main goals of CodeRefinery workshops"
  - "Discuss differences between CodeRefinery and the Carpentries"
  - "Discuss the CodeRefinery training philosophies"
  - "Give an overview of CodeRefinery lessons"
keypoints:
  - "CodeRefinery teaches best practices for research software development"
  - "CodeRefinery workshops benefit most those who already code"
  - "CodeRefinery lessons are programming language-independent"
  - "CodeRefinery complements The Carpentries curriculum"
---

# Welcome

# CodeRefinery goals

CodeRefinery is a [Nordic e-Infrastructure Collaboration (NeIC)](https://neic.no/) project that has started in October 2016 and will end in October 2021.

The project has four main goals:

- Develop and maintain training material on software best practices for researchers that already write code. Our material addresses all academic disciplines and tries to be as programming language-independent as possible.
- Provide a [code repository hosting service](https://coderefinery.org/repository/) that is open and free for all researchers based in universities and research institutes from Nordic countries
- Provide training opportunities in the Nordics using Carpentries and CodeRefinery training materials
- Articulate and implement the CodeRefinery sustainability plan

This instructor training lesson aims at increasing the number of CodeRefinery instructors hence contributes to the project sustainability.

## Carpentries membership

One important challenge of CodeRefinery is to become sustainable by the end of the project. To be able to maintain and develop further CodeRefinery lessons, it is important to have a sufficient number of qualified instructors and maintainers. 

Since November 2018, [NeIC](https://neic.no) is a [Platinum Partner](https://carpentries.org/members/) to [The Carpentries](https://carpentries.org/).

The Carpentries teaches foundational coding and data science skills to researchers worldwide and as such is complementary to CodeRefinery. 
an international successful project that comprises Software Carpentry and Data Carpentry, communities of Instructors, Trainers, Maintainers, helpers, 
and supporters who share a mission to teach foundational computational and data science skills to researchers. With this we have access to:

- 6 Carpentries workshops in the Nordics each year. The workshop fee is on us, only the instructor travel is on the host institution.
- 15 seats in the Carpentries instructor training each year. Carpentries train the trainer program aims at building partnerships with Research Software Engineers and researchers who are willing to lead skills' transfer within their local communities in the Nordics.

# Carpentries approach to teaching

**This section is copied from [the Carpentries instructor training material](https://carpentries.github.io/instructor-training/).**

We will give you a short overview of the Carpentries approach to teaching and highlight parts that are most important for teaching CodeRefinery lessons.

In the "Carpentries" approach to teaching, emphasis is put on:

- Applying research-based teaching principles, especially as they apply to the Carpentries audience.
- Understanding the importance of a respectful and inclusive classroom environment.


Before going into details, let's summarize the Carpentries teaching principles:

- Learners need to practice what they are learning in real time and get feedback on what they are doing. That is why Carpentries teaching approach uses **live coding**.
- Learners best learn in a respectful and classroom enviromment. They can help each others during the workshops as it also improves their confidence and reinforce concepts taught. The Carpentries has put in place a [Code of Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html). The Carpentries try to have learners do something that they think is useful in their daily work within 15 minutes of starting each lesson. 

![What to Teach](https://carpentries.github.io/instructor-training/fig/what-to-teach.png)

And now let's formalize the Carpentries teaching approach.

## Why feedback is important?

Feedback is an essential part of effective learning. To be effective, instructors need feedback on their learners' progress. This feedback comes through what we call *formative assessments* (in contrast
  to *summative assessment*).

> ## Summative Assessment
> *Summative assessment* is used
> to judge whether a learner has reached an acceptable level of competence.
> Learners either "pass" or "fail" a summative assessment.
> One example is a driving exam,
> which tells the rest of society whether someone can safely be allowed on the road. Most assessment done in university
> courses is summative, and is used to assign course grades.
{: .callout}

*Formative assessment* takes place during teaching and learning. It sounds like
a fancy term, but it can be used to describe any interaction or activity
that provides feedback to both instructors and learners about learners' level of understanding of the
material. For learners, this feedback can help focus their study efforts. For instructors, it allows them to refocus
their instruction to respond to challenges that learners are facing.  

Learners don't "pass" or "fail" formative assessments; they are simply a feedback mechanism.
For example, a music teacher might ask a learner to play a scale very slowly
in order to see whether they are breathing correctly,
and if not, what they should change.

Formative assessment is most useful when it happens frequently (we'll talk about how frequently later) and when the
results are easily interpretable by the learner and instructor.

> ## Exercise: Give Feedback on Bad Teaching
> As a group, watch [this video of bad teaching](https://www.youtube.com/watch?v=-ApVt04rB4U) and 
> give feedback on two axes: positive vs. negative and content vs. presentation. Have each person in 
> the class add one point to a 2x2 grid on a whiteboard or in the shared notes without duplicating any points.
> What did other people see that you missed? What did they think that you strongly agree or disagree with?
>
{: .challenge}

## Mental Models and Formative Assessment

The first task in teaching is to figure out who your learners are. The Carpentries approach is based on the work of researchers like [Patricia Benner](https://en.wikipedia.org/wiki/Patricia_Benner), who applied the [Dreyfus model of skill acquisition](https://en.wikipedia.org/wiki/Dreyfus_model_of_skill_acquisition) in her studies of [how nurses progress from novice to expert](http://journals.sagepub.com/doi/10.1177/0270467604265061) ([see also books by Benner](https://www.worldcat.org/search?q=au%3ABenner%2C+Patricia+E.&qt=hot_author)). This work indicates that through practice and formal instruction, learners acquire skills and advance through distinct stages. In simplified form, the three stages of this model are:

## Novices, Competent practitioners and experts

![Novice, Competent Practitioner, Expert](https://carpentries.github.io/instructor-training/fig/skill-level.svg)

*   *Novice*: someone who doesn't know what they don't know, i.e.,
    they don't yet know what the key ideas in the domain are or how they relate.
    One sign that someone is a novice is that their questions "aren't even wrong".

     > Example: A *novice* learner in a Carpentries workshop might never have heard of the bash shell, and therefore
     may have no understanding of how it relates to their file system or other programs on their computer.

*   *Competent practitioner*: someone who has enough understanding for everyday purposes. They won't know all the details
    of how something works and their understanding may not be entirely accurate, but it is sufficient for completing normal
    tasks with normal effort under normal circumstances.

    > Example: A *competent practitioner* in a Carpentries workshop might have used the shell before and understand how to
    move around directories and use individual programs, but they might not understand how they can fit these programs
    together to build scripts and automate large tasks.

*   *Expert*: someone who can easily handle situations that are out of the ordinary.

    > Example: An *expert* in a Carpentries workshop may have experience writing and running shell scripts and, when
    presented with a problem, immediately sees how these skills can be used to solve the problem.

## Cognitive Development and Mental Models

Effective learning is facilitated by the creation of a well-founded mental model. A mental model is a collection of concepts and facts,
along with the relationships between those concepts, which a person has about a topic. For example, a long-time resident of the United
States may have an advanced understanding of the location of US states, major cities and landmarks, weather patterns, regional
economies and demographic patterns, as well as the relationships among these, compared with their understanding of these relationships
for other countries. In other words, their mental model of the United States is more complex compared with their mental model of other
countries.

We can distinguish between a *novice* and a *competent
practitioner* for a given domain based on the complexity of their mental models.

*     A *novice* is someone who has not yet built a mental model of the domain.
They therefore reason by analogy and guesswork,
borrowing bits and pieces of their mental models of other domains
which seem superficially similar.
*     A *competent practitioner* is someone who has a mental model that's good enough for everyday purposes. This model
does not have to be completely accurate in order to be useful:
for example, the average driver's mental model of how a car works probably doesn't include
most of the complexities that a mechanical engineer would be concerned with.

![Mental Models](https://carpentries.github.io/instructor-training/fig/mental_models.svg)

# Carpentries and CodeRefinery target audience

## Carpentries audience

The carpentries is primarily concerned with **novices**. 

It aims to teach computational **competence** to learners through an applied approach, avoiding the theoretical and general in favor of the practical and specific. 
By showing learners how to solve specific problems with specific tools and providing hands-on practice, learners develops confidence for future learning.

## CodeRefinery audience

In that sense, CodeRefinery differs significantly as we assume our audience already write codes and we aims at teaching them **best software practices**.

Our target audience is a *competent practitioner** writing codes on a regular basis but that usually does not have a good overview of **best software practices**.

Whenever we can, we direct **novices** to Carpentries workshops.

## How “Knowledge” Gets in the Way

Mental models are hardly ever built from scratch. Every learner comes to a topic with some amount of information, ideas and opinions about the topic. This is true even in the case where a learner can’t articulate their prior knowledge and beliefs.

In many cases, this prior knowledge is incomplete or inaccurate. Inaccurate beliefs can be termed “misconceptions” and can impede learning by making it more difficult for learners to incorporate new, correct information into their mental models. Correcting learners’ misconceptions is at least as important as presenting them with correct information. Broadly speaking, misconceptions fall into three categories:

- Simple factual errors, such as believing that Vancouver is the capital of British Columbia. These are the easiest to correct.
- Broken models, such as believing that motion and acceleration must be in the same direction. We can address these by having learners reason through examples to see contradictions.
- Fundamental beliefs, such as “the world is only a few thousand years old” or “human beings cannot affect the planet’s climate”. These beliefs are deeply connected to the learner’s social identity and are the hardest to change.


CodeRefinery workshops target **competent practioners** that write code on a regular basis so we very often have learners with misconceptions. That is why it is important to get accurate feedback.

> ## Exercise: Carpentries versus CodeRefinery audience
>
> Split into groups (3 to 4 persons). Discuss and summarize in the etherpad:
> 1. Why does CodeRefinery target **competent practitioner**? 
> 2. Why is it important to be able to write code for attenting a CodeRefinery workshop? 
> For this exercise, we suggest to read [Motivation and Demotivation](https://carpentries.github.io/instructor-training/08-motivation/index.html) from the Carpentries instructor training lesson.
{: .challenge}

## CodeRefinery training philosophies

Here CodeRefinery instructors share their training philosophy. The main goal is to show that we all have different teaching styles and how these differences are beneficial to CodeRefinery workshops.

It is important to explain how much we value individuals and that there is not one way to teach but as many ways as individuals. The goal is to help each others to find the way that is best for each of us.

### Anne Fouilloux

I regularly teach Carpentries workshops so I try to apply what I have learnt to CodeRefinery workshops. However, I know our target audience is very much different and that I need to adapt my teaching style. I am still trying to find what works best in which situations and this is why I like so much CodeRefinery workshops. We usually have a wider range of skills and very mixed backgrounds so we usually have to be more careful with the pace and time given for exercises.

Some considerations:
- I spend quite a lot of time reading the CodeRefinery material and practising myself exercises. I particularly like to read the instructor notes just before teaching: they usually highlight important aspects both for preparing and teaching. 
- I usually do not show too much in advance the material as I think it prevents asking questions. If you have less competent practitioners in the classroom, they can easily copy-paste to avoid slowing down the entire classroom.
- Ideally, I'd like to give several exercises so anyone can work at its own pace. I find it is important that everybody gets something different from the workshop. 
- I love breaks as it gives us an opportunity to discuss with attendees on their research topics. I am especially interested to understand what software they write and how they plan to use what they learn during our workshops.


# CodeRefinery lessons and workshop

## What is a CodeRefinery workshop?

In this section, we explain briefly what is a CodeRefinery workshop and in particular how much we can mix and match lessons for new workshops.

Practical information on how to organize a workshop will be given later.

All our [CodeRefinery teaching material](https://coderefinery.org/lessons/) is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Code examples: [OSI](http://opensource.org/)-approved [MIT license](http://opensource.org/licenses/mit-license.html). You are free to use this material, but please [let us know](https://coderefinery.org/contact/) - it is important for us to know whether this material has impact outside of our workshops.

We usually run our workshops in 3 days and to get an overview of a typical CodeRefinery workshop, look at the programme  [here](https://coderefinery.org/workshops/2019-10-22-trondheim/).

However, anyone is free to mix and match to define its own CodeRefinery programme.

## Reverse Instructional Design


When writing curriculum, it is easy to allow *content*
objectives to distract from *learning* objectives. It is especially true for CodeRefinery material as we do not target novices but competent practitioners. So for all our lessons, we try to take a "reverse" approach to instruction, as
advanced in Wiggins and McTighe's *[Understanding by Design](http://www.worldcat.org/title/understanding-by-
design/oclc/56491025)*, that keeps the focus firmly on learning outcomes. The order of preparation in this case becomes

1.  Determine your learning objectives
2.  Decide what constitutes evidence that objectives have been met, and design assessments to target that evidence
3.  Design instruction: Sort assessments in order of increasing complexity, and write content that connects everything together


### Working With Learning Objectives

Each CodeRefinery lesson usually has a *learning objectives* section.

The "learning objectives" section is an easy thing to pass over when you're preparing to teach. It may seem obvious or
unnecessary. However, good learning objectives are quite specific about the intended effect of a lesson on its learners. We
aim to create learning objectives that are specific, accurate, and informative for both learners and instructors.

[Bloom's Taxonomy](https://cft.vanderbilt.edu/guides-sub-pages/blooms-taxonomy/) is a framework for thinking about learning that breaks progress down into discrete, hierarchical steps.
While many ideas have come and gone in education, Bloom's has remained a useful tool for educators, in particular because the
hierarchy seems to be reasonably valid: outcomes at the top of the hierarchy cannot be achieved without mastery of outcomes at
the bottom. In the long term, everybody wants to be at the top. However, in aiming to meet learners where they are, we also
need to be mindful about helping them to ["grow a level,"](https://software-carpentry.org/blog/2018/03/tractenberg-summary.html) helping them to recognize when they have achieved that growth, and
guiding them to look ahead to where we might not be able to take them.

![Bloom's Taxonomy](https://carpentries.github.io/instructor-training/fig/Blooms.png)

Image credit: Vanderbilt University Center for Teaching

When using existing teaching material, *reverse instructional design*  principles might be applied as
follows: 1) review the lesson's learning objectives carefully, thinking about how they will work for your audience, 2) scan
the lesson to identify promising points to check in with your learners, using formative assessment to verify that objectives have been met, and then 3) review the connecting content in detail to be sure everything works and you have anticipated likely problems and questions.

### Lightning overview of all lessons 

Details on lessons will be given later, so here we mostly give a very short overview of each CodeRefinery lesson.

> ## Exercise: Learning objectives
> Split in group of 3-4 persons and choose one of the presented CodeRefinery lesson.
> 1. Give feedback on two axes: positive vs. negative and content vs. presentation.
> 1. Discuss the learning objectives and how they fit to CodeRefinery objectives that are to improve researcher's best software practices.
>
{: .challenge}
