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
# Warmup Iteration   1: 1.556 ops/ms
Iteration   1: 5.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.954 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.019 ops/ms
Iteration   1: 10.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.173 ops/ms


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
# Warmup Iteration   1: 5.389 ops/ms
Iteration   1: 11.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.433 ops/ms


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
# Warmup Iteration   1: 5.385 ops/ms
Iteration   1: 8.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.416 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.679 ±(99.9%) 0.083 ms/op
Iteration   1: 2.438 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.438 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.390 ±(99.9%) 0.051 ms/op
Iteration   1: 1.950 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.950 ms/op


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
# Warmup Iteration   1: 3.410 ±(99.9%) 0.066 ms/op
Iteration   1: 2.226 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.226 ms/op


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
# Warmup Iteration   1: 5.877 ±(99.9%) 0.137 ms/op
Iteration   1: 4.031 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.031 ms/op


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
# Warmup Iteration   1: 3.999 ±(99.9%) 0.117 ms/op
Iteration   1: 2.251 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.428 ms/op
                 createUser·p0.50:   1.919 ms/op
                 createUser·p0.90:   2.870 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   12.550 ms/op
                 createUser·p0.999:  18.776 ms/op
                 createUser·p0.9999: 20.352 ms/op
                 createUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14241
  mean =      2.251 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11259 
    [ 2.500,  5.000) = 2707 
    [ 5.000,  7.500) = 81 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.428 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.870 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =     12.550 ms/op
     p(99.9000) =     18.776 ms/op
     p(99.9900) =     20.352 ms/op
     p(99.9990) =     20.644 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


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
# Warmup Iteration   1: 3.073 ±(99.9%) 0.068 ms/op
Iteration   1: 1.931 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.571 ms/op
                 existUser·p0.50:   1.786 ms/op
                 existUser·p0.90:   2.454 ms/op
                 existUser·p0.95:   2.748 ms/op
                 existUser·p0.99:   4.698 ms/op
                 existUser·p0.999:  11.886 ms/op
                 existUser·p0.9999: 12.026 ms/op
                 existUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16550
  mean =      1.931 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 220 
    [ 1.250,  2.500) = 14876 
    [ 2.500,  3.750) = 1263 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      1.786 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      4.698 ms/op
     p(99.9000) =     11.886 ms/op
     p(99.9900) =     12.026 ms/op
     p(99.9990) =     12.026 ms/op
     p(99.9999) =     12.026 ms/op
    p(100.0000) =     12.026 ms/op


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
# Warmup Iteration   1: 3.495 ±(99.9%) 0.127 ms/op
Iteration   1: 2.067 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.616 ms/op
                 getUser·p0.50:   1.876 ms/op
                 getUser·p0.90:   2.548 ms/op
                 getUser·p0.95:   2.826 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  14.884 ms/op
                 getUser·p0.9999: 14.999 ms/op
                 getUser·p1.00:   15.008 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15569
  mean =      2.067 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 13611 
    [ 2.500,  3.750) = 1490 
    [ 3.750,  5.000) = 134 
    [ 5.000,  6.250) = 83 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.548 ms/op
     p(95.0000) =      2.826 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     14.884 ms/op
     p(99.9900) =     14.999 ms/op
     p(99.9990) =     15.008 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


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
# Warmup Iteration   1: 5.087 ±(99.9%) 0.311 ms/op
Iteration   1: 3.170 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.116 ms/op
                 listUser·p0.50:   2.847 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   6.899 ms/op
                 listUser·p0.999:  17.269 ms/op
                 listUser·p0.9999: 18.185 ms/op
                 listUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10081
  mean =      3.170 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 2363 
    [ 2.500,  3.750) = 5677 
    [ 3.750,  5.000) = 1619 
    [ 5.000,  6.250) = 248 
    [ 6.250,  7.500) = 86 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 39 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      6.899 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     18.185 ms/op
     p(99.9990) =     18.186 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.954          ops/ms
ClientSimple.existUser                       thrpt         10.173          ops/ms
ClientSimple.getUser                         thrpt         11.433          ops/ms
ClientSimple.listUser                        thrpt          8.416          ops/ms
ClientSimple.createUser                       avgt          2.438           ms/op
ClientSimple.existUser                        avgt          1.950           ms/op
ClientSimple.getUser                          avgt          2.226           ms/op
ClientSimple.listUser                         avgt          4.031           ms/op
ClientSimple.createUser                     sample  14241   2.251 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.428           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.919           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.870           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.162           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.550           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.776           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.352           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.644           ms/op
ClientSimple.existUser                      sample  16550   1.931 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.571           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.786           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.454           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.748           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.698           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.886           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.026           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.026           ms/op
ClientSimple.getUser                        sample  15569   2.067 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.616           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.876           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.548           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.826           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.865           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.884           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.999           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.008           ms/op
ClientSimple.listUser                       sample  10081   3.170 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.116           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.847           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.137           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.784           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.899           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.269           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.185           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.186           ms/op

Benchmark result is saved to 1717330488608.json
