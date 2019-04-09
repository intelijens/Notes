Git-Notes
===============
http://localhost/_Notes/Git-Notes.md

Just a small list of things I'd like to remember regarding Git(.git) commands


# ...or create a new repository on the command line
echo "# Notes" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:intelijens/Notes.git
git push -u origin master

# ...or push an existing repository from the command line
git remote add origin git@github.com:intelijens/Notes.git
git push -u origin master


# Check origin
git remote -v