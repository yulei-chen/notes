#se 

Factory provides means to create domain concept
- that hides complexity of object construction
	- creation of [[aggregate|aggregates]] / [[entity|entities]] / [[value object]]s in atomic operation
	- ensures that products’ invariant holds
- that separates construction concern
	- extracted into separate domain concept
	- only factory depends on aggregate’s internal elements