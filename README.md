## EU4 AUSTRALIA MULTIPLAYER MOD
This mod is used in the EU4 Australia discord community, and removes the most egregious vanilla imbalances, and adds our own changes :)

Our Discord:  
` https://discord.gg/y76Wdja`

# Usage
To begin using the git repo, a good starting point are the github instructions here:
https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository

To get started using the git command line (eg. Git Bash), the following commands are your friends, in rough order of intended usage:  

Create a branch, which you can add your changes to, and set it to track the GitHub repo
>git push --set-upstream origin *BranchName*  


 Stage a file to git tracking (eg. if you create a new file, or make changes). 
>git add *Filename*


 Commits changes you've added above to git tracking; Until you commit no changes are actually recorded, and they can be lost
>git commit -m "*Message*"
 

 Push your local changes to the upstream git repository, making them visible to everyone else
>git push
 

 After a mod update, or merged changes on the upstream repo, you may update your local copy
 >git fetch

After the above process, your changes can be added to the mainline mod, assuming everyone else likes them :D

Have fun modding. I suggest you discuss changes you'd like to make to the main mod beforehand, if you want to be sure your changes are included!

# Local modding
1. Open the EU4 Launcher
2. Go to "all installed mods" on the sidebar
3. Click on "upload mod"
4. Click on "create mod"
5. Name, version, tag and assign a path to the mod (eg. EU4AU, 0.01, mod/EU4AU, balance)
6. Create the mod
7. Open the mod folder path. It will probably look like this:
"C:\Users\\[username]\Documents\Paradox Interactive\Europa Universalis IV\mod\EU4AU"
8. Clone the git repositary to the created folder 
9. Move the files inside the "EU4-Australia-Mod" folder up a level, so the file structure is:
\mod\EU4AU\\[mod files], NOT \mod\EU4AU\EU4-Australia-Mod\\[modfiles]
10. The mod should now be available in the launcher!

Make changes to these files and they will be reflected in the mod on EU4 relaunch

