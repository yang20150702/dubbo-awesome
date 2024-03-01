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
# Warmup Iteration   1: 2.256 ops/ms
Iteration   1: 5.455 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.455 ops/ms


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
# Warmup Iteration   1: 6.374 ops/ms
Iteration   1: 13.733 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.733 ops/ms


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
# Warmup Iteration   1: 4.875 ops/ms
Iteration   1: 8.646 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.646 ops/ms


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
# Warmup Iteration   1: 2.337 ops/ms
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
# Warmup Iteration   1: 5.246 ±(99.9%) 0.074 ms/op
Iteration   1: 3.139 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.139 ms/op


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
# Warmup Iteration   1: 3.269 ±(99.9%) 0.035 ms/op
Iteration   1: 1.983 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.983 ms/op


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
# Warmup Iteration   1: 5.191 ±(99.9%) 0.057 ms/op
Iteration   1: 3.277 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.277 ms/op


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
# Warmup Iteration   1: 11.700 ±(99.9%) 0.244 ms/op
Iteration   1: 9.254 ±(99.9%) 0.146 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.254 ms/op


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
# Warmup Iteration   1: 6.209 ±(99.9%) 0.463 ms/op
Iteration   1: 2.879 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   1.180 ms/op
                 createUser·p0.50:   2.740 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   5.982 ms/op
                 createUser·p0.999:  12.481 ms/op
                 createUser·p0.9999: 13.482 ms/op
                 createUser·p1.00:   13.484 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11095
  mean =      2.879 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 3633 
    [ 2.500,  3.750) = 6706 
    [ 3.750,  5.000) = 538 
    [ 5.000,  6.250) = 113 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      2.740 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      5.982 ms/op
     p(99.9000) =     12.481 ms/op
     p(99.9900) =     13.482 ms/op
     p(99.9990) =     13.484 ms/op
     p(99.9999) =     13.484 ms/op
    p(100.0000) =     13.484 ms/op


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
# Warmup Iteration   1: 3.073 ±(99.9%) 0.070 ms/op
Iteration   1: 1.823 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.497 ms/op
                 existUser·p0.50:   1.767 ms/op
                 existUser·p0.90:   2.212 ms/op
                 existUser·p0.95:   2.351 ms/op
                 existUser·p0.99:   2.933 ms/op
                 existUser·p0.999:  13.081 ms/op
                 existUser·p0.9999: 13.185 ms/op
                 existUser·p1.00:   13.222 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17588
  mean =      1.823 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 553 
    [ 1.250,  2.500) = 16536 
    [ 2.500,  3.750) = 402 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 0 
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
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      1.767 ms/op
     p(90.0000) =      2.212 ms/op
     p(95.0000) =      2.351 ms/op
     p(99.0000) =      2.933 ms/op
     p(99.9000) =     13.081 ms/op
     p(99.9900) =     13.185 ms/op
     p(99.9990) =     13.222 ms/op
     p(99.9999) =     13.222 ms/op
    p(100.0000) =     13.222 ms/op


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
# Warmup Iteration   1: 4.197 ±(99.9%) 0.092 ms/op
Iteration   1: 3.149 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.378 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.950 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.021 ms/op
                 getUser·p0.999:  5.947 ms/op
                 getUser·p0.9999: 7.353 ms/op
                 getUser·p1.00:   7.373 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10156
  mean =      3.149 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 4 
    [1.500, 2.000) = 91 
    [2.000, 2.500) = 1740 
    [2.500, 3.000) = 2364 
    [3.000, 3.500) = 3113 
    [3.500, 4.000) = 1922 
    [4.000, 4.500) = 664 
    [4.500, 5.000) = 155 
    [5.000, 5.500) = 50 
    [5.500, 6.000) = 48 
    [6.000, 6.500) = 4 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.378 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.950 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.021 ms/op
     p(99.9000) =      5.947 ms/op
     p(99.9900) =      7.353 ms/op
     p(99.9990) =      7.373 ms/op
     p(99.9999) =      7.373 ms/op
    p(100.0000) =      7.373 ms/op


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
# Warmup Iteration   1: 11.663 ±(99.9%) 0.430 ms/op
Iteration   1: 8.035 ±(99.9%) 0.160 ms/op
                 listUser·p0.00:   2.982 ms/op
                 listUser·p0.50:   7.504 ms/op
                 listUser·p0.90:   10.060 ms/op
                 listUser·p0.95:   11.305 ms/op
                 listUser·p0.99:   22.396 ms/op
                 listUser·p0.999:  34.206 ms/op
                 listUser·p0.9999: 34.669 ms/op
                 listUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4053
  mean =      8.035 ±(99.9%) 0.160 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 111 
    [ 5.000,  7.500) = 1909 
    [ 7.500, 10.000) = 1613 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.982 ms/op
     p(50.0000) =      7.504 ms/op
     p(90.0000) =     10.060 ms/op
     p(95.0000) =     11.305 ms/op
     p(99.0000) =     22.396 ms/op
     p(99.9000) =     34.206 ms/op
     p(99.9900) =     34.669 ms/op
     p(99.9990) =     34.669 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.455          ops/ms
