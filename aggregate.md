#se 

Aggregate clusters related [[entity|entities]] and [[value object|value objects]]
- defines ==boundaries== around specific ==root entities==
	- root entity serves as Façade to access enclosed elements
	- identity of aggregate derived from root entity
	- removal of root removes complete aggregate
- ensures invariants and concurrent access
	- prohibit references to elements other than its root
	- changes to aggregate only through root ensuring invariants
	- constructed as a whole satisfying invariants
	- locking strategy decided for whole aggregate