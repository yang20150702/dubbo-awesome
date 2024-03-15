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
# Warmup Iteration   1: 1.851 ops/ms
Iteration   1: 7.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.298 ops/ms


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
# Warmup Iteration   1: 7.069 ops/ms
Iteration   1: 11.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.219 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.735 ops/ms
Iteration   1: 14.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.017 ops/ms


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
# Warmup Iteration   1: 6.036 ops/ms
Iteration   1: 8.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.778 ops/ms


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
# Warmup Iteration   1: 3.985 ±(99.9%) 0.068 ms/op
Iteration   1: 2.148 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.148 ms/op


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
# Warmup Iteration   1: 3.636 ±(99.9%) 0.062 ms/op
Iteration   1: 1.987 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.987 ms/op


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
# Warmup Iteration   1: 3.048 ±(99.9%) 0.054 ms/op
Iteration   1: 2.209 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.209 ms/op


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
# Warmup Iteration   1: 4.200 ±(99.9%) 0.094 ms/op
Iteration   1: 3.280 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.280 ms/op


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
# Warmup Iteration   1: 3.394 ±(99.9%) 0.075 ms/op
Iteration   1: 2.152 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   0.614 ms/op
                 createUser·p0.50:   1.970 ms/op
                 createUser·p0.90:   2.576 ms/op
                 createUser·p0.95:   2.765 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  36.110 ms/op
                 createUser·p0.9999: 38.700 ms/op
                 createUser·p1.00:   38.732 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14902
  mean =      2.152 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12913 
    [ 2.500,  5.000) = 1817 
    [ 5.000,  7.500) = 68 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      1.970 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.765 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     36.110 ms/op
     p(99.9900) =     38.700 ms/op
     p(99.9990) =     38.732 ms/op
     p(99.9999) =     38.732 ms/op
    p(100.0000) =     38.732 ms/op


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
# Warmup Iteration   1: 3.170 ±(99.9%) 0.086 ms/op
Iteration   1: 2.043 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.553 ms/op
                 existUser·p0.50:   2.036 ms/op
                 existUser·p0.90:   2.441 ms/op
                 existUser·p0.95:   2.609 ms/op
                 existUser·p0.99:   3.155 ms/op
                 existUser·p0.999:  14.702 ms/op
                 existUser·p0.9999: 14.860 ms/op
                 existUser·p1.00:   14.860 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15666
  mean =      2.043 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 160 
    [ 1.250,  2.500) = 14347 
    [ 2.500,  3.750) = 1095 
    [ 3.750,  5.000) = 18 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      2.036 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      3.155 ms/op
     p(99.9000) =     14.702 ms/op
     p(99.9900) =     14.860 ms/op
     p(99.9990) =     14.860 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 2.987 ±(99.9%) 0.081 ms/op
Iteration   1: 2.219 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   2.109 ms/op
                 getUser·p0.90:   2.728 ms/op
                 getUser·p0.95:   2.970 ms/op
                 getUser·p0.99:   5.266 ms/op
                 getUser·p0.999:  12.888 ms/op
                 getUser·p0.9999: 13.302 ms/op
                 getUser·p1.00:   13.353 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14406
  mean =      2.219 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 11430 
    [ 2.500,  3.750) = 2739 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 90 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      2.109 ms/op
     p(90.0000) =      2.728 ms/op
     p(95.0000) =      2.970 ms/op
     p(99.0000) =      5.266 ms/op
     p(99.9000) =     12.888 ms/op
     p(99.9900) =     13.302 ms/op
     p(99.9990) =     13.353 ms/op
     p(99.9999) =     13.353 ms/op
    p(100.0000) =     13.353 ms/op


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
# Warmup Iteration   1: 5.991 ±(99.9%) 0.205 ms/op
Iteration   1: 3.500 ±(99.9%) 0.052 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   3.236 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.941 ms/op
                 listUser·p0.99:   12.614 ms/op
                 listUser·p0.999:  18.116 ms/op
                 listUser·p0.9999: 19.530 ms/op
                 listUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9155
  mean =      3.500 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 612 
    [ 2.500,  3.750) = 6353 
    [ 3.750,  5.000) = 1738 
    [ 5.000,  6.250) = 283 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.941 ms/op
     p(99.0000) =     12.614 ms/op
     p(99.9000) =     18.116 ms/op
     p(99.9900) =     19.530 ms/op
     p(99.9990) =     19.530 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.298          ops/ms
ClientSimple.existUser                       thrpt         11.219          ops/ms
ClientSimple.getUser                         thrpt         14.017          ops/ms
ClientSimple.listUser                        thrpt          8.778          ops/ms
ClientSimple.createUser                       avgt          2.148           ms/op
ClientSimple.existUser                        avgt          1.987           ms/op
ClientSimple.getUser                          avgt          2.209           ms/op
ClientSimple.listUser                         avgt          3.280           ms/op
ClientSimple.createUser                     sample  14902   2.152 ± 0.048   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.614           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.970           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.576           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.765           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.956           ms/op
ClientSimple.createUser:createUser·p0.999   sample         36.110           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         38.700           ms/op
ClientSimple.createUser:createUser·p1.00    sample         38.732           ms/op
ClientSimple.existUser                      sample  15666   2.043 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.553           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.036           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.441           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.609           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.155           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.702           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.860           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.860           ms/op
ClientSimple.getUser                        sample  14406   2.219 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          1.073           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.109           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.728           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.970           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.266           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.888           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.302           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.353           ms/op
ClientSimple.listUser                       sample   9155   3.500 ± 0.052   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.950           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.236           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.941           ms/op
ClientSimple.listUser:listUser·p0.99        sample         12.614           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.116           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.530           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.530           ms/op

Benchmark result is saved to 1710526310930.json
