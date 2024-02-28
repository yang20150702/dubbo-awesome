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
# Warmup Iteration   1: 2.214 ops/ms
Iteration   1: 6.691 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.691 ops/ms


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
# Warmup Iteration   1: 6.283 ops/ms
Iteration   1: 12.535 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.535 ops/ms


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
# Warmup Iteration   1: 4.358 ops/ms
Iteration   1: 9.316 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.316 ops/ms


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
Iteration   1: 3.708 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.708 ops/ms


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
# Warmup Iteration   1: 5.715 ±(99.9%) 0.065 ms/op
Iteration   1: 3.090 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.090 ms/op


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
# Warmup Iteration   1: 3.352 ±(99.9%) 0.042 ms/op
Iteration   1: 1.863 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.863 ms/op


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
# Warmup Iteration   1: 5.217 ±(99.9%) 0.068 ms/op
Iteration   1: 2.951 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.951 ms/op


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
# Warmup Iteration   1: 13.661 ±(99.9%) 0.198 ms/op
Iteration   1: 9.637 ±(99.9%) 0.143 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.637 ms/op


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
# Warmup Iteration   1: 5.156 ±(99.9%) 0.110 ms/op
Iteration   1: 3.038 ±(99.9%) 0.054 ms/op
                 createUser·p0.00:   0.740 ms/op
                 createUser·p0.50:   2.871 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  23.986 ms/op
                 createUser·p0.9999: 25.208 ms/op
                 createUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10639
  mean =      3.038 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2427 
    [ 2.500,  5.000) = 8030 
    [ 5.000,  7.500) = 106 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     23.986 ms/op
     p(99.9900) =     25.208 ms/op
     p(99.9990) =     25.231 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 3.220 ±(99.9%) 0.071 ms/op
Iteration   1: 1.856 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.671 ms/op
                 existUser·p0.50:   1.747 ms/op
                 existUser·p0.90:   2.335 ms/op
                 existUser·p0.95:   2.527 ms/op
                 existUser·p0.99:   4.134 ms/op
                 existUser·p0.999:  13.245 ms/op
                 existUser·p0.9999: 13.618 ms/op
                 existUser·p1.00:   13.713 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17311
  mean =      1.856 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 420 
    [ 1.250,  2.500) = 15924 
    [ 2.500,  3.750) = 752 
    [ 3.750,  5.000) = 160 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      1.747 ms/op
     p(90.0000) =      2.335 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      4.134 ms/op
     p(99.9000) =     13.245 ms/op
     p(99.9900) =     13.618 ms/op
     p(99.9990) =     13.713 ms/op
     p(99.9999) =     13.713 ms/op
    p(100.0000) =     13.713 ms/op


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
# Warmup Iteration   1: 4.412 ±(99.9%) 0.105 ms/op
Iteration   1: 3.515 ±(99.9%) 0.045 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   5.014 ms/op
                 getUser·p0.99:   6.700 ms/op
                 getUser·p0.999:  19.449 ms/op
                 getUser·p0.9999: 19.857 ms/op
                 getUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9113
  mean =      3.515 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 18 
    [ 1.250,  2.500) = 1148 
    [ 2.500,  3.750) = 4876 
    [ 3.750,  5.000) = 2612 
    [ 5.000,  6.250) = 302 
    [ 6.250,  7.500) = 107 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      6.700 ms/op
     p(99.9000) =     19.449 ms/op
     p(99.9900) =     19.857 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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
# Warmup Iteration   1: 12.379 ±(99.9%) 0.508 ms/op
Iteration   1: 8.408 ±(99.9%) 0.115 ms/op
                 listUser·p0.00:   2.748 ms/op
                 listUser·p0.50:   8.045 ms/op
                 listUser·p0.90:   10.928 ms/op
                 listUser·p0.95:   12.042 ms/op
                 listUser·p0.99:   16.744 ms/op
                 listUser·p0.999:  22.269 ms/op
                 listUser·p0.9999: 23.134 ms/op
                 listUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3800
  mean =      8.408 ±(99.9%) 0.115 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 51 
    [ 5.000,  7.500) = 1315 
    [ 7.500, 10.000) = 1781 
    [10.000, 12.500) = 495 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.748 ms/op
     p(50.0000) =      8.045 ms/op
     p(90.0000) =     10.928 ms/op
     p(95.0000) =     12.042 ms/op
     p(99.0000) =     16.744 ms/op
     p(99.9000) =     22.269 ms/op
     p(99.9900) =     23.134 ms/op
     p(99.9990) =     23.134 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.691          ops/ms
Client.existUser                       thrpt         12.535          ops/ms
Client.getUser                         thrpt          9.316          ops/ms
Client.listUser                        thrpt          3.708          ops/ms
Client.createUser                       avgt          3.090           ms/op
Client.existUser                        avgt          1.863           ms/op
Client.getUser                          avgt          2.951           ms/op
Client.listUser                         avgt          9.637           ms/op
Client.createUser                     sample  10639   3.038 ± 0.054   ms/op
Client.createUser:createUser·p0.00    sample          0.740           ms/op
Client.createUser:createUser·p0.50    sample          2.871           ms/op
Client.createUser:createUser·p0.90    sample          3.576           ms/op
Client.createUser:createUser·p0.95    sample          4.194           ms/op
Client.createUser:createUser·p0.99    sample          6.005           ms/op
Client.createUser:createUser·p0.999   sample         23.986           ms/op
Client.createUser:createUser·p0.9999  sample         25.208           ms/op
Client.createUser:createUser·p1.00    sample         25.231           ms/op
Client.existUser                      sample  17311   1.856 ± 0.016   ms/op
Client.existUser:existUser·p0.00      sample          0.671           ms/op
Client.existUser:existUser·p0.50      sample          1.747           ms/op
Client.existUser:existUser·p0.90      sample          2.335           ms/op
Client.existUser:existUser·p0.95      sample          2.527           ms/op
Client.existUser:existUser·p0.99      sample          4.134           ms/op
Client.existUser:existUser·p0.999     sample         13.245           ms/op
Client.existUser:existUser·p0.9999    sample         13.618           ms/op
Client.existUser:existUser·p1.00      sample         13.713           ms/op
Client.getUser                        sample   9113   3.515 ± 0.045   ms/op
Client.getUser:getUser·p0.00          sample          0.901           ms/op
Client.getUser:getUser·p0.50          sample          3.428           ms/op
Client.getUser:getUser·p0.90          sample          4.489           ms/op
Client.getUser:getUser·p0.95          sample          5.014           ms/op
Client.getUser:getUser·p0.99          sample          6.700           ms/op
Client.getUser:getUser·p0.999         sample         19.449           ms/op
Client.getUser:getUser·p0.9999        sample         19.857           ms/op
Client.getUser:getUser·p1.00          sample         19.857           ms/op
Client.listUser                       sample   3800   8.408 ± 0.115   ms/op
Client.listUser:listUser·p0.00        sample          2.748           ms/op
Client.listUser:listUser·p0.50        sample          8.045           ms/op
Client.listUser:listUser·p0.90        sample         10.928           ms/op
Client.listUser:listUser·p0.95        sample         12.042           ms/op
Client.listUser:listUser·p0.99        sample         16.744           ms/op
Client.listUser:listUser·p0.999       sample         22.269           ms/op
Client.listUser:listUser·p0.9999      sample         23.134           ms/op
Client.listUser:listUser·p1.00        sample         23.134           ms/op
