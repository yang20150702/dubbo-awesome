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
# Warmup Iteration   1: 1.870 ops/ms
Iteration   1: 6.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.150 ops/ms


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
# Warmup Iteration   1: 5.816 ops/ms
Iteration   1: 14.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.087 ops/ms


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
# Warmup Iteration   1: 5.282 ops/ms
Iteration   1: 13.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.290 ops/ms


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
# Warmup Iteration   1: 5.131 ops/ms
Iteration   1: 9.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.369 ops/ms


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
# Warmup Iteration   1: 3.550 ±(99.9%) 0.067 ms/op
Iteration   1: 2.110 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.110 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.143 ±(99.9%) 0.050 ms/op
Iteration   1: 1.918 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.918 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.415 ±(99.9%) 0.054 ms/op
Iteration   1: 2.230 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.230 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.849 ±(99.9%) 0.107 ms/op
Iteration   1: 3.565 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.565 ms/op


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
# Warmup Iteration   1: 3.296 ±(99.9%) 0.076 ms/op
Iteration   1: 2.349 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.527 ms/op
                 createUser·p0.50:   2.146 ms/op
                 createUser·p0.90:   2.879 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   9.650 ms/op
                 createUser·p0.999:  17.408 ms/op
                 createUser·p0.9999: 17.941 ms/op
                 createUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13741
  mean =      2.349 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 385 
    [ 1.250,  2.500) = 9455 
    [ 2.500,  3.750) = 3501 
    [ 3.750,  5.000) = 141 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      2.146 ms/op
     p(90.0000) =      2.879 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      9.650 ms/op
     p(99.9000) =     17.408 ms/op
     p(99.9900) =     17.941 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 3.003 ±(99.9%) 0.071 ms/op
Iteration   1: 2.054 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.365 ms/op
                 existUser·p0.50:   1.976 ms/op
                 existUser·p0.90:   2.617 ms/op
                 existUser·p0.95:   2.757 ms/op
                 existUser·p0.99:   3.523 ms/op
                 existUser·p0.999:  12.941 ms/op
                 existUser·p0.9999: 13.851 ms/op
                 existUser·p1.00:   14.107 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15578
  mean =      2.054 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 386 
    [ 1.250,  2.500) = 12537 
    [ 2.500,  3.750) = 2558 
    [ 3.750,  5.000) = 64 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.365 ms/op
     p(50.0000) =      1.976 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      3.523 ms/op
     p(99.9000) =     12.941 ms/op
     p(99.9900) =     13.851 ms/op
     p(99.9990) =     14.107 ms/op
     p(99.9999) =     14.107 ms/op
    p(100.0000) =     14.107 ms/op


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
# Warmup Iteration   1: 3.528 ±(99.9%) 0.109 ms/op
Iteration   1: 2.196 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   0.554 ms/op
                 getUser·p0.50:   2.054 ms/op
                 getUser·p0.90:   2.601 ms/op
                 getUser·p0.95:   2.871 ms/op
                 getUser·p0.99:   5.975 ms/op
                 getUser·p0.999:  22.213 ms/op
                 getUser·p0.9999: 22.807 ms/op
                 getUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14551
  mean =      2.196 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12360 
    [ 2.500,  5.000) = 1978 
    [ 5.000,  7.500) = 100 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      2.054 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.871 ms/op
     p(99.0000) =      5.975 ms/op
     p(99.9000) =     22.213 ms/op
     p(99.9900) =     22.807 ms/op
     p(99.9990) =     22.807 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 4.288 ±(99.9%) 0.149 ms/op
Iteration   1: 3.192 ±(99.9%) 0.068 ms/op
                 listUser·p0.00:   0.759 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   6.398 ms/op
                 listUser·p0.999:  36.438 ms/op
                 listUser·p0.9999: 36.700 ms/op
                 listUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10033
  mean =      3.192 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1607 
    [ 2.500,  5.000) = 8247 
    [ 5.000,  7.500) = 113 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     36.438 ms/op
     p(99.9900) =     36.700 ms/op
     p(99.9990) =     36.700 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.150          ops/ms
ClientSimple.existUser                       thrpt         14.087          ops/ms
ClientSimple.getUser                         thrpt         13.290          ops/ms
ClientSimple.listUser                        thrpt          9.369          ops/ms
ClientSimple.createUser                       avgt          2.110           ms/op
ClientSimple.existUser                        avgt          1.918           ms/op
ClientSimple.getUser                          avgt          2.230           ms/op
ClientSimple.listUser                         avgt          3.565           ms/op
ClientSimple.createUser                     sample  13741   2.349 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.527           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.146           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.879           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.138           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.650           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.408           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.941           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.990           ms/op
ClientSimple.existUser                      sample  15578   2.054 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.365           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.976           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.617           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.757           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.523           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.941           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.851           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.107           ms/op
ClientSimple.getUser                        sample  14551   2.196 ± 0.034   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.554           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.054           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.871           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.975           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.213           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.807           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.807           ms/op
ClientSimple.listUser                       sample  10033   3.192 ± 0.068   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.759           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.896           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.957           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.398           ms/op
ClientSimple.listUser:listUser·p0.999       sample         36.438           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         36.700           ms/op
ClientSimple.listUser:listUser·p1.00        sample         36.700           ms/op

Benchmark result is saved to 1718863988158.json
