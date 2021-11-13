2021-10-28
1430
Create a MVC project called as2 using individual credential, https under the instruction of Professor
Steele.
Test the project. It is succefully built as expected.
Go to https://bootswatch.com/, navigate to darkly, click  'download' to download the source file.
But i tried this differently by click the picture of darkley, go to github copy the source code, and then
copy it to wwwroot/lib/bootstrap/dist/css/bootstrap.css, save it. 
open blackboard, locate ASP.NET course content, download the css file and copy the source code to 
wwwroot/css/site.css (before copy to it, all original code was deleted).
1715
add a readme.txt file, and commit change and push it github.
after updated bootstrap.css and site.css files, check its appearance, the appearance changed!
2021-11-1
13:30
Added image to index page, it succeeded, but i tried to modify its style like putting in the center, it wont work.
2021-11-3
1251
modify the startup.cs file.
--delete option part in services.AddDefaultIdentity.
1313
--download bootstrap.css from bootswatch.com (use the theme Darkly)
--delete bootstrap.css in the directory wwwroot/css/lib/bootstrap/dist/css/bootstrap.css
--drag the downloaded one to css fold to replace the old one. save it.
--download site.css from blackboard, and replaced the old one in the directory wwwroot/css/site,.css with
the downloaded version by dragging the new one to the folder.save it.
1319
--go to view/shared/_layout.cshtml
--find the link href, modify the directory from bootstrap.min.css to bootstrap.css
--change the nav class from navbar-light to navbar-dark and bg-white to bg-primary
--on line 22, remove text-dark
--update footer class with text-white-50 and bg-primary, save it.
--update file _loginPartial.cshtml in the shared folder
2021-11-13
11:00 check if my project works properly, it turned out 33 errors,most of them are assembly related errors.
11:30 deleted other three projects, still errors
12:00 use the old version with as2 project only, it works fine.
12:40 added three projects to as2 projects, errors produced again.
13:00 deleted these projects except as2, try to push to github, it says push failed

14:45 view git and git/visual studio video, every video says there is a create repository in git menu,
it actually no such thing. I believe this is because my project has created repository in github, 
somehow I have to dissociate my local file with github file. I archived my previous version on github.

15:50 try to modify the git/settings/source control/git repository settings/remote, deleted existing directories
created new repository in the github web, and added the new address to git/settings/source control/git repository settings/remote

16:00 check visual studio, under push pull at the bottom right, no changes, close and reopen visual studio and project
push on the bottom right shows 21 commits. Try to commit, succeeded! 
16:05 check if the project works. It does.
16:07 check if files has been changed on the github. It did.
16:08 push and commited.
16:08 try to added project_2 but not in the as2 folder. the project_2 was successfully added
16:10 check if as2 still works fine. rebuilt as2. Succeeded!
16:11 go ahead added another two projects under as2-copy, not under as2. All three projects undergo individual accouts
 as credential method. and all in the folder as2-copy.

16:14 check if the as2 project works well. built as2, it does.

16:16 all four projects show the same interfaces so far.
16:30 
--open as2 part 2 slides, follow the slides starting from page 2
--migration using command Add-Migration InitialCreate and Update-Database, successfully built
--check the migration files, there is a new file called 20211113212911_InitialCreate.cs generated.
(noticed that this operation is different with as1, which does a few steps before migration.)
--commited and push to github.


