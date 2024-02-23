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
Iteration   1: 5.727 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.727 ops/ms


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
# Warmup Iteration   1: 6.375 ops/ms
Iteration   1: 13.283 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.283 ops/ms


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
# Warmup Iteration   1: 4.330 ops/ms
Iteration   1: 7.525 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.525 ops/ms


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
# Warmup Iteration   1: 1.935 ops/ms
Iteration   1: 3.492 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.492 ops/ms


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
# Warmup Iteration   1: 5.477 ±(99.9%) 0.073 ms/op
Iteration   1: 3.076 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.076 ms/op


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
# Warmup Iteration   1: 3.046 ±(99.9%) 0.031 ms/op
Iteration   1: 1.732 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.732 ms/op


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
# Warmup Iteration   1: 4.692 ±(99.9%) 0.057 ms/op
Iteration   1: 2.889 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.889 ms/op


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
# Warmup Iteration   1: 11.909 ±(99.9%) 0.176 ms/op
Iteration   1: 8.660 ±(99.9%) 0.083 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.660 ms/op


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
# Warmup Iteration   1: 5.143 ±(99.9%) 0.110 ms/op
Iteration   1: 3.037 ±(99.9%) 0.070 ms/op
                 createUser·p0.00:   0.740 ms/op
                 createUser·p0.50:   2.818 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   4.964 ms/op
                 createUser·p0.999:  40.567 ms/op
                 createUser·p0.9999: 46.707 ms/op
                 createUser·p1.00:   46.727 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10517
  mean =      3.037 ±(99.9%) 0.070 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10417 
    [ 5.000, 10.000) = 68 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 11 
    [40.000, 45.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      2.818 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      4.964 ms/op
     p(99.9000) =     40.567 ms/op
     p(99.9900) =     46.707 ms/op
     p(99.9990) =     46.727 ms/op
     p(99.9999) =     46.727 ms/op
    p(100.0000) =     46.727 ms/op


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
# Warmup Iteration   1: 3.062 ±(99.9%) 0.067 ms/op
Iteration   1: 2.156 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.574 ms/op
                 existUser·p0.50:   2.036 ms/op
                 existUser·p0.90:   2.724 ms/op
                 existUser·p0.95:   2.961 ms/op
                 existUser·p0.99:   4.289 ms/op
                 existUser·p0.999:  22.090 ms/op
                 existUser·p0.9999: 23.036 ms/op
                 existUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14854
  mean =      2.156 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12179 
    [ 2.500,  5.000) = 2600 
    [ 5.000,  7.500) = 42 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      2.036 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      2.961 ms/op
     p(99.0000) =      4.289 ms/op
     p(99.9000) =     22.090 ms/op
     p(99.9900) =     23.036 ms/op
     p(99.9990) =     23.036 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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
# Warmup Iteration   1: 4.567 ±(99.9%) 0.093 ms/op
Iteration   1: 3.015 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   2.863 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   5.199 ms/op
                 getUser·p0.999:  12.763 ms/op
                 getUser·p0.9999: 14.249 ms/op
                 getUser·p1.00:   14.320 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10618
  mean =      3.015 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1573 
    [ 2.500,  3.750) = 8178 
    [ 3.750,  5.000) = 730 
    [ 5.000,  6.250) = 57 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      5.199 ms/op
     p(99.9000) =     12.763 ms/op
     p(99.9900) =     14.249 ms/op
     p(99.9990) =     14.320 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 12.592 ±(99.9%) 0.471 ms/op
Iteration   1: 9.178 ±(99.9%) 0.127 ms/op
                 listUser·p0.00:   2.662 ms/op
                 listUser·p0.50:   8.913 ms/op
                 listUser·p0.90:   12.354 ms/op
                 listUser·p0.95:   13.746 ms/op
                 listUser·p0.99:   15.794 ms/op
                 listUser·p0.999:  19.482 ms/op
                 listUser·p0.9999: 20.709 ms/op
                 listUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3483
  mean =      9.178 ±(99.9%) 0.127 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 47 
    [ 5.000,  7.500) = 713 
    [ 7.500, 10.000) = 1741 
    [10.000, 12.500) = 664 
    [12.500, 15.000) = 255 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.662 ms/op
     p(50.0000) =      8.913 ms/op
     p(90.0000) =     12.354 ms/op
     p(95.0000) =     13.746 ms/op
     p(99.0000) =     15.794 ms/op
     p(99.9000) =     19.482 ms/op
     p(99.9900) =     20.709 ms/op
     p(99.9990) =     20.709 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.727          ops/ms
Client.existUser                       thrpt         13.283          ops/ms
Client.getUser                         thrpt          7.525          ops/ms
Client.listUser                        thrpt          3.492          ops/ms
Client.createUser                       avgt          3.076           ms/op
Client.existUser                        avgt          1.732           ms/op
Client.getUser                          avgt          2.889           ms/op
Client.listUser                         avgt          8.660           ms/op
Client.createUser                     sample  10517   3.037 ± 0.070   ms/op
Client.createUser:createUser·p0.00    sample          0.740           ms/op
Client.createUser:createUser·p0.50    sample          2.818           ms/op
Client.createUser:createUser·p0.90    sample          3.703           ms/op
Client.createUser:createUser·p0.95    sample          4.104           ms/op
Client.createUser:createUser·p0.99    sample          4.964           ms/op
Client.createUser:createUser·p0.999   sample         40.567           ms/op
Client.createUser:createUser·p0.9999  sample         46.707           ms/op
Client.createUser:createUser·p1.00    sample         46.727           ms/op
Client.existUser                      sample  14854   2.156 ± 0.029   ms/op
Client.existUser:existUser·p0.00      sample          0.574           ms/op
Client.existUser:existUser·p0.50      sample          2.036           ms/op
Client.existUser:existUser·p0.90      sample          2.724           ms/op
Client.existUser:existUser·p0.95      sample          2.961           ms/op
Client.existUser:existUser·p0.99      sample          4.289           ms/op
Client.existUser:existUser·p0.999     sample         22.090           ms/op
Client.existUser:existUser·p0.9999    sample         23.036           ms/op
Client.existUser:existUser·p1.00      sample         23.036           ms/op
Client.getUser                        sample  10618   3.015 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          0.952           ms/op
Client.getUser:getUser·p0.50          sample          2.863           ms/op
Client.getUser:getUser·p0.90          sample          3.670           ms/op
Client.getUser:getUser·p0.95          sample          3.928           ms/op
Client.getUser:getUser·p0.99          sample          5.199           ms/op
Client.getUser:getUser·p0.999         sample         12.763           ms/op
Client.getUser:getUser·p0.9999        sample         14.249           ms/op
Client.getUser:getUser·p1.00          sample         14.320           ms/op
Client.listUser                       sample   3483   9.178 ± 0.127   ms/op
Client.listUser:listUser·p0.00        sample          2.662           ms/op
Client.listUser:listUser·p0.50        sample          8.913           ms/op
Client.listUser:listUser·p0.90        sample         12.354           ms/op
Client.listUser:listUser·p0.95        sample         13.746           ms/op
Client.listUser:listUser·p0.99        sample         15.794           ms/op
Client.listUser:listUser·p0.999       sample         19.482           ms/op
Client.listUser:listUser·p0.9999      sample         20.709           ms/op
Client.listUser:listUser·p1.00        sample         20.709           ms/op
