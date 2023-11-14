# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.697 ops/ms
Iteration   1: 6.071 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.071 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.237 ops/ms
Iteration   1: 15.023 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  15.023 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.222 ops/ms
Iteration   1: 8.622 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.622 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.138 ops/ms
Iteration   1: 3.701 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.701 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.002 ±(99.9%) 0.061 ms/op
Iteration   1: 3.092 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.092 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.068 ±(99.9%) 0.036 ms/op
Iteration   1: 1.906 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.906 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.481 ±(99.9%) 0.045 ms/op
Iteration   1: 3.080 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.080 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.106 ±(99.9%) 0.165 ms/op
Iteration   1: 7.854 ±(99.9%) 0.076 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.854 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.599 ±(99.9%) 0.093 ms/op
Iteration   1: 3.012 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   1.165 ms/op
                 createUser·p0.50:   2.814 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   6.726 ms/op
                 createUser·p0.999:  13.933 ms/op
                 createUser·p0.9999: 14.787 ms/op
                 createUser·p1.00:   14.811 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10592
  mean =      3.012 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 2751 
    [ 2.500,  3.750) = 6794 
    [ 3.750,  5.000) = 809 
    [ 5.000,  6.250) = 90 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      2.814 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     13.933 ms/op
     p(99.9900) =     14.787 ms/op
     p(99.9990) =     14.811 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.986 ±(99.9%) 0.057 ms/op
Iteration   1: 1.785 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.461 ms/op
                 existUser·p0.50:   1.688 ms/op
                 existUser·p0.90:   2.236 ms/op
                 existUser·p0.95:   2.507 ms/op
                 existUser·p0.99:   3.015 ms/op
                 existUser·p0.999:  14.042 ms/op
                 existUser·p0.9999: 14.973 ms/op
                 existUser·p1.00:   15.155 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17933
  mean =      1.785 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 576 
    [ 1.250,  2.500) = 16444 
    [ 2.500,  3.750) = 835 
    [ 3.750,  5.000) = 23 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.461 ms/op
     p(50.0000) =      1.688 ms/op
     p(90.0000) =      2.236 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      3.015 ms/op
     p(99.9000) =     14.042 ms/op
     p(99.9900) =     14.973 ms/op
     p(99.9990) =     15.155 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.346 ±(99.9%) 0.087 ms/op
Iteration   1: 2.737 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   5.202 ms/op
                 getUser·p0.999:  7.037 ms/op
                 getUser·p0.9999: 8.604 ms/op
                 getUser·p1.00:   8.782 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11988
  mean =      2.737 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 20 
    [1.500, 2.000) = 533 
    [2.000, 2.500) = 5305 
    [2.500, 3.000) = 2412 
    [3.000, 3.500) = 2353 
    [3.500, 4.000) = 880 
    [4.000, 4.500) = 232 
    [4.500, 5.000) = 98 
    [5.000, 5.500) = 67 
    [5.500, 6.000) = 18 
    [6.000, 6.500) = 47 
    [6.500, 7.000) = 9 
    [7.000, 7.500) = 7 
    [7.500, 8.000) = 4 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =      7.037 ms/op
     p(99.9900) =      8.604 ms/op
     p(99.9990) =      8.782 ms/op
     p(99.9999) =      8.782 ms/op
    p(100.0000) =      8.782 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 11.204 ±(99.9%) 0.389 ms/op
Iteration   1: 7.404 ±(99.9%) 0.096 ms/op
                 listUser·p0.00:   2.466 ms/op
                 listUser·p0.50:   7.143 ms/op
                 listUser·p0.90:   10.022 ms/op
                 listUser·p0.95:   10.830 ms/op
                 listUser·p0.99:   12.785 ms/op
                 listUser·p0.999:  16.472 ms/op
                 listUser·p0.9999: 18.022 ms/op
                 listUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4312
  mean =      7.404 ±(99.9%) 0.096 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1 
    [ 2.500,  3.750) = 29 
    [ 3.750,  5.000) = 262 
    [ 5.000,  6.250) = 926 
    [ 6.250,  7.500) = 1274 
    [ 7.500,  8.750) = 969 
    [ 8.750, 10.000) = 416 
    [10.000, 11.250) = 268 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.466 ms/op
     p(50.0000) =      7.143 ms/op
     p(90.0000) =     10.022 ms/op
     p(95.0000) =     10.830 ms/op
     p(99.0000) =     12.785 ms/op
     p(99.9000) =     16.472 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     18.022 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.071          ops/ms
Client.existUser                       thrpt         15.023          ops/ms
Client.getUser                         thrpt          8.622          ops/ms
Client.listUser                        thrpt          3.701          ops/ms
Client.createUser                       avgt          3.092           ms/op
Client.existUser                        avgt          1.906           ms/op
Client.getUser                          avgt          3.080           ms/op
Client.listUser                         avgt          7.854           ms/op
Client.createUser                     sample  10592   3.012 ± 0.032   ms/op
Client.createUser:createUser·p0.00    sample          1.165           ms/op
Client.createUser:createUser·p0.50    sample          2.814           ms/op
Client.createUser:createUser·p0.90    sample          3.740           ms/op
Client.createUser:createUser·p0.95    sample          4.145           ms/op
Client.createUser:createUser·p0.99    sample          6.726           ms/op
Client.createUser:createUser·p0.999   sample         13.933           ms/op
Client.createUser:createUser·p0.9999  sample         14.787           ms/op
Client.createUser:createUser·p1.00    sample         14.811           ms/op
Client.existUser                      sample  17933   1.785 ± 0.016   ms/op
Client.existUser:existUser·p0.00      sample          0.461           ms/op
Client.existUser:existUser·p0.50      sample          1.688           ms/op
Client.existUser:existUser·p0.90      sample          2.236           ms/op
Client.existUser:existUser·p0.95      sample          2.507           ms/op
Client.existUser:existUser·p0.99      sample          3.015           ms/op
Client.existUser:existUser·p0.999     sample         14.042           ms/op
Client.existUser:existUser·p0.9999    sample         14.973           ms/op
Client.existUser:existUser·p1.00      sample         15.155           ms/op
Client.getUser                        sample  11988   2.737 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          0.827           ms/op
Client.getUser:getUser·p0.50          sample          2.519           ms/op
Client.getUser:getUser·p0.90          sample          3.559           ms/op
Client.getUser:getUser·p0.95          sample          3.903           ms/op
Client.getUser:getUser·p0.99          sample          5.202           ms/op
Client.getUser:getUser·p0.999         sample          7.037           ms/op
Client.getUser:getUser·p0.9999        sample          8.604           ms/op
Client.getUser:getUser·p1.00          sample          8.782           ms/op
Client.listUser                       sample   4312   7.404 ± 0.096   ms/op
Client.listUser:listUser·p0.00        sample          2.466           ms/op
Client.listUser:listUser·p0.50        sample          7.143           ms/op
Client.listUser:listUser·p0.90        sample         10.022           ms/op
Client.listUser:listUser·p0.95        sample         10.830           ms/op
Client.listUser:listUser·p0.99        sample         12.785           ms/op
Client.listUser:listUser·p0.999       sample         16.472           ms/op
Client.listUser:listUser·p0.9999      sample         18.022           ms/op
Client.listUser:listUser·p1.00        sample         18.022           ms/op
