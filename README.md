# Before running notebook

If you haven't generated a census api key, please generate it and activate it on https://api.census.gov/data/key_signup.html

After you've generated your key, please add a (`.env`) file in your git repo copy and input the following:

```
CENSUS_API_KEY=INSERT API KEY
```

# Before you make changes

Please pull from main by doing (`git pull`) then branching off by running the following:

```
git checkout -b [name]/[branch-name]
```

Once you are done with your changes, do the following:

```
git add .
git commit -m "[insert useful message]"
git push
```

Then create a PR on the github website to make sure there aren't merge conflicts and merge with main.

I wanted to provide baseline for you guys to add on to. Let me know if you have any questions!
-Jon