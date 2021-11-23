# remove cached file 
git rm --cached -r .; git add .; git status; git commit -m "Ignore unwanted files"
# get repo name inside project
git config --get remote.origin.url
