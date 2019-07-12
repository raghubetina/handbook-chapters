# Notes

## PullRequest.com

50k LOC — expect 120$ / mo

99$ / hour (edu rate)

$80000 for Unity (50 team)

$6000 for a regular team of 50

Maybe less for us since we aren't full-time programming

# Research Professional Bootcamp

## Questions

### What are all of the existing resources that faculty have?

Are there resources from the University at large? Where does Booth IT fit in? Do we need to worry about training RPs on infrastructure (e.g. setting up and deploying to clusters) or is that handled by someone else?

### What is the size of a typical team?

E.g. 1 faculty member and 3 RPs collaborating on 1 codebase?

### How are RPs assigned to projects?

### What is the timeframe for the bootcamp?

How many days/weeks/hours per day?

### Do we want to teach languages/software packages?
 
 - My instinct is no; we can recommend MOOCs instead.
 - But if so, which ones?
    - Stata
    - R
    - Matlab
    - Python
    - Julia
    - Jupyter
    - We should poll current RPs/faculty to find out demand.

### What should we teach?

 - Git
    - A simple, effective git workflow
    - How to write a commit message
    - Git's object model: a peek under the hood
 - Writing tests
    - It's just automating what you do manually
    - Test the interface, not the internals
    - Four-phase tests and other tips
 - Code review
    - It's about knowledge transfer, not finding bugs
    - Ask, don't tell
    - What to review, and what _not_ to review
 - Continuous integration
    - Run your tests (CircleCI)
    - Check your style (Hound)
    - Static analysis (CodeClimate)
 - Automate all the things
    - One command should build _everything_
    - Virtual environments (e.g. Docker), not local
    - Reproducibility
 - Project management (this may be better targeted at faculty?)
    - Trello/Codetree/kanban
    - "I intend to"
    - The Goal
 - General tips
    - Premature optimization / preserving optionality / measuring performance
    - The cost of the wrong abstraction vs duplication
    - Put Digital Object Identifiers in your function documentation, e.g. "Implements equation 5.9 of Doe et. al. (2019), doi:4.12.16/foo"

### What about ongoing learning?

### Should we hire a tech lead to oversee/mentor/code review RPs?

### Should we develop something for faculty also, on how to best utilize/manage RPs?

## References

 - https://reproducible-analysis-workshop.readthedocs.io/en/latest/8.Intro-Docker.html
 - https://github.com/gslab-econ/ra-manual/wiki
 - https://news.ycombinator.com/item?id=18740000

## Notes

 - I think that I should probably be involved in one or two research projects to get a feel for things in order to really develop a robust process.
 - At some point, present to all faculty to set standards/expectations?

## Scribbles

 - Clean Code
 - Set up continuous integration
 - CodeClimate
 - Rubocop, Hound, etc
 - CODE REVIEW
 - "One things that has worked well for us, is to give a very explicit invitation to every new code user to question every bit of the code. If something is not obvious, ask why it is there and why it is the way it is. Once the new user understand the code he then adds a comment to the code or explanation in the documentation. After four new users very little code is left where the design considerations is undocumented."
 - Pair programming?
 - A really great idea: put DOIs in your function documentation.

    Writing things like:

    Implements equation 3.2 of Foo et. al. (2005), doi:10.2.3/baz

    has saved me no end of pain in the past.
 - Good commit messages
 - Git in general - branching, etc
 - Don't be clever, optimize for readability. Measure performance, then tune only bottlenecks
 - Also don't forget to document all dependencies and their versions! Fork them if applicable.
 - Papers should include a commit SHA
 - Press Y to highlight a line of code in GitHub
 - Test public methods / interface
    - If you find yourself tempted to write tests for private methods, maybe that should be extracted
 - Docker/VMs
 - VSCode online/remote environments
 - Wait to repeat yourself 3 times before DRYing repetition — the cost of the wrong abstraction
 - Premature optimization / preserving optionality
 - Trello / Codetree
 - Avoid global state
 - 4 phase tests
 - Workstation procedure?

## GitHub enterprise

## Docker enterprise



