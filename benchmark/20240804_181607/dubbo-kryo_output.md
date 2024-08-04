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
# Warmup Iteration   1: 1.784 ops/ms
Iteration   1: 6.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.760 ops/ms


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
# Warmup Iteration   1: 5.825 ops/ms
Iteration   1: 12.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.791 ops/ms


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
# Warmup Iteration   1: 5.282 ops/ms
Iteration   1: 12.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.412 ops/ms


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
# Warmup Iteration   1: 5.007 ops/ms
Iteration   1: 8.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.400 ops/ms


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
# Warmup Iteration   1: 4.528 ±(99.9%) 0.066 ms/op
Iteration   1: 2.260 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.260 ms/op


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
# Warmup Iteration   1: 3.258 ±(99.9%) 0.055 ms/op
Iteration   1: 1.977 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.977 ms/op


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
# Warmup Iteration   1: 2.982 ±(99.9%) 0.048 ms/op
Iteration   1: 1.853 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.468 ±(99.9%) 0.093 ms/op
Iteration   1: 3.560 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.560 ms/op


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
# Warmup Iteration   1: 3.654 ±(99.9%) 0.083 ms/op
Iteration   1: 2.103 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.689 ms/op
                 createUser·p0.50:   1.915 ms/op
                 createUser·p0.90:   2.433 ms/op
                 createUser·p0.95:   2.679 ms/op
                 createUser·p0.99:   9.159 ms/op
                 createUser·p0.999:  17.324 ms/op
                 createUser·p0.9999: 17.939 ms/op
                 createUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15311
  mean =      2.103 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 157 
    [ 1.250,  2.500) = 13860 
    [ 2.500,  3.750) = 986 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 71 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      1.915 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.679 ms/op
     p(99.0000) =      9.159 ms/op
     p(99.9000) =     17.324 ms/op
     p(99.9900) =     17.939 ms/op
     p(99.9990) =     17.957 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 2.766 ±(99.9%) 0.066 ms/op
Iteration   1: 2.101 ±(99.9%) 0.119 ms/op
                 existUser·p0.00:   0.365 ms/op
                 existUser·p0.50:   1.815 ms/op
                 existUser·p0.90:   2.322 ms/op
                 existUser·p0.95:   2.499 ms/op
                 existUser·p0.99:   3.274 ms/op
                 existUser·p0.999:  85.763 ms/op
                 existUser·p0.9999: 121.456 ms/op
                 existUser·p1.00:   122.946 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14939
  mean =      2.101 ±(99.9%) 0.119 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 14878 
    [ 12.500,  25.000) = 4 
    [ 25.000,  37.500) = 7 
    [ 37.500,  50.000) = 10 
    [ 50.000,  62.500) = 7 
    [ 62.500,  75.000) = 13 
    [ 75.000,  87.500) = 6 
    [ 87.500, 100.000) = 7 
    [100.000, 112.500) = 3 
    [112.500, 125.000) = 4 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.365 ms/op
     p(50.0000) =      1.815 ms/op
     p(90.0000) =      2.322 ms/op
     p(95.0000) =      2.499 ms/op
     p(99.0000) =      3.274 ms/op
     p(99.9000) =     85.763 ms/op
     p(99.9900) =    121.456 ms/op
     p(99.9990) =    122.946 ms/op
     p(99.9999) =    122.946 ms/op
    p(100.0000) =    122.946 ms/op


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
# Warmup Iteration   1: 3.372 ±(99.9%) 0.079 ms/op
Iteration   1: 1.809 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   1.765 ms/op
                 getUser·p0.90:   2.073 ms/op
                 getUser·p0.95:   2.281 ms/op
                 getUser·p0.99:   2.753 ms/op
                 getUser·p0.999:  11.960 ms/op
                 getUser·p0.9999: 12.177 ms/op
                 getUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17605
  mean =      1.809 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 175 
    [ 1.250,  2.500) = 16943 
    [ 2.500,  3.750) = 410 
    [ 3.750,  5.000) = 38 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      1.765 ms/op
     p(90.0000) =      2.073 ms/op
     p(95.0000) =      2.281 ms/op
     p(99.0000) =      2.753 ms/op
     p(99.9000) =     11.960 ms/op
     p(99.9900) =     12.177 ms/op
     p(99.9990) =     12.190 ms/op
     p(99.9999) =     12.190 ms/op
    p(100.0000) =     12.190 ms/op


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
# Warmup Iteration   1: 4.141 ±(99.9%) 0.130 ms/op
Iteration   1: 3.576 ±(99.9%) 0.050 ms/op
                 listUser·p0.00:   1.284 ms/op
                 listUser·p0.50:   3.527 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.759 ms/op
                 listUser·p0.999:  21.070 ms/op
                 listUser·p0.9999: 29.852 ms/op
                 listUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8943
  mean =      3.576 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 452 
    [ 2.500,  5.000) = 8258 
    [ 5.000,  7.500) = 161 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      3.527 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.759 ms/op
     p(99.9000) =     21.070 ms/op
     p(99.9900) =     29.852 ms/op
     p(99.9990) =     29.852 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           6.760          ops/ms
ClientSimple.existUser                       thrpt          12.791          ops/ms
ClientSimple.getUser                         thrpt          12.412          ops/ms
ClientSimple.listUser                        thrpt           8.400          ops/ms
ClientSimple.createUser                       avgt           2.260           ms/op
ClientSimple.existUser                        avgt           1.977           ms/op
ClientSimple.getUser                          avgt           1.853           ms/op
ClientSimple.listUser                         avgt           3.560           ms/op
ClientSimple.createUser                     sample  15311    2.103 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.689           ms/op
ClientSimple.createUser:createUser·p0.50    sample           1.915           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.433           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.679           ms/op
ClientSimple.createUser:createUser·p0.99    sample           9.159           ms/op
ClientSimple.createUser:createUser·p0.999   sample          17.324           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          17.939           ms/op
ClientSimple.createUser:createUser·p1.00    sample          17.957           ms/op
ClientSimple.existUser                      sample  14939    2.101 ± 0.119   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.365           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.815           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.322           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.499           ms/op
ClientSimple.existUser:existUser·p0.99      sample           3.274           ms/op
ClientSimple.existUser:existUser·p0.999     sample          85.763           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         121.456           ms/op
ClientSimple.existUser:existUser·p1.00      sample         122.946           ms/op
ClientSimple.getUser                        sample  17605    1.809 ± 0.013   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.814           ms/op
ClientSimple.getUser:getUser·p0.50          sample           1.765           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.073           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.281           ms/op
ClientSimple.getUser:getUser·p0.99          sample           2.753           ms/op
ClientSimple.getUser:getUser·p0.999         sample          11.960           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          12.177           ms/op
ClientSimple.getUser:getUser·p1.00          sample          12.190           ms/op
ClientSimple.listUser                       sample   8943    3.576 ± 0.050   ms/op
ClientSimple.listUser:listUser·p0.00        sample           1.284           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.527           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.166           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.407           ms/op
ClientSimple.listUser:listUser·p0.99        sample           6.759           ms/op
ClientSimple.listUser:listUser·p0.999       sample          21.070           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          29.852           ms/op
ClientSimple.listUser:listUser·p1.00        sample          29.852           ms/op

Benchmark result is saved to 1722795095429.json
