
# patternplate - state of the union & vision
* Location: S2, Hamburg
* Date: January 28th 2016

## Attendees
* @chopstick
* @dannyfischer
* @dipe
* @felabr-s2
* @lkuechler
* @marionebl
* @mrpelz
* @oraks
* @timbru31
* @dangoo
* @knisterpeter

## Questions concerning last meeting
- @felabr-s2: Are the principles describing the software or other way round and/or usecases?
- @marneb: Principles ares describing software, not usecases

## Problems to be solved by principles
* Open by default
  - @knisterpeter: Documentation is written twice (external and as markdown in pp).
  - @knisterpeter: API documentation could be auto generated, handwritten docu separated.
  - @marneb: Documentation generation based on props and proptypes.
  - @dangoo: Add markdown editor for documentation editing/adding for each pattern.
    - @knisterpeter: We are talking about another user group (ux) unknown to us.
    - @dangoo: Bringing this request along from a project.
    - @marneb: Full git client to build, at least adding of persistence, high engineering efforts.
    - @felabr-s2: Are we loosing focus? Features for other groups are possibly distracking.
* Full Livecycle
  - @knisterpeter: 1:1 presentation of patterntree as in file system -> ensure consistency in pattern tree, e.g. CLI with moving/changing tasks.
  - @timbru31: Add init task, to create initial pattern.
  - @felabr-s2: Atomic design not good for order, instead display whole pattern tree.
  - @knisterpeter: Provide alternative display methods for pattern structure.
  - @marneb: patternplate ignores folder names, make it configurable because of breaking changes, problem might be mapping on new folder structure
  - @knisterpeter: Sorting by tags per pattern
  - @marneb: search is manadatory dependency. Resulting tasks: search, tagging system, customizeable structuring
  - @knisterpeter: idea of saving view setting in storage
  - @marneb: violates thought of single source of truth
* The source is the styleguide
  - @felabr-s2: display of permutations is hard
  - @marneb: idea of interactive demos -> configure interface for props
  - @knisterpeter: dangerous because of unwanted prop combination which than become a requirement
  - @felabr-s2: keep children in mind
  - @marneb: Demo dependencies are important, available in demo only!

## Time budget splitting
