# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.032 ops/ms
Iteration   1: 2.640 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.640 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.029 ops/ms
Iteration   1: 7.272 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.272 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.316 ops/ms
Iteration   1: 5.477 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.477 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.874 ops/ms
Iteration   1: 1.423 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.423 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 15.743 ±(99.9%) 0.201 ms/op
Iteration   1: 7.398 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.398 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.228 ±(99.9%) 0.065 ms/op
Iteration   1: 3.141 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.141 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.188 ±(99.9%) 0.116 ms/op
Iteration   1: 4.981 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.981 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 27.083 ±(99.9%) 0.547 ms/op
Iteration   1: 14.902 ±(99.9%) 0.050 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  14.902 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.467 ±(99.9%) 0.300 ms/op
Iteration   1: 5.076 ±(99.9%) 0.093 ms/op
                 createUser·p0.00:   1.559 ms/op
                 createUser·p0.50:   4.907 ms/op
                 createUser·p0.90:   6.603 ms/op
                 createUser·p0.95:   8.160 ms/op
                 createUser·p0.99:   16.335 ms/op
                 createUser·p0.999:  17.224 ms/op
                 createUser·p0.9999: 17.433 ms/op
                 createUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 6357
  mean =      5.076 ±(99.9%) 0.093 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 151 
    [ 2.500,  3.750) = 1566 
    [ 3.750,  5.000) = 1544 
    [ 5.000,  6.250) = 2252 
    [ 6.250,  7.500) = 467 
    [ 7.500,  8.750) = 122 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 70 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 64 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.559 ms/op
     p(50.0000) =      4.907 ms/op
     p(90.0000) =      6.603 ms/op
     p(95.0000) =      8.160 ms/op
     p(99.0000) =     16.335 ms/op
     p(99.9000) =     17.224 ms/op
     p(99.9900) =     17.433 ms/op
     p(99.9990) =     17.433 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.869 ±(99.9%) 0.200 ms/op
Iteration   1: 2.906 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.589 ms/op
                 existUser·p0.50:   2.666 ms/op
                 existUser·p0.90:   3.353 ms/op
                 existUser·p0.95:   3.971 ms/op
                 existUser·p0.99:   10.533 ms/op
                 existUser·p0.999:  12.954 ms/op
                 existUser·p0.9999: 14.362 ms/op
                 existUser·p1.00:   14.369 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 11104
  mean =      2.906 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 1695 
    [ 2.500,  3.750) = 8724 
    [ 3.750,  5.000) = 270 
    [ 5.000,  6.250) = 113 
    [ 6.250,  7.500) = 105 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      2.666 ms/op
     p(90.0000) =      3.353 ms/op
     p(95.0000) =      3.971 ms/op
     p(99.0000) =     10.533 ms/op
     p(99.9000) =     12.954 ms/op
     p(99.9900) =     14.362 ms/op
     p(99.9990) =     14.369 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 8.735 ±(99.9%) 0.324 ms/op
Iteration   1: 4.388 ±(99.9%) 0.046 ms/op
                 getUser·p0.00:   1.714 ms/op
                 getUser·p0.50:   4.301 ms/op
                 getUser·p0.90:   5.292 ms/op
                 getUser·p0.95:   5.669 ms/op
                 getUser·p0.99:   9.519 ms/op
                 getUser·p0.999:  15.319 ms/op
                 getUser·p0.9999: 19.104 ms/op
                 getUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7455
  mean =      4.388 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 20 
    [ 2.500,  3.750) = 1587 
    [ 3.750,  5.000) = 4747 
    [ 5.000,  6.250) = 850 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.714 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      5.292 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      9.519 ms/op
     p(99.9000) =     15.319 ms/op
     p(99.9900) =     19.104 ms/op
     p(99.9990) =     19.104 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 24.860 ±(99.9%) 0.952 ms/op
