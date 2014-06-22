Server Details
==============

We have decided that it would be good to have a physical server present wherever we are incase we lose access to the internet.  The server will need to have everything required to support the team.

Version Control (Git)
---------------------
As a team we have decided to use Git, and GitHub to store and manage our code and documentation.  The server should have git installed and allow remote pushes to it (SSH/HTTP).  It should also keep in sync with GitHub to allow easy transistion if the internet goes down.

Some options for a friendly web interface are [Gitorious](https://gitorious.org/) and [Gitlab](https://about.gitlab.com/) but this is not necessarily a requirement.

Dashboard
---------
We've discussed at meetings the idea of having a progress dashboard.  Some ideas of things we could show are:
* TravisCI results
* Git commits
* Twitter feed

[Dashing](http://dashing.io/) is a framework that a few of us have experiance with.  It is written in **Ruby**.

Storage
-------
Storing installers for common tools, and the ablilty to mirror datasets locally.  This should be easily accessible.  So, HTTP presentation, and potentially SMB/CIFS.