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
# Warmup Iteration   1: 1.787 ops/ms
Iteration   1: 7.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.019 ops/ms


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
# Warmup Iteration   1: 6.391 ops/ms
Iteration   1: 12.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.983 ops/ms


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
# Warmup Iteration   1: 5.826 ops/ms
Iteration   1: 12.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.995 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.335 ops/ms
Iteration   1: 7.988 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.988 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.186 ±(99.9%) 0.074 ms/op
Iteration   1: 2.419 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.419 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.429 ±(99.9%) 0.057 ms/op
Iteration   1: 1.721 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.721 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.418 ±(99.9%) 0.077 ms/op
Iteration   1: 1.812 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.812 ms/op


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
# Warmup Iteration   1: 4.744 ±(99.9%) 0.074 ms/op
Iteration   1: 3.397 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.397 ms/op


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
# Warmup Iteration   1: 4.064 ±(99.9%) 0.103 ms/op
Iteration   1: 2.050 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.617 ms/op
                 createUser·p0.50:   1.880 ms/op
                 createUser·p0.90:   2.343 ms/op
                 createUser·p0.95:   2.589 ms/op
                 createUser·p0.99:   5.248 ms/op
                 createUser·p0.999:  21.201 ms/op
                 createUser·p0.9999: 22.217 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15584
  mean =      2.050 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14564 
    [ 2.500,  5.000) = 862 
    [ 5.000,  7.500) = 25 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      1.880 ms/op
     p(90.0000) =      2.343 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      5.248 ms/op
     p(99.9000) =     21.201 ms/op
     p(99.9900) =     22.217 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.036 ±(99.9%) 0.066 ms/op
Iteration   1: 1.873 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.644 ms/op
                 existUser·p0.50:   1.778 ms/op
                 existUser·p0.90:   2.286 ms/op
                 existUser·p0.95:   2.470 ms/op
                 existUser·p0.99:   3.991 ms/op
                 existUser·p0.999:  12.287 ms/op
                 existUser·p0.9999: 12.522 ms/op
                 existUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17057
  mean =      1.873 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 521 
    [ 1.250,  2.500) = 15766 
    [ 2.500,  3.750) = 593 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      1.778 ms/op
     p(90.0000) =      2.286 ms/op
     p(95.0000) =      2.470 ms/op
     p(99.0000) =      3.991 ms/op
     p(99.9000) =     12.287 ms/op
     p(99.9900) =     12.522 ms/op
     p(99.9990) =     12.534 ms/op
     p(99.9999) =     12.534 ms/op
    p(100.0000) =     12.534 ms/op


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
# Warmup Iteration   1: 3.548 ±(99.9%) 0.102 ms/op
Iteration   1: 2.070 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.627 ms/op
                 getUser·p0.50:   2.028 ms/op
                 getUser·p0.90:   2.556 ms/op
                 getUser·p0.95:   2.802 ms/op
                 getUser·p0.99:   3.678 ms/op
                 getUser·p0.999:  11.895 ms/op
                 getUser·p0.9999: 12.281 ms/op
                 getUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15518
  mean =      2.070 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 295 
    [ 1.250,  2.500) = 13484 
    [ 2.500,  3.750) = 1608 
    [ 3.750,  5.000) = 47 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      2.028 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =     11.895 ms/op
     p(99.9900) =     12.281 ms/op
     p(99.9990) =     12.354 ms/op
     p(99.9999) =     12.354 ms/op
    p(100.0000) =     12.354 ms/op


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
# Warmup Iteration   1: 4.685 ±(99.9%) 0.136 ms/op
Iteration   1: 3.300 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   0.776 ms/op
                 listUser·p0.50:   3.158 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   6.096 ms/op
                 listUser·p0.999:  20.382 ms/op
                 listUser·p0.9999: 20.480 ms/op
                 listUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9720
  mean =      3.300 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1578 
    [ 2.500,  5.000) = 7836 
    [ 5.000,  7.500) = 272 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      6.096 ms/op
     p(99.9000) =     20.382 ms/op
     p(99.9900) =     20.480 ms/op
     p(99.9990) =     20.480 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.019          ops/ms
ClientSimple.existUser                       thrpt         12.983          ops/ms
ClientSimple.getUser                         thrpt         12.995          ops/ms
ClientSimple.listUser                        thrpt          7.988          ops/ms
ClientSimple.createUser                       avgt          2.419           ms/op
ClientSimple.existUser                        avgt          1.721           ms/op
ClientSimple.getUser                          avgt          1.812           ms/op
ClientSimple.listUser                         avgt          3.397           ms/op
ClientSimple.createUser                     sample  15584   2.050 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.617           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.880           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.343           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.589           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.248           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.201           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.217           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.217           ms/op
ClientSimple.existUser                      sample  17057   1.873 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.644           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.778           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.286           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.470           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.991           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.287           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.522           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.534           ms/op
ClientSimple.getUser                        sample  15518   2.070 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.627           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.028           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.556           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.802           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.678           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.895           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.281           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.354           ms/op
ClientSimple.listUser                       sample   9720   3.300 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.776           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.158           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.219           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.588           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.096           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.382           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.480           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.480           ms/op

Benchmark result is saved to 1721609054935.json
