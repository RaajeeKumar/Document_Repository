# Document_Repository

How to add the documents to Git

1. Open up git bash
2. Move to the folder where you have the documents
3. Execute the following commands

git init
git add 'Java_J2EE_DesignPatterns.xlsx'
git commit -m "Added Java & J2EE Design Patterns"
git remote add origin https://github.com/RaajeeKumar/Document_Repository.git [Needed only for the first time]
git push -u origin master


How to override the local changes and do a pull

git checkout HEAD^ file/to/overwrite //It's dropping local changes, reverting to the HEAD reference which is probably the last commit in                                        //the master branch. HEAD^ is short for HEAD^1, which essentially means the one commit before HEAD.                                        //You could also do HEAD^2 for the commit before that one
git pull
