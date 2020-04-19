# PIP 2020 Homework Gallery

This repo contains all the classwork from Spring 2020, NYU DM-9013. I thought about a few different ways to get all of this work together, and for the moment the best thing I could think of was git submodules. A submodule is basically a way to have a repository-in-a-repository. The advantage here is, if you make some change to an assignment after the fact, you can pull those changes from this repo with one command line action.

## Initializing the repo

After you've checked out this repository, the next thing you'll want to do is get all the submodules. That should be as easy as running:

```
git submodule update --init
```

This will pull in all the work from each homework repository. With this done, you can `cd` into any particular repo and view the project-specific README to see how to run that code.

## Why isn't this all organized into a nice online gallery?

I'll try to get it there, but it could be a bit tricky and might require making some changes to the original code. Stay tuned, we'll try to make it happen.
