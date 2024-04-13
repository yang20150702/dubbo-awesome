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
# Warmup Iteration   1: 1.669 ops/ms
Iteration   1: 5.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.566 ops/ms


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
# Warmup Iteration   1: 6.700 ops/ms
Iteration   1: 11.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.319 ops/ms


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
# Warmup Iteration   1: 5.113 ops/ms
Iteration   1: 12.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.396 ops/ms


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
# Warmup Iteration   1: 4.549 ops/ms
Iteration   1: 8.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.267 ops/ms


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
# Warmup Iteration   1: 4.348 ±(99.9%) 0.080 ms/op
Iteration   1: 2.255 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.255 ms/op


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
# Warmup Iteration   1: 3.185 ±(99.9%) 0.065 ms/op
Iteration   1: 2.089 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.089 ms/op


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
# Warmup Iteration   1: 3.280 ±(99.9%) 0.063 ms/op
Iteration   1: 2.223 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.223 ms/op


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
# Warmup Iteration   1: 4.630 ±(99.9%) 0.105 ms/op
Iteration   1: 3.627 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.627 ms/op


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
# Warmup Iteration   1: 3.778 ±(99.9%) 0.104 ms/op
Iteration   1: 2.195 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.431 ms/op
                 createUser·p0.50:   2.025 ms/op
                 createUser·p0.90:   2.640 ms/op
                 createUser·p0.95:   3.076 ms/op
                 createUser·p0.99:   8.124 ms/op
                 createUser·p0.999:  14.025 ms/op
                 createUser·p0.9999: 15.463 ms/op
                 createUser·p1.00:   15.679 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14554
  mean =      2.195 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 421 
    [ 1.250,  2.500) = 12070 
    [ 2.500,  3.750) = 1462 
    [ 3.750,  5.000) = 262 
    [ 5.000,  6.250) = 104 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.431 ms/op
     p(50.0000) =      2.025 ms/op
     p(90.0000) =      2.640 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      8.124 ms/op
     p(99.9000) =     14.025 ms/op
     p(99.9900) =     15.463 ms/op
     p(99.9990) =     15.679 ms/op
     p(99.9999) =     15.679 ms/op
    p(100.0000) =     15.679 ms/op


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
# Warmup Iteration   1: 3.290 ±(99.9%) 0.105 ms/op
Iteration   1: 1.958 ±(99.9%) 0.037 ms/op
                 existUser·p0.00:   0.440 ms/op
                 existUser·p0.50:   1.815 ms/op
                 existUser·p0.90:   2.413 ms/op
                 existUser·p0.95:   2.630 ms/op
                 existUser·p0.99:   4.082 ms/op
                 existUser·p0.999:  30.966 ms/op
                 existUser·p0.9999: 31.425 ms/op
                 existUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16646
  mean =      1.958 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15396 
    [ 2.500,  5.000) = 1141 
    [ 5.000,  7.500) = 13 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      1.815 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      4.082 ms/op
     p(99.9000) =     30.966 ms/op
     p(99.9900) =     31.425 ms/op
     p(99.9990) =     31.687 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


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
# Warmup Iteration   1: 3.278 ±(99.9%) 0.086 ms/op
Iteration   1: 2.100 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.489 ms/op
                 getUser·p0.50:   1.937 ms/op
                 getUser·p0.90:   2.699 ms/op
                 getUser·p0.95:   2.904 ms/op
                 getUser·p0.99:   4.088 ms/op
                 getUser·p0.999:  21.201 ms/op
                 getUser·p0.9999: 22.166 ms/op
                 getUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15332
  mean =      2.100 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12633 
    [ 2.500,  5.000) = 2595 
    [ 5.000,  7.500) = 40 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.489 ms/op
     p(50.0000) =      1.937 ms/op
     p(90.0000) =      2.699 ms/op
     p(95.0000) =      2.904 ms/op
     p(99.0000) =      4.088 ms/op
     p(99.9000) =     21.201 ms/op
     p(99.9900) =     22.166 ms/op
     p(99.9990) =     22.184 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


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
# Warmup Iteration   1: 4.590 ±(99.9%) 0.169 ms/op
Iteration   1: 3.391 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   6.058 ms/op
                 listUser·p0.999:  15.705 ms/op
                 listUser·p0.9999: 16.466 ms/op
                 listUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9427
  mean =      3.391 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 400 
    [ 2.500,  3.750) = 6124 
    [ 3.750,  5.000) = 2621 
    [ 5.000,  6.250) = 200 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.058 ms/op
     p(99.9000) =     15.705 ms/op
     p(99.9900) =     16.466 ms/op
     p(99.9990) =     16.466 ms/op
     p(99.9999) =     16.466 ms/op
    p(100.0000) =     16.466 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.566          ops/ms
ClientSimple.existUser                       thrpt         11.319          ops/ms
ClientSimple.getUser                         thrpt         12.396          ops/ms
ClientSimple.listUser                        thrpt          8.267          ops/ms
ClientSimple.createUser                       avgt          2.255           ms/op
ClientSimple.existUser                        avgt          2.089           ms/op
ClientSimple.getUser                          avgt          2.223           ms/op
ClientSimple.listUser                         avgt          3.627           ms/op
ClientSimple.createUser                     sample  14554   2.195 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.431           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.025           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.640           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.076           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.124           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.025           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.463           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.679           ms/op
ClientSimple.existUser                      sample  16646   1.958 ± 0.037   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.440           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.815           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.413           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.630           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.082           ms/op
ClientSimple.existUser:existUser·p0.999     sample         30.966           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         31.425           ms/op
ClientSimple.existUser:existUser·p1.00      sample         31.687           ms/op
ClientSimple.getUser                        sample  15332   2.100 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.489           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.937           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.699           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.904           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.088           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.201           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.166           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.184           ms/op
ClientSimple.listUser                       sample   9427   3.391 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.237           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.035           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.383           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.678           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.058           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.705           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.466           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.466           ms/op

Benchmark result is saved to 1713010327318.json
