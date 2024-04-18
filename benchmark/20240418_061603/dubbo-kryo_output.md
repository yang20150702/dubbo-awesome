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
# Warmup Iteration   1: 2.019 ops/ms
Iteration   1: 6.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.848 ops/ms


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
# Warmup Iteration   1: 7.077 ops/ms
Iteration   1: 14.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.236 ops/ms


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
# Warmup Iteration   1: 5.987 ops/ms
Iteration   1: 14.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.482 ops/ms


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
# Warmup Iteration   1: 4.855 ops/ms
Iteration   1: 8.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.507 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.687 ±(99.9%) 0.063 ms/op
Iteration   1: 2.147 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.147 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.961 ±(99.9%) 0.050 ms/op
Iteration   1: 1.862 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.862 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.305 ±(99.9%) 0.050 ms/op
Iteration   1: 1.945 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.945 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.711 ±(99.9%) 0.099 ms/op
Iteration   1: 3.045 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.045 ms/op


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
# Warmup Iteration   1: 3.624 ±(99.9%) 0.100 ms/op
Iteration   1: 2.185 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.483 ms/op
                 createUser·p0.50:   1.933 ms/op
                 createUser·p0.90:   2.642 ms/op
                 createUser·p0.95:   2.822 ms/op
                 createUser·p0.99:   11.511 ms/op
                 createUser·p0.999:  15.151 ms/op
                 createUser·p0.9999: 16.254 ms/op
                 createUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14620
  mean =      2.185 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 354 
    [ 1.250,  2.500) = 12089 
    [ 2.500,  3.750) = 1708 
    [ 3.750,  5.000) = 114 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      1.933 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =     11.511 ms/op
     p(99.9000) =     15.151 ms/op
     p(99.9900) =     16.254 ms/op
     p(99.9990) =     16.269 ms/op
     p(99.9999) =     16.269 ms/op
    p(100.0000) =     16.269 ms/op


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
# Warmup Iteration   1: 2.908 ±(99.9%) 0.080 ms/op
Iteration   1: 2.107 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.468 ms/op
                 existUser·p0.50:   2.122 ms/op
                 existUser·p0.90:   2.650 ms/op
                 existUser·p0.95:   2.864 ms/op
                 existUser·p0.99:   3.306 ms/op
                 existUser·p0.999:  5.002 ms/op
                 existUser·p0.9999: 6.416 ms/op
                 existUser·p1.00:   6.496 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15174
  mean =      2.107 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 2 
    [0.500, 1.000) = 124 
    [1.000, 1.500) = 1102 
    [1.500, 2.000) = 5227 
    [2.000, 2.500) = 5754 
    [2.500, 3.000) = 2529 
    [3.000, 3.500) = 344 
    [3.500, 4.000) = 38 
    [4.000, 4.500) = 32 
    [4.500, 5.000) = 7 
    [5.000, 5.500) = 12 
    [5.500, 6.000) = 0 
    [6.000, 6.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      2.122 ms/op
     p(90.0000) =      2.650 ms/op
     p(95.0000) =      2.864 ms/op
     p(99.0000) =      3.306 ms/op
     p(99.9000) =      5.002 ms/op
     p(99.9900) =      6.416 ms/op
     p(99.9990) =      6.496 ms/op
     p(99.9999) =      6.496 ms/op
    p(100.0000) =      6.496 ms/op


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
# Warmup Iteration   1: 3.165 ±(99.9%) 0.071 ms/op
Iteration   1: 2.243 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   0.628 ms/op
                 getUser·p0.50:   2.122 ms/op
                 getUser·p0.90:   2.707 ms/op
                 getUser·p0.95:   2.851 ms/op
                 getUser·p0.99:   3.863 ms/op
                 getUser·p0.999:  29.987 ms/op
                 getUser·p0.9999: 30.773 ms/op
                 getUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14440
  mean =      2.243 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11354 
    [ 2.500,  5.000) = 2999 
    [ 5.000,  7.500) = 19 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.122 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =     29.987 ms/op
     p(99.9900) =     30.773 ms/op
     p(99.9990) =     30.802 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


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
# Warmup Iteration   1: 4.370 ±(99.9%) 0.114 ms/op
Iteration   1: 3.598 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.342 ms/op
                 listUser·p0.999:  6.090 ms/op
                 listUser·p0.9999: 6.447 ms/op
                 listUser·p1.00:   6.447 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8883
  mean =      3.598 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 8 
    [1.500, 2.000) = 74 
    [2.000, 2.500) = 395 
    [2.500, 3.000) = 909 
    [3.000, 3.500) = 2316 
    [3.500, 4.000) = 3024 
    [4.000, 4.500) = 1661 
    [4.500, 5.000) = 352 
    [5.000, 5.500) = 88 
    [5.500, 6.000) = 46 
    [6.000, 6.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.249 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.342 ms/op
     p(99.9000) =      6.090 ms/op
     p(99.9900) =      6.447 ms/op
     p(99.9990) =      6.447 ms/op
     p(99.9999) =      6.447 ms/op
    p(100.0000) =      6.447 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.848          ops/ms
ClientSimple.existUser                       thrpt         14.236          ops/ms
ClientSimple.getUser                         thrpt         14.482          ops/ms
ClientSimple.listUser                        thrpt          8.507          ops/ms
ClientSimple.createUser                       avgt          2.147           ms/op
ClientSimple.existUser                        avgt          1.862           ms/op
ClientSimple.getUser                          avgt          1.945           ms/op
ClientSimple.listUser                         avgt          3.045           ms/op
ClientSimple.createUser                     sample  14620   2.185 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.483           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.933           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.642           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.822           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.511           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.151           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.254           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.269           ms/op
ClientSimple.existUser                      sample  15174   2.107 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.468           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.122           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.650           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.864           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.306           ms/op
ClientSimple.existUser:existUser·p0.999     sample          5.002           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          6.416           ms/op
ClientSimple.existUser:existUser·p1.00      sample          6.496           ms/op
ClientSimple.getUser                        sample  14440   2.243 ± 0.040   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.628           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.122           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.707           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.851           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.863           ms/op
ClientSimple.getUser:getUser·p0.999         sample         29.987           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         30.773           ms/op
ClientSimple.getUser:getUser·p1.00          sample         30.802           ms/op
ClientSimple.listUser                       sample   8883   3.598 ± 0.022   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.249           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.596           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.342           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.090           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.447           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.447           ms/op

Benchmark result is saved to 1713420712909.json
