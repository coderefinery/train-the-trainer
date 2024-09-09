(backwards-lesson-design)=

# Backwards lesson design

It happens far too often: someone creates a lesson, but they think
about what is interesting to them, not what is important for the
learners.  In fact, an earlier version of this instructor training had
this very issue.

It is critical to backwards design almost any piece of communication,
especially something as widespread as teaching.


## The approach

- You don't think about how to do something and try to explain it.
- Avoid the typical approach *"I want to show a number of things which I think are cool about
  tool X - how do I press these into 90 minutes?"*
- Instead, you start defining your target audience by answering to questions
  such **What is the expected educational level of my audience?**, **Have they
  been already exposed to the technologies I am planning to teach?**, **What
  tools do they already use?**, **What are the main issues they are currently
  experiencing?**. It is important to discuss these points with a group of
  colleagues, preferably from diverse backgrounds and institutions to reduce
  biases. Once you clarified your target audience, it is useful to create
  **learner personas**; that will help you during the development process by
  providing concrete examples of potential learners showing up at your
  workshops. For each **learner personas**, try to think of what is **useful to
  them**: *"What do they **need** to
  [remember/understand/apply/analyze/evaluate/create](https://coderefinery.github.io/instructor-training/03-teaching-style/#using-bloom-s-taxonomy-to-write-effective-learning-objectives)?"*.
  Asking and answering to these questions will allow you to define the
  background knowledge (starting points) and goals (end points) of your
  learners.  Then, you create a sequence of exercises which test incrementally
  progressing tasks and acquisition of the new skills (from starting to end
  points).
- Then, you write the minimum amount
  of material to teach the gap between exercises.


## The process

As described in ["A lesson design process" in the book Teaching Tech
Together](https://teachtogether.tech/en/index.html#s:process):

1. Understand your learners

2. Brainstorm rough ideas

3. Create an summative assessment to know your overall goal

   * CodeRefinery translation: think of the things your learners will
     be able to do at the end of the lesson.  Think simple!  The
     simpler the better.  Think of three main points they will
     remember, of which maybe one or two are a concrete skill.

4. Create formative assessments to go from the starting point to this.

   * CodeRefinery translation: think of some engaging and active
     exercises.

5. Order the formative assessments (exercises) into a reasonable order.

6. Write just enough material to get from one assessment (exercise) to
   another.

7. Describe the course so the learners know if it is relevant to them.

We can't emphasize enough how important it is to **know your end
state and keep it simple**.

```{discussion} Example: designing an HPC Carpentry lesson

Let's take as an example the *[HPC Carpentry lesson](https://hpc-carpentry.github.io/hpc-intro/)*

**Target audience**
  - What is the expected educational level of my audience?
      - A PhD student, postdoc or young researcher.
  - Have they been already exposed to the technologies I am planning to teach?
      - The word **HPC** is not new to them and they may have already used an HPC but are still not capable of giving a proper definition of HPC. In addition, we do not expect them to know much about parallelism and they cannot make any distinction between various available parallelism paradigms.
  - What tools do they already use?
      - serial codes, multi-threaded codes, data parallelism; usually out-of-the-box tools.
      - they may have tried to "scale" their code (multiprocessing, threading, GPUs) with more or less success.
  - What are the main issues they are currently experiencing?
      - they cannot solve their problems either because they would like to run the same code but with many different datasets or because their problem is larger (more computations/memory).
      - most of the time they know their codes can run on HPC (from the documentation) but never really had the opportunity to try it out.
      - Very few will have their own codes where they may have tried different things to speed it up (threading, task parallelism) but have no clear strategy.

**Learner persona**
  - Sonya is a 1st year PhD student: she recently moved to Oslo and joined the
    Computational and Systems Neuroscience group. She will be using the
    [NEST](https://nest-simulator.readthedocs.io/), a simulator for spiking
    neural network model. She used NEST during her master thesis but on her
    small cluster: **she never used an HPC resource** and is really excited about it.
  - Robert is a field ecologist who obtained his PhD 6 months ago. He is now
    working on a new project with Climate scientists and as a consequence will
    need to run global climate models. He is **not very familiar with command
    line** even though he attended a Software Carpentry workshop and the idea to
    use HPC is a bit terrifying. He knows that he will get support from his
    team who has extensive experience with HPC but would like to become more
    independent and be able to **run his own simulations** (rather than copying
    existing cases).
  - Jessica is a postdoc working on a project that investigates numerically the
    complex dynamics arising at the tip of a fluid-driven rupture. Fluid
    dynamics will be computed by a finite element method solving the
    compressible Navier-Stokes equations on a moving mesh. She **uses a code she
    has developed** during her PhD and that is based on existing libraries. She
    has mostly ran it on a local desktop; her work during her PhD was very
    limited due to the lack of computing resources and she is now very keen is
    **moving to HPC**; she knows that it will requires some work, in particular to
    parallelize her code. This HPC training will be her first experience with
    HPC.

**Learning outcomes**
  - Understand the difference between HPCs and other local/remote machines
  - Understand the notion of core, nodes, cluster, shared/distributed memory, etc.
  - Understand the notion of login nodes.
  - Understand the need for a scheduler and how to use it appropriately
  - Understand why optimising I/O is important on HPC and how to best use HPC filesystems
  - Understand the need to parallelize (or use existing parallel) codes and in which cases HPCs is a must (when communications is required)
  - Understand how to get your code ready to use on HPC (access to libraries, installation of your own libraries/software, etc.)
  - Understand that an HPC is an operational machine and is not meant for developing codes.

**Exercises**
  - Get basic information such the number of CPUs, memory from your laptop and try to do the same on a HPC. Discuss outcomes.
  - Try to create files on the different filesystems on your HPC resource and access them.
  - Create different types of job scripts, submit and check outputs.
  - Make a concrete example to run a specific software on your HPC (something like GROMACS).
```


## Exercises

```{exercise} Backwards-design a lesson/topic
Choose a simple lesson topic and apply backwards lesson design.  You
won't get all the way through, but come up with a logical
progression of exercises.

The section you pick should require **screen sharing** and be of some **follow-along
task** (preferably using a shell).

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
```
