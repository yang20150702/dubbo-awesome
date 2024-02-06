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
# Warmup Iteration   1: 2.186 ops/ms
Iteration   1: 5.736 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.736 ops/ms


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
# Warmup Iteration   1: 5.182 ops/ms
Iteration   1: 12.286 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.286 ops/ms


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
# Warmup Iteration   1: 4.647 ops/ms
Iteration   1: 9.462 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.462 ops/ms


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
# Warmup Iteration   1: 1.902 ops/ms
Iteration   1: 3.962 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.962 ops/ms


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
# Warmup Iteration   1: 5.658 ±(99.9%) 0.066 ms/op
Iteration   1: 3.099 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.099 ms/op


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
# Warmup Iteration   1: 3.041 ±(99.9%) 0.028 ms/op
Iteration   1: 1.843 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.843 ms/op


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
# Warmup Iteration   1: 4.706 ±(99.9%) 0.055 ms/op
Iteration   1: 3.095 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.095 ms/op


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
# Warmup Iteration   1: 12.285 ±(99.9%) 0.199 ms/op
Iteration   1: 8.733 ±(99.9%) 0.097 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.733 ms/op


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
# Warmup Iteration   1: 5.057 ±(99.9%) 0.117 ms/op
Iteration   1: 2.767 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.946 ms/op
                 createUser·p0.99:   6.811 ms/op
                 createUser·p0.999:  13.857 ms/op
                 createUser·p0.9999: 13.992 ms/op
                 createUser·p1.00:   13.992 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11552
  mean =      2.767 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 5352 
    [ 2.500,  3.750) = 5339 
    [ 3.750,  5.000) = 624 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 80 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.946 ms/op
     p(99.0000) =      6.811 ms/op
     p(99.9000) =     13.857 ms/op
     p(99.9900) =     13.992 ms/op
     p(99.9990) =     13.992 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


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
# Warmup Iteration   1: 2.854 ±(99.9%) 0.056 ms/op
Iteration   1: 1.865 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.531 ms/op
                 existUser·p0.50:   1.702 ms/op
                 existUser·p0.90:   2.527 ms/op
                 existUser·p0.95:   2.748 ms/op
                 existUser·p0.99:   3.165 ms/op
                 existUser·p0.999:  22.793 ms/op
                 existUser·p0.9999: 23.532 ms/op
                 existUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17140
  mean =      1.865 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15328 
    [ 2.500,  5.000) = 1756 
    [ 5.000,  7.500) = 23 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      1.702 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      3.165 ms/op
     p(99.9000) =     22.793 ms/op
     p(99.9900) =     23.532 ms/op
     p(99.9990) =     23.626 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 4.639 ±(99.9%) 0.139 ms/op