Iteration   1: 16.602 ±(99.9%) 0.311 ms/op
                 listUser·p0.00:   8.143 ms/op
                 listUser·p0.50:   16.777 ms/op
                 listUser·p0.90:   19.897 ms/op
                 listUser·p0.95:   26.542 ms/op
                 listUser·p0.99:   34.126 ms/op
                 listUser·p0.999:  38.522 ms/op
                 listUser·p0.9999: 39.191 ms/op
                 listUser·p1.00:   39.191 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1927
  mean =     16.602 ±(99.9%) 0.311 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 231 
    [12.500, 15.000) = 391 
    [15.000, 17.500) = 841 
    [17.500, 20.000) = 265 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      8.143 ms/op
     p(50.0000) =     16.777 ms/op
     p(90.0000) =     19.897 ms/op
     p(95.0000) =     26.542 ms/op
     p(99.0000) =     34.126 ms/op
     p(99.9000) =     38.522 ms/op
     p(99.9900) =     39.191 ms/op
     p(99.9990) =     39.191 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          2.640          ops/ms
Client.existUser                       thrpt          7.272          ops/ms
Client.getUser                         thrpt          5.477          ops/ms
Client.listUser                        thrpt          1.423          ops/ms
Client.createUser                       avgt          7.398           ms/op
Client.existUser                        avgt          3.141           ms/op
Client.getUser                          avgt          4.981           ms/op
Client.listUser                         avgt         14.902           ms/op
Client.createUser                     sample   6357   5.076 ± 0.093   ms/op
Client.createUser:createUser·p0.00    sample          1.559           ms/op
Client.createUser:createUser·p0.50    sample          4.907           ms/op
Client.createUser:createUser·p0.90    sample          6.603           ms/op
Client.createUser:createUser·p0.95    sample          8.160           ms/op
Client.createUser:createUser·p0.99    sample         16.335           ms/op
Client.createUser:createUser·p0.999   sample         17.224           ms/op
Client.createUser:createUser·p0.9999  sample         17.433           ms/op
Client.createUser:createUser·p1.00    sample         17.433           ms/op
Client.existUser                      sample  11104   2.906 ± 0.035   ms/op
Client.existUser:existUser·p0.00      sample          0.589           ms/op
Client.existUser:existUser·p0.50      sample          2.666           ms/op
Client.existUser:existUser·p0.90      sample          3.353           ms/op
Client.existUser:existUser·p0.95      sample          3.971           ms/op
Client.existUser:existUser·p0.99      sample         10.533           ms/op
Client.existUser:existUser·p0.999     sample         12.954           ms/op
Client.existUser:existUser·p0.9999    sample         14.362           ms/op
Client.existUser:existUser·p1.00      sample         14.369           ms/op
Client.getUser                        sample   7455   4.388 ± 0.046   ms/op
Client.getUser:getUser·p0.00          sample          1.714           ms/op
Client.getUser:getUser·p0.50          sample          4.301           ms/op
Client.getUser:getUser·p0.90          sample          5.292           ms/op
Client.getUser:getUser·p0.95          sample          5.669           ms/op
Client.getUser:getUser·p0.99          sample          9.519           ms/op
Client.getUser:getUser·p0.999         sample         15.319           ms/op
Client.getUser:getUser·p0.9999        sample         19.104           ms/op
Client.getUser:getUser·p1.00          sample         19.104           ms/op
Client.listUser                       sample   1927  16.602 ± 0.311   ms/op
Client.listUser:listUser·p0.00        sample          8.143           ms/op
Client.listUser:listUser·p0.50        sample         16.777           ms/op
Client.listUser:listUser·p0.90        sample         19.897           ms/op
Client.listUser:listUser·p0.95        sample         26.542           ms/op
Client.listUser:listUser·p0.99        sample         34.126           ms/op
Client.listUser:listUser·p0.999       sample         38.522           ms/op
Client.listUser:listUser·p0.9999      sample         39.191           ms/op
Client.listUser:listUser·p1.00        sample         39.191           ms/op
