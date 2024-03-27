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
# Warmup Iteration   1: 1.799 ops/ms
Iteration   1: 7.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.158 ops/ms


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
# Warmup Iteration   1: 5.505 ops/ms
Iteration   1: 12.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.308 ops/ms


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
# Warmup Iteration   1: 6.549 ops/ms
Iteration   1: 13.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.800 ops/ms


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
# Warmup Iteration   1: 4.120 ops/ms
Iteration   1: 8.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.509 ops/ms


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
# Warmup Iteration   1: 4.124 ±(99.9%) 0.076 ms/op
Iteration   1: 2.034 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.034 ms/op


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
# Warmup Iteration   1: 3.026 ±(99.9%) 0.046 ms/op
Iteration   1: 1.871 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.871 ms/op


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
# Warmup Iteration   1: 3.472 ±(99.9%) 0.071 ms/op
Iteration   1: 2.058 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.058 ms/op


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
# Warmup Iteration   1: 4.687 ±(99.9%) 0.123 ms/op
Iteration   1: 3.799 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.799 ms/op


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
# Warmup Iteration   1: 3.637 ±(99.9%) 0.099 ms/op
Iteration   1: 2.349 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.535 ms/op
                 createUser·p0.50:   2.163 ms/op
                 createUser·p0.90:   2.904 ms/op
                 createUser·p0.95:   3.416 ms/op
                 createUser·p0.99:   11.108 ms/op
                 createUser·p0.999:  19.726 ms/op
                 createUser·p0.9999: 21.571 ms/op
                 createUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13741
  mean =      2.349 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10605 
    [ 2.500,  5.000) = 2829 
    [ 5.000,  7.500) = 62 
    [ 7.500, 10.000) = 76 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      2.163 ms/op
     p(90.0000) =      2.904 ms/op
     p(95.0000) =      3.416 ms/op
     p(99.0000) =     11.108 ms/op
     p(99.9000) =     19.726 ms/op
     p(99.9900) =     21.571 ms/op
     p(99.9990) =     22.479 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


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
# Warmup Iteration   1: 2.895 ±(99.9%) 0.066 ms/op
Iteration   1: 1.924 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.499 ms/op
                 existUser·p0.50:   1.847 ms/op
                 existUser·p0.90:   2.392 ms/op
                 existUser·p0.95:   2.650 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  20.906 ms/op
                 existUser·p0.9999: 21.572 ms/op
                 existUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16730
  mean =      1.924 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15535 
    [ 2.500,  5.000) = 1080 
    [ 5.000,  7.500) = 51 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      1.847 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =     20.906 ms/op
     p(99.9900) =     21.572 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 3.540 ±(99.9%) 0.082 ms/op
Iteration   1: 1.970 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   1.866 ms/op
                 getUser·p0.90:   2.347 ms/op
                 getUser·p0.95:   2.572 ms/op
                 getUser·p0.99:   3.146 ms/op
                 getUser·p0.999:  12.354 ms/op
                 getUser·p0.9999: 12.755 ms/op
                 getUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16226
  mean =      1.970 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 15165 
    [ 2.500,  3.750) = 917 
    [ 3.750,  5.000) = 34 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      1.866 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      3.146 ms/op
     p(99.9000) =     12.354 ms/op
     p(99.9900) =     12.755 ms/op
     p(99.9990) =     12.878 ms/op
     p(99.9999) =     12.878 ms/op
    p(100.0000) =     12.878 ms/op


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
# Warmup Iteration   1: 4.442 ±(99.9%) 0.145 ms/op
Iteration   1: 3.310 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   3.113 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.139 ms/op
                 listUser·p0.999:  14.850 ms/op
                 listUser·p0.9999: 14.975 ms/op
                 listUser·p1.00:   14.975 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9656
  mean =      3.310 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 939 
    [ 2.500,  3.750) = 6079 
    [ 3.750,  5.000) = 2515 
    [ 5.000,  6.250) = 71 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.139 ms/op
     p(99.9000) =     14.850 ms/op
     p(99.9900) =     14.975 ms/op
     p(99.9990) =     14.975 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.158          ops/ms
ClientSimple.existUser                       thrpt         12.308          ops/ms
ClientSimple.getUser                         thrpt         13.800          ops/ms
ClientSimple.listUser                        thrpt          8.509          ops/ms
ClientSimple.createUser                       avgt          2.034           ms/op
ClientSimple.existUser                        avgt          1.871           ms/op
ClientSimple.getUser                          avgt          2.058           ms/op
ClientSimple.listUser                         avgt          3.799           ms/op
ClientSimple.createUser                     sample  13741   2.349 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.535           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.163           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.904           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.416           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.108           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.726           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.571           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.479           ms/op
ClientSimple.existUser                      sample  16730   1.924 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.499           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.847           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.392           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.650           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.629           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.906           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.572           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.594           ms/op
ClientSimple.getUser                        sample  16226   1.970 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.910           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.866           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.347           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.572           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.146           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.354           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.755           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.878           ms/op
ClientSimple.listUser                       sample   9656   3.310 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.949           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.113           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.194           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.139           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.850           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.975           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.975           ms/op

Benchmark result is saved to 1711541712717.json
