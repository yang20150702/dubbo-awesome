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
# Warmup Iteration   1: 1.458 ops/ms
Iteration   1: 6.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.989 ops/ms


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
# Warmup Iteration   1: 5.393 ops/ms
Iteration   1: 12.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.463 ops/ms


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
# Warmup Iteration   1: 5.299 ops/ms
Iteration   1: 13.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.966 ops/ms


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
# Warmup Iteration   1: 6.041 ops/ms
Iteration   1: 8.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.023 ops/ms


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
# Warmup Iteration   1: 4.136 ±(99.9%) 0.085 ms/op
Iteration   1: 2.352 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.352 ms/op


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
# Warmup Iteration   1: 3.347 ±(99.9%) 0.060 ms/op
Iteration   1: 1.804 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.804 ms/op


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
# Warmup Iteration   1: 3.393 ±(99.9%) 0.059 ms/op
Iteration   1: 2.466 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.466 ms/op


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
# Warmup Iteration   1: 4.443 ±(99.9%) 0.087 ms/op
Iteration   1: 3.479 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.479 ms/op


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
# Warmup Iteration   1: 3.547 ±(99.9%) 0.084 ms/op
Iteration   1: 2.013 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   1.909 ms/op
                 createUser·p0.90:   2.396 ms/op
                 createUser·p0.95:   2.630 ms/op
                 createUser·p0.99:   5.226 ms/op
                 createUser·p0.999:  14.533 ms/op
                 createUser·p0.9999: 15.114 ms/op
                 createUser·p1.00:   15.548 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15887
  mean =      2.013 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 403 
    [ 1.250,  2.500) = 14374 
    [ 2.500,  3.750) = 896 
    [ 3.750,  5.000) = 28 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 63 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      5.226 ms/op
     p(99.9000) =     14.533 ms/op
     p(99.9900) =     15.114 ms/op
     p(99.9990) =     15.548 ms/op
     p(99.9999) =     15.548 ms/op
    p(100.0000) =     15.548 ms/op


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
# Warmup Iteration   1: 3.063 ±(99.9%) 0.074 ms/op
Iteration   1: 1.750 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.626 ms/op
                 existUser·p0.50:   1.559 ms/op
                 existUser·p0.90:   2.224 ms/op
                 existUser·p0.95:   2.408 ms/op
                 existUser·p0.99:   3.387 ms/op
                 existUser·p0.999:  25.582 ms/op
                 existUser·p0.9999: 26.029 ms/op
                 existUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18298
  mean =      1.750 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17689 
    [ 2.500,  5.000) = 532 
    [ 5.000,  7.500) = 13 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      1.559 ms/op
     p(90.0000) =      2.224 ms/op
     p(95.0000) =      2.408 ms/op
     p(99.0000) =      3.387 ms/op
     p(99.9000) =     25.582 ms/op
     p(99.9900) =     26.029 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 3.050 ±(99.9%) 0.081 ms/op
Iteration   1: 2.235 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   2.150 ms/op
                 getUser·p0.90:   2.654 ms/op
                 getUser·p0.95:   2.884 ms/op
                 getUser·p0.99:   4.915 ms/op
                 getUser·p0.999:  17.512 ms/op
                 getUser·p0.9999: 18.018 ms/op
                 getUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14286
  mean =      2.235 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 11848 
    [ 2.500,  3.750) = 2126 
    [ 3.750,  5.000) = 130 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      2.150 ms/op
     p(90.0000) =      2.654 ms/op
     p(95.0000) =      2.884 ms/op
     p(99.0000) =      4.915 ms/op
     p(99.9000) =     17.512 ms/op
     p(99.9900) =     18.018 ms/op
     p(99.9990) =     18.088 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 4.931 ±(99.9%) 0.157 ms/op
Iteration   1: 3.765 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   6.514 ms/op
                 listUser·p0.999:  13.836 ms/op
                 listUser·p0.9999: 14.270 ms/op
                 listUser·p1.00:   14.270 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8498
  mean =      3.765 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 390 
    [ 2.500,  3.750) = 4176 
    [ 3.750,  5.000) = 3535 
    [ 5.000,  6.250) = 305 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      6.514 ms/op
     p(99.9000) =     13.836 ms/op
     p(99.9900) =     14.270 ms/op
     p(99.9990) =     14.270 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.989          ops/ms
ClientSimple.existUser                       thrpt         12.463          ops/ms
ClientSimple.getUser                         thrpt         13.966          ops/ms
ClientSimple.listUser                        thrpt          8.023          ops/ms
ClientSimple.createUser                       avgt          2.352           ms/op
ClientSimple.existUser                        avgt          1.804           ms/op
ClientSimple.getUser                          avgt          2.466           ms/op
ClientSimple.listUser                         avgt          3.479           ms/op
ClientSimple.createUser                     sample  15887   2.013 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.754           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.909           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.396           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.630           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.226           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.533           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.114           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.548           ms/op
ClientSimple.existUser                      sample  18298   1.750 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.626           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.559           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.224           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.408           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.387           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.582           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.029           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.083           ms/op
ClientSimple.getUser                        sample  14286   2.235 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.754           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.150           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.654           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.884           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.915           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.512           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.018           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.088           ms/op
ClientSimple.listUser                       sample   8498   3.765 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.141           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.707           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.481           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.948           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.514           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.836           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.270           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.270           ms/op

Benchmark result is saved to 1717503375927.json
