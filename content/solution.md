## Solution
{:#solution}

We propose an extension of the existing [traversal-based query processing technique for Solid](cite:cites solidquery)
that is able to discover heterogeneous interfaces on pods besides the regular document-oriented interface.
Furthermore, these discovered interfaces can then be incorporated into the query plan in an adaptive manner.
Concretely, we will develop a prototype of this approach into the open-source [Comunica](cite:cites comunica) query engine framework.
In order to evaluate this approach, we will expose heterogeneous interfaces in the simulated SolidBench environment,
which simulates a decentralized Solid environment containing pods by different people based on a social networking use case.
