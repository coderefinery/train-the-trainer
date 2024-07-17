(collaborative-notes)=

# Collaborative notes

:::{objectives}
- Be able to provide a highly interactive online workshop environment with collaborative documents
:::

:::{instructor-note}
- Teaching: ? min
- Exercises: ? min
:::

## Introduction

The Collaborative document is how you interact with the participants.
The participants can ask questions and give feedback through the collborative
document. During a CodeRefinery session there can be a large a volume of questions.
A dedicated person is needed to answer and edit the collaborative document.
Let us see how the collaborative document is used, then discuss the role of 
the editor or HackMD-manager.

## Collaborative document mechanics and controls

[Hackmd](https://hackmd.io) or  [HedgeDoc](https://hedgedoc.org/) are real-time text editor online.  We use it to:
* As a threaded chat, to **answer questions and provide other information** without
  interrupting the main flow of the room.
* provide everyone with a **more equal opportunity to ask questions**.
* **create notes** which will be archived, for your later reference.

You do not need to login/create an account to be able to edit the document.

### Basic controls

```{figure} img/hackmd--controls.png

This may look slightly different on mobile devices and small windows.
```

- At the top (left or right), you can switch between **view**,
  **edit**, and **split view and edit** modes.

- You write in [markdown](https://commonmark.org/help/) here.  Don't
  worry about the syntax, just see what others do and try to be like
  that!  Someone will come and fix any problems there may be.

- Please go back to view mode if you think you won't edit for a
  while - it will still live update.


### Asking questions

**Always ask questions and add new sections at the very bottom**.
You can also answer and comment on older questions, too.

```{figure} img/hackmd--questions2.png

Questions and answers in bullet points
```

Since we plan to publish the questions and answers later as part
of the workshop page, we recommend to not use any names. You can indicate
your own name to make it easier to discuss more during the workshop but
then always use this form: `[name=Myname]`. This makes it easier for
us to automatically remove all names before publishing the notes.

Other hints:

- Use `+1` to agree with a statement or question (we are more likely
  to comment on it).

- Please leave some blank lines at the bottom

- NOTE: Please don't "select all", it highlights for everyone and adds a
  risk of losing data (there are periodic backups, but not instant).

- It can be quite demanding to follow the collaborative document closely.  Keep an eye
  on it, but consider how distracted you may get from the course.  For
  things beyond the scope of the course, we may come back and answer
  later.


### Don't get overwhelmed

There can be a flood of information on the collaborative document.  Scan for what is
important, then if you would like come back later.  But it is
important to keep checking it.


### Privacy

- Assume the collaborative document is **public and published: you never
  need to put your name there**.

- The collaborative document will be **published on the website afterwards**.  We will
  remove all non-instructors names, but it's easier if you don't add
  it there in the first place.

- Please keep the link private during the workshop, since since
  security is "editable by those who have the link".

- You can use `[name=YOURNAME]`, to name yourself.  We *will* remove
  all names (but not the comments) before archiving the notes (use
  this format to make it easy for us).


## HackMD manager

We have one person who is a "HackMD helper".  This isn't the only
person that should edit and answer, but one person shouldn't have too
much else on their mind so can focus on it.  They also make sure that
HackMD is updated with exercise, break, and other meta-information to
keep people on track.

Below, (*) = important.

### Before the workshop

* Create a new hackmd for the workshop
* make sure that **editing is enabled for anyone without login**
* Add workshop information, links to the workshop page and material 
and an example question and answer to the top of the hackmd (see below)

### Most things to edit (everyone)

Make it easy to post after the course and consistent to follow:

* Tag all names with `[name=XXX]` (so they can be removed later),
  remove other personal data or make it obvious.
* Add in information on exercises (new section for them, link, end
  time, what to accomplish)
* Make a logical section structure (`#` for title, `##` for sections,
  `###` for episodes, etc. - or what makes sense)



### General HackMD practices

```{figure} img/hackmd--full-demo.png
:align: right

A live demo of HackMD during a Q&A time.  The two instructors are
discussing some of the import answers.  Multiple learners have asked
questions, multiple answers, and some remaining to be answered
```



Keep it formatted well:

- (*) Tag names you see with `[name=XXX]` so that we can remove it
  later.
- Heading level `#` is only the page title
- Add a new `##` heading when a new *lesson* or similar thing is
  started (introduction, icebreaker, break between lessons, etc)
- Add a new `###` heading when a new *episode*, *exercise*, *break*
  (within exercise session)
- Ensure people are asking questions at the bottom, direct them there
  if they aren't.
- (*) Ensure each question is a bullet point.  Each answer or follow-up
  should be a bullet point below.
  - Should you use more deeply nested bullet points, or have only one
    level below the initial question?  It depends on the context, but
    if a conversation goes on too long, try not to let it go too
    deep.


Update with meta-talk, so that learners can follow along easily:

- Add Icebreaker and introductory material of the day.  Try to talk to
  people as they joined to get them to open HackMD and answer.
- Anything important for following along should not be only said via
  voice.  It needs to be in the HackMD, too.
- New lessons or episodes, with links to them.
- For exercises, link to exercise and add the duration, end time,
  goals.  If these are unclear, bring it up to the instructor by voice.
- Add a status display about breaks.


Screenshare it when necessary:

- During breaks and other times, share the HackMD (including the
  notification about break, and when it ends).
- It is nice if the arrangement allows some of the latest questions to
  be seen, so people are reminded to ask there.
- Someone else may do this, but should make sure it happens.

Answer questions

- If there is an question that should be answered by the instructor by
  voice, bring it up (by voice) to the instructor immediately.
- During breakout sessions, watch for HackMD notifications about
  breakout rooms that need help
  and direct someone to that room.
- How soon do you answer questions? Two points of view:
  - Answer questions right away: can be really intense to follow.
  - Wait some so that we don't overload learners: reduces the info
    flow.  But then do people need to check back more often.
  - You need to find your own balance.  Maybe a quick answer right
    away, and more detailed later.  Or delay answers during the most
    important parts of the lecture.
- Avoid wall-of-text answers.  If reading an answer takes too long, it
  puts the person (and other people who even try to read it) behind
  even more by taking up valuable mental energy.  If an answer needs a
  wall of text, consider these alternatives:
  - Progressive bullet points getting more detailed (first ones
    useful alone for basic cases)
  - Don't be worried to say "don't worry about this now, let's talk
    later."
  - Figure out the root problem instead of answering every possible
    interpretation
  - Declare it advanced and that you will come back later.

Ensure it can be posted quickly:

- HackMD gets posted to the workshop webpage.  For this, it needs some
  minimal amount of formatting (it doesn't need to be perfect, just
  not horrible).
- All names and private information needs to be stripped.  This is why
  you should rigorously tag all names with `[name=XXX]` so they can be
  removed (see above).
  - Learner names can be completely removed.  CR staff names can be
    `[name=CR]` or something similar.
  - There may be other private URLs at the top or bottom.

- If possible, send the PR adding the HackMD to the workshop webpage
  (though others can do this, too).



### HackMD format example

```
# Workshop, day 1


## Lesson name
https://coderefinery.github.io/lesson/

### Episode name
https://coderefinery.github.io/01-episode/

- This is a question
  - Anwser
  - More detailed answer
- question
  - answer

### Exercises:
https://link-to-exercise/.../.../#section
20 minutes, until xx:45
Try to accomplish all of points 1-3.  Parts 4-5 are optional.

Breakout room status:
- room 2, need help with Linux permissions
- room 5, done

### Break
:::danger
We are on a 10 minute break until xx:10
:::


## Lesson 2
https://coderefinery.github.io/lesson-2/

```

### Posting HackMD to website

HackMD should be posted sooner rather than later, and hopefully the
steps above will make it easy to do so quickly.  You could wait a few
hours, to allow any remaining questions to be asked an answered.

- Download as markdown
- Remove any private links at the top
- Adjust headings so that they are reasonable
- Look for private info and remove it
  - Search document for `[name=???]`  (change to `[name=staff]` or
    `[name=learner]`)
  - Any names not tagged with `[name=]`
  - usernames in URLs
  - private links

### Feedback template

``````
## Feedback, day N

:::info
### News for day N+1
- .
- .
:::

### Today was (multi-answer):
- too fast: 
- just right: 
- too slow: 
- too easy: 
- right level: 
- too advanced: 
- I would recommend this course to others: 
- Exercises were good: 
- I would recommend today to others: 
- I wouldn't recommend today: 

### One good thing about today:
- ...
- ...

### One thing to be improved for next time:
- ...
- ...

### Any other comments:
- ...
- ...
``````
:::{keypoints}
- Here we summarize keypoints.
:::
