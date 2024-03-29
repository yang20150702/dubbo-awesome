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
# Warmup Iteration   1: 1.751 ops/ms
Iteration   1: 6.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.423 ops/ms


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
# Warmup Iteration   1: 6.513 ops/ms
Iteration   1: 14.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.267 ops/ms


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
# Warmup Iteration   1: 6.056 ops/ms
Iteration   1: 14.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.338 ops/ms


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
# Warmup Iteration   1: 5.318 ops/ms
Iteration   1: 8.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.382 ops/ms


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
# Warmup Iteration   1: 3.508 ±(99.9%) 0.061 ms/op
Iteration   1: 2.041 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.041 ms/op


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
# Warmup Iteration   1: 3.112 ±(99.9%) 0.051 ms/op
Iteration   1: 2.164 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.164 ms/op


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
# Warmup Iteration   1: 3.018 ±(99.9%) 0.049 ms/op
Iteration   1: 2.042 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.042 ms/op


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
# Warmup Iteration   1: 4.678 ±(99.9%) 0.097 ms/op
Iteration   1: 3.867 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.867 ms/op


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
# Warmup Iteration   1: 3.648 ±(99.9%) 0.099 ms/op
Iteration   1: 2.179 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.482 ms/op
                 createUser·p0.50:   2.013 ms/op
                 createUser·p0.90:   2.609 ms/op
                 createUser·p0.95:   2.908 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  19.661 ms/op
                 createUser·p0.9999: 20.611 ms/op
                 createUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14757
  mean =      2.179 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12817 
    [ 2.500,  5.000) = 1757 
    [ 5.000,  7.500) = 56 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      2.013 ms/op
     p(90.0000) =      2.609 ms/op
     p(95.0000) =      2.908 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     19.661 ms/op
     p(99.9900) =     20.611 ms/op
     p(99.9990) =     20.611 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 3.003 ±(99.9%) 0.074 ms/op
Iteration   1: 1.829 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.446 ms/op
                 existUser·p0.50:   1.698 ms/op
                 existUser·p0.90:   2.408 ms/op
                 existUser·p0.95:   2.642 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  13.494 ms/op
                 existUser·p0.9999: 14.721 ms/op
                 existUser·p1.00:   15.172 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17864
  mean =      1.829 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 496 
    [ 1.250,  2.500) = 15960 
    [ 2.500,  3.750) = 1260 
    [ 3.750,  5.000) = 110 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.446 ms/op
     p(50.0000) =      1.698 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      3.453 ms/op
     p(99.9000) =     13.494 ms/op
     p(99.9900) =     14.721 ms/op
     p(99.9990) =     15.172 ms/op
     p(99.9999) =     15.172 ms/op
    p(100.0000) =     15.172 ms/op


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
# Warmup Iteration   1: 3.093 ±(99.9%) 0.090 ms/op
Iteration   1: 2.118 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.497 ms/op
                 getUser·p0.50:   2.077 ms/op
                 getUser·p0.90:   2.605 ms/op
                 getUser·p0.95:   2.839 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  11.074 ms/op
                 getUser·p0.9999: 11.893 ms/op
                 getUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15088
  mean =      2.118 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 435 
    [ 1.250,  2.500) = 12574 
    [ 2.500,  3.750) = 1835 
    [ 3.750,  5.000) = 111 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      2.077 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.839 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =     11.074 ms/op
     p(99.9900) =     11.893 ms/op
     p(99.9990) =     11.993 ms/op
     p(99.9999) =     11.993 ms/op
    p(100.0000) =     11.993 ms/op


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
# Warmup Iteration   1: 4.162 ±(99.9%) 0.114 ms/op
Iteration   1: 3.338 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.881 ms/op
                 listUser·p0.50:   3.236 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.067 ms/op
                 listUser·p0.999:  18.842 ms/op
                 listUser·p0.9999: 19.726 ms/op
                 listUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9587
  mean =      3.338 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1442 
    [ 2.500,  3.750) = 5444 
    [ 3.750,  5.000) = 2509 
    [ 5.000,  6.250) = 98 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.067 ms/op
     p(99.9000) =     18.842 ms/op
     p(99.9900) =     19.726 ms/op
     p(99.9990) =     19.726 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.423          ops/ms
ClientSimple.existUser                       thrpt         14.267          ops/ms
ClientSimple.getUser                         thrpt         14.338          ops/ms
ClientSimple.listUser                        thrpt          8.382          ops/ms
ClientSimple.createUser                       avgt          2.041           ms/op
ClientSimple.existUser                        avgt          2.164           ms/op
ClientSimple.getUser                          avgt          2.042           ms/op
ClientSimple.listUser                         avgt          3.867           ms/op
ClientSimple.createUser                     sample  14757   2.179 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.482           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.013           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.609           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.908           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.661           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.661           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.611           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.611           ms/op
ClientSimple.existUser                      sample  17864   1.829 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.446           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.698           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.408           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.642           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.453           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.494           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.721           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.172           ms/op
ClientSimple.getUser                        sample  15088   2.118 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.497           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.077           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.605           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.839           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.612           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.074           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.893           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.993           ms/op
ClientSimple.listUser                       sample   9587   3.338 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.881           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.236           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.506           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.067           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.842           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.726           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.726           ms/op

Benchmark result is saved to 1711692679661.json
