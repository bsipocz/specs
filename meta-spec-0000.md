---
title: "MetaSPEC 0 — Purpose and Process"
date: 2020-12-17T19:53:08-08:00
draft: false
author: 'Jarrod Millman <millman@berkeley.edu>'
spec_status: Draft
spec_type: meta
summary: |
  The Scientific Python Ecosystem Coordination (SPEC) mechanism
  is used to recommend project policies, coding conventions,
  and standard tooling.
---

# Description

The SPEC author is responsible for building consensus within the
community and documenting dissenting opinions.

Because the SPECs are maintained as text files in a versioned
repository, their revision history is the historical record of the
feature proposal[^1].

## Types

# Implementation

## Workflow

### Review and Resolution

### How a SPEC becomes Accepted

### Maintenance


## Format and Template

SPECs are UTF-8 encoded text files using
[Markdown](https://www.markdownguide.org/) format.
We use [Hugo](https://gohugo.io/) to convert SPECs to HTML for viewing on the
web [^2].

Please see the [spec-template]({{< ref "/specs/spec-template.md" >}})
file and for more information.

# Notes

[^1]: This historical record is available by the normal git commands for
    retrieving older revisions, and can also be browsed on
    [GitHub](https://github.com/scientific-python/scientific-python.org/tree/master/content/specs).

[^2]: The URL for viewing SPECs on the web is
    <https://scientific-python.org/specs/>