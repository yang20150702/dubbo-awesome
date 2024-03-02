# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.649 ops/ms
Iteration   1: 5.400 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.400 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.350 ops/ms
Iteration   1: 12.294 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.294 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.979 ops/ms
Iteration   1: 8.498 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.498 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.063 ops/ms
Iteration   1: 3.348 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.348 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.723 ±(99.9%) 0.092 ms/op
Iteration   1: 3.254 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.254 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.008 ±(99.9%) 0.025 ms/op
Iteration   1: 1.877 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.877 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.863 ±(99.9%) 0.072 ms/op
Iteration   1: 3.140 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.140 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.717 ±(99.9%) 0.226 ms/op
Iteration   1: 8.756 ±(99.9%) 0.129 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.756 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.005 ±(99.9%) 0.110 ms/op
Iteration   1: 3.078 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   7.496 ms/op
                 createUser·p0.999:  14.909 ms/op
                 createUser·p0.9999: 14.975 ms/op
                 createUser·p1.00:   14.975 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10374
  mean =      3.078 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 2245 
    [ 2.500,  3.750) = 7122 
    [ 3.750,  5.000) = 719 
    [ 5.000,  6.250) = 89 
    [ 6.250,  7.500) = 91 
    [ 7.500,  8.750) = 70 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.005 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     14.909 ms/op
     p(99.9900) =     14.975 ms/op
     p(99.9990) =     14.975 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.016 ±(99.9%) 0.070 ms/op
Iteration   1: 1.979 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.294 ms/op
                 existUser·p0.50:   1.966 ms/op
                 existUser·p0.90:   2.564 ms/op
                 existUser·p0.95:   2.818 ms/op
                 existUser·p0.99:   3.277 ms/op
                 existUser·p0.999:  4.078 ms/op
                 existUser·p0.9999: 4.642 ms/op
                 existUser·p1.00:   5.194 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16179
  mean =      1.979 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 3 
    [0.500, 1.000) = 175 
    [1.000, 1.500) = 2174 
    [1.500, 2.000) = 6271 
    [2.000, 2.500) = 5679 
    [2.500, 3.000) = 1496 
    [3.000, 3.500) = 297 
    [3.500, 4.000) = 68 
    [4.000, 4.500) = 15 
    [4.500, 5.000) = 0 
    [5.000, 5.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.294 ms/op
     p(50.0000) =      1.966 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      3.277 ms/op
     p(99.9000) =      4.078 ms/op
     p(99.9900) =      4.642 ms/op
     p(99.9990) =      5.194 ms/op
     p(99.9999) =      5.194 ms/op
    p(100.0000) =      5.194 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.706 ±(99.9%) 0.126 ms/op
Iteration   1: 2.992 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   2.855 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   5.236 ms/op
                 getUser·p0.999:  6.365 ms/op
                 getUser·p0.9999: 7.265 ms/op
                 getUser·p1.00:   7.274 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10683
  mean =      2.992 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 23 
    [1.500, 2.000) = 297 
    [2.000, 2.500) = 2200 
    [2.500, 3.000) = 3685 
    [3.000, 3.500) = 2461 
    [3.500, 4.000) = 1074 
    [4.000, 4.500) = 534 
    [4.500, 5.000) = 208 
    [5.000, 5.500) = 133 
    [5.500, 6.000) = 29 
    [6.000, 6.500) = 35 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.236 ms/op
     p(99.9000) =      6.365 ms/op
     p(99.9900) =      7.265 ms/op
     p(99.9990) =      7.274 ms/op
     p(99.9999) =      7.274 ms/op
    p(100.0000) =      7.274 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.325 ±(99.9%) 0.398 ms/op
Iteration   1: 9.482 ±(99.9%) 0.167 ms/op
                 listUser·p0.00:   2.044 ms/op
                 listUser·p0.50:   8.864 ms/op
                 listUser·p0.90:   13.222 ms/op
                 listUser·p0.95:   14.778 ms/op
                 listUser·p0.99:   20.480 ms/op
                 listUser·p0.999:  26.288 ms/op
                 listUser·p0.9999: 26.804 ms/op
                 listUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3370
  mean =      9.482 ±(99.9%) 0.167 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 63 
    [ 5.000,  7.500) = 774 
    [ 7.500, 10.000) = 1366 
    [10.000, 12.500) = 697 
    [12.500, 15.000) = 308 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.044 ms/op
     p(50.0000) =      8.864 ms/op
     p(90.0000) =     13.222 ms/op
     p(95.0000) =     14.778 ms/op
     p(99.0000) =     20.480 ms/op
     p(99.9000) =     26.288 ms/op
     p(99.9900) =     26.804 ms/op
     p(99.9990) =     26.804 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.400          ops/ms
Client.existUser                       thrpt         12.294          ops/ms
Client.getUser                         thrpt          8.498          ops/ms
Client.listUser                        thrpt          3.348          ops/ms
Client.createUser                       avgt          3.254           ms/op
Client.existUser                        avgt          1.877           ms/op
Client.getUser                          avgt          3.140           ms/op
Client.listUser                         avgt          8.756           ms/op
Client.createUser                     sample  10374   3.078 ± 0.034   ms/op
Client.createUser:createUser·p0.00    sample          1.005           ms/op
Client.createUser:createUser·p0.50    sample          2.925           ms/op
Client.createUser:createUser·p0.90    sample          3.736           ms/op
Client.createUser:createUser·p0.95    sample          4.112           ms/op
Client.createUser:createUser·p0.99    sample          7.496           ms/op
Client.createUser:createUser·p0.999   sample         14.909           ms/op
Client.createUser:createUser·p0.9999  sample         14.975           ms/op
Client.createUser:createUser·p1.00    sample         14.975           ms/op
Client.existUser                      sample  16179   1.979 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          0.294           ms/op
Client.existUser:existUser·p0.50      sample          1.966           ms/op
Client.existUser:existUser·p0.90      sample          2.564           ms/op
Client.existUser:existUser·p0.95      sample          2.818           ms/op
Client.existUser:existUser·p0.99      sample          3.277           ms/op
Client.existUser:existUser·p0.999     sample          4.078           ms/op
Client.existUser:existUser·p0.9999    sample          4.642           ms/op
Client.existUser:existUser·p1.00      sample          5.194           ms/op
Client.getUser                        sample  10683   2.992 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          1.128           ms/op
Client.getUser:getUser·p0.50          sample          2.855           ms/op
Client.getUser:getUser·p0.90          sample          3.908           ms/op
Client.getUser:getUser·p0.95          sample          4.325           ms/op
Client.getUser:getUser·p0.99          sample          5.236           ms/op
Client.getUser:getUser·p0.999         sample          6.365           ms/op
Client.getUser:getUser·p0.9999        sample          7.265           ms/op
Client.getUser:getUser·p1.00          sample          7.274           ms/op
Client.listUser                       sample   3370   9.482 ± 0.167   ms/op
Client.listUser:listUser·p0.00        sample          2.044           ms/op
Client.listUser:listUser·p0.50        sample          8.864           ms/op
Client.listUser:listUser·p0.90        sample         13.222           ms/op
Client.listUser:listUser·p0.95        sample         14.778           ms/op
Client.listUser:listUser·p0.99        sample         20.480           ms/op
Client.listUser:listUser·p0.999       sample         26.288           ms/op
Client.listUser:listUser·p0.9999      sample         26.804           ms/op
Client.listUser:listUser·p1.00        sample         26.804           ms/op
