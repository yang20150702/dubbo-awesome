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
# Warmup Iteration   1: 2.444 ops/ms
Iteration   1: 5.715 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.715 ops/ms


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
# Warmup Iteration   1: 5.995 ops/ms
Iteration   1: 13.143 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.143 ops/ms


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
# Warmup Iteration   1: 4.433 ops/ms
Iteration   1: 8.487 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.487 ops/ms


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
# Warmup Iteration   1: 2.036 ops/ms
Iteration   1: 3.832 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.832 ops/ms


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
# Warmup Iteration   1: 5.592 ±(99.9%) 0.083 ms/op
Iteration   1: 2.827 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.827 ms/op


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
# Warmup Iteration   1: 3.251 ±(99.9%) 0.038 ms/op
Iteration   1: 2.014 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.014 ms/op


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
# Warmup Iteration   1: 4.714 ±(99.9%) 0.053 ms/op
Iteration   1: 3.070 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.070 ms/op


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
# Warmup Iteration   1: 11.725 ±(99.9%) 0.218 ms/op
Iteration   1: 8.978 ±(99.9%) 0.069 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.978 ms/op


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
# Warmup Iteration   1: 5.240 ±(99.9%) 0.119 ms/op
Iteration   1: 2.940 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.032 ms/op
                 createUser·p0.50:   2.716 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   6.242 ms/op
                 createUser·p0.999:  10.129 ms/op
                 createUser·p0.9999: 11.793 ms/op
                 createUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10877
  mean =      2.940 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 2655 
    [ 2.500,  3.750) = 6947 
    [ 3.750,  5.000) = 1053 
    [ 5.000,  6.250) = 113 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.032 ms/op
     p(50.0000) =      2.716 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     10.129 ms/op
     p(99.9900) =     11.793 ms/op
     p(99.9990) =     11.813 ms/op
     p(99.9999) =     11.813 ms/op
    p(100.0000) =     11.813 ms/op


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
# Warmup Iteration   1: 3.274 ±(99.9%) 0.104 ms/op
Iteration   1: 1.968 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   1.872 ms/op
                 existUser·p0.90:   2.503 ms/op
                 existUser·p0.95:   2.720 ms/op
                 existUser·p0.99:   3.702 ms/op
                 existUser·p0.999:  12.246 ms/op
                 existUser·p0.9999: 12.442 ms/op
                 existUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16275
  mean =      1.968 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 389 
    [ 1.250,  2.500) = 14257 
    [ 2.500,  3.750) = 1471 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 82 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      1.872 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      3.702 ms/op
     p(99.9000) =     12.246 ms/op
     p(99.9900) =     12.442 ms/op
     p(99.9990) =     12.452 ms/op
     p(99.9999) =     12.452 ms/op
    p(100.0000) =     12.452 ms/op


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
# Warmup Iteration   1: 4.573 ±(99.9%) 0.122 ms/op
Iteration   1: 3.185 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.893 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.901 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.534 ms/op
                 getUser·p0.999:  14.712 ms/op
                 getUser·p0.9999: 15.024 ms/op
                 getUser·p1.00:   15.024 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10055
  mean =      3.185 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 1540 
    [ 2.500,  3.750) = 7036 
    [ 3.750,  5.000) = 1349 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.901 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.534 ms/op
     p(99.9000) =     14.712 ms/op
     p(99.9900) =     15.024 ms/op
     p(99.9990) =     15.024 ms/op
     p(99.9999) =     15.024 ms/op
    p(100.0000) =     15.024 ms/op


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
# Warmup Iteration   1: 11.231 ±(99.9%) 0.428 ms/op
Iteration   1: 8.684 ±(99.9%) 0.137 ms/op
                 listUser·p0.00:   1.335 ms/op
                 listUser·p0.50:   8.307 ms/op
                 listUser·p0.90:   11.305 ms/op
                 listUser·p0.95:   12.157 ms/op
                 listUser·p0.99:   17.383 ms/op
                 listUser·p0.999:  28.320 ms/op
                 listUser·p0.9999: 36.700 ms/op
                 listUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3849
  mean =      8.684 ±(99.9%) 0.137 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 63 
    [ 5.000,  7.500) = 1164 
    [ 7.500, 10.000) = 1783 
    [10.000, 12.500) = 675 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      8.307 ms/op
     p(90.0000) =     11.305 ms/op
     p(95.0000) =     12.157 ms/op
     p(99.0000) =     17.383 ms/op
     p(99.9000) =     28.320 ms/op
     p(99.9900) =     36.700 ms/op
     p(99.9990) =     36.700 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.715          ops/ms
Client.existUser                       thrpt         13.143          ops/ms
Client.getUser                         thrpt          8.487          ops/ms
Client.listUser                        thrpt          3.832          ops/ms
Client.createUser                       avgt          2.827           ms/op
Client.existUser                        avgt          2.014           ms/op
Client.getUser                          avgt          3.070           ms/op
Client.listUser                         avgt          8.978           ms/op
Client.createUser                     sample  10877   2.940 ± 0.025   ms/op
Client.createUser:createUser·p0.00    sample          1.032           ms/op
Client.createUser:createUser·p0.50    sample          2.716           ms/op
Client.createUser:createUser·p0.90    sample          3.953           ms/op
Client.createUser:createUser·p0.95    sample          4.375           ms/op
Client.createUser:createUser·p0.99    sample          6.242           ms/op
Client.createUser:createUser·p0.999   sample         10.129           ms/op
Client.createUser:createUser·p0.9999  sample         11.793           ms/op
Client.createUser:createUser·p1.00    sample         11.813           ms/op
Client.existUser                      sample  16275   1.968 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.670           ms/op
Client.existUser:existUser·p0.50      sample          1.872           ms/op
Client.existUser:existUser·p0.90      sample          2.503           ms/op
Client.existUser:existUser·p0.95      sample          2.720           ms/op
Client.existUser:existUser·p0.99      sample          3.702           ms/op
Client.existUser:existUser·p0.999     sample         12.246           ms/op
Client.existUser:existUser·p0.9999    sample         12.442           ms/op
Client.existUser:existUser·p1.00      sample         12.452           ms/op
Client.getUser                        sample  10055   3.185 ± 0.030   ms/op
Client.getUser:getUser·p0.00          sample          0.893           ms/op
Client.getUser:getUser·p0.50          sample          3.154           ms/op
Client.getUser:getUser·p0.90          sample          3.901           ms/op
Client.getUser:getUser·p0.95          sample          4.309           ms/op
Client.getUser:getUser·p0.99          sample          5.534           ms/op
Client.getUser:getUser·p0.999         sample         14.712           ms/op
Client.getUser:getUser·p0.9999        sample         15.024           ms/op
Client.getUser:getUser·p1.00          sample         15.024           ms/op
Client.listUser                       sample   3849   8.684 ± 0.137   ms/op
Client.listUser:listUser·p0.00        sample          1.335           ms/op
Client.listUser:listUser·p0.50        sample          8.307           ms/op
Client.listUser:listUser·p0.90        sample         11.305           ms/op
Client.listUser:listUser·p0.95        sample         12.157           ms/op
Client.listUser:listUser·p0.99        sample         17.383           ms/op
Client.listUser:listUser·p0.999       sample         28.320           ms/op
Client.listUser:listUser·p0.9999      sample         36.700           ms/op
Client.listUser:listUser·p1.00        sample         36.700           ms/op
