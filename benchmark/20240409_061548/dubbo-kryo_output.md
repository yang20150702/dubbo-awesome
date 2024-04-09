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
# Warmup Iteration   1: 1.619 ops/ms
Iteration   1: 7.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.147 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.816 ops/ms
Iteration   1: 12.881 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.881 ops/ms


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
# Warmup Iteration   1: 5.236 ops/ms
Iteration   1: 13.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.114 ops/ms


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
# Warmup Iteration   1: 4.228 ops/ms
Iteration   1: 9.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.017 ops/ms


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
# Warmup Iteration   1: 4.430 ±(99.9%) 0.074 ms/op
Iteration   1: 2.294 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.294 ms/op


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
# Warmup Iteration   1: 2.971 ±(99.9%) 0.044 ms/op
Iteration   1: 2.054 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.054 ms/op


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
# Warmup Iteration   1: 3.150 ±(99.9%) 0.060 ms/op
Iteration   1: 2.084 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.084 ms/op


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
# Warmup Iteration   1: 4.540 ±(99.9%) 0.109 ms/op
Iteration   1: 4.003 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.003 ms/op


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
# Warmup Iteration   1: 3.455 ±(99.9%) 0.086 ms/op
Iteration   1: 2.187 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.931 ms/op
                 createUser·p0.50:   2.025 ms/op
                 createUser·p0.90:   2.642 ms/op
                 createUser·p0.95:   2.970 ms/op
                 createUser·p0.99:   4.822 ms/op
                 createUser·p0.999:  16.548 ms/op
                 createUser·p0.9999: 17.220 ms/op
                 createUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14736
  mean =      2.187 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 12220 
    [ 2.500,  3.750) = 2243 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      2.025 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.970 ms/op
     p(99.0000) =      4.822 ms/op
     p(99.9000) =     16.548 ms/op
     p(99.9900) =     17.220 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 2.833 ±(99.9%) 0.056 ms/op
Iteration   1: 2.316 ±(99.9%) 0.086 ms/op
                 existUser·p0.00:   0.494 ms/op
                 existUser·p0.50:   2.146 ms/op
                 existUser·p0.90:   2.707 ms/op
                 existUser·p0.95:   2.900 ms/op
                 existUser·p0.99:   4.223 ms/op
                 existUser·p0.999:  63.308 ms/op
                 existUser·p0.9999: 64.281 ms/op
                 existUser·p1.00:   64.356 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 13842
  mean =      2.316 ±(99.9%) 0.086 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13740 
    [ 5.000, 10.000) = 6 
    [10.000, 15.000) = 64 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      2.146 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =      4.223 ms/op
     p(99.9000) =     63.308 ms/op
     p(99.9900) =     64.281 ms/op
     p(99.9990) =     64.356 ms/op
     p(99.9999) =     64.356 ms/op
    p(100.0000) =     64.356 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.210 ±(99.9%) 0.081 ms/op
Iteration   1: 2.161 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.401 ms/op
                 getUser·p0.50:   2.130 ms/op
                 getUser·p0.90:   2.781 ms/op
                 getUser·p0.95:   2.937 ms/op
                 getUser·p0.99:   4.907 ms/op
                 getUser·p0.999:  10.786 ms/op
                 getUser·p0.9999: 11.642 ms/op
                 getUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14887
  mean =      2.161 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 362 
    [ 1.250,  2.500) = 10812 
    [ 2.500,  3.750) = 3520 
    [ 3.750,  5.000) = 65 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.401 ms/op
     p(50.0000) =      2.130 ms/op
     p(90.0000) =      2.781 ms/op
     p(95.0000) =      2.937 ms/op
     p(99.0000) =      4.907 ms/op
     p(99.9000) =     10.786 ms/op
     p(99.9900) =     11.642 ms/op
     p(99.9990) =     11.682 ms/op
     p(99.9999) =     11.682 ms/op
    p(100.0000) =     11.682 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.709 ±(99.9%) 0.153 ms/op
Iteration   1: 3.613 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.983 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   5.344 ms/op
                 listUser·p0.999:  6.893 ms/op
                 listUser·p0.9999: 7.242 ms/op
                 listUser·p1.00:   7.242 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8870
  mean =      3.613 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 3 
    [1.000, 1.500) = 18 
    [1.500, 2.000) = 91 
    [2.000, 2.500) = 486 
    [2.500, 3.000) = 946 
    [3.000, 3.500) = 1828 
    [3.500, 4.000) = 3196 
    [4.000, 4.500) = 1756 
    [4.500, 5.000) = 370 
    [5.000, 5.500) = 100 
    [5.500, 6.000) = 39 
    [6.000, 6.500) = 23 
    [6.500, 7.000) = 10 
    [7.000, 7.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.983 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      5.344 ms/op
     p(99.9000) =      6.893 ms/op
     p(99.9900) =      7.242 ms/op
     p(99.9990) =      7.242 ms/op
     p(99.9999) =      7.242 ms/op
    p(100.0000) =      7.242 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.147          ops/ms
ClientSimple.existUser                       thrpt         12.881          ops/ms
ClientSimple.getUser                         thrpt         13.114          ops/ms
ClientSimple.listUser                        thrpt          9.017          ops/ms
ClientSimple.createUser                       avgt          2.294           ms/op
ClientSimple.existUser                        avgt          2.054           ms/op
ClientSimple.getUser                          avgt          2.084           ms/op
ClientSimple.listUser                         avgt          4.003           ms/op
ClientSimple.createUser                     sample  14736   2.187 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.931           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.025           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.642           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.970           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.822           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.548           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.220           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.531           ms/op
ClientSimple.existUser                      sample  13842   2.316 ± 0.086   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.494           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.146           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.707           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.900           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.223           ms/op
ClientSimple.existUser:existUser·p0.999     sample         63.308           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         64.281           ms/op
ClientSimple.existUser:existUser·p1.00      sample         64.356           ms/op
ClientSimple.getUser                        sample  14887   2.161 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.401           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.130           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.781           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.937           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.907           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.786           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.642           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.682           ms/op
ClientSimple.listUser                       sample   8870   3.613 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.983           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.674           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.620           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.344           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.893           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.242           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.242           ms/op

Benchmark result is saved to 1712643112284.json
