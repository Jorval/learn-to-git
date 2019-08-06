# learn-to-git
A repo just to learn git

Hi,
This Repo is only for me to learn git and how to use the Atom Editor in conjuction with github.
Also i like to try out Kraken which i have since Beta Relase but never ever really used it because i never got warm with git or other versionsystems.

Yesterday i decided it's about time!

So if you stumbled over this project leave an issue or another form of contribution to help managing the task a git repo offers.

thanks. jorval

---

# Pimping Atom for Github use
i found a package that let me use git commands directly from Atom without switching to my terminator session. Awesome. Installing it led's to a LOT more of these packages for Atom. Diversity is not a crime right!<br />
so i stick with the first package i found which is called **Git-Plus**<br />
if that sucks ... i'll try the next package and so on.

# Pimping Atom Part 2
ok... as commiting and status doesn't worked by me as expected with Git-Plus i now installed **git-control**. Whe i open up the corresponding Feature in atom it say this is not a git project.<br />
maybe this was also the problem with Git-Plus. don't know, still investigating this.

# Back to Git Plus and now i Understand how it works.
And God it **WORKS!**<br />
Good have to learn how to invoke the palette and more spezific that this Palette only consist of the Git commands. Invoke it with CTRL+SHIFT+H and all the needed commands are there at your hands.<br />
GREAT!

# Ok, something strange
normally when i push my repo with git on the terminal it asks me for user and password.<br />
Git-Plus plugin didn't asked, and i didn't mind. I don't know i there is a special settings where i have to put my credentials, but i dont like it taht way. it should ask me! i will try it a bit more and than search the Git-Plus issues or open a new one ;) Still love Git-Plus!

# Got it. Git-Plus works with sshkeys
so i have to configure the ssh keys for autologin in github.<br />
hope pushing now works also. thi spart is mainly to test this.
OK, didn't worked at the first try. i updated the git config so it changed from https to ssh.
giving it another try.

# Ok Pulling works fine.
Now a nother test with pushing. this is a copy of the repo in a different place on my local maschine that i have cloned with gitkraken via ssh.
hopefully this means it also pushing works now with the same key.<br />
OK that look fine. pushing now worked. i deleted my selfgenerated sshkey again from github because iam sure its only using the one from gitkraken.<br />
will check the config for further learning. again atom with Git-Plus is awesome, its real fun to work with these tools.

OK, deleting the selfgenratedkey was dump it uses this one for pushing. i re-added it and now it works fine again. learning git is great, esp. making mistakes ;) no mistakes no progress right?!

---

ok now i try to make some use of the webhooksystem and i need a push for it to work! ;) so this is the only prupose, also now that i use vscode with git in my daily routine, using the terminal git client becomes somewhat obsolete. this is also a good practice to see if i remember all the commands and workflow on the console correctl! as always nothing of intterest here ;) over and out!
