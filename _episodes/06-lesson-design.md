---
layout: episode
title: "Lesson design and lesson development"
teaching: 15
exercises: 45
questions:
  - "How can you improve and contribute to CodeRefinery lessons?"
  - "How can you design new lessons?"
keypoints:
  - "The backwards lesson design process increases quality and relevance for the learners"
  - "We have checklists for reviewing existing lessons and creating new lessons"
---

## Lesson design and lesson development

In this episode we first discuss **backwards lesson design**, then we go over a
process of **contributing to existing lessons** (that's easier and is done more often).
Then, the process of **creating new lessons**.

- [Backwards lesson design](#backwards-lesson-design)
- [Contributing to existing lessons](#contributing-to-existing-lessons)
- [Creating new teaching material](#creating-new-teaching-material)
- [Technical aspects](#technical-aspects)


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
>
> How does this compare to other lessons or courses you have designed?
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

---

### Contributing to existing lessons

Our lessons are **collaboratively developed**.  They are made by many
people, and there is no single fixed master plan (but there should be,
in the instructors or maintainer's guide).  We encourage
everyone to contribute to the lessons.

Lessons are reviewed very often - essentially, before each workshop by
the instructor of that workshop.  This can be a quick review, looking
at issues and fixing easy things, or more thorough.

Every so often (such as at this training), there is an extensive
hackathon period of fully revising a lesson and making major improvements.

We've made the [lesson-review](https://github.com/coderefinery/manuals/blob/master/lesson-review.md) checklist
to guide the review process.

> ## Discussion
>
> We now go to the
> [lesson-review](https://github.com/coderefinery/manuals/blob/master/lesson-review.md)
> checklist (link above) and discuss it, instead of duplicating things here.
{: .discussion}

---

### Creating new teaching material

Creating new teaching material is a longer process, because you should
go through the whole backwards lesson design process and get extensive
comments.  Still, don't feel afraid: nothing is perfect (or even good)
the first time. In fact, **it may be an advantage to share an imperfect
lesson with others early** to collect feedback and suggestions before the lesson
"solidifies" too much. Draft it and collect feedback. The result will probably
be better than working in isolation towards a "perfect" lesson.

We should use the backwards lesson design process, mentioned above.  This is
extensively discussed in the chapter ["A lesson design process"](https://teachtogether.tech/#s:process)
of the book "Teaching Tech Together", but we have a
shorter summary for quicker reference and discussion in the CodeRefinery
[lesson-design](https://github.com/coderefinery/manuals/blob/master/lesson-design.md) manual.

---

### Technical aspects


#### Existing lessons

There is not much special to say about contributing to existing
lessons: they are public and open [repositories on GitHub](https://github.com/coderefinery).
Make issues and pull
requests (PR) about ideas and improvements.

* It's OK to make issues/PRs about ideas or things still under
  discussion.
* If you see an open pull request, don't be afraid to comment and
  merge!
* Avoid merging own pull requests.

You can most likely figure out how the different pages work.  In
short:
* `_episodes/` contains the markdown files of each episode, which get
  automatically assembled.  There is YAML metadata at the top of
  each.
* `index.md` is the main page, `guide.md` is the instructor's guide,
  and `reference.md` is the learner's reference guide.

For substantial changes we recommend to first open an issue and describe your
idea and collect feedback before you start with an extensive rewrite.


#### New lessons

Again, lessons are developed on [GitHub](https://github.com/coderefinery).

To get started, we recommend to [generate a copy](https://github.com/coderefinery/example-lesson/generate)
from the example [lesson template](https://github.com/coderefinery/example-lesson).

After creating the new lesson repository, adapt `_config.yml`.

Note that the [lesson template](https://github.com/coderefinery/example-lesson) contains
the repository [jekyll-common](https://github.com/coderefinery/jekyll-common) as Git submodule.
We do this to have one repository with common layout and styling and to make it relatively
easy to update lesson repositories after layout or styling changes.
