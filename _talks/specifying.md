---
name: 'Specifying Source Code and Signal-based Behaviour of Cyber-Physical System Components'
speakers:
  - Joshua Dawes
  - Domenico Bianculli
categories:
  - Cyber-Physical Systems
---

Specifying properties over the behaviour of components of Cyber-Physical Systems usually 
focuses on the behaviour of signals, i.e., the behaviour of the 
physical part of the system, leaving the behaviour of the cyber 
components implicit. There have been some attempts to provide 
specification languages that enable more explicit reference to the 
behaviour of cyber components, but it remains awkward to directly 
express the behaviour of both cyber and physical components in the 
same specification, using one formalism. 

In this paper, we introduce a new specification language, Source Code 
and Signal Logic (SCSL), that 1) provides syntax specific to both 
signals and events originating in source code; and 2) does not require 
source code events to be abstracted into signals. We introduce SCSL 
by giving its syntax and semantics, along with examples. We then 
provide a comparison between SCSL and existing specification 
languages, using an example property, to show the benefit of using SCSL 
to capture certain types of properties.