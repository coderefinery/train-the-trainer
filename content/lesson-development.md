---
layout: episode
title: "Lesson development"
teaching: 15
exercises: 45
questions:
  - "How can you improve and contribute to CodeRefinery lessons?"
keypoints:
  - "We have checklists for reviewing existing lessons and creating new lessons"
---

## Lesson development

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
> checklist and discuss it, instead of duplicating things here.
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

- All lessons are public and open [repositories on GitHub](https://github.com/coderefinery).
- Make issues and pull requests about ideas and improvements.
- For substantial changes we recommend to first open an issue and describe your
  idea and collect feedback before you start with an extensive rewrite.
- If you see an open pull request, don't be afraid to comment and merge!
- Avoid merging own pull requests.
- For things still under construction, open a draft pull request to collect
  feedback and to signal to others what you are working on.
- `_episodes/` contains the markdown files of each episode, which get
  automatically assembled.  There is YAML metadata at the top of
  each.
- `index.md` is the main page, `guide.md` is the instructor's guide,
  and `reference.md` is the learner's reference guide.
- To get started with new lessons, we recommend to [generate a
  copy](https://github.com/coderefinery/example-lesson/generate) from the
  example [lesson template](https://github.com/coderefinery/example-lesson).
- After creating the new lesson repository, adapt `_config.yml`.

Note that most lessons and the
[lesson template](https://github.com/coderefinery/example-lesson) contain the
repository [jekyll-common](https://github.com/coderefinery/jekyll-common) as
Git submodule.  We do this to have one repository with common layout and
styling and to make it relatively easy to update lesson repositories after
layout or styling changes.
