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
# Warmup Iteration   1: 1.363 ops/ms
Iteration   1: 5.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.806 ops/ms


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
# Warmup Iteration   1: 4.969 ops/ms
Iteration   1: 11.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.546 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 4.785 ops/ms
Iteration   1: 12.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.551 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 3.705 ops/ms
Iteration   1: 7.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.466 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.495 ±(99.9%) 0.089 ms/op
Iteration   1: 2.374 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.374 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.405 ±(99.9%) 0.066 ms/op
Iteration   1: 1.916 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.916 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.049 ±(99.9%) 0.071 ms/op
Iteration   1: 2.193 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.193 ms/op


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
# Warmup Iteration   1: 4.509 ±(99.9%) 0.108 ms/op
Iteration   1: 3.320 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.320 ms/op


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
# Warmup Iteration   1: 3.873 ±(99.9%) 0.114 ms/op
Iteration   1: 2.462 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   2.269 ms/op
                 createUser·p0.90:   2.806 ms/op
                 createUser·p0.95:   3.120 ms/op
                 createUser·p0.99:   5.657 ms/op
                 createUser·p0.999:  23.724 ms/op
                 createUser·p0.9999: 23.790 ms/op
                 createUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13003
  mean =      2.462 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9415 
    [ 2.500,  5.000) = 3383 
    [ 5.000,  7.500) = 103 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      2.269 ms/op
     p(90.0000) =      2.806 ms/op
     p(95.0000) =      3.120 ms/op
     p(99.0000) =      5.657 ms/op
     p(99.9000) =     23.724 ms/op
     p(99.9900) =     23.790 ms/op
     p(99.9990) =     23.790 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


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
# Warmup Iteration   1: 3.448 ±(99.9%) 0.115 ms/op
Iteration   1: 1.904 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.633 ms/op
                 existUser·p0.50:   1.780 ms/op
                 existUser·p0.90:   2.224 ms/op
                 existUser·p0.95:   2.408 ms/op
                 existUser·p0.99:   4.047 ms/op
                 existUser·p0.999:  22.938 ms/op
                 existUser·p0.9999: 23.781 ms/op
                 existUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16805
  mean =      1.904 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16167 
    [ 2.500,  5.000) = 521 
    [ 5.000,  7.500) = 63 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      1.780 ms/op
     p(90.0000) =      2.224 ms/op
     p(95.0000) =      2.408 ms/op
     p(99.0000) =      4.047 ms/op
     p(99.9000) =     22.938 ms/op
     p(99.9900) =     23.781 ms/op
     p(99.9990) =     24.183 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


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
# Warmup Iteration   1: 3.512 ±(99.9%) 0.091 ms/op
Iteration   1: 2.362 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.607 ms/op
                 getUser·p0.50:   2.277 ms/op
                 getUser·p0.90:   2.900 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   5.858 ms/op
                 getUser·p0.999:  12.180 ms/op
                 getUser·p0.9999: 13.651 ms/op
                 getUser·p1.00:   14.090 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13529
  mean =      2.362 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 155 
    [ 1.250,  2.500) = 8933 
    [ 2.500,  3.750) = 4167 
    [ 3.750,  5.000) = 134 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      2.277 ms/op
     p(90.0000) =      2.900 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      5.858 ms/op
     p(99.9000) =     12.180 ms/op
     p(99.9900) =     13.651 ms/op
     p(99.9990) =     14.090 ms/op
     p(99.9999) =     14.090 ms/op
    p(100.0000) =     14.090 ms/op


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
# Warmup Iteration   1: 4.746 ±(99.9%) 0.156 ms/op
Iteration   1: 3.571 ±(99.9%) 0.060 ms/op
                 listUser·p0.00:   0.758 ms/op
                 listUser·p0.50:   3.219 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   11.330 ms/op
                 listUser·p0.999:  21.333 ms/op
                 listUser·p0.9999: 21.922 ms/op
                 listUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8957
  mean =      3.571 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 561 
    [ 2.500,  5.000) = 7983 
    [ 5.000,  7.500) = 240 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =     11.330 ms/op
     p(99.9000) =     21.333 ms/op
     p(99.9900) =     21.922 ms/op
     p(99.9990) =     21.922 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.806          ops/ms
ClientSimple.existUser                       thrpt         11.546          ops/ms
ClientSimple.getUser                         thrpt         12.551          ops/ms
ClientSimple.listUser                        thrpt          7.466          ops/ms
ClientSimple.createUser                       avgt          2.374           ms/op
ClientSimple.existUser                        avgt          1.916           ms/op
ClientSimple.getUser                          avgt          2.193           ms/op
ClientSimple.listUser                         avgt          3.320           ms/op
ClientSimple.createUser                     sample  13003   2.462 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.744           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.269           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.806           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.120           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.657           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.724           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.790           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.790           ms/op
ClientSimple.existUser                      sample  16805   1.904 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.633           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.780           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.224           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.408           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.047           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.938           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.781           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.183           ms/op
ClientSimple.getUser                        sample  13529   2.362 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.607           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.277           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.900           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.109           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.858           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.180           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.651           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.090           ms/op
ClientSimple.listUser                       sample   8957   3.571 ± 0.060   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.758           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.219           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.841           ms/op
ClientSimple.listUser:listUser·p0.99        sample         11.330           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.333           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.922           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.922           ms/op

Benchmark result is saved to 1719511861716.json
