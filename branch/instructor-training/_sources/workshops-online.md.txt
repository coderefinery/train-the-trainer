---
layout: episode
title: "Lessons learned from running online and in-person workshops"
teaching: 20
exercises: 10
questions:
  - "What are the steps for organizing a CodeRefinery workshop?"
  - "What can I learn about running my own workshop?"
  - "What have we learned from running large online workshops?"
objectives:
  - "Learn how to use the manuals to organize and teach a workshop."
keypoints:
  - "There are many aspects to consider to deliver a successful workshop."
  - "CodeRefinery maintains a number of manuals - use them when preparing a workshop."
---

> ## Workshop manuals
> CodeRefinery maintains a number of [workshop manuals](https://github.com/coderefinery/manuals/)
> with most of the "primary" information.  This episode condenses this
> into a quick overview.
{: .callout}


# Running a workshop: online


## Online teaching discussion

```{discussion} Discussion: Online vs in-person

In notes:
- Compare and contrast the benefits of online teaching with
  in-person: {advantage, disadvantage} × {content, presentation}
- How do you have to prepare differently?
- What are your own experiences?
```



## Case study: Mega-CodeRefinery and Finland HPC Kickstart

- Mega-CodeRefinery
  - Audience of around 90-100
  - "bring your own breakout room" (see below)
  - 3 days/week, 6 days total
  - Lessons as normal in CodeRefinery
- HPC Kickstart
  - 250 registered, ~180 max participants
  - Multi-university: local differences made this much harder to manage.
  - Breakout rooms not pre-planned.

Mega-CodeRefinery worked very well, HPC kickstart didn't - but not
because of the size.



## General workshop arrangements

> ## Manuals link
> - [before the
>   workshop](https://github.com/coderefinery/manuals/blob/master/workshop-administration.md#before-the-workshop)
{: .callout}

- Select a coordinator, recruit instructors (at least 3 is important),
  find helpers
- Find a good lecture room:
  [requirements](https://github.com/coderefinery/manuals/blob/master/workshop-requirements-inperson.md)
- Set up workshop webpage using the [Github, template
  repository](https://github.com/coderefinery/template-workshop-webpage]:
  [see
  manuals](https://github.com/coderefinery/manuals/blob/master/workshop-administration.md#set-up-workshop-page)
- Advertising the workshop
- Communication with registered participants



## CodeRefinery online scaling strategy

- We started online workshops in 2020 March, for the obvious reasons.
- First, we started with two "normal size" (20 people) practice
  workshops
- Then we did a 100 person workshop.  It went well, but there is less
  tolerance for problems.


### Basic preparation

- You need more breaks are needed
- People have a way of doing too many things and not focusing.
- "[How to attend an online
  workshop](https://coderefinery.github.io/manuals/how-to-attend-online/)"
  guide to prepare learners

### Basic platform: Zoom

- Zoom (not the most ethical, but worked well and was available)
- [Zoom mechanics: instructions for
    students](https://coderefinery.github.io/manuals/zoom-mechanics/).
  - Mostly things that are known
  - We don't use Zoom interaction features much anymore
    (faster/slower/etc), but breakout rooms and HackMD instead
- See also: [Online training
  manual](https://coderefinery.github.io/manuals/online-training/)
  (which is getting a bit old compared to what is below).

### Breakout rooms, bring your own team

- Breakout rooms are
  - Static: same people across whole workshop
  - Contain one helper per room (see below)
- Team registration: accept a "team" field when registering, people on the
    same team are put together.
	- Gives motivations for learners to bring their colleagues and
      learn together.
	- More than one person learning together greatly increases update
- You need a powerful enough registration system to assign rooms and
  email them to people!
- We ask people to name themselves "(N) Firstname Lastname" or "(N,H)
  Firstname Lastname" for helpers.  Then it is fast to assign them to
  their designated breakout rooms.
- See also: [Breakout room
  mechanics](https://coderefinery.github.io/manuals/breakout-rooms-helping/)


### Helper training

- Each breakout room has a helper
- Helper should be a little bit familiar, but not expected to be able
  to answer all questions.
- Special, custom [helper
  training](https://coderefinery.github.io/manuals/helper-intro/)
  since helpers make or break the workshop
- Helper recruitment:
  - Our networks
  - Team registration: if a team registers with their own helper, then
    they are guaranteed to get in together.  "bring your own breakout
    room"
  - Former learners, ask them to come back.
- Two helper trainings the week before the workshop.

### Staff roles

To reduce stress on any one person, we clearly define the different
roles and try to avoid overlap.  We actually have enough people for
all of these, so it works well.

- Workshop coordinator
  - Registration, etc.
- Zoom host
  - Handles registration, breakout rooms, recording, Zoom chat.
- HackMD helper
  - Dedicated to watching HackMD and answering questions quickly.
  - [Host on manuals](https://coderefinery.github.io/manuals/host/)
- Expert helpers
  - "Spare hands" who rotate between breakout rooms and make sure
    helpers are doing well.
  - Give feedback to instructor about how breakout rooms are going.
  - Take the place of missing helpers.
  - Easy way for any people with a bit of spare time to help out.
  - [Expert helpers in workshop](https://coderefinery.github.io/manuals/expert-helpers/)
- Instructors
  - Teach, they shouldn't overlap with the above roles (but serve as
    expert helpers other times).
  - Usually also improve the lesson a bit before teaching
  - [General staff intro in manuals](https://coderefinery.github.io/manuals/instructor-intro/)
- Workshop preparation meeting
  - Get together, introduce roles, kickstart instructors
  - [Workshop prep meeting in manuals](https://coderefinery.github.io/manuals/workshop-prep-call/)


### HackMD

- We've been using it here
- Chat doesn't work wen large, written
  document does.
- HackMD can just about scale to ~100 person workshop.  Recommend
  learners keep it in view mode while not editing.
- Voice questions are still allowed, but will be recorded.  Staff
  raise important questions from HackMD to the instructor immediately.
- HackMD also allows communication when in breakout rooms.
- You can get multiple answers, and answers can be improved over
  time.
- [HackMD
  mechanics](https://coderefinery.github.io/manuals/hackmd-mechanics/)
  and [HackMD
  helpers](https://coderefinery.github.io/manuals/hackmd-helper/).

### Recording and streaming

- When you have 100 people, main room is quiet anyway: you don't lose
  much by recording.
  - Questions anonymously in HackMD, privacy loss is not so bad
- Breakout rooms are never recorded
- Streaming
  - We streamed via Twitch: https://twitch.tv/coderefinery
  - We typically get 5-40 viewers.
  - Zoom can directly send the stream to Twitch: no extra software
    needed.
  - Twitch archives videos for 14 days, which allows learners to get
    an instant reply (we get hundreds of views in the next days).
  - So while possibly not useful for new people to learn, the instant
    reply *is* very useful.  Instructor can also work on problems in
    main stream during breakout rooms, which learners can watch
    later.
  - Streamers also have access to HackMD to ask questions.
- Certain tricks needed to keep learners from appearing in recording
  or stream
  - "Spotlight video", host does not go to gallery view, uses dual
    monitor mode.  We are still figuring this out.

### Installation time

- People *have* to be ready once we start, or else everything fails.
- Two installation help times the week before.
- Every email emphasizes that you have to be prepared, and "requires"
  you to attend workshops (but really it's only)
- Installation instructions include *steps to verify*
- Installation instructions also include *video demonstrations* of
  installation and verification.
- We haven't had that many installation problems, but also we keep the
  requirements simple.
- Helper introduction is right before software install time, so
  helpers can stay and help with install if they want.
- *Design to be easy to install and get set up.*

### Other notes

- Make breakout sessions as long as possible: 10 minutes is really too
  short.  20 minutes is a good minimum time.
- Be very clear about exercise expectations
- Keep HackMD updated as a log.
- Don't combine breaks and breakout times.
- The more people you have, the more diverse audience you have and the
  more people overwhelmed and under whelmed.



## Workshop collaborations

Why limit ourselves to CodeRefinery workshop?  Why not use our network
and techniquess for more

- Case study: [Python for Scientific
  Computing](https://aaltoscicomp.github.io/python-for-scicomp/)
  - Started by Aalto
  - Announced to CodeRefinery, five more instructors from three
    countries joined.
  - Rapid collaboration, taught course shortly later.
  - Announced to all institutions.  Some places had physical rooms,
    some were pure online
  - Also streamed
  - It was much more fun and less stressful to work together

- We want to continue this kind of collaboration in other workshops.


