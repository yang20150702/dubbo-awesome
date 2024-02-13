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
# Warmup Iteration   1: 2.409 ops/ms
Iteration   1: 6.089 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.089 ops/ms


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
# Warmup Iteration   1: 6.233 ops/ms
Iteration   1: 13.608 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.608 ops/ms


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
# Warmup Iteration   1: 4.338 ops/ms
Iteration   1: 8.664 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.664 ops/ms


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
# Warmup Iteration   1: 2.294 ops/ms
Iteration   1: 3.494 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.494 ops/ms


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
# Warmup Iteration   1: 5.592 ±(99.9%) 0.087 ms/op
Iteration   1: 3.118 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.118 ms/op


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
# Warmup Iteration   1: 3.142 ±(99.9%) 0.033 ms/op
Iteration   1: 1.856 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.856 ms/op


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
# Warmup Iteration   1: 4.544 ±(99.9%) 0.048 ms/op
Iteration   1: 3.112 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.112 ms/op


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
# Warmup Iteration   1: 13.471 ±(99.9%) 0.237 ms/op
Iteration   1: 8.884 ±(99.9%) 0.093 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.884 ms/op


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
# Warmup Iteration   1: 4.911 ±(99.9%) 0.094 ms/op
Iteration   1: 3.198 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   1.257 ms/op
                 createUser·p0.50:   2.904 ms/op
                 createUser·p0.90:   3.876 ms/op
                 createUser·p0.95:   4.193 ms/op
                 createUser·p0.99:   9.437 ms/op
                 createUser·p0.999:  17.531 ms/op
                 createUser·p0.9999: 18.973 ms/op
                 createUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10007
  mean =      3.198 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 870 
    [ 2.500,  3.750) = 7841 
    [ 3.750,  5.000) = 1001 
    [ 5.000,  6.250) = 108 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.876 ms/op
     p(95.0000) =      4.193 ms/op
     p(99.0000) =      9.437 ms/op
     p(99.9000) =     17.531 ms/op
     p(99.9900) =     18.973 ms/op
     p(99.9990) =     18.973 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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
# Warmup Iteration   1: 3.037 ±(99.9%) 0.069 ms/op
Iteration   1: 1.735 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.650 ms/op
                 existUser·p0.50:   1.628 ms/op
                 existUser·p0.90:   2.249 ms/op
                 existUser·p0.95:   2.474 ms/op
                 existUser·p0.99:   3.338 ms/op
                 existUser·p0.999:  9.208 ms/op
                 existUser·p0.9999: 9.311 ms/op
                 existUser·p1.00:   9.339 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18440
  mean =      1.735 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 78 
    [ 1.000,  2.000) = 14485 
    [ 2.000,  3.000) = 3485 
    [ 3.000,  4.000) = 292 
    [ 4.000,  5.000) = 34 
    [ 5.000,  6.000) = 33 
    [ 6.000,  7.000) = 1 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      1.628 ms/op
     p(90.0000) =      2.249 ms/op
     p(95.0000) =      2.474 ms/op
     p(99.0000) =      3.338 ms/op
     p(99.9000) =      9.208 ms/op
     p(99.9900) =      9.311 ms/op
     p(99.9990) =      9.339 ms/op
     p(99.9999) =      9.339 ms/op
    p(100.0000) =      9.339 ms/op


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
# Warmup Iteration   1: 4.647 ±(99.9%) 0.107 ms/op
Iteration   1: 3.238 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   4.157 ms/op
                 getUser·p0.95:   4.529 ms/op
                 getUser·p0.99:   5.572 ms/op
                 getUser·p0.999:  6.056 ms/op
                 getUser·p0.9999: 7.930 ms/op
                 getUser·p1.00:   7.930 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9881
  mean =      3.238 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 52 
    [1.500, 2.000) = 141 
    [2.000, 2.500) = 1187 
    [2.500, 3.000) = 2892 
    [3.000, 3.500) = 2359 
    [3.500, 4.000) = 1893 
    [4.000, 4.500) = 848 
    [4.500, 5.000) = 277 
    [5.000, 5.500) = 109 
    [5.500, 6.000) = 112 
    [6.000, 6.500) = 8 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.529 ms/op
     p(99.0000) =      5.572 ms/op
     p(99.9000) =      6.056 ms/op
     p(99.9900) =      7.930 ms/op
     p(99.9990) =      7.930 ms/op
     p(99.9999) =      7.930 ms/op
    p(100.0000) =      7.930 ms/op


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
# Warmup Iteration   1: 13.175 ±(99.9%) 0.504 ms/op
Iteration   1: 8.722 ±(99.9%) 0.148 ms/op
                 listUser·p0.00:   2.638 ms/op
                 listUser·p0.50:   8.258 ms/op
                 listUser·p0.90:   12.157 ms/op
                 listUser·p0.95:   14.251 ms/op
                 listUser·p0.99:   17.727 ms/op
                 listUser·p0.999:  20.689 ms/op
                 listUser·p0.9999: 22.741 ms/op
                 listUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3663
  mean =      8.722 ±(99.9%) 0.148 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 131 
    [ 5.000,  7.500) = 1214 
    [ 7.500, 10.000) = 1413 
    [10.000, 12.500) = 592 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.638 ms/op
     p(50.0000) =      8.258 ms/op
     p(90.0000) =     12.157 ms/op
     p(95.0000) =     14.251 ms/op
     p(99.0000) =     17.727 ms/op
     p(99.9000) =     20.689 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     22.741 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.089          ops/ms
