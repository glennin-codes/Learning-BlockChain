## Distributed systems


A distrubuted system is a computing paradigm whereby two or more node work together in a cordinated fashoin to achieve a common outcome.

It composed of process ``NODES`` and Channels ` communication channels`  where nodes communicate by passing message.A blockchain is a message passing distributed system.


**A Node** is an individual player `computer` in a distributed systems.All nodes send and recieve messeges to and from each other.
 - Nodes can be honesty,faulty and malicious and the have memory and processor.
 - a node that exhebits arbitrary behaviour is called a **bzyantine node** 

      - <span style="color: blue;">
      ✔️ **The Byzantine Generals problem**
In 1982, a thought experiment was proposed by Lamport et al. in their research paper,
The Byzantine Generals Problem, which is available here: https://www.microsoft.com/
en-us/research/publication/byzantine-generals-problem/
In this problem, a group of army generals who lead different parts of the Byzantine army
is planning to attack or retreat from a city. The only way of communicating with them is
via a messenger. They need to agree to strike at the same time to win. The issue is that one
or more generals might be traitors who could send a misleading message. Moreover, the
messenger could be captured by the city, resulting in no message delivery. Therefore, there
is a need for a viable mechanism that allows agreement among the generals, even in the
presence of the treacherous ones, and message loss, so that the attack can still take place
at the same time. As an analogy for distributed systems, the generals can be considered
as honest nodes, the traitors as Byzantine nodes (that is, nodes with arbitrary behavior),
the messenger can be thought of as a channel of communication with the generals, and
a captured messenger as a delayed or lost message. Several solutions were presented to
this problem in the paper by Lamport et al. in 1982.
</span>
