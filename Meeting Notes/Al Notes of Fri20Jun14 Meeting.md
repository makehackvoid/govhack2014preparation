#Prelim
Hello,
-  These are my notes on the MHV Meeting Fri20Jun14.
-  The environment is new for me and written notes help me move ahead in incremental steps (and I have posted these notes as they may be helpful for others).
-  Unfortunately my brain had shut down half way through the meeting =>
  - please excuse any errors and/or omissions, and
  - if you are able, please correct this post and/or add detail as you see fit.
Thanks, AL.
Sun 22Jun14

#Use of Wiki
Rather than use a Wiki we will use notes within folders within the code so the documentation synchronises alongside the code.
[ ] Redo [Video Plan Wiki](https://github.com/makehackvoid/mhvdb2/tree/master/tests) folder.
[ ] Post my 5Jun14 Meeting Notes.

#Approach
We will use Continuous Integration (CI) with Feature Driven Milestones.
##Continuous Integration (CI)
- CI means everyone continually tests the code they working on so we don't drift from a working app.
- The minimum test will be "the App ran in Flask" ([Flask](http://flask.pocoo.org/) Web Site Creation tool).
- We also will use [Travis](http://docs.travis-ci.com/user/ci-environment/) CI tool.
- Additional Tests can be added and run automatically.
##Feature Driven Milestones
- A Milestone will describe Features we wish to create in the application.
- Features are grouped into Milestones.
- Issues are linked to Milestones.
- People work on Issues.
- Before you raise a new Issue it should be checked by another.
##Study mhvdb2
- Brenda showed us MHV's [mhvdb2](https://github.com/makehackvoid/mhvdb2).
- _Post Meeting Note_ The mhvdb2 [README.md](https://github.com/makehackvoid/mhvdb2/blob/master/README.md) includes a pointer to [contributing.md](https://github.com/makehackvoid/mhvdb2/blob/master/contributing.md) with "details of how to setup development environment and suggested workflow." 
- [ ] Download and study [mhvdb2](https://github.com/makehackvoid/mhvdb2)'s structure, particularly the  [tests  folder](https://github.com/makehackvoid/mhvdb2/tree/master/tests) and [contributing.md](https://github.com/makehackvoid/mhvdb2/blob/master/contributing.md).

#GovHack2014 Collaboration
- Based on last years experience we will bring our own network infrastructure as backup.
- Max has built a Virtual Machine (VM) that is available for others to use.
- [ ] Q. Our local Git architecture that supports this and our approach? _(My brain had shut down when this was discussed.)_
- [ ] _Post Meeting Note_ Raise Issue on how to get and spin up a copy of Max's VM.

#Background Reading on Git and GitHub
- [GitHub Help on Forking a Repository](https://help.github.com/articles/fork-a-repo)
- Scott Chacon's [GitHub Flow](http://scottchacon.com/2011/08/31/github-flow.html) which references [A successful Git branching model](http://nvie.com/posts/a-successful-git-branching-model/).
- [Pro Git book](http://git-scm.com/book) by Scott Chacon, 2009, which includes at Section 1.3.5, The Three States:
Pay attention: This is the main thing to remember about Git if you want the rest of your learning process to go smoothly. Git has three main states that your files can reside in:
  - **committed** - means that the data is safely stored in your local database
  - **modified** - means that you have changed the file but have not committed it to your database yet, and
  - **staged** - means that you have marked a modified file in its current version to go into your next commit snapshot.