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
# Warmup Iteration   1: 1.938 ops/ms
Iteration   1: 6.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.671 ops/ms


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
# Warmup Iteration   1: 6.853 ops/ms
Iteration   1: 13.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.281 ops/ms


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
# Warmup Iteration   1: 5.968 ops/ms
Iteration   1: 14.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.243 ops/ms


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
# Warmup Iteration   1: 5.572 ops/ms
Iteration   1: 8.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.456 ops/ms


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
# Warmup Iteration   1: 3.482 ±(99.9%) 0.057 ms/op
Iteration   1: 1.952 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.952 ms/op


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
# Warmup Iteration   1: 3.010 ±(99.9%) 0.049 ms/op
Iteration   1: 1.707 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.707 ms/op


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
# Warmup Iteration   1: 3.260 ±(99.9%) 0.054 ms/op
Iteration   1: 2.136 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.136 ms/op


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
# Warmup Iteration   1: 4.560 ±(99.9%) 0.073 ms/op
Iteration   1: 3.650 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.650 ms/op


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
# Warmup Iteration   1: 3.721 ±(99.9%) 0.105 ms/op
Iteration   1: 2.139 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.563 ms/op
                 createUser·p0.50:   1.776 ms/op
                 createUser·p0.90:   2.920 ms/op
                 createUser·p0.95:   3.326 ms/op
                 createUser·p0.99:   10.094 ms/op
                 createUser·p0.999:  16.515 ms/op
                 createUser·p0.9999: 16.835 ms/op
                 createUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14988
  mean =      2.139 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 470 
    [ 1.250,  2.500) = 11443 
    [ 2.500,  3.750) = 2648 
    [ 3.750,  5.000) = 136 
    [ 5.000,  6.250) = 67 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      1.776 ms/op
     p(90.0000) =      2.920 ms/op
     p(95.0000) =      3.326 ms/op
     p(99.0000) =     10.094 ms/op
     p(99.9000) =     16.515 ms/op
     p(99.9900) =     16.835 ms/op
     p(99.9990) =     16.908 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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
# Warmup Iteration   1: 2.714 ±(99.9%) 0.055 ms/op
Iteration   1: 2.111 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.489 ms/op
                 existUser·p0.50:   2.001 ms/op
                 existUser·p0.90:   2.515 ms/op
                 existUser·p0.95:   2.687 ms/op
                 existUser·p0.99:   5.067 ms/op
                 existUser·p0.999:  18.575 ms/op
                 existUser·p0.9999: 20.051 ms/op
                 existUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15147
  mean =      2.111 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13533 
    [ 2.500,  5.000) = 1452 
    [ 5.000,  7.500) = 98 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.489 ms/op
     p(50.0000) =      2.001 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      5.067 ms/op
     p(99.9000) =     18.575 ms/op
     p(99.9900) =     20.051 ms/op
     p(99.9990) =     20.742 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 3.048 ±(99.9%) 0.070 ms/op
Iteration   1: 2.079 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.464 ms/op
                 getUser·p0.50:   2.038 ms/op
                 getUser·p0.90:   2.683 ms/op
                 getUser·p0.95:   2.966 ms/op
                 getUser·p0.99:   3.449 ms/op
                 getUser·p0.999:  11.063 ms/op
                 getUser·p0.9999: 11.551 ms/op
                 getUser·p1.00:   11.551 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15398
  mean =      2.079 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 397 
    [ 1.250,  2.500) = 12431 
    [ 2.500,  3.750) = 2446 
    [ 3.750,  5.000) = 19 
    [ 5.000,  6.250) = 54 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.464 ms/op
     p(50.0000) =      2.038 ms/op
     p(90.0000) =      2.683 ms/op
     p(95.0000) =      2.966 ms/op
     p(99.0000) =      3.449 ms/op
     p(99.9000) =     11.063 ms/op
     p(99.9900) =     11.551 ms/op
     p(99.9990) =     11.551 ms/op
     p(99.9999) =     11.551 ms/op
    p(100.0000) =     11.551 ms/op


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
# Warmup Iteration   1: 4.534 ±(99.9%) 0.129 ms/op
Iteration   1: 3.693 ±(99.9%) 0.089 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   3.506 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  40.829 ms/op
                 listUser·p0.9999: 41.943 ms/op
                 listUser·p1.00:   41.943 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8700
  mean =      3.693 ±(99.9%) 0.089 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8305 
    [ 5.000, 10.000) = 330 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 5 
    [20.000, 25.000) = 28 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 15 
    [40.000, 45.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     40.829 ms/op
     p(99.9900) =     41.943 ms/op
     p(99.9990) =     41.943 ms/op
     p(99.9999) =     41.943 ms/op
    p(100.0000) =     41.943 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.671          ops/ms
ClientSimple.existUser                       thrpt         13.281          ops/ms
ClientSimple.getUser                         thrpt         14.243          ops/ms
ClientSimple.listUser                        thrpt          8.456          ops/ms
ClientSimple.createUser                       avgt          1.952           ms/op
ClientSimple.existUser                        avgt          1.707           ms/op
ClientSimple.getUser                          avgt          2.136           ms/op
ClientSimple.listUser                         avgt          3.650           ms/op
ClientSimple.createUser                     sample  14988   2.139 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.563           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.776           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.920           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.326           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.094           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.515           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.835           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.908           ms/op
ClientSimple.existUser                      sample  15147   2.111 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.489           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.001           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.515           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.687           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.067           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.575           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.051           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.742           ms/op
ClientSimple.getUser                        sample  15398   2.079 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.464           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.038           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.683           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.966           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.449           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.063           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.551           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.551           ms/op
ClientSimple.listUser                       sample   8700   3.693 ± 0.089   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.092           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.506           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.833           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.595           ms/op
ClientSimple.listUser:listUser·p0.999       sample         40.829           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         41.943           ms/op
ClientSimple.listUser:listUser·p1.00        sample         41.943           ms/op

Benchmark result is saved to 1711001461947.json
