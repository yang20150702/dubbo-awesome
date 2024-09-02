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
# Warmup Iteration   1: 1.740 ops/ms
Iteration   1: 6.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.916 ops/ms


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
# Warmup Iteration   1: 5.614 ops/ms
Iteration   1: 11.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.624 ops/ms


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
# Warmup Iteration   1: 5.491 ops/ms
Iteration   1: 12.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.940 ops/ms


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
# Warmup Iteration   1: 4.268 ops/ms
Iteration   1: 8.988 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.988 ops/ms


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
# Warmup Iteration   1: 3.225 ±(99.9%) 0.063 ms/op
Iteration   1: 2.338 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.338 ms/op


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
# Warmup Iteration   1: 3.388 ±(99.9%) 0.055 ms/op
Iteration   1: 1.903 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.903 ms/op


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
# Warmup Iteration   1: 3.313 ±(99.9%) 0.060 ms/op
Iteration   1: 1.988 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.988 ms/op


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
# Warmup Iteration   1: 4.486 ±(99.9%) 0.102 ms/op
Iteration   1: 3.323 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.323 ms/op


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
# Warmup Iteration   1: 3.481 ±(99.9%) 0.088 ms/op
Iteration   1: 2.290 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.462 ms/op
                 createUser·p0.50:   2.130 ms/op
                 createUser·p0.90:   2.862 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   9.214 ms/op
                 createUser·p0.999:  15.994 ms/op
                 createUser·p0.9999: 16.442 ms/op
                 createUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13952
  mean =      2.290 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 458 
    [ 1.250,  2.500) = 10256 
    [ 2.500,  3.750) = 2881 
    [ 3.750,  5.000) = 135 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      2.130 ms/op
     p(90.0000) =      2.862 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      9.214 ms/op
     p(99.9000) =     15.994 ms/op
     p(99.9900) =     16.442 ms/op
     p(99.9990) =     16.630 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


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
# Warmup Iteration   1: 2.967 ±(99.9%) 0.060 ms/op
Iteration   1: 2.021 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.412 ms/op
                 existUser·p0.50:   1.966 ms/op
                 existUser·p0.90:   2.445 ms/op
                 existUser·p0.95:   2.580 ms/op
                 existUser·p0.99:   3.101 ms/op
                 existUser·p0.999:  13.367 ms/op
                 existUser·p0.9999: 15.155 ms/op
                 existUser·p1.00:   15.155 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15798
  mean =      2.021 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 197 
    [ 1.250,  2.500) = 14497 
    [ 2.500,  3.750) = 1045 
    [ 3.750,  5.000) = 12 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.412 ms/op
     p(50.0000) =      1.966 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.580 ms/op
     p(99.0000) =      3.101 ms/op
     p(99.9000) =     13.367 ms/op
     p(99.9900) =     15.155 ms/op
     p(99.9990) =     15.155 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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
# Warmup Iteration   1: 3.310 ±(99.9%) 0.084 ms/op
Iteration   1: 2.046 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.579 ms/op
                 getUser·p0.50:   1.913 ms/op
                 getUser·p0.90:   2.535 ms/op
                 getUser·p0.95:   2.818 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  12.501 ms/op
                 getUser·p0.9999: 12.831 ms/op
                 getUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15634
  mean =      2.046 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 252 
    [ 1.250,  2.500) = 13661 
    [ 2.500,  3.750) = 1383 
    [ 3.750,  5.000) = 129 
    [ 5.000,  6.250) = 128 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      1.913 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     12.501 ms/op
     p(99.9900) =     12.831 ms/op
     p(99.9990) =     13.025 ms/op
     p(99.9999) =     13.025 ms/op
    p(100.0000) =     13.025 ms/op


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
# Warmup Iteration   1: 4.544 ±(99.9%) 0.115 ms/op
Iteration   1: 3.987 ±(99.9%) 0.058 ms/op
                 listUser·p0.00:   1.151 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.926 ms/op
                 listUser·p0.999:  25.951 ms/op
                 listUser·p0.9999: 26.378 ms/op
                 listUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8025
  mean =      3.987 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 271 
    [ 2.500,  5.000) = 7175 
    [ 5.000,  7.500) = 532 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.151 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      6.926 ms/op
     p(99.9000) =     25.951 ms/op
     p(99.9900) =     26.378 ms/op
     p(99.9990) =     26.378 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.916          ops/ms
ClientSimple.existUser                       thrpt         11.624          ops/ms
ClientSimple.getUser                         thrpt         12.940          ops/ms
ClientSimple.listUser                        thrpt          8.988          ops/ms
ClientSimple.createUser                       avgt          2.338           ms/op
ClientSimple.existUser                        avgt          1.903           ms/op
ClientSimple.getUser                          avgt          1.988           ms/op
ClientSimple.listUser                         avgt          3.323           ms/op
ClientSimple.createUser                     sample  13952   2.290 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.462           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.130           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.862           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.117           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.214           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.994           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.442           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.630           ms/op
ClientSimple.existUser                      sample  15798   2.021 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.412           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.966           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.445           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.580           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.101           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.367           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.155           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.155           ms/op
ClientSimple.getUser                        sample  15634   2.046 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.579           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.913           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.535           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.818           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.595           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.501           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.831           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.025           ms/op
ClientSimple.listUser                       sample   8025   3.987 ± 0.058   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.151           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.879           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.751           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.407           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.926           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.951           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.378           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.378           ms/op

Benchmark result is saved to 1725238024570.json
