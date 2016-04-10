# Pandas Weirdness of the Week

A collection of Weird behaviour encountered when using Pandas.

Weird behaviour has a fuzzy definition. In some cases the behaviour is a bug. In other cases it is correct but unexpected behaviour. 
In most cases not understanding or expecting the behaviour will leads to bugs in Pandas users' code. This repo documents the strange behaviour found in the hope that once documented these bugs can be avoided     

*Pull requests most welcome!*

Weirdnesses:

* [Negative Slicing with ix](./notebooks/2016-03-17-negative-slicing.ipynb)
* [Inconsistent behaviour with to_datetime](./notebooks/2016-04-10-coerce-NaT.ipynb)

## Faq

*Some of these look pretty weird - should I use Pandas?*
If you are doing data analysis in Python I strongly recommend using Pandas. Pandas is a large library with and large complex API. Bugs and unexpected behaviour are unavoidable in any project of this complexity.  

*Isn't this what Github issues are for?*
There are over 1,000 issues currently open for Pandas. This repo is meant to highlight behaviour that is unexpected with a high probablility of being encountered by the average user. Where possible the relevant Github issue is referenced.
