# The devEco devOSH Open Modular Design Specification - Preliminary  Proposal

## Table of Contents

## Summary

This document is an initial draft of the devEco devOSH Modular Open Design Specification. It will describe the process required to develop functional design units, or modules that can be combined together to create a valid schematic and layout with minimal electronics design knowledge or experience.

## Introduction

Modular design has been beneficial to many industries. Construction, motor vehicles, software development and aerospace all benefit from breaking complex systems down into functional, modular components. the devHW-MODS initiative strives to apply this design strategy to PCB design for the benefit of hobbyists, embedded developers, and the Open Hardware community.

### Why PCB Design

PCB design has a notoriously high barrier to entry compared to many adjacent disciplines. Not only does it require a solid education in circuit analysis, and a good understanding of materials Science, but the tools themselves are necessarily complex.

Unfortunately, it is also something that stands in the way of many developers with innovative, creative, or even world-changing ideas. Modular open PCB design aims to do for the embedded developerwhat Arduino did for artists and creators. If they are given tools that abstract away the majority of the complexity, they have the opportunity to create something amazing.

### Why Open

In order to truly foster growth in embedded technology, the tools cannot be locked to closed intellectual property. The practice of freely providing tools that force users into using a single paid service for manufacturing and delivery invites legal issues regarding ownership and monopoly on support.

Individuals, consultants,and businesses should be free to use the result of their efforts as they see fit, with the exception of attribution and waiver of liability, as discussed in a later section.

### Why Modular

There is a high potential for error in electronics design at the passive component level. Resistor-capacitor (RC) circuits for comparators or voltage regulators, resistors on MCU configuration pins, decoupling capacitors on power inputs, and many more, have caused an uncountable number of board failures. 

Additionaly, certain components must always be connected to specific support devices. some microcontrollers require external flash memory, for example, and are unusable without. By including these fundamental components as part of the design element, designers with little to no electrical engineering training will experience fewer failures from these and similar flaws.

## Software Requirements

The devOSH Open Modular Design Specification has been defined for use with contemporary versions of KiCad (>=8.0). Any scripts or software tools produced to support the spec shall be designed such that they work harmoniously, or symbiotically, with these versions of KiCad. All design modules shall be released as a KiCad project.

## The Specification

The sections below cover the technical aspects of the specification.

The schematic specification describes, in detail, the permitted scope of a single module. In addition it defines naming conventions, placement, and grouping of nets and signals that are targeted at inter-module connection, as well as any other conventions that aid in merging design module schematics.

The layout specification describes what routing is permitted, prohibited, and required within a module. It provides footprint selection strategies and provides recommendations for initial placement density.

The project file structure specification describes project, file and folder naming conventions, as well as guidelines for any submitted firmware or example code.

By following the specification, module designers ensure a smooth integration with other existing or future modules. It also provides the foundation for a software ecosystem to support and facilitate the module library's use.

### Schematic Specification

### Layout Specification

### Project File Structure Specification

## Proposed Rules

### EDA Design Rules

### Bill of Materials and Part Sourcing

### Module Submission and Review Process

### Module Validation

### Attribution and Liability

## Community Guidelines

### GitHub

### devEco Discord Server

### DMs and E-Mail

## Conclusion
