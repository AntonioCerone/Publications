---
title: Using Maude to Model Motivation in Human Behaviour
summary: Published on LNCS, Springer.
authors:
    - Antonio Cerone
date: 2024-07-15
some_url: https://antoniocerone.github.io/Publications/2023/CIFMA/
---
# Using Maude to Model Motivation in Human Behaviour
## Antonio Cerone and Olzhas Zhangeldinov
Presented at [CIFMA 2023](https://cifma.github.io/2023/)
### Abstract
Human beings act and think driven by motivation, which can be physiological as well as psychological.
Although there is no unified theory of motivation, there are a number of theories in psychology that define
conceptual models to explain distinct kinds and aspects of motivation. 
Such a conceptual fragmentation of the notion of motivation makes it very challenging the attempt to build
a formal framework to model motivation.
In this paper we address the needs underlying motivation, focusing in particular on physiological needs,
such as the ones for food, water and sleep, and on the lowest level of psychological needs, the needs
for safety and security.
We use BRDL (Behaviour and Reasoning Description Language) to model human behaviour and thinking as well as
its psychological motivation and LTS (Labelled Transition Systems) to model physiological motivation.
Finally, we illustrate our translation of this formal framework into the Maude rewrite language,
which supports the simulation and analysis of the modelled cognitive systems.
### Keywords
Cognitive Modelling; Rewriting Logic; Maude; Theories of Motivation.
### Maude Code
**GitHub repository:**
* [https://github.com/CIFMA/cifma.github.io/blob/master/index.html](https://github.com/AntonioCerone/Publications/tree/master/2023/CIFMA)

**Download:**
* [README.txt](README.txt)
* [entities.maude](entities.maude)
* [example-vending.maude](example-vending.maude)
* [generic-evolution.maude](generic-evolution.maude)
* [prelude.maude](prelude.maude)
* [untimed-evolution.maude](untimed-evolution.maude)

### To Run the Code

1. Download and install Maude 2.7.1 from: https://maude.cs.illinois.edu/wiki/The_Maude_System

   (Real-Time Maude does not work with Maude 3)

2. Download Real-Time Maude from: https://olveczky.se/RealTimeMaude/

   and copy it in the Maude directory.

3. Start the Maude system. The following prompt should appear:

   **maude>**
4. Start Real-Time Maude:
   
   **maude> load real-time-maude**
   
5. Load the example

   **maude> load example-vending.maude**
