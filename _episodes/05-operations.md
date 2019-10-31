---
layout: episode
title: "Running workshops"
teaching: 20
exercises: 10
questions:
  - "What are the steps for organizing a CodeRefinery workshop?"
  - "How should I prepare before teaching or helping in a workshop?"
objectives:
  - "Learn how to use the manuals to organize and teach a workshop."
keypoints:
  - "There are many aspects to consider to deliver a successful workshop."
  - "CodeRefinery maintains a number of manuals - use them when preparing a workshop."
---

## Organizing a CodeRefinery workshop

Anyone can organize a CodeRefinery workshop and teach the CodeRefinery lessons which are 
licensed under [CC-BY](https://creativecommons.org/licenses/by/4.0/).
However, making it a successful workshop requires careful planning and preparation. Here we will go 
through practical aspects of organizing a workshop. 

> ## Workshop manuals
> CodeRefinery maintains a number of [workshop manuals](https://github.com/coderefinery/manuals/) 
> with practical tips and checklists. We will be referring to this material below.
{: .callout}

## [Before the workshop](https://github.com/coderefinery/manuals/blob/master/workshop-administration.md#before-the-workshop)

- Select workshop coordinator
- Instructors and helpers
- Lecture room
- Advertising the workshop
- Communication with registered participants 
- Practicals

> ## Set up a workshop webpage
>
> 1. Go to the [workshop template repository](https://github.com/coderefinery/template-workshop-webpage). 
> 2. Click the green "Use this template" button to import the template to your own account. 
>    Name the new repository to include a date and a location, e.g. "2019-12-24-stockholm".
> 3. Clone the new repository and inspect the files. Open `index.md`, update some fields and commit the changes.
> 4. Push the commits. The workshop page should now be served on GitHub Pages
>    (e.g., *https://username.github.io/2019-12-24-stockholm/*).
{: .task}

---

## [Pre-workshop survey](https://github.com/coderefinery/pre-workshop-survey)

It is very useful to ask future workshop participants to fill a pre-workshop survey before 
attending a workshop. The survey should probe the participants' previous experience 
with different tools and programming practices, which operating system the participants use 
and what lessons they are most interested in. 

The questions that are currently asked in the CodeRefinery 
[pre-workshop survey](https://github.com/coderefinery/pre-workshop-survey)
are the following:
- What is the operating system that you will use during the course (on your laptop)?
- Which version of operating system are you using? If your operating system is Linux, which distribution are you using? 
- Are you using version control? If yes, which?
- Which programming languages are you using or will you use in your projects?
- Are you using automated testing in your programming project(s)?
- Are you using code coverage analysis in your programming project(s)? These are tools and services like Gcov, Cobertura, Codecov, Coveralls, Code Climate, etc.
- Are you employing code review in your programming project(s)?
- Are you using the Travis or Jenkins or GitLab CI continuous integration service in your programming project(s)?
- How do you document your code?
- Are you using a web-based repository for your code(s)? Which ones?
- How would you describe your programming experience?
- How comfortable are you with the Unix/Linux command line working in a terminal window?
- Are you using an integrated development environment (IDE) for your programming project(s)?
- Please specify your main academic discipline. Please take the entry which is closest to your main field of study/work.
- Please select the sessions that you are most interested in.
- What do you expect to get from this course?

> ## Discussion: Pre-workshop survey questions and results
> 
> - Take a moment to read the survey questions. Is there anything you would want to add? Or remove?
> - How do you think the survey results look like for past workshops? Have a look at the
>   [survey repository](https://github.com/coderefinery/pre-workshop-survey) which shows the 
>   main results, and compare them with your expectations.
{: .task}

---

## Preparing lessons

- Go through the lesson material you will be teaching and think about how you 
  intend to teach it, and how much time you will be spending on each episode.
- Are there any unsolved issues that you can fix?
- Go through the instructor guides of the lessons you will be teaching. 
  - Review the intended learning outcomes, and try to keep these in mind while teaching.
  - Try to memorize the typical pitfalls and common questions.
- Go through the [lesson presentation hints](https://github.com/coderefinery/manuals/blob/master/presenting.md).
- Go through the [helping and teaching guide](https://github.com/coderefinery/manuals/blob/master/helping-and-teaching.md),
  and request all helpers to go through it too.

---

## [During workshop](https://github.com/coderefinery/manuals/blob/master/workshop-administration.md#during-workshop)

- Give an introductory talk, see [https://github.com/coderefinery/workshop-intro](https://github.com/coderefinery/workshop-intro).
- Have a 10 minute ice-breaker session where participants and instructors introduce themselves 
  and either describe their research in 2-3 sentences or what they hope to get out of the workshop.
- While teaching, keep [these tips](https://github.com/coderefinery/manuals/blob/master/workshop-administration.md#during-workshop) in mind
- Don't start off with tech details, say why this is important.
- Try to [stick to the material](https://github.com/coderefinery/manuals/blob/master/presenting.md#try-to-stick-to-the-material),
  although some excursions are useful.
- [Wrap up](https://github.com/coderefinery/manuals/blob/master/presenting.md#wrap-up),
  say what you taught and why, and what comes next.

---

## End of workshop

- Give credit to those who contributed and helped.
- Say some [final words](https://github.com/coderefinery/workshop-outro).

---

## Post-workshop

- Process final feedback and distribute to co-instructors (e.g. type up in shared document)
- Debrief with instructors.
- Process certificate requests.




