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
# Warmup Iteration   1: 1.787 ops/ms
Iteration   1: 6.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.483 ops/ms


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
# Warmup Iteration   1: 6.470 ops/ms
Iteration   1: 11.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.621 ops/ms


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
# Warmup Iteration   1: 5.279 ops/ms
Iteration   1: 11.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.746 ops/ms


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
# Warmup Iteration   1: 4.436 ops/ms
Iteration   1: 8.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.632 ops/ms


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
# Warmup Iteration   1: 3.630 ±(99.9%) 0.058 ms/op
Iteration   1: 2.111 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.111 ms/op


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
# Warmup Iteration   1: 3.272 ±(99.9%) 0.046 ms/op
Iteration   1: 2.022 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.022 ms/op


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
# Warmup Iteration   1: 3.425 ±(99.9%) 0.057 ms/op
Iteration   1: 1.993 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.993 ms/op


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
# Warmup Iteration   1: 4.441 ±(99.9%) 0.086 ms/op
Iteration   1: 2.929 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.929 ms/op


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.125 ms/op
Iteration   1: 2.248 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.449 ms/op
                 createUser·p0.50:   2.075 ms/op
                 createUser·p0.90:   2.666 ms/op
                 createUser·p0.95:   2.904 ms/op
                 createUser·p0.99:   7.661 ms/op
                 createUser·p0.999:  12.981 ms/op
                 createUser·p0.9999: 14.528 ms/op
                 createUser·p1.00:   15.221 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14226
  mean =      2.248 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 311 
    [ 1.250,  2.500) = 11563 
    [ 2.500,  3.750) = 1970 
    [ 3.750,  5.000) = 110 
    [ 5.000,  6.250) = 102 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.449 ms/op
     p(50.0000) =      2.075 ms/op
     p(90.0000) =      2.666 ms/op
     p(95.0000) =      2.904 ms/op
     p(99.0000) =      7.661 ms/op
     p(99.9000) =     12.981 ms/op
     p(99.9900) =     14.528 ms/op
     p(99.9990) =     15.221 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


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
# Warmup Iteration   1: 3.080 ±(99.9%) 0.070 ms/op
Iteration   1: 2.000 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.396 ms/op
                 existUser·p0.50:   1.944 ms/op
                 existUser·p0.90:   2.454 ms/op
                 existUser·p0.95:   2.605 ms/op
                 existUser·p0.99:   3.150 ms/op
                 existUser·p0.999:  11.190 ms/op
                 existUser·p0.9999: 11.436 ms/op
                 existUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15987
  mean =      2.000 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 184 
    [ 1.250,  2.500) = 14554 
    [ 2.500,  3.750) = 1168 
    [ 3.750,  5.000) = 25 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.396 ms/op
     p(50.0000) =      1.944 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      3.150 ms/op
     p(99.9000) =     11.190 ms/op
     p(99.9900) =     11.436 ms/op
     p(99.9990) =     11.485 ms/op
     p(99.9999) =     11.485 ms/op
    p(100.0000) =     11.485 ms/op


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
# Warmup Iteration   1: 3.296 ±(99.9%) 0.087 ms/op
Iteration   1: 2.273 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.665 ms/op
                 getUser·p0.50:   2.228 ms/op
                 getUser·p0.90:   2.867 ms/op
                 getUser·p0.95:   3.027 ms/op
                 getUser·p0.99:   6.242 ms/op
                 getUser·p0.999:  13.073 ms/op
                 getUser·p0.9999: 14.037 ms/op
                 getUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14066
  mean =      2.273 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 190 
    [ 1.250,  2.500) = 9323 
    [ 2.500,  3.750) = 4340 
    [ 3.750,  5.000) = 21 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 88 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      2.228 ms/op
     p(90.0000) =      2.867 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     13.073 ms/op
     p(99.9900) =     14.037 ms/op
     p(99.9990) =     14.057 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


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
# Warmup Iteration   1: 4.258 ±(99.9%) 0.157 ms/op
Iteration   1: 3.354 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.333 ms/op
                 listUser·p0.50:   3.383 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.009 ms/op
                 listUser·p0.999:  13.776 ms/op
                 listUser·p0.9999: 14.057 ms/op
                 listUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9541
  mean =      3.354 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 990 
    [ 2.500,  3.750) = 5968 
    [ 3.750,  5.000) = 2429 
    [ 5.000,  6.250) = 77 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.009 ms/op
     p(99.9000) =     13.776 ms/op
     p(99.9900) =     14.057 ms/op
     p(99.9990) =     14.057 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.483          ops/ms
ClientSimple.existUser                       thrpt         11.621          ops/ms
ClientSimple.getUser                         thrpt         11.746          ops/ms
ClientSimple.listUser                        thrpt          8.632          ops/ms
ClientSimple.createUser                       avgt          2.111           ms/op
ClientSimple.existUser                        avgt          2.022           ms/op
ClientSimple.getUser                          avgt          1.993           ms/op
ClientSimple.listUser                         avgt          2.929           ms/op
ClientSimple.createUser                     sample  14226   2.248 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.449           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.075           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.666           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.904           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.661           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.981           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.528           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.221           ms/op
ClientSimple.existUser                      sample  15987   2.000 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.396           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.944           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.454           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.605           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.150           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.190           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.436           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.485           ms/op
ClientSimple.getUser                        sample  14066   2.273 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.665           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.228           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.867           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.027           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.242           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.073           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.037           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.057           ms/op
ClientSimple.listUser                       sample   9541   3.354 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.333           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.383           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.063           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.009           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.776           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.057           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.057           ms/op

Benchmark result is saved to 1717265478592.json
