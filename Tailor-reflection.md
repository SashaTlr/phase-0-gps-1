#Phase 0 Week 2 - GPS 1.1 Version Control and Git

##What git concepts were you struggling with prior to the GPS session?
It was interesting because I felt comfortable with the basic git concepts before we started the pairing session, and realized that I had just gotten used to the steps but didn't understand it as well as I thought I did. I realized that I don't understand feature branches as well as I thought, and added extra steps in the first release by creating a new branch before creating the reflections file.

##What concepts were clarified during the GPS?
I hadn't seen the command git push -u origin master. I learned that git push on its own assumes that a remote branch already exists and is being tracked by the local branch. -u will create the remote branch if it doesn't exist yet and will set the upstream repo for git pull/status tracking. I haven't seen a need to use this in practice, so I am still not entirely sure when to use it, but will practice the command.

We also clarified how merge conflicts can be created, and how version control works with multiple people working on the same remote.

##What questions did you ask your pair and the guide?
I was confused as to how we avoided a merge via Github for release one. The way that it was explained was that at this stage, the repo was empty, and only one person was working on it. This meant that we didn't need to create a feature branch, and were able to add the new file directly to the master. From here, we can push directly to the remote master without creating a pull request in GitHub.

##What still confuses you about git?
I'm still not clear as to how we didn't need to create a pull request in the first release. The master branch in the remote repository still differed from the local copy since the local now had a file added. Shouldn't there still be some sort of approval of this addition, even if the remote repo was empty?

##How was your first experience of pairing in a GPS?
Pairing was good. Since the instructions were quite explicit, I found that when I was driving, I still would read the instructions, and then go ahead and implement the steps. I think I stepped back and let my partner navigate once I noticed that I was doing this. I found driving kind of difficult as I wasn't sure when my partner needed me to navigate versus when he understood what to do next. Since we're pairing remotely, it was difficult to pick up on body language to see where he was in the step and if I needed to clarify or navigate more.