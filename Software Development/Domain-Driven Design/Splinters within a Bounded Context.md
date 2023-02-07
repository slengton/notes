Splinters can often be seen by inconsistencies in the interfaces in the code.
However, confusion of language is a an early warning sign that there are splinters in a [[Bounded Context]]. There are 2 types of problems that arise:
1. Duplicate concepts
	* Multiple models that represent the same concept
	* The models could even have different data and rules attached to it
2. False cognates
	* Using the same term (in both conversation and code) thinking they mean the same thing when they actually don't
	* This is more insidious than duplicate concepts