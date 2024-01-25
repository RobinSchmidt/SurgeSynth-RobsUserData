These are my (Robin's) personal files for the Surge XT software synthesizer. On Windows in 2024, the
content of this repo needs to locally reside in:

  C:\Users\UserName\Documents\Surge XT

for Surge to able to use it. That means, to make use of that data, one needs to clone the repo to a
local folder and then rename the folder from "SurgeSynth-RobsUserData" to "Surge XT" and move it 
into:

  C:\Users\UserName\Documents\  

But of course, anyone who has Surge installed will already have their own user data folder in that
place. So in reality, unless you are me (which you aren't because I am already me), you will 
probably want to somehow combine your own user data with the data from thisn repo - most likely by 
just copying some subfolders of the "Patches" folder into your own 

  C:\Users\YourUserName\Documents\Surge XT\Patches

folder. 

----------------------------------------------------------------------------------------------------
I myself need to set up GitHub Desktop in such a way that

  C:\Users\MyUserName\Documents\Surge XT

becomes the local copy of the

  https://github.com/RobinSchmidt/SurgeSynth-RobsUserData
  
repository. This can be done as follows: Open the GitHub Desktop application and go to:

  File -> Clone Repository

then go to the URL tab and paste:

  https://github.com/RobinSchmidt/SurgeSynth-RobsUserData

into the "URL" field and edit the "Local Path" field to 

  C:\Users\rob\Documents\Surge XT

where I have replaced the "MyUserName" placeholder with my actual user name on that machine which 
is "rob" and then click the "Clone" button. After the cloning is finished, the Surge XT folder 
should be in its right place and at the same time serve as the local copy of the repo. When 
TortoiseGit is installed, the folder should have a green check/hook in the Windows Explorer and it 
will be possible to commit and push the updates via GitHub Desktop.

----------------------------------------------------------------------------------------------------
Notes: 

The MarkDown renderer on GitHub messes up the path names when using things like "[UserName]" instead 
of "UserName". That's why I'm not using the common convention for indicating placeholder strings 
with square brackets here.

The file README.txt explains how this folder is supposed to be used by Surge. It was not written by 
me but rather created automatically by the Surge installer.