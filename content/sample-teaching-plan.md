---
orphan: true
---

# Sample teaching plan

This teaching plan is created for demo purposes, to use during
the streaming/team teaching exercises.

## The teaching plan

**Motivation (1 min)**

- A: greeting
- A: asks B if you have ever had code break due to changing it wrongly, and not being able to go backwards
- B: (answers yes somehow)
- B: asks A about how version control helps with this
- A: Tells about version control
    - Record checkpoints (versions)
    - Get a history
    - Share and collaborate
    - we demonstrate git

**demo (3 min)**

For demos, A talks and B types the demo.

- A: introduce demo and asks B if they want to type
- Action: B opens a termnial and `cd` to existing project dir
    - mentions how termainal may be hard but isn't part of today's lesson.
- Actions: A talks, B types
    - (make two files if they don't exist yet)
    - `git init`
    - `git status`
    - `git add file file`
    - `git commit -m "MESSAGE"`
    - `git log`

**outro (1 min)**

- B: asks how often this is really used
- Q&A via Notes
- Whoever: recommend trying this on one project



## Sample questions

These are some sample questions which the instructors (of the teaching
practice) may ask the teaching-learners via the Notes.

:::{admonition} Sample Q&A questions (teaching practice students, don't look)
---
class: dropdown
---

Ask the teachers practicing various questions.  Some samples are
below.  The teachers aren't expected to have time to answer every
question (and it's good if they have to filter and decide which are
most important to answer by voice, so ask some that can be answered
and some that can't).

- What other version control systems would you recommend?
- What should I put in the commit message?
- Is git the same as Github?
- Should I use git or Gitlab?
- Do I have to run `git add` before I run `git commit`?  I don't
  usually do this.
- I get this error message: `fatal: not a git repository (or any of the parent directories): .git`
- Simulate some terminal error
- I have a detached head
- I tried to use VScode as my editor but commits didn't work
- What happens if I make a commit wrong?
- How should I make a commit message?
- Should I be worried about making a wrong commit?

... and more

:::
