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

1. Quantum Computing for Option Valuation Description, [Bloomberg
   LP](https://www.bloomberg.com/company/)

    During the summer of 2020 I did a 3 month Software Engineering Internship at Bloomberg LP
    working for the London office on the department of Financial Analytics. My
    project consisted of implementing ideas from the paper [Option Pricing
    using Quantum Computers](https://arxiv.org/abs/1905.02666) to develop a
    product for pricing a variety of [option
    contracts](https://www.investopedia.com/terms/o/option.asp) and integrate
    it to the Bloomberg terminal.

    We developed an API from scratch that received pricing requests for
    European, Asian and Barrier options in the appropriate format. After
    parsing the requests our service constructed the appropriate circuit that
    would perform the pricing of the option using [Quantum Amplitude Estimation](https://arxiv.org/abs/quant-ph/0005055).
    Then our API would contact the Quantum Computers accessible
    through [IBM Quantum Experience](https://quantum-computing.ibm.com/) and
    return the price of the requested option contract.

    Our project achieved matching results to traditional pricing methods such
    as
    [Black-Scholes](https://en.wikipedia.org/wiki/Black%E2%80%93Scholes_model)
    and therefore is a major stepping stone for the use of the novel Quantum
    Computing techniques in the Financial Technology spectrum.

    Technologies used: Python, Javascript, C++, XML, Node.JS, React.JS, Numpy,
    Qiskit, Matplotlib

    Points of reference: [Callum
    Piper](https://www.linkedin.com/in/callum-piper-3691373/?originalSubdomain=uk),
    [Mark Smith](https://www.linkedin.com/in/mark-smith-038a6b162/)

2. Epidemic Simulator,
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

3. QuaSiMode, [Github](https://github.com/infinity4471/QuaSiMode)

    QuaSiMode(Quantum Simulator) is a framework where you can develop and run
    [Quantum Circuits](https://en.wikipedia.org/wiki/Quantum_circuit). It's a
    primal quantum computer simulator built from scratch. The circuits are 
    modeled as [Directed Acyclic Graphs](https://en.wikipedia.org/wiki/Directed_acyclic_graph)
    and there is a method for actually viewing the graphical representation of
    the circuits.

    QuaSiMode allows you to measure your circuits and extract results. You can
    find some sample circuits implemented like [Quantum Coin
    Flip](https://github.com/infinity4471/QuaSiMode/blob/master/entanglement.py)
    or [Quantum
    Teleporation](https://en.wikipedia.org/wiki/Quantum_teleportation). Feel
    free to play around!

    Technologies used: Python 3.8, Numpy, Networkx, Matplotlib
