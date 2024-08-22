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
# Warmup Iteration   1: 2.111 ops/ms
Iteration   1: 8.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.133 ops/ms


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
# Warmup Iteration   1: 5.834 ops/ms
Iteration   1: 14.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.977 ops/ms


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
# Warmup Iteration   1: 5.892 ops/ms
Iteration   1: 13.183 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.183 ops/ms


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
# Warmup Iteration   1: 4.914 ops/ms
Iteration   1: 8.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.550 ops/ms


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
# Warmup Iteration   1: 3.570 ±(99.9%) 0.063 ms/op
Iteration   1: 2.044 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.044 ms/op


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
# Warmup Iteration   1: 3.170 ±(99.9%) 0.059 ms/op
Iteration   1: 1.946 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.946 ms/op


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
# Warmup Iteration   1: 3.584 ±(99.9%) 0.070 ms/op
Iteration   1: 2.073 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.073 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.406 ±(99.9%) 0.101 ms/op
Iteration   1: 3.682 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.682 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.705 ±(99.9%) 0.092 ms/op
Iteration   1: 2.221 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.658 ms/op
                 createUser·p0.50:   2.054 ms/op
                 createUser·p0.90:   2.716 ms/op
                 createUser·p0.95:   2.920 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  19.436 ms/op
                 createUser·p0.9999: 30.616 ms/op
                 createUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14873
  mean =      2.221 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12042 
    [ 2.500,  5.000) = 2651 
    [ 5.000,  7.500) = 60 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      2.054 ms/op
     p(90.0000) =      2.716 ms/op
     p(95.0000) =      2.920 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     19.436 ms/op
     p(99.9900) =     30.616 ms/op
     p(99.9990) =     31.031 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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
# Warmup Iteration   1: 3.013 ±(99.9%) 0.066 ms/op
Iteration   1: 1.860 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.484 ms/op
                 existUser·p0.50:   1.729 ms/op
                 existUser·p0.90:   2.328 ms/op
                 existUser·p0.95:   2.597 ms/op
                 existUser·p0.99:   3.282 ms/op
                 existUser·p0.999:  28.103 ms/op
                 existUser·p0.9999: 28.625 ms/op
                 existUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17185
  mean =      1.860 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15986 
    [ 2.500,  5.000) = 1096 
    [ 5.000,  7.500) = 39 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      1.729 ms/op
     p(90.0000) =      2.328 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      3.282 ms/op
     p(99.9000) =     28.103 ms/op
     p(99.9900) =     28.625 ms/op
     p(99.9990) =     28.672 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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
# Warmup Iteration   1: 3.551 ±(99.9%) 0.115 ms/op
Iteration   1: 2.051 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   1.956 ms/op
                 getUser·p0.90:   2.540 ms/op
                 getUser·p0.95:   2.724 ms/op
                 getUser·p0.99:   4.251 ms/op
                 getUser·p0.999:  11.776 ms/op
                 getUser·p0.9999: 12.373 ms/op
                 getUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15609
  mean =      2.051 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 286 
    [ 1.250,  2.500) = 13484 
    [ 2.500,  3.750) = 1649 
    [ 3.750,  5.000) = 103 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.540 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      4.251 ms/op
     p(99.9000) =     11.776 ms/op
     p(99.9900) =     12.373 ms/op
     p(99.9990) =     12.419 ms/op
     p(99.9999) =     12.419 ms/op
    p(100.0000) =     12.419 ms/op


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
# Warmup Iteration   1: 4.235 ±(99.9%) 0.124 ms/op
Iteration   1: 3.255 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.602 ms/op
                 listUser·p0.50:   3.052 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.501 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.014 ms/op
                 listUser·p0.9999: 10.437 ms/op
                 listUser·p1.00:   10.437 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9830
  mean =      3.255 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 4 
    [ 1.000,  2.000) = 74 
    [ 2.000,  3.000) = 4480 
    [ 3.000,  4.000) = 3778 
    [ 4.000,  5.000) = 1313 
    [ 5.000,  6.000) = 119 
    [ 6.000,  7.000) = 47 
    [ 7.000,  8.000) = 2 
    [ 8.000,  9.000) = 2 
    [ 9.000, 10.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.501 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.014 ms/op
     p(99.9900) =     10.437 ms/op
     p(99.9990) =     10.437 ms/op
     p(99.9999) =     10.437 ms/op
    p(100.0000) =     10.437 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.133          ops/ms
ClientSimple.existUser                       thrpt         14.977          ops/ms
ClientSimple.getUser                         thrpt         13.183          ops/ms
ClientSimple.listUser                        thrpt          8.550          ops/ms
ClientSimple.createUser                       avgt          2.044           ms/op
ClientSimple.existUser                        avgt          1.946           ms/op
ClientSimple.getUser                          avgt          2.073           ms/op
ClientSimple.listUser                         avgt          3.682           ms/op
ClientSimple.createUser                     sample  14873   2.221 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.658           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.054           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.716           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.920           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.702           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.436           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.616           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.031           ms/op
ClientSimple.existUser                      sample  17185   1.860 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.484           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.729           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.328           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.597           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.282           ms/op
ClientSimple.existUser:existUser·p0.999     sample         28.103           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.625           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.672           ms/op
ClientSimple.getUser                        sample  15609   2.051 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.798           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.956           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.540           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.724           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.251           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.776           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.373           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.419           ms/op
ClientSimple.listUser                       sample   9830   3.255 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.602           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.052           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.170           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.501           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.669           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.014           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.437           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.437           ms/op

Benchmark result is saved to 1724287461025.json
