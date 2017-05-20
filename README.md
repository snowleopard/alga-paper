# Algebraic Graphs with Class

Get the PDF here: https://github.com/snowleopard/alga-paper/releases/download/icfp-submission-archived/alga.pdf.

## Abstract

The paper presents a minimalistic, elegant and powerful approach to working
with graphs in a functional programming language. We build on a rigorous
mathematical foundation --- an algebra of graphs --- that allows to apply
equational reasoning for proving the correctness of graph transformation
algorithms. Algebraic graphs allow to avoid partial functions, typically
required for handling 'malformed graphs' that contain an edge referring to
a non-existent vertex. Such malformed graphs are impossible to specify
algebraically, which helps to liberate APIs of existing graph libraries
from partial functions.

We show that the algebra of graphs can represent directed, undirected, reflexive
and transitive graphs, as well as hypergraphs, by appropriately choosing
the set of underlying axioms. The flexibility of the approach is
demonstrated by a few examples, and by developing a library for construction
and transformation of polymorphic graphs.

## Implementation

See https://github.com/snowleopard/alga for the source code and links to blog posts.
