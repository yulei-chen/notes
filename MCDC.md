#testing 

> Modified Condition/Decision Coverage (MC/DC)

MC/DC is similar to [[condition determination coverage]], but it requires for each [[atomic condition]] to show only one case where the atomic condition influences the overall decision.

For example, in condition determination coverage, it should be

![[Screenshot 2025-12-24 at 03.14.37.png]]

but in MC/DC, you can remove some of them to make sure there is just one change from 0 to 1 in each row (for each atomic condition).

![[Pasted image 20251224031542.png]]
