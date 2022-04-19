# Yarn release

This is a command used whenever the version of a project needs to be changed.

Many at times, this is applied whenever code is to be merged into the master branch. 

`yarn release`

This command generates a few questions that you need to answer to determine the correct version it should be changed into. 

After a new version is chosen, `yarn release` goes ahead and updates the CHANGELOG.md and package.json files with the new version number. 

When this is done, it is advisabe to merge the created branch with the new version to the develop branch as well.