Iteration   1: 2.913 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.902 ms/op
                 getUser·p0.50:   2.793 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   5.329 ms/op
                 getUser·p0.999:  8.282 ms/op
                 getUser·p0.9999: 9.431 ms/op
                 getUser·p1.00:   9.437 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11005
  mean =      2.913 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 3 
    [ 1.000,  2.000) = 304 
    [ 2.000,  3.000) = 6295 
    [ 3.000,  4.000) = 3902 
    [ 4.000,  5.000) = 374 
    [ 5.000,  6.000) = 33 
    [ 6.000,  7.000) = 77 
    [ 7.000,  8.000) = 3 
    [ 8.000,  9.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      2.793 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      5.329 ms/op
     p(99.9000) =      8.282 ms/op
     p(99.9900) =      9.431 ms/op
     p(99.9990) =      9.437 ms/op
     p(99.9999) =      9.437 ms/op
    p(100.0000) =      9.437 ms/op


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
# Warmup Iteration   1: 12.010 ±(99.9%) 0.423 ms/op
Iteration   1: 8.606 ±(99.9%) 0.113 ms/op
                 listUser·p0.00:   2.083 ms/op
                 listUser·p0.50:   8.323 ms/op
                 listUser·p0.90:   11.354 ms/op
                 listUser·p0.95:   12.321 ms/op
                 listUser·p0.99:   14.839 ms/op
                 listUser·p0.999:  17.212 ms/op
                 listUser·p0.9999: 18.317 ms/op
                 listUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3731
  mean =      8.606 ±(99.9%) 0.113 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1 
    [ 2.500,  3.750) = 11 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 334 
    [ 6.250,  7.500) = 798 
    [ 7.500,  8.750) = 1009 
    [ 8.750, 10.000) = 670 
    [10.000, 11.250) = 450 
    [11.250, 12.500) = 238 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.083 ms/op
     p(50.0000) =      8.323 ms/op
     p(90.0000) =     11.354 ms/op
     p(95.0000) =     12.321 ms/op
     p(99.0000) =     14.839 ms/op
     p(99.9000) =     17.212 ms/op
     p(99.9900) =     18.317 ms/op
     p(99.9990) =     18.317 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.736          ops/ms
Client.existUser                       thrpt         12.286          ops/ms
Client.getUser                         thrpt          9.462          ops/ms
Client.listUser                        thrpt          3.962          ops/ms
Client.createUser                       avgt          3.099           ms/op
Client.existUser                        avgt          1.843           ms/op
Client.getUser                          avgt          3.095           ms/op
Client.listUser                         avgt          8.733           ms/op
Client.createUser                     sample  11552   2.767 ± 0.031   ms/op
Client.createUser:createUser·p0.00    sample          0.907           ms/op
Client.createUser:createUser·p0.50    sample          2.535           ms/op
Client.createUser:createUser·p0.90    sample          3.441           ms/op
Client.createUser:createUser·p0.95    sample          3.946           ms/op
Client.createUser:createUser·p0.99    sample          6.811           ms/op
Client.createUser:createUser·p0.999   sample         13.857           ms/op
Client.createUser:createUser·p0.9999  sample         13.992           ms/op
Client.createUser:createUser·p1.00    sample         13.992           ms/op
Client.existUser                      sample  17140   1.865 ± 0.026   ms/op
Client.existUser:existUser·p0.00      sample          0.531           ms/op
Client.existUser:existUser·p0.50      sample          1.702           ms/op
Client.existUser:existUser·p0.90      sample          2.527           ms/op
Client.existUser:existUser·p0.95      sample          2.748           ms/op
Client.existUser:existUser·p0.99      sample          3.165           ms/op
Client.existUser:existUser·p0.999     sample         22.793           ms/op
Client.existUser:existUser·p0.9999    sample         23.532           ms/op
Client.existUser:existUser·p1.00      sample         23.626           ms/op
Client.getUser                        sample  11005   2.913 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          0.902           ms/op
Client.getUser:getUser·p0.50          sample          2.793           ms/op
Client.getUser:getUser·p0.90          sample          3.682           ms/op
Client.getUser:getUser·p0.95          sample          3.965           ms/op
Client.getUser:getUser·p0.99          sample          5.329           ms/op
Client.getUser:getUser·p0.999         sample          8.282           ms/op
Client.getUser:getUser·p0.9999        sample          9.431           ms/op
Client.getUser:getUser·p1.00          sample          9.437           ms/op
Client.listUser                       sample   3731   8.606 ± 0.113   ms/op
Client.listUser:listUser·p0.00        sample          2.083           ms/op
Client.listUser:listUser·p0.50        sample          8.323           ms/op
Client.listUser:listUser·p0.90        sample         11.354           ms/op
Client.listUser:listUser·p0.95        sample         12.321           ms/op
Client.listUser:listUser·p0.99        sample         14.839           ms/op
Client.listUser:listUser·p0.999       sample         17.212           ms/op
Client.listUser:listUser·p0.9999      sample         18.317           ms/op
Client.listUser:listUser·p1.00        sample         18.317           ms/op
