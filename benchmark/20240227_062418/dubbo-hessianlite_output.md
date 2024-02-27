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
# Warmup Iteration   1: 2.178 ops/ms
Iteration   1: 6.164 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.164 ops/ms


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
# Warmup Iteration   1: 5.758 ops/ms
Iteration   1: 12.065 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.065 ops/ms


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
# Warmup Iteration   1: 3.951 ops/ms
Iteration   1: 8.787 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.787 ops/ms


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
# Warmup Iteration   1: 2.106 ops/ms
Iteration   1: 3.761 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.761 ops/ms


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
# Warmup Iteration   1: 5.794 ±(99.9%) 0.100 ms/op
Iteration   1: 3.194 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.194 ms/op


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
# Warmup Iteration   1: 3.932 ±(99.9%) 0.055 ms/op
Iteration   1: 2.044 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.044 ms/op


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
# Warmup Iteration   1: 5.396 ±(99.9%) 0.053 ms/op
Iteration   1: 3.050 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.050 ms/op


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
# Warmup Iteration   1: 13.633 ±(99.9%) 0.217 ms/op
Iteration   1: 8.934 ±(99.9%) 0.104 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.934 ms/op


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
# Warmup Iteration   1: 5.771 ±(99.9%) 0.218 ms/op
Iteration   1: 3.346 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   8.343 ms/op
                 createUser·p0.999:  16.803 ms/op
                 createUser·p0.9999: 18.842 ms/op
                 createUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9557
  mean =      3.346 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 895 
    [ 2.500,  3.750) = 6834 
    [ 3.750,  5.000) = 1405 
    [ 5.000,  6.250) = 212 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.992 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      8.343 ms/op
     p(99.9000) =     16.803 ms/op
     p(99.9900) =     18.842 ms/op
     p(99.9990) =     18.842 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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
# Warmup Iteration   1: 3.068 ±(99.9%) 0.067 ms/op
Iteration   1: 1.791 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.343 ms/op
                 existUser·p0.50:   1.671 ms/op
                 existUser·p0.90:   2.327 ms/op
                 existUser·p0.95:   2.478 ms/op
                 existUser·p0.99:   3.524 ms/op
                 existUser·p0.999:  18.153 ms/op
                 existUser·p0.9999: 18.823 ms/op
                 existUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17853
  mean =      1.791 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1175 
    [ 1.250,  2.500) = 15860 
    [ 2.500,  3.750) = 648 
    [ 3.750,  5.000) = 69 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.343 ms/op
     p(50.0000) =      1.671 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.478 ms/op
     p(99.0000) =      3.524 ms/op
     p(99.9000) =     18.153 ms/op
     p(99.9900) =     18.823 ms/op
     p(99.9990) =     18.874 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


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
# Warmup Iteration   1: 4.376 ±(99.9%) 0.102 ms/op
Iteration   1: 3.456 ±(99.9%) 0.146 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   4.149 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   6.022 ms/op
                 getUser·p0.999:  75.855 ms/op
                 getUser·p0.9999: 77.070 ms/op
                 getUser·p1.00:   77.070 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9272
  mean =      3.456 ±(99.9%) 0.146 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9017 
    [ 5.000, 10.000) = 223 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      6.022 ms/op
     p(99.9000) =     75.855 ms/op
     p(99.9900) =     77.070 ms/op
     p(99.9990) =     77.070 ms/op
     p(99.9999) =     77.070 ms/op
    p(100.0000) =     77.070 ms/op


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
# Warmup Iteration   1: 13.265 ±(99.9%) 0.438 ms/op
Iteration   1: 7.930 ±(99.9%) 0.119 ms/op
                 listUser·p0.00:   2.904 ms/op
                 listUser·p0.50:   7.582 ms/op
                 listUser·p0.90:   10.387 ms/op
                 listUser·p0.95:   11.698 ms/op
                 listUser·p0.99:   16.994 ms/op
                 listUser·p0.999:  22.048 ms/op
                 listUser·p0.9999: 22.938 ms/op
                 listUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4036
  mean =      7.930 ±(99.9%) 0.119 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 139 
    [ 5.000,  7.500) = 1813 
    [ 7.500, 10.000) = 1571 
    [10.000, 12.500) = 368 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.904 ms/op
     p(50.0000) =      7.582 ms/op
     p(90.0000) =     10.387 ms/op
     p(95.0000) =     11.698 ms/op
     p(99.0000) =     16.994 ms/op
     p(99.9000) =     22.048 ms/op
     p(99.9900) =     22.938 ms/op
     p(99.9990) =     22.938 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.164          ops/ms
Client.existUser                       thrpt         12.065          ops/ms
Client.getUser                         thrpt          8.787          ops/ms
Client.listUser                        thrpt          3.761          ops/ms
Client.createUser                       avgt          3.194           ms/op
Client.existUser                        avgt          2.044           ms/op
Client.getUser                          avgt          3.050           ms/op
Client.listUser                         avgt          8.934           ms/op
Client.createUser                     sample   9557   3.346 ± 0.041   ms/op
Client.createUser:createUser·p0.00    sample          0.992           ms/op
Client.createUser:createUser·p0.50    sample          3.109           ms/op
Client.createUser:createUser·p0.90    sample          4.342           ms/op
Client.createUser:createUser·p0.95    sample          4.850           ms/op
Client.createUser:createUser·p0.99    sample          8.343           ms/op
Client.createUser:createUser·p0.999   sample         16.803           ms/op
Client.createUser:createUser·p0.9999  sample         18.842           ms/op
Client.createUser:createUser·p1.00    sample         18.842           ms/op
Client.existUser                      sample  17853   1.791 ± 0.021   ms/op
Client.existUser:existUser·p0.00      sample          0.343           ms/op
Client.existUser:existUser·p0.50      sample          1.671           ms/op
Client.existUser:existUser·p0.90      sample          2.327           ms/op
Client.existUser:existUser·p0.95      sample          2.478           ms/op
Client.existUser:existUser·p0.99      sample          3.524           ms/op
Client.existUser:existUser·p0.999     sample         18.153           ms/op
Client.existUser:existUser·p0.9999    sample         18.823           ms/op
Client.existUser:existUser·p1.00      sample         18.874           ms/op
Client.getUser                        sample   9272   3.456 ± 0.146   ms/op
Client.getUser:getUser·p0.00          sample          0.839           ms/op
Client.getUser:getUser·p0.50          sample          3.166           ms/op
Client.getUser:getUser·p0.90          sample          4.149           ms/op
Client.getUser:getUser·p0.95          sample          4.514           ms/op
Client.getUser:getUser·p0.99          sample          6.022           ms/op
Client.getUser:getUser·p0.999         sample         75.855           ms/op
Client.getUser:getUser·p0.9999        sample         77.070           ms/op
Client.getUser:getUser·p1.00          sample         77.070           ms/op
Client.listUser                       sample   4036   7.930 ± 0.119   ms/op
Client.listUser:listUser·p0.00        sample          2.904           ms/op
Client.listUser:listUser·p0.50        sample          7.582           ms/op
Client.listUser:listUser·p0.90        sample         10.387           ms/op
Client.listUser:listUser·p0.95        sample         11.698           ms/op
Client.listUser:listUser·p0.99        sample         16.994           ms/op
Client.listUser:listUser·p0.999       sample         22.048           ms/op
Client.listUser:listUser·p0.9999      sample         22.938           ms/op
Client.listUser:listUser·p1.00        sample         22.938           ms/op
