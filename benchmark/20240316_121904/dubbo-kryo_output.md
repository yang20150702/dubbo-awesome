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
# Warmup Iteration   1: 1.740 ops/ms
Iteration   1: 6.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.966 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.384 ops/ms
Iteration   1: 13.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.582 ops/ms


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
# Warmup Iteration   1: 5.849 ops/ms
Iteration   1: 12.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.723 ops/ms


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
# Warmup Iteration   1: 5.055 ops/ms
Iteration   1: 9.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.074 ops/ms


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
# Warmup Iteration   1: 3.939 ±(99.9%) 0.083 ms/op
Iteration   1: 2.272 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.272 ms/op


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
# Warmup Iteration   1: 3.271 ±(99.9%) 0.060 ms/op
Iteration   1: 2.046 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.046 ms/op


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
# Warmup Iteration   1: 3.169 ±(99.9%) 0.059 ms/op
Iteration   1: 1.902 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.902 ms/op


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
# Warmup Iteration   1: 4.341 ±(99.9%) 0.079 ms/op
Iteration   1: 3.120 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.120 ms/op


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
# Warmup Iteration   1: 3.292 ±(99.9%) 0.078 ms/op
Iteration   1: 1.932 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.618 ms/op
                 createUser·p0.50:   1.776 ms/op
                 createUser·p0.90:   2.417 ms/op
                 createUser·p0.95:   2.703 ms/op
                 createUser·p0.99:   7.246 ms/op
                 createUser·p0.999:  12.885 ms/op
                 createUser·p0.9999: 13.600 ms/op
                 createUser·p1.00:   13.664 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16547
  mean =      1.932 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 252 
    [ 1.250,  2.500) = 14974 
    [ 2.500,  3.750) = 1053 
    [ 3.750,  5.000) = 63 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      1.776 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.703 ms/op
     p(99.0000) =      7.246 ms/op
     p(99.9000) =     12.885 ms/op
     p(99.9900) =     13.600 ms/op
     p(99.9990) =     13.664 ms/op
     p(99.9999) =     13.664 ms/op
    p(100.0000) =     13.664 ms/op


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
# Warmup Iteration   1: 3.047 ±(99.9%) 0.069 ms/op
Iteration   1: 1.806 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.239 ms/op
                 existUser·p0.50:   1.675 ms/op
                 existUser·p0.90:   2.355 ms/op
                 existUser·p0.95:   2.589 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  15.827 ms/op
                 existUser·p0.9999: 16.011 ms/op
                 existUser·p1.00:   16.024 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17697
  mean =      1.806 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 842 
    [ 1.250,  2.500) = 15736 
    [ 2.500,  3.750) = 944 
    [ 3.750,  5.000) = 92 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.239 ms/op
     p(50.0000) =      1.675 ms/op
     p(90.0000) =      2.355 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =     15.827 ms/op
     p(99.9900) =     16.011 ms/op
     p(99.9990) =     16.024 ms/op
     p(99.9999) =     16.024 ms/op
    p(100.0000) =     16.024 ms/op


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
# Warmup Iteration   1: 3.236 ±(99.9%) 0.075 ms/op
Iteration   1: 1.979 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.630 ms/op
                 getUser·p0.50:   1.802 ms/op
                 getUser·p0.90:   2.609 ms/op
                 getUser·p0.95:   2.840 ms/op
                 getUser·p0.99:   3.641 ms/op
                 getUser·p0.999:  12.529 ms/op
                 getUser·p0.9999: 12.889 ms/op
                 getUser·p1.00:   13.074 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16292
  mean =      1.979 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 369 
    [ 1.250,  2.500) = 13705 
    [ 2.500,  3.750) = 2062 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      1.802 ms/op
     p(90.0000) =      2.609 ms/op
     p(95.0000) =      2.840 ms/op
     p(99.0000) =      3.641 ms/op
     p(99.9000) =     12.529 ms/op
     p(99.9900) =     12.889 ms/op
     p(99.9990) =     13.074 ms/op
     p(99.9999) =     13.074 ms/op
    p(100.0000) =     13.074 ms/op


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
# Warmup Iteration   1: 4.201 ±(99.9%) 0.130 ms/op
Iteration   1: 3.518 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.417 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   6.363 ms/op
                 listUser·p0.999:  8.927 ms/op
                 listUser·p0.9999: 9.716 ms/op
                 listUser·p1.00:   9.716 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9110
  mean =      3.518 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 1 
    [ 1.500,  2.000) = 81 
    [ 2.000,  2.500) = 558 
    [ 2.500,  3.000) = 1833 
    [ 3.000,  3.500) = 1607 
    [ 3.500,  4.000) = 3212 
    [ 4.000,  4.500) = 1353 
    [ 4.500,  5.000) = 170 
    [ 5.000,  5.500) = 111 
    [ 5.500,  6.000) = 65 
    [ 6.000,  6.500) = 36 
    [ 6.500,  7.000) = 43 
    [ 7.000,  7.500) = 2 
    [ 7.500,  8.000) = 6 
    [ 8.000,  8.500) = 0 
    [ 8.500,  9.000) = 24 
    [ 9.000,  9.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.417 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.363 ms/op
     p(99.9000) =      8.927 ms/op
     p(99.9900) =      9.716 ms/op
     p(99.9990) =      9.716 ms/op
     p(99.9999) =      9.716 ms/op
    p(100.0000) =      9.716 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.966          ops/ms
ClientSimple.existUser                       thrpt         13.582          ops/ms
ClientSimple.getUser                         thrpt         12.723          ops/ms
ClientSimple.listUser                        thrpt          9.074          ops/ms
ClientSimple.createUser                       avgt          2.272           ms/op
ClientSimple.existUser                        avgt          2.046           ms/op
ClientSimple.getUser                          avgt          1.902           ms/op
ClientSimple.listUser                         avgt          3.120           ms/op
ClientSimple.createUser                     sample  16547   1.932 ± 0.023   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.618           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.776           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.417           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.703           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.246           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.885           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.600           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.664           ms/op
ClientSimple.existUser                      sample  17697   1.806 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.239           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.675           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.355           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.589           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.711           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.827           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.011           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.024           ms/op
ClientSimple.getUser                        sample  16292   1.979 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.630           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.802           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.609           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.840           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.641           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.529           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.889           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.074           ms/op
ClientSimple.listUser                       sample   9110   3.518 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.417           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.592           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.227           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.363           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.927           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.716           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.716           ms/op

Benchmark result is saved to 1710591292210.json
