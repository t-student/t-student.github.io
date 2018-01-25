# README.md

The easiest way to update this (that I have found) is to clone this repository to a specific folder, i.e. the public folder and then invoke hugo to recreate your site. Doing so updates the public folder. Change directory to the public folder then git add, git commit, then git push and that should be it. 

Afterwards you can cd back out of the public folder then rm -rf public. In theory you should be in the websource repository again. To check you can do: git config --get remote.origin.url.

