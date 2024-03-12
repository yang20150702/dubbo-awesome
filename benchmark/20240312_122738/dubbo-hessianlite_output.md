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
# Warmup Iteration   1: 2.244 ops/ms
Iteration   1: 5.657 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.657 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.490 ops/ms
Iteration   1: 11.794 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.794 ops/ms


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
# Warmup Iteration   1: 3.831 ops/ms
Iteration   1: 8.410 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.410 ops/ms


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
# Warmup Iteration   1: 2.052 ops/ms
Iteration   1: 3.788 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.788 ops/ms


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
# Warmup Iteration   1: 5.722 ±(99.9%) 0.095 ms/op
Iteration   1: 3.400 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.400 ms/op


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
# Warmup Iteration   1: 3.272 ±(99.9%) 0.036 ms/op
Iteration   1: 2.028 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.028 ms/op


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
# Warmup Iteration   1: 4.941 ±(99.9%) 0.081 ms/op
Iteration   1: 3.073 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.073 ms/op


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
# Warmup Iteration   1: 12.527 ±(99.9%) 0.198 ms/op
Iteration   1: 7.835 ±(99.9%) 0.061 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.835 ms/op


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
# Warmup Iteration   1: 5.137 ±(99.9%) 0.101 ms/op
Iteration   1: 2.939 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   2.826 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   6.500 ms/op
                 createUser·p0.999:  10.060 ms/op
                 createUser·p0.9999: 10.268 ms/op
                 createUser·p1.00:   10.273 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11048
  mean =      2.939 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 549 
    [ 2.000,  3.000) = 6419 
    [ 3.000,  4.000) = 3467 
    [ 4.000,  5.000) = 439 
    [ 5.000,  6.000) = 35 
    [ 6.000,  7.000) = 42 
    [ 7.000,  8.000) = 32 
    [ 8.000,  9.000) = 1 
    [ 9.000, 10.000) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      2.826 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      6.500 ms/op
     p(99.9000) =     10.060 ms/op
     p(99.9900) =     10.268 ms/op
     p(99.9990) =     10.273 ms/op
     p(99.9999) =     10.273 ms/op
    p(100.0000) =     10.273 ms/op


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
# Warmup Iteration   1: 3.339 ±(99.9%) 0.082 ms/op
Iteration   1: 1.854 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.486 ms/op
                 existUser·p0.50:   1.733 ms/op
                 existUser·p0.90:   2.277 ms/op
                 existUser·p0.95:   2.454 ms/op
                 existUser·p0.99:   3.582 ms/op
                 existUser·p0.999:  13.450 ms/op
                 existUser·p0.9999: 13.977 ms/op
                 existUser·p1.00:   14.025 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17275
  mean =      1.854 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 318 
    [ 1.250,  2.500) = 16228 
    [ 2.500,  3.750) = 567 
    [ 3.750,  5.000) = 63 
    [ 5.000,  6.250) = 28 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.486 ms/op
     p(50.0000) =      1.733 ms/op
     p(90.0000) =      2.277 ms/op
     p(95.0000) =      2.454 ms/op
     p(99.0000) =      3.582 ms/op
     p(99.9000) =     13.450 ms/op
     p(99.9900) =     13.977 ms/op
     p(99.9990) =     14.025 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


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
# Warmup Iteration   1: 4.786 ±(99.9%) 0.102 ms/op
Iteration   1: 3.085 ±(99.9%) 0.039 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   10.207 ms/op
                 getUser·p0.999:  15.565 ms/op
                 getUser·p0.9999: 17.001 ms/op
                 getUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10360
  mean =      3.085 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 2445 
    [ 2.500,  3.750) = 6757 
    [ 3.750,  5.000) = 982 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =     10.207 ms/op
     p(99.9000) =     15.565 ms/op
     p(99.9900) =     17.001 ms/op
     p(99.9990) =     17.039 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 12.495 ±(99.9%) 0.445 ms/op
