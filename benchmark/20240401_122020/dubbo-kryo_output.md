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
# Warmup Iteration   1: 1.825 ops/ms
Iteration   1: 7.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.349 ops/ms


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
# Warmup Iteration   1: 5.749 ops/ms
Iteration   1: 12.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.227 ops/ms


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
# Warmup Iteration   1: 5.907 ops/ms
Iteration   1: 12.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.848 ops/ms


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
# Warmup Iteration   1: 5.794 ops/ms
Iteration   1: 9.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.119 ops/ms


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
# Warmup Iteration   1: 3.757 ±(99.9%) 0.063 ms/op
Iteration   1: 2.038 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.038 ms/op


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
# Warmup Iteration   1: 3.111 ±(99.9%) 0.054 ms/op
Iteration   1: 1.970 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.970 ms/op


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
# Warmup Iteration   1: 3.302 ±(99.9%) 0.057 ms/op
Iteration   1: 2.115 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.115 ms/op


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
# Warmup Iteration   1: 4.029 ±(99.9%) 0.095 ms/op
Iteration   1: 3.434 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.434 ms/op


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
# Warmup Iteration   1: 3.419 ±(99.9%) 0.085 ms/op
Iteration   1: 2.227 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   2.042 ms/op
                 createUser·p0.90:   2.724 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   5.725 ms/op
                 createUser·p0.999:  15.604 ms/op
                 createUser·p0.9999: 16.315 ms/op
                 createUser·p1.00:   16.368 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14617
  mean =      2.227 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 12034 
    [ 2.500,  3.750) = 1991 
    [ 3.750,  5.000) = 205 
    [ 5.000,  6.250) = 155 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      2.042 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      5.725 ms/op
     p(99.9000) =     15.604 ms/op
     p(99.9900) =     16.315 ms/op
     p(99.9990) =     16.368 ms/op
     p(99.9999) =     16.368 ms/op
    p(100.0000) =     16.368 ms/op


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
# Warmup Iteration   1: 2.974 ±(99.9%) 0.088 ms/op
Iteration   1: 1.801 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.390 ms/op
                 existUser·p0.50:   1.698 ms/op
                 existUser·p0.90:   2.134 ms/op
                 existUser·p0.95:   2.310 ms/op
                 existUser·p0.99:   3.987 ms/op
                 existUser·p0.999:  12.976 ms/op
                 existUser·p0.9999: 13.140 ms/op
                 existUser·p1.00:   13.140 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18185
  mean =      1.801 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 674 
    [ 1.250,  2.500) = 16964 
    [ 2.500,  3.750) = 344 
    [ 3.750,  5.000) = 80 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.390 ms/op
     p(50.0000) =      1.698 ms/op
     p(90.0000) =      2.134 ms/op
     p(95.0000) =      2.310 ms/op
     p(99.0000) =      3.987 ms/op
     p(99.9000) =     12.976 ms/op
     p(99.9900) =     13.140 ms/op
     p(99.9990) =     13.140 ms/op
     p(99.9999) =     13.140 ms/op
    p(100.0000) =     13.140 ms/op


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
# Warmup Iteration   1: 3.261 ±(99.9%) 0.096 ms/op
Iteration   1: 2.028 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   1.964 ms/op
                 getUser·p0.90:   2.482 ms/op
                 getUser·p0.95:   2.679 ms/op
                 getUser·p0.99:   5.481 ms/op
                 getUser·p0.999:  11.485 ms/op
                 getUser·p0.9999: 12.810 ms/op
                 getUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15790
  mean =      2.028 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 435 
    [ 1.250,  2.500) = 13875 
    [ 2.500,  3.750) = 1205 
    [ 3.750,  5.000) = 85 
    [ 5.000,  6.250) = 114 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.482 ms/op
     p(95.0000) =      2.679 ms/op
     p(99.0000) =      5.481 ms/op
     p(99.9000) =     11.485 ms/op
     p(99.9900) =     12.810 ms/op
     p(99.9990) =     12.829 ms/op
     p(99.9999) =     12.829 ms/op
    p(100.0000) =     12.829 ms/op


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
# Warmup Iteration   1: 4.719 ±(99.9%) 0.131 ms/op
Iteration   1: 3.383 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   1.511 ms/op
                 listUser·p0.50:   3.351 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   5.719 ms/op
                 listUser·p0.999:  26.619 ms/op
                 listUser·p0.9999: 27.361 ms/op
                 listUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9297
  mean =      3.383 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1444 
    [ 2.500,  5.000) = 7548 
    [ 5.000,  7.500) = 293 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.511 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      5.719 ms/op
     p(99.9000) =     26.619 ms/op
     p(99.9900) =     27.361 ms/op
     p(99.9990) =     27.361 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.349          ops/ms
ClientSimple.existUser                       thrpt         12.227          ops/ms
ClientSimple.getUser                         thrpt         12.848          ops/ms
ClientSimple.listUser                        thrpt          9.119          ops/ms
ClientSimple.createUser                       avgt          2.038           ms/op
ClientSimple.existUser                        avgt          1.970           ms/op
ClientSimple.getUser                          avgt          2.115           ms/op
ClientSimple.listUser                         avgt          3.434           ms/op
ClientSimple.createUser                     sample  14617   2.227 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.962           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.042           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.724           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.178           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.725           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.604           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.315           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.368           ms/op
ClientSimple.existUser                      sample  18185   1.801 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.390           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.698           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.134           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.310           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.987           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.976           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.140           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.140           ms/op
ClientSimple.getUser                        sample  15790   2.028 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.693           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.964           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.482           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.679           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.481           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.485           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.810           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.829           ms/op
ClientSimple.listUser                       sample   9297   3.383 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.511           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.351           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.661           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.719           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.619           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.361           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.361           ms/op

Benchmark result is saved to 1711973747177.json
