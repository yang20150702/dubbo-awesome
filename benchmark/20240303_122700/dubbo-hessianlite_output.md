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
# Warmup Iteration   1: 2.622 ops/ms
Iteration   1: 6.300 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.300 ops/ms


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
# Warmup Iteration   1: 6.459 ops/ms
Iteration   1: 12.738 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.738 ops/ms


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
# Warmup Iteration   1: 4.241 ops/ms
Iteration   1: 8.773 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.773 ops/ms


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
# Warmup Iteration   1: 2.033 ops/ms
Iteration   1: 3.236 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.236 ops/ms


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
# Warmup Iteration   1: 5.337 ±(99.9%) 0.074 ms/op
Iteration   1: 3.275 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.275 ms/op


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
# Warmup Iteration   1: 3.145 ±(99.9%) 0.032 ms/op
Iteration   1: 1.901 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.901 ms/op


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
# Warmup Iteration   1: 4.844 ±(99.9%) 0.070 ms/op
Iteration   1: 3.231 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.231 ms/op


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
# Warmup Iteration   1: 13.254 ±(99.9%) 0.295 ms/op
Iteration   1: 9.923 ±(99.9%) 0.121 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.923 ms/op


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
# Warmup Iteration   1: 5.050 ±(99.9%) 0.116 ms/op
Iteration   1: 3.059 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.427 ms/op
                 createUser·p0.50:   2.863 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.841 ms/op
                 createUser·p0.999:  10.402 ms/op
                 createUser·p0.9999: 11.631 ms/op
                 createUser·p1.00:   11.633 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10709
  mean =      3.059 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1445 
    [ 2.500,  3.750) = 8076 
    [ 3.750,  5.000) = 1103 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.427 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      4.841 ms/op
     p(99.9000) =     10.402 ms/op
     p(99.9900) =     11.631 ms/op
     p(99.9990) =     11.633 ms/op
     p(99.9999) =     11.633 ms/op
    p(100.0000) =     11.633 ms/op


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
# Warmup Iteration   1: 3.300 ±(99.9%) 0.086 ms/op
Iteration   1: 2.013 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   1.946 ms/op
                 existUser·p0.90:   2.433 ms/op
                 existUser·p0.95:   2.605 ms/op
                 existUser·p0.99:   4.124 ms/op
                 existUser·p0.999:  6.103 ms/op
                 existUser·p0.9999: 8.069 ms/op
                 existUser·p1.00:   8.454 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15874
  mean =      2.013 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 29 
    [1.000, 1.500) = 1045 
    [1.500, 2.000) = 7704 
    [2.000, 2.500) = 5910 
    [2.500, 3.000) = 725 
    [3.000, 3.500) = 178 
    [3.500, 4.000) = 106 
    [4.000, 4.500) = 54 
    [4.500, 5.000) = 21 
    [5.000, 5.500) = 11 
    [5.500, 6.000) = 44 
    [6.000, 6.500) = 40 
    [6.500, 7.000) = 3 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 2 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      1.946 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      4.124 ms/op
     p(99.9000) =      6.103 ms/op
     p(99.9900) =      8.069 ms/op
     p(99.9990) =      8.454 ms/op
     p(99.9999) =      8.454 ms/op
    p(100.0000) =      8.454 ms/op


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
# Warmup Iteration   1: 4.455 ±(99.9%) 0.099 ms/op
Iteration   1: 3.420 ±(99.9%) 0.080 ms/op
                 getUser·p0.00:   0.677 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   4.610 ms/op
                 getUser·p0.99:   6.638 ms/op
                 getUser·p0.999:  42.271 ms/op
                 getUser·p0.9999: 48.431 ms/op
                 getUser·p1.00:   48.431 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9363
  mean =      3.420 ±(99.9%) 0.080 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9056 
    [ 5.000, 10.000) = 269 
    [10.000, 15.000) = 4 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.610 ms/op
     p(99.0000) =      6.638 ms/op
     p(99.9000) =     42.271 ms/op
     p(99.9900) =     48.431 ms/op
     p(99.9990) =     48.431 ms/op
     p(99.9999) =     48.431 ms/op
    p(100.0000) =     48.431 ms/op


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
# Warmup Iteration   1: 13.658 ±(99.9%) 0.463 ms/op
Iteration   1: 8.429 ±(99.9%) 0.115 ms/op
                 listUser·p0.00:   1.812 ms/op
                 listUser·p0.50:   8.200 ms/op
                 listUser·p0.90:   11.043 ms/op
                 listUser·p0.95:   12.173 ms/op
                 listUser·p0.99:   15.405 ms/op
                 listUser·p0.999:  21.377 ms/op
                 listUser·p0.9999: 27.197 ms/op
                 listUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3791
  mean =      8.429 ±(99.9%) 0.115 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 67 
    [ 5.000,  7.500) = 1254 
    [ 7.500, 10.000) = 1773 
    [10.000, 12.500) = 538 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.812 ms/op
     p(50.0000) =      8.200 ms/op
     p(90.0000) =     11.043 ms/op
     p(95.0000) =     12.173 ms/op
     p(99.0000) =     15.405 ms/op
     p(99.9000) =     21.377 ms/op
     p(99.9900) =     27.197 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.300          ops/ms
