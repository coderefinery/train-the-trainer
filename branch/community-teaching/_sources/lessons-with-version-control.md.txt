# Lesson development with version control

So, we want to practically share.  We have these minimum requirements:

* Someone can get the preferred form of modification, to improve
  without limitation.

* It is trivial to track differences and send the changes back to the
  source, with little cost to the original maintainer.

Especially with the second of these, version control in an online
platform seems to be the only reasonable option.


## Version control and static site generators

CodeRefinery and the Carpentries use git and Github to develop
lessons.  The general procedure is this:

* Version control to store the raw files in text format
* A static website compiler to convert them to HTML files
* Serving to the public via Github Pages (but this could be replaced
  with other systems)

This allows for true collaborative development and community
contributions.

Carpentries uses a custom website complierer based on R, CodeRefinery
uses the Sphinx documentation engine which is used in many different
projects for documentation.  CodeRefinery's use of a standard tool
allows us to build on a huge and growing ecosystem of extensions and
themes, and promotes local reuse.

The exact static website generator used isn't so important, as long as
some form of version control is used.

A open-source license is the last bit to consider: without a license,
it can't be reused and passed on, and there is little incentive for
someone to contribute.


## CodeRefinery lesson tools

CodeRefinery uses the following tools to actually make its lessons
right now:

* [Sphinx](https://www.sphinx-doc.org/) (a common documentation
  generator, widely used in open source projects in general)
* The [sphinx-lesson](https://github.com/coderefinery/sphinx-lesson), which is more of
  a small collection of other extensions than new development itself.
* Github for hosting lessons: <https://github.com/coderefinery/>
* Github Actions and Github Pages for building and web serving our
  lessons.


## Exercises

```{exercise} Contribute to a sample lesson
* Open this very lesson in GitHub (it uses the same format as
  typical CodeRefinery lessons):
  <https://github.com/coderefinery/community-teaching/>

* Browse the files and understand the general idea.  Check out at
  least these and use HackMD to record their functions:

  * .github/workflows/sphinx.yml
  * content/conf.py
  * content/index.rst
  * content/lessons-with-version-control.rst

* If you want, try to make a pull request to this lesson.  It
  doesn't have to have any significant content, it can be a pure
  test pull request.
```

```{exercise} (advanced) Create your own lesson
Use the
[sphinx-lesson-template](https://github.com/coderefinery/sphinx-lesson-template)
to create a new lesson of your choice.  Alternatively, use the current
Carpentries system, or some other system of your choice.
```


## Recommendations and lessons learned

- Convert feedback about lessons and suggestions for improvements into *issues*
  so that these don't get lost.
- Make your lesson citable: get a DOI.
- Credit contributors (not only Git commits).
- Instructor guide is essential for new instructors.
- Lesson changes should be accompanied with instructor guide changes (it's like
  a documentation for the lesson material).
- Apply and validate {ref}`backwards-lesson-design` again and again.
- Make it possible to try out new ideas (by making the lesson branch-able).
- Before making larger changes, talk with somebody and discuss these changes.
- For substantial changes we recommend to first open an issue and describe your
  idea and collect feedback before you start with an extensive rewrite.
- For things still under construction, open a draft pull request to collect
  feedback and to signal to others what you are working on.


## See also

- [CodeRefinery git-intro](https://coderefinery.github.io/git-intro/)
- [CodeRefinery git-collaborative](https://coderefinery.github.io/git-collaborative/)
- [Carpentries lesson development](https://docs.carpentries.org/topic_folders/lesson_development/index.html)
