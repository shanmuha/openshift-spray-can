openshift-spray-can
===================

A starter project for spray-can, Scala 2.10 + Akka 2.3 + spray 1.3 on Openshift (DIY Cartridge)

The changes from the basic spray-can starter is the addition of project/assembly.sbt and changes to build.sbt to do assembly and the .openshift directory and hooks.

The project gets compiled and archived into one uber jar which is then directly run from the start action-hook.
