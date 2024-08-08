(lesson-design)=

# Lesson design and development

:::{objectives}
- Understand how collaborative development of lesson material works
- Understand the design of CodeRefinery lessons
- Be able to contribute to existing CodeRefinery lessons
:::

:::{instructor-note}
- Discussion: 20 min
- Exercises: 30 min
:::


## Exercise: How do you design your teaching material?

:::{exercise} We collect notes using a shared document (10 min)
- When you start preparing a new lesson or training material, where do you start?
- What tricks help you with "writer's block" or the empty page problem?
- If your design process has changed over time, please describe what you used to do and what you do now instead.
- What do you know now about lesson/training preparation that you wish you knew earlier?
:::


## Creating new teaching material


### Typical problems

- Someone creates a lesson, but they think about what is interesting to them,
  not what is important for the learners.
- "I want to show a number of things which I think are cool about
  tool X - how do I press these into 90 minutes?"
- Write down material you want to cover and then sprinkle in some exercises.
- They think about how they work, not how the learners work.
- Trying to bring learners to their level/setup, not trying to meet the learners
  where they are.
- Not really knowing the learning objectives or the learner personas.


### Better approach

Good questions to ask and discuss with a group of colleagues **from diverse backgrounds**:
- What is the expected educational level of my audience?
- Have they been already exposed to the technologies I am planning to teach?
- What tools do they already use?
- What are the main issues they are currently experiencing?
- What do they need to remember/understand/apply/analyze/evaluate/create
  ([Bloom's taxonomy](https://en.wikipedia.org/wiki/Bloom%27s_taxonomy))?
- Define learner personas.
- It may be an advantage to share an imperfect lesson with others early to
  collect feedback and suggestions before the lesson “solidifies” too much.
  Draft it and collect feedback. The result will probably be better than
  working in isolation towards a "perfect" lesson.


### The process of designing a lesson "backwards"

As described in ["A lesson design process" in the book Teaching Tech
Together](https://teachtogether.tech/en/index.html#s:process):

1. Understand your learners.
1. Brainstorm rough ideas.
1. Create an summative assessment to know your overall goal.
   > [Think of the things your learners will be able to do at the end of the lesson]
1. Create formative assessments to go from the starting point to this.
   > [Think of some engaging and active exercises]
1. Order the formative assessments (exercises) into a reasonable order.
1. Write just enough material to get from one assessment (exercise) to
   another.
1. Describe the course so the learners know if it is relevant to them.


## Improving existing lessons

Collect feedback during the workshop:
- Collect feedback from learners and instructors ([Example from a past
  workshop](https://coderefinery.github.io/2024-03-12-workshop/questions/)).
- Convert feedback about lessons and suggestions for improvements into issues
  so that these don't get lost and stay close to the lesson material.

Collect feedback before you start a big rewrite:
- First open an issue and describe your idea and collect feedback before you
  start with an extensive rewrite.
- For things still under construction, open a draft pull/merge request to collect
  feedback and to signal to others what you are working on.

Small picture changes vs. big picture changes:
- Lesson changes should be accompanied with instructor guide changes (it’s like
  a documentation for the lesson material).
- Instructor guide is essential for new instructors.
- Before making larger changes, talk with somebody and discuss these changes.


## Use case: our lessons

:::{instructor-note} Work in progress ...
- We will browse the overview of [our
  lessons](https://coderefinery.org/lessons/), all are shared under CC-BY
  license.
- Show and discuss the evolution of the Git lesson over time, and our choices
  and lessons learned.
:::


## Exercise: Discussion about learning objectives and exercise design

:::{exercise} We work in groups but use the shared document as result (20 min)
1. As a group **pick a lesson topic**. It can be one of the topics listed here but
   you can also choose something else that your group is interested in, or a topic
   that you have taught before or would like to teach. Some suggestions:
    - Git: Creating a repository and porting your project to Git and GitHub
    - Git: Basic commands
    - Git: Branching and merging
    - Git: Recovering from typical mistakes
    - Code documentation
    - Jupyter Notebooks
    - Collaboration using Git and GitHub/GitLab
    - Using GitHub without the command line
    - Project organization
    - Automated testing
    - Data transfer
    - Data management and versioning
    - Code quality and good practices
    - Modular code development
    - How to release and publish your code
    - How to document and track code dependencies
    - Recording environments in containers
    - Profiling memory and CPU usage
    - Strategies for parallelization
    - Conda environments
    - Data processing using workflow managers
    - Regular expressions
    - Making papers in LaTeX
    - Making figures in your favorite programming language
    - Linux shell basics
    - Something non-technical, such as painting a room
    - Introduction to high-performance computing
    - A lesson you always wanted to teach
    - ...
1. Try to define 2-3 learning objectives for the lesson and write them down.
1. Can you come up with one or two engaging exercises that could be used to
   demonstrate one of those objectives? Some standard exercise types:
    - Multiple choice (easy to get feedback via a classroom tool - try to design each wrong answer so that it identifies a specific misconception).
    - Code yourself (traditional programming)
    - Code yourself + multiple choice to see what the answer is (allows you to get feedback)
    - Inverted coding (given code, have to debug)
    - Parsons problems (working solution but lines in random order, learner must only put in proper order)
    - Fill in the blank
    - Discussions, self directed learning exercises
:::


## Great resources

- [Teaching Tech Together](http://teachtogether.tech/)
- [Our summary of Teaching Tech Together](https://coderefinery.github.io/manuals/teaching-tech-together/)
- [Ten quick tips for creating an effective lesson](https://doi.org/10.1371/journal.pcbi.1006915)
- [Carpentries Curriculum Development Handbook](https://cdh.carpentries.org/)
- [Our manual on lesson design](https://coderefinery.github.io/manuals/lesson-design/)
