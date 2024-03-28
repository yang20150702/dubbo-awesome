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
# Warmup Iteration   1: 1.759 ops/ms
Iteration   1: 6.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.843 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.176 ops/ms
Iteration   1: 12.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.805 ops/ms


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
# Warmup Iteration   1: 6.476 ops/ms
Iteration   1: 14.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.722 ops/ms


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
# Warmup Iteration   1: 5.720 ops/ms
Iteration   1: 9.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.110 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.845 ±(99.9%) 0.070 ms/op
Iteration   1: 2.357 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.357 ms/op


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
# Warmup Iteration   1: 2.863 ±(99.9%) 0.040 ms/op
Iteration   1: 1.960 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.960 ms/op


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
# Warmup Iteration   1: 3.256 ±(99.9%) 0.055 ms/op
Iteration   1: 2.396 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.396 ms/op


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
# Warmup Iteration   1: 4.227 ±(99.9%) 0.090 ms/op
Iteration   1: 3.368 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.368 ms/op


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
# Warmup Iteration   1: 3.420 ±(99.9%) 0.083 ms/op
Iteration   1: 2.073 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.560 ms/op
                 createUser·p0.50:   2.023 ms/op
                 createUser·p0.90:   2.429 ms/op
                 createUser·p0.95:   2.597 ms/op
                 createUser·p0.99:   3.267 ms/op
                 createUser·p0.999:  18.121 ms/op
                 createUser·p0.9999: 18.478 ms/op
                 createUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15427
  mean =      2.073 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 269 
    [ 1.250,  2.500) = 14050 
    [ 2.500,  3.750) = 994 
    [ 3.750,  5.000) = 38 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      2.023 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      3.267 ms/op
     p(99.9000) =     18.121 ms/op
     p(99.9900) =     18.478 ms/op
     p(99.9990) =     18.514 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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
# Warmup Iteration   1: 3.236 ±(99.9%) 0.082 ms/op
Iteration   1: 1.778 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   1.712 ms/op
                 existUser·p0.90:   2.224 ms/op
                 existUser·p0.95:   2.666 ms/op
                 existUser·p0.99:   3.196 ms/op
                 existUser·p0.999:  23.855 ms/op
                 existUser·p0.9999: 23.921 ms/op
                 existUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17976
  mean =      1.778 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16838 
    [ 2.500,  5.000) = 1072 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      1.712 ms/op
     p(90.0000) =      2.224 ms/op
     p(95.0000) =      2.666 ms/op
     p(99.0000) =      3.196 ms/op
     p(99.9000) =     23.855 ms/op
     p(99.9900) =     23.921 ms/op
     p(99.9990) =     23.921 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


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
# Warmup Iteration   1: 3.436 ±(99.9%) 0.082 ms/op
Iteration   1: 2.100 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.680 ms/op
                 getUser·p0.50:   2.070 ms/op
                 getUser·p0.90:   2.589 ms/op
                 getUser·p0.95:   2.744 ms/op
                 getUser·p0.99:   3.920 ms/op
                 getUser·p0.999:  16.061 ms/op
                 getUser·p0.9999: 16.417 ms/op
                 getUser·p1.00:   16.417 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15284
  mean =      2.100 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 259 
    [ 1.250,  2.500) = 12705 
    [ 2.500,  3.750) = 2134 
    [ 3.750,  5.000) = 116 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      2.070 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =     16.061 ms/op
     p(99.9900) =     16.417 ms/op
     p(99.9990) =     16.417 ms/op
     p(99.9999) =     16.417 ms/op
    p(100.0000) =     16.417 ms/op


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
# Warmup Iteration   1: 4.247 ±(99.9%) 0.123 ms/op
Iteration   1: 3.789 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   5.366 ms/op
                 listUser·p0.999:  7.666 ms/op
                 listUser·p0.9999: 8.372 ms/op
                 listUser·p1.00:   8.372 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8439
  mean =      3.789 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 16 
    [1.500, 2.000) = 119 
    [2.000, 2.500) = 370 
    [2.500, 3.000) = 1032 
    [3.000, 3.500) = 1368 
    [3.500, 4.000) = 1843 
    [4.000, 4.500) = 2244 
    [4.500, 5.000) = 1103 
    [5.000, 5.500) = 279 
    [5.500, 6.000) = 26 
    [6.000, 6.500) = 7 
    [6.500, 7.000) = 4 
    [7.000, 7.500) = 11 
    [7.500, 8.000) = 15 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =      7.666 ms/op
     p(99.9900) =      8.372 ms/op
     p(99.9990) =      8.372 ms/op
     p(99.9999) =      8.372 ms/op
    p(100.0000) =      8.372 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.843          ops/ms
ClientSimple.existUser                       thrpt         12.805          ops/ms
ClientSimple.getUser                         thrpt         14.722          ops/ms
ClientSimple.listUser                        thrpt          9.110          ops/ms
ClientSimple.createUser                       avgt          2.357           ms/op
ClientSimple.existUser                        avgt          1.960           ms/op
ClientSimple.getUser                          avgt          2.396           ms/op
ClientSimple.listUser                         avgt          3.368           ms/op
ClientSimple.createUser                     sample  15427   2.073 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.560           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.023           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.429           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.597           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.267           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.121           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.478           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.514           ms/op
ClientSimple.existUser                      sample  17976   1.778 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.602           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.712           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.224           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.666           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.196           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.855           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.921           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.921           ms/op
ClientSimple.getUser                        sample  15284   2.100 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.680           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.070           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.589           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.744           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.920           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.061           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.417           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.417           ms/op
ClientSimple.listUser                       sample   8439   3.789 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.130           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.875           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.702           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.915           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.366           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.666           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.372           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.372           ms/op

Benchmark result is saved to 1711649463760.json
