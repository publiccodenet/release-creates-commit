---
# SPDX-License-Identifier: CC0-1.0
# SPDX-FileCopyrightText: 2023 The Foundation for Public Code <info@publiccode.net>
---
# Version history

<!-- script/release-body.sh expects VERSION in the first second-level header -->
<!-- script/update-changelog-date.sh expects DATE-OF-RELEASE and a colon -->

## Version 0.0.7

July 20th 2023: Enforce releases happen from a release-x.y.z branch

## Version 0.0.6

July 20th 2023: This adds an SSH key to allow workflow to push to main

* As `main` is now a protected branch, we need special secrets to push

## Version 0.0.5

July 20th 2023: This changes the trigging tag pattern to be "trigger-x.y.z"

* Clarify intent with tag names for automation

## Version 0.0.4

July 20th 2023: This drops the "release-0.0.4" tag after "0.0.4" is created

* no more "before release" tag in the tags history

## Version 0.0.3

July 20th 2023: This demo fixes the codebase name in the release text

* script has the `CODEBASE_NAME` in quotes now

## Version 0.0.2

July 20th 2023: This demo fixes the version in the release text

Version is now a parameter of the release-body script.

## Version 0.0.1

July 20th 2023: This is the first demo

The goal of this release is to have the workflow replace the DATE-OF-RELEASE with the date it is run.


## Version 0.0.0

July 17th 2023: init
