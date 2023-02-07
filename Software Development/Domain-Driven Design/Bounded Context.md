A [[Bounded Context]] delimits the applicability of a particular [[Model]] so that team members have a clear and shared understanding of what needs to be consistent and how it relates to other [[Bounded Context|bounded contexts]]. A [[Bounded Context|bounded context]] is very similar to a cell: a cell exists because its membranes determine what is in and out and what can pass. We set boundaries for the [[Bounded Context|contexts]] in which the [[Model|models]] reside. 

Within a [[Bounded Context|context]] we aim to be make it logically consisten without worrying about the applicablity outside the bounds of our [[Bounded Context|context]]. We define a [[Ubiquitious Language|ubiquotous language]] within the context so that w have no differences in language. The concepts and rules within the [[Bounded Context|context]] are consisent.
By focusing on a [[Bounded Context|context]] like this, we can ensure a pure model that is potent where it is applicable.

The boundaries of a [[Bounded Context|bounded context]] can be visible in a number of ways:
* Teams could be organised by these boundaries
* Services could be defined within these boundaries
* Code bases and schemas could be organise to adhere to these boundaries

Code re-use between [[Bounded Context|bounded contexts]] is a hazard to be avoided, thus translations between [[Bounded Context|bounded contexts]] become necessary.
