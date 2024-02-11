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
Iteration   1: 5.363 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.363 ops/ms


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
# Warmup Iteration   1: 5.533 ops/ms
Iteration   1: 12.868 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.868 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.439 ops/ms
Iteration   1: 8.060 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.060 ops/ms


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
# Warmup Iteration   1: 2.019 ops/ms
Iteration   1: 3.264 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.264 ops/ms


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
# Warmup Iteration   1: 5.613 ±(99.9%) 0.076 ms/op
Iteration   1: 3.109 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.109 ms/op


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
# Warmup Iteration   1: 3.147 ±(99.9%) 0.036 ms/op
Iteration   1: 1.858 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.858 ms/op


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
# Warmup Iteration   1: 5.124 ±(99.9%) 0.074 ms/op
Iteration   1: 3.177 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.177 ms/op


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
# Warmup Iteration   1: 14.303 ±(99.9%) 0.248 ms/op
Iteration   1: 9.049 ±(99.9%) 0.161 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.049 ms/op


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
# Warmup Iteration   1: 5.647 ±(99.9%) 0.174 ms/op
Iteration   1: 3.187 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   4.104 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   6.988 ms/op
                 createUser·p0.999:  12.829 ms/op
                 createUser·p0.9999: 12.894 ms/op
                 createUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10021
  mean =      3.187 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 2250 
    [ 2.500,  3.750) = 6139 
    [ 3.750,  5.000) = 1161 
    [ 5.000,  6.250) = 255 
    [ 6.250,  7.500) = 124 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     12.829 ms/op
     p(99.9900) =     12.894 ms/op
     p(99.9990) =     12.894 ms/op
     p(99.9999) =     12.894 ms/op
    p(100.0000) =     12.894 ms/op


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
# Warmup Iteration   1: 3.340 ±(99.9%) 0.078 ms/op
Iteration   1: 1.807 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.746 ms/op
                 existUser·p0.50:   1.737 ms/op
                 existUser·p0.90:   2.216 ms/op
                 existUser·p0.95:   2.404 ms/op
                 existUser·p0.99:   3.010 ms/op
                 existUser·p0.999:  5.554 ms/op
                 existUser·p0.9999: 6.433 ms/op
                 existUser·p1.00:   6.439 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17703
  mean =      1.807 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 47 
    [1.000, 1.500) = 1997 
    [1.500, 2.000) = 12514 
    [2.000, 2.500) = 2476 
    [2.500, 3.000) = 487 
    [3.000, 3.500) = 43 
    [3.500, 4.000) = 47 
    [4.000, 4.500) = 18 
    [4.500, 5.000) = 21 
    [5.000, 5.500) = 27 
    [5.500, 6.000) = 11 
    [6.000, 6.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      1.737 ms/op
     p(90.0000) =      2.216 ms/op
     p(95.0000) =      2.404 ms/op
     p(99.0000) =      3.010 ms/op
     p(99.9000) =      5.554 ms/op
     p(99.9900) =      6.433 ms/op
     p(99.9990) =      6.439 ms/op
     p(99.9999) =      6.439 ms/op
    p(100.0000) =      6.439 ms/op


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
# Warmup Iteration   1: 5.044 ±(99.9%) 0.138 ms/op
Iteration   1: 3.362 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.566 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   4.178 ms/op
                 getUser·p0.95:   4.781 ms/op
                 getUser·p0.99:   7.258 ms/op
                 getUser·p0.999:  10.273 ms/op
                 getUser·p0.9999: 14.729 ms/op
                 getUser·p1.00:   14.729 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9506
  mean =      3.362 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 1095 
    [ 2.500,  3.750) = 6169 
    [ 3.750,  5.000) = 1819 
    [ 5.000,  6.250) = 260 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.781 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     10.273 ms/op
     p(99.9900) =     14.729 ms/op
     p(99.9990) =     14.729 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 13.428 ±(99.9%) 0.462 ms/op
Iteration   1: 9.013 ±(99.9%) 0.119 ms/op
                 listUser·p0.00:   3.097 ms/op
                 listUser·p0.50:   8.651 ms/op
                 listUser·p0.90:   11.829 ms/op
                 listUser·p0.95:   13.025 ms/op
                 listUser·p0.99:   15.855 ms/op
                 listUser·p0.999:  20.818 ms/op
                 listUser·p0.9999: 24.314 ms/op
                 listUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3590
  mean =      9.013 ±(99.9%) 0.119 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 53 
    [ 5.000,  7.500) = 741 
    [ 7.500, 10.000) = 1838 
    [10.000, 12.500) = 704 
    [12.500, 15.000) = 212 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.097 ms/op
     p(50.0000) =      8.651 ms/op
     p(90.0000) =     11.829 ms/op
     p(95.0000) =     13.025 ms/op
     p(99.0000) =     15.855 ms/op
     p(99.9000) =     20.818 ms/op
     p(99.9900) =     24.314 ms/op
     p(99.9990) =     24.314 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.363          ops/ms
Client.existUser                       thrpt         12.868          ops/ms
Client.getUser                         thrpt          8.060          ops/ms
Client.listUser                        thrpt          3.264          ops/ms
Client.createUser                       avgt          3.109           ms/op
Client.existUser                        avgt          1.858           ms/op
Client.getUser                          avgt          3.177           ms/op
Client.listUser                         avgt          9.049           ms/op
Client.createUser                     sample  10021   3.187 ± 0.037   ms/op
Client.createUser:createUser·p0.00    sample          0.863           ms/op
Client.createUser:createUser·p0.50    sample          3.023           ms/op
Client.createUser:createUser·p0.90    sample          4.104           ms/op
Client.createUser:createUser·p0.95    sample          4.841           ms/op
Client.createUser:createUser·p0.99    sample          6.988           ms/op
Client.createUser:createUser·p0.999   sample         12.829           ms/op
Client.createUser:createUser·p0.9999  sample         12.894           ms/op
Client.createUser:createUser·p1.00    sample         12.894           ms/op
Client.existUser                      sample  17703   1.807 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.746           ms/op
Client.existUser:existUser·p0.50      sample          1.737           ms/op
Client.existUser:existUser·p0.90      sample          2.216           ms/op
Client.existUser:existUser·p0.95      sample          2.404           ms/op
Client.existUser:existUser·p0.99      sample          3.010           ms/op
Client.existUser:existUser·p0.999     sample          5.554           ms/op
Client.existUser:existUser·p0.9999    sample          6.433           ms/op
Client.existUser:existUser·p1.00      sample          6.439           ms/op
Client.getUser                        sample   9506   3.362 ± 0.033   ms/op
Client.getUser:getUser·p0.00          sample          0.566           ms/op
Client.getUser:getUser·p0.50          sample          3.281           ms/op
Client.getUser:getUser·p0.90          sample          4.178           ms/op
Client.getUser:getUser·p0.95          sample          4.781           ms/op
Client.getUser:getUser·p0.99          sample          7.258           ms/op
Client.getUser:getUser·p0.999         sample         10.273           ms/op
Client.getUser:getUser·p0.9999        sample         14.729           ms/op
Client.getUser:getUser·p1.00          sample         14.729           ms/op
Client.listUser                       sample   3590   9.013 ± 0.119   ms/op
Client.listUser:listUser·p0.00        sample          3.097           ms/op
Client.listUser:listUser·p0.50        sample          8.651           ms/op
Client.listUser:listUser·p0.90        sample         11.829           ms/op
Client.listUser:listUser·p0.95        sample         13.025           ms/op
Client.listUser:listUser·p0.99        sample         15.855           ms/op
Client.listUser:listUser·p0.999       sample         20.818           ms/op
Client.listUser:listUser·p0.9999      sample         24.314           ms/op
Client.listUser:listUser·p1.00        sample         24.314           ms/op
