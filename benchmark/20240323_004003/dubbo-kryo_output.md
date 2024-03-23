# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.651 ops/ms
Iteration   1: 6.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.922 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.830 ops/ms
Iteration   1: 12.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.561 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.878 ops/ms
Iteration   1: 13.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.578 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.659 ops/ms
Iteration   1: 8.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.733 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.113 ±(99.9%) 0.080 ms/op
Iteration   1: 2.112 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.112 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.471 ±(99.9%) 0.051 ms/op
Iteration   1: 2.063 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.063 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.563 ±(99.9%) 0.073 ms/op
Iteration   1: 1.760 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.760 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.128 ±(99.9%) 0.140 ms/op
Iteration   1: 3.455 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.455 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.559 ±(99.9%) 0.113 ms/op
Iteration   1: 2.276 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   2.017 ms/op
                 createUser·p0.90:   2.712 ms/op
                 createUser·p0.95:   2.950 ms/op
                 createUser·p0.99:   11.004 ms/op
                 createUser·p0.999:  20.185 ms/op
                 createUser·p0.9999: 20.303 ms/op
                 createUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14037
  mean =      2.276 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10967 
    [ 2.500,  5.000) = 2804 
    [ 5.000,  7.500) = 105 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      2.017 ms/op
     p(90.0000) =      2.712 ms/op
     p(95.0000) =      2.950 ms/op
     p(99.0000) =     11.004 ms/op
     p(99.9000) =     20.185 ms/op
     p(99.9900) =     20.303 ms/op
     p(99.9990) =     20.316 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.080 ±(99.9%) 0.078 ms/op
Iteration   1: 1.863 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.351 ms/op
                 existUser·p0.50:   1.774 ms/op
                 existUser·p0.90:   2.408 ms/op
                 existUser·p0.95:   2.601 ms/op
                 existUser·p0.99:   3.733 ms/op
                 existUser·p0.999:  10.961 ms/op
                 existUser·p0.9999: 11.960 ms/op
                 existUser·p1.00:   11.960 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17166
  mean =      1.863 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 664 
    [ 1.250,  2.500) = 15269 
    [ 2.500,  3.750) = 1068 
    [ 3.750,  5.000) = 63 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.351 ms/op
     p(50.0000) =      1.774 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      3.733 ms/op
     p(99.9000) =     10.961 ms/op
     p(99.9900) =     11.960 ms/op
     p(99.9990) =     11.960 ms/op
     p(99.9999) =     11.960 ms/op
    p(100.0000) =     11.960 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.285 ±(99.9%) 0.089 ms/op
Iteration   1: 1.819 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.539 ms/op
                 getUser·p0.50:   1.657 ms/op
                 getUser·p0.90:   2.425 ms/op
                 getUser·p0.95:   2.741 ms/op
                 getUser·p0.99:   5.079 ms/op
                 getUser·p0.999:  15.539 ms/op
                 getUser·p0.9999: 15.700 ms/op
                 getUser·p1.00:   15.712 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17574
  mean =      1.819 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1498 
    [ 1.250,  2.500) = 14605 
    [ 2.500,  3.750) = 1132 
    [ 3.750,  5.000) = 148 
    [ 5.000,  6.250) = 122 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      1.657 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      2.741 ms/op
     p(99.0000) =      5.079 ms/op
     p(99.9000) =     15.539 ms/op
     p(99.9900) =     15.700 ms/op
     p(99.9990) =     15.712 ms/op
     p(99.9999) =     15.712 ms/op
    p(100.0000) =     15.712 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.326 ±(99.9%) 0.158 ms/op
Iteration   1: 3.757 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   7.700 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 19.268 ms/op
                 listUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8521
  mean =      3.757 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 336 
    [ 2.500,  3.750) = 3964 
    [ 3.750,  5.000) = 3775 
    [ 5.000,  6.250) = 229 
    [ 6.250,  7.500) = 117 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      7.700 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     19.268 ms/op
     p(99.9990) =     19.268 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.922          ops/ms
ClientSimple.existUser                       thrpt         12.561          ops/ms
ClientSimple.getUser                         thrpt         13.578          ops/ms
ClientSimple.listUser                        thrpt          8.733          ops/ms
ClientSimple.createUser                       avgt          2.112           ms/op
ClientSimple.existUser                        avgt          2.063           ms/op
ClientSimple.getUser                          avgt          1.760           ms/op
ClientSimple.listUser                         avgt          3.455           ms/op
ClientSimple.createUser                     sample  14037   2.276 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.686           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.017           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.712           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.950           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.004           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.185           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.303           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.316           ms/op
ClientSimple.existUser                      sample  17166   1.863 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.351           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.774           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.408           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.601           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.733           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.961           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.960           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.960           ms/op
ClientSimple.getUser                        sample  17574   1.819 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.539           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.657           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.425           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.741           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.079           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.539           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.700           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.712           ms/op
ClientSimple.listUser                       sample   8521   3.757 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.071           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.744           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.481           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.063           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.700           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.236           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.268           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.268           ms/op

Benchmark result is saved to 1711154147943.json
