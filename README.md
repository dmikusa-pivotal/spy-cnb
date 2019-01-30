# Spy Cloud Native Buildpack

A small buildpack which can be inserted into a buildpack group to spy on the input to or output from other buildpacks in the group. This is mainly useful for debugging and buildpack authors.

For example:

 - There is a buildpack group consisting of buildpack-A, buildpack-B and buildpack-C.
 - You could insert the Spy buildpack, like buildpack-A, spy-buildpack, buildpack-B, buildpack-C and that would allow you to see what comes out of buildpack-A and gets feed into buildpack-C.

