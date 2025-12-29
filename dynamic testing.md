#testing 

The program **is executed**.

- [[white-box testing]]
- [[black-box testing]]
- [[simulation]]
- [[prototyping]]


Often reveals [[failure]]s.

The resulting processes (from interpretation) are [[validation|validated]] against a document from the construction phases.

Procedures:
1. design tests
2. specify [[test case]]s
3. specify test process specification
	arrange test cases in executable order, taking pre- and post-conditions into account. This defines the order of tests and allows for automation.
4. text execution planning
	define the concrete order of execution, using criteria like regression testing, prioritization, and logical dependencies.

实践策略建议:

1. **首选黑盒测试**：先基于需求，利用**等价类划分**和**边界值分析**设计测试用例。
2. **测量覆盖率**：在执行黑盒用例时记录语句覆盖和判定覆盖。
3. **补充白盒用例**：针对未覆盖的代码部分，利用白盒技术补充用例。
	1. **判定覆盖**应作为最低标准。
	2. **循环**必须执行多次。
4. **因地制宜**：根据软件的批判性（Criticality）和结构复杂度选择合适的技术组合。
5. **避免单一策略**：采用不同的测试技术进行交叉验证，以防止遗漏特定的“雷区”。

**比喻**：如果把软件比作一座大楼，**黑盒测试**是检查电梯是否按键即达、水龙头是否有水（功能外观）；而**白盒测试**则是拆开墙板检查内部的电线布局是否合理、管道转弯处是否存在压力隐患（内部结构逻辑）。只有内外兼修，大楼才真正安全可靠。