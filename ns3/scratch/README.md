scratch 目录

## Tutorial 例子
 以 my[first|second|third等].cc 为命名格式
 * 

## manual 例子
 以 mn[0-9]-<orignal-source>.cc 为命名格式
 其中 mn 为 manual 缩写 [0-9] 为章节小标题, 例如 mn072 即 1.07.2 章小结. 因为手册都在第一大章中，所以 1 忽略了。
 
* 01 Organization 3
* 02 RandomVariables 4
* 03 HashFunctions 9
* 04 EventsandSimulator 11
* 05 Callbacks 13
   - 设置与获取对象属性 `./waf --run mn172-main-attribute-value`, copy from "src/point-to-point/examples/main-attribute-value.cc"
* 06 Objectmodel 22
* 07 ConfigurationandAttributes 26
   - 使用 Callback 函数 `./waf --run scratch/mn153-main-callback`
* 08 Objectnames 43
* 09 Logging 43
* 10 Tracing 48
  - 使用 tracing `./waf --run scratch/mn103-tcp-large-transfer`
* 11 DataCollection 64
  - 11.2 Helper: `src/stats/examples/gnuplot-helper-example.cc`
* 12 StatisticalFramework 89
* 13 RealTime 97
* 14 Helpers 99
* 15 MakingPlotsusingtheGnuplotClass 99
* 16 UsingPythontoRunns-3 107
* 17 Tests 112
* 18 Support 128

  
 
 