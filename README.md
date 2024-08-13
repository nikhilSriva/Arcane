## Problem
This is a reference copy issue. When we are creating the source data in reconcile, the checks object is not being newly created, hence there is this referential bug.

### Fix
Fixed this issue by creating a new copy of the checks object by using the ... (spread) operator right from the data source when it was created


### How to run

* Clone the repo
 * Run `yarn` to install dependencies 
 * Run the server with `yarn dev`

### Challenge: Eligibility Check Chaos

This is a single-page application designed to test your debugging skills. You'll be presented with candidate verification based on eligibility checks from two different sources. Each source has four individual checks, and initially, one check from each source appears passed.

Here's the twist: when you try to toggle the other checks, things get strange. There seems to be a bug in the code causing unexpected behavior.

Your mission: dive into the code and uncover the culprit behind this bizarre behavior. Identify the bug and understand why the application reacts the way it does.

### Unveiling the Bug: The Key to the Fix

You've identified the weirdness in the eligibility checks, but don't just jump in with a fix! The real challenge lies in uncovering the root cause, the sneaky bug making things wonky.

Think like a code detective. Isolate the culprit, understand why it's causing trouble, and then propose a solution that sets things straight. This is how you'll truly showcase your debugging mastery!
