## Information Theory

* Invented by Claude Shannon

![shannon](shannon.gif)

* Information theory: Shannon discovered these formulas about information transmission. Such as how many bits per second should be able to transfer over various media. Coined the term "bit".

* Laid ground work to switch from analog to digital communication. The Bell phone systems' analog communications were degraded when sent over long distances and noise was amplified by repeaters. By switching to digital, Bell implemented a type of digital repeater that reduced degradation of signal, reducing loss, and improving communication. 

* Shannon Capacity: the fundamental limit of information that can be sent across a medium

* Shannon entropy or level of surprise in a message/communication

## Shannon works

* A symbolic analysis of relay and switching circuits (https://dspace.mit.edu/handle/1721.1/11173)
* Communication Theory of Secrecy Systems (https://web.archive.org/web/20070605092733/http://netlab.cs.ucla.edu/wiki/files/shannon1949.pdf)
* The Mathematical Theory of Communication (https://people.math.harvard.edu/~ctm/home/text/others/shannon/entropy/entropy.pdf)

## Some concepts

* Self-Information

* Entropy

* Mutual Information

* Conditional Entropy

* Kullback-Leibler Divergence

* Binary Cross Entropy

* Multiclass Cross Entropy

## Logarithm

* The bit lenght of the number N is: n = log2 N
* By the basic definition of logarithms this is equivalent as such: N = 2**n
* 

## Models

* Hopfield
* Boltzman Machines

## Entropy

* Entropy is the measure of uncertainty, or disorder in a system.
* You can think of Entropy as the amount of surprise found from a process.
* The higher the entropy, the less the certainty you have in the result
* For a distribution of probabilities (p1, p2, ..., pN), the entropy is:
* = p1 * log(p1) -p2 * log(p2) ... -pN * log(pN)
* Here log is the "binary logarithm"
* Entropy of a coin toss .......(1/2, 1/2) -> -(1/2) * log(1/2) - (1/2) * log(1/2) = 1/2 + 1/2 = 1 bit
* Entropy of a biased coin toss (3/4, 1/4) -> -(3/4) * log(3/4) - (1/4) * log(1/4) = 0.81 bits
* 
