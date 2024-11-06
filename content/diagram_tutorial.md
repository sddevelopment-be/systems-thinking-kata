+++
title = "Causal Loop Diagrams"
subtitle = "Modeling complex systems with causal loop diagrams"
aliases=["causal-loops", "diagramming_tutorial"]
author = "Stijn Dejongh"
description = ""
summary="""
"""
further_exploration = [
    {type="raw", author="Kim, H.D.", year="?", title="Guidelines for Drawing Causal Loop Diagram", link="https://www.cs.toronto.edu/~sme/SystemsThinking/GuidelinesforDrawingCausalLoopDiagrams.pdf", publisher="University of Toronto", site="cs.toronto.edu"},
    {type="raw", author="Sterman, J.D.", year="2000", title="Business Dynamics: Systems Thinking and Modeling for a Complex World", link="https://www.goodreads.com/book/show/39736248-business-dynamics", publisher="McGraw-Hill Education",  isbn="978-0072389159"},
    {type="raw", author="Meadows, D.H.", year="2008", title="Thinking in Systems: A Primer", link="https://www.goodreads.com/book/show/3828902-thinking-in-systems", publisher="Chelsea Green Publishing", isbn="978-1603580557"},
    {type="raw", author="Senge, P.", year="2006", title="The Fifth Discipline: The Art & Practice of The Learning Organization", link="https://www.goodreads.com/book/show/86618.The_Fifth_Discipline", publisher="Doubleday", isbn="978-0385517256"},
    {type="raw", author="Stroh, D.P.", year="2015", title="Systems Thinking For Social Change", link="https://www.amazon.com/Systems-Thinking-Social-Change-Consequences/dp/160358580X", publisher="Chelsea Green Publishing", isbn="978-1603585804"}
]
+++

This tutorial will introduce you to the basics of Causal Loop Diagrams, and provide you with some examples to help you get started with modeling
your own complex systems.

After completing this introductory tutorial, you will be able to:

* Read and interpret a Causal Loop Diagram
* Understand the basic concepts behind modeling complex systems
* Be able to create your own Causal Loop Diagrams

## Introduction

Systems Thinking is an approach to understanding and solving complex problems by viewing them as parts of an interconnected whole rather than in
isolation. It involves recognizing patterns, relationships, and feedback loops within systems to better anticipate the impact of decisions and
actions, thereby enabling more holistic and effective solutions.

In order to model these complex systems, we use a variety of tools and techniques to help us visualize and understand the relationships between
various elements within our chosen system. One such tool is the `Causal Loop Diagram`, which is a graphical representation of the feedback loops
that (likely) exist within a system.


## Basic Concepts

The basic building blocks of a Causal Loop Diagram are `Nodes` and `Links`. **Nodes** represent the elements within the system that we are modeling.
These are concepts, objects, or entities that interact with each other in some way. They are generally depicted as circles, boxes, or words, and
are written down as nouns or noun phrases.

**Links** represent the relationships between the nodes. These are the connections, influences, or dependencies that exist between the elements 
of the diagram. They are generally depicted as directed arrows or simple lines. The direction of the arrow indicates the nature of the 
relationship. A node can either have no effect, a strengthening effect, or a weakening effect on the node it connects to. In other words, if the 
quantity of one node increases, what happens to the quantity of the other node?

* **Same**: If the quantity of one node increases, the quantity of the other node also increases.  
  This is depicted by a line with an arrowhead (and optionally a `+` or `S` sign). Mathematically, this is know as a correlation.
* **Opposite**: If the quantity of one node increases, the quantity of the other node decreases.  
  This is depicted by a line with an arrowhead and a `−` or `O` sign. Mathematically, this is known as an inverse correlation.
* **None**: If the quantity of one node increases, the quantity of the other node remains the same.
  This is the easiest to draw, as you don't need to draw any line at all.

### Chickens, Eggs, and Road Crossings



{{< image src="/images/diagramming/example_loop.png" alt="Causal Loop Diagram for chickens cross the road" size="50%" >}}

## Less Common Concepts

### Balancing and Reinforcing Loops





