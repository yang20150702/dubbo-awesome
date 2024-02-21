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
# Warmup Iteration   1: 2.253 ops/ms
Iteration   1: 6.055 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.055 ops/ms


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
# Warmup Iteration   1: 6.310 ops/ms
Iteration   1: 11.631 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.631 ops/ms


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
# Warmup Iteration   1: 4.347 ops/ms
Iteration   1: 8.752 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.752 ops/ms


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
# Warmup Iteration   1: 2.100 ops/ms
Iteration   1: 3.205 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.205 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.930 ±(99.9%) 0.084 ms/op
Iteration   1: 3.335 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.335 ms/op


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
# Warmup Iteration   1: 3.610 ±(99.9%) 0.038 ms/op
Iteration   1: 2.013 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.013 ms/op


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
# Warmup Iteration   1: 5.126 ±(99.9%) 0.143 ms/op
Iteration   1: 3.358 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.358 ms/op


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
# Warmup Iteration   1: 12.476 ±(99.9%) 0.212 ms/op
Iteration   1: 9.717 ±(99.9%) 0.087 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.717 ms/op


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
# Warmup Iteration   1: 5.474 ±(99.9%) 0.117 ms/op
Iteration   1: 3.329 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   4.262 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   7.457 ms/op
                 createUser·p0.999:  15.696 ms/op
                 createUser·p0.9999: 15.860 ms/op
                 createUser·p1.00:   15.860 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9676
  mean =      3.329 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 860 
    [ 2.500,  3.750) = 7029 
    [ 3.750,  5.000) = 1397 
    [ 5.000,  6.250) = 202 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      4.262 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.457 ms/op
     p(99.9000) =     15.696 ms/op
     p(99.9900) =     15.860 ms/op
     p(99.9990) =     15.860 ms/op
     p(99.9999) =     15.860 ms/op
    p(100.0000) =     15.860 ms/op


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
# Warmup Iteration   1: 3.167 ±(99.9%) 0.070 ms/op
Iteration   1: 1.739 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.428 ms/op
                 existUser·p0.50:   1.577 ms/op
                 existUser·p0.90:   2.232 ms/op
                 existUser·p0.95:   2.437 ms/op
                 existUser·p0.99:   5.005 ms/op
                 existUser·p0.999:  15.092 ms/op
                 existUser·p0.9999: 15.182 ms/op
                 existUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18419
  mean =      1.739 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2058 
    [ 1.250,  2.500) = 15551 
    [ 2.500,  3.750) = 553 
    [ 3.750,  5.000) = 67 
    [ 5.000,  6.250) = 78 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.428 ms/op
     p(50.0000) =      1.577 ms/op
     p(90.0000) =      2.232 ms/op
     p(95.0000) =      2.437 ms/op
     p(99.0000) =      5.005 ms/op
     p(99.9000) =     15.092 ms/op
     p(99.9900) =     15.182 ms/op
     p(99.9990) =     15.237 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


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
# Warmup Iteration   1: 5.083 ±(99.9%) 0.130 ms/op
Iteration   1: 3.123 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.309 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   5.282 ms/op
                 getUser·p0.999:  6.136 ms/op
                 getUser·p0.9999: 11.042 ms/op
                 getUser·p1.00:   11.076 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10239
  mean =      3.123 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 146 
    [ 2.000,  3.000) = 4973 
    [ 3.000,  4.000) = 3911 
    [ 4.000,  5.000) = 1086 
    [ 5.000,  6.000) = 97 
    [ 6.000,  7.000) = 24 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 1 
    [10.000, 11.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.309 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.282 ms/op
     p(99.9000) =      6.136 ms/op
     p(99.9900) =     11.042 ms/op
     p(99.9990) =     11.076 ms/op
     p(99.9999) =     11.076 ms/op
    p(100.0000) =     11.076 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 13.731 ±(99.9%) 0.449 ms/op
Iteration   1: 9.113 ±(99.9%) 0.176 ms/op
                 listUser·p0.00:   2.095 ms/op
                 listUser·p0.50:   8.552 ms/op
                 listUser·p0.90:   12.419 ms/op
                 listUser·p0.95:   14.074 ms/op
                 listUser·p0.99:   20.876 ms/op
                 listUser·p0.999:  34.014 ms/op
                 listUser·p0.9999: 44.958 ms/op
                 listUser·p1.00:   44.958 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3494
  mean =      9.113 ±(99.9%) 0.176 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 81 
    [ 5.000, 10.000) = 2489 
    [10.000, 15.000) = 800 
    [15.000, 20.000) = 82 
    [20.000, 25.000) = 19 
    [25.000, 30.000) = 10 
    [30.000, 35.000) = 12 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.095 ms/op
     p(50.0000) =      8.552 ms/op
     p(90.0000) =     12.419 ms/op
     p(95.0000) =     14.074 ms/op
     p(99.0000) =     20.876 ms/op
     p(99.9000) =     34.014 ms/op
     p(99.9900) =     44.958 ms/op
     p(99.9990) =     44.958 ms/op
     p(99.9999) =     44.958 ms/op
    p(100.0000) =     44.958 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.055          ops/ms
Client.existUser                       thrpt         11.631          ops/ms
Client.getUser                         thrpt          8.752          ops/ms
Client.listUser                        thrpt          3.205          ops/ms
Client.createUser                       avgt          3.335           ms/op
Client.existUser                        avgt          2.013           ms/op
Client.getUser                          avgt          3.358           ms/op
Client.listUser                         avgt          9.717           ms/op
Client.createUser                     sample   9676   3.329 ± 0.038   ms/op
Client.createUser:createUser·p0.00    sample          0.973           ms/op
Client.createUser:createUser·p0.50    sample          3.133           ms/op
Client.createUser:createUser·p0.90    sample          4.262           ms/op
Client.createUser:createUser·p0.95    sample          4.776           ms/op
Client.createUser:createUser·p0.99    sample          7.457           ms/op
Client.createUser:createUser·p0.999   sample         15.696           ms/op
Client.createUser:createUser·p0.9999  sample         15.860           ms/op
Client.createUser:createUser·p1.00    sample         15.860           ms/op
Client.existUser                      sample  18419   1.739 ± 0.022   ms/op
Client.existUser:existUser·p0.00      sample          0.428           ms/op
Client.existUser:existUser·p0.50      sample          1.577           ms/op
Client.existUser:existUser·p0.90      sample          2.232           ms/op
Client.existUser:existUser·p0.95      sample          2.437           ms/op
Client.existUser:existUser·p0.99      sample          5.005           ms/op
Client.existUser:existUser·p0.999     sample         15.092           ms/op
Client.existUser:existUser·p0.9999    sample         15.182           ms/op
Client.existUser:existUser·p1.00      sample         15.237           ms/op
Client.getUser                        sample  10239   3.123 ± 0.023   ms/op
Client.getUser:getUser·p0.00          sample          1.309           ms/op
Client.getUser:getUser·p0.50          sample          3.002           ms/op
Client.getUser:getUser·p0.90          sample          4.121           ms/op
Client.getUser:getUser·p0.95          sample          4.432           ms/op
Client.getUser:getUser·p0.99          sample          5.282           ms/op
Client.getUser:getUser·p0.999         sample          6.136           ms/op
Client.getUser:getUser·p0.9999        sample         11.042           ms/op
Client.getUser:getUser·p1.00          sample         11.076           ms/op
Client.listUser                       sample   3494   9.113 ± 0.176   ms/op
Client.listUser:listUser·p0.00        sample          2.095           ms/op
Client.listUser:listUser·p0.50        sample          8.552           ms/op
Client.listUser:listUser·p0.90        sample         12.419           ms/op
Client.listUser:listUser·p0.95        sample         14.074           ms/op
Client.listUser:listUser·p0.99        sample         20.876           ms/op
Client.listUser:listUser·p0.999       sample         34.014           ms/op
Client.listUser:listUser·p0.9999      sample         44.958           ms/op
Client.listUser:listUser·p1.00        sample         44.958           ms/op
