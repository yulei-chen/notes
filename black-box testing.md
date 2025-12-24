#testing 

| **Input Derivation**    | Derived _without_ knowledge about internal program logic.                                                                                            |
| :---------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Design Approach**     | Specification-based/Specification-oriented.                                                                                                          |
| **Focus**               | ==Functionality==, models, and requirements.                                                                                                         |
| **Control/Observation** | Execution is controlled externally via input values ([[Point of Control]] - PoC). Behavior is monitored externally ([[Point of Observation]] - PoO). |
Specification-Based Black-Box Testing Techniques:
- [[equivalence class]]es
- [[boundary value analysis]]
- [[decision table testing]]
- use case testing
- cause effect graphs
- classification tree
- syntax testing


Assessment of Black-Box Testing:

Black-box testing methods are founded on the system's requirements and specifications. Consequently:

- They ==cannot== detect missing or incorrect requirements or specifications.
- Detection of non-specified functionality (additional, non-required functions) is likely only found by coincidence.
- Black-box techniques are prioritized because they focus on the functionality of the test object, which is paramount for the final product.