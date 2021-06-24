# gitb - a web shell for  
This repo exists to allow a simple, temporary web shell for Carpentries' git lessons.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bgue/gitb/HEAD)

On a remotely delivered We're running across learners who don't have access to install the packages for git or openrefine. This repo is a bare-bones option to allow a MyBinder container to be run. 

Users should:
 1. Launch the binder link
 2. In the Jupyter file browser, locate the 'New' drop-down near the top-right
 3. Select New Shell.
 4. (Optional) Change the local prompt by setting the env variable PS1=$  at the command prompt.

The resulting shell has git available. Note that after ten minutes of inactivity, the entire container will be recycled, removing your content!

