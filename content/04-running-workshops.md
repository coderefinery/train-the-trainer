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


# Running a workshop


## Online teaching discussion

```{discussion} Discussion: Online vs in-person

In notes:
- Compare and contrast the benefits of online teaching with
  in-person.
- {advantage, disadvantage} × {content, presentation}
```


## Arranging the workshop

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


## Preparing for the workshop

- Train helpers:
  [manuals](https://github.com/coderefinery/manuals/#helper-training).
  Good helpers can make a big difference.
- Get participants ready
  - Right equipment
  - Right mindset
  - Installation help in advance!

## Running the workshop

- Mostly nothing specific to CodeRefinery here, but we have many of
  our own checklists:
  - [in-class
    checklist](https://github.com/coderefinery/manuals/blob/master/presenting.md)
  - [helping and teaching](https://github.com/coderefinery/manuals/blob/master/helping-and-teaching.md)
- Online workshop have their own checklists (more below):

## Online procedures

Main article: [Online training manual](https://github.com/coderefinery/manuals/blob/master/online-training.md)

For the obvious reason in March 2019, we transitioned to online
workshops.
- We have less interaction with learners
- We can reach many more people at once
- You can't just move things straight to online: it actually requires
  thinking about it.  Details at the bottom.

- Zoom
  - Not the most ethical platform, but worked quickly and has good
    features for group work.
  - [Zoom mechanics: instructions for
    students](https://github.com/coderefinery/manuals/blob/master/zoom-mechanics.md).
  - Being able to divide people into breakout rooms is a key point to
    scale to many people
  - Breakout room helpers need training: [Helpers managing breakout rooms](https://github.com/coderefinery/manuals/blob/master/breakout-rooms-groups-help.md)

- HackMD
  - Online "collaborative notes"
  - HackMD is alternative to Google Docs
- We found that it takes about the same amount of time as in-person,
  but you much longer breaks and much less per day. (5 min too short,
  15-20 min best.  Max 3-4h/day.)


## Lessons learned from our online Mega-CodeRefinery workshop

In May 2020, we have a "mega-workshop" online: 150 people registered,
120 were accepted, and our audience was around 90-100 each day.

The workshop *did* work well, and required preparation but not so much
more than an in person or online workshop of 20-30 people.

However, you *have* to think about it differently and prepare
appropriately.

> ## Online workshop differences
>
> What do you think you have to do differently for a massive online
> workshop.  Answer in the collaborative document / discuss in
> breakout rooms.
>
> 1. What are the possible problems/disadvantages?
> 2. What are the advantages?
> 3. How do you have to prepare differently?
> 4. What is your experience with online teaching?
{: .discussion}

### Case study: Mega-CodeRefinery and Finland HPC Kickstart

- Mega-CodeRefinery
  - Audience of around 90-100
  - "bring your own breakout room" (see below)
  - 3 days/week, 6 days total
  - Lessons as normal in CodeRefinery
- HPC Kickstart
  - 250 registered, ~180 max participants
  - Multi-university: local differences made this much harder to manage.
  - Breakout


## Main differences with mega-online

- Less tolerance for problems
- More diversity in skill levels

### Key adaption mechanisms

This will be later published in a final report

- Breakout rooms
  - Consistent members over sessions and days - form community
  - Requires Zoom naming like "(4) First Last", so that rooms can be
    managed efficiently.
- Teams
  - Teams adapt tools better when there are multiple adopters.
  - Offer team registrations
  - Bring your own helper: "bring your own breakout room"
  - Anyone bringing own helper can be accepted
  - Must already be considered at the registration phase!
- Helpers
  - [Helper training for breakout
    rooms](https://github.com/coderefinery/manuals/blob/master/breakout-rooms-helping.md)
  - "helper sessions" - two the previous week, expect all helpers to
    attend at least one to learn about what to do
  - Recommend make these sessions 60 minutes, prepare a lesson which
    demonstrates all the main tech and also preparation
  - Helpers: stay in each room consistently
  - Expert helpers: move between rooms, make sure things stay on track.
- Installation help
  - Two installation help sessions the week before
  - Expect everyone to attend one, otherwise you are on your own.
  - Right after the "helper intro sessions" - helpers stay and give
    install help.
- HackMD: Asking questions during the workshop
  - Most questions asked via collaborative notes, not by voice.
  - Voice still allowed.
  - This provides a safer way for most people to ask questions - and
    without interrupting the flow
  - And multiple people can answer, asynchronously
  - Beware: don't go too in-depth.
  - Always write at the every bottom (only one palace needs to be watched)
  - HackMD worked even with the 180-person workshop.  We recommend
    keeping the length short, and having people switch to view mode if
    more than 50 people.
- Recording
  - With 100 people, main room is already quite silent, thus we lose
    less by recording.
  - Collaborative notes provide a way to ask questions other than
    voice which would be recorded.
  - Breakout rooms never recorded.
- Lesson adjustments
  - Make breakout sessions as long as possible: effectively, assume 5
    minutes overhead each time you start a breakout session.
  - Don't combine breaks and breakout time
  - Be very clear about exercise expectations: write down end time,
    expected outcomes, links for exercises.  "Meta-talk": the more,
    the better.
  - Also discuss overall expectations: more people will be both
    overwhelmed and underwhelmed.  Set expectations right: is this
    basic or advanced?

- Roles:
  - Zoom host (Zoom tech, watches chat)
  - HackMD master (watches, answers questions, organizes)
  - Instructors
  - Helpers
  - Expert helpers
  - All of these should be different, even if in practice everyone
    does a bit of everything!  Otherwise cognitive load becomes too
    much.
