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
# Warmup Iteration   1: 1.523 ops/ms
Iteration   1: 7.201 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.201 ops/ms


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
# Warmup Iteration   1: 5.260 ops/ms
Iteration   1: 11.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.601 ops/ms


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
# Warmup Iteration   1: 5.084 ops/ms
Iteration   1: 11.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.413 ops/ms


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
# Warmup Iteration   1: 3.902 ops/ms
Iteration   1: 9.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.225 ops/ms


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
# Warmup Iteration   1: 3.900 ±(99.9%) 0.081 ms/op
Iteration   1: 2.526 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.526 ms/op


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
# Warmup Iteration   1: 3.294 ±(99.9%) 0.051 ms/op
Iteration   1: 1.951 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.951 ms/op


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
# Warmup Iteration   1: 3.415 ±(99.9%) 0.059 ms/op
Iteration   1: 1.948 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.948 ms/op


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
# Warmup Iteration   1: 4.818 ±(99.9%) 0.092 ms/op
Iteration   1: 3.598 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.598 ms/op


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
# Warmup Iteration   1: 3.775 ±(99.9%) 0.119 ms/op
Iteration   1: 2.198 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.563 ms/op
                 createUser·p0.50:   1.937 ms/op
                 createUser·p0.90:   2.597 ms/op
                 createUser·p0.95:   2.884 ms/op
                 createUser·p0.99:   7.062 ms/op
                 createUser·p0.999:  20.709 ms/op
                 createUser·p0.9999: 21.037 ms/op
                 createUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14590
  mean =      2.198 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12767 
    [ 2.500,  5.000) = 1613 
    [ 5.000,  7.500) = 75 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      1.937 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      2.884 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     20.709 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     21.037 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


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
# Warmup Iteration   1: 2.959 ±(99.9%) 0.062 ms/op
Iteration   1: 2.015 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.412 ms/op
                 existUser·p0.50:   1.944 ms/op
                 existUser·p0.90:   2.466 ms/op
                 existUser·p0.95:   2.630 ms/op
                 existUser·p0.99:   3.809 ms/op
                 existUser·p0.999:  17.075 ms/op
                 existUser·p0.9999: 17.413 ms/op
                 existUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15902
  mean =      2.015 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 354 
    [ 1.250,  2.500) = 14178 
    [ 2.500,  3.750) = 1204 
    [ 3.750,  5.000) = 117 
    [ 5.000,  6.250) = 17 
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
      p(0.0000) =      0.412 ms/op
     p(50.0000) =      1.944 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =     17.075 ms/op
     p(99.9900) =     17.413 ms/op
     p(99.9990) =     17.433 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


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
# Warmup Iteration   1: 3.251 ±(99.9%) 0.092 ms/op
Iteration   1: 2.188 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.461 ms/op
                 getUser·p0.50:   2.146 ms/op
                 getUser·p0.90:   2.720 ms/op
                 getUser·p0.95:   2.920 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  14.816 ms/op
                 getUser·p0.9999: 15.237 ms/op
                 getUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14608
  mean =      2.188 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 622 
    [ 1.250,  2.500) = 10561 
    [ 2.500,  3.750) = 3180 
    [ 3.750,  5.000) = 202 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.461 ms/op
     p(50.0000) =      2.146 ms/op
     p(90.0000) =      2.720 ms/op
     p(95.0000) =      2.920 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =     14.816 ms/op
     p(99.9900) =     15.237 ms/op
     p(99.9990) =     15.237 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


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
# Warmup Iteration   1: 4.462 ±(99.9%) 0.131 ms/op
Iteration   1: 3.278 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   8.164 ms/op
                 listUser·p0.999:  17.826 ms/op
                 listUser·p0.9999: 17.924 ms/op
                 listUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9748
  mean =      3.278 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1013 
    [ 2.500,  3.750) = 6782 
    [ 3.750,  5.000) = 1714 
    [ 5.000,  6.250) = 103 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      8.164 ms/op
     p(99.9000) =     17.826 ms/op
     p(99.9900) =     17.924 ms/op
     p(99.9990) =     17.924 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.201          ops/ms
ClientSimple.existUser                       thrpt         11.601          ops/ms
ClientSimple.getUser                         thrpt         11.413          ops/ms
ClientSimple.listUser                        thrpt          9.225          ops/ms
ClientSimple.createUser                       avgt          2.526           ms/op
ClientSimple.existUser                        avgt          1.951           ms/op
ClientSimple.getUser                          avgt          1.948           ms/op
ClientSimple.listUser                         avgt          3.598           ms/op
ClientSimple.createUser                     sample  14590   2.198 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.563           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.937           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.597           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.884           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.062           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.709           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.037           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.037           ms/op
ClientSimple.existUser                      sample  15902   2.015 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.412           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.944           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.466           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.630           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.809           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.075           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.413           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.433           ms/op
ClientSimple.getUser                        sample  14608   2.188 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.461           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.146           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.720           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.920           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.252           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.816           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.237           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.237           ms/op
ClientSimple.listUser                       sample   9748   3.278 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.100           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.035           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.055           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.391           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.164           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.826           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.924           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.924           ms/op

Benchmark result is saved to 1716597505248.json
