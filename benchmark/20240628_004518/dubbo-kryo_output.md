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
# Warmup Iteration   1: 1.650 ops/ms
Iteration   1: 6.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.921 ops/ms


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
# Warmup Iteration   1: 5.562 ops/ms
Iteration   1: 11.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.933 ops/ms


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
# Warmup Iteration   1: 6.671 ops/ms
Iteration   1: 13.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.780 ops/ms


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
# Warmup Iteration   1: 4.534 ops/ms
Iteration   1: 8.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.280 ops/ms


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
# Warmup Iteration   1: 4.030 ±(99.9%) 0.081 ms/op
Iteration   1: 2.422 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.422 ms/op


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
# Warmup Iteration   1: 3.272 ±(99.9%) 0.068 ms/op
Iteration   1: 2.212 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.212 ms/op


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
# Warmup Iteration   1: 3.445 ±(99.9%) 0.063 ms/op
Iteration   1: 2.014 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.014 ms/op


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
# Warmup Iteration   1: 4.963 ±(99.9%) 0.089 ms/op
Iteration   1: 3.168 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.168 ms/op


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
# Warmup Iteration   1: 5.048 ±(99.9%) 0.252 ms/op
Iteration   1: 2.304 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.760 ms/op
                 createUser·p0.50:   2.050 ms/op
                 createUser·p0.90:   2.605 ms/op
                 createUser·p0.95:   3.040 ms/op
                 createUser·p0.99:   11.817 ms/op
                 createUser·p0.999:  21.299 ms/op
                 createUser·p0.9999: 22.381 ms/op
                 createUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13873
  mean =      2.304 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11982 
    [ 2.500,  5.000) = 1549 
    [ 5.000,  7.500) = 114 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      2.050 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      3.040 ms/op
     p(99.0000) =     11.817 ms/op
     p(99.9000) =     21.299 ms/op
     p(99.9900) =     22.381 ms/op
     p(99.9990) =     22.381 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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
# Warmup Iteration   1: 3.064 ±(99.9%) 0.073 ms/op
Iteration   1: 1.819 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.579 ms/op
                 existUser·p0.50:   1.712 ms/op
                 existUser·p0.90:   2.064 ms/op
                 existUser·p0.95:   2.400 ms/op
                 existUser·p0.99:   3.184 ms/op
                 existUser·p0.999:  17.236 ms/op
                 existUser·p0.9999: 17.899 ms/op
                 existUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17578
  mean =      1.819 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 239 
    [ 1.250,  2.500) = 16567 
    [ 2.500,  3.750) = 661 
    [ 3.750,  5.000) = 29 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      1.712 ms/op
     p(90.0000) =      2.064 ms/op
     p(95.0000) =      2.400 ms/op
     p(99.0000) =      3.184 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     17.899 ms/op
     p(99.9990) =     17.924 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 3.684 ±(99.9%) 0.104 ms/op
Iteration   1: 1.759 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.568 ms/op
                 getUser·p0.50:   1.585 ms/op
                 getUser·p0.90:   2.347 ms/op
                 getUser·p0.95:   2.544 ms/op
                 getUser·p0.99:   3.709 ms/op
                 getUser·p0.999:  13.973 ms/op
                 getUser·p0.9999: 14.238 ms/op
                 getUser·p1.00:   14.238 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18175
  mean =      1.759 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1010 
    [ 1.250,  2.500) = 16124 
    [ 2.500,  3.750) = 864 
    [ 3.750,  5.000) = 104 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      1.585 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.544 ms/op
     p(99.0000) =      3.709 ms/op
     p(99.9000) =     13.973 ms/op
     p(99.9900) =     14.238 ms/op
     p(99.9990) =     14.238 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 4.729 ±(99.9%) 0.158 ms/op
Iteration   1: 3.048 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   2.867 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.071 ms/op
                 listUser·p0.99:   4.630 ms/op
                 listUser·p0.999:  8.373 ms/op
                 listUser·p0.9999: 10.540 ms/op
                 listUser·p1.00:   10.568 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10483
  mean =      3.048 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 105 
    [ 2.000,  3.000) = 6302 
    [ 3.000,  4.000) = 3392 
    [ 4.000,  5.000) = 622 
    [ 5.000,  6.000) = 37 
    [ 6.000,  7.000) = 4 
    [ 7.000,  8.000) = 8 
    [ 8.000,  9.000) = 9 
    [ 9.000, 10.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      4.630 ms/op
     p(99.9000) =      8.373 ms/op
     p(99.9900) =     10.540 ms/op
     p(99.9990) =     10.568 ms/op
     p(99.9999) =     10.568 ms/op
    p(100.0000) =     10.568 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.921          ops/ms
ClientSimple.existUser                       thrpt         11.933          ops/ms
ClientSimple.getUser                         thrpt         13.780          ops/ms
ClientSimple.listUser                        thrpt          8.280          ops/ms
ClientSimple.createUser                       avgt          2.422           ms/op
ClientSimple.existUser                        avgt          2.212           ms/op
ClientSimple.getUser                          avgt          2.014           ms/op
ClientSimple.listUser                         avgt          3.168           ms/op
ClientSimple.createUser                     sample  13873   2.304 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.760           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.050           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.605           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.040           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.817           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.299           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.381           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.381           ms/op
ClientSimple.existUser                      sample  17578   1.819 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.579           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.712           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.064           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.400           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.184           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.236           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.899           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.924           ms/op
ClientSimple.getUser                        sample  18175   1.759 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.568           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.585           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.347           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.544           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.709           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.973           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.238           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.238           ms/op
ClientSimple.listUser                       sample  10483   3.048 ± 0.020   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.055           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.867           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.875           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.071           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.630           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.373           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.540           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.568           ms/op

Benchmark result is saved to 1719535271452.json
