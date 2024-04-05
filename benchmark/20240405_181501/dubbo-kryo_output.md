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
# Warmup Iteration   1: 1.793 ops/ms
Iteration   1: 7.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.843 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.750 ops/ms
Iteration   1: 12.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.931 ops/ms


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
# Warmup Iteration   1: 5.891 ops/ms
Iteration   1: 12.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.719 ops/ms


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
# Warmup Iteration   1: 5.700 ops/ms
Iteration   1: 8.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.633 ops/ms


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
# Warmup Iteration   1: 3.829 ±(99.9%) 0.067 ms/op
Iteration   1: 2.132 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.132 ms/op


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
# Warmup Iteration   1: 3.053 ±(99.9%) 0.051 ms/op
Iteration   1: 1.937 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.937 ms/op


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
# Warmup Iteration   1: 3.099 ±(99.9%) 0.063 ms/op
Iteration   1: 1.993 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.993 ms/op


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
# Warmup Iteration   1: 4.509 ±(99.9%) 0.094 ms/op
Iteration   1: 3.146 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.146 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.687 ±(99.9%) 0.106 ms/op
Iteration   1: 2.470 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   2.261 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.437 ms/op
                 createUser·p0.99:   6.991 ms/op
                 createUser·p0.999:  20.054 ms/op
                 createUser·p0.9999: 21.856 ms/op
                 createUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12934
  mean =      2.470 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9188 
    [ 2.500,  5.000) = 3494 
    [ 5.000,  7.500) = 140 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      2.261 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.437 ms/op
     p(99.0000) =      6.991 ms/op
     p(99.9000) =     20.054 ms/op
     p(99.9900) =     21.856 ms/op
     p(99.9990) =     21.856 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


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
# Warmup Iteration   1: 2.912 ±(99.9%) 0.070 ms/op
Iteration   1: 1.803 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.517 ms/op
                 existUser·p0.50:   1.651 ms/op
                 existUser·p0.90:   2.466 ms/op
                 existUser·p0.95:   2.748 ms/op
                 existUser·p0.99:   3.117 ms/op
                 existUser·p0.999:  12.486 ms/op
                 existUser·p0.9999: 13.213 ms/op
                 existUser·p1.00:   13.238 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17727
  mean =      1.803 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 479 
    [ 1.250,  2.500) = 15585 
    [ 2.500,  3.750) = 1618 
    [ 3.750,  5.000) = 10 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      1.651 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      3.117 ms/op
     p(99.9000) =     12.486 ms/op
     p(99.9900) =     13.213 ms/op
     p(99.9990) =     13.238 ms/op
     p(99.9999) =     13.238 ms/op
    p(100.0000) =     13.238 ms/op


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
# Warmup Iteration   1: 3.208 ±(99.9%) 0.077 ms/op
Iteration   1: 1.916 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.682 ms/op
                 getUser·p0.50:   1.821 ms/op
                 getUser·p0.90:   2.294 ms/op
                 getUser·p0.95:   2.540 ms/op
                 getUser·p0.99:   3.133 ms/op
                 getUser·p0.999:  14.325 ms/op
                 getUser·p0.9999: 14.505 ms/op
                 getUser·p1.00:   14.516 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16937
  mean =      1.916 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 121 
    [ 1.250,  2.500) = 15875 
    [ 2.500,  3.750) = 857 
    [ 3.750,  5.000) = 18 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 24 
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
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.294 ms/op
     p(95.0000) =      2.540 ms/op
     p(99.0000) =      3.133 ms/op
     p(99.9000) =     14.325 ms/op
     p(99.9900) =     14.505 ms/op
     p(99.9990) =     14.516 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


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
# Warmup Iteration   1: 4.450 ±(99.9%) 0.155 ms/op
Iteration   1: 3.373 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   3.441 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.018 ms/op
                 listUser·p0.999:  9.683 ms/op
                 listUser·p0.9999: 13.468 ms/op
                 listUser·p1.00:   13.468 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9504
  mean =      3.373 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 1858 
    [ 2.500,  3.750) = 4535 
    [ 3.750,  5.000) = 2768 
    [ 5.000,  6.250) = 229 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      7.018 ms/op
     p(99.9000) =      9.683 ms/op
     p(99.9900) =     13.468 ms/op
     p(99.9990) =     13.468 ms/op
     p(99.9999) =     13.468 ms/op
    p(100.0000) =     13.468 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.843          ops/ms
ClientSimple.existUser                       thrpt         12.931          ops/ms
ClientSimple.getUser                         thrpt         12.719          ops/ms
ClientSimple.listUser                        thrpt          8.633          ops/ms
ClientSimple.createUser                       avgt          2.132           ms/op
ClientSimple.existUser                        avgt          1.937           ms/op
ClientSimple.getUser                          avgt          1.993           ms/op
ClientSimple.listUser                         avgt          3.146           ms/op
ClientSimple.createUser                     sample  12934   2.470 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.633           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.261           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.076           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.437           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.991           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.054           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.856           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.856           ms/op
ClientSimple.existUser                      sample  17727   1.803 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.517           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.651           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.466           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.748           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.117           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.486           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.213           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.238           ms/op
ClientSimple.getUser                        sample  16937   1.916 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.682           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.821           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.294           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.540           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.133           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.325           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.505           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.516           ms/op
ClientSimple.listUser                       sample   9504   3.373 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.149           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.441           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.612           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.018           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.683           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.468           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.468           ms/op

Benchmark result is saved to 1712340660814.json
