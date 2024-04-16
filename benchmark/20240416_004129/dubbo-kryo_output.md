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
# Warmup Iteration   1: 1.563 ops/ms
Iteration   1: 6.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.661 ops/ms


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
# Warmup Iteration   1: 6.364 ops/ms
Iteration   1: 12.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.587 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.683 ops/ms
Iteration   1: 13.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.707 ops/ms


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
# Warmup Iteration   1: 4.324 ops/ms
Iteration   1: 7.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.699 ops/ms


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
# Warmup Iteration   1: 4.294 ±(99.9%) 0.083 ms/op
Iteration   1: 2.529 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.529 ms/op


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
# Warmup Iteration   1: 2.827 ±(99.9%) 0.045 ms/op
Iteration   1: 1.869 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.869 ms/op


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
# Warmup Iteration   1: 3.517 ±(99.9%) 0.068 ms/op
Iteration   1: 2.292 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.292 ms/op


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
# Warmup Iteration   1: 4.580 ±(99.9%) 0.098 ms/op
Iteration   1: 3.671 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.671 ms/op


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
# Warmup Iteration   1: 3.831 ±(99.9%) 0.111 ms/op
Iteration   1: 2.141 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.020 ms/op
                 createUser·p0.50:   1.970 ms/op
                 createUser·p0.90:   2.654 ms/op
                 createUser·p0.95:   3.023 ms/op
                 createUser·p0.99:   4.817 ms/op
                 createUser·p0.999:  13.631 ms/op
                 createUser·p0.9999: 14.336 ms/op
                 createUser·p1.00:   14.729 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15004
  mean =      2.141 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 12905 
    [ 2.500,  3.750) = 1632 
    [ 3.750,  5.000) = 287 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.020 ms/op
     p(50.0000) =      1.970 ms/op
     p(90.0000) =      2.654 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      4.817 ms/op
     p(99.9000) =     13.631 ms/op
     p(99.9900) =     14.336 ms/op
     p(99.9990) =     14.729 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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
# Warmup Iteration   1: 2.878 ±(99.9%) 0.060 ms/op
Iteration   1: 1.879 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.312 ms/op
                 existUser·p0.50:   1.722 ms/op
                 existUser·p0.90:   2.372 ms/op
                 existUser·p0.95:   2.642 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  16.843 ms/op
                 existUser·p0.9999: 16.941 ms/op
                 existUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17190
  mean =      1.879 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 193 
    [ 1.250,  2.500) = 15687 
    [ 2.500,  3.750) = 1177 
    [ 3.750,  5.000) = 3 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.312 ms/op
     p(50.0000) =      1.722 ms/op
     p(90.0000) =      2.372 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      3.535 ms/op
     p(99.9000) =     16.843 ms/op
     p(99.9900) =     16.941 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


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
# Warmup Iteration   1: 3.247 ±(99.9%) 0.082 ms/op
Iteration   1: 1.994 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.788 ms/op
                 getUser·p0.50:   1.905 ms/op
                 getUser·p0.90:   2.485 ms/op
                 getUser·p0.95:   2.654 ms/op
                 getUser·p0.99:   3.296 ms/op
                 getUser·p0.999:  14.615 ms/op
                 getUser·p0.9999: 15.250 ms/op
                 getUser·p1.00:   15.319 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16031
  mean =      1.994 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 14486 
    [ 2.500,  3.750) = 1349 
    [ 3.750,  5.000) = 16 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      1.905 ms/op
     p(90.0000) =      2.485 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      3.296 ms/op
     p(99.9000) =     14.615 ms/op
     p(99.9900) =     15.250 ms/op
     p(99.9990) =     15.319 ms/op
     p(99.9999) =     15.319 ms/op
    p(100.0000) =     15.319 ms/op


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
# Warmup Iteration   1: 4.387 ±(99.9%) 0.131 ms/op
Iteration   1: 3.298 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.473 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.185 ms/op
                 listUser·p0.999:  9.044 ms/op
                 listUser·p0.9999: 11.518 ms/op
                 listUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9747
  mean =      3.298 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 445 
    [ 2.500,  3.750) = 6585 
    [ 3.750,  5.000) = 2468 
    [ 5.000,  6.250) = 157 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.473 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     11.518 ms/op
     p(99.9990) =     11.518 ms/op
     p(99.9999) =     11.518 ms/op
    p(100.0000) =     11.518 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.661          ops/ms
ClientSimple.existUser                       thrpt         12.587          ops/ms
ClientSimple.getUser                         thrpt         13.707          ops/ms
ClientSimple.listUser                        thrpt          7.699          ops/ms
ClientSimple.createUser                       avgt          2.529           ms/op
ClientSimple.existUser                        avgt          1.869           ms/op
ClientSimple.getUser                          avgt          2.292           ms/op
ClientSimple.listUser                         avgt          3.671           ms/op
ClientSimple.createUser                     sample  15004   2.141 ± 0.023   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.020           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.970           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.654           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.023           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.817           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.631           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.336           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.729           ms/op
ClientSimple.existUser                      sample  17190   1.879 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.312           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.722           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.372           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.642           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.535           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.843           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.941           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.941           ms/op
ClientSimple.getUser                        sample  16031   1.994 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.788           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.905           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.485           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.654           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.296           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.615           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.250           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.319           ms/op
ClientSimple.listUser                       sample   9747   3.298 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.473           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.027           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.211           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.185           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.044           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.518           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.518           ms/op

Benchmark result is saved to 1713227824819.json
