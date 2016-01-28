# patternplate - state of the union & vision
* Location: S2, Hamburg
* Date: January 21th 2016

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

## State of the union
Presentation by @marionebl available at [slides.com](http://slides.com/marionebl/patternplate-state-of-the-union-2016)

## Vision draft by @marionebl
### Mission statement
patternplate strives to provide the best platform for development, presentation and maintenance of Living Style Guides for the net.

### Principles
#### Open by default
Development and discussion on the platform are inclusive and open to everyone.
Style Guides make details of the project understandable and transparent to everyone.

#### The source is the Style Guide
Style Guides are exactly what they document.
This enables full life cycle support for projects.

#### Components are first class citizens
Style Guides are made up from resuable components.
The whole system revolves around them, thus focuses on modularization and dependency management.
This should hold true for a multitude of integration environments.

#### Full life cycle
The platform helps with design, initial development, deployment, integration, documentation and longterm maintenance of Style Guides.

#### Pick your own poison
Platform functionality is configurable, extensible and can be overridden, but sane defaults are always available.
As much functionality as possible is deferred to plugins.

#### Plug and Play
Setup, starting and deployment of Style Guides should be a matter of minutes when using the platform.

#### Extensible
Plugin system to provide customized functionality, reduce core build to basics -> keep it simple

## Vision discussion
* The group asserts the mission statement is okay as it is
* No immediate problems with the top level principles

* Easy setup for non-techs is a concern in some projects (@lkuechler)
  - Should this be reframed to "easy access"? (@marionebl)
  - There are hurdles for non-techs to participate in the lsg process (@felabr-s2, @lkuechler)
  - Could be tackled by "open by default" (@marionebl)
  - Currently we are really bad at this, "open by default" and "plug and play" should tackle this (@marionebl)

* Performance currently is bad (@oraks, @chopstick, @lkuechler, @felabr-s2)
  - some components need 60 seconds plus to load (@chopstick)
  - performance definitely is a concern we should pin down, how to express this in terms of a vision principle? (@marionebl)
  - should we understand patternplate as an IDE? (@dipe)
  - does this mean a "CRUD" dev environment? (@marionebl)
  - currently there is no way to decide this for the long run, to specific for vision? (@marionebl)

* patternplate frontend usage
  - what are patternplate's user groups? (@dipe)
    - programmers (@marionebl)
    - designer / ux (@lkuechler) 
    - stakeholder@client (@felabr)
    - quality assurance (@marionebl)
  - analysis of group needs has to be done (@marionebl)
  - we need this for decisions about supported use cases ( -> how tos, docs?) (@marionebl, @timbru31)
  - criteria for the frontend patternplate provides? (@marionebl)
  - noise in the ui has to be avoided (@lkuechler)
  - interdisciplinary work has to facilitated by unified frontend (@dipe, @marionebl)

  - **Draft**: The LSG interface helps everyone working with it understanding the contents of the style guide better and in the same way. The interface has to hold up against standards in usability, performance and joy of use. (@marionebl)

* We have technical issues concerning (@timbru31)
  * npm dependency updates
  * code quality / linting
  * [`patternplate-core`](https://github.com/marionebl/patternplate-core) could show the way forward (@marionebl)

* How can we help new contributors? (@oraks) 
* Good documentation definetely would help (@timbru31)
* What should the project do for contributors? (@dipe)

## Next steps
* Release meeting minutes on Github (@marionebl)
* Next meeting will focus on current draft, talk about feasability according to daily doing in specific scopes (@felabr, @dipe, @marionebl)
* More information will be available via patternplate@sinnerschrader.com (@marionebl)
