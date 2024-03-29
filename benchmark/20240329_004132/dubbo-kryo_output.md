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
# Warmup Iteration   1: 1.930 ops/ms
Iteration   1: 6.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.518 ops/ms


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
# Warmup Iteration   1: 5.971 ops/ms
Iteration   1: 13.005 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.005 ops/ms


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
# Warmup Iteration   1: 5.478 ops/ms
Iteration   1: 14.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.180 ops/ms


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
# Warmup Iteration   1: 4.177 ops/ms
Iteration   1: 9.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.144 ops/ms


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
# Warmup Iteration   1: 3.913 ±(99.9%) 0.077 ms/op
Iteration   1: 2.464 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.464 ms/op


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
# Warmup Iteration   1: 3.154 ±(99.9%) 0.061 ms/op
Iteration   1: 1.706 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.706 ms/op


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
# Warmup Iteration   1: 3.199 ±(99.9%) 0.056 ms/op
Iteration   1: 2.094 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.094 ms/op


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
# Warmup Iteration   1: 4.904 ±(99.9%) 0.104 ms/op
Iteration   1: 3.697 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.697 ms/op


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
# Warmup Iteration   1: 3.774 ±(99.9%) 0.119 ms/op
Iteration   1: 2.248 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.527 ms/op
                 createUser·p0.50:   2.105 ms/op
                 createUser·p0.90:   2.851 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   8.471 ms/op
                 createUser·p0.999:  16.047 ms/op
                 createUser·p0.9999: 21.342 ms/op
                 createUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14277
  mean =      2.248 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11327 
    [ 2.500,  5.000) = 2679 
    [ 5.000,  7.500) = 85 
    [ 7.500, 10.000) = 90 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.851 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     16.047 ms/op
     p(99.9900) =     21.342 ms/op
     p(99.9990) =     21.987 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


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
# Warmup Iteration   1: 3.232 ±(99.9%) 0.076 ms/op
Iteration   1: 1.987 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.374 ms/op
                 existUser·p0.50:   1.931 ms/op
                 existUser·p0.90:   2.426 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   3.668 ms/op
                 existUser·p0.999:  11.019 ms/op
                 existUser·p0.9999: 12.032 ms/op
                 existUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16106
  mean =      1.987 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 202 
    [ 1.250,  2.500) = 14688 
    [ 2.500,  3.750) = 1057 
    [ 3.750,  5.000) = 78 
    [ 5.000,  6.250) = 28 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.374 ms/op
     p(50.0000) =      1.931 ms/op
     p(90.0000) =      2.426 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      3.668 ms/op
     p(99.9000) =     11.019 ms/op
     p(99.9900) =     12.032 ms/op
     p(99.9990) =     12.042 ms/op
     p(99.9999) =     12.042 ms/op
    p(100.0000) =     12.042 ms/op


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
# Warmup Iteration   1: 3.428 ±(99.9%) 0.101 ms/op
Iteration   1: 1.816 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.558 ms/op
                 getUser·p0.50:   1.669 ms/op
                 getUser·p0.90:   2.331 ms/op
                 getUser·p0.95:   2.556 ms/op
                 getUser·p0.99:   3.297 ms/op
                 getUser·p0.999:  16.908 ms/op
                 getUser·p0.9999: 16.974 ms/op
                 getUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17603
  mean =      1.816 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 483 
    [ 1.250,  2.500) = 16056 
    [ 2.500,  3.750) = 975 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      1.669 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.556 ms/op
     p(99.0000) =      3.297 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 4.242 ±(99.9%) 0.125 ms/op
Iteration   1: 3.686 ±(99.9%) 0.060 ms/op
                 listUser·p0.00:   0.910 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  28.407 ms/op
                 listUser·p0.9999: 29.491 ms/op
                 listUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8698
  mean =      3.686 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 661 
    [ 2.500,  5.000) = 7712 
    [ 5.000,  7.500) = 240 
    [ 7.500, 10.000) = 53 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      7.471 ms/op
     p(99.9000) =     28.407 ms/op
     p(99.9900) =     29.491 ms/op
     p(99.9990) =     29.491 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.518          ops/ms
ClientSimple.existUser                       thrpt         13.005          ops/ms
ClientSimple.getUser                         thrpt         14.180          ops/ms
ClientSimple.listUser                        thrpt          9.144          ops/ms
ClientSimple.createUser                       avgt          2.464           ms/op
ClientSimple.existUser                        avgt          1.706           ms/op
ClientSimple.getUser                          avgt          2.094           ms/op
ClientSimple.listUser                         avgt          3.697           ms/op
ClientSimple.createUser                     sample  14277   2.248 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.527           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.105           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.851           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.109           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.471           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.047           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.342           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.987           ms/op
ClientSimple.existUser                      sample  16106   1.987 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.374           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.931           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.426           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.668           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.019           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.032           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.042           ms/op
ClientSimple.getUser                        sample  17603   1.816 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.558           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.669           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.331           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.556           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.297           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.908           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.974           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.974           ms/op
ClientSimple.listUser                       sample   8698   3.686 ± 0.060   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.910           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.572           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.424           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.825           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.471           ms/op
ClientSimple.listUser:listUser·p0.999       sample         28.407           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         29.491           ms/op
ClientSimple.listUser:listUser·p1.00        sample         29.491           ms/op

Benchmark result is saved to 1711672600849.json
