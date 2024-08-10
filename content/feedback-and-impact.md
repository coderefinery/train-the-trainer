# How we collect feedback and measure impact

:::{objectives}
- Discuss how one can collect feedback from learners ("what can we improve?").
- Discuss how we convert feedback into actionable items.
- Discuss how we measure the impact of teaching ("did we achieve our goals?").
- Discuss the "why".
- Get to know the reasons and sources of inspiration behind major lesson and workshop updates.
:::

:::{instructor-note}
- Discussion: 20 min
- Exercises: 10 min
:::


## Asking questions the workshop

- Motivation: Know your audience.
- Until 2021 we had a pre-workshop survey:
  - Data, questions, and notebook: <https://github.com/coderefinery/pre-workshop-survey/>
  - Zenodo/DOI: <https://doi.org/10.5281/zenodo.2671578>
- After 2021 we incorporated some of the questions into the registration form.
  - Easier registration experience for participants.
  - After 5 years of running workshops, we had a good idea of what to expect.


## Collecting feedback as we teach

- Each day we ask for feedback in the collaborative notes.
  - One good thing about today
  - One thing to improve for next time.
  - Any other comments?
- During the workshop we sometimes check in and ask about the pace, example:
  ```
  How is the speed so far? (add an "o")
  - Too fast:   oooooo
  - Too slow:   ooo
  - Just right: ooooooooooooooooooo
  ```
- We publish all questions, answers, and feedback. Example: <https://coderefinery.github.io/2024-03-12-workshop/questions/>
- How we follow up:
  - Some problems we can fix already before the next workshop day.
  - We convert feedback/problems into GitHub issues and track these close to the lesson material.


## Trying to measure impact with longer-term surveys

- Motivation: Understand the long-term impact of our workshops. Have something to show to funders.
- 2024 post-workshop survey:
  - Blog post: <https://coderefinery.org/blog/2024/08/10/post-workshop-survey/>
  - Questions, notebook, and figures: <https://github.com/coderefinery/2024-post-workshop-survey>
  - Zenodo/DOI: <https://doi.org/10.5281/zenodo.13292363>
- 2021 version:
  - Data, questions, notebook, and figures: <https://github.com/coderefinery/post-workshop-survey>
  - Zenodo/DOI: <https://doi.org/10.5281/zenodo.2671576>
- How we use the results:
  - When reporting to funders.
  - When planning future workshops and bigger picture changes.


## Lessons learned

- Think about how to measure impact/success from the beginning.
- **Make the feedback and survey results public**.
- Make the results persistent and citable.
- Have a mechanism to follow-up on feedback.
- Anonymization is more than just removing or dissociating names.
- Take time designing your survey and collect feedback on the survey itself.


## Take time designing your survey

We are not experts in survey design but we reached out to RISE Research
Institutes of Sweden to get feedback on our survey questions. They provided us
with a lot of valuable feedback and suggestions for improvements.
Below are few examples.


### Example 1

First version of our survey question about impact:
- "Do our workshops help to save time in future?" Please quantify in hours saved: ...

Feedback:
- Difficult to answer.
- Since when? Until all eternity?

```{figure} feedback-and-impact/survey-impact1.png
:width: 80%
:class: with-border
:alt: Screenshot of earlier version of the survey question about impact.

Earlier version of the survey question about impact.
```

Feedback:
- The question "Do our workshops help to save time in future?" is unspecified,
  unnecessary, and leading.
- "No time saving" does not match the wording "save time" in the question.

```{figure} feedback-and-impact/survey-impact2.png
:width: 80%
:class: with-border
:alt: Screenshot of later version of the survey question about impact.

Later version of the survey question about impact.
```

- The wording "have you saved" now matches "No time saved".


### Example 2

- Earlier version:
  ```
  Would you judge your code to be better reusable/reproducible/modular/documented
  as a result of attending the workshop?

  - More reusable
  - More reproducible
  - More modular
  - Better documented
  - None of the above
  ```
- Feedback: The question is not neutrally formulated and risks leading to
  over-reporting of yes answers. Consider balancing so that the questions are
  formulated more neutrally.
- Reformulated to:
  ```
  After attending the workshop, would you judge your code to be
  more reusable or not more reusable?

  - My code is more reusable
  - My code is not more reusable
  - Not sure
  ```


### Example 3

- Early version:
  ```
  What else has changed in how you write code since attending the workshop?

  [free-form text field]
  ```
- Feedback: Leading and assumes that something has changed.
- Reformulated to:
  ```
  Has anything else changed in how you write code for your research after
  attending the workshop?

  [free-form text field]
  ```


### Example 4

- Earlier version:
  ```
  Has it become easier for you to collaborate on software development with your
  colleagues and collaborators?

  - Yes
  - Not sure
  - No
  ```
- Feedback:
  - Leading question.
  - Avoid "Yes" and "No" response options because respondents tend to answer
    "Yes" if that option is available, leading to a risk of measurement error
    (acquiescence bias).
  - Do not place "Not sure" in the middle of the scale because it captures
    participants who actually don't know and should therefore be placed at the
    bottom instead of in the middle of the scale.
- Reformulated to:
  ```
  After attending the workshop, has it become easier or not for you to
  collaborate on software development with your colleagues and collaborators?

  - Collaboration is easier
  - Collaboration is not easier
  - Not sure
  ```


## Exercise: Group discussion (10 min)

:::{exercise} Group discussion using the collaborative notes
- What tricks/techniques have you tried in your teaching or seen in someone
  else's teaching that you think have been particularly effective in collecting
  feedback from learners?
- Can you give tips or share your experiences about how to convert feedback
  into actionable items?
- How do you measure the impact of your teaching? Any tips or experiences about
  what you have tried or seen other courses do?
- Anybody knows of good resources on survey design? Please link them in
  the collaborative notes.
:::
