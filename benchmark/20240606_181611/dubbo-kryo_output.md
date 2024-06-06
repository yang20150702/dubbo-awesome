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
# Warmup Iteration   1: 2.079 ops/ms
Iteration   1: 7.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.354 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.807 ops/ms
Iteration   1: 11.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.833 ops/ms


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
# Warmup Iteration   1: 6.032 ops/ms
Iteration   1: 10.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.643 ops/ms


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
# Warmup Iteration   1: 4.076 ops/ms
Iteration   1: 8.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.191 ops/ms


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
# Warmup Iteration   1: 4.142 ±(99.9%) 0.085 ms/op
Iteration   1: 2.194 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.194 ms/op


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
# Warmup Iteration   1: 3.334 ±(99.9%) 0.054 ms/op
Iteration   1: 1.833 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.833 ms/op


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
# Warmup Iteration   1: 3.232 ±(99.9%) 0.049 ms/op
Iteration   1: 1.919 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.919 ms/op


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
# Warmup Iteration   1: 4.644 ±(99.9%) 0.090 ms/op
Iteration   1: 3.746 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.746 ms/op


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
# Warmup Iteration   1: 3.701 ±(99.9%) 0.102 ms/op
Iteration   1: 2.130 ±(99.9%) 0.083 ms/op
                 createUser·p0.00:   0.485 ms/op
                 createUser·p0.50:   1.763 ms/op
                 createUser·p0.90:   2.417 ms/op
                 createUser·p0.95:   2.623 ms/op
                 createUser·p0.99:   11.865 ms/op
                 createUser·p0.999:  62.389 ms/op
                 createUser·p0.9999: 71.827 ms/op
                 createUser·p1.00:   72.090 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15012
  mean =      2.130 ±(99.9%) 0.083 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14718 
    [ 5.000, 10.000) = 116 
    [10.000, 15.000) = 103 
    [15.000, 20.000) = 3 
    [20.000, 25.000) = 32 
    [25.000, 30.000) = 5 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 2 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 2 
    [55.000, 60.000) = 5 
    [60.000, 65.000) = 3 
    [65.000, 70.000) = 9 
    [70.000, 75.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.485 ms/op
     p(50.0000) =      1.763 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.623 ms/op
     p(99.0000) =     11.865 ms/op
     p(99.9000) =     62.389 ms/op
     p(99.9900) =     71.827 ms/op
     p(99.9990) =     72.090 ms/op
     p(99.9999) =     72.090 ms/op
    p(100.0000) =     72.090 ms/op


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
# Warmup Iteration   1: 2.963 ±(99.9%) 0.075 ms/op
Iteration   1: 1.946 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.744 ms/op
                 existUser·p0.50:   1.878 ms/op
                 existUser·p0.90:   2.367 ms/op
                 existUser·p0.95:   2.540 ms/op
                 existUser·p0.99:   2.900 ms/op
                 existUser·p0.999:  14.004 ms/op
                 existUser·p0.9999: 14.385 ms/op
                 existUser·p1.00:   14.385 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16510
  mean =      1.946 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 15438 
    [ 2.500,  3.750) = 893 
    [ 3.750,  5.000) = 21 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      1.878 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.540 ms/op
     p(99.0000) =      2.900 ms/op
     p(99.9000) =     14.004 ms/op
     p(99.9900) =     14.385 ms/op
     p(99.9990) =     14.385 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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
# Warmup Iteration   1: 3.384 ±(99.9%) 0.092 ms/op
Iteration   1: 1.952 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.609 ms/op
                 getUser·p0.50:   1.796 ms/op
                 getUser·p0.90:   2.511 ms/op
                 getUser·p0.95:   2.716 ms/op
                 getUser·p0.99:   3.531 ms/op
                 getUser·p0.999:  12.042 ms/op
                 getUser·p0.9999: 12.261 ms/op
                 getUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16632
  mean =      1.952 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 14800 
    [ 2.500,  3.750) = 1596 
    [ 3.750,  5.000) = 49 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      1.796 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.716 ms/op
     p(99.0000) =      3.531 ms/op
     p(99.9000) =     12.042 ms/op
     p(99.9900) =     12.261 ms/op
     p(99.9990) =     12.272 ms/op
     p(99.9999) =     12.272 ms/op
    p(100.0000) =     12.272 ms/op


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
# Warmup Iteration   1: 4.251 ±(99.9%) 0.119 ms/op
Iteration   1: 3.195 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   1.004 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   6.108 ms/op
                 listUser·p0.999:  16.941 ms/op
                 listUser·p0.9999: 17.007 ms/op
                 listUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10036
  mean =      3.195 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 1454 
    [ 2.500,  3.750) = 6394 
    [ 3.750,  5.000) = 1970 
    [ 5.000,  6.250) = 130 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.004 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.108 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     17.007 ms/op
     p(99.9990) =     17.007 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.354          ops/ms
ClientSimple.existUser                       thrpt         11.833          ops/ms
ClientSimple.getUser                         thrpt         10.643          ops/ms
ClientSimple.listUser                        thrpt          8.191          ops/ms
ClientSimple.createUser                       avgt          2.194           ms/op
ClientSimple.existUser                        avgt          1.833           ms/op
ClientSimple.getUser                          avgt          1.919           ms/op
ClientSimple.listUser                         avgt          3.746           ms/op
ClientSimple.createUser                     sample  15012   2.130 ± 0.083   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.485           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.763           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.417           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.623           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.865           ms/op
ClientSimple.createUser:createUser·p0.999   sample         62.389           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         71.827           ms/op
ClientSimple.createUser:createUser·p1.00    sample         72.090           ms/op
ClientSimple.existUser                      sample  16510   1.946 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.744           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.878           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.367           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.540           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.900           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.004           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.385           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.385           ms/op
ClientSimple.getUser                        sample  16632   1.952 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.609           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.796           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.511           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.716           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.531           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.042           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.261           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.272           ms/op
ClientSimple.listUser                       sample  10036   3.195 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.004           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.974           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.125           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.424           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.108           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.941           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.007           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.007           ms/op

Benchmark result is saved to 1717697509544.json
