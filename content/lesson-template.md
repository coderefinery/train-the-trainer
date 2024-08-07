(lesson-template)=

# Lesson template

:::{objectives}
- Undertstand how the CodeRefinery lesson template is used to create new lessons
:::

:::{instructor-note}
- Teaching: ? min
- Exercises: ? min
:::

## [Sphinx](https://www.sphinx-doc.org)

- We build all our lesson material with Sphinx
- Generate HTML/PDF/LaTeX from RST and Markdown.
- Many Python projects use Sphinx for documentation but **Sphinx is not limited to Python**.
- [Read the docs](https://readthedocs.org) hosts public Sphinx documentation for free!
- Also hostable anywhere else, like Github pages, like our lesson material
- For code a selling point for Sphinx is that also API documentation is possible.

Sphinx is a doc generator, not HTML generator. It can:

- Markdown, Jupyter, and ReST (and more...) inputs. (jupyter-book is Sphinx, so anything it can do we can do. This was one of the inspirations for using Sphinx)
- Good support for inline code. Much more than static code display, if you want to look at extensions.
- generate different output formats (pdf, epub, etc)
- strong cross-referencing within and between projects

## [CodeRefinery lesson template](https://github.com/coderefinery/sphinx-lesson-template)

It is "just Sphinx" - with extensions:
 - The addition is various directives (boxes) tuned to lesson purposes
 - In addition it provides a sample organization and template repo you can use so that lessons look consistent
 - Tabs: they are very important for us and allow us to customize in-place instead of copying everything and fragmenting lessons
 - Emphasize lines: they make it easier to spot what has changed in longer code snippets
 - You can write Markdown (I know it's an extension and a flavor of ...) and we really like and use MyST parser
 - It's fine if you use some other static site generator or git-based lesson method.

:::{exercise}
Find the lesson template on Github, create your own repository in your own namespace using the template and play around with the features:
- How can you do tabs?
- How can you highlight lines in code boxes?
- How can you change color, logo and fonts?
- What directives are available?

> Some solution here
:::




:::{keypoints}
- Here we summarize keypoints.
:::
