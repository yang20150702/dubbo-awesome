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
# Warmup Iteration   1: 1.270 ops/ms
Iteration   1: 6.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.570 ops/ms


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
# Warmup Iteration   1: 6.318 ops/ms
Iteration   1: 13.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.071 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.471 ops/ms
Iteration   1: 14.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.120 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.248 ops/ms
Iteration   1: 8.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.421 ops/ms


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
# Warmup Iteration   1: 3.477 ±(99.9%) 0.065 ms/op
Iteration   1: 2.194 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.194 ms/op


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
# Warmup Iteration   1: 2.983 ±(99.9%) 0.044 ms/op
Iteration   1: 1.906 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.906 ms/op


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
# Warmup Iteration   1: 3.267 ±(99.9%) 0.051 ms/op
Iteration   1: 2.163 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.163 ms/op


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
# Warmup Iteration   1: 4.346 ±(99.9%) 0.076 ms/op
Iteration   1: 3.187 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.187 ms/op


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
# Warmup Iteration   1: 3.669 ±(99.9%) 0.118 ms/op
Iteration   1: 2.094 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.414 ms/op
                 createUser·p0.50:   1.861 ms/op
                 createUser·p0.90:   2.646 ms/op
                 createUser·p0.95:   2.821 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  23.580 ms/op
                 createUser·p0.9999: 27.737 ms/op
                 createUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15266
  mean =      2.094 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12849 
    [ 2.500,  5.000) = 2245 
    [ 5.000,  7.500) = 43 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.414 ms/op
     p(50.0000) =      1.861 ms/op
     p(90.0000) =      2.646 ms/op
     p(95.0000) =      2.821 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     23.580 ms/op
     p(99.9900) =     27.737 ms/op
     p(99.9990) =     27.754 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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
# Warmup Iteration   1: 3.098 ±(99.9%) 0.076 ms/op
Iteration   1: 1.806 ±(99.9%) 0.036 ms/op
                 existUser·p0.00:   0.511 ms/op
                 existUser·p0.50:   1.604 ms/op
                 existUser·p0.90:   2.265 ms/op
                 existUser·p0.95:   2.544 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  30.966 ms/op
                 existUser·p0.9999: 31.765 ms/op
                 existUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17697
  mean =      1.806 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16676 
    [ 2.500,  5.000) = 843 
    [ 5.000,  7.500) = 78 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      1.604 ms/op
     p(90.0000) =      2.265 ms/op
     p(95.0000) =      2.544 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     30.966 ms/op
     p(99.9900) =     31.765 ms/op
     p(99.9990) =     31.916 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


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
# Warmup Iteration   1: 3.531 ±(99.9%) 0.082 ms/op
Iteration   1: 2.014 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.500 ms/op
                 getUser·p0.50:   1.815 ms/op
                 getUser·p0.90:   2.626 ms/op
                 getUser·p0.95:   2.863 ms/op
                 getUser·p0.99:   5.124 ms/op
                 getUser·p0.999:  11.731 ms/op
                 getUser·p0.9999: 14.744 ms/op
                 getUser·p1.00:   14.811 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15875
  mean =      2.014 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 449 
    [ 1.250,  2.500) = 12843 
    [ 2.500,  3.750) = 2343 
    [ 3.750,  5.000) = 80 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      1.815 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.863 ms/op
     p(99.0000) =      5.124 ms/op
     p(99.9000) =     11.731 ms/op
     p(99.9900) =     14.744 ms/op
     p(99.9990) =     14.811 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


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
# Warmup Iteration   1: 5.974 ±(99.9%) 0.146 ms/op
Iteration   1: 3.774 ±(99.9%) 0.073 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.140 ms/op
                 listUser·p0.99:   12.829 ms/op
                 listUser·p0.999:  30.736 ms/op
                 listUser·p0.9999: 31.359 ms/op
                 listUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8469
  mean =      3.774 ±(99.9%) 0.073 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 634 
    [ 2.500,  5.000) = 7362 
    [ 5.000,  7.500) = 306 
    [ 7.500, 10.000) = 70 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.140 ms/op
     p(99.0000) =     12.829 ms/op
     p(99.9000) =     30.736 ms/op
     p(99.9900) =     31.359 ms/op
     p(99.9990) =     31.359 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.570          ops/ms
ClientSimple.existUser                       thrpt         13.071          ops/ms
ClientSimple.getUser                         thrpt         14.120          ops/ms
ClientSimple.listUser                        thrpt          8.421          ops/ms
ClientSimple.createUser                       avgt          2.194           ms/op
ClientSimple.existUser                        avgt          1.906           ms/op
ClientSimple.getUser                          avgt          2.163           ms/op
ClientSimple.listUser                         avgt          3.187           ms/op
ClientSimple.createUser                     sample  15266   2.094 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.414           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.861           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.646           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.821           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.103           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.580           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.737           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.754           ms/op
ClientSimple.existUser                      sample  17697   1.806 ± 0.036   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.511           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.604           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.265           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.544           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.579           ms/op
ClientSimple.existUser:existUser·p0.999     sample         30.966           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         31.765           ms/op
ClientSimple.existUser:existUser·p1.00      sample         31.916           ms/op
ClientSimple.getUser                        sample  15875   2.014 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.500           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.815           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.626           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.863           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.124           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.731           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.744           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.811           ms/op
ClientSimple.listUser                       sample   8469   3.774 ± 0.073   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.916           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.604           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.563           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.140           ms/op
ClientSimple.listUser:listUser·p0.99        sample         12.829           ms/op
ClientSimple.listUser:listUser·p0.999       sample         30.736           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         31.359           ms/op
ClientSimple.listUser:listUser·p1.00        sample         31.359           ms/op

Benchmark result is saved to 1712383856830.json
