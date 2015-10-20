
git - ၽိုၼ်ၸုင် ဢၼ်သၢင်းလၢင်းသေပိူၼ်ႈ
===============================

မၼ်းပဵၼ် ၽိုၼ်ၸုင် ဢၼ်သၢင်းလၢင်းသေပိူၼ်ႈ။ ယွၼ်ႉပိူဝ်ႈၼႆ မၼ်းဢမ်ႇပႃးႁူဝ်ယွႆႈမၼ်း။

[Tweet](https://twitter.com/share)

ၵေႃႈတႅမ်ႈၽိင်ႈတိုၼ်း [Roger Dudler](http://www.twitter.com/rogerdudler) (ၵေႃႉပိၼ်ႇၽႃႇသႃႇမၢၼ်ႈ
[saturngod](http://www.twitter.com/saturngod)) (ၵေႃႉပိၼ်ႇၽႃႇသႃႇတႆး [ၸၢႆးမွၼ်းၶမ်း](https://www.facebook.com/jaimawnkham)) 

ငိၼ်းၸူမ်းၶွပ်ႈၸႂ်ထိုင် [@tfnico](http://www.twitter.com/tfnico),
[@fhd](http://www.twitter.com/fhd) လႄႈ
[Namics](http://www.namics.com)


ၸိူဝ်းပဵၼ် လွင်ႈဢုပ်ႇဢူဝ်းလႄႈ ၶေႃႈမုၼ်း လွင်ႈမူၼ်ႉ​မႄးၸိူဝ်းၼႆႉ ၵႂႃႇၵႂႃႇ တၢင်ႇပၼ်ၵႃႈတီႈ
[github](https://github.com/rogerdudler/git-guide/issues) ၽွင်ႈၶႃႈ။

![](img/arrow.png)

လွင်ႈမူၼ်ႉမႄး
------------

[git download တွၼ်ႈတႃႇ OSX
](http://code.google.com/p/git-osx-installer/downloads/list?can=3)

[git download တွၼ်ႈတႃႇ Windows ](http://msysgit.github.io/)

[git download တွၼ်ႈတႃႇ Linux ](http://book.git-scm.com/2_installing_git.html)

ၵေႃႇသၢင်ႈ repository ဢၼ်မႂ်ႇမႂ်ႇ
---------------------------

ၵေႃႇသၢင်ႈ directory ဢၼ်မႂ်ႇ ဢၼ်ၼိုင်ႈလႄႈ။ ယဝ်ႉၵေႃႈ လုၵ်ႉတီႈ terminal သေ​ ပေႃႉသႂ်ႇပၼ် ၸွမ်းၼင်ႇ ပႃႈတႂ်ႈၼႆႉ။

 `git init`

ၼႆသေ တႄႇပၼ်  git repository ဢၼ်ၼိုင်ႈၶႃႈလႄႈ


ႁဵတ်း checkout တႃႇ repository 
---------------------------------

ပေႃးတေဢၢၼ်း ထုတ်ႇဢဝ် Copy သေ ႁဵတ်းၵၢၼ်ၼႆႉ​ တေလႆႈ ပေႃႉ ၶေႃႈပူင် command ၸွမ်းၼင်ႇ ပႃႈတႂ်ႈၼႆႉၶႃႈ။

 `git clone /path/to/repository`


သင်ၸိူဝ်ႉဝႃႈ ႁဵတ်းၵၢၼ်ၸွမ်း သႃႇပိူဝ်ႇ Server ၼႆ ၸႂ်ႉလႆႈၸွမ်းၼင်ႇ ပႃႈတႂ်ႈၼႆႉယူႇၶႃႈ။

 `git clone username@host:/path/to/repository`

လၢႆးႁဵတ်းၵၢၼ်
------------

ဢၼ် git မႃးႁဵတ်းၵၢၼ်ၵုမ်းထိင်း တီႈၼႂ်း local repository ၼႆႉ မၼ်းမီးဝႆႉယူႇ ၵိင်ႇမၼ်း ႓ ၵိင်ႇ။ ဢၼ်ပဵၼ် ၵိင်ႇဢွၼ်တၢင်းသုတ်းတႄႉ `Working Directory` ဢေႃႈ။ မၼ်းတႄႉ မၼ်းတေသိမ်းပၼ် file ဢၼ်မီးယူႇ ယၢမ်းလဵဝ်။ မၢႆသွင်တႄႉပဵၼ် `Index` ဢေႃႈ။ မၼ်းတႄႉ ပဵၼ်တွၼ်ႈ staging area ဢေႃႈ။ ဢၼ်ပဵၼ် ၵမ်းလိုၼ်းတႄႉ ပဵၼ် `HEAD` ဢေႃႈ။ မၼ်းတေၸီႉၼႄပၼ် ဢၼ်ၸဝ်ႈၵဝ်ႇ ႁဵတ်း commit ၵမ်းလိုၼ်းသုတ်းၼၼ်ႉၶႃႈဢေႃႈ။

![](img/trees.png)

add လႄႈ commit
----------------

ပေႃးၸဝ်ႈၵဝ်ႇ ၶႂ်ႈသႂ်ႇ ၸိူဝ်းဢၼ်ၸဝ်ႈၵဝ်ႇ မူၼ်ႉမႄးဝႆႉၼႆ ၸႂ်ႉၼင်ႇပႃႈတႂ်ႈၼႆႉလႆႈယူႇၶႃႈ။

 `git add <filename>`

 `git add *`

ၸၼ်ႉ​ၼႆႉတႄႉ ပဵၼ် ၸၼ်ႉမၢႆၼိုင်ႈဢေႃႈ။ ပေႃးၶႂ်ႈႁဵတ်း commit ၸိူဝ်းဢၼ်လႅၵ်ႈလၢႆႈမႃးၼၼ်ႉၼႆ

 `git commit -m "Commit message"`

ၸိူဝ်းပၼ်မူၼ်ႉမႄးမႃးၸိူဝ်းၼၼ်ႉ မၼ်းပေႃးသိမ်းဝႆႉပၼ် ၵႃႈတီႈၼႂ်း **HEAD** ယဝ်ႉဢေႃႈ။ ၵူၺ်းၵႃႈဝႃႈ မၼ်းဢမ်ႇပႆႇၽႅဝ်တီႈၼိူဝ် remote repository ၵွၼ်ႇၶႃႈ။

pushing changes
---------------

ၸိူဝ်းဢၼ်ၸဝ်ႈၵဝ်ႇ ႁၢင်ႈႁႅၼ်းဝႆႉၼၼ်ႉ ယၢမ်းလဵဝ် မၼ်းလုၵ်ႉဢဝ် local working copy ​သေ ၵႂႃႇၽႅဝ်ဝႆႉၵႃႈတီႈၼႂ်း **<HEAD\>** ယူႇယဝ်ႉ။

တွၼ်ႈတႃႇဢဝ် code ၸိူဝ်းႁဝ်းႁဵတ်းလွင်ႈလႅၵ်ႈလၢႆႈဝႆႉၼၼ်ႉ သူင်ႇၸူးၵႃႈတီႈ remote repository ၼၼ်ႉၼႆ

 `git push origin master`

ဢၼ်ပဵၼ် *master*  မၼ်းတႄႉ ဢိင်ၼိူဝ် ၵမ်ႉၸႂ်ၸဝ်ႈၵဝ်ႇသေ ၸဝ်ႈၵဝ်ႇ ၸၢင်ႈလႅၵ်ႈလၢႆႈလႆႈ branch လႆႈယူႇ။ ၸဝ်ႈၵဝ်ႇ ၶႂ်ႈသူင်ႇၸူး branch သေဢၼ်ဢၼ် ၵေႃႈလီယဝ်ႉ။

သင်ၸိူဝ်ႉဝႃႈ ၸဝ်ႈၵဝ်ႇၸမ်ႉ ဢမ်ႇၶႂ်ႈႁဵတ်း Cloned။ ၶူတ်ႉဢၼ်ၸဝ်ႈၵဝ်ႇ မီးယူႇ ယၢမ်းလဵဝ်ၼႆႉ ၶႂ်ႈႁဵတ်း remote server သေ ၵွင်ႉသိုပ်ႇၵၼ်ၼႆတႄႉ

 `git remote add origin <server>`

ယၢမ်းလဵဝ် ဢဝ်ၶူတ်ႉ ၸဝ်ႈၵဝ်ႇသေ တၢင်ႇၶိုၼ်ႈလႆႈၼိူဝ် remote server ဢၼ်ၸဝ်ႈၵဝ်ႇ လိူၵ်ႈဝႆႉၼၼ်ႉလႆႈယဝ်ႉ။

branching
---------

ၸိူဝ်းပဵၼ် Branches ၼႆႉတႄႉ ၵႆႉလႆႈၸႂ်ႉတီႈၸၼ်ႉႁဵတ်း develop ဢေႃႈ။ ဢၼ်ပဵၼ် *master* branch တႄႉ ပေႃးႁဝ်းၶႃႈ ၵေႃႇသၢင်ႈ repository ဢၼ်မႂ်ႇ မၼ်းၵေႃႈပႃးမႃးၸွမ်း ပိူင်တၢႆမၼ်းယဝ်ႉ။ သင်ၸိူဝ်ႉဝႃႈ တွၼ်ႈတႃႇ development သေ လႆႈၸႅၵ်ႈၽႄ branches မၼ်းၼႆၵေႃႈ ပေႃးဝႃႈ ယဝ်ႉတူဝ်ႈမူတ်းယဝ်ႉၼႆ ၸင်ႇၵႆႈ ဢဝ်မႃးႁူမ်ႈၵၼ်တင်း master branch ဢေႃႈ။


![](img/branches.png)

ၵေႃႇသၢင်ႈ branch ဢၼ်မႂ်ႇ ဢၼ်လႆႈၸိုဝ်ႈဝႃႈ “feature_x” ၼႆသေ လၢႆးတေႁဵတ်းႁိုဝ်ဢဝ် branch ၼၼ်ႉ လႅၵ်ႈလၢႆႈသေၸႂ်ႉ


 `git checkout -b feature_x`

ၶိုၼ်းမႄးလႅၵ်ႈလၢႆႈ master branch 

 `git checkout master`

မွတ်ႇပႅတ်ႈ branch 

 `git branch -d feature_x`


ပေႃးၶႂ်ႈႁဵတ်း push ဢဝ် branch ၸူး remote repository ၼႆ

 `git push origin <branch>`


ၸၼ်လူင်းဢၼ်မႂ်ႇ လႄႈ ႁူမ်ႈႁွမ်းၵၼ်
------------------------------------


ပေႃးဝႃႈ တေၸၼ်ဢဝ် ၸိူဝ်းႁဵတ်း commit ဢၼ်မႂ်ႇ ၵႃႈတီႈၼႂ်ႈ remote repository လူင်းၸူး local repository ၼႆၸိုင်

 `git pull`

ပေႃးဝႃႈ ႁွင်ႉ *pull* ၼႆၸိုင် ၸိူဝ်းႁဵဝ်းႁဵတ်းဝႆႉ လွင်ႈလႅၵ်ႈလၢႆႈ ၵမ်းလိုၼ်းသုတ်း ၵႃႈတီႈၼႂ်း working directory ၼၼ်ႉ မၼ်းတေႁဵတ်း *fetch* လႄႈ *marge* ၵႂႃႇဢေႃႈ။

ပေႃးတေဢဝ် branch တၢင်ႇဢၼ် မႃးလေႃးသႂ်ႇၼႂ်း ဢၼ်ႁဵတ်းၵၢၼ်ယူႇ ယၢမ်းလဵဝ် branch (တူဝ်ယၢင်ႇ။ ။ master) ၼႆ


 `git merge <branch>`

မိူဝ်ႈၼၼ်ႉ git ၼႆႉ မၼ်းတေဢဝ် ၸိူဝ်းဢၼ်မႄးဝႆႉၼၼ်ႉ လေႃးပၼ်ၵႂႃႇ ႁင်းမူၼ်းယဝ်ႉ။ ၵူၺ်းၵႃႈဝႃႈ မၼ်းၵေႃႈ တေဢမ်ႇ ၶႅမ်ႉလႅပ်ႈ တႃႇသေႇၼင်ႇၵဝ်ႇ။ မၢင်ပွၵ်ႈမၢင်လႂ်ၵေႃႈ တေၸၢင်ႈမီး ဢၼ်ၶွင်ႉၶမ် *confilicts” ၼင်ႇၵဝ်ႇ။ မိူဝ်ႈပဵၼ် လွင်ႈၶွင်ႉၶမ်ၸိူင်ႉၼၼ်မႃးၸိုင် ႁူႉၵႃႈ တေလႆႈႁဵတ်း တႃႇႁူမ်ႈၵၼ် ႁင်းၸဝ်ႈၵဝ်ႇယဝ်ႉ။ ၸိူဝ်းပဵၼ် file ဢၼ်ပဵၼ် *confilitcs* ၼၼ်ႉ မၼ်းၵေႃႈ ၼႄဝႆႉပၼ် တီႈ git ယူႇၼင်ႇၵဝ်ႇ။ ႁဝ်းၶႃႈ တေလႆႈမူၼ်ႉမႄး file ၸိူဝ်းၼၼ်ႉ ႁဝ်းၵူၺ်းႁဝ်းသေ ၸင်ႇၵႆႈ ၶိုၼ်းထႅမ်သႂ်ႇပၼ်ယဝ်ႉ။


 `git add <filename>`

မိူဝ်ႈပႆႇႁူမ်ႈၵၼ်ၼၼ်ႉ ၸဝ်ႈၵဝ်ႇ တေၸၢင်ႈဢဝ် code ၸိူဝ်းလႅၵ်ႈလၢႆႈဝႆႉၼၼ်ႉ ၼိူင်းၵၼ်တူၺ်းလႆႈယူႇ။

 `git diff <source_branch> <target_branch>`

tagging
-------

ပေႃးဝႃႈ ​ႁဵတ်းဢွၵ်ႇ မၢႆဢွၵ်ႇ Software version ၼိုင်ႈဢၼ်ယဝ်ႉၼႆ ၶႂ်ႈပၼ်တၢင်းႁၼ်ထိုင် ႁႂ်ႈၸႂ်ႉ tag ၼႆဢေႃႈ။ ဢၼ်ၸႂ်ႉလၢႆးၼႆႉၼႆႉ မၼ်းၵေႃႈပဵၼ် ပၢႆးဝူၼ်ႉ ဢၼ်ပႃးၵိုၵ်းမႃးတင်း SVN ဢၼ်ၼိုင်ႈ။ ၸဝ်ႈၵဝ်ႇ ၸၢင်ႈပၼ် tag ၸူး ၸိုဝ်ႈဢၼ်မႂ်ႇ *1.0.0* ၼႆယူႇ။


 `git tag 1.0.0 1b2e1d63ff`

*1b2e1d63ff* ၼႆႉတႄႉ မၼ်းပဵၼ် တူဝ်လိၵ်ႈ ၵမ်းဢွၼ်တၢင်းသုတ်း ႑႐ တူဝ် ၵႃႈတီႈ commit id ဢၼ်ၸဝ်ႈၵဝ်ႇ ၶႂ်ႈႁဵတ်း tag ၼၼ်ႉယဝ်ႉ။ ပေႃးဝႃႈ ၸဝ်ႈၵဝ်ႇ ၶႂ်ႈလႆႈ commit id ၼႆ ပေႃးၸွမ်းၼင်ႇ ပႃႈတႂ်ႈၼႆႉသေ ဢဝ်လႆႈယူႇၶႃႈ။

 `git log`

 
တွၼ်ႈတႃႈ commit id ၼႆႉ ၸဝ်ႈၵဝ်ႇ တေၸၢင်ႈဢဝ် တူဝ်လိၵ်ႈ မၢင်ၸိူဝ်း ဢိတ်းဢွတ်းသေၵေႃႈ ၸႂ်ႉၵႂႃႇလႆႈယူႇ။ ၵူၺ်းၵႃႈဝႃႈ id ဢၼ်ဝႃႈၼႆႉ မၼ်းတေဢမ်ႇ လႆႈၵႂႃႇၸႂ်ႉဝႆႉသေတီႈ ဢမ်ႇၼၼ် မၼ်းတေလႆႈပဵၼ် ႁင်းၶေႃ unique ​ဝႆႉဢေႃႈ။

တႅၼ်းတီႈၸူး လွၵ်ႈလႅၵ်ႈလၢႆႈ local
-----------------------------------------

သင်ၸိူဝ်ႉဝႃႈ သေဢၼ်ဢၼ်လႆႈ ၽိတ်းပိူင်ႈၵႂႃႇလႄႈ ၶႂ်ႈၶိုၼ်းဢဝ် ၾၢႆႇ ၸိူဝ်းမီးၵႃႈတီႈၼႂ်း local ၼၼ်ႉ ၶိုၼ်းတႅၼ်းတၢင်တီႈၼႆ

 `git checkout -- <filename>`

ဢၼ်လႅၵ်ႈလၢႆႈၼင်ႇ ယၢမ်းလဵဝ်ၼႆႉ မၼ်းတေဢဝ် content ၸိူဝ်းမီးၵႃႈတီႈၼႂ်း HEAD ဢၼ်မီးၼႂ်း working tree ၵမ်းလိုၼ်းသုတ်းၼၼ်ႉ မႃးတႅၼ်းတၢင်တီႈ ၵႂႃႇဢေႃႈ။ ၸိူဝ်းဢၼ်လႅၵ်ႈလၢႆႈဝႆႉၼၼ်ႉတႄႉ မၼ်းတေသႂ်ႇၼင်ႇ index ​သေ ၸိူဝ်းပဵၼ် file ဢၼ်မႂ်ႇၵေႃႈ တေသိမ်းပၼ်ၵႂႃႇယူႇၶႃႈ။

သင်ၸိူဝ်ႉဝႃႈ ပေႃးၸဝ်ႈၵဝ်ႇ ၶႂ်းမွတ်ႇပႅတ်ႈ local changes လႄႈ commits တင်းမူတ်းသေ တေၶႂ်ႈၶိုၼ်းၸၼ်ဢဝ် server လႄႈ master brance မႃးတႅၼ်းတၢင်တီႈၼႆၸိုင်

 `git fetch origin`

 `git reset --hard origin/master`

ၸိူဝ်းၶဝ်ႈတၢင်းတိုဝ်း
-------------------

git  ဢၼ်ၶဝ်ႈပႃး GUI

 `gitk`

 git output ၸိူဝ်းပႃးဝႆႉသီ

 `git config color.ui true`

 တွၼ်ႈတႃႇဢဝ် commit သေတူၺ်းၼင်ႇ လိၵ်ႈၵမ်းထႅဝ်ထႅဝ်။

 `git config format.pretty oneline`

လွင်ႈၸႂ်ႉတိုဝ်း interactive adding 

 `git add -i`

link လႄႈ resources
--------------------

### graphical clients

-   [GitX (L) (OSX, open source)](http://gitx.laullon.com/)
-   [Tower (OSX)](http://www.git-tower.com/)
-   [Source Tree (OSX, free)](http://www.sourcetreeapp.com/)
-   [GitHub for Mac (OSX, free)](http://mac.github.com/)
-   [GitBox
    (OSX)](https://itunes.apple.com/gb/app/gitbox/id403388357?mt=12)

### ၽိုၼ်ၸုင် လွၵ်းလၢႆးၸႂ်ႉတိုဝ်း

-   [Git Community Book](http://book.git-scm.com/)
-   [Pro Git](http://progit.org/book/)
-   [Think like a git](http://think-like-a-git.net/)
-   [GitHub Help](http://help.github.com/)
-   [A Visual Git
    Guide](http://marklodato.github.com/visual-git-guide/index-en.html)
