GRADLE COMPOSITE PLAYGROUND
===========================

Where I go insane configuring Gradle to resolve artifacts whilst
--include-building to infinity.

The goal is to be able to do:

    gradle extractABin --include-build ../projectA --include-build ../projectB

from inside projectC and have it automatically figure out how to
resolve jars and tars.

Seems to be working with Gradle 4.2.1.
