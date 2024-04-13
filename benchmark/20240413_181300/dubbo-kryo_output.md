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
# Warmup Iteration   1: 1.521 ops/ms
Iteration   1: 6.332 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.332 ops/ms


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
# Warmup Iteration   1: 5.013 ops/ms
Iteration   1: 10.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.284 ops/ms


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
# Warmup Iteration   1: 5.003 ops/ms
Iteration   1: 13.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.017 ops/ms


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
# Warmup Iteration   1: 4.566 ops/ms
Iteration   1: 8.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.745 ops/ms


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
# Warmup Iteration   1: 4.383 ±(99.9%) 0.085 ms/op
Iteration   1: 2.249 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.249 ms/op


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
# Warmup Iteration   1: 3.279 ±(99.9%) 0.049 ms/op
Iteration   1: 1.924 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.924 ms/op


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
# Warmup Iteration   1: 3.369 ±(99.9%) 0.060 ms/op
Iteration   1: 2.173 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.173 ms/op


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
# Warmup Iteration   1: 4.616 ±(99.9%) 0.087 ms/op
Iteration   1: 3.435 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.435 ms/op


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
# Warmup Iteration   1: 3.563 ±(99.9%) 0.096 ms/op
Iteration   1: 2.238 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   0.615 ms/op
                 createUser·p0.50:   2.040 ms/op
                 createUser·p0.90:   2.630 ms/op
                 createUser·p0.95:   2.834 ms/op
                 createUser·p0.99:   5.709 ms/op
                 createUser·p0.999:  34.435 ms/op
                 createUser·p0.9999: 34.809 ms/op
                 createUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14282
  mean =      2.238 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11687 
    [ 2.500,  5.000) = 2391 
    [ 5.000,  7.500) = 107 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      2.040 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      5.709 ms/op
     p(99.9000) =     34.435 ms/op
     p(99.9900) =     34.809 ms/op
     p(99.9990) =     34.865 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


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
# Warmup Iteration   1: 2.933 ±(99.9%) 0.073 ms/op
Iteration   1: 1.834 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.588 ms/op
                 existUser·p0.50:   1.630 ms/op
                 existUser·p0.90:   2.720 ms/op
                 existUser·p0.95:   2.998 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  10.322 ms/op
                 existUser·p0.9999: 12.477 ms/op
                 existUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17496
  mean =      1.834 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 375 
    [ 1.250,  2.500) = 14964 
    [ 2.500,  3.750) = 2103 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      1.630 ms/op
     p(90.0000) =      2.720 ms/op
     p(95.0000) =      2.998 ms/op
     p(99.0000) =      3.465 ms/op
     p(99.9000) =     10.322 ms/op
     p(99.9900) =     12.477 ms/op
     p(99.9990) =     12.845 ms/op
     p(99.9999) =     12.845 ms/op
    p(100.0000) =     12.845 ms/op


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
# Warmup Iteration   1: 3.836 ±(99.9%) 0.122 ms/op
Iteration   1: 2.253 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.528 ms/op
                 getUser·p0.50:   2.204 ms/op
                 getUser·p0.90:   2.785 ms/op
                 getUser·p0.95:   2.994 ms/op
                 getUser·p0.99:   3.779 ms/op
                 getUser·p0.999:  11.318 ms/op
                 getUser·p0.9999: 12.692 ms/op
                 getUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14190
  mean =      2.253 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 202 
    [ 1.250,  2.500) = 10195 
    [ 2.500,  3.750) = 3647 
    [ 3.750,  5.000) = 58 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      2.204 ms/op
     p(90.0000) =      2.785 ms/op
     p(95.0000) =      2.994 ms/op
     p(99.0000) =      3.779 ms/op
     p(99.9000) =     11.318 ms/op
     p(99.9900) =     12.692 ms/op
     p(99.9990) =     12.747 ms/op
     p(99.9999) =     12.747 ms/op
    p(100.0000) =     12.747 ms/op


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
# Warmup Iteration   1: 4.479 ±(99.9%) 0.137 ms/op
Iteration   1: 3.464 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   3.310 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.705 ms/op
                 listUser·p0.999:  16.167 ms/op
                 listUser·p0.9999: 19.137 ms/op
                 listUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9219
  mean =      3.464 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 911 
    [ 2.500,  3.750) = 5868 
    [ 3.750,  5.000) = 2083 
    [ 5.000,  6.250) = 208 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.395 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      7.705 ms/op
     p(99.9000) =     16.167 ms/op
     p(99.9900) =     19.137 ms/op
     p(99.9990) =     19.137 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.332          ops/ms
ClientSimple.existUser                       thrpt         10.284          ops/ms
ClientSimple.getUser                         thrpt         13.017          ops/ms
ClientSimple.listUser                        thrpt          8.745          ops/ms
ClientSimple.createUser                       avgt          2.249           ms/op
ClientSimple.existUser                        avgt          1.924           ms/op
ClientSimple.getUser                          avgt          2.173           ms/op
ClientSimple.listUser                         avgt          3.435           ms/op
ClientSimple.createUser                     sample  14282   2.238 ± 0.052   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.615           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.040           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.630           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.834           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.709           ms/op
ClientSimple.createUser:createUser·p0.999   sample         34.435           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         34.809           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.865           ms/op
ClientSimple.existUser                      sample  17496   1.834 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.588           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.630           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.720           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.998           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.465           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.322           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.477           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.845           ms/op
ClientSimple.getUser                        sample  14190   2.253 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.528           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.204           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.785           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.994           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.779           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.318           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.692           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.747           ms/op
ClientSimple.listUser                       sample   9219   3.464 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.395           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.310           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.174           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.612           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.705           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.167           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.137           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.137           ms/op

Benchmark result is saved to 1713031738927.json
