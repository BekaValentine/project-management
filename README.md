# Project Management

This repo is intended to be used for doing project management of DDoSecrets projects.

The framework for how to do this is roughly based on a GTD model, but with some changes. Details are given below.

An example project, `projects/example_project`, is given as a template. When starting a new project, you can duplicate this directory and go from there.

## Structure of the Repo and the Process

This repo has a top level directory `projects/` which contains subdirectories `projects/<project_name>`. Within each project directory, we have the following structure. A detailed explanation of each file is included in those files, in lined as example text.

```
- projects/<project_name>/
  |- overview.md : a description of the project and who's working on it, including who's bottom lining
  |- inbox.md : a list of items arising from outside the project tasks that need to be dealt with
  |- task_tree.md : a breakdown of the tasks that need to be performed
  |- library/ : a directory of associated information that is useful or necessary for the project
```

The process in general works like so:

If anyone is ever looking to work on something, they can look at the task tree and determine what can be done next. Sometimes this just means fleshing out the task tree, and sometimes it means doing items that can't be broken into smaller problems.

Periodically, perhaps every day or week, it's useful to review the inbox and the task tree (or the delegations). The project's Bottom Liner can do this daily, and while the team can do it less frequently. During these reviews, you should look at the inbox and try to process the items there. You should also look to if delegations can be resolved and turned into follow-up, and if anyone has status updates that they haven't yet incorporated into the task tree.

As things come up in the world, contributors may need to record them for the team to address later. These should go into the inbox. Sometimes you can just process an item in the inbox immediately without actually adding it and waiting for review. That's always good and useful to do! But sometimes it's nice to also leave a note in the inbox for the next group review session so folx are on the same page.