Client.existUser                       thrpt         13.733          ops/ms
Client.getUser                         thrpt          8.646          ops/ms
Client.listUser                        thrpt          3.832          ops/ms
Client.createUser                       avgt          3.139           ms/op
Client.existUser                        avgt          1.983           ms/op
Client.getUser                          avgt          3.277           ms/op
Client.listUser                         avgt          9.254           ms/op
Client.createUser                     sample  11095   2.879 ± 0.029   ms/op
Client.createUser:createUser·p0.00    sample          1.180           ms/op
Client.createUser:createUser·p0.50    sample          2.740           ms/op
Client.createUser:createUser·p0.90    sample          3.555           ms/op
Client.createUser:createUser·p0.95    sample          3.994           ms/op
Client.createUser:createUser·p0.99    sample          5.982           ms/op
Client.createUser:createUser·p0.999   sample         12.481           ms/op
Client.createUser:createUser·p0.9999  sample         13.482           ms/op
Client.createUser:createUser·p1.00    sample         13.484           ms/op
Client.existUser                      sample  17588   1.823 ± 0.015   ms/op
Client.existUser:existUser·p0.00      sample          0.497           ms/op
Client.existUser:existUser·p0.50      sample          1.767           ms/op
Client.existUser:existUser·p0.90      sample          2.212           ms/op
Client.existUser:existUser·p0.95      sample          2.351           ms/op
Client.existUser:existUser·p0.99      sample          2.933           ms/op
Client.existUser:existUser·p0.999     sample         13.081           ms/op
Client.existUser:existUser·p0.9999    sample         13.185           ms/op
Client.existUser:existUser·p1.00      sample         13.222           ms/op
Client.getUser                        sample  10156   3.149 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          1.378           ms/op
Client.getUser:getUser·p0.50          sample          3.133           ms/op
Client.getUser:getUser·p0.90          sample          3.950           ms/op
Client.getUser:getUser·p0.95          sample          4.235           ms/op
Client.getUser:getUser·p0.99          sample          5.021           ms/op
Client.getUser:getUser·p0.999         sample          5.947           ms/op
Client.getUser:getUser·p0.9999        sample          7.353           ms/op
Client.getUser:getUser·p1.00          sample          7.373           ms/op
Client.listUser                       sample   4053   8.035 ± 0.160   ms/op
Client.listUser:listUser·p0.00        sample          2.982           ms/op
Client.listUser:listUser·p0.50        sample          7.504           ms/op
Client.listUser:listUser·p0.90        sample         10.060           ms/op
Client.listUser:listUser·p0.95        sample         11.305           ms/op
Client.listUser:listUser·p0.99        sample         22.396           ms/op
Client.listUser:listUser·p0.999       sample         34.206           ms/op
Client.listUser:listUser·p0.9999      sample         34.669           ms/op
Client.listUser:listUser·p1.00        sample         34.669           ms/op
