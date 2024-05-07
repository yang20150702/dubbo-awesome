# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.474 ops/ms
Iteration   1: 6.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.150 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.855 ops/ms
Iteration   1: 12.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.727 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.180 ops/ms
Iteration   1: 12.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.554 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.900 ops/ms
Iteration   1: 8.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.959 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.899 ±(99.9%) 0.075 ms/op
Iteration   1: 1.971 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.971 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.097 ±(99.9%) 0.090 ms/op
Iteration   1: 1.959 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.959 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.124 ±(99.9%) 0.060 ms/op
Iteration   1: 2.342 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.342 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.597 ±(99.9%) 0.100 ms/op
Iteration   1: 3.701 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.701 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.521 ±(99.9%) 0.149 ms/op
Iteration   1: 2.061 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.620 ms/op
                 createUser·p0.50:   1.948 ms/op
                 createUser·p0.90:   2.499 ms/op
                 createUser·p0.95:   2.732 ms/op
                 createUser·p0.99:   4.274 ms/op
                 createUser·p0.999:  19.673 ms/op
                 createUser·p0.9999: 22.020 ms/op
                 createUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15623
  mean =      2.061 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14063 
    [ 2.500,  5.000) = 1433 
    [ 5.000,  7.500) = 63 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.620 ms/op
     p(50.0000) =      1.948 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.732 ms/op
     p(99.0000) =      4.274 ms/op
     p(99.9000) =     19.673 ms/op
     p(99.9900) =     22.020 ms/op
     p(99.9990) =     22.020 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.209 ±(99.9%) 0.079 ms/op
Iteration   1: 1.976 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.565 ms/op
                 existUser·p0.50:   1.884 ms/op
                 existUser·p0.90:   2.486 ms/op
                 existUser·p0.95:   2.642 ms/op
                 existUser·p0.99:   3.659 ms/op
                 existUser·p0.999:  16.250 ms/op
                 existUser·p0.9999: 16.941 ms/op
                 existUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16189
  mean =      1.976 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 314 
    [ 1.250,  2.500) = 14334 
    [ 2.500,  3.750) = 1381 
    [ 3.750,  5.000) = 83 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      3.659 ms/op
     p(99.9000) =     16.250 ms/op
     p(99.9900) =     16.941 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.080 ±(99.9%) 0.074 ms/op
Iteration   1: 2.145 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.674 ms/op
                 getUser·p0.50:   2.032 ms/op
                 getUser·p0.90:   2.687 ms/op
                 getUser·p0.95:   2.863 ms/op
                 getUser·p0.99:   5.136 ms/op
                 getUser·p0.999:  12.847 ms/op
                 getUser·p0.9999: 13.100 ms/op
                 getUser·p1.00:   13.156 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14909
  mean =      2.145 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 166 
    [ 1.250,  2.500) = 11876 
    [ 2.500,  3.750) = 2569 
    [ 3.750,  5.000) = 118 
    [ 5.000,  6.250) = 143 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      2.032 ms/op
     p(90.0000) =      2.687 ms/op
     p(95.0000) =      2.863 ms/op
     p(99.0000) =      5.136 ms/op
     p(99.9000) =     12.847 ms/op
     p(99.9900) =     13.100 ms/op
     p(99.9990) =     13.156 ms/op
     p(99.9999) =     13.156 ms/op
    p(100.0000) =     13.156 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.356 ±(99.9%) 0.163 ms/op
Iteration   1: 3.607 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   1.462 ms/op
                 listUser·p0.50:   3.469 ms/op
                 listUser·p0.90:   4.782 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   7.351 ms/op
                 listUser·p0.999:  15.405 ms/op
                 listUser·p0.9999: 16.695 ms/op
                 listUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8861
  mean =      3.607 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 669 
    [ 2.500,  3.750) = 5082 
    [ 3.750,  5.000) = 2428 
    [ 5.000,  6.250) = 540 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.462 ms/op
     p(50.0000) =      3.469 ms/op
     p(90.0000) =      4.782 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      7.351 ms/op
     p(99.9000) =     15.405 ms/op
     p(99.9900) =     16.695 ms/op
     p(99.9990) =     16.695 ms/op
     p(99.9999) =     16.695 ms/op
    p(100.0000) =     16.695 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.150          ops/ms
ClientSimple.existUser                       thrpt         12.727          ops/ms
ClientSimple.getUser                         thrpt         12.554          ops/ms
ClientSimple.listUser                        thrpt          8.959          ops/ms
ClientSimple.createUser                       avgt          1.971           ms/op
ClientSimple.existUser                        avgt          1.959           ms/op
ClientSimple.getUser                          avgt          2.342           ms/op
ClientSimple.listUser                         avgt          3.701           ms/op
ClientSimple.createUser                     sample  15623   2.061 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.620           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.948           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.499           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.732           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.274           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.673           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.020           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.020           ms/op
ClientSimple.existUser                      sample  16189   1.976 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.565           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.884           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.486           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.642           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.659           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.250           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.941           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.941           ms/op
ClientSimple.getUser                        sample  14909   2.145 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.674           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.032           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.687           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.863           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.136           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.847           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.100           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.156           ms/op
ClientSimple.listUser                       sample   8861   3.607 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.462           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.469           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.782           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.341           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.351           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.405           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.695           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.695           ms/op

Benchmark result is saved to 1715105505540.json
