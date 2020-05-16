ANSWER 1:  
Version 2.26.2.windows.1  

-----------------------------------------------------------

ANSWER 2:   
diff.astextplain.textconv=astextplain      
filter.lfs.clean=git-lfs clean -- %f       
filter.lfs.smudge=git-lfs smudge -- %f     
filter.lfs.process=git-lfs filter-process  
filter.lfs.required=true  
http.sslbackend=openssl  
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt  
core.autocrlf=true  
core.fscache=true  
core.symlinks=false  
credential.helper=manager  

-----------------------------------------------------------

ANSWER 3:   
A window is opened up in my browser titled "git-add(1) Manual Page"   (link file:///C:/Program%20Files/Git/mingw64/share/doc/git-doc/git-add.html), which seems to describe the function of the 'add' command.  

----------------------------------------------------------------

ANSWER 4: No commits yet  

Untracked files:  
  (use "git add <file>..." to include in what will be committed)  
        README.md  
        answers.md  

nothing added to commit but untracked files present (use "git add" to track)  

--------------------------------------------------------------------

ANSWER 5:   
On branch master  
 
No commits yet  

Changes to be committed:  
  (use "git rm --cached <file>..." to unstage)  
        new file:   README.md  

Untracked files:  
  (use "git add <file>..." to include in what will be committed)  
        answers.md  

---------------------------------------------------------------

ANSWER 6:   
On branch master  

No commits yet  

Changes to be committed:  
  (use "git rm --cached <file>..." to unstage)  
        new file:   README.md  
        new file:   answers.md  

-------------------------------------------------------------------------

 ANSWER 7:   
 On branch master  
nothing to commit, working tree clean  

------------------------------------------------------------------------------

ANSWER 8:   
commit c738bef56abbbd4fc307ef7f1f194e4307c5196a (HEAD -> master)  
Author: EYE657318 <ip657318@ohio.edu>  
Date:   Fri May 15 03:25:57 2020 -0400  

    Initial commit  

----------------------------------------------------------------------------------

ANSWER 9:   
On branch master  
Your branch is up to date with 'origin/master'.  

nothing to commit, working tree clean  

------------------------------------------------------------------------

ANSWER 10:   
Nope.  

------------------------------------------------------------------------

ANSWER 11: An error occurs.  

hint: Updates were rejected because the remote contains work that you do  
hint: not have locally. This is usually caused by another repository pushing  
hint: to the same ref. You may want to first integrate the remote changes  
hint: (e.g., 'git pull ...') before pushing again.  
hint: See the 'Note about fast-forwards' in 'git push --help' for details.  

---------------------------------------------------------------------------------

ANSWER 12: 

Yup, README has the class information now.

----------------------------------------------------------

ANSWER 13: 

Get-ChildItem : Parameter cannot be processed because the parameter name 'a' is ambiguous. Possible matches include: -Attributes -Directory -File -Hidden -ReadOnly -System.
At line:1 char:4  
+ ls -a  
+    ~~  
    + CategoryInfo          : InvalidArgument: (:) [Get-ChildItem], ParameterBindingException  
    + FullyQualifiedErrorId : AmbiguousParameter,Microsoft.PowerShell.Commands.GetChildItemCommand  