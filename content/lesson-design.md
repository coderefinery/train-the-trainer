---
layout: episode
title: "Lesson design"
teaching: 15
exercises: 45
questions:
  - "How can you design new lessons?"
keypoints:
  - "The backwards lesson design process increases quality and relevance for the learners"
  - "We have checklists for reviewing existing lessons and creating new lessons"
---

## Lesson design

> ## Recommended reading
>
> We will extensively refer to the CodeRefinery [lesson-design](https://github.com/coderefinery/manuals/blob/master/lesson-design.md)
> manual
> and the [lesson-review](https://github.com/coderefinery/manuals/blob/master/lesson-review.md) checklist.
>
> We also use and recommend to read [The Carpentries Curriculum Development Handbook](https://cdh.carpentries.org).
{: .prereq}


### Backwards lesson design

Previously, we've talked about the general concept of how to design
lessons to match learners.  Here, we will go through a practical
process.

The basic idea is called **backwards lesson design**.
- You don't think about how to do something and try to explain it.
- Avoid the typical approach *"I want to show a number of things which I think are cool about
  tool X - how do I press these into 90 minutes?"*
- Instead, you start with **learner personas**, and think of what is
  **useful to them**: *"What do I want them to be able to remember/understand/apply/analyze/evaluate/create?"*.
  Then, you create a sequence of exercises which test
  incrementally progressing tasks.
- Then, you write the minimum amount
  of material to teach the gap between exercises.

Why is it good to have a process?:

* Having a semi-rigid design process **saves time** (hopefully).
* It can increase quality.
* It will probably increase relevance of lessons for learners.
* **We aren't perfect yet.**  CodeRefinery is still striving to get
  better at this, and we are more ad-hoc than you might think.
  A number of our lessons have not been designed this way but we are now improving
  these lessons with the backwards lesson design in mind.

The whole process (copied from
[lesson-design](https://github.com/coderefinery/manuals/blob/master/lesson-design.md))
is:

1. Brainstorm what you want to cover.
2. Create or reuse learner personas - understand who you want to
   teach.  What do they care about?  Perhaps as important is what they
   don't care about: make sure that you don't go too in depth too
   early and turn people off.
3. Create some summative assessments, that show what learners should
   learn by the end.  Try to connect these to the learner personas.
4. Create formative assessments (exercises) that let the learners
   practice what you want them to learn.  See below for hints on coming
   up with good exercises.  These should also connect to things the
   learners will actually do, but can also be more of checkpoints.
5. Put exercises in a logical order, and fill in any gaps.  Ideally
   there should be 15-20 min of teaching between each exercise.  Perhaps
   most are short (a few longer examples as needed), to identify a
   certain learning goal and misconception.
6. Write just enough material to get from one exercise to the other.

When designing exercises, consider that some participants will get stuck
and may want to re-join at a later exercise. In other words it is nice
if exercises build up on each other but not at the cost that if participants
get stuck at exercise 2, they will not be able to do exercises 3 to N.

> ## Practice backwards design
>
> Choose a simple lesson topic and apply backwards lesson design.  You
> won't get all the way through, but come up with a logical
> progression of exercises.
>
> Some suggestions:
> - Regular expressions
> - Making papers in LaTeX
> - Making figures in your favorite programming language
> - Linux shell basics
> - Something non-technical, such as painting a room
> - An instructor training for CodeRefinery
> - Some aspect from an already existing lesson
> - A lesson you always wanted to teach
> - A lesson you plan to teach this autumn (maybe independently of Carpentries and CodeRefinery)
>
> Exercise (30 minutes):
> - Collect notes in a shared document.
> - Start with learner personas and learning outcomes.
> - Come up with a logical progression of exercises.
>
> Discussion (15 minutes):
> - How does this approach compare to other lessons or courses you have designed?
> - We read, compare, and discuss our notes.
{: .challenge}
