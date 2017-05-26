---
layout: post
title: So You Wanna be a Hacker

---

#So You Wanna be a Hacker
##Code Cracker, Slacker
###Morning Warmup 5/26

##1. What I Learned My First Week of Camp

The biggest thing I learned was getting back into the habit of discovery. I've always been a lifelong learner, but being back in the classroom brings a different tenor to it. Remembering the feeling of uncovering something completely new, finding something familiar and yet just a little beyond your cognitive grasp and then finding it and wrestling it into sumbission.

##2. Why Did I Join a Web Developer Bootcamp?

Good question. After years in restaurant management, I found myself in a job where I was good at it, but I was limited in terms of upward mobility. At some point I wanted to make the jump but with only a history major and 11 years in foodservice, making the jump can be daunting when you no longer want to do either of those things. Once upon a time I had an interest in coding and math, but it had been shelved over years and at some point, the gap seemed to broad to cross. Technology had spun too many times around and left me behind. I first heard of bootcamps in California and thought about it but moving away for months from family seemed like too big a moonshot, but when this one came to my attention, it offered a great opportunity, a bridge to the other side. This was my chance and I took it.

##3. Explain a technical concept

Git is a great tool for managing versions but every so often you will come across merge conflicts, places where git attempted to update two versions of the same file and was unable to do so. These must be resolved but git will still merge the file, with errors and some signals around the conflict zone. For example:


<!--- Merge Conflict Sample -
<html>
  <head>

<<<<<<< HEAD
    <link type="text/css" rel="stylesheet" media="all" href="style.css" />
=======
 
>>>>>>> master

  </head>
  <body>
    <h1>Hello,World! Life is great!</h1>
  </body>
</html>
-->

In the first section that spans from '<<<<<<< HEAD' until the '=======' is in the 'HEAD' version, which is the most recent commit. the part that runs from the '========' to the '>>>>>>>>> master' is what was stored in the the master branch of the repository. To resolve the conflict, you need to delete the added symbols from git and decide which of the code you need to keep, deleting the rest. Once you've done that, you can save your changes and make a new commit to push the file, conflict free!
