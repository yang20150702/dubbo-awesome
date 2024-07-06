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
# Warmup Iteration   1: 1.504 ops/ms
Iteration   1: 6.404 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.404 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.233 ops/ms
Iteration   1: 11.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.257 ops/ms


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
# Warmup Iteration   1: 6.025 ops/ms
Iteration   1: 12.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.746 ops/ms


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
# Warmup Iteration   1: 4.632 ops/ms
Iteration   1: 8.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.789 ops/ms


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
# Warmup Iteration   1: 4.108 ±(99.9%) 0.071 ms/op
Iteration   1: 2.182 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.182 ms/op


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
# Warmup Iteration   1: 3.118 ±(99.9%) 0.053 ms/op
Iteration   1: 1.805 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.805 ms/op


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
# Warmup Iteration   1: 3.211 ±(99.9%) 0.062 ms/op
Iteration   1: 2.062 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.062 ms/op


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
# Warmup Iteration   1: 5.133 ±(99.9%) 0.100 ms/op
Iteration   1: 3.448 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.448 ms/op


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
# Warmup Iteration   1: 3.381 ±(99.9%) 0.100 ms/op
Iteration   1: 2.061 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.761 ms/op
                 createUser·p0.50:   1.954 ms/op
                 createUser·p0.90:   2.515 ms/op
                 createUser·p0.95:   2.761 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  15.033 ms/op
                 createUser·p0.9999: 16.950 ms/op
                 createUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15726
  mean =      2.061 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 13955 
    [ 2.500,  3.750) = 1421 
    [ 3.750,  5.000) = 59 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      1.954 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.761 ms/op
     p(99.0000) =      5.251 ms/op
     p(99.9000) =     15.033 ms/op
     p(99.9900) =     16.950 ms/op
     p(99.9990) =     17.203 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 3.197 ±(99.9%) 0.094 ms/op
Iteration   1: 1.971 ±(99.9%) 0.040 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   1.817 ms/op
                 existUser·p0.90:   2.388 ms/op
                 existUser·p0.95:   2.580 ms/op
                 existUser·p0.99:   4.809 ms/op
                 existUser·p0.999:  34.800 ms/op
                 existUser·p0.9999: 34.911 ms/op
                 existUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16471
  mean =      1.971 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15364 
    [ 2.500,  5.000) = 955 
    [ 5.000,  7.500) = 88 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      1.817 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.580 ms/op
     p(99.0000) =      4.809 ms/op
     p(99.9000) =     34.800 ms/op
     p(99.9900) =     34.911 ms/op
     p(99.9990) =     34.996 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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
# Warmup Iteration   1: 3.192 ±(99.9%) 0.083 ms/op
Iteration   1: 2.392 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.028 ms/op
                 getUser·p0.50:   2.298 ms/op
                 getUser·p0.90:   2.822 ms/op
                 getUser·p0.95:   3.012 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  12.975 ms/op
                 getUser·p0.9999: 13.129 ms/op
                 getUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13353
  mean =      2.392 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 9096 
    [ 2.500,  3.750) = 4006 
    [ 3.750,  5.000) = 120 
    [ 5.000,  6.250) = 54 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      2.298 ms/op
     p(90.0000) =      2.822 ms/op
     p(95.0000) =      3.012 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =     12.975 ms/op
     p(99.9900) =     13.129 ms/op
     p(99.9990) =     13.173 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


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
# Warmup Iteration   1: 4.524 ±(99.9%) 0.110 ms/op
Iteration   1: 3.305 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.886 ms/op
                 listUser·p0.50:   3.342 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.259 ms/op
                 listUser·p0.999:  10.195 ms/op
                 listUser·p0.9999: 10.322 ms/op
                 listUser·p1.00:   10.322 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9716
  mean =      3.305 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 172 
    [ 2.000,  3.000) = 3342 
    [ 3.000,  4.000) = 4714 
    [ 4.000,  5.000) = 1374 
    [ 5.000,  6.000) = 30 
    [ 6.000,  7.000) = 50 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =     10.195 ms/op
     p(99.9900) =     10.322 ms/op
     p(99.9990) =     10.322 ms/op
     p(99.9999) =     10.322 ms/op
    p(100.0000) =     10.322 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.404          ops/ms
ClientSimple.existUser                       thrpt         11.257          ops/ms
ClientSimple.getUser                         thrpt         12.746          ops/ms
ClientSimple.listUser                        thrpt          8.789          ops/ms
ClientSimple.createUser                       avgt          2.182           ms/op
ClientSimple.existUser                        avgt          1.805           ms/op
ClientSimple.getUser                          avgt          2.062           ms/op
ClientSimple.listUser                         avgt          3.448           ms/op
ClientSimple.createUser                     sample  15726   2.061 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.761           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.954           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.515           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.761           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.251           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.033           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.950           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.203           ms/op
ClientSimple.existUser                      sample  16471   1.971 ± 0.040   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.727           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.817           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.388           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.580           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.809           ms/op
ClientSimple.existUser:existUser·p0.999     sample         34.800           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         34.911           ms/op
ClientSimple.existUser:existUser·p1.00      sample         34.996           ms/op
ClientSimple.getUser                        sample  13353   2.392 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          1.028           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.298           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.822           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.012           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.260           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.975           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.129           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.173           ms/op
ClientSimple.listUser                       sample   9716   3.305 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.886           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.342           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.129           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.259           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.195           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.322           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.322           ms/op

Benchmark result is saved to 1720226410684.json
