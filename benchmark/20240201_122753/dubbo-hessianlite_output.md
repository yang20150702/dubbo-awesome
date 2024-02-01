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
# Warmup Iteration   1: 2.088 ops/ms
Iteration   1: 5.868 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.868 ops/ms


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
# Warmup Iteration   1: 5.232 ops/ms
Iteration   1: 10.995 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.995 ops/ms


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
# Warmup Iteration   1: 3.553 ops/ms
Iteration   1: 7.933 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.933 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.118 ops/ms
Iteration   1: 3.422 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.422 ops/ms


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
# Warmup Iteration   1: 5.037 ±(99.9%) 0.063 ms/op
Iteration   1: 3.118 ±(99.9%) 0.016 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.141 ±(99.9%) 0.033 ms/op
Iteration   1: 1.738 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.738 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.766 ±(99.9%) 0.049 ms/op
Iteration   1: 3.206 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.206 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.902 ±(99.9%) 0.222 ms/op
Iteration   1: 9.449 ±(99.9%) 0.085 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.449 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.555 ±(99.9%) 0.135 ms/op
Iteration   1: 3.090 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   1.206 ms/op
                 createUser·p0.50:   2.810 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   7.799 ms/op
                 createUser·p0.999:  14.330 ms/op
                 createUser·p0.9999: 16.383 ms/op
                 createUser·p1.00:   16.384 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10350
  mean =      3.090 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 1407 
    [ 2.500,  3.750) = 7618 
    [ 3.750,  5.000) = 1085 
    [ 5.000,  6.250) = 94 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      2.810 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      7.799 ms/op
     p(99.9000) =     14.330 ms/op
     p(99.9900) =     16.383 ms/op
     p(99.9990) =     16.384 ms/op
     p(99.9999) =     16.384 ms/op
    p(100.0000) =     16.384 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.319 ±(99.9%) 0.092 ms/op
