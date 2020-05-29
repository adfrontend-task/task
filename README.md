# Task (template)
Template repository used for creating FDND tasks.

## Standard repository structure
We use a standard folder structure which is described in [fdnd/conventions/folder-structure.md](https://github.com/fdnd/conventions/blob/master/folder-structure.md)

    .
    ├── build                   # Compiled bestanden of de publicatie van een website
    ├── docs                    # Documentatie
    ├── src                     # Bronbestanden
    ├── test                    # Geautomatiseerde tests
    ├── CHANGELOG.md            # Lijst van noemenswaardige aanpassingen (zie changelog.md)
    ├── LICENSE                 # Licentiemodel (zie license.md)
    ├── README.md               # Beschrijving van het project (zie readme.md)
    └── TODO.md                 # Uit te voeren stappen om een taak te volbrengen (zie todo.md)


# Front Matter in .description
De leertaak wordt aan het curriculum gekoppeld door de gegevens in het bestand (.description)[.description]. Vul dit zo goed mogelijk in om taakaggregatie mogelijk te maken.
---
title: "een titel"
# max 280 characters in description
description: "korte beschrijving van de taak"
semester: 1-4
# taskclass will be used to group tasks together in a semester
# make sure you use a unique name
taskclass: "naam van taakklasse voor bundeling van taken"
# level determines the order of tasks in a taskclass
level: 0-5
# these criteria determine the skill level of a task compared
# to the whole curriculum on a 6 point scale. Read the Rubric!
behavior-criteria:
  collaboration: 0-5
  learning-capacity: 0-5
  problem-solving: 0-5
  act-methodically: 0-5
  communicating: 0-5
# how many students will work on this task, 0 for individual
collaborators: 0-8
# tags are used to categorize tasks
tags:
  - opsomming
  - van
  - tags
# burn-points determine the weight of a task, 0 is easy and
# probably fast, 144 takes a whole sprint
burn-points: 0-144
---

# Een titel
Hier een heldere beschrijving van de taak. Je kunt volledige markdown syntax en links gebruiken maar geen afbeeldingen!


