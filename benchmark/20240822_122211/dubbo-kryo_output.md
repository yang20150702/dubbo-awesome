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
# Warmup Iteration   1: 1.644 ops/ms
Iteration   1: 6.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.516 ops/ms


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
# Warmup Iteration   1: 5.810 ops/ms
Iteration   1: 12.766 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.766 ops/ms


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
# Warmup Iteration   1: 6.511 ops/ms
Iteration   1: 14.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.442 ops/ms


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
# Warmup Iteration   1: 6.224 ops/ms
Iteration   1: 9.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.190 ops/ms


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
# Warmup Iteration   1: 3.913 ±(99.9%) 0.078 ms/op
Iteration   1: 2.021 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.021 ms/op


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
# Warmup Iteration   1: 3.724 ±(99.9%) 0.052 ms/op
Iteration   1: 1.794 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.794 ms/op


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
# Warmup Iteration   1: 3.284 ±(99.9%) 0.070 ms/op
Iteration   1: 2.265 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.265 ms/op


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
# Warmup Iteration   1: 4.691 ±(99.9%) 0.102 ms/op
Iteration   1: 3.135 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.135 ms/op


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
# Warmup Iteration   1: 3.520 ±(99.9%) 0.096 ms/op
Iteration   1: 2.054 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.591 ms/op
                 createUser·p0.50:   1.917 ms/op
                 createUser·p0.90:   2.511 ms/op
                 createUser·p0.95:   2.683 ms/op
                 createUser·p0.99:   4.029 ms/op
                 createUser·p0.999:  12.456 ms/op
                 createUser·p0.9999: 12.665 ms/op
                 createUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15726
  mean =      2.054 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 13984 
    [ 2.500,  3.750) = 1403 
    [ 3.750,  5.000) = 98 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      1.917 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      4.029 ms/op
     p(99.9000) =     12.456 ms/op
     p(99.9900) =     12.665 ms/op
     p(99.9990) =     12.665 ms/op
     p(99.9999) =     12.665 ms/op
    p(100.0000) =     12.665 ms/op


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
# Warmup Iteration   1: 2.966 ±(99.9%) 0.065 ms/op
Iteration   1: 1.952 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.596 ms/op
                 existUser·p0.50:   1.802 ms/op
                 existUser·p0.90:   2.376 ms/op
                 existUser·p0.95:   2.526 ms/op
                 existUser·p0.99:   3.043 ms/op
                 existUser·p0.999:  23.560 ms/op
                 existUser·p0.9999: 24.436 ms/op
                 existUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16385
  mean =      1.952 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15490 
    [ 2.500,  5.000) = 801 
    [ 5.000,  7.500) = 30 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      1.802 ms/op
     p(90.0000) =      2.376 ms/op
     p(95.0000) =      2.526 ms/op
     p(99.0000) =      3.043 ms/op
     p(99.9000) =     23.560 ms/op
     p(99.9900) =     24.436 ms/op
     p(99.9990) =     24.478 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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
# Warmup Iteration   1: 3.130 ±(99.9%) 0.080 ms/op
Iteration   1: 2.030 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.465 ms/op
                 getUser·p0.50:   1.968 ms/op
                 getUser·p0.90:   2.433 ms/op
                 getUser·p0.95:   2.601 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  14.281 ms/op
                 getUser·p0.9999: 16.131 ms/op
                 getUser·p1.00:   16.187 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15742
  mean =      2.030 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 348 
    [ 1.250,  2.500) = 14190 
    [ 2.500,  3.750) = 991 
    [ 3.750,  5.000) = 98 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.465 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      4.661 ms/op
     p(99.9000) =     14.281 ms/op
     p(99.9900) =     16.131 ms/op
     p(99.9990) =     16.187 ms/op
     p(99.9999) =     16.187 ms/op
    p(100.0000) =     16.187 ms/op


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
# Warmup Iteration   1: 6.223 ±(99.9%) 0.205 ms/op
Iteration   1: 3.661 ±(99.9%) 0.060 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   3.465 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   9.516 ms/op
                 listUser·p0.999:  24.216 ms/op
                 listUser·p0.9999: 26.739 ms/op
                 listUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8758
  mean =      3.661 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 382 
    [ 2.500,  5.000) = 7893 
    [ 5.000,  7.500) = 377 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      9.516 ms/op
     p(99.9000) =     24.216 ms/op
     p(99.9900) =     26.739 ms/op
     p(99.9990) =     26.739 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.516          ops/ms
ClientSimple.existUser                       thrpt         12.766          ops/ms
ClientSimple.getUser                         thrpt         14.442          ops/ms
ClientSimple.listUser                        thrpt          9.190          ops/ms
ClientSimple.createUser                       avgt          2.021           ms/op
ClientSimple.existUser                        avgt          1.794           ms/op
ClientSimple.getUser                          avgt          2.265           ms/op
ClientSimple.listUser                         avgt          3.135           ms/op
ClientSimple.createUser                     sample  15726   2.054 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.591           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.917           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.511           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.683           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.029           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.456           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         12.665           ms/op
ClientSimple.createUser:createUser·p1.00    sample         12.665           ms/op
ClientSimple.existUser                      sample  16385   1.952 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.596           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.802           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.376           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.526           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.043           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.560           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.436           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.478           ms/op
ClientSimple.getUser                        sample  15742   2.030 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.465           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.968           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.433           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.661           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.281           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.131           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.187           ms/op
ClientSimple.listUser                       sample   8758   3.661 ± 0.060   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.106           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.465           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.399           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.177           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.516           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.216           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.739           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.739           ms/op

Benchmark result is saved to 1724329068799.json
