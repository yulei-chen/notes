#testing 

手动插桩：
```ts
if (x > 0) {
    counterTrue++;   // 记录 true 分支执行
    A();
} else {
    counterFalse++;  // 记录 false 分支执行
    B();
}
```

白盒测试要求验证程序内部是否被执行，因此必须通过插桩记录执行情况，而这在大规模程序中只能依靠工具自动 (e.g, [[istanbul]])完成。