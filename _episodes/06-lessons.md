---
layout: episode
title: "Contributing to lesson development"
teaching: 30
exercises: 20
questions:
  - "How can you contribute to CodeRefinery lessons?"
  - "How can you create new lessons?"
objectives:
  - "Learn how to contribute to CodeRefinery."
  - "Discuss on important steps for designing a new lesson."
keypoints:
  - "Technical aspects related to CodeRefinery lesson material"
  - "Backwards lesson design process"
---

> ## Remark
> We will extensively refer to [CodeRefinery manual on lesson
> design](https://github.com/coderefinery/manuals/blob/master/lesson-design.md)
> and [CodeRefinery checklist on lesson
> review](https://github.com/coderefinery/manuals/blob/master/lesson-review.md)
>
> More useful documentation from [The Carpentries Curriculum Development Handbook](https://cdh.carpentries.org/)
{: .callout}


## Backwards lesson design

Previously, we've talked about the general concept of how to design
lessons to match learners.  Here, we will go through a practical
process.

* Having a semi-rigid design process **saves time** (hopefully).  This
  is one of the main reasons we have written so much here, not because
  we want to control everything.
* It can increase quality and ensure that you don't forget some of the
  important design considerations
* It can make review faster.
* **We aren't perfect yet.**  CodeRefinery is still striving to get
  here, and are more ad-hoc than you might think.

First, we go over a process of reviewing existing lessons.  Then, a
process of creating new lessons.


## Contributing to existing CodeRefinery lessons

Our lessons are collaboratively developed.  They are made by many
people, and there is no single fixed master plan.  Thus, we encourage
everyone to contribute to the lessons.

The simplest method is to file issues and open pull requests.  This is
rather obvious and the process is covered in CodeRefinery git
lessons.  The remainder of this section goes over a checklist of
things to consider when revising lessons.


### Contribution process

We've made [the
lesson-review checklist](https://github.com/coderefinery/manuals/blob/master/lesson-review.md)
to guide the review process.

Lessons are reviewed very often - essentially, before each workshop by
the instructor of that workshop.  This can be a quick review, looking
at issues and fixing easy things, or more thorough.

Every so often (such as at this training), there is an extensive
hackathon period of fully revising a lesson and making major improvements.

We now go to teh lesson-review checklist and discuss it, instead of
duplicating things here.


### Technical aspects

There is not much special to say about contributing to existing
lessons: it is an open project on Github.  Make issues and pull
requests about ideas and improvements.

* It's OK to make issues/PRs about ideas or things still under
  discussion.
* If you see an open pull request, don't be afraid to comment and
  merge!

You can most likely figure out how the different pages work.  In
short:
* `_episodes/` contains the markdown files of each episode, which get
  automatically assembled.  There is YAML metadata at the top.
* `index.md` is the main page, `guide.md` is the instructor's guide,
  and `reference.md` is the learner's reference guide.


## Creating new teaching material

Creating new teaching material is a longer process, because you should
go through the whole backwards lesson design process and get extensive
comments.  Still, don't feel afraid: nothing is perfect (or even good)
the first time.


### Conceptual approach

We should use the backwards lesson design process.  This is
extensively discussed in a [chapter of the book Teaching Teach
Together ("A lesson design
process")](https://teachtogether.tech/#s:process), but we have a
shorter summary for quicker reference and discussion in [the
coderefinery lesson-design
manual](https://github.com/coderefinery/manuals/blob/master/lesson-design.md).

Instead of duplicating information here, we will directly discuss the
design process with the CodeRefinery manual.


### Technical aspects

Again, lessons are developed on Github.

Copy the workshop repository template (TODO: where is it).

## Backwards design exercise

> ## Practice backwards design
>
> Choose a simple lesson topic and apply backwards lesson design.  You
> won't get all the way through, but come up with a logical
> progression of exercises.
>
> Some suggestions:
> - Regular expressions
> - Making papers in LaTeX
> - Making figures in your favorite programming language.
> - Linux shell basics
> - Something non-technical, such as painting a room
> - An instructor training for CodeRefinery
>
> How does this compare to other lessons you have designed?
>
{: .challenge}

> ## Backwards lesson design in practice (advanced)
>
> Was this instructor training material backwards-designed?  How can
> you tell?
>
{: .challenge}
