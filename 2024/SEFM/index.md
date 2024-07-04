---
title: SEFM 2024
summary: Submitted conference paper information, including abstract, keywords and links to the code.
authors:
    - Antonio Cerone
date: 2024-07-04
some_url: https://antoniocerone.github.io/Publications/2024/SEFM/
---
# Formal Modelling and Verification of Multy-party Human-computer Interaction
## Antonio Cerone and Olzhas Zhangeldinov
Submitted to [SEFM 2024](https://sefm-conference.github.io/2024/)
### Abstract
The unpredictability of human behaviour makes formal analysis of human-computer interaction (HCI)
already difficult when one single user is interacting with one computer system.
However, nowadays interaction normally involves several users, i.e., human components, interacting
simultaneously with separate interfaces which communicate with and/or act upon the same computer resource.
Independently on whether the human components aim at using computer resources to communicate with each
other or to concurrently act upon and modify information stored in  computer resources, not only need
interface to be usable but they also must prevent those forms of user behaviour that may negatively
interfere with actions performed by other users.

In this paper, we define a framework that combines the formal modelling of cognitive aspects of human
components and the modelling of actual computer system into an overall model that can be formally analysed
using model-checking.
We use the Behaviour and Reasoning Description Language (BRDL) to model human cognition and we encapsulate
it within an extension of the Real-time Maude language that is used to model the computer system.
Real-time Maude model-checker is then used to carry out formal verification.
### Keywords
Human-computer Interaction; Human Cognition; Model Checking; Maude Rewrite System.
### Maude Code
**GitHub repository:**
* [https://github.com/CIFMA/cifma.github.io/blob/master/index.html](https://github.com/AntonioCerone/Publications/tree/master/2024/SEFM)

**Download:**
* [entities.maude](entities.maude)
* [example-registration-lts.maude](example-registration-lts.maude)
* [timed-evolution.maude](timed-evolution.maude)
