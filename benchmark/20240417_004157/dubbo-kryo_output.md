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
# Warmup Iteration   1: 1.981 ops/ms
Iteration   1: 6.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.922 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.842 ops/ms
Iteration   1: 12.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.432 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 6.133 ops/ms
Iteration   1: 14.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.523 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.451 ops/ms
Iteration   1: 8.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.629 ops/ms


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
# Warmup Iteration   1: 3.599 ±(99.9%) 0.058 ms/op
Iteration   1: 2.146 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.146 ms/op


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
# Warmup Iteration   1: 3.021 ±(99.9%) 0.050 ms/op
Iteration   1: 1.857 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.857 ms/op


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
# Warmup Iteration   1: 3.078 ±(99.9%) 0.050 ms/op
Iteration   1: 1.906 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.906 ms/op


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
# Warmup Iteration   1: 4.638 ±(99.9%) 0.095 ms/op
Iteration   1: 3.193 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.193 ms/op


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
# Warmup Iteration   1: 3.610 ±(99.9%) 0.083 ms/op
Iteration   1: 2.317 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   2.200 ms/op
                 createUser·p0.90:   2.769 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   7.021 ms/op
                 createUser·p0.999:  15.434 ms/op
                 createUser·p0.9999: 17.305 ms/op
                 createUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13797
  mean =      2.317 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 153 
    [ 1.250,  2.500) = 10634 
    [ 2.500,  3.750) = 2518 
    [ 3.750,  5.000) = 161 
    [ 5.000,  6.250) = 170 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      2.200 ms/op
     p(90.0000) =      2.769 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     15.434 ms/op
     p(99.9900) =     17.305 ms/op
     p(99.9990) =     17.367 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 2.994 ±(99.9%) 0.070 ms/op
Iteration   1: 1.863 ±(99.9%) 0.037 ms/op
                 existUser·p0.00:   0.366 ms/op
                 existUser·p0.50:   1.708 ms/op
                 existUser·p0.90:   2.249 ms/op
                 existUser·p0.95:   2.437 ms/op
                 existUser·p0.99:   3.661 ms/op
                 existUser·p0.999:  31.916 ms/op
                 existUser·p0.9999: 32.810 ms/op
                 existUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17157
  mean =      1.863 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16451 
    [ 2.500,  5.000) = 603 
    [ 5.000,  7.500) = 7 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.366 ms/op
     p(50.0000) =      1.708 ms/op
     p(90.0000) =      2.249 ms/op
     p(95.0000) =      2.437 ms/op
     p(99.0000) =      3.661 ms/op
     p(99.9000) =     31.916 ms/op
     p(99.9900) =     32.810 ms/op
     p(99.9990) =     32.834 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


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
# Warmup Iteration   1: 3.616 ±(99.9%) 0.102 ms/op
Iteration   1: 2.109 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   2.015 ms/op
                 getUser·p0.90:   2.668 ms/op
                 getUser·p0.95:   2.851 ms/op
                 getUser·p0.99:   3.400 ms/op
                 getUser·p0.999:  14.746 ms/op
                 getUser·p0.9999: 16.242 ms/op
                 getUser·p1.00:   16.581 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15305
  mean =      2.109 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 228 
    [ 1.250,  2.500) = 12041 
    [ 2.500,  3.750) = 2951 
    [ 3.750,  5.000) = 46 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      2.015 ms/op
     p(90.0000) =      2.668 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      3.400 ms/op
     p(99.9000) =     14.746 ms/op
     p(99.9900) =     16.242 ms/op
     p(99.9990) =     16.581 ms/op
     p(99.9999) =     16.581 ms/op
    p(100.0000) =     16.581 ms/op


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
# Warmup Iteration   1: 4.563 ±(99.9%) 0.133 ms/op
Iteration   1: 3.478 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   3.482 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.857 ms/op
                 listUser·p0.999:  13.058 ms/op
                 listUser·p0.9999: 14.696 ms/op
                 listUser·p1.00:   14.696 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9233
  mean =      3.478 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 929 
    [ 2.500,  3.750) = 5253 
    [ 3.750,  5.000) = 2868 
    [ 5.000,  6.250) = 94 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     13.058 ms/op
     p(99.9900) =     14.696 ms/op
     p(99.9990) =     14.696 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.922          ops/ms
ClientSimple.existUser                       thrpt         12.432          ops/ms
ClientSimple.getUser                         thrpt         14.523          ops/ms
ClientSimple.listUser                        thrpt          8.629          ops/ms
ClientSimple.createUser                       avgt          2.146           ms/op
ClientSimple.existUser                        avgt          1.857           ms/op
ClientSimple.getUser                          avgt          1.906           ms/op
ClientSimple.listUser                         avgt          3.193           ms/op
ClientSimple.createUser                     sample  13797   2.317 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.665           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.200           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.769           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.203           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.021           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.434           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.305           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.367           ms/op
ClientSimple.existUser                      sample  17157   1.863 ± 0.037   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.366           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.708           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.249           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.437           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.661           ms/op
ClientSimple.existUser:existUser·p0.999     sample         31.916           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         32.810           ms/op
ClientSimple.existUser:existUser·p1.00      sample         32.834           ms/op
ClientSimple.getUser                        sample  15305   2.109 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.690           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.015           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.668           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.851           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.400           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.746           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.242           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.581           ms/op
ClientSimple.listUser                       sample   9233   3.478 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.000           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.482           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.432           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.857           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.058           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.696           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.696           ms/op

Benchmark result is saved to 1713314268480.json
