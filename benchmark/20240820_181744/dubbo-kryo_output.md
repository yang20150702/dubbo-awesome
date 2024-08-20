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
# Warmup Iteration   1: 1.519 ops/ms
Iteration   1: 6.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.608 ops/ms


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
# Warmup Iteration   1: 5.683 ops/ms
Iteration   1: 12.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.678 ops/ms


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
# Warmup Iteration   1: 5.476 ops/ms
Iteration   1: 11.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.236 ops/ms


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
# Warmup Iteration   1: 4.555 ops/ms
Iteration   1: 8.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.082 ops/ms


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
# Warmup Iteration   1: 3.932 ±(99.9%) 0.072 ms/op
Iteration   1: 2.176 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.176 ms/op


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
# Warmup Iteration   1: 3.609 ±(99.9%) 0.066 ms/op
Iteration   1: 1.858 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.858 ms/op


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
# Warmup Iteration   1: 3.563 ±(99.9%) 0.114 ms/op
Iteration   1: 2.419 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.651 ±(99.9%) 0.085 ms/op
Iteration   1: 3.406 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.406 ms/op


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
# Warmup Iteration   1: 3.954 ±(99.9%) 0.100 ms/op
Iteration   1: 2.377 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   0.406 ms/op
                 createUser·p0.50:   2.183 ms/op
                 createUser·p0.90:   2.843 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   10.797 ms/op
                 createUser·p0.999:  32.455 ms/op
                 createUser·p0.9999: 35.007 ms/op
                 createUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13540
  mean =      2.377 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10151 
    [ 2.500,  5.000) = 3171 
    [ 5.000,  7.500) = 44 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.406 ms/op
     p(50.0000) =      2.183 ms/op
     p(90.0000) =      2.843 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =     10.797 ms/op
     p(99.9000) =     32.455 ms/op
     p(99.9900) =     35.007 ms/op
     p(99.9990) =     35.193 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 3.105 ±(99.9%) 0.089 ms/op
Iteration   1: 1.922 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.580 ms/op
                 existUser·p0.50:   1.704 ms/op
                 existUser·p0.90:   2.675 ms/op
                 existUser·p0.95:   2.867 ms/op
                 existUser·p0.99:   3.358 ms/op
                 existUser·p0.999:  9.978 ms/op
                 existUser·p0.9999: 10.158 ms/op
                 existUser·p1.00:   10.158 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16626
  mean =      1.922 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 41 
    [ 1.000,  2.000) = 11086 
    [ 2.000,  3.000) = 5051 
    [ 3.000,  4.000) = 379 
    [ 4.000,  5.000) = 31 
    [ 5.000,  6.000) = 6 
    [ 6.000,  7.000) = 0 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      1.704 ms/op
     p(90.0000) =      2.675 ms/op
     p(95.0000) =      2.867 ms/op
     p(99.0000) =      3.358 ms/op
     p(99.9000) =      9.978 ms/op
     p(99.9900) =     10.158 ms/op
     p(99.9990) =     10.158 ms/op
     p(99.9999) =     10.158 ms/op
    p(100.0000) =     10.158 ms/op


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
# Warmup Iteration   1: 3.813 ±(99.9%) 0.116 ms/op
Iteration   1: 2.308 ±(99.9%) 0.049 ms/op
                 getUser·p0.00:   0.689 ms/op
                 getUser·p0.50:   2.109 ms/op
                 getUser·p0.90:   2.834 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   5.308 ms/op
                 getUser·p0.999:  33.257 ms/op
                 getUser·p0.9999: 33.751 ms/op
                 getUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14029
  mean =      2.308 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10582 
    [ 2.500,  5.000) = 3245 
    [ 5.000,  7.500) = 134 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      2.109 ms/op
     p(90.0000) =      2.834 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     33.257 ms/op
     p(99.9900) =     33.751 ms/op
     p(99.9990) =     33.751 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 4.956 ±(99.9%) 0.143 ms/op
Iteration   1: 3.486 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   3.183 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   7.555 ms/op
                 listUser·p0.999:  15.023 ms/op
                 listUser·p0.9999: 16.466 ms/op
                 listUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9186
  mean =      3.486 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 400 
    [ 2.500,  3.750) = 6100 
    [ 3.750,  5.000) = 2245 
    [ 5.000,  6.250) = 225 
    [ 6.250,  7.500) = 114 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      7.555 ms/op
     p(99.9000) =     15.023 ms/op
     p(99.9900) =     16.466 ms/op
     p(99.9990) =     16.466 ms/op
     p(99.9999) =     16.466 ms/op
    p(100.0000) =     16.466 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.608          ops/ms
ClientSimple.existUser                       thrpt         12.678          ops/ms
ClientSimple.getUser                         thrpt         11.236          ops/ms
ClientSimple.listUser                        thrpt          8.082          ops/ms
ClientSimple.createUser                       avgt          2.176           ms/op
ClientSimple.existUser                        avgt          1.858           ms/op
ClientSimple.getUser                          avgt          2.419           ms/op
ClientSimple.listUser                         avgt          3.406           ms/op
ClientSimple.createUser                     sample  13540   2.377 ± 0.057   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.406           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.183           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.843           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.088           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.797           ms/op
ClientSimple.createUser:createUser·p0.999   sample         32.455           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         35.007           ms/op
ClientSimple.createUser:createUser·p1.00    sample         35.193           ms/op
ClientSimple.existUser                      sample  16626   1.922 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.580           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.704           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.675           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.867           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.358           ms/op
ClientSimple.existUser:existUser·p0.999     sample          9.978           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.158           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.158           ms/op
ClientSimple.getUser                        sample  14029   2.308 ± 0.049   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.689           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.109           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.834           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.105           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.308           ms/op
ClientSimple.getUser:getUser·p0.999         sample         33.257           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         33.751           ms/op
ClientSimple.getUser:getUser·p1.00          sample         33.751           ms/op
ClientSimple.listUser                       sample   9186   3.486 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.163           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.183           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.907           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.555           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.023           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.466           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.466           ms/op

Benchmark result is saved to 1724177600960.json
