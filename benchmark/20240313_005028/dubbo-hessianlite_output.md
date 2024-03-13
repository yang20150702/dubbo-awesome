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
# Warmup Iteration   1: 2.349 ops/ms
Iteration   1: 6.313 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.313 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.619 ops/ms
Iteration   1: 11.755 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.755 ops/ms


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
# Warmup Iteration   1: 4.720 ops/ms
Iteration   1: 8.935 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.935 ops/ms


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
# Warmup Iteration   1: 1.906 ops/ms
Iteration   1: 3.243 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.243 ops/ms


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
# Warmup Iteration   1: 6.185 ±(99.9%) 0.082 ms/op
Iteration   1: 3.204 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.204 ms/op


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.051 ms/op
Iteration   1: 2.078 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.078 ms/op


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
# Warmup Iteration   1: 4.613 ±(99.9%) 0.059 ms/op
Iteration   1: 3.498 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.498 ms/op


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
# Warmup Iteration   1: 13.335 ±(99.9%) 0.192 ms/op
Iteration   1: 8.251 ±(99.9%) 0.072 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.251 ms/op


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
# Warmup Iteration   1: 5.026 ±(99.9%) 0.101 ms/op
Iteration   1: 2.909 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.653 ms/op
                 createUser·p0.99:   6.401 ms/op
                 createUser·p0.999:  12.207 ms/op
                 createUser·p0.9999: 13.024 ms/op
                 createUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10964
  mean =      2.909 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 3729 
    [ 2.500,  3.750) = 5905 
    [ 3.750,  5.000) = 1021 
    [ 5.000,  6.250) = 178 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      2.666 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      6.401 ms/op
     p(99.9000) =     12.207 ms/op
     p(99.9900) =     13.024 ms/op
     p(99.9990) =     13.025 ms/op
     p(99.9999) =     13.025 ms/op
    p(100.0000) =     13.025 ms/op


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
# Warmup Iteration   1: 3.132 ±(99.9%) 0.066 ms/op
Iteration   1: 1.890 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.556 ms/op
                 existUser·p0.50:   1.757 ms/op
                 existUser·p0.90:   2.318 ms/op
                 existUser·p0.95:   2.540 ms/op
                 existUser·p0.99:   4.116 ms/op
                 existUser·p0.999:  17.564 ms/op
                 existUser·p0.9999: 17.828 ms/op
                 existUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17334
  mean =      1.890 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 345 
    [ 1.250,  2.500) = 15995 
    [ 2.500,  3.750) = 777 
    [ 3.750,  5.000) = 111 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      1.757 ms/op
     p(90.0000) =      2.318 ms/op
     p(95.0000) =      2.540 ms/op
     p(99.0000) =      4.116 ms/op
     p(99.9000) =     17.564 ms/op
     p(99.9900) =     17.828 ms/op
     p(99.9990) =     18.285 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 4.916 ±(99.9%) 0.122 ms/op
Iteration   1: 3.281 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.631 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.723 ms/op
                 getUser·p0.99:   6.263 ms/op
                 getUser·p0.999:  9.209 ms/op
                 getUser·p0.9999: 20.742 ms/op
                 getUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9748
  mean =      3.281 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1490 
    [ 2.500,  5.000) = 7944 
    [ 5.000,  7.500) = 296 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.723 ms/op
     p(99.0000) =      6.263 ms/op
     p(99.9000) =      9.209 ms/op
     p(99.9900) =     20.742 ms/op
     p(99.9990) =     20.742 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 12.623 ±(99.9%) 0.472 ms/op
Iteration   1: 7.942 ±(99.9%) 0.124 ms/op
                 listUser·p0.00:   2.732 ms/op
                 listUser·p0.50:   7.545 ms/op
                 listUser·p0.90:   10.043 ms/op
                 listUser·p0.95:   11.141 ms/op
                 listUser·p0.99:   19.956 ms/op
                 listUser·p0.999:  26.706 ms/op
                 listUser·p0.9999: 29.196 ms/op
                 listUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4024
  mean =      7.942 ±(99.9%) 0.124 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 106 
    [ 5.000,  7.500) = 1857 
    [ 7.500, 10.000) = 1646 
    [10.000, 12.500) = 295 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.732 ms/op
     p(50.0000) =      7.545 ms/op
     p(90.0000) =     10.043 ms/op
     p(95.0000) =     11.141 ms/op
     p(99.0000) =     19.956 ms/op
     p(99.9000) =     26.706 ms/op
     p(99.9900) =     29.196 ms/op
     p(99.9990) =     29.196 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.313          ops/ms
Client.existUser                       thrpt         11.755          ops/ms
Client.getUser                         thrpt          8.935          ops/ms
Client.listUser                        thrpt          3.243          ops/ms
Client.createUser                       avgt          3.204           ms/op
Client.existUser                        avgt          2.078           ms/op
Client.getUser                          avgt          3.498           ms/op
Client.listUser                         avgt          8.251           ms/op
Client.createUser                     sample  10964   2.909 ± 0.030   ms/op
Client.createUser:createUser·p0.00    sample          0.916           ms/op
Client.createUser:createUser·p0.50    sample          2.666           ms/op
Client.createUser:createUser·p0.90    sample          4.022           ms/op
Client.createUser:createUser·p0.95    sample          4.653           ms/op
Client.createUser:createUser·p0.99    sample          6.401           ms/op
Client.createUser:createUser·p0.999   sample         12.207           ms/op
Client.createUser:createUser·p0.9999  sample         13.024           ms/op
Client.createUser:createUser·p1.00    sample         13.025           ms/op
Client.existUser                      sample  17334   1.890 ± 0.021   ms/op
Client.existUser:existUser·p0.00      sample          0.556           ms/op
Client.existUser:existUser·p0.50      sample          1.757           ms/op
Client.existUser:existUser·p0.90      sample          2.318           ms/op
Client.existUser:existUser·p0.95      sample          2.540           ms/op
Client.existUser:existUser·p0.99      sample          4.116           ms/op
Client.existUser:existUser·p0.999     sample         17.564           ms/op
Client.existUser:existUser·p0.9999    sample         17.828           ms/op
Client.existUser:existUser·p1.00      sample         18.285           ms/op
Client.getUser                        sample   9748   3.281 ± 0.032   ms/op
Client.getUser:getUser·p0.00          sample          0.631           ms/op
Client.getUser:getUser·p0.50          sample          3.178           ms/op
Client.getUser:getUser·p0.90          sample          4.202           ms/op
Client.getUser:getUser·p0.95          sample          4.723           ms/op
Client.getUser:getUser·p0.99          sample          6.263           ms/op
Client.getUser:getUser·p0.999         sample          9.209           ms/op
Client.getUser:getUser·p0.9999        sample         20.742           ms/op
Client.getUser:getUser·p1.00          sample         20.742           ms/op
Client.listUser                       sample   4024   7.942 ± 0.124   ms/op
Client.listUser:listUser·p0.00        sample          2.732           ms/op
Client.listUser:listUser·p0.50        sample          7.545           ms/op
Client.listUser:listUser·p0.90        sample         10.043           ms/op
Client.listUser:listUser·p0.95        sample         11.141           ms/op
Client.listUser:listUser·p0.99        sample         19.956           ms/op
Client.listUser:listUser·p0.999       sample         26.706           ms/op
Client.listUser:listUser·p0.9999      sample         29.196           ms/op
Client.listUser:listUser·p1.00        sample         29.196           ms/op
