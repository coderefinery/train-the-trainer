(obs-config)=

# Open Broadcaster Software (OBS) setup

:::{objectives}
- See how to configure OBS using the pre-made CodeRefinery scene
  collections
- Modify the collections to suit your needs.
:::

:::{instructor-note}
- Teaching: ?? min
- Hands-on: ?? min
- Q&A: ?? min
:::

:::{See also}
* The previous episode {doc}`obs`
* [OBS theory in CodeRefinery manuals](https://coderefinery.github.io/manuals/obs/)
:::


In this lesson, we'll see how to configure OBS from scratch for your
purposes.  We'll do this by deleting the instructor's configuration
and trying to recreate it

This section is short, since it has never been done before: we'll just
give it a short and update the lesson later.


## CodeRefinery OBS configs

- CodeRefinery configs are shared in a repository:
  <https://github.com/coderefinery/obs-config>
- These can be imported to pre-configure some things
- There are two types of configs:
  - Profiles
	- Servers, resolutions, audio, video, etc.
  - Scene collections
    - The graphical layouts.


## Installing the OBS config

- Clone the git repository.
- Import the profile and scene collections under their respective
  menus.


## Initial setup

- Click through each menu and change anything that is needed
- Set the streaming server

:::{demo} The instructor will go through the setup.

- Reset configuration: `mv .config/obs-studio/
  .config/obs-studio-old/`
- Import `profiles/TeachingStreamingv3/`
- Import `scenes/TeachingStreamingZoomv3.json`
:::



## Set up the remote control

- Create a Python environment and install it: `pip install https://github.com/coderefinery/obs-cr/archive/refs/heads/master.zip`

- Run it: `python obs_cr/control.py localhost:4445 TOKEN
  --broadcaster`
- There are more options but let's not cover them yet... and leave
  this for a hands-on session.


## Setup before each course

- Re-confirm audio
- Re-confirm each scene
- Test everything
- rkdarst has a [rather long
  checklist](https://docs.google.com/spreadsheets/d/1g8Bc_76OPcv1vYWtB54wz6HsXQcb3B1GtQFga4Oanw4/edit?gid=0#gid=0),
  but each individual step is short.


## Q&A

We'll answer audience questions.


:::{keypoints}
- Most of our configuration has been OBS may seem complicated, but it's a graphical application and most
  pieces make sense once you know how it works.
:::
