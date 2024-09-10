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
# Warmup Iteration   1: 1.999 ops/ms
Iteration   1: 7.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.236 ops/ms


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
# Warmup Iteration   1: 6.691 ops/ms
Iteration   1: 13.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.857 ops/ms


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
# Warmup Iteration   1: 6.078 ops/ms
Iteration   1: 14.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.943 ops/ms


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
# Warmup Iteration   1: 5.458 ops/ms
Iteration   1: 8.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.628 ops/ms


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
# Warmup Iteration   1: 3.626 ±(99.9%) 0.055 ms/op
Iteration   1: 2.017 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.017 ms/op


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
# Warmup Iteration   1: 3.196 ±(99.9%) 0.071 ms/op
Iteration   1: 1.750 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.750 ms/op


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
# Warmup Iteration   1: 2.988 ±(99.9%) 0.044 ms/op
Iteration   1: 2.220 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.220 ms/op


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
# Warmup Iteration   1: 4.263 ±(99.9%) 0.081 ms/op
Iteration   1: 3.666 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.666 ms/op


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
# Warmup Iteration   1: 3.635 ±(99.9%) 0.088 ms/op
Iteration   1: 2.101 ±(99.9%) 0.138 ms/op
                 createUser·p0.00:   0.346 ms/op
                 createUser·p0.50:   1.765 ms/op
                 createUser·p0.90:   2.134 ms/op
                 createUser·p0.95:   2.298 ms/op
                 createUser·p0.99:   11.030 ms/op
                 createUser·p0.999:  110.494 ms/op
                 createUser·p0.9999: 117.503 ms/op
                 createUser·p1.00:   117.572 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15217
  mean =      2.101 ±(99.9%) 0.138 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 15121 
    [ 12.500,  25.000) = 64 
    [ 25.000,  37.500) = 0 
    [ 37.500,  50.000) = 0 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 23 
    [112.500, 125.000) = 9 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.346 ms/op
     p(50.0000) =      1.765 ms/op
     p(90.0000) =      2.134 ms/op
     p(95.0000) =      2.298 ms/op
     p(99.0000) =     11.030 ms/op
     p(99.9000) =    110.494 ms/op
     p(99.9900) =    117.503 ms/op
     p(99.9990) =    117.572 ms/op
     p(99.9999) =    117.572 ms/op
    p(100.0000) =    117.572 ms/op


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
# Warmup Iteration   1: 3.064 ±(99.9%) 0.086 ms/op
Iteration   1: 1.925 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.540 ms/op
                 existUser·p0.50:   1.907 ms/op
                 existUser·p0.90:   2.396 ms/op
                 existUser·p0.95:   2.515 ms/op
                 existUser·p0.99:   2.820 ms/op
                 existUser·p0.999:  13.156 ms/op
                 existUser·p0.9999: 13.277 ms/op
                 existUser·p1.00:   13.287 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16652
  mean =      1.925 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 711 
    [ 1.250,  2.500) = 15018 
    [ 2.500,  3.750) = 834 
    [ 3.750,  5.000) = 49 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      1.907 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.515 ms/op
     p(99.0000) =      2.820 ms/op
     p(99.9000) =     13.156 ms/op
     p(99.9900) =     13.277 ms/op
     p(99.9990) =     13.287 ms/op
     p(99.9999) =     13.287 ms/op
    p(100.0000) =     13.287 ms/op


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
# Warmup Iteration   1: 3.343 ±(99.9%) 0.081 ms/op
Iteration   1: 2.241 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.407 ms/op
                 getUser·p0.50:   2.101 ms/op
                 getUser·p0.90:   2.884 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  19.974 ms/op
                 getUser·p0.9999: 20.553 ms/op
                 getUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14440
  mean =      2.241 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10702 
    [ 2.500,  5.000) = 3674 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.407 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.884 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =     19.974 ms/op
     p(99.9900) =     20.553 ms/op
     p(99.9990) =     20.611 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 3.848 ±(99.9%) 0.111 ms/op
Iteration   1: 3.250 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   0.929 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.925 ms/op
                 listUser·p0.999:  12.108 ms/op
                 listUser·p0.9999: 12.239 ms/op
                 listUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9973
  mean =      3.250 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 465 
    [ 2.500,  3.750) = 7467 
    [ 3.750,  5.000) = 1796 
    [ 5.000,  6.250) = 158 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.925 ms/op
     p(99.9000) =     12.108 ms/op
     p(99.9900) =     12.239 ms/op
     p(99.9990) =     12.239 ms/op
     p(99.9999) =     12.239 ms/op
    p(100.0000) =     12.239 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           7.236          ops/ms
ClientSimple.existUser                       thrpt          13.857          ops/ms
ClientSimple.getUser                         thrpt          14.943          ops/ms
ClientSimple.listUser                        thrpt           8.628          ops/ms
ClientSimple.createUser                       avgt           2.017           ms/op
ClientSimple.existUser                        avgt           1.750           ms/op
ClientSimple.getUser                          avgt           2.220           ms/op
ClientSimple.listUser                         avgt           3.666           ms/op
ClientSimple.createUser                     sample  15217    2.101 ± 0.138   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.346           ms/op
ClientSimple.createUser:createUser·p0.50    sample           1.765           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.134           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.298           ms/op
ClientSimple.createUser:createUser·p0.99    sample          11.030           ms/op
ClientSimple.createUser:createUser·p0.999   sample         110.494           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         117.503           ms/op
ClientSimple.createUser:createUser·p1.00    sample         117.572           ms/op
ClientSimple.existUser                      sample  16652    1.925 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.540           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.907           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.396           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.515           ms/op
ClientSimple.existUser:existUser·p0.99      sample           2.820           ms/op
ClientSimple.existUser:existUser·p0.999     sample          13.156           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          13.277           ms/op
ClientSimple.existUser:existUser·p1.00      sample          13.287           ms/op
ClientSimple.getUser                        sample  14440    2.241 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.407           ms/op
ClientSimple.getUser:getUser·p0.50          sample           2.101           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.884           ms/op
ClientSimple.getUser:getUser·p0.95          sample           3.105           ms/op
ClientSimple.getUser:getUser·p0.99          sample           4.211           ms/op
ClientSimple.getUser:getUser·p0.999         sample          19.974           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          20.553           ms/op
ClientSimple.getUser:getUser·p1.00          sample          20.611           ms/op
ClientSimple.listUser                       sample   9973    3.250 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample           0.929           ms/op
ClientSimple.listUser:listUser·p0.50        sample           2.970           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.043           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.440           ms/op
ClientSimple.listUser:listUser·p0.99        sample           5.925           ms/op
ClientSimple.listUser:listUser·p0.999       sample          12.108           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          12.239           ms/op
ClientSimple.listUser:listUser·p1.00        sample          12.239           ms/op

Benchmark result is saved to 1725948869412.json
