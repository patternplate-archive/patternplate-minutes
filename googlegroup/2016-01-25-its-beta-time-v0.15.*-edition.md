# It's beta time (v0.15.* edition)

Sender: mario.nebl@sinnerschrader.com
Recipient: patternplate@sinnerschrader.com

Hello there,

## TL;WR
* There are new versions of patternplate-server and patternplate
* patternplate-server v0.13.9 for stability
* patternplate v0.15.0-beta / patternplate-server v0.14.*-beta for performance
* Install the new version via npm install patternplate@beta
* Report any regression you may find to patternplate-server/issues and state the version you are using

I just released several versions of patternplate-server and patternplate and here is what this is about:

## patternplate-server v0.13.9
This release reverts the first approach towards a smart incremental commonjs build task.
As it turns out the original approach tried a little bit to hard on the being-smart-side and introduced bugs concerning error reporting and build stability.
To avoid the same for the next try on incremental builds there now is

## patternplate-server v0.14.*-beta
This introduces a revisited version of the incremental build, which
analyses mtimes of sources and artifacts on 1 source → n artifacts level
prunes orphaned artifacts on the file level
derives dependencies for the artifacts package.json from the build run
reenables the read cache
allows for fine-grained control of what actually ends up in the artifacts package.json
sports significantly better performance
All this goodness comes with a price tag attached, namely I expect some regressions.

First, these are massive changes to the commonjs task and the underlying pattern abstraction.
Second, this make the commonjs task way more complex, adding about 400 LOC to the former 100.
Third, this is a minor version bump, which means you won't be able to install patternplate-server@0.14.*-beta alongside patternplate@0.14.
This leads us to

## patternplate v0.15.0-beta
This merely exists to let you install the patternplate-server v0.14.*-beta range conveniently. To do so just

npm install patternplate@beta

and you should be good to go.


Beta testers needed!
Please give the new beta version a try and report any issues you find to the patternplate-server project. Be sure to state the patternplate and patternplate-server versions you are using.

Cheers,
Mario
