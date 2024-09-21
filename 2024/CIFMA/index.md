---
title: Cognitive Aspects in the Formal Modelling of Multi-party Human-computer Interaction
summary: Submitted conference paper information, including abstract, keywords and links to the code.
authors:
    - Antonio Cerone
date: 2024-09-21
some_url: https://antoniocerone.github.io/Publications/2024/CIFMA/
---
# Cognitive Aspects in the Formal Modelling of Multi-party Human-computer Interaction
## Antonio Cerone and Olzhas Zhangeldinov
Submitted to [CIFMA 2024](https://cifma.github.io)
### Abstract
The unpredictability of human behaviour makes formal analysis of human-computer
interaction (HCI) already difficult when one single user is interacting with one
computer system. However, nowadays interaction normally involves several users,
i.e., human components, interacting simultaneously with separate interfaces
which communicate with and/or act upon the same computer resources.
Independently of whether human components aim at using computer resources to communicate
with each other or to concurrently act upon and modify stored information, not only need
interfaces to be usable but they also must protect users from the potential negative
effects caused by the behaviour of other users.

In this research paper, we define a framework that combines the formal modelling of
cognitive aspects of human components and the modelling of the actual computer system
into an overall model that can be formally analysed using model-checking. We use the
Behaviour and Reasoning Description Language (BRDL) to model human cognition and
implement our framework using Real-time Maude, whose model-checker is then used to
carry out formal verification.
### Keywords
Human-computer Interaction;
Human Cognition;
Behaviour and Reasoning Description Language;
LTSs;
Formal Analysis.
### Maude Code
**GitHub repository:**
* [https://github.com/CIFMA/cifma.github.io/blob/master/index.html](https://github.com/AntonioCerone/Publications/tree/master/2024/CIFMA)

**Download:**
* [README.txt](README.txt)
* [entities.maude](entities.maude)
* [example-registration-lts.maude](example-registration-lts.maude)
* [timed-evolution.maude](timed-evolution.maude)

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

   **maude> load example-registration-lts.maude**
