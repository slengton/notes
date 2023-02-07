A [[Context Map|context map]] is in the overlay between project management and software design. The natural course of events is for the boundaries to follow the contours of team organisation ([[Conway's Law]]).

The [[Context Map|context map]] is a representation of the [[Bounded Context|bounded contexts]] within a domain. We map out the *existing* terrain. The names of the [[Bounded Context|bounded contexts]] form part of the [[Ubiquitious Language|ubiquitious language]] of the larger domain. We map out the relationships between [[Bounded Context|bounded contexts]] by describing the means of translation used between these [[Bounded Context|context]], as well as how sharing and communication are facilitated.

It is crucial that the [[Context Map|context map]] is shared and understood by everyone working with the domain.

There are a number of patterns to describe the relationships between [[Bounded Context|bounded contexts]]. These patterns may not perfectly fit the situation at hand, so use them as a guide and don't force it.

Patterns for the relationships between [[Bounded Context|bounded contexts]]:
* [[Shared Kernel]]
* [[Customer-Supplier]]
* [[Open Host Services]]
* [[Separate Ways]]
* ...

Once you have a coherent [[Context Map|context map]] you may want to make some changes to the organisation, team or design to affect a better design. Be cautious of repair leading into a wholesale reorganisation, rather follow an agile mindset of small changes and gather feedback. 