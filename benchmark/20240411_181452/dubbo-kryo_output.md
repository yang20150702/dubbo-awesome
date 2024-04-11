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
# Warmup Iteration   1: 1.666 ops/ms
Iteration   1: 6.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.087 ops/ms


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
# Warmup Iteration   1: 5.213 ops/ms
Iteration   1: 12.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.466 ops/ms


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
# Warmup Iteration   1: 5.723 ops/ms
Iteration   1: 12.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.812 ops/ms


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
# Warmup Iteration   1: 3.568 ops/ms
Iteration   1: 8.027 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.027 ops/ms


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
# Warmup Iteration   1: 3.866 ±(99.9%) 0.064 ms/op
Iteration   1: 1.775 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.775 ms/op


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
# Warmup Iteration   1: 3.338 ±(99.9%) 0.072 ms/op
Iteration   1: 1.877 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.877 ms/op


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
# Warmup Iteration   1: 3.333 ±(99.9%) 0.058 ms/op
Iteration   1: 1.987 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.154 ±(99.9%) 0.125 ms/op
Iteration   1: 3.391 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.391 ms/op


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
# Warmup Iteration   1: 3.919 ±(99.9%) 0.124 ms/op
Iteration   1: 2.273 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   2.023 ms/op
                 createUser·p0.90:   2.789 ms/op
                 createUser·p0.95:   3.128 ms/op
                 createUser·p0.99:   6.918 ms/op
                 createUser·p0.999:  16.284 ms/op
                 createUser·p0.9999: 17.564 ms/op
                 createUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14086
  mean =      2.273 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 11274 
    [ 2.500,  3.750) = 2417 
    [ 3.750,  5.000) = 67 
    [ 5.000,  6.250) = 117 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      2.023 ms/op
     p(90.0000) =      2.789 ms/op
     p(95.0000) =      3.128 ms/op
     p(99.0000) =      6.918 ms/op
     p(99.9000) =     16.284 ms/op
     p(99.9900) =     17.564 ms/op
     p(99.9990) =     17.564 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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
# Warmup Iteration   1: 3.117 ±(99.9%) 0.078 ms/op
Iteration   1: 1.816 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.782 ms/op
                 existUser·p0.50:   1.696 ms/op
                 existUser·p0.90:   2.050 ms/op
                 existUser·p0.95:   2.269 ms/op
                 existUser·p0.99:   3.112 ms/op
                 existUser·p0.999:  18.678 ms/op
                 existUser·p0.9999: 19.405 ms/op
                 existUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17629
  mean =      1.816 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 17128 
    [ 2.500,  3.750) = 215 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      1.696 ms/op
     p(90.0000) =      2.050 ms/op
     p(95.0000) =      2.269 ms/op
     p(99.0000) =      3.112 ms/op
     p(99.9000) =     18.678 ms/op
     p(99.9900) =     19.405 ms/op
     p(99.9990) =     19.530 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 3.432 ±(99.9%) 0.097 ms/op
Iteration   1: 2.178 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   2.054 ms/op
                 getUser·p0.90:   2.662 ms/op
                 getUser·p0.95:   2.900 ms/op
                 getUser·p0.99:   5.546 ms/op
                 getUser·p0.999:  15.750 ms/op
                 getUser·p0.9999: 16.138 ms/op
                 getUser·p1.00:   16.138 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14680
  mean =      2.178 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 12201 
    [ 2.500,  3.750) = 2204 
    [ 3.750,  5.000) = 64 
    [ 5.000,  6.250) = 91 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      2.054 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     15.750 ms/op
     p(99.9900) =     16.138 ms/op
     p(99.9990) =     16.138 ms/op
     p(99.9999) =     16.138 ms/op
    p(100.0000) =     16.138 ms/op


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
# Warmup Iteration   1: 5.128 ±(99.9%) 0.174 ms/op
Iteration   1: 3.799 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.843 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.284 ms/op
                 listUser·p0.999:  15.934 ms/op
                 listUser·p0.9999: 16.400 ms/op
                 listUser·p1.00:   16.400 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8444
  mean =      3.799 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 464 
    [ 2.500,  3.750) = 3792 
    [ 3.750,  5.000) = 3560 
    [ 5.000,  6.250) = 534 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.382 ms/op
     p(99.0000) =      6.284 ms/op
     p(99.9000) =     15.934 ms/op
     p(99.9900) =     16.400 ms/op
     p(99.9990) =     16.400 ms/op
     p(99.9999) =     16.400 ms/op
    p(100.0000) =     16.400 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.087          ops/ms
ClientSimple.existUser                       thrpt         12.466          ops/ms
ClientSimple.getUser                         thrpt         12.812          ops/ms
ClientSimple.listUser                        thrpt          8.027          ops/ms
ClientSimple.createUser                       avgt          1.775           ms/op
ClientSimple.existUser                        avgt          1.877           ms/op
ClientSimple.getUser                          avgt          1.987           ms/op
ClientSimple.listUser                         avgt          3.391           ms/op
ClientSimple.createUser                     sample  14086   2.273 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.753           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.023           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.128           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.918           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.284           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.564           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.564           ms/op
ClientSimple.existUser                      sample  17629   1.816 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.782           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.696           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.050           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.269           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.112           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.678           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.405           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.530           ms/op
ClientSimple.getUser                        sample  14680   2.178 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.757           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.054           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.662           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.900           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.546           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.750           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.138           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.138           ms/op
ClientSimple.listUser                       sample   8444   3.799 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.843           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.744           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.669           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.382           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.284           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.934           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.400           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.400           ms/op

Benchmark result is saved to 1712859037920.json
