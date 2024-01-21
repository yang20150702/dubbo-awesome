# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.384 ops/ms
Iteration   1: 6.023 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.023 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.858 ops/ms
Iteration   1: 12.388 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.388 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.941 ops/ms
Iteration   1: 8.156 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.156 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.018 ops/ms
Iteration   1: 4.217 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.217 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.526 ±(99.9%) 0.059 ms/op
Iteration   1: 3.070 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.070 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.971 ±(99.9%) 0.026 ms/op
Iteration   1: 1.835 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.835 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.582 ±(99.9%) 0.073 ms/op
Iteration   1: 3.314 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.314 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.756 ±(99.9%) 0.262 ms/op
Iteration   1: 7.967 ±(99.9%) 0.083 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.967 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.616 ±(99.9%) 0.172 ms/op
Iteration   1: 3.332 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   1.294 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   11.434 ms/op
                 createUser·p0.999:  13.563 ms/op
                 createUser·p0.9999: 13.795 ms/op
                 createUser·p1.00:   13.795 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9593
  mean =      3.332 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1057 
    [ 2.500,  3.750) = 7024 
    [ 3.750,  5.000) = 1267 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =     11.434 ms/op
     p(99.9000) =     13.563 ms/op
     p(99.9900) =     13.795 ms/op
     p(99.9990) =     13.795 ms/op
     p(99.9999) =     13.795 ms/op
    p(100.0000) =     13.795 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.294 ±(99.9%) 0.077 ms/op
Iteration   1: 1.830 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.537 ms/op
                 existUser·p0.50:   1.751 ms/op
                 existUser·p0.90:   2.470 ms/op
                 existUser·p0.95:   2.699 ms/op
                 existUser·p0.99:   3.618 ms/op
                 existUser·p0.999:  4.596 ms/op
                 existUser·p0.9999: 5.987 ms/op
                 existUser·p1.00:   10.109 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17576
  mean =      1.830 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 98 
    [ 1.000,  2.000) = 12421 
    [ 2.000,  3.000) = 4706 
    [ 3.000,  4.000) = 259 
    [ 4.000,  5.000) = 91 
    [ 5.000,  6.000) = 0 
    [ 6.000,  7.000) = 0 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      1.751 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.699 ms/op
     p(99.0000) =      3.618 ms/op
     p(99.9000) =      4.596 ms/op
     p(99.9900) =      5.987 ms/op
     p(99.9990) =     10.109 ms/op
     p(99.9999) =     10.109 ms/op
    p(100.0000) =     10.109 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.571 ±(99.9%) 0.103 ms/op
Iteration   1: 3.093 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.489 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.204 ms/op
                 getUser·p0.99:   5.110 ms/op
                 getUser·p0.999:  6.658 ms/op
                 getUser·p0.9999: 8.242 ms/op
                 getUser·p1.00:   8.274 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10415
  mean =      3.093 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 1 
    [0.500, 1.000) = 22 
    [1.000, 1.500) = 65 
    [1.500, 2.000) = 295 
    [2.000, 2.500) = 1076 
    [2.500, 3.000) = 3334 
    [3.000, 3.500) = 3312 
    [3.500, 4.000) = 1547 
    [4.000, 4.500) = 502 
    [4.500, 5.000) = 147 
    [5.000, 5.500) = 66 
    [5.500, 6.000) = 34 
    [6.000, 6.500) = 3 
    [6.500, 7.000) = 6 
    [7.000, 7.500) = 3 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.489 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.204 ms/op
     p(99.0000) =      5.110 ms/op
     p(99.9000) =      6.658 ms/op
     p(99.9900) =      8.242 ms/op
     p(99.9990) =      8.274 ms/op
     p(99.9999) =      8.274 ms/op
    p(100.0000) =      8.274 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.797 ±(99.9%) 0.436 ms/op
Iteration   1: 8.985 ±(99.9%) 0.126 ms/op
                 listUser·p0.00:   2.605 ms/op
                 listUser·p0.50:   8.782 ms/op
                 listUser·p0.90:   12.009 ms/op
                 listUser·p0.95:   12.984 ms/op
                 listUser·p0.99:   15.396 ms/op
                 listUser·p0.999:  18.651 ms/op
                 listUser·p0.9999: 25.133 ms/op
                 listUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3530
  mean =      8.985 ±(99.9%) 0.126 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 84 
    [ 5.000,  7.500) = 884 
    [ 7.500, 10.000) = 1548 
    [10.000, 12.500) = 771 
    [12.500, 15.000) = 197 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.605 ms/op
     p(50.0000) =      8.782 ms/op
     p(90.0000) =     12.009 ms/op
     p(95.0000) =     12.984 ms/op
     p(99.0000) =     15.396 ms/op
     p(99.9000) =     18.651 ms/op
     p(99.9900) =     25.133 ms/op
     p(99.9990) =     25.133 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.023          ops/ms
Client.existUser                       thrpt         12.388          ops/ms
Client.getUser                         thrpt          8.156          ops/ms
Client.listUser                        thrpt          4.217          ops/ms
Client.createUser                       avgt          3.070           ms/op
Client.existUser                        avgt          1.835           ms/op
Client.getUser                          avgt          3.314           ms/op
Client.listUser                         avgt          7.967           ms/op
Client.createUser                     sample   9593   3.332 ± 0.044   ms/op
Client.createUser:createUser·p0.00    sample          1.294           ms/op
Client.createUser:createUser·p0.50    sample          3.154           ms/op
Client.createUser:createUser·p0.90    sample          4.006           ms/op
Client.createUser:createUser·p0.95    sample          4.276           ms/op
Client.createUser:createUser·p0.99    sample         11.434           ms/op
Client.createUser:createUser·p0.999   sample         13.563           ms/op
Client.createUser:createUser·p0.9999  sample         13.795           ms/op
Client.createUser:createUser·p1.00    sample         13.795           ms/op
Client.existUser                      sample  17576   1.830 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          0.537           ms/op
Client.existUser:existUser·p0.50      sample          1.751           ms/op
Client.existUser:existUser·p0.90      sample          2.470           ms/op
Client.existUser:existUser·p0.95      sample          2.699           ms/op
Client.existUser:existUser·p0.99      sample          3.618           ms/op
Client.existUser:existUser·p0.999     sample          4.596           ms/op
Client.existUser:existUser·p0.9999    sample          5.987           ms/op
Client.existUser:existUser·p1.00      sample         10.109           ms/op
Client.getUser                        sample  10415   3.093 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          0.489           ms/op
Client.getUser:getUser·p0.50          sample          3.052           ms/op
Client.getUser:getUser·p0.90          sample          3.842           ms/op
Client.getUser:getUser·p0.95          sample          4.204           ms/op
Client.getUser:getUser·p0.99          sample          5.110           ms/op
Client.getUser:getUser·p0.999         sample          6.658           ms/op
Client.getUser:getUser·p0.9999        sample          8.242           ms/op
Client.getUser:getUser·p1.00          sample          8.274           ms/op
Client.listUser                       sample   3530   8.985 ± 0.126   ms/op
Client.listUser:listUser·p0.00        sample          2.605           ms/op
Client.listUser:listUser·p0.50        sample          8.782           ms/op
Client.listUser:listUser·p0.90        sample         12.009           ms/op
Client.listUser:listUser·p0.95        sample         12.984           ms/op
Client.listUser:listUser·p0.99        sample         15.396           ms/op
Client.listUser:listUser·p0.999       sample         18.651           ms/op
Client.listUser:listUser·p0.9999      sample         25.133           ms/op
Client.listUser:listUser·p1.00        sample         25.133           ms/op
