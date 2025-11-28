# Engineering Principles

## Why Have Principles?

## Our Tenets

### Pragmatism
*Choosing the practical path forwards given the current situation.*

We make straight-forward decisions which are correct in the moment and are easily defendable. For example, it's more pragmatic to add a new endpoint to an existing REST API than creating an entirely new API and supporting infrastructure.

### Simplicity
*Optimising for others’ comprehension over one’s ego.*

We always write code that is simple to read and design systems that are easy to understand. Things shouldn’t be more complicated or complex than they absolutely must be. Simple systems are easier to reason about, cheaper to run, and more straightforward to keep secure.

## Our Principles

### Consistency over Small Improvements

We should strive for consistency unless there is a magnitudinal improvement. That means using familiar technology or following existing patterns where they exist unless there is a significant advantage. For example, REST is the primary way systems communicate with each other; creating a new service using gRPC would be inconsistent.

### Be Explicit

Write things down and explain the reasoning. For example, document small decisions in code comments, or for larger decisions write Architectural Decision Records (ADRs).

### Share Early, Share Often

Share thoughts, designs, code, problems, incidents, and anything else as early as possible to let folk know what's going on and be able to provide feedback. Share often to keep folk informed as situations evolve.

### We Succeed and Fail Together

Software Engineering is a team activity where we win and lose together: there is never a single responsible individual. Share problems, run Blameless Post-Mortems (BPMs), incidents, or project delays as soon as possible.

### Prefer Small Changes

Many small changes are less than the sum of their parts but they're easier to reason about. A small change is easier to review, easier to roll-back, and harder to get "wrong".
