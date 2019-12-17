# DEP-0: Department enhancement proposal structure

Author: Andranik Muradyan  
Email: a.muradyan@polytechnic.am  
State: Open  
Tags: dep, structure

## TL;DR

Even thou the specifics for the ideas behind DEPs are hard to pinpoint, the ideas themselves are usually very clear hence the definitions and descriptions in DEPs can lack structure but the DEP itself can and should be structured. This DEP proposes such a structure. The issue section is rather short and the proposal section provides rationale behind decisions made. Caveats section is not very informative either.

## Issue

Unstructured DEPs will be unbearable to manage.

## Proposal

DEP always starts with a [Caption](#dep-0-department-enhancement-proposal-structure)
> DEP[dash][DEP number]:[space][DEP name]

followed by the unnamed info section, containing:

* authors full name and
* authors email
* DEP state
* DEP tags

We should keep in mind that these are enhancement proposals which means that we can talk about an issue, it's proposed solution and caveats of the later. This simple approach is curently adopted so three more sections are introduced: [Issue](#issue), [Proposal](#proposal) and [Caveats](#caveats).

The [Issue](#issue) section discusses status quo of the matter and issues with concerned with it. It should provide the reasons behind the needed change.

The [Proposal](#proposal) section should explain the proposed change and the reasoning behing the decisions, provide comparison with other possible solutions, if any, or provide examples. It should introduce us the reader to limitations of solution space and assumptions made and provide a comprehensive description of the proposal in general.

The [Caveats](#caveats) section explores the limitations that the proposed solution imposes on the system. It may also contain reamrks on workarounds for the former but these should be kept concise in sense that they should not flow into a detailed workaround solution of the caveat. Such things belong in a separate DEP or on a task board.

Finally, it would also be nice to have a section with brief description of a DEP before diving into details. Such a section should provide the overview of the DEP and help the reader to navigate it. This is the [TL;DR](#tldr) section and comes right after the [Caption](#dep-0-department-enhancement-proposal-structure)

File structure is demonstrated in this file and can be viewed in DEP [template](dep-template.md).

## Caveats

The structure will change rapidly as more people join/DEPs come in, but what can you do?
