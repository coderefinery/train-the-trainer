# Collaborative lesson development

This session focuses on **organizational** and **technical aspects**
of collaborative lesson development.

```{discussion}
This session is about **collaborative** lesson development. What advantages do
you see in developing lessons collaboratively and sharing lessons (making
material accessible)?  What difficulties are there?
```

---

## Lesson templates for static sites

- [Jekyll](https://jekyllrb.com/)-based
  - Example: [Introduction to version control with Git](https://coderefinery.github.io/git-intro/)
  - [Lesson template](https://github.com/coderefinery/example-lesson)
  - Common styling implemented as Git submodule: [jekyll-common](https://github.com/coderefinery/jekyll-common)
  - Based on a past version of the [Carpentries lesson style](https://github.com/carpentries/styles/)
  - A new Carpentries lesson template is in the works
- [Sphinx](https://www.sphinx-doc.org)-based
  - Example: this lesson
  - Starting point: [sphinx-lesson](https://github.com/coderefinery/sphinx-lesson)
  - [Documentation](https://coderefinery.github.io/sphinx-lesson/)
- Templates can be freely re-used

Why static sites?
- Decentralized (in terms of organization/namespace)
- Forkable
- Anybody can suggest changes

---

## Creating new teaching material

Creating new teaching material is a longer process, because you should
go through the whole
[backwards lesson design process](/lesson-design/)
and get extensive comments.
Still, don't feel afraid: nothing is perfect (or even good)
the first time. In fact, **it may be an advantage to share an imperfect
lesson with others early** to collect feedback and suggestions before the lesson
"solidifies" too much. Draft it and collect feedback. The result will probably
be better than working in isolation towards a "perfect" lesson.

```{discussion}
How can we share unfinished work/ideas?
- Draft pull requests (GitHub) or WIP (work in progress) merge requests (GitLab).
- Open an issue and discuss your idea before implementing it.
```

---

## Contributing to existing lessons

Our lessons are **collaboratively developed**.  They are made by many
people, and there is no single fixed master plan (but there should be,
in the instructors or maintainer's guide).  We encourage
everyone to contribute to the lessons.

Lessons are reviewed very often - essentially, before each workshop by
the instructor of that workshop.  This can be a quick review, looking
at issues and fixing easy things, or more thorough.

Every so often (such as at this training), there is an extensive
hackathon period of fully revising a lesson and making major improvements.

We've made the [lesson-review](https://coderefinery.github.io/manuals/lesson-review/) checklist
to guide the review process.

```{discussion}
We now go to the
[lesson-review](https://coderefinery.github.io/manuals/lesson-review/)
checklist and discuss it, instead of duplicating things here.
```

---

## Recommendations and lessons learned

- Convert feedback about lessons and suggestions for improvements into *issues*
  so that these don't get lost.
- Make your lesson citable: get a DOI.
- Credit contributors (not only Git commits).
- Instructor guide is essential for new instructors.
- Lesson changes should be accompanied with instructor guide changes (it's like
  a documentation for the lesson material).
- Apply and validate backwards lesson design again and again.
- Make it possible to try out new ideas (by making the lesson branch-able).
- Before making larger changes, talk with somebody and discuss these changes.
- For substantial changes we recommend to first open an issue and describe your
  idea and collect feedback before you start with an extensive rewrite.
- For things still under construction, open a draft pull request to collect
  feedback and to signal to others what you are working on.
