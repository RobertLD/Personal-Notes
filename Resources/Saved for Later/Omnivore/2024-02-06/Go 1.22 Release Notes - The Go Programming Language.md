---
id: 15d4b368-89df-4662-bb21-9f030b2fc7a4
---

#Omnivore

[Read on Omnivore](https://omnivore.app/me/go-1-22-release-notes-the-go-programming-language-18d811c8905)
[Read Original](https://go.dev/doc/go1.22)

## Highlights

> Previously, the variables declared by a "for" loop were created once and updated by each iteration. In Go 1.22, each iteration of the loop creates new variables, to avoid accidental sharing bugs. [⤴️](https://omnivore.app/me/go-1-22-release-notes-the-go-programming-language-18d811c8905#2bc2bf90-789e-40f2-a100-0bb805e232de)  ^2bc2bf90

> The runtime now keeps type-based garbage collection metadata nearer to each
>   heap object, improving the CPU performance (latency or throughput) of Go programs
>   by 1–3%.
>  [⤴️](https://omnivore.app/me/go-1-22-release-notes-the-go-programming-language-18d811c8905#56bbd796-b1f3-482f-aefd-48ee797e14ce)  ^56bbd796

> Profile-guided Optimization (PGO) builds
>   can now devirtualize a higher proportion of calls than previously possible.
>   Most programs from a representative set of Go programs now see between 2 and
>   14% improvement from enabling PGO. [⤴️](https://omnivore.app/me/go-1-22-release-notes-the-go-programming-language-18d811c8905#d3ca5856-d1f0-4fbf-bf50-dcef065df7be)  ^d3ca5856

