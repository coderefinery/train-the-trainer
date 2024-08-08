(lesson-design)=

# Lesson design and development

:::{objectives}
- Understand how collaborative development of lesson material works
- Understand the design of CodeRefinery lessons
- Be able to contribute to existing CodeRefinery lessons
:::

:::{instructor-note}
- Teaching: 30 min
- Exercises: 30 min
:::


## A look over existing lessons (10min)

### Current Tools Workshop

There is a current list of Tools Workshop lessons on
[coderefinery.org/lessons](https://coderefinery.org/lessons).

Days 1-3 focus on the practical use of version control. Version control
is a prerequisite for the somewhat less technical lessons on days 4-6.

One way to understand the structure is that the first 3 days have a
single **learning objective**: applying the forking workflow to interact
with open source codes. The second half branches of to multiple useful
directions.

 * **Days 1-2**: [Introduction to version control](https://coderefinery.github.io/git-intro/)
 * **Day 3**: [Collaborative distributed version control](https://coderefinery.github.io/git-collaborative/)
 * **Day 4**: [Reproducible research](https://coderefinery.github.io/reproducible-research/)
 * **Day 4**: [Social coding and open software](https://coderefinery.github.io/social-coding/)
 * **Day 5**: [How to document your research software](https://coderefinery.github.io/documentation/)
 * **Day 5**: [Jupyter notebooks](https://coderefinery.github.io/jupyter/)
 * **Day 6**: [Automated testing](https://coderefinery.github.io/testing/)
 * **Day 6**: [Modular code development type-along](https://coderefinery.github.io/modular-type-along/)


### Other lessons

All of our lessons, including main lessons, but also additional lessons for
other workshops like this one, are on our
[GitHub page](https://github.com/orgs/coderefinery/repositories). The
repositories also contain exercises and workshop pages. All our lessons are
shared under Creative Commons Attribution, so feel free to use them for your
own purposes, modify them and make them better.


## Backward lesson design (15min)

### Why "Backward"

The "natural" way to design a lesson, that people often default to, is
to write down material you want to cover and then springle in related
exercises. This approach has a couple of significant downsides:
 - The content feel meandering and it's unclear what is meant to be learned.
 - The exercises and exam may not test the intended learning outcomes.

In backward lesson design we start from the learning objective and the
"final exam" and work backwards from there to


### The method

 1. Understand you learners
 2. Brainstorm rough ideas
 3. Start from learning objectives. Write down 1-3 overarching learning
   objectives for the lesson.
    - Think of the things your learners will
      be able to do at the end of the lesson. Think simple! The simpler
      the better. Think of three main points they will remember, of which
      maybe one or two are a concrete skill.
 4. Write an summative assesment for each outcome. Try to think of engaging
    and active exercises.
 5. For a longer lesson, add intermediate goals and formative assesments
    to bridge between the starting point and the learning objective and put them
    in a reasonable order.
 6. Write just enough material to get from one assessment (exercise) to another.
 7. Describe the course so the learners know if it is relevant to them.


## Know your audience

Creating **learner personas** helps you understand your audience, even if you
already know who the lesson is targeting. They ground your understanding of
what the audience knows and is interested in.


## Summative and formative assesments

A **formative assesment** is an exercise that gives feedback to the learner.
It should help a learner understand what they have learned and what they need
to pay attention to. They also give feedback to the teachers, who can adjust
timing depending on how learners understand the exercise.

A **summative assesment** is like and exam question. It's purpose is to check
that a learner has reached a **learning obejctive**. Summative assesments
should still provide feedback to the learner and the teacher.

Some standard exercise types:
 - Multiple choice (easy to get feedback via a classroom tool - try to design each wrong answer so that it identifies a specific misconception).
 - Code yourself (traditional programming)
 - Code yourself + multiple choice to see what the answer is (allows you to get feedback)
 - Inverted coding (given code, have to debug)
 - Parsons problems (working solution but lines in random order, learner must only put in proper order)
 - Fill in the blank
 - Discussions, self directed learning exercises


## Contributing (5min)

Our lessons are **collaboratively developed**. They are made by many people, and
there is no single fixed master plan (but there should be, in the instructors or
maintainer’s guide). We encourage everyone to contribute to the lessons.

Lessons are reviewed very often - essentially, before each workshop by the
instructor of that workshop. This can be a quick review, looking at issues and
fixing easy things, or more thorough.

We’ve made the [lesson-review](https://coderefinery.github.io/manuals/lesson-review/)
checklist to guide the review process.

If you are looking for a quick way to contribute, you can always check issues and
pull requests on GitHub.
 - From a lesson page, click "Edit on GitHub" in the top right corner
 - Click for the "Issues" or "Pull Requests" panel at the top of the page
 - Comment and take part in the discussion

Some issues you might be able to solve directly. Even then, you should comment on
the issue first. This way no-one else will start working on it at the same time and
you can be sure your work will be accepted.

So essentially, we follow the open source collaboration workflow we teach in the
[collaborative git lesson](https://coderefinery.github.io/git-collaborative/forking-workflow/).

- More about the files and format in the next lesson.


## Exercises

### Lesson design exercise (10-20min, or longer)

 - Pick a lesson topic. Any of the Tools Workshop lessons are OK,
   or you can choose any other topic you might want to teach.
 - Write down three learning objectives. What abilities would you
   expect the student to have at the end of the lesson?
 - Brainstorm an exercise that demonstrates one of those objectives.
 - If you have time:
   - Create two more exercises
   - Write chapter headers for a quick structure


### Contributing exercies (10-20min)

 - Read an issue on a CodeRefinery lesson's GitHub page.
 - Brainstorm solutions. Write a comment in the issue.


:::{keypoints}
- Here we summarize keypoints.
:::
