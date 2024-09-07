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
# Warmup Iteration   1: 1.769 ops/ms
Iteration   1: 6.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.209 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.174 ops/ms
Iteration   1: 12.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.133 ops/ms


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
# Warmup Iteration   1: 5.281 ops/ms
Iteration   1: 12.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.907 ops/ms


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
# Warmup Iteration   1: 5.588 ops/ms
Iteration   1: 9.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.613 ops/ms


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
# Warmup Iteration   1: 3.475 ±(99.9%) 0.059 ms/op
Iteration   1: 1.980 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.980 ms/op


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
# Warmup Iteration   1: 3.290 ±(99.9%) 0.061 ms/op
Iteration   1: 1.717 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.717 ms/op


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
# Warmup Iteration   1: 3.270 ±(99.9%) 0.050 ms/op
Iteration   1: 2.015 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.015 ms/op


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
# Warmup Iteration   1: 4.574 ±(99.9%) 0.097 ms/op
Iteration   1: 3.668 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.668 ms/op


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
# Warmup Iteration   1: 3.614 ±(99.9%) 0.082 ms/op
Iteration   1: 2.194 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.718 ms/op
                 createUser·p0.50:   2.083 ms/op
                 createUser·p0.90:   2.757 ms/op
                 createUser·p0.95:   2.966 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  14.533 ms/op
                 createUser·p0.9999: 15.114 ms/op
                 createUser·p1.00:   15.204 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14996
  mean =      2.194 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 267 
    [ 1.250,  2.500) = 11662 
    [ 2.500,  3.750) = 2758 
    [ 3.750,  5.000) = 112 
    [ 5.000,  6.250) = 97 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      2.083 ms/op
     p(90.0000) =      2.757 ms/op
     p(95.0000) =      2.966 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     14.533 ms/op
     p(99.9900) =     15.114 ms/op
     p(99.9990) =     15.204 ms/op
     p(99.9999) =     15.204 ms/op
    p(100.0000) =     15.204 ms/op


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
# Warmup Iteration   1: 3.035 ±(99.9%) 0.073 ms/op
Iteration   1: 2.004 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.644 ms/op
                 existUser·p0.50:   1.966 ms/op
                 existUser·p0.90:   2.413 ms/op
                 existUser·p0.95:   2.564 ms/op
                 existUser·p0.99:   3.594 ms/op
                 existUser·p0.999:  11.781 ms/op
                 existUser·p0.9999: 12.493 ms/op
                 existUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15948
  mean =      2.004 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 333 
    [ 1.250,  2.500) = 14562 
    [ 2.500,  3.750) = 900 
    [ 3.750,  5.000) = 87 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      1.966 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.564 ms/op
     p(99.0000) =      3.594 ms/op
     p(99.9000) =     11.781 ms/op
     p(99.9900) =     12.493 ms/op
     p(99.9990) =     12.747 ms/op
     p(99.9999) =     12.747 ms/op
    p(100.0000) =     12.747 ms/op


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
# Warmup Iteration   1: 3.375 ±(99.9%) 0.085 ms/op
Iteration   1: 1.977 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.659 ms/op
                 getUser·p0.50:   1.810 ms/op
                 getUser·p0.90:   2.556 ms/op
                 getUser·p0.95:   2.806 ms/op
                 getUser·p0.99:   4.039 ms/op
                 getUser·p0.999:  13.304 ms/op
                 getUser·p0.9999: 13.448 ms/op
                 getUser·p1.00:   13.550 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16200
  mean =      1.977 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 203 
    [ 1.250,  2.500) = 14124 
    [ 2.500,  3.750) = 1689 
    [ 3.750,  5.000) = 117 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.806 ms/op
     p(99.0000) =      4.039 ms/op
     p(99.9000) =     13.304 ms/op
     p(99.9900) =     13.448 ms/op
     p(99.9990) =     13.550 ms/op
     p(99.9999) =     13.550 ms/op
    p(100.0000) =     13.550 ms/op


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
# Warmup Iteration   1: 4.377 ±(99.9%) 0.123 ms/op
Iteration   1: 2.984 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.814 ms/op
                 listUser·p0.50:   2.851 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.153 ms/op
                 listUser·p0.99:   4.760 ms/op
                 listUser·p0.999:  6.231 ms/op
                 listUser·p0.9999: 6.341 ms/op
                 listUser·p1.00:   6.341 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10716
  mean =      2.984 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 3 
    [1.000, 1.500) = 2 
    [1.500, 2.000) = 34 
    [2.000, 2.500) = 938 
    [2.500, 3.000) = 6416 
    [3.000, 3.500) = 1812 
    [3.500, 4.000) = 724 
    [4.000, 4.500) = 573 
    [4.500, 5.000) = 136 
    [5.000, 5.500) = 25 
    [5.500, 6.000) = 16 
    [6.000, 6.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =      6.231 ms/op
     p(99.9900) =      6.341 ms/op
     p(99.9990) =      6.341 ms/op
     p(99.9999) =      6.341 ms/op
    p(100.0000) =      6.341 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.209          ops/ms
ClientSimple.existUser                       thrpt         12.133          ops/ms
ClientSimple.getUser                         thrpt         12.907          ops/ms
ClientSimple.listUser                        thrpt          9.613          ops/ms
ClientSimple.createUser                       avgt          1.980           ms/op
ClientSimple.existUser                        avgt          1.717           ms/op
ClientSimple.getUser                          avgt          2.015           ms/op
ClientSimple.listUser                         avgt          3.668           ms/op
ClientSimple.createUser                     sample  14996   2.194 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.718           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.083           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.757           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.966           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.726           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.533           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.114           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.204           ms/op
ClientSimple.existUser                      sample  15948   2.004 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.644           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.966           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.413           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.594           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.781           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.493           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.747           ms/op
ClientSimple.getUser                        sample  16200   1.977 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.659           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.810           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.556           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.806           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.039           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.304           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.448           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.550           ms/op
ClientSimple.listUser                       sample  10716   2.984 ± 0.018   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.814           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.851           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.875           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.153           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.760           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.231           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.341           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.341           ms/op

Benchmark result is saved to 1725689601759.json
