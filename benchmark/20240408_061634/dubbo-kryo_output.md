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
# Warmup Iteration   1: 1.696 ops/ms
Iteration   1: 6.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.890 ops/ms


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
# Warmup Iteration   1: 6.573 ops/ms
Iteration   1: 11.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.095 ops/ms


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
# Warmup Iteration   1: 5.413 ops/ms
Iteration   1: 13.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.757 ops/ms


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
# Warmup Iteration   1: 6.053 ops/ms
Iteration   1: 8.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.100 ops/ms


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
# Warmup Iteration   1: 3.751 ±(99.9%) 0.066 ms/op
Iteration   1: 2.226 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.226 ms/op


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
# Warmup Iteration   1: 3.694 ±(99.9%) 0.058 ms/op
Iteration   1: 1.948 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.948 ms/op


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
# Warmup Iteration   1: 3.090 ±(99.9%) 0.058 ms/op
Iteration   1: 1.897 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.897 ms/op


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
# Warmup Iteration   1: 4.342 ±(99.9%) 0.083 ms/op
Iteration   1: 3.964 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.964 ms/op


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
# Warmup Iteration   1: 3.259 ±(99.9%) 0.080 ms/op
Iteration   1: 1.938 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.588 ms/op
                 createUser·p0.50:   1.794 ms/op
                 createUser·p0.90:   2.138 ms/op
                 createUser·p0.95:   2.363 ms/op
                 createUser·p0.99:   5.433 ms/op
                 createUser·p0.999:  23.656 ms/op
                 createUser·p0.9999: 28.312 ms/op
                 createUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16491
  mean =      1.938 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15888 
    [ 2.500,  5.000) = 423 
    [ 5.000,  7.500) = 36 
    [ 7.500, 10.000) = 44 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      1.794 ms/op
     p(90.0000) =      2.138 ms/op
     p(95.0000) =      2.363 ms/op
     p(99.0000) =      5.433 ms/op
     p(99.9000) =     23.656 ms/op
     p(99.9900) =     28.312 ms/op
     p(99.9990) =     28.312 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


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
# Warmup Iteration   1: 3.229 ±(99.9%) 0.105 ms/op
Iteration   1: 1.870 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.635 ms/op
                 existUser·p0.50:   1.767 ms/op
                 existUser·p0.90:   2.408 ms/op
                 existUser·p0.95:   2.540 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  10.091 ms/op
                 existUser·p0.9999: 10.397 ms/op
                 existUser·p1.00:   10.420 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17115
  mean =      1.870 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 68 
    [ 1.000,  2.000) = 11487 
    [ 2.000,  3.000) = 5327 
    [ 3.000,  4.000) = 95 
    [ 4.000,  5.000) = 38 
    [ 5.000,  6.000) = 61 
    [ 6.000,  7.000) = 4 
    [ 7.000,  8.000) = 1 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      1.767 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.540 ms/op
     p(99.0000) =      3.592 ms/op
     p(99.9000) =     10.091 ms/op
     p(99.9900) =     10.397 ms/op
     p(99.9990) =     10.420 ms/op
     p(99.9999) =     10.420 ms/op
    p(100.0000) =     10.420 ms/op


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
# Warmup Iteration   1: 3.192 ±(99.9%) 0.080 ms/op
Iteration   1: 2.095 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.400 ms/op
                 getUser·p0.50:   2.060 ms/op
                 getUser·p0.90:   2.535 ms/op
                 getUser·p0.95:   2.746 ms/op
                 getUser·p0.99:   3.877 ms/op
                 getUser·p0.999:  17.391 ms/op
                 getUser·p0.9999: 18.266 ms/op
                 getUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15253
  mean =      2.095 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 455 
    [ 1.250,  2.500) = 12920 
    [ 2.500,  3.750) = 1688 
    [ 3.750,  5.000) = 116 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.400 ms/op
     p(50.0000) =      2.060 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.746 ms/op
     p(99.0000) =      3.877 ms/op
     p(99.9000) =     17.391 ms/op
     p(99.9900) =     18.266 ms/op
     p(99.9990) =     18.317 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 4.457 ±(99.9%) 0.149 ms/op
Iteration   1: 3.284 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   5.857 ms/op
                 listUser·p0.999:  6.629 ms/op
                 listUser·p0.9999: 6.980 ms/op
                 listUser·p1.00:   6.980 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9748
  mean =      3.284 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 16 
    [1.500, 2.000) = 75 
    [2.000, 2.500) = 637 
    [2.500, 3.000) = 4063 
    [3.000, 3.500) = 1859 
    [3.500, 4.000) = 1438 
    [4.000, 4.500) = 1053 
    [4.500, 5.000) = 255 
    [5.000, 5.500) = 133 
    [5.500, 6.000) = 165 
    [6.000, 6.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =      6.629 ms/op
     p(99.9900) =      6.980 ms/op
     p(99.9990) =      6.980 ms/op
     p(99.9999) =      6.980 ms/op
    p(100.0000) =      6.980 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.890          ops/ms
ClientSimple.existUser                       thrpt         11.095          ops/ms
ClientSimple.getUser                         thrpt         13.757          ops/ms
ClientSimple.listUser                        thrpt          8.100          ops/ms
ClientSimple.createUser                       avgt          2.226           ms/op
ClientSimple.existUser                        avgt          1.948           ms/op
ClientSimple.getUser                          avgt          1.897           ms/op
ClientSimple.listUser                         avgt          3.964           ms/op
ClientSimple.createUser                     sample  16491   1.938 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.588           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.794           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.138           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.363           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.433           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.656           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.312           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.312           ms/op
ClientSimple.existUser                      sample  17115   1.870 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.635           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.767           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.408           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.540           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.592           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.091           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.397           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.420           ms/op
ClientSimple.getUser                        sample  15253   2.095 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.400           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.060           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.535           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.746           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.877           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.391           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.266           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.317           ms/op
ClientSimple.listUser                       sample   9748   3.284 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.145           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.011           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.727           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.857           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.629           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.980           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.980           ms/op

Benchmark result is saved to 1712556720522.json
