# kormanize

A LaTeX environment/package for representing arguments.

With apologies, inspired by my friend and former professor [Dan Korman][1] (now at UCSB) this LaTeX package provides an environment for representing arguments in standard form using the "@#" style that Dan taught and used while I was his student at UIUC.

## Basics

In philosophy an argument is in __standard form__ iff the argument satifies the following conditions:

1. The argument is represented in an enumerated or ordered list.
2. Each item in the list is a single proposition, either premise or conclusion.
3. The premises are listed directly above the conclusion they immediately support.

Some authors also require a conclusion indicator word such as "Therefore..." or "So..." for the argument to be in standard form.

Jointly, the requirements of standard form ensure that each proposition in the argument can be individually identified and that the structure of the argument is more clearly presented. However, standard form can stand to be improved and a kormanized argument is a step in that direction.

### Example Standard Form Argument

1. We are morally responsible for our actions only if we can do otherwise.
2. We can not do otherwise.
3. So, we are not morally responsible for our actions.

## Motivation

In most academic work in philosophy, several arguments are under discussion in a paper. This motivates a desire to distinguish between both individual propositions in the argument but also propositions among different arguments. Ideally, we could [rigidly designate][2] every proposition but this approach faces many practical, philosophical, and political problems. See e.g. the first sentence in the [SEP article on "naturalism"][3]:

> The term "naturalism" has no very precise meaning in contemporary philosophy.

Given that any attempt at rigid designation of propositions in philosophy will require institutional cooperation that seems unlikely, we can improve standard form by adding another counter to each argument. So each kormanized argument begins with a letter in addition to the number that counts propositions within the argument: "@#"

### Example Kormanized Argument

A1. We are morally responsible for our actions only if we can do otherwise.
A2. We can not do otherwise.
A3. So, we are not morally responsible for our actions.

[1]: http://www.philosophy.ucsb.edu/faculty/korman/
[2]: https://plato.stanford.edu/entries/rigid-designators
[3]: https://plato.stanford.edu/entries/naturalism/