Client.existUser                       thrpt         12.738          ops/ms
Client.getUser                         thrpt          8.773          ops/ms
Client.listUser                        thrpt          3.236          ops/ms
Client.createUser                       avgt          3.275           ms/op
Client.existUser                        avgt          1.901           ms/op
Client.getUser                          avgt          3.231           ms/op
Client.listUser                         avgt          9.923           ms/op
Client.createUser                     sample  10709   3.059 ± 0.022   ms/op
Client.createUser:createUser·p0.00    sample          1.427           ms/op
Client.createUser:createUser·p0.50    sample          2.863           ms/op
Client.createUser:createUser·p0.90    sample          3.793           ms/op
Client.createUser:createUser·p0.95    sample          4.010           ms/op
Client.createUser:createUser·p0.99    sample          4.841           ms/op
Client.createUser:createUser·p0.999   sample         10.402           ms/op
Client.createUser:createUser·p0.9999  sample         11.631           ms/op
Client.createUser:createUser·p1.00    sample         11.633           ms/op
Client.existUser                      sample  15874   2.013 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.767           ms/op
Client.existUser:existUser·p0.50      sample          1.946           ms/op
Client.existUser:existUser·p0.90      sample          2.433           ms/op
Client.existUser:existUser·p0.95      sample          2.605           ms/op
Client.existUser:existUser·p0.99      sample          4.124           ms/op
Client.existUser:existUser·p0.999     sample          6.103           ms/op
Client.existUser:existUser·p0.9999    sample          8.069           ms/op
Client.existUser:existUser·p1.00      sample          8.454           ms/op
Client.getUser                        sample   9363   3.420 ± 0.080   ms/op
Client.getUser:getUser·p0.00          sample          0.677           ms/op
Client.getUser:getUser·p0.50          sample          3.215           ms/op
Client.getUser:getUser·p0.90          sample          4.243           ms/op
Client.getUser:getUser·p0.95          sample          4.610           ms/op
Client.getUser:getUser·p0.99          sample          6.638           ms/op
Client.getUser:getUser·p0.999         sample         42.271           ms/op
Client.getUser:getUser·p0.9999        sample         48.431           ms/op
Client.getUser:getUser·p1.00          sample         48.431           ms/op
Client.listUser                       sample   3791   8.429 ± 0.115   ms/op
Client.listUser:listUser·p0.00        sample          1.812           ms/op
Client.listUser:listUser·p0.50        sample          8.200           ms/op
Client.listUser:listUser·p0.90        sample         11.043           ms/op
Client.listUser:listUser·p0.95        sample         12.173           ms/op
Client.listUser:listUser·p0.99        sample         15.405           ms/op
Client.listUser:listUser·p0.999       sample         21.377           ms/op
Client.listUser:listUser·p0.9999      sample         27.197           ms/op
Client.listUser:listUser·p1.00        sample         27.197           ms/op
