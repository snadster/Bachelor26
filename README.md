# Technical details
Bachelor Project within Computer Science, written at SDU Odense in spring of 2026.
**Bachelors students:** Sofie Løfberg & Sandra Johansen
**Advisor:** Sandra Greiner
Currently a work in progress, expected done by summer of 2026.

# Description: A web-based knitting pattern configuration tool

##  Background and Topic Area

Software Product Line Engineering is a paradigm to tame the complexity of configurable software systems and to efficiently create customized software products.
Research recommends a proactive development process: developers shall create a platform that realizes all identified features. Given a full selection of features (called configuration), customized (software) products can be derived ideally completely automatically. [1]

## Motivation and Problem

In practice, identifying all supported features in the product line, including possible interaction (feature A forbids to select feature B), poses a first challenge. A second challenge lies in realizing the platform with a targeted variability mechanism (e.g., annotative, delta-oriented, feature-oriented) and ensuring that the derived product is actually sound (in case of source code it compiles and passes all tests). Finally, choosing how to configure the product of a product line exhibits several strategies in the wild [1,2].

Using (software) product line engineering methods in the area of knitting and crocheting patterns is fully unexplored. Similar to software features, elements of these patterns can be recombined resulting in billions of different variants. So far, technical support is rare. Small devices help in memorizing counts but help to configure novel knitting and memorizing variants relies on the pure inspiration and brain of human beings.

## Contribution

This project shall explore how an online configuration tool can help creating novel knitting pattern variants by using product line engineering methods.
To do so, a feature model with knitting patterns will be created as result of a domain analysis.  It will serve as basis to build the online configuration tool.
At the same time, a realization mechanism is devised which helps to assemble the selected features.


## Success criteria

At a minimum, a small feature model that builds the basis for the configuration tool is created. It shall be possible to select and create at least different 5 variants of knitting and crocheting patterns from the online tool .

      
[1] Sven Apel, Don S. Batory, Christian Kästner, Gunter Saake:
Feature-Oriented Software Product Lines - Concepts and Implementation. Springer 2013, ISBN 978-3-642-37520-0, pp. I-XVI, 1-315

[2] Thomas Thüm, Sebastian Krieter, Ina Schaefer:
Product Configuration in the Wild: Strategies for Conflicting Decisions in Web Configurators. ConfWS 2018: 1-8
