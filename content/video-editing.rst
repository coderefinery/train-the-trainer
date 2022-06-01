Video editing
=============

Video recordings could be useful for people attending a course later,
but also are (perhaps more) useful for **immediate review and catching
up after missing a day in a workshop**.  For this, they need to be
released immediately, within a few hours of the workshop.
CodeRefinery can do this.



Primary articles
----------------
* Video editor role description:
  https://coderefinery.github.io/manuals/video-editor/
* ffmpeg-editlist: the primary tool: https://github.com/coderefinery/ffmpeg-editlist

  * Example YAML editlists:
    https://github.com/AaltoSciComp/video-editlists-asc


Summary
-------

* Basic principle: privacy is more important than any other factor.
  If we can't guarantee privacy, we can't release videos at all.

  - Disclaimers such as "if you don't want to appear in a recording,
    leave your video off and don't say anything", since a) accidents
    happen especially when coming back from breakout rooms.  b) it
    creates an incentive to not interact  or participate in the course.

* Livestreaming is important here: by separating the instruction from
  the audience audio/video, there is no privacy risk in the raw
  recording.  They could be released or shared unprocessed.

* Our overall priorities

  1) No learner (or anyone not staff) video, audio, names, etc. are
     present in the recordings.
  2) Good descriptions.
  3) Removing breaks and other dead time.
  4) Splitting videos into useful chunks (e.g. per-episode), perhaps
     equal with the next one:
  5) Good Table of Contents information so learners can jump to the
     right spots (this also helps with “good description”.)



Exercises
---------

.. exercise:: Use ffmpeg-editlist to edit this sample video

   Prerequisites: be able to install ffmpeg-editlist.  This is simple
   in a Python virtual environment, but if not the only dependency is
   ``PyYAML``.  ``ffmpeg`` must be installed on your computer outside
   of Python.

   * Download the sample video: link TODO
   * Copy a sample editlist YAML
   * Modify it to cut out the dead time at the beginning and the end.
   * Run ffmpeg-editlist

.. solution::

   .. code:: yaml

      TODO

   .. code:: shell-session

      ffmpeg-editlist editlist.yaml ...TODO


See also
--------

(none yet)
