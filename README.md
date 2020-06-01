# Task (template)
Template repository used for creating FDND tasks. Replace the contents [README.md](README.md) (this file) when you create a new task.

## Folder structure
Task uses a standard folder structure following convention described in [conventions/folder-structure.md](https://github.com/fdnd/conventions/blob/master/folder-structure.md). Feel free to remove folders if you're creating a task without scaffolding.

## .description
This task is hooked up to the FDND curriculum using [yaml front matter](https://assemble.io/docs/YAML-front-matter.html) in the [.description](.description) file.

```
---
title: "descriptive title"          # Same as repo name but with spaces and caps 
description: "short description"    # Max. 280 characters in description
semester: 1-4                       # Please choose only one semester
taskclass: "taskclass name"         # Taskclassses group tasks together in a semester
support-level: 1-5                  # 1:example 2:duplicate 3:experiment 4:extension 5:autonomous
behavior-criteria:                  # These criteria determine the skill level of a task
  collaboration: 0-6                # compared to the whole curriculum on a 6 point scale.
  learning-capacity: 0-6            # Make sure you understand the levels before changing
  problem-solving: 0-6              # these in a task. In general 0-2 will be used for tasks
  act-methodically: 0-6             # in semester 1 (static web), 3-4 for tasks in semester 2
  communicating: 0-6                # (data driven), 5-6 for tasks in semester 3 (wtf?!).
collaborators: 1-8                  # How big is the team with wich to adress this task.
tags:                               # tags can be used to categorize tasks
  - list                                        
  - of
  - usefull
  - tags
burn-points: 1-144                  # burn-points determine the weight of a task
---
```