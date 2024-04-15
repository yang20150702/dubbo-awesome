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
# Warmup Iteration   1: 1.589 ops/ms
Iteration   1: 6.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.968 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.601 ops/ms
Iteration   1: 13.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.356 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.374 ops/ms
Iteration   1: 14.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.741 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.433 ops/ms
Iteration   1: 8.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.780 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.644 ±(99.9%) 0.070 ms/op
Iteration   1: 2.184 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.184 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.992 ±(99.9%) 0.040 ms/op
Iteration   1: 1.934 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.934 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.102 ±(99.9%) 0.051 ms/op
Iteration   1: 1.770 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.770 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.043 ±(99.9%) 0.126 ms/op
Iteration   1: 3.242 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.242 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.545 ±(99.9%) 0.089 ms/op
Iteration   1: 2.511 ±(99.9%) 0.068 ms/op
                 createUser·p0.00:   0.427 ms/op
                 createUser·p0.50:   2.232 ms/op
                 createUser·p0.90:   2.925 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   12.452 ms/op
                 createUser·p0.999:  29.950 ms/op
                 createUser·p0.9999: 30.137 ms/op
                 createUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12806
  mean =      2.511 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9125 
    [ 2.500,  5.000) = 3452 
    [ 5.000,  7.500) = 25 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.427 ms/op
     p(50.0000) =      2.232 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =     12.452 ms/op
     p(99.9000) =     29.950 ms/op
     p(99.9900) =     30.137 ms/op
     p(99.9990) =     30.147 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.032 ±(99.9%) 0.082 ms/op
Iteration   1: 1.915 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.380 ms/op
                 existUser·p0.50:   1.782 ms/op
                 existUser·p0.90:   2.535 ms/op
                 existUser·p0.95:   2.777 ms/op
                 existUser·p0.99:   4.740 ms/op
                 existUser·p0.999:  11.190 ms/op
                 existUser·p0.9999: 11.771 ms/op
                 existUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16735
  mean =      1.915 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 313 
    [ 1.250,  2.500) = 14557 
    [ 2.500,  3.750) = 1644 
    [ 3.750,  5.000) = 95 
    [ 5.000,  6.250) = 90 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.380 ms/op
     p(50.0000) =      1.782 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      4.740 ms/op
     p(99.9000) =     11.190 ms/op
     p(99.9900) =     11.771 ms/op
     p(99.9990) =     12.157 ms/op
     p(99.9999) =     12.157 ms/op
    p(100.0000) =     12.157 ms/op


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
# Warmup Iteration   1: 3.670 ±(99.9%) 0.082 ms/op
Iteration   1: 2.086 ±(99.9%) 0.037 ms/op
                 getUser·p0.00:   0.578 ms/op
                 getUser·p0.50:   2.017 ms/op
                 getUser·p0.90:   2.630 ms/op
                 getUser·p0.95:   2.950 ms/op
                 getUser·p0.99:   4.307 ms/op
                 getUser·p0.999:  27.472 ms/op
                 getUser·p0.9999: 28.109 ms/op
                 getUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15313
  mean =      2.086 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13124 
    [ 2.500,  5.000) = 2067 
    [ 5.000,  7.500) = 26 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      2.017 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.950 ms/op
     p(99.0000) =      4.307 ms/op
     p(99.9000) =     27.472 ms/op
     p(99.9900) =     28.109 ms/op
     p(99.9990) =     28.213 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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
# Warmup Iteration   1: 4.538 ±(99.9%) 0.157 ms/op
Iteration   1: 3.134 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.041 ms/op
                 listUser·p0.50:   2.834 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.120 ms/op
                 listUser·p0.999:  6.790 ms/op
                 listUser·p0.9999: 6.971 ms/op
                 listUser·p1.00:   6.971 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10194
  mean =      3.134 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 7 
    [1.500, 2.000) = 42 
    [2.000, 2.500) = 1022 
    [2.500, 3.000) = 4727 
    [3.000, 3.500) = 1371 
    [3.500, 4.000) = 1881 
    [4.000, 4.500) = 765 
    [4.500, 5.000) = 262 
    [5.000, 5.500) = 42 
    [5.500, 6.000) = 41 
    [6.000, 6.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.041 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.120 ms/op
     p(99.9000) =      6.790 ms/op
     p(99.9900) =      6.971 ms/op
     p(99.9990) =      6.971 ms/op
     p(99.9999) =      6.971 ms/op
    p(100.0000) =      6.971 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.968          ops/ms
ClientSimple.existUser                       thrpt         13.356          ops/ms
ClientSimple.getUser                         thrpt         14.741          ops/ms
ClientSimple.listUser                        thrpt          8.780          ops/ms
ClientSimple.createUser                       avgt          2.184           ms/op
ClientSimple.existUser                        avgt          1.934           ms/op
ClientSimple.getUser                          avgt          1.770           ms/op
ClientSimple.listUser                         avgt          3.242           ms/op
ClientSimple.createUser                     sample  12806   2.511 ± 0.068   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.427           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.232           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.925           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.178           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.452           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.950           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.137           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.147           ms/op
ClientSimple.existUser                      sample  16735   1.915 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.380           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.782           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.535           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.777           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.740           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.190           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.771           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.157           ms/op
ClientSimple.getUser                        sample  15313   2.086 ± 0.037   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.578           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.017           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.630           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.950           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.307           ms/op
ClientSimple.getUser:getUser·p0.999         sample         27.472           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         28.109           ms/op
ClientSimple.getUser:getUser·p1.00          sample         28.213           ms/op
ClientSimple.listUser                       sample  10194   3.134 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.041           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.834           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.043           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.120           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.790           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.971           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.971           ms/op

Benchmark result is saved to 1713183434175.json
