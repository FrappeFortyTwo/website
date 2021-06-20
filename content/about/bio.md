---
title: "Professional Bio"
description: "What mischief I've been upto"
imgURL: "/images/sample.png"
katex: "true"
---

{{<mermaid>}}
classDiagram
Class01 <|-- AveryLongClass : Cool
Class03 *-- Class04
Class05 o-- Class06
Class07 .. Class08
Class09 --> C2 : Where am i?
Class09 --* C3
Class09 --|> Class07
Class07 : equals()
Class07 : Object[] elementData
Class01 : size()
Class01 : int chimp
Class01 : int gorilla
Class08 <--> C2: Cool label
{{</mermaid>}}

# Concurrency

When we think about `concurrency` another idea automatically comes attached to it that is `parallelism`. Before discussing concurrency and how it works, we must have some idea about both these concepts to avoid confusion.

A `blocking call` is call is where program execution comes to a halt, such as while sleeping, or when waiting for an http response.

## Concurrency
`single CPU Core`
***
{{<details "somee shit">}}

Scheduler runs one go routine until it finishes or makes a blocking call, and switches to another. This way multiple chunks of code run (kinda) at the same time. By default go tries to use only a single core.
We can have multiple threads executing code. If one thread blocks, another one is picked up and worked on.

lorem
{{</details>}}

{{<mermaid "something">}}
    graph TD
    K[CPU Core]
    K --- A[Scheduler]
    A --- B[Go Routine]
    A --- C[Go Routine]
    A --- D[Go Routine]
{{</mermaid>}}

# Hello


{{<katex>}}
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
{{</katex>}}

