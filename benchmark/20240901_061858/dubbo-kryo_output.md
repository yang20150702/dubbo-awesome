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
# Warmup Iteration   1: 1.842 ops/ms
Iteration   1: 6.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.992 ops/ms


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
# Warmup Iteration   1: 6.463 ops/ms
Iteration   1: 13.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.693 ops/ms


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
# Warmup Iteration   1: 5.915 ops/ms
Iteration   1: 12.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.899 ops/ms


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
# Warmup Iteration   1: 4.634 ops/ms
Iteration   1: 9.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.483 ops/ms


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
# Warmup Iteration   1: 4.179 ±(99.9%) 0.078 ms/op
Iteration   1: 2.166 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.166 ms/op


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
# Warmup Iteration   1: 3.280 ±(99.9%) 0.047 ms/op
Iteration   1: 1.853 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.853 ms/op


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
# Warmup Iteration   1: 3.102 ±(99.9%) 0.052 ms/op
Iteration   1: 2.079 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.079 ms/op


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
# Warmup Iteration   1: 4.176 ±(99.9%) 0.087 ms/op
Iteration   1: 3.679 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.679 ms/op


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
# Warmup Iteration   1: 3.332 ±(99.9%) 0.078 ms/op
Iteration   1: 2.149 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.890 ms/op
                 createUser·p0.50:   2.015 ms/op
                 createUser·p0.90:   2.523 ms/op
                 createUser·p0.95:   2.765 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  16.847 ms/op
                 createUser·p0.9999: 19.759 ms/op
                 createUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14866
  mean =      2.149 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 13166 
    [ 2.500,  3.750) = 1365 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 53 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      2.015 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.765 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     16.847 ms/op
     p(99.9900) =     19.759 ms/op
     p(99.9990) =     19.759 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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
# Warmup Iteration   1: 3.297 ±(99.9%) 0.098 ms/op
Iteration   1: 2.022 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.749 ms/op
                 existUser·p0.50:   1.946 ms/op
                 existUser·p0.90:   2.335 ms/op
                 existUser·p0.95:   2.519 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  14.189 ms/op
                 existUser·p0.9999: 15.663 ms/op
                 existUser·p1.00:   15.712 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15954
  mean =      2.022 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 215 
    [ 1.250,  2.500) = 14904 
    [ 2.500,  3.750) = 579 
    [ 3.750,  5.000) = 125 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      1.946 ms/op
     p(90.0000) =      2.335 ms/op
     p(95.0000) =      2.519 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =     14.189 ms/op
     p(99.9900) =     15.663 ms/op
     p(99.9990) =     15.712 ms/op
     p(99.9999) =     15.712 ms/op
    p(100.0000) =     15.712 ms/op


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
# Warmup Iteration   1: 3.140 ±(99.9%) 0.078 ms/op
Iteration   1: 2.080 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.351 ms/op
                 getUser·p0.50:   1.960 ms/op
                 getUser·p0.90:   2.580 ms/op
                 getUser·p0.95:   2.888 ms/op
                 getUser·p0.99:   3.700 ms/op
                 getUser·p0.999:  12.375 ms/op
                 getUser·p0.9999: 14.544 ms/op
                 getUser·p1.00:   14.615 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15359
  mean =      2.080 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 449 
    [ 1.250,  2.500) = 13068 
    [ 2.500,  3.750) = 1696 
    [ 3.750,  5.000) = 77 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.351 ms/op
     p(50.0000) =      1.960 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.888 ms/op
     p(99.0000) =      3.700 ms/op
     p(99.9000) =     12.375 ms/op
     p(99.9900) =     14.544 ms/op
     p(99.9990) =     14.615 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


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
# Warmup Iteration   1: 4.498 ±(99.9%) 0.147 ms/op
Iteration   1: 3.214 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   5.906 ms/op
                 listUser·p0.999:  9.519 ms/op
                 listUser·p0.9999: 9.552 ms/op
                 listUser·p1.00:   9.552 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9950
  mean =      3.214 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 9 
    [ 1.500,  2.000) = 117 
    [ 2.000,  2.500) = 319 
    [ 2.500,  3.000) = 4772 
    [ 3.000,  3.500) = 2151 
    [ 3.500,  4.000) = 1715 
    [ 4.000,  4.500) = 605 
    [ 4.500,  5.000) = 61 
    [ 5.000,  5.500) = 72 
    [ 5.500,  6.000) = 48 
    [ 6.000,  6.500) = 15 
    [ 6.500,  7.000) = 2 
    [ 7.000,  7.500) = 0 
    [ 7.500,  8.000) = 16 
    [ 8.000,  8.500) = 16 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.395 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =      9.519 ms/op
     p(99.9900) =      9.552 ms/op
     p(99.9990) =      9.552 ms/op
     p(99.9999) =      9.552 ms/op
    p(100.0000) =      9.552 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.992          ops/ms
ClientSimple.existUser                       thrpt         13.693          ops/ms
ClientSimple.getUser                         thrpt         12.899          ops/ms
ClientSimple.listUser                        thrpt          9.483          ops/ms
ClientSimple.createUser                       avgt          2.166           ms/op
ClientSimple.existUser                        avgt          1.853           ms/op
ClientSimple.getUser                          avgt          2.079           ms/op
ClientSimple.listUser                         avgt          3.679           ms/op
ClientSimple.createUser                     sample  14866   2.149 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.890           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.015           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.523           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.765           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.504           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.847           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.759           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.759           ms/op
ClientSimple.existUser                      sample  15954   2.022 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.749           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.946           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.335           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.519           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.604           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.189           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.663           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.712           ms/op
ClientSimple.getUser                        sample  15359   2.080 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.351           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.960           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.580           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.888           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.700           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.375           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.544           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.615           ms/op
ClientSimple.listUser                       sample   9950   3.214 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.395           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.978           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.949           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.906           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.519           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.552           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.552           ms/op

Benchmark result is saved to 1725171262528.json
