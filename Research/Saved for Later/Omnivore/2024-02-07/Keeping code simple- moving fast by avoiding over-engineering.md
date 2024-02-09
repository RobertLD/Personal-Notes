---
id: cfe83b0e-f33c-45aa-9f3f-95a2344dec6e
---

#Omnivore

[Read on Omnivore](https://omnivore.app/me/keeping-code-simple-moving-fast-by-avoiding-over-engineering-18d8545c886)
[Read Original](https://graphite.dev/blog/keeping-code-simple)

## Highlights

> ## **Urgently building a todo list slowly** [⤴️](https://omnivore.app/me/keeping-code-simple-moving-fast-by-avoiding-over-engineering-18d8545c886#21fdabd7-be61-48f2-8a77-ce32e54b2234)  ^21fdabd7

> Extending the story with a bit of realism, let’s assume you get halfway through coding the to-do list when your manager and PM start breathing down your neck. You’re running out of time, and the feature needs to get out the door yesterday. You start typing faster, but you also start skipping clean coding patterns. Your functions become more coupled, you directly call external libraries all over, and you skip writing any unit tests. Along the way you also cut and modify scope all over the place, hacking your initial spec to pieces. [⤴️](https://omnivore.app/me/keeping-code-simple-moving-fast-by-avoiding-over-engineering-18d8545c886#589319a2-9531-437f-a165-146f32e2751c)  ^589319a2

> The to-do list ships on time, albeit with a few more bugs than you would have liked. [⤴️](https://omnivore.app/me/keeping-code-simple-moving-fast-by-avoiding-over-engineering-18d8545c886#e64d0191-8984-4088-b9b6-1ee8b3db1c2e)  ^e64d0191

> delivering sloppy architecture while at the same time over-engineering performance, scalability, and security. [⤴️](https://omnivore.app/me/keeping-code-simple-moving-fast-by-avoiding-over-engineering-18d8545c886#e7e95910-6b12-4361-9234-2d4b2843971a)  ^e7e95910

> This inevitably reduces quality, due to the unplanned cost of more time debugging and slower estimates on iterative changes, while over-engineered specs often go forever unused. [⤴️](https://omnivore.app/me/keeping-code-simple-moving-fast-by-avoiding-over-engineering-18d8545c886#f2729efa-6961-423a-98b2-739bd9946ef3)  ^f2729efa

> Over-engineering is an attempt to predict the future, while quality-engineering is maximizing extensibility. [⤴️](https://omnivore.app/me/keeping-code-simple-moving-fast-by-avoiding-over-engineering-18d8545c886#cca2339a-194d-47d4-9803-dd42793d22c8)  ^cca2339a

> The bare minimum spec needs a data store that can read and write thousands of text records. In the future, it may need to be faster, bigger, more secure, or backed by the network. But you don’t know yet, so the best thing you can do is punt the decision and throw the data store behind a narrow interface. Code a module with a simple generic read-and-write interface, and for the sake of your MVP, initially implement the entire datastore as a JSON blob written to disk. [⤴️](https://omnivore.app/me/keeping-code-simple-moving-fast-by-avoiding-over-engineering-18d8545c886#2503545c-662b-452f-bb86-c896680fd3bf)  ^2503545c

> Over-engineering is inefficient for two fundamental reasons:
> 
> 1. Wasted time: Any feature that isn’t necessary costs time to implement that could have been spent implementing other necessary features.
> 2. Slowing development: Extra features result in extra complexity. Codebase complexity slows down future development. [⤴️](https://omnivore.app/me/keeping-code-simple-moving-fast-by-avoiding-over-engineering-18d8545c886#806a35cb-3ca7-4970-99d0-69d83ac243c5)  ^806a35cb

> Punt complexity as long as possible [⤴️](https://omnivore.app/me/keeping-code-simple-moving-fast-by-avoiding-over-engineering-18d8545c886#bed6fd79-237f-41b6-9364-eea3c3696bd8)  ^bed6fd79

> Engineers should build to the minimum product specifications needed at the time while holding to high-quality engineering standards. In order to follow the best practices for simple, clean coding prioritize:
> 
> * unit tests
> * linters
> * narrow interfaces
> * low coupling
> * clean variable names
> 
> Punt on:
> 
> * powerful data stores
> * complicated APIs
> * unnecessary frameworks
> 
> The fastest way to engineer is to punt as much as possible - often by separating the core application logic from dependencies that you might change in the future. [⤴️](https://omnivore.app/me/keeping-code-simple-moving-fast-by-avoiding-over-engineering-18d8545c886#8e3fcf6f-340d-4f8f-995c-a6fddc10d827)  ^8e3fcf6f

