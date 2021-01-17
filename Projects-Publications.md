---
layout: page
title: Projects-Publications
permalink: /Projects-Publications/
---

Thanks for sticking around. Below you can find a list of my publications as
well as some of the projects I am most proud of.

### Publications

1. Dimitris Fotakis, Loukas Kavouras, Panagiotis Kostopanagiotis, Philip Lazos,
   Stratis Skoulakis, Nikolas Zarifis. ["Reallocating Multiple Facilities on the
   Line"](https://arxiv.org/abs/1905.12379). [International Joint Conference on
   Artificial Intelligence 2019](https://ijcai19.org/)

### Projects

1. Epidemic Simulator,
   [Github](https://github.com/infinity4471/Epidemic-Simulator)

   This was a project developed during the early stages of lockdown in Greece.
   We used a modified [SIR
   Model](https://en.wikipedia.org/wiki/Compartmental_models_in_epidemiology)
   where every individual was modeled as a point in a 2-dimensional space
   executing a [brownian
   motion](https://en.wikipedia.org/wiki/Brownian_motion).
   
   The population parameters could be altered by the user and there was a real
   time graphical representation of several statistical measures.

   Later on we added modes that resembled the real world such as a region of
   interest where every particle was attracted to through a random potential
   function or a random sampling algorithm where the infectious individuals
   where isolated from the general population and quarantined until cured. This
   allowed us to observe how different senarios affect the curves and the
   statistics of the simulation.

   Technologies used: Python 3.8, Numpy, Matplotlib

   Co-authors: [Natalia Salpea](https://github.com/nattienat09)

2. QuaSiMode, [Github](https://github.com/infinity4471/QuaSiMode)

    Through my summer internship in Bloomberg LP I developed an interest for
    Quantum Computing both from a theoretical as well as from a practical point
    of view. This project was heavily influenced from thsi experience.

    QuaSiMode(Quantum Simulator) is a framework where you can develop and run
    [Quantum Circuits](https://en.wikipedia.org/wiki/Quantum_circuit). It's a
    primal quantum computer simulator built from scratch. The circuits are 
    modeled as [Directed Acyclic Graphs](https://en.wikipedia.org/wiki/Directed_acyclic_graph)
    and there is a method for actually viewing the graphical representation of
    the circuits.

    QuaSiMode allows you to measure your circuits and extract results. You can
    also find some sample circuits implemented like [Quantum Coin
    Flip](https://github.com/infinity4471/QuaSiMode/blob/master/entanglement.py)
    or [Quantum
    Teleporation](https://en.wikipedia.org/wiki/Quantum_teleportation)

    Technologies used: Python 3.8, Numpy, Networkx, Matplotlib
