build-talk-scripts
==================

There are many lone wolf developers out there that don't have the benefit of human interaction. Heck, most don't even wear pants. 
And honestly, we are OK with that! However, too much time alone without some kind of interaction causes you to do bad things (*cough*The Shining*cough).
This is where build-talk-scripts comes in. Never be lonely AGAIN!

Simply install the .sh files included in the repository in your favorite folder (mine is ~/ because, well that is a cool path string). Next, go into 
Xcode and open the Edit Behaviors dialog. Under the 'Build succeeds' option, uncheck the 'Speak announcement...' if checked, and select the 'Run...' 
option, then pick the build-talk.sh script file. Do the same for the 'Build fails' option, except pick the fail-talk.sh instead.

If this doesn't work, make sure to set the execute flag on the script files (if you don't know how to do this, stop coding immediately and go learn
how to dig ditches or something).

FAQ:
What are the empty strings at the end of the set thePhrases line for?
These empty strings make sure that you don't get a phrase on every single build. Add more empty strings to get less talk.

The phrases that you put in the file are stupid.
FORK YOU!

