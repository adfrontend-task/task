# Task (template)
Template repository used for creating FDND tasks. Replace the contents [README.md](README.md) (this file) when you create a new task.

## Task instructions (the final readme.md for the derived task)
<!-- Remove this 👆 in the final task -->
```
# Naam

## Context
Beschrijving opdrachtgever en context

## Briefing
Beschrijving taak

## Doel van deze opdracht
Wat er met de taak moet worden bereikt

## Materiaal
Bronnen en resources (artikelen, video's, visuals, talks, posters, etc)

## Werkwijze
Instructies over hoe te werk gaan, verder uitgewerkt in [Stappenplan](todo.md)  
(In meer of mindere mate sturing afhankelijk van het niveau van de taak)

## Criteria
Definitions of done

## Niveau van deze taak

|   | Scaffolding | Description |
| ---: | :----   | :--- |
| a | Example | Uitgewerkt voorbeeld |
| b | Duplicate | Immitatietaak |
| c | Experiment | Taak zonder een specifiek doel |
| d | Extension | Aanvultaak |
| e | Autonomous | Taak zonder ondersteuning |
```

<!-- Remove this 👇 in the final task -->
## Folder structure
Task uses a standard folder structure following convention described in [conventions/folder-structure.md](https://github.com/fdnd/conventions/blob/master/folder-structure.md). Feel free to remove folders if you're creating a task without scaffolding.

## .description
The task you create based upon this template is hooked up to the FDND curriculum using [yaml front matter](https://assemble.io/docs/YAML-front-matter.html) in the [.description](.description) file. Feel free to change all values to put your task in the right place but leave the keys the same.

```YAML
---
title: "descriptive title"          # Same as repo name but with spaces and caps 
description: "short description"    # Max. 280 characters in description
semester: 1-4                       # Please choose only one semester
sprint: 1-18                        # Please choose only one sprint
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

## License

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
