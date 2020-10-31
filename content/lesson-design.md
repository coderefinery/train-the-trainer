# Lesson design

```{prereq} Recommended reading
- CodeRefinery [lesson-design](https://coderefinery.github.io/manuals/lesson-design/) manual
- [The Carpentries Curriculum Development Handbook](https://cdh.carpentries.org)
- [Teaching Tech Together](http://teachtogether.tech/)
- Our [summary](https://coderefinery.github.io/manuals/teaching-tech-together/) of "Teaching Tech Together"
- [Ten quick tips for creating an effective lesson](https://doi.org/10.1371/journal.pcbi.1006915)
```

---

## How do you design?

```{discussion}
Discuss either in groups or via collaborative document:
- How do you start when you design a new lesson/presentation?
- Has your approach changed over the years? If yes, how?
```

---

## Backwards lesson design

### The approach

- You don't think about how to do something and try to explain it.
- Avoid the typical approach *"I want to show a number of things which I think are cool about
  tool X - how do I press these into 90 minutes?"*
- Instead, you start with **learner personas**, and think of what is
  **useful to them**: *"What do I want **them** to be able to remember/understand/apply/analyze/evaluate/create?"*.
  Then, you create a sequence of exercises which test
  incrementally progressing tasks.
- Then, you write the minimum amount
  of material to teach the gap between exercises.


### The process

For the whole process, see [our
manual](https://coderefinery.github.io/manuals/lesson-design/#backwards-lesson-design)
(instructor discusses these points briefly).


### Why is it good to have a process?:

- Having a semi-rigid design process can **save time** to start drafting.
- It will probably **increase quality and relevance** of lessons for learners.
- **We aren't perfect yet.**  CodeRefinery is still striving to get
  better at this, and we are more ad-hoc than you might think.
  A number of our lessons have not been designed this way but we are now improving
  these lessons with the backwards lesson design in mind.


### Designing exercises

When designing exercises, consider that some participants will get stuck
and may want to re-join at a later exercise. In other words it is nice
if exercises build up on each other but not at the cost that if participants
get stuck at exercise 2, they will not be able to do exercises 3 to N.

---

## Practice backwards design

```{discussion} Example: backwards-designing *this* lesson
**Learner persona**
  - Future HPC Carpentry trainer
  - Instructor who want to improve their own teaching of HPC courses
  - Technically very skilled
  - May or may not know/use interactive style of teaching

**Learning outcomes**
  - Teach HPC Carpentry lessons
    - Manage cognitive load of learners
    - Motivate them to use HPC resources instead of scaring them away
    - Competently use technical tools, e.g. screenshare well, don't go too fast, etc.
    - Place yourself into the learner's perspective (possibly everything is new)
  - Create own lessons
    - Backwards lesson design
      - Learner personas, clearly defining target audience
      - Devolping good exercises and examples
    - Use collaborative workflows
      - git, github
      - network of teachers
      - Make it possible to consolidate material and encourage contributions (even from learners)
  - Run workshops
    - Effectively teach over online
    - Train helpers
    - Kickstart other instructors

**Exercises**
  - Backwards-design an example lesson
  - Teach one segment for 5 minutes and get feedback
  - Adapt your example to the feedback
  - Give constructive feedback

**Material**
  - [Material to get from one exercise to another]
```

```{challenge} Exercise
Choose a simple lesson topic and apply backwards lesson design.  You
won't get all the way through, but come up with a logical
progression of exercises.

Some suggestions:
- Regular expressions
- Making papers in LaTeX
- Making figures in your favorite programming language
- Linux shell basics
- Something non-technical, such as painting a room
- An instructor training for CodeRefinery
- Some aspect from an already existing lesson
- [Introduction to high-performance computing](https://hpc-carpentry.github.io/hpc-intro/) (or an episode therein)
- [Unix shell in a HPC context](https://hpc-carpentry.github.io/hpc-shell/) (or an episode therein)
- A lesson you always wanted to teach

Exercise (30 minutes):
- Collect notes in a shared document.
- Start with learner personas and learning outcomes.
- Come up with a logical progression of exercises.

Discussion (15 minutes):
- How does this approach compare to other lessons or courses you have designed?
- We read, compare, and discuss our notes.
```