Client.existUser                       thrpt         13.608          ops/ms
Client.getUser                         thrpt          8.664          ops/ms
Client.listUser                        thrpt          3.494          ops/ms
Client.createUser                       avgt          3.118           ms/op
Client.existUser                        avgt          1.856           ms/op
Client.getUser                          avgt          3.112           ms/op
Client.listUser                         avgt          8.884           ms/op
Client.createUser                     sample  10007   3.198 ± 0.044   ms/op
Client.createUser:createUser·p0.00    sample          1.257           ms/op
Client.createUser:createUser·p0.50    sample          2.904           ms/op
Client.createUser:createUser·p0.90    sample          3.876           ms/op
Client.createUser:createUser·p0.95    sample          4.193           ms/op
Client.createUser:createUser·p0.99    sample          9.437           ms/op
Client.createUser:createUser·p0.999   sample         17.531           ms/op
Client.createUser:createUser·p0.9999  sample         18.973           ms/op
Client.createUser:createUser·p1.00    sample         18.973           ms/op
Client.existUser                      sample  18440   1.735 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.650           ms/op
Client.existUser:existUser·p0.50      sample          1.628           ms/op
Client.existUser:existUser·p0.90      sample          2.249           ms/op
Client.existUser:existUser·p0.95      sample          2.474           ms/op
Client.existUser:existUser·p0.99      sample          3.338           ms/op
Client.existUser:existUser·p0.999     sample          9.208           ms/op
Client.existUser:existUser·p0.9999    sample          9.311           ms/op
Client.existUser:existUser·p1.00      sample          9.339           ms/op
Client.getUser                        sample   9881   3.238 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          0.916           ms/op
Client.getUser:getUser·p0.50          sample          3.170           ms/op
Client.getUser:getUser·p0.90          sample          4.157           ms/op
Client.getUser:getUser·p0.95          sample          4.529           ms/op
Client.getUser:getUser·p0.99          sample          5.572           ms/op
Client.getUser:getUser·p0.999         sample          6.056           ms/op
Client.getUser:getUser·p0.9999        sample          7.930           ms/op
Client.getUser:getUser·p1.00          sample          7.930           ms/op
Client.listUser                       sample   3663   8.722 ± 0.148   ms/op
Client.listUser:listUser·p0.00        sample          2.638           ms/op
Client.listUser:listUser·p0.50        sample          8.258           ms/op
Client.listUser:listUser·p0.90        sample         12.157           ms/op
Client.listUser:listUser·p0.95        sample         14.251           ms/op
Client.listUser:listUser·p0.99        sample         17.727           ms/op
Client.listUser:listUser·p0.999       sample         20.689           ms/op
Client.listUser:listUser·p0.9999      sample         22.741           ms/op
Client.listUser:listUser·p1.00        sample         22.741           ms/op
