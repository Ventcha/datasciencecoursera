## Simple test file for process of create local file, add, commit and push to github
## Create the file, and save into the appropriate directory for the local repository. Git push will do nothing - everything up to date
## Add the file to the local repository: Git add -A:  Git push will STILL do nothing - everything up to date (needs committing)
## Commit, with message:  git commit -m "Procedural MD file created." 
###(see [master 4d5e841] Procedural MD file created.
### 1 file changed, 1 insertion(+)
### create mode 100644 HWSteps.md))
## Now try pushing to github: git push origin master
###Counting objects: 3, done.
###Delta compression using up to 8 threads.
###Compressing objects: 100% (2/2), done.
###Writing objects: 100% (2/2), 261 bytes | 0 bytes/s, done.
###Total 2 (delta 1), reused 0 (delta 0)
###To https://github.com/Ventcha/datasciencecoursera.git
###   87a8a5f..4d5e841  master -> master