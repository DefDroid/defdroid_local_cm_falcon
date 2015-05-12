defdroid_local_cm_falcon
========================

Local manifests for CM tree on Moto G device

Getting Started
---------------
If you are not a project member of DefDroid, for now you should remove `defdroid.xml` 
to be able to compile a vanilla CM-11.0 for falcon because `defdroid.xml` refers to 
project repositories that are currently hosted as private.


Follow the standard way of getting a CM source tree. Then 
switch to the root of the source tree and put the content of
this repository in `.repo/local_manifests` (`mkdir .repo/local_manifests` 
if it does not exist).
Then sync up with
```
repo sync
```
