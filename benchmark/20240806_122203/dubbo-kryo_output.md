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
# Warmup Iteration   1: 1.543 ops/ms
Iteration   1: 5.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.812 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.112 ops/ms
Iteration   1: 12.368 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.368 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.915 ops/ms
Iteration   1: 12.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.098 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.773 ops/ms
Iteration   1: 7.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.939 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.158 ±(99.9%) 0.087 ms/op
Iteration   1: 2.460 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.460 ms/op


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
# Warmup Iteration   1: 3.597 ±(99.9%) 0.065 ms/op
Iteration   1: 1.928 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.928 ms/op


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
# Warmup Iteration   1: 3.577 ±(99.9%) 0.061 ms/op
Iteration   1: 2.217 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.217 ms/op


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
# Warmup Iteration   1: 4.555 ±(99.9%) 0.133 ms/op
Iteration   1: 3.388 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.388 ms/op


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
# Warmup Iteration   1: 4.168 ±(99.9%) 0.136 ms/op
Iteration   1: 2.487 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   2.273 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   6.562 ms/op
                 createUser·p0.999:  13.337 ms/op
                 createUser·p0.9999: 13.997 ms/op
                 createUser·p1.00:   14.123 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12856
  mean =      2.487 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 8502 
    [ 2.500,  3.750) = 3667 
    [ 3.750,  5.000) = 246 
    [ 5.000,  6.250) = 162 
    [ 6.250,  7.500) = 117 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      2.273 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     13.337 ms/op
     p(99.9900) =     13.997 ms/op
     p(99.9990) =     14.123 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


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
# Warmup Iteration   1: 3.206 ±(99.9%) 0.096 ms/op
Iteration   1: 2.133 ±(99.9%) 0.037 ms/op
                 existUser·p0.00:   0.647 ms/op
                 existUser·p0.50:   1.972 ms/op
                 existUser·p0.90:   2.560 ms/op
                 existUser·p0.95:   2.982 ms/op
                 existUser·p0.99:   5.335 ms/op
                 existUser·p0.999:  27.001 ms/op
                 existUser·p0.9999: 27.837 ms/op
                 existUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14974
  mean =      2.133 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13277 
    [ 2.500,  5.000) = 1479 
    [ 5.000,  7.500) = 152 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      1.972 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =      5.335 ms/op
     p(99.9000) =     27.001 ms/op
     p(99.9900) =     27.837 ms/op
     p(99.9990) =     27.886 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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
# Warmup Iteration   1: 3.320 ±(99.9%) 0.088 ms/op
Iteration   1: 2.057 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   1.931 ms/op
                 getUser·p0.90:   2.527 ms/op
                 getUser·p0.95:   2.666 ms/op
                 getUser·p0.99:   5.100 ms/op
                 getUser·p0.999:  17.200 ms/op
                 getUser·p0.9999: 17.709 ms/op
                 getUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15543
  mean =      2.057 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 97 
    [ 1.250,  2.500) = 13710 
    [ 2.500,  3.750) = 1500 
    [ 3.750,  5.000) = 79 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      1.931 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.666 ms/op
     p(99.0000) =      5.100 ms/op
     p(99.9000) =     17.200 ms/op
     p(99.9900) =     17.709 ms/op
     p(99.9990) =     17.727 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 4.759 ±(99.9%) 0.136 ms/op
Iteration   1: 3.381 ±(99.9%) 0.061 ms/op
                 listUser·p0.00:   1.270 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  31.311 ms/op
                 listUser·p0.9999: 31.621 ms/op
                 listUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9465
  mean =      3.381 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 685 
    [ 2.500,  5.000) = 8438 
    [ 5.000,  7.500) = 309 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     31.311 ms/op
     p(99.9900) =     31.621 ms/op
     p(99.9990) =     31.621 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.812          ops/ms
ClientSimple.existUser                       thrpt         12.368          ops/ms
ClientSimple.getUser                         thrpt         12.098          ops/ms
ClientSimple.listUser                        thrpt          7.939          ops/ms
ClientSimple.createUser                       avgt          2.460           ms/op
ClientSimple.existUser                        avgt          1.928           ms/op
ClientSimple.getUser                          avgt          2.217           ms/op
ClientSimple.listUser                         avgt          3.388           ms/op
ClientSimple.createUser                     sample  12856   2.487 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.754           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.273           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.097           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.707           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.562           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.337           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.997           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.123           ms/op
ClientSimple.existUser                      sample  14974   2.133 ± 0.037   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.647           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.972           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.560           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.982           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.335           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.001           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.837           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.886           ms/op
ClientSimple.getUser                        sample  15543   2.057 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.750           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.931           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.527           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.666           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.100           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.200           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.709           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.727           ms/op
ClientSimple.listUser                       sample   9465   3.381 ± 0.061   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.270           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.006           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.489           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.874           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.718           ms/op
ClientSimple.listUser:listUser·p0.999       sample         31.311           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         31.621           ms/op
ClientSimple.listUser:listUser·p1.00        sample         31.621           ms/op

Benchmark result is saved to 1722946659902.json
