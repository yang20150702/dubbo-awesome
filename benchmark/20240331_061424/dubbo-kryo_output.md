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
# Warmup Iteration   1: 1.790 ops/ms
Iteration   1: 6.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.685 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.075 ops/ms
Iteration   1: 13.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.285 ops/ms


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
# Warmup Iteration   1: 6.655 ops/ms
Iteration   1: 15.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.446 ops/ms


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
# Warmup Iteration   1: 5.432 ops/ms
Iteration   1: 8.495 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.495 ops/ms


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
# Warmup Iteration   1: 3.807 ±(99.9%) 0.073 ms/op
Iteration   1: 2.112 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.112 ms/op


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
# Warmup Iteration   1: 3.110 ±(99.9%) 0.053 ms/op
Iteration   1: 1.793 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.793 ms/op


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
# Warmup Iteration   1: 3.216 ±(99.9%) 0.056 ms/op
Iteration   1: 1.966 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.966 ms/op


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
# Warmup Iteration   1: 5.092 ±(99.9%) 0.109 ms/op
Iteration   1: 3.402 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.402 ms/op


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
# Warmup Iteration   1: 3.684 ±(99.9%) 0.110 ms/op
Iteration   1: 2.507 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   2.421 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.326 ms/op
                 createUser·p0.99:   6.970 ms/op
                 createUser·p0.999:  17.269 ms/op
                 createUser·p0.9999: 17.984 ms/op
                 createUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12957
  mean =      2.507 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 165 
    [ 1.250,  2.500) = 7398 
    [ 2.500,  3.750) = 4999 
    [ 3.750,  5.000) = 183 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      2.421 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.326 ms/op
     p(99.0000) =      6.970 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     17.984 ms/op
     p(99.9990) =     18.022 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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
# Warmup Iteration   1: 2.887 ±(99.9%) 0.077 ms/op
Iteration   1: 2.043 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.600 ms/op
                 existUser·p0.50:   1.946 ms/op
                 existUser·p0.90:   2.535 ms/op
                 existUser·p0.95:   2.875 ms/op
                 existUser·p0.99:   4.768 ms/op
                 existUser·p0.999:  13.124 ms/op
                 existUser·p0.9999: 13.305 ms/op
                 existUser·p1.00:   13.369 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15637
  mean =      2.043 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 400 
    [ 1.250,  2.500) = 13526 
    [ 2.500,  3.750) = 1498 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      1.946 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.875 ms/op
     p(99.0000) =      4.768 ms/op
     p(99.9000) =     13.124 ms/op
     p(99.9900) =     13.305 ms/op
     p(99.9990) =     13.369 ms/op
     p(99.9999) =     13.369 ms/op
    p(100.0000) =     13.369 ms/op


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
# Warmup Iteration   1: 3.162 ±(99.9%) 0.072 ms/op
Iteration   1: 1.953 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.454 ms/op
                 getUser·p0.50:   1.817 ms/op
                 getUser·p0.90:   2.429 ms/op
                 getUser·p0.95:   2.654 ms/op
                 getUser·p0.99:   3.265 ms/op
                 getUser·p0.999:  17.092 ms/op
                 getUser·p0.9999: 17.313 ms/op
                 getUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16382
  mean =      1.953 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 202 
    [ 1.250,  2.500) = 14883 
    [ 2.500,  3.750) = 1217 
    [ 3.750,  5.000) = 41 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.454 ms/op
     p(50.0000) =      1.817 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      3.265 ms/op
     p(99.9000) =     17.092 ms/op
     p(99.9900) =     17.313 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 4.754 ±(99.9%) 0.123 ms/op
Iteration   1: 3.126 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   0.969 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   4.212 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.390 ms/op
                 listUser·p0.999:  20.753 ms/op
                 listUser·p0.9999: 21.332 ms/op
                 listUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10218
  mean =      3.126 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3131 
    [ 2.500,  5.000) = 6883 
    [ 5.000,  7.500) = 171 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      4.212 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     20.753 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.685          ops/ms
ClientSimple.existUser                       thrpt         13.285          ops/ms
ClientSimple.getUser                         thrpt         15.446          ops/ms
ClientSimple.listUser                        thrpt          8.495          ops/ms
ClientSimple.createUser                       avgt          2.112           ms/op
ClientSimple.existUser                        avgt          1.793           ms/op
ClientSimple.getUser                          avgt          1.966           ms/op
ClientSimple.listUser                         avgt          3.402           ms/op
ClientSimple.createUser                     sample  12957   2.507 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.653           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.421           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.011           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.326           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.970           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.269           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.984           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.022           ms/op
ClientSimple.existUser                      sample  15637   2.043 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.600           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.946           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.535           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.875           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.768           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.124           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.305           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.369           ms/op
ClientSimple.getUser                        sample  16382   1.953 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.454           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.817           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.429           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.654           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.265           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.092           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.313           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.334           ms/op
ClientSimple.listUser                       sample  10218   3.126 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.969           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.937           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.212           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.390           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.753           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.332           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.332           ms/op

Benchmark result is saved to 1711865407592.json
