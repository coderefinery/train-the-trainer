---
layout: episode
title: "Carpentries and CodeRefinery approach to teaching"
teaching: 30
exercises: 30
questions:
  - "What pedagogical concepts underpin CodeRefinery and Carpentry workshops?"
  - "How to get and give feedback?"
  - "Who are the CodeRefinery learners?"
  - "Why is it important to define learning objectives?"
objectives:
  - "Explain The Carpentries and CodeRefinery approaches to teaching"
  - "Understand what is meant by feedback, cognitive development, mental models and reverse instructional design"
  - "Explain and practice important pedagogical concepts"
keypoints:
  - "CodeRefinery lessons and teaching build on these principles"
---

# The Carpentries and CodeRefinery approaches to teaching

Here we will give you a very short overview of the Carpentries approach to teaching and highlight
parts that are most important for teaching CodeRefinery style lessons.

Most CodeRefinery instructors have completed the
[Carpentry instructor training workshop](https://carpentries.github.io/instructor-training/), which
[anyone can apply for](https://carpentries.org/become-instructor/) 

> ## This material
>
> This section is derived from the
> [Carpentries instructor training material](https://carpentries.github.io/instructor-training/).
> We encourage you to further study this material later, and to sign up for a 2-day Carpentry
> intructor training workshop.
{: .callout}

---

## Key principles

The "Carpentries" approach to teaching is based on:

- Applying research-based teaching principles, especially as they apply to the Carpentries audience.
- Understanding the importance of a respectful and inclusive classroom environment.


### Carpentries teaching principles

- Learners need to practice what they are learning in real time and get **feedback** on what they are doing. That is why the teaching approach relies on **live coding**.
- Learners best learn in a respectful classroom environment, so the Carpentries use a [Code of Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html).
- Learners are encouraged to help each other during workshops as this improves their confidence and reinforces concepts taught.
- Carpentry instructors try to have learners do something that they think is useful in their daily work within **15 minutes of starting each lesson**.

![What to Teach](https://carpentries.github.io/instructor-training/fig/what-to-teach.png)

In CodeRefinery, we follow The Carpentries teaching principles but in addition to **live coding** we often use **group discussions** to put in context the concepts we are teaching.

Applying these teaching principles are not sufficient and in addition we need to be able to check the effectivness of our methods.

---

## On the importance of feedback

Feedback is an essential part of effective learning. Feedback is bi-directional:
- To be effective, instructors need feedback on their learners' progress. Learners can also check their progress and ask relevant questions to get clarification.
- Instructors also need feedback on their teaching. For instance, this can help them to adapt the pace, add/skip optional exercises and improve their teaching.

### Getting/giving feedback on learners' progress

This feedback comes through what is called *formative assessments* (in contrast
  to *summative assessment*).

> ## Summative Assessment
> *Summative assessment* is used
> to judge whether a learner has reached an acceptable level of competence.
> Usually at the end of a course 
> Learners either "pass" or "fail" a summative assessment.
> One example is a driving exam,
> which tells the rest of society whether someone can safely be allowed on the road. Most assessment done in university
> courses is summative, and is used to assign course grades.
{: .callout}

> ## Formative assessment
> *Formative assessment* takes place during teaching and learning. It sounds like
> a fancy term, but it can be used to describe any interaction or activity
> that provides feedback to both instructors and learners about learners' level of understanding of the
> material. For learners, this feedback can help focus their study efforts. For instructors, it allows them to refocus
> their instruction to respond to challenges that learners are facing.
> Used continuously
{: .callout}

Learners don't "pass" or "fail" formative assessments; they are simply a feedback mechanism.
For example, a music teacher might ask a learner to play a scale very slowly
in order to see whether they are breathing correctly,
and if not, what they should change.

Formative assessment is most useful when it happens frequently (we'll talk about how frequently later)
and when the results are easily interpretable by the learner and instructor.


CodeRefinery uses different instruments to get feedback from learners:

- Surveys: we will discuss about CodeRefinery pre/post-surveys in the episode
  [Running workshops](https://coderefinery.github.io/instructor-training/05-operations/).
- Exercises: we have many exercises during CodeRefinery workshops and use polls too but not necessarily many multiple-choice questions. 
  This is something that we may change in the future but the initial reason was that we build on existing knowledge 
  (see below section on our target audience) and give recommendations for best software practices:
  there is no unique solution and you would like our learners to choose the approach that is most suitable for them.
  For the same reasons, we have many optional exercises to accommodate the different levels. 
  We would like everyone to get something useful out of the CodeRefinery workshops.

### Getting/giving feedback on teaching

Teaching is a skill. One of the objective of the CodeRefinery Instructor training is to give you 
the confidence in teaching CodeRefinery lessons. Later we will have group work where we will 
practice teaching some lessons.

Before doing so, we will learn here to give feedback on teaching using the same 
positive-vs-negative and content-vs-presentation rubric.

> ## Give feedback on teaching (optional, 10 mn)
> This exercise aims at learning to give feedback. It is optional as we have 
> similar exercises when [practising teaching](https://coderefinery.github.io/instructor-training/08-teaching/).
> As a group, we will watch [this video of teaching](https://www.youtube.com/watch?v=-ApVt04rB4U) and
> give feedback on two axes: positive vs. negative and content vs. presentation. Have each person in
> the class add one point to a 2x2 grid on a whiteboard or in the shared notes  (hackMD, etherpad, google doc) without duplicating any points.
> For online instructor training event, use breakout room (4-5 persons per group) to facilitate discussion. Then each group reports to the shared notes.
> You can use a [rubric](http://carpentries.github.io/instructor-training/demos_rubric/) (used during The Carpentries teaching demos) to help you take notes.
> What did other people see that you missed? What did they think that you strongly agree or disagree with?
>
{: .challenge}

---

## Who are the learners

The first task in teaching is to figure out who your learners are. The Carpentries approach is based on the work of researchers like [Patricia Benner](https://en.wikipedia.org/wiki/Patricia_Benner), who applied the [Dreyfus model of skill acquisition](https://en.wikipedia.org/wiki/Dreyfus_model_of_skill_acquisition) in her studies of [how nurses progress from novice to expert](http://journals.sagepub.com/doi/10.1177/0270467604265061) ([see also books by Benner](https://www.worldcat.org/search?q=au%3ABenner%2C+Patricia+E.&qt=hot_author)). This work indicates that through practice and formal instruction, learners acquire skills and advance through distinct stages. In simplified form, the three stages of this model are:

### Novices, competent practitioners and experts

![Novice, Competent Practitioner, Expert](https://carpentries.github.io/instructor-training/fig/skill-level.svg)

*   *Novice*: someone who doesn't know what they don't know, i.e.,
    they don't yet know what the key ideas in the domain are or how they relate.
    One sign that someone is a novice is that their questions "aren't even wrong".

     > Example: A *novice* learner in a Carpentries workshop might never have heard of the bash 
       shell, and therefore may have no understanding of how it relates to their file system or
       other programs on their computer.
     > Example HPC: A learner who has never executed a program on remote computer in headless mode
     > Example HPC: A learner who has no understanding about using a queue system and having a 
       hard time why a program can not be run directly after login in. 

*   *Competent practitioner*: someone who has enough understanding for everyday purposes. 
    They won't know all the details of how something works and their understanding may not
    be entirely accurate, but it is sufficient for completing normal  tasks with normal 
    effort under normal circumstances.

    > Example: A *competent practitioner* in a Carpentries workshop might have used the shell 
      before and understand how to  move around directories and use individual programs, but
      they might not understand how they can fit these programs together to build scripts
      and automate large tasks.
    > Example: A *competent practitioner* in a CodeRefinery workshop is someone that understands
      the concepts of best software practices and its importance. He/she clearly sees the
      benefits of applying best software practices but he/she does not fully know yet how and 
      what to use for their own projects.
    > Example HPC: Knows how to establish a connection to a cluster and have submitted jobs.
      But may not know how to request optimal amount of resources in a job or parallel processing

*   *Expert*: someone who can easily handle situations that are out of the ordinary.
    > Example: An *expert* in a Carpentries workshop may have experience writing and running shell
      scripts and, when presented with a problem, immediately sees how these skills can be used 
      to solve the problem.
    > Example HPC: A learner who has a good understanding of the queue system, parallel processing
      and understand how to interpret error reports when something goes wrong and knows how to 
      get help. 


### Cognitive Development and Mental Models

Effective learning is facilitated by the creation of a well-founded mental model. A mental model
is a collection of concepts and facts, along with the relationships between those concepts, which 
a person has about a topic. For example, a long-time resident of the United States may have an 
advanced understanding of the location of US states, major cities and landmarks, weather patterns,
regional economies and demographic patterns, as well as the relationships among these, compared 
with their understanding of these relationships for other countries. In other words, their mental
model of the United States is more complex compared with their mental model of other countries.

We can distinguish between a *novice* and a *competent
practitioner* for a given domain based on the complexity of their mental models.

*     A *novice* is someone who has not yet built a mental model of the domain.
      They therefore reason by analogy and guesswork, borrowing bits and pieces 
      of their mental models of other domains  which seem superficially similar.
*     A *competent practitioner* is someone who has a mental model that's good enough 
      for everyday purposes. This model does not have to be completely accurate in order 
      to be useful: for example, the average driver's mental model of how a car works 
      probably doesn't include most of the complexities that a mechanical engineer 
      would be concerned with.

We could expect a mixture of learners from *novice* and *competent practitioner* groups
in HPC training events. 

![Mental Models](https://carpentries.github.io/instructor-training/fig/mental_models.svg)

---

### How “knowledge” gets in the way

Mental models are hardly ever built from scratch. Every learner comes to a topic with some amount of information, ideas and opinions about the topic. This is true even in the case where a learner can’t articulate their prior knowledge and beliefs.

In many cases, this prior knowledge is incomplete or inaccurate. Inaccurate beliefs can be termed “misconceptions” and can impede learning by making it more difficult for learners to incorporate new, correct information into their mental models. Correcting learners’ misconceptions is at least as important as presenting them with correct information. Broadly speaking, misconceptions fall into three categories:

- **Simple factual errors**, such as believing that Vancouver is the capital of British Columbia. These are the easiest to correct.
- **Broken models**, such as believing that motion and acceleration must be in the same direction. We can address these by having learners reason through examples to see contradictions.
- **Fundamental beliefs**, such as “the world is only a few thousand years old” or “human beings cannot affect the planet’s climate”. These beliefs are deeply connected to the learner’s social identity and are the hardest to change.


CodeRefinery workshops are aimed for researchers and/or Research Software Engineers or anyone who codes (in any programming language) on a regular basus. In that sense, our learners are not novices but **competent practitioners**.

They often use version control, write code in different programming languages and very often are familiar with the command line. Some have attended Carpentries workshops but very often developed their programming skills on their own. Therefore, they may have misconceptions. That is why it is important to get accurate feedback.

> ## How to handle novices in CodeRefinery workshops
>
> - We have a few prerequisites for attending CodeRefinery workshops but those are mostly recommendations (we do not have any assessment at registration). It is very common to have a few learners that never used version control and do not code on a regular basis. Even though we are trying our best to support them during CodeRefinery workshops and give them an overview of best software practices, we do not focus our attention to these learners.
> - We recommend (at the beginning of a CodeRefinery workshop) to clearly remind the CodeRefinery target audience about the prerequisites. This will clearly help you and the helpers during the workshop and make sure you do not demotivate potential learners.
>
{: .callout}

> ## Exercise: Carpentries versus CodeRefinery audience
>
> Split into groups (3 to 4 persons). Discuss and summarize in the hackmd pad:
> 1. Why does CodeRefinery target **competent practitioner**?
> 2. Why is it important to be able to write code for attending a CodeRefinery workshop?
> For this exercise, we suggest to read [Motivation and Demotivation](https://carpentries.github.io/instructor-training/08-motivation/index.html) from the Carpentries instructor training lesson.
{: .challenge}

---

## CodeRefinery Curriculum and Reverse Instructional Design

When writing a CodeRefinery lesson, we take a “reverse” approach to instruction, as advanced in Wiggins and McTighe’s [Understanding by Design](http://www.worldcat.org/title/understanding-by-design/oclc/56491025), that keeps the focus firmly on learning outcomes. The order of preparation in this case becomes

- Determine your learning objectives
- Decide what constitutes evidence that objectives have been met, and design assessments to target that evidence
- Design instruction: Sort assessments in order of increasing complexity, and write content that connects everything together

### Working with learning objectives

Each CodeRefinery lesson usually has a *learning objectives* section. 

Good learning objectives are quite specific about the intended effect of a lesson on its learners. We aim to create learning objectives that are specific, accurate, and informative for both learners and instructors.


### Using Bloom's Taxonomy to write effective learning objectives

[Bloom's Taxonomy](https://cft.vanderbilt.edu/guides-sub-pages/blooms-taxonomy/) is a framework for thinking about learning that breaks progress down into discrete, hierarchical steps.
While many ideas have come and gone in education, Bloom's has remained a useful tool for educators, in particular because the
hierarchy seems to be reasonably valid: outcomes at the top of the hierarchy cannot be achieved without mastery of outcomes at
the bottom. In the long term, everybody wants to be at the top. However, in aiming to meet learners where they are, we also
need to be mindful about helping them to ["grow a level,"](https://software-carpentry.org/blog/2018/03/tractenberg-summary.html) helping them to recognize when they have achieved that growth, and
guiding them to look ahead to where we might not be able to take them.

![Bloom's Taxonomy](https://carpentries.github.io/instructor-training/fig/Blooms.png)

Image credit: Vanderbilt University Center for Teaching

### Revisiting Learning objectives

When using existing teaching material, *reverse instructional design*  principles might be applied as
follows:

1. Review the lesson's learning objectives carefully, thinking about how they will work for your audience
2. Scan the lesson to identify promising points to check in with your learners, using formative assessment to verify that objectives have been met
3. Review the connecting content in detail to be sure everything works and you have anticipated likely problems and questions.


We strongly encourage you to read them before teaching a CodeRefinery lesson and to review whether they still match the content of the lesson: CodeRefinery lessons are regularly updated, taking into account feedback from our learners and instructors.

