
~~What is a JIRA and how do I get one?~~


## Overview

-   <span>The Watcher</span>

-   <span>Basic workflow</span>

-   <span>Syntax Party</span>

-   <span>Food || Questions</span>

-   <span>Integration and reuse</span>

-   <span>Gotchas</span>

-   <span>Useful Queries</span>


## The Watcher

Don't measure what you don't want to optimize.

Automation can help.

![image](eye_of_sauron.jpg)


## Workflow as seen on JIRA

![image](workflow.png)


## Syntax and Semantics

![image](sleep.png)

### Don't Panic

## Operators

Logical

-   <span>AND</span>

-   <span>OR</span>

-   <span>NOT</span>

Conditional

-   =

-   !=

-   ~

-   is

-   is not

-   in

-   not in


## Algebra all over again

Which are the same?

A AND B OR C

A AND (B OR C)

(A AND B) OR C

Don't guess! Just include parens all the time.

## Fields and Values

project = Android OR project = iOS

project in (Android, iOS) AND type = Bug

(project != ATEAM) AND (text ~ Drawing) AND resolved is EMPTY

## Food and Questions Break

![image](comic.png)


## Integration and reuse

-   <span>Filters</span>

-   <span>Boards</span>

-   <span>Quick Filters</span>

-   <span>Sharing</span>

-   <span>Saving</span>

-   <span>Webhooks!</span>


### Gotchas

-   <span>Dates are goofy</span>

-   <span>Editing a saved filter is dangerous</span>

-   <span>Two types of sharing</span>

-   <span>Different teams, different states</span>

-   <span>Absolute truth and duplication</span>

### Useful Queries

Intentionally left blank. Show and tell.
