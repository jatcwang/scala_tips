# scala_tips
Tips and tricks for your everyday Scala work

# SBT

### Inspecting Meta-build (e.g. your plugins)

You can inspect the meta-build of your build (where plugins are loaded etc) with `reload plugins`. 
Return to the project's build using `reload return`.
Useful when you want to e.g. check dependency updates that are available for your SBT plugins
