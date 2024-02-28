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
# Warmup Iteration   1: 2.630 ops/ms
Iteration   1: 5.864 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.864 ops/ms


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
# Warmup Iteration   1: 5.970 ops/ms
Iteration   1: 12.911 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.911 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.007 ops/ms
Iteration   1: 8.383 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.383 ops/ms


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
# Warmup Iteration   1: 2.027 ops/ms
Iteration   1: 3.510 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.510 ops/ms


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
# Warmup Iteration   1: 5.100 ±(99.9%) 0.071 ms/op
Iteration   1: 3.118 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.118 ms/op


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
# Warmup Iteration   1: 3.039 ±(99.9%) 0.037 ms/op
Iteration   1: 2.022 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.022 ms/op


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
# Warmup Iteration   1: 5.424 ±(99.9%) 0.075 ms/op
Iteration   1: 2.999 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.999 ms/op


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
# Warmup Iteration   1: 12.022 ±(99.9%) 0.284 ms/op
Iteration   1: 8.492 ±(99.9%) 0.154 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.492 ms/op


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
# Warmup Iteration   1: 5.165 ±(99.9%) 0.133 ms/op
Iteration   1: 3.062 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   1.247 ms/op
                 createUser·p0.50:   2.818 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.622 ms/op
                 createUser·p0.99:   7.193 ms/op
                 createUser·p0.999:  12.507 ms/op
                 createUser·p0.9999: 13.009 ms/op
                 createUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10636
  mean =      3.062 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 2799 
    [ 2.500,  3.750) = 6689 
    [ 3.750,  5.000) = 682 
    [ 5.000,  6.250) = 281 
    [ 6.250,  7.500) = 103 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      2.818 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.622 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     12.507 ms/op
     p(99.9900) =     13.009 ms/op
     p(99.9990) =     13.009 ms/op
     p(99.9999) =     13.009 ms/op
    p(100.0000) =     13.009 ms/op


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
# Warmup Iteration   1: 3.155 ±(99.9%) 0.072 ms/op
Iteration   1: 1.923 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.377 ms/op
                 existUser·p0.50:   1.847 ms/op
                 existUser·p0.90:   2.464 ms/op
                 existUser·p0.95:   2.720 ms/op
                 existUser·p0.99:   4.776 ms/op
                 existUser·p0.999:  11.300 ms/op
                 existUser·p0.9999: 12.021 ms/op
                 existUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16644
  mean =      1.923 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1016 
    [ 1.250,  2.500) = 14094 
    [ 2.500,  3.750) = 1278 
    [ 3.750,  5.000) = 116 
    [ 5.000,  6.250) = 76 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.377 ms/op
     p(50.0000) =      1.847 ms/op
     p(90.0000) =      2.464 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      4.776 ms/op
     p(99.9000) =     11.300 ms/op
     p(99.9900) =     12.021 ms/op
     p(99.9990) =     12.108 ms/op
     p(99.9999) =     12.108 ms/op
    p(100.0000) =     12.108 ms/op


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
# Warmup Iteration   1: 4.826 ±(99.9%) 0.119 ms/op
Iteration   1: 2.988 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   2.892 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  14.117 ms/op
                 getUser·p0.9999: 14.139 ms/op
                 getUser·p1.00:   14.139 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10689
  mean =      2.988 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 22 
    [ 1.250,  2.500) = 3153 
    [ 2.500,  3.750) = 6340 
    [ 3.750,  5.000) = 984 
    [ 5.000,  6.250) = 73 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      6.291 ms/op
     p(99.9000) =     14.117 ms/op
     p(99.9900) =     14.139 ms/op
     p(99.9990) =     14.139 ms/op
     p(99.9999) =     14.139 ms/op
    p(100.0000) =     14.139 ms/op


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
# Warmup Iteration   1: 12.756 ±(99.9%) 0.495 ms/op
Iteration   1: 6.982 ±(99.9%) 0.080 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   6.758 ms/op
                 listUser·p0.90:   8.962 ms/op
                 listUser·p0.95:   9.994 ms/op
                 listUser·p0.99:   12.472 ms/op
                 listUser·p0.999:  16.384 ms/op
                 listUser·p0.9999: 22.577 ms/op
                 listUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4577
  mean =      6.982 ±(99.9%) 0.080 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 312 
    [ 5.000,  7.500) = 2895 
    [ 7.500, 10.000) = 1138 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      6.758 ms/op
     p(90.0000) =      8.962 ms/op
     p(95.0000) =      9.994 ms/op
     p(99.0000) =     12.472 ms/op
     p(99.9000) =     16.384 ms/op
     p(99.9900) =     22.577 ms/op
     p(99.9990) =     22.577 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.864          ops/ms
Client.existUser                       thrpt         12.911          ops/ms
Client.getUser                         thrpt          8.383          ops/ms
Client.listUser                        thrpt          3.510          ops/ms
Client.createUser                       avgt          3.118           ms/op
Client.existUser                        avgt          2.022           ms/op
Client.getUser                          avgt          2.999           ms/op
Client.listUser                         avgt          8.492           ms/op
Client.createUser                     sample  10636   3.062 ± 0.033   ms/op
Client.createUser:createUser·p0.00    sample          1.247           ms/op
Client.createUser:createUser·p0.50    sample          2.818           ms/op
Client.createUser:createUser·p0.90    sample          3.772           ms/op
Client.createUser:createUser·p0.95    sample          4.622           ms/op
Client.createUser:createUser·p0.99    sample          7.193           ms/op
Client.createUser:createUser·p0.999   sample         12.507           ms/op
Client.createUser:createUser·p0.9999  sample         13.009           ms/op
Client.createUser:createUser·p1.00    sample         13.009           ms/op
Client.existUser                      sample  16644   1.923 ± 0.018   ms/op
Client.existUser:existUser·p0.00      sample          0.377           ms/op
Client.existUser:existUser·p0.50      sample          1.847           ms/op
Client.existUser:existUser·p0.90      sample          2.464           ms/op
Client.existUser:existUser·p0.95      sample          2.720           ms/op
Client.existUser:existUser·p0.99      sample          4.776           ms/op
Client.existUser:existUser·p0.999     sample         11.300           ms/op
Client.existUser:existUser·p0.9999    sample         12.021           ms/op
Client.existUser:existUser·p1.00      sample         12.108           ms/op
Client.getUser                        sample  10689   2.988 ± 0.029   ms/op
Client.getUser:getUser·p0.00          sample          0.888           ms/op
Client.getUser:getUser·p0.50          sample          2.892           ms/op
Client.getUser:getUser·p0.90          sample          3.789           ms/op
Client.getUser:getUser·p0.95          sample          4.055           ms/op
Client.getUser:getUser·p0.99          sample          6.291           ms/op
Client.getUser:getUser·p0.999         sample         14.117           ms/op
Client.getUser:getUser·p0.9999        sample         14.139           ms/op
Client.getUser:getUser·p1.00          sample         14.139           ms/op
Client.listUser                       sample   4577   6.982 ± 0.080   ms/op
Client.listUser:listUser·p0.00        sample          1.186           ms/op
Client.listUser:listUser·p0.50        sample          6.758           ms/op
Client.listUser:listUser·p0.90        sample          8.962           ms/op
Client.listUser:listUser·p0.95        sample          9.994           ms/op
Client.listUser:listUser·p0.99        sample         12.472           ms/op
Client.listUser:listUser·p0.999       sample         16.384           ms/op
Client.listUser:listUser·p0.9999      sample         22.577           ms/op
Client.listUser:listUser·p1.00        sample         22.577           ms/op
