# Engineering Principles

## Why Have Principles?
Our engineering principles are not about who we are, but who we *choose* to be. They are a conscious choice that help lead us towards the organisation we aspire to be.

Owned by us all, they represent the behaviours that define our engineering culture, and those we want to apply.

**We apply these principles to everything we do.**

## Our Tenets

### Pragmatism
*Choosing the practical path forwards given the current situation.*

We make straight-forward decisions which are correct in the moment and are easily defendable. For example, it's more pragmatic to add a new endpoint to an existing REST API than creating an entirely new API and supporting infrastructure.

### Simplicity
*Optimising for others’ comprehension over one’s ego.*

We always write code that is simple to read and design systems that are easy to understand. Things shouldn’t be more complicated or complex than they absolutely must be. Simple systems are easier to reason about, cheaper to run, and more straightforward to keep secure.

## Our Principles

### Consistency by Default

We should strive for consistency unless there is a magnitudinal improvement. That means using familiar technology & tools and following existing patterns where they exist—unless there is a significant advantage to doing otherwise. For example, REST is the primary way systems communicate with each other; creating a new service using gRPC would be inconsistent.

### Be Explicit

Write things down and explain the reasoning. For example, document small decisions in code comments, or for larger decisions write Architectural Decision Records (ADRs).

### Value a Second Opinion

Share thoughts, designs, code, problems, incidents, and anything else as early as possible to let folk know what's going on so they can provide feedback. Share often to keep everyone informed as situations evolve. Feedback is a gift that can be given freely.

### We Succeed and Fail Together

Software Engineering is a team activity where we win and lose together: there is never a single responsible individual. Run Blameless Post-Mortems (BPMs), and share problems, incidents, or project delays as soon as possible. But don’t forget to celebrate our successes!

### Prefer Small Changes

Many small changes are less than the sum of their parts but they're easier to reason about. A small change is easier to give feedback on, easier to roll-back, can build confidence and comfort through frequent releases, and is harder to get “wrong”. Many small changes allow for many small improvements. And bluntly, 10KLOC PRs don’t get good reviews!

### Secure by Design

We’re all responsible for the security of our systems, holding them to a high standard to protect the data our customers trust us with. Think about how someone could abuse a system, whether they’re outside the company or already inside it, and close those gaps before it ships. Our engineering standards describe what this looks like in practice, and following them is how we get there.
