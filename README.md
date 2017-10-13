# Algebraic Graphs with Class

The paper is freely available in the ACM Digital Library: https://dl.acm.org/authorize?N46678.

Alternatively, you can download the preprint from https://github.com/snowleopard/alga-paper/releases.

Talks:
* Haskell eXchange 2017 (longer and more recent): [slides](https://github.com/snowleopard/alga-paper/releases/download/final/algebraic-graphs-haskellx.pdf).
* Haskell Symposium 2017: [slides](https://github.com/snowleopard/alga-paper/releases/download/final/algebraic-graphs-slides.pdf).


## Abstract

The paper presents a minimalistic and elegant approach to working
with graphs in Haskell. It is built on a rigorous
mathematical foundation --- an algebra of graphs --- that allows us to apply
equational reasoning for proving the correctness of graph transformation
algorithms. Algebraic graphs let us avoid partial functions typically
caused by 'malformed graphs' that contain an edge referring to
a non-existent vertex. This helps to liberate APIs of existing graph libraries
from partial functions.

The algebra of graphs can represent directed, undirected, reflexive
and transitive graphs, as well as hypergraphs, by appropriately choosing
the set of underlying axioms. The flexibility of the approach is
demonstrated by developing a library for constructing
and transforming polymorphic graphs.

## Implementation

See https://github.com/snowleopard/alga for the source code and links to blog posts.
