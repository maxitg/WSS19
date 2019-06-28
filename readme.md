# Wolfram Summer School 2019 - Maksim Piskunov

## Quantum SetReplace [Final Project]
The goal is to understand how quantum physics might work in [SetReplace](https://github.com/maxitg/SetReplace) systems.

The basic idea is to consider SetReplace systems, which are not necessarily confluent. That means, they will have critical pairs, which are the pairs of potential substitution events, which produce different outputs. If we allow the system to evolve, we will get a multiway system in which different branches do not interact.

That has a certain resemblance to the many-worlds interpretation of quantum physics, except probabilities are combined in the wrong way.

Alternatively, every time we encounter a critical pair, we can add a new pair of rules, which would replace two different outcomes into each other. This way, due to [Newman's lemma](https://en.wikipedia.org/wiki/Newman%27s_lemma), the global system has to converge. Note, the convergence of critical pairs is a weaker condition than nonoverlapness, as there are examples of systems for which critical-pair convergence is possible, even though they overlap.

Now, consider a system that does not terminate. In that case, in addition to original system rules, we now have a set of new bidirectional rules, which we can think of as equivalence relations.

Next, imagine we evaluate a system in such an order that we always prioritize original system rules over the new rules. The system does not terminate, therefore we will never actually have to use the new rules. Hence, the behavior of the system will be exactly the same, however complex or multiway-looking.

With that said, however, due to Newman's lemma the system is globally confluent, i.e., there must exist a sequence of new rule applications that will bring it from any state (branch) of the original multiway system to any other state.

We can then think about these rules as completely separate. We have original rules that evolve the multiway system. However, we also have a set of equivalence relations between branches. That is different from any previously considered way of combining these branches, in particular, it is distinct from non-overlapping systems because the branches might diverge quite significantly.

Now, consider a president of a country making a decision to start a war based on the output of a quantum number generator. In this case, the entire human civilization will be in a superposition of the war happening and not. However, there will exist a sequence of equivalence rules applying which we can get from one state to another.

Further, it is curious to note that there is a notion of distance on this equivalence class, which we can define as the minimum number of applications of equivalence relations required to get from one state to another.

Perhaps, these equivalence sets are in fact quantum states, and the branches of the multiway system are classical states that, for example, one would integrate over in a path integral.

One potential issue is that by making the newly added rules anonymous, we will essentially make classical states completely define quantum states, which does not seem right. So, perhaps, we should instead make these new rules as specific as possible, by perhaps referring to specific vertices and edges.

## The Simplest Set Replace Rules [Homework]
The homework is a computational essay that enumerates [SetReplace](https://github.com/maxitg/SetReplace) systems with sizes up to 8.

### Build
To build the notebook:
1. Open the [./Homework/Drafts/ComputationalEssay.nb](Homework/Drafts/ComputationalEssay.nb).
2. Do Evaluation -> Evaluate Notebook, when asked to evaluate initialization cells, press "Yes" or "No", does not matter.
3. If you do not have [SetReplace](https://github.com/maxitg/SetReplace) installed, you will be asked to install it. Click "OK".
4. Wait for all cells to evaluate (that takes a while).
5. Save the evaluated notebook elsewhere, from now on, it is only necessary to evaluate initialization cells to view the notebook.

## Contributions
Nothing here yet.

## Wolfram Community Post
Nothing here yet.