Iteration   1: 1.854 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.475 ms/op
                 existUser·p0.50:   1.778 ms/op
                 existUser·p0.90:   2.228 ms/op
                 existUser·p0.95:   2.466 ms/op
                 existUser·p0.99:   3.969 ms/op
                 existUser·p0.999:  6.496 ms/op
                 existUser·p0.9999: 7.338 ms/op
                 existUser·p1.00:   7.635 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17250
  mean =      1.854 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 1 
    [0.500, 1.000) = 42 
    [1.000, 1.500) = 1193 
    [1.500, 2.000) = 12549 
    [2.000, 2.500) = 2702 
    [2.500, 3.000) = 490 
    [3.000, 3.500) = 58 
    [3.500, 4.000) = 59 
    [4.000, 4.500) = 73 
    [4.500, 5.000) = 37 
    [5.000, 5.500) = 4 
    [5.500, 6.000) = 17 
    [6.000, 6.500) = 8 
    [6.500, 7.000) = 15 
    [7.000, 7.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.475 ms/op
     p(50.0000) =      1.778 ms/op
     p(90.0000) =      2.228 ms/op
     p(95.0000) =      2.466 ms/op
     p(99.0000) =      3.969 ms/op
     p(99.9000) =      6.496 ms/op
     p(99.9900) =      7.338 ms/op
     p(99.9990) =      7.635 ms/op
     p(99.9999) =      7.635 ms/op
    p(100.0000) =      7.635 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.882 ±(99.9%) 0.128 ms/op
Iteration   1: 2.913 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   2.912 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  7.041 ms/op
                 getUser·p0.9999: 8.152 ms/op
                 getUser·p1.00:   8.167 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10990
  mean =      2.913 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 42 
    [1.500, 2.000) = 773 
    [2.000, 2.500) = 2603 
    [2.500, 3.000) = 2569 
    [3.000, 3.500) = 3058 
    [3.500, 4.000) = 1398 
    [4.000, 4.500) = 402 
    [4.500, 5.000) = 90 
    [5.000, 5.500) = 12 
    [5.500, 6.000) = 8 
    [6.000, 6.500) = 18 
    [6.500, 7.000) = 5 
    [7.000, 7.500) = 2 
    [7.500, 8.000) = 8 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =      7.041 ms/op
     p(99.9900) =      8.152 ms/op
     p(99.9990) =      8.167 ms/op
     p(99.9999) =      8.167 ms/op
    p(100.0000) =      8.167 ms/op


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
# Warmup Iteration   1: 13.541 ±(99.9%) 0.486 ms/op
Iteration   1: 7.868 ±(99.9%) 0.116 ms/op
                 listUser·p0.00:   2.933 ms/op
                 listUser·p0.50:   7.487 ms/op
                 listUser·p0.90:   10.306 ms/op
                 listUser·p0.95:   11.391 ms/op
                 listUser·p0.99:   15.627 ms/op
                 listUser·p0.999:  23.165 ms/op
                 listUser·p0.9999: 24.740 ms/op
                 listUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4054
  mean =      7.868 ±(99.9%) 0.116 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 130 
    [ 5.000,  7.500) = 1904 
    [ 7.500, 10.000) = 1550 
    [10.000, 12.500) = 360 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.933 ms/op
     p(50.0000) =      7.487 ms/op
     p(90.0000) =     10.306 ms/op
     p(95.0000) =     11.391 ms/op
     p(99.0000) =     15.627 ms/op
     p(99.9000) =     23.165 ms/op
     p(99.9900) =     24.740 ms/op
     p(99.9990) =     24.740 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.868          ops/ms
Client.existUser                       thrpt         10.995          ops/ms
Client.getUser                         thrpt          7.933          ops/ms
Client.listUser                        thrpt          3.422          ops/ms
Client.createUser                       avgt          3.118           ms/op
Client.existUser                        avgt          1.738           ms/op
Client.getUser                          avgt          3.206           ms/op
Client.listUser                         avgt          9.449           ms/op
Client.createUser                     sample  10350   3.090 ± 0.033   ms/op
Client.createUser:createUser·p0.00    sample          1.206           ms/op
Client.createUser:createUser·p0.50    sample          2.810           ms/op
Client.createUser:createUser·p0.90    sample          3.961           ms/op
Client.createUser:createUser·p0.95    sample          4.415           ms/op
Client.createUser:createUser·p0.99    sample          7.799           ms/op
Client.createUser:createUser·p0.999   sample         14.330           ms/op
Client.createUser:createUser·p0.9999  sample         16.383           ms/op
Client.createUser:createUser·p1.00    sample         16.384           ms/op
Client.existUser                      sample  17250   1.854 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.475           ms/op
Client.existUser:existUser·p0.50      sample          1.778           ms/op
Client.existUser:existUser·p0.90      sample          2.228           ms/op
Client.existUser:existUser·p0.95      sample          2.466           ms/op
Client.existUser:existUser·p0.99      sample          3.969           ms/op
Client.existUser:existUser·p0.999     sample          6.496           ms/op
Client.existUser:existUser·p0.9999    sample          7.338           ms/op
Client.existUser:existUser·p1.00      sample          7.635           ms/op
Client.getUser                        sample  10990   2.913 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          1.161           ms/op
Client.getUser:getUser·p0.50          sample          2.912           ms/op
Client.getUser:getUser·p0.90          sample          3.715           ms/op
Client.getUser:getUser·p0.95          sample          3.990           ms/op
Client.getUser:getUser·p0.99          sample          4.686           ms/op
Client.getUser:getUser·p0.999         sample          7.041           ms/op
Client.getUser:getUser·p0.9999        sample          8.152           ms/op
Client.getUser:getUser·p1.00          sample          8.167           ms/op
Client.listUser                       sample   4054   7.868 ± 0.116   ms/op
Client.listUser:listUser·p0.00        sample          2.933           ms/op
Client.listUser:listUser·p0.50        sample          7.487           ms/op
Client.listUser:listUser·p0.90        sample         10.306           ms/op
Client.listUser:listUser·p0.95        sample         11.391           ms/op
Client.listUser:listUser·p0.99        sample         15.627           ms/op
Client.listUser:listUser·p0.999       sample         23.165           ms/op
Client.listUser:listUser·p0.9999      sample         24.740           ms/op
Client.listUser:listUser·p1.00        sample         24.740           ms/op
