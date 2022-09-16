# Why fork?

This repository is a fork of the [PCSC lite project (gitlab)](https://salsa.debian.org/rousseau/PCSC),
focused on the needs of [Teleport](https://github.com/gravitational/teleport).

Teleport uses PCSC-lite for both OSS and Enterprise builds, the latter of which cannot depend on GNU GLP
v3 copyrighted code. This fork exists to Remove GNU GLP v3 copyrighted code which does not provide functionality 
needed by Teleport. 

We do intend to contribute widely valuable changes to the original repo, if such changes are made.

The `master` branch reflects the upstream master.

The `teleport` branch is the default and reflects the library version used by
Teleport. There is no concept of semantic versioning for the `teleport` branch,
it rolls forward as Teleport needs it to.

You are looking at the `teleport` branch now.

PCSC lite project
=================

Middleware to access a smart card using SCard API (PC/SC)
---------------------------------------------------------

The project Web site is: https://pcsclite.apdu.fr/

<a href="https://codeclimate.com/github/LudovicRousseau/PCSC"><img src="https://codeclimate.com/github/LudovicRousseau/PCSC/badges/gpa.svg" /></a>