Iteration   1: 7.761 ±(99.9%) 0.105 ms/op
                 listUser·p0.00:   1.880 ms/op
                 listUser·p0.50:   7.594 ms/op
                 listUser·p0.90:   10.174 ms/op
                 listUser·p0.95:   11.239 ms/op
                 listUser·p0.99:   14.033 ms/op
                 listUser·p0.999:  21.822 ms/op
                 listUser·p0.9999: 23.298 ms/op
                 listUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4116
  mean =      7.761 ±(99.9%) 0.105 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 215 
    [ 5.000,  7.500) = 1756 
    [ 7.500, 10.000) = 1682 
    [10.000, 12.500) = 380 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.880 ms/op
     p(50.0000) =      7.594 ms/op
     p(90.0000) =     10.174 ms/op
     p(95.0000) =     11.239 ms/op
     p(99.0000) =     14.033 ms/op
     p(99.9000) =     21.822 ms/op
     p(99.9900) =     23.298 ms/op
     p(99.9990) =     23.298 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.657          ops/ms
Client.existUser                       thrpt         11.794          ops/ms
Client.getUser                         thrpt          8.410          ops/ms
Client.listUser                        thrpt          3.788          ops/ms
Client.createUser                       avgt          3.400           ms/op
Client.existUser                        avgt          2.028           ms/op
Client.getUser                          avgt          3.073           ms/op
Client.listUser                         avgt          7.835           ms/op
Client.createUser                     sample  11048   2.939 ± 0.027   ms/op
Client.createUser:createUser·p0.00    sample          1.057           ms/op
Client.createUser:createUser·p0.50    sample          2.826           ms/op
Client.createUser:createUser·p0.90    sample          3.723           ms/op
Client.createUser:createUser·p0.95    sample          4.030           ms/op
Client.createUser:createUser·p0.99    sample          6.500           ms/op
Client.createUser:createUser·p0.999   sample         10.060           ms/op
Client.createUser:createUser·p0.9999  sample         10.268           ms/op
Client.createUser:createUser·p1.00    sample         10.273           ms/op
Client.existUser                      sample  17275   1.854 ± 0.019   ms/op
Client.existUser:existUser·p0.00      sample          0.486           ms/op
Client.existUser:existUser·p0.50      sample          1.733           ms/op
Client.existUser:existUser·p0.90      sample          2.277           ms/op
Client.existUser:existUser·p0.95      sample          2.454           ms/op
Client.existUser:existUser·p0.99      sample          3.582           ms/op
Client.existUser:existUser·p0.999     sample         13.450           ms/op
Client.existUser:existUser·p0.9999    sample         13.977           ms/op
Client.existUser:existUser·p1.00      sample         14.025           ms/op
Client.getUser                        sample  10360   3.085 ± 0.039   ms/op
Client.getUser:getUser·p0.00          sample          0.886           ms/op
Client.getUser:getUser·p0.50          sample          3.006           ms/op
Client.getUser:getUser·p0.90          sample          3.801           ms/op
Client.getUser:getUser·p0.95          sample          4.104           ms/op
Client.getUser:getUser·p0.99          sample         10.207           ms/op
Client.getUser:getUser·p0.999         sample         15.565           ms/op
Client.getUser:getUser·p0.9999        sample         17.001           ms/op
Client.getUser:getUser·p1.00          sample         17.039           ms/op
Client.listUser                       sample   4116   7.761 ± 0.105   ms/op
Client.listUser:listUser·p0.00        sample          1.880           ms/op
Client.listUser:listUser·p0.50        sample          7.594           ms/op
Client.listUser:listUser·p0.90        sample         10.174           ms/op
Client.listUser:listUser·p0.95        sample         11.239           ms/op
Client.listUser:listUser·p0.99        sample         14.033           ms/op
Client.listUser:listUser·p0.999       sample         21.822           ms/op
Client.listUser:listUser·p0.9999      sample         23.298           ms/op
Client.listUser:listUser·p1.00        sample         23.298           ms/op
