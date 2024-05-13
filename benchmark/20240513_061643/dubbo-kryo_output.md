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
# Warmup Iteration   1: 1.948 ops/ms
Iteration   1: 6.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.072 ops/ms


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
# Warmup Iteration   1: 5.942 ops/ms
Iteration   1: 12.347 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.347 ops/ms


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
# Warmup Iteration   1: 5.897 ops/ms
Iteration   1: 12.309 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.309 ops/ms


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
# Warmup Iteration   1: 4.022 ops/ms
Iteration   1: 8.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.453 ops/ms


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
# Warmup Iteration   1: 4.177 ±(99.9%) 0.069 ms/op
Iteration   1: 2.144 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.144 ms/op


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
# Warmup Iteration   1: 3.241 ±(99.9%) 0.047 ms/op
Iteration   1: 1.846 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.846 ms/op


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
# Warmup Iteration   1: 3.625 ±(99.9%) 0.065 ms/op
Iteration   1: 2.321 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.321 ms/op


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
# Warmup Iteration   1: 4.508 ±(99.9%) 0.106 ms/op
Iteration   1: 3.255 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.255 ms/op


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
# Warmup Iteration   1: 3.636 ±(99.9%) 0.125 ms/op
Iteration   1: 2.154 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.828 ms/op
                 createUser·p0.50:   2.001 ms/op
                 createUser·p0.90:   2.769 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  14.336 ms/op
                 createUser·p0.9999: 15.217 ms/op
                 createUser·p1.00:   15.352 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14839
  mean =      2.154 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 185 
    [ 1.250,  2.500) = 12120 
    [ 2.500,  3.750) = 2180 
    [ 3.750,  5.000) = 119 
    [ 5.000,  6.250) = 138 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      2.001 ms/op
     p(90.0000) =      2.769 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     14.336 ms/op
     p(99.9900) =     15.217 ms/op
     p(99.9990) =     15.352 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


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
# Warmup Iteration   1: 3.046 ±(99.9%) 0.066 ms/op
Iteration   1: 2.023 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.592 ms/op
                 existUser·p0.50:   1.862 ms/op
                 existUser·p0.90:   2.404 ms/op
                 existUser·p0.95:   2.658 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  19.762 ms/op
                 existUser·p0.9999: 21.530 ms/op
                 existUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15923
  mean =      2.023 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14623 
    [ 2.500,  5.000) = 1204 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      1.862 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      3.654 ms/op
     p(99.9000) =     19.762 ms/op
     p(99.9900) =     21.530 ms/op
     p(99.9990) =     21.627 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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
# Warmup Iteration   1: 3.403 ±(99.9%) 0.107 ms/op
Iteration   1: 2.151 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.607 ms/op
                 getUser·p0.50:   2.046 ms/op
                 getUser·p0.90:   2.724 ms/op
                 getUser·p0.95:   2.957 ms/op
                 getUser·p0.99:   4.776 ms/op
                 getUser·p0.999:  13.795 ms/op
                 getUser·p0.9999: 14.991 ms/op
                 getUser·p1.00:   14.991 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14802
  mean =      2.151 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 132 
    [ 1.250,  2.500) = 12078 
    [ 2.500,  3.750) = 2293 
    [ 3.750,  5.000) = 165 
    [ 5.000,  6.250) = 89 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      2.046 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      2.957 ms/op
     p(99.0000) =      4.776 ms/op
     p(99.9000) =     13.795 ms/op
     p(99.9900) =     14.991 ms/op
     p(99.9990) =     14.991 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 4.533 ±(99.9%) 0.121 ms/op
Iteration   1: 3.615 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   0.847 ms/op
                 listUser·p0.50:   3.527 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   5.964 ms/op
                 listUser·p0.999:  22.690 ms/op
                 listUser·p0.9999: 23.364 ms/op
                 listUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8846
  mean =      3.615 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 740 
    [ 2.500,  5.000) = 7850 
    [ 5.000,  7.500) = 222 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      3.527 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     22.690 ms/op
     p(99.9900) =     23.364 ms/op
     p(99.9990) =     23.364 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.072          ops/ms
ClientSimple.existUser                       thrpt         12.347          ops/ms
ClientSimple.getUser                         thrpt         12.309          ops/ms
ClientSimple.listUser                        thrpt          8.453          ops/ms
ClientSimple.createUser                       avgt          2.144           ms/op
ClientSimple.existUser                        avgt          1.846           ms/op
ClientSimple.getUser                          avgt          2.321           ms/op
ClientSimple.listUser                         avgt          3.255           ms/op
ClientSimple.createUser                     sample  14839   2.154 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.828           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.001           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.769           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.170           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.571           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.336           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.217           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.352           ms/op
ClientSimple.existUser                      sample  15923   2.023 ± 0.035   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.592           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.862           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.404           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.658           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.654           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.762           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.530           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.627           ms/op
ClientSimple.getUser                        sample  14802   2.151 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.607           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.046           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.724           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.957           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.776           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.795           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.991           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.991           ms/op
ClientSimple.listUser                       sample   8846   3.615 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.847           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.527           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.809           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.964           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.690           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.364           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.364           ms/op

Benchmark result is saved to 1715580763514.json
