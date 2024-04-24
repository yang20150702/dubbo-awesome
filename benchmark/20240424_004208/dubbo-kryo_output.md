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
# Warmup Iteration   1: 1.408 ops/ms
Iteration   1: 7.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.159 ops/ms


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
# Warmup Iteration   1: 5.566 ops/ms
Iteration   1: 12.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.353 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.572 ops/ms
Iteration   1: 12.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.317 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.913 ops/ms
Iteration   1: 8.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.888 ops/ms


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
# Warmup Iteration   1: 4.140 ±(99.9%) 0.093 ms/op
Iteration   1: 2.089 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.089 ms/op


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
# Warmup Iteration   1: 3.458 ±(99.9%) 0.058 ms/op
Iteration   1: 1.892 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.892 ms/op


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
# Warmup Iteration   1: 3.361 ±(99.9%) 0.070 ms/op
Iteration   1: 2.086 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.086 ms/op


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
# Warmup Iteration   1: 5.553 ±(99.9%) 0.149 ms/op
Iteration   1: 3.747 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.747 ms/op


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
# Warmup Iteration   1: 3.807 ±(99.9%) 0.110 ms/op
Iteration   1: 2.391 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.309 ms/op
                 createUser·p0.50:   1.901 ms/op
                 createUser·p0.90:   3.277 ms/op
                 createUser·p0.95:   4.444 ms/op
                 createUser·p0.99:   11.665 ms/op
                 createUser·p0.999:  19.562 ms/op
                 createUser·p0.9999: 24.048 ms/op
                 createUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13350
  mean =      2.391 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10026 
    [ 2.500,  5.000) = 2799 
    [ 5.000,  7.500) = 237 
    [ 7.500, 10.000) = 104 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.309 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      3.277 ms/op
     p(95.0000) =      4.444 ms/op
     p(99.0000) =     11.665 ms/op
     p(99.9000) =     19.562 ms/op
     p(99.9900) =     24.048 ms/op
     p(99.9990) =     24.707 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


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
# Warmup Iteration   1: 2.840 ±(99.9%) 0.063 ms/op
Iteration   1: 1.992 ±(99.9%) 0.048 ms/op
                 existUser·p0.00:   0.710 ms/op
                 existUser·p0.50:   1.782 ms/op
                 existUser·p0.90:   2.556 ms/op
                 existUser·p0.95:   2.724 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  38.654 ms/op
                 existUser·p0.9999: 47.448 ms/op
                 existUser·p1.00:   47.448 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16090
  mean =      1.992 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15979 
    [ 5.000, 10.000) = 32 
    [10.000, 15.000) = 38 
    [15.000, 20.000) = 6 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 6 
    [30.000, 35.000) = 6 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      1.782 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      3.457 ms/op
     p(99.9000) =     38.654 ms/op
     p(99.9900) =     47.448 ms/op
     p(99.9990) =     47.448 ms/op
     p(99.9999) =     47.448 ms/op
    p(100.0000) =     47.448 ms/op


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
# Warmup Iteration   1: 3.422 ±(99.9%) 0.100 ms/op
Iteration   1: 2.348 ±(99.9%) 0.122 ms/op
                 getUser·p0.00:   0.621 ms/op
                 getUser·p0.50:   1.985 ms/op
                 getUser·p0.90:   2.724 ms/op
                 getUser·p0.95:   2.970 ms/op
                 getUser·p0.99:   4.919 ms/op
                 getUser·p0.999:  90.782 ms/op
                 getUser·p0.9999: 109.851 ms/op
                 getUser·p1.00:   110.232 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13625
  mean =      2.348 ±(99.9%) 0.122 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 13538 
    [ 12.500,  25.000) = 40 
    [ 25.000,  37.500) = 1 
    [ 37.500,  50.000) = 7 
    [ 50.000,  62.500) = 15 
    [ 62.500,  75.000) = 6 
    [ 75.000,  87.500) = 3 
    [ 87.500, 100.000) = 9 
    [100.000, 112.500) = 6 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      2.970 ms/op
     p(99.0000) =      4.919 ms/op
     p(99.9000) =     90.782 ms/op
     p(99.9900) =    109.851 ms/op
     p(99.9990) =    110.232 ms/op
     p(99.9999) =    110.232 ms/op
    p(100.0000) =    110.232 ms/op


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
# Warmup Iteration   1: 4.424 ±(99.9%) 0.127 ms/op
Iteration   1: 3.532 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   0.577 ms/op
                 listUser·p0.50:   3.535 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  15.352 ms/op
                 listUser·p0.9999: 15.974 ms/op
                 listUser·p1.00:   15.974 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9049
  mean =      3.532 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 1137 
    [ 2.500,  3.750) = 4906 
    [ 3.750,  5.000) = 2669 
    [ 5.000,  6.250) = 187 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     15.352 ms/op
     p(99.9900) =     15.974 ms/op
     p(99.9990) =     15.974 ms/op
     p(99.9999) =     15.974 ms/op
    p(100.0000) =     15.974 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           7.159          ops/ms
ClientSimple.existUser                       thrpt          12.353          ops/ms
ClientSimple.getUser                         thrpt          12.317          ops/ms
ClientSimple.listUser                        thrpt           8.888          ops/ms
ClientSimple.createUser                       avgt           2.089           ms/op
ClientSimple.existUser                        avgt           1.892           ms/op
ClientSimple.getUser                          avgt           2.086           ms/op
ClientSimple.listUser                         avgt           3.747           ms/op
ClientSimple.createUser                     sample  13350    2.391 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.309           ms/op
ClientSimple.createUser:createUser·p0.50    sample           1.901           ms/op
ClientSimple.createUser:createUser·p0.90    sample           3.277           ms/op
ClientSimple.createUser:createUser·p0.95    sample           4.444           ms/op
ClientSimple.createUser:createUser·p0.99    sample          11.665           ms/op
ClientSimple.createUser:createUser·p0.999   sample          19.562           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          24.048           ms/op
ClientSimple.createUser:createUser·p1.00    sample          24.707           ms/op
ClientSimple.existUser                      sample  16090    1.992 ± 0.048   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.710           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.782           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.556           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.724           ms/op
ClientSimple.existUser:existUser·p0.99      sample           3.457           ms/op
ClientSimple.existUser:existUser·p0.999     sample          38.654           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          47.448           ms/op
ClientSimple.existUser:existUser·p1.00      sample          47.448           ms/op
ClientSimple.getUser                        sample  13625    2.348 ± 0.122   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.621           ms/op
ClientSimple.getUser:getUser·p0.50          sample           1.985           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.724           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.970           ms/op
ClientSimple.getUser:getUser·p0.99          sample           4.919           ms/op
ClientSimple.getUser:getUser·p0.999         sample          90.782           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         109.851           ms/op
ClientSimple.getUser:getUser·p1.00          sample         110.232           ms/op
ClientSimple.listUser                       sample   9049    3.532 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample           0.577           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.535           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.301           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.686           ms/op
ClientSimple.listUser:listUser·p0.99        sample           6.865           ms/op
ClientSimple.listUser:listUser·p0.999       sample          15.352           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          15.974           ms/op
ClientSimple.listUser:listUser·p1.00        sample          15.974           ms/op

Benchmark result is saved to 1713919080814.json
