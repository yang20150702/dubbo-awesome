# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.000 ops/ms
Iteration   1: 6.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.469 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.524 ops/ms
Iteration   1: 13.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.340 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.040 ops/ms
Iteration   1: 11.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.737 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.238 ops/ms
Iteration   1: 8.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.559 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.916 ±(99.9%) 0.076 ms/op
Iteration   1: 2.363 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.363 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.386 ±(99.9%) 0.046 ms/op
Iteration   1: 1.930 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.930 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.272 ±(99.9%) 0.051 ms/op
Iteration   1: 2.165 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.165 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.459 ±(99.9%) 0.106 ms/op
Iteration   1: 3.274 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.274 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.683 ±(99.9%) 0.085 ms/op
Iteration   1: 2.072 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.411 ms/op
                 createUser·p0.50:   1.901 ms/op
                 createUser·p0.90:   2.605 ms/op
                 createUser·p0.95:   2.858 ms/op
                 createUser·p0.99:   5.599 ms/op
                 createUser·p0.999:  14.986 ms/op
                 createUser·p0.9999: 15.319 ms/op
                 createUser·p1.00:   15.319 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15346
  mean =      2.072 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 367 
    [ 1.250,  2.500) = 12989 
    [ 2.500,  3.750) = 1711 
    [ 3.750,  5.000) = 96 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.411 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.858 ms/op
     p(99.0000) =      5.599 ms/op
     p(99.9000) =     14.986 ms/op
     p(99.9900) =     15.319 ms/op
     p(99.9990) =     15.319 ms/op
     p(99.9999) =     15.319 ms/op
    p(100.0000) =     15.319 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.103 ±(99.9%) 0.062 ms/op
Iteration   1: 1.771 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.474 ms/op
                 existUser·p0.50:   1.683 ms/op
                 existUser·p0.90:   2.126 ms/op
                 existUser·p0.95:   2.261 ms/op
                 existUser·p0.99:   3.838 ms/op
                 existUser·p0.999:  10.666 ms/op
                 existUser·p0.9999: 10.767 ms/op
                 existUser·p1.00:   10.781 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18609
  mean =      1.771 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 356 
    [ 1.250,  2.500) = 17754 
    [ 2.500,  3.750) = 304 
    [ 3.750,  5.000) = 119 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.474 ms/op
     p(50.0000) =      1.683 ms/op
     p(90.0000) =      2.126 ms/op
     p(95.0000) =      2.261 ms/op
     p(99.0000) =      3.838 ms/op
     p(99.9000) =     10.666 ms/op
     p(99.9900) =     10.767 ms/op
     p(99.9990) =     10.781 ms/op
     p(99.9999) =     10.781 ms/op
    p(100.0000) =     10.781 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.512 ±(99.9%) 0.112 ms/op
Iteration   1: 2.068 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.517 ms/op
                 getUser·p0.50:   1.978 ms/op
                 getUser·p0.90:   2.638 ms/op
                 getUser·p0.95:   2.802 ms/op
                 getUser·p0.99:   3.400 ms/op
                 getUser·p0.999:  16.277 ms/op
                 getUser·p0.9999: 18.096 ms/op
                 getUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15523
  mean =      2.068 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 213 
    [ 1.250,  2.500) = 13194 
    [ 2.500,  3.750) = 2006 
    [ 3.750,  5.000) = 27 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      1.978 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      3.400 ms/op
     p(99.9000) =     16.277 ms/op
     p(99.9900) =     18.096 ms/op
     p(99.9990) =     18.186 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.483 ±(99.9%) 0.122 ms/op
Iteration   1: 3.578 ±(99.9%) 0.052 ms/op
                 listUser·p0.00:   0.940 ms/op
                 listUser·p0.50:   3.404 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.954 ms/op
                 listUser·p0.999:  19.108 ms/op
                 listUser·p0.9999: 19.530 ms/op
                 listUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8938
  mean =      3.578 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 937 
    [ 2.500,  3.750) = 4496 
    [ 3.750,  5.000) = 3181 
    [ 5.000,  6.250) = 149 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 46 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      7.954 ms/op
     p(99.9000) =     19.108 ms/op
     p(99.9900) =     19.530 ms/op
     p(99.9990) =     19.530 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.469          ops/ms
ClientSimple.existUser                       thrpt         13.340          ops/ms
ClientSimple.getUser                         thrpt         11.737          ops/ms
ClientSimple.listUser                        thrpt          8.559          ops/ms
ClientSimple.createUser                       avgt          2.363           ms/op
ClientSimple.existUser                        avgt          1.930           ms/op
ClientSimple.getUser                          avgt          2.165           ms/op
ClientSimple.listUser                         avgt          3.274           ms/op
ClientSimple.createUser                     sample  15346   2.072 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.411           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.901           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.605           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.858           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.599           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.986           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.319           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.319           ms/op
ClientSimple.existUser                      sample  18609   1.771 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.474           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.683           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.126           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.261           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.838           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.666           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.767           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.781           ms/op
ClientSimple.getUser                        sample  15523   2.068 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.517           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.978           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.638           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.802           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.400           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.277           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.096           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.186           ms/op
ClientSimple.listUser                       sample   8938   3.578 ± 0.052   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.940           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.404           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.669           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.954           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.108           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.530           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.530           ms/op

Benchmark result is saved to 1724004702713.json
