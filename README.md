# Modeling and Simulation of Social Systems Fall 2018


> * Group Name: obiglobis
> * Group participants names: Alexander Bruun, Anton Bruun
> * Project Title: Two Predators and Two Prey Interactions
> * Programming language: Python

## General Introduction

In natural sciences cellular automaton plays an important role. It is a very powerful tool to describe highly complex and nonlinear system with a simple set of rules. It is used in a broad spectrum of topics which vary from computer sciences, mathematics, physics, biology to chemistry. The basics of cellular automaton is that a state is changed based on inputs (mostly neighbors) and its previous state.
A broad spectrum of simulations can be made with the cellular automaton. A very popular, yet very simple application is Conway’s Game of Life. It is a two-dimensional simulation in which a cell is either alive or dead.
To our knowledge there exist only few simulations that are researching the behavior of a two-predator and two-prey environment. This calls for an actual simulation between two predators and two preys.

## The Model

The parameters we are observing are:

- global `offspring_chance_table`, `values_offspring`, `eat_values`
- global `death_values`
- global `cost_reproduction`, `cost_movement` 
- global `rules`
- global `nutrition_level_start`, `nutrition_value_each_turn`

Our model captures the key interactions between large populations and these key interactions can be changed easily through parameter.
While capturing key interactions they are still not all interactions. One of them is the sense of packs. This can have a strong influence in decrease of a popula-tion since it will be more resistant in most cases to attacks or extinction. The other is a sense for attack and defense so the predators wills not take a decreasing population into account. 


## Fundamental Questions

Will we either get:
- pattern stabilizations into homogeneity?
- patterns stabilizing or oscillating?
- chaotic pattern evolution?
- highly complex structures with local stabilities?

How will parameters like food preferences, reproduction or death probability influence population dynamics? Are our results in any way representable by governing population equations or the real world?

## Expected Results

We expect oscillations, overpopulations, extinctions and some sort of gliders.

## References 

[1]	https://en.wikipedia.org/wiki/Cellular_automaton, 09.12.2018.
[2]	Hiroki Sayama, Introduction to the Modeling and Analysis of Complex Systems.
 	Pages 185-225, August 2015.
[3]	https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life, 09.12.2018.
[4]	https://en.wikipedia.org/wiki/Wa-Tor, 09.12.2018.
[5]	Gabriela Kirlinger, Two predators feeding on two prey species: A result on
 	permanence, September 1989.
[6]	Vahidin Hadžiabdić, Midhat Mehuljić and Jasmin Bektešević, Lotka-Volterra
 	Model with Two Predators and Their Prey, February 2017.
[7]	https://en.wikipedia.org/wiki/Wa-Tor, 09.12.2018.
[8]	Patrick Misteli & Ruben Kälin, Circle Of Life, May 2014.
[9]	https://en.wikipedia.org/wiki/Lotka–Volterra_equations, 09.12.2018.
[10]	https://en.wikipedia.org/wiki/Generalized_Lotka–Volterra_equation, 09.12.2018.

## Research Methods

Cellular Automata

# Reproducibility
### All the informations can be found under:

https://github.com/parisj/project_survival/tree/master/code/Reproducibility%20Guide

