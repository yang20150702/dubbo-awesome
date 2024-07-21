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
# Warmup Iteration   1: 1.626 ops/ms
Iteration   1: 6.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.920 ops/ms


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
# Warmup Iteration   1: 5.050 ops/ms
Iteration   1: 12.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.000 ops/ms


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
# Warmup Iteration   1: 4.785 ops/ms
Iteration   1: 12.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.060 ops/ms


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
# Warmup Iteration   1: 4.697 ops/ms
Iteration   1: 8.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.706 ops/ms


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
# Warmup Iteration   1: 4.120 ±(99.9%) 0.097 ms/op
Iteration   1: 2.628 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.628 ms/op


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
# Warmup Iteration   1: 3.705 ±(99.9%) 0.066 ms/op
Iteration   1: 2.250 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.250 ms/op


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
# Warmup Iteration   1: 3.289 ±(99.9%) 0.054 ms/op
Iteration   1: 2.127 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.127 ms/op


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
# Warmup Iteration   1: 5.572 ±(99.9%) 0.126 ms/op
Iteration   1: 3.526 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.526 ms/op


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
# Warmup Iteration   1: 3.629 ±(99.9%) 0.105 ms/op
Iteration   1: 2.026 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.736 ms/op
                 createUser·p0.50:   1.909 ms/op
                 createUser·p0.90:   2.605 ms/op
                 createUser·p0.95:   2.953 ms/op
                 createUser·p0.99:   4.589 ms/op
                 createUser·p0.999:  14.729 ms/op
                 createUser·p0.9999: 16.435 ms/op
                 createUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15778
  mean =      2.026 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 390 
    [ 1.250,  2.500) = 13331 
    [ 2.500,  3.750) = 1824 
    [ 3.750,  5.000) = 99 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.953 ms/op
     p(99.0000) =      4.589 ms/op
     p(99.9000) =     14.729 ms/op
     p(99.9900) =     16.435 ms/op
     p(99.9990) =     16.908 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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
# Warmup Iteration   1: 3.129 ±(99.9%) 0.081 ms/op
Iteration   1: 2.079 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.585 ms/op
                 existUser·p0.50:   2.028 ms/op
                 existUser·p0.90:   2.466 ms/op
                 existUser·p0.95:   2.630 ms/op
                 existUser·p0.99:   3.405 ms/op
                 existUser·p0.999:  14.444 ms/op
                 existUser·p0.9999: 15.064 ms/op
                 existUser·p1.00:   15.073 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15383
  mean =      2.079 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 241 
    [ 1.250,  2.500) = 13789 
    [ 2.500,  3.750) = 1215 
    [ 3.750,  5.000) = 69 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      2.028 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      3.405 ms/op
     p(99.9000) =     14.444 ms/op
     p(99.9900) =     15.064 ms/op
     p(99.9990) =     15.073 ms/op
     p(99.9999) =     15.073 ms/op
    p(100.0000) =     15.073 ms/op


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
# Warmup Iteration   1: 3.494 ±(99.9%) 0.101 ms/op
Iteration   1: 1.957 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   1.839 ms/op
                 getUser·p0.90:   2.417 ms/op
                 getUser·p0.95:   2.593 ms/op
                 getUser·p0.99:   3.233 ms/op
                 getUser·p0.999:  11.275 ms/op
                 getUser·p0.9999: 12.197 ms/op
                 getUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16366
  mean =      1.957 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 15085 
    [ 2.500,  3.750) = 1110 
    [ 3.750,  5.000) = 29 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      1.839 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.593 ms/op
     p(99.0000) =      3.233 ms/op
     p(99.9000) =     11.275 ms/op
     p(99.9900) =     12.197 ms/op
     p(99.9990) =     12.468 ms/op
     p(99.9999) =     12.468 ms/op
    p(100.0000) =     12.468 ms/op


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
# Warmup Iteration   1: 4.472 ±(99.9%) 0.132 ms/op
Iteration   1: 3.246 ±(99.9%) 0.053 ms/op
                 listUser·p0.00:   0.726 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.318 ms/op
                 listUser·p0.99:   5.972 ms/op
                 listUser·p0.999:  28.315 ms/op
                 listUser·p0.9999: 28.410 ms/op
                 listUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9898
  mean =      3.246 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 423 
    [ 2.500,  5.000) = 9226 
    [ 5.000,  7.500) = 180 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.318 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     28.315 ms/op
     p(99.9900) =     28.410 ms/op
     p(99.9990) =     28.410 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.920          ops/ms
ClientSimple.existUser                       thrpt         12.000          ops/ms
ClientSimple.getUser                         thrpt         12.060          ops/ms
ClientSimple.listUser                        thrpt          8.706          ops/ms
ClientSimple.createUser                       avgt          2.628           ms/op
ClientSimple.existUser                        avgt          2.250           ms/op
ClientSimple.getUser                          avgt          2.127           ms/op
ClientSimple.listUser                         avgt          3.526           ms/op
ClientSimple.createUser                     sample  15778   2.026 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.736           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.909           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.605           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.953           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.589           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.729           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.435           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.908           ms/op
ClientSimple.existUser                      sample  15383   2.079 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.585           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.028           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.466           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.630           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.405           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.444           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.064           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.073           ms/op
ClientSimple.getUser                        sample  16366   1.957 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.723           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.839           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.417           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.593           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.233           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.275           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.197           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.468           ms/op
ClientSimple.listUser                       sample   9898   3.246 ± 0.053   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.726           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.925           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.981           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.318           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.972           ms/op
ClientSimple.listUser:listUser·p0.999       sample         28.315           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.410           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.410           ms/op

Benchmark result is saved to 1721585471265.json
