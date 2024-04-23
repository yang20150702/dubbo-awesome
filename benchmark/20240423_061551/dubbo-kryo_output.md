# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.687 ops/ms
Iteration   1: 7.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.042 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.079 ops/ms
Iteration   1: 11.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.650 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.713 ops/ms
Iteration   1: 11.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.838 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.177 ops/ms
Iteration   1: 8.747 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.747 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.793 ±(99.9%) 0.070 ms/op
Iteration   1: 2.270 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.270 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.298 ±(99.9%) 0.060 ms/op
Iteration   1: 1.979 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.979 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.199 ±(99.9%) 0.095 ms/op
Iteration   1: 2.211 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.211 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.539 ±(99.9%) 0.085 ms/op
Iteration   1: 3.161 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.161 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.465 ±(99.9%) 0.091 ms/op
Iteration   1: 2.291 ±(99.9%) 0.147 ms/op
                 createUser·p0.00:   0.397 ms/op
                 createUser·p0.50:   1.840 ms/op
                 createUser·p0.90:   2.466 ms/op
                 createUser·p0.95:   2.810 ms/op
                 createUser·p0.99:   9.985 ms/op
                 createUser·p0.999:  114.736 ms/op
                 createUser·p0.9999: 130.843 ms/op
                 createUser·p1.00:   131.465 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13958
  mean =      2.291 ±(99.9%) 0.147 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 13874 
    [ 12.500,  25.000) = 43 
    [ 25.000,  37.500) = 3 
    [ 37.500,  50.000) = 4 
    [ 50.000,  62.500) = 2 
    [ 62.500,  75.000) = 3 
    [ 75.000,  87.500) = 2 
    [ 87.500, 100.000) = 5 
    [100.000, 112.500) = 7 
    [112.500, 125.000) = 11 
    [125.000, 137.500) = 4 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.397 ms/op
     p(50.0000) =      1.840 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      9.985 ms/op
     p(99.9000) =    114.736 ms/op
     p(99.9900) =    130.843 ms/op
     p(99.9990) =    131.465 ms/op
     p(99.9999) =    131.465 ms/op
    p(100.0000) =    131.465 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.225 ±(99.9%) 0.073 ms/op
Iteration   1: 1.996 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   1.851 ms/op
                 existUser·p0.90:   2.535 ms/op
                 existUser·p0.95:   2.818 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  13.041 ms/op
                 existUser·p0.9999: 14.555 ms/op
                 existUser·p1.00:   14.664 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16020
  mean =      1.996 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 683 
    [ 1.250,  2.500) = 13575 
    [ 2.500,  3.750) = 1476 
    [ 3.750,  5.000) = 107 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      1.851 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     13.041 ms/op
     p(99.9900) =     14.555 ms/op
     p(99.9990) =     14.664 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.358 ±(99.9%) 0.076 ms/op
Iteration   1: 2.107 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.706 ms/op
                 getUser·p0.50:   2.009 ms/op
                 getUser·p0.90:   2.626 ms/op
                 getUser·p0.95:   2.879 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  12.826 ms/op
                 getUser·p0.9999: 13.446 ms/op
                 getUser·p1.00:   13.599 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15180
  mean =      2.107 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 13045 
    [ 2.500,  3.750) = 1850 
    [ 3.750,  5.000) = 131 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      2.009 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.879 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =     12.826 ms/op
     p(99.9900) =     13.446 ms/op
     p(99.9990) =     13.599 ms/op
     p(99.9999) =     13.599 ms/op
    p(100.0000) =     13.599 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.679 ±(99.9%) 0.138 ms/op
Iteration   1: 3.534 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   3.449 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   6.078 ms/op
                 listUser·p0.999:  20.310 ms/op
                 listUser·p0.9999: 21.496 ms/op
                 listUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9047
  mean =      3.534 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 562 
    [ 2.500,  5.000) = 8227 
    [ 5.000,  7.500) = 213 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     20.310 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           7.042          ops/ms
ClientSimple.existUser                       thrpt          11.650          ops/ms
ClientSimple.getUser                         thrpt          11.838          ops/ms
ClientSimple.listUser                        thrpt           8.747          ops/ms
ClientSimple.createUser                       avgt           2.270           ms/op
ClientSimple.existUser                        avgt           1.979           ms/op
ClientSimple.getUser                          avgt           2.211           ms/op
ClientSimple.listUser                         avgt           3.161           ms/op
ClientSimple.createUser                     sample  13958    2.291 ± 0.147   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.397           ms/op
ClientSimple.createUser:createUser·p0.50    sample           1.840           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.466           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.810           ms/op
ClientSimple.createUser:createUser·p0.99    sample           9.985           ms/op
ClientSimple.createUser:createUser·p0.999   sample         114.736           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         130.843           ms/op
ClientSimple.createUser:createUser·p1.00    sample         131.465           ms/op
ClientSimple.existUser                      sample  16020    1.996 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.606           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.851           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.535           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.818           ms/op
ClientSimple.existUser:existUser·p0.99      sample           5.988           ms/op
ClientSimple.existUser:existUser·p0.999     sample          13.041           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          14.555           ms/op
ClientSimple.existUser:existUser·p1.00      sample          14.664           ms/op
ClientSimple.getUser                        sample  15180    2.107 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.706           ms/op
ClientSimple.getUser:getUser·p0.50          sample           2.009           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.626           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.879           ms/op
ClientSimple.getUser:getUser·p0.99          sample           4.538           ms/op
ClientSimple.getUser:getUser·p0.999         sample          12.826           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          13.446           ms/op
ClientSimple.getUser:getUser·p1.00          sample          13.599           ms/op
ClientSimple.listUser                       sample   9047    3.534 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample           1.128           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.449           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.317           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.612           ms/op
ClientSimple.listUser:listUser·p0.99        sample           6.078           ms/op
ClientSimple.listUser:listUser·p0.999       sample          20.310           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          21.496           ms/op
ClientSimple.listUser:listUser·p1.00        sample          21.496           ms/op

Benchmark result is saved to 1713852688858.json
