# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.120 ops/ms
Iteration   1: 5.606 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.606 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.152 ops/ms
Iteration   1: 11.784 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.784 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.212 ops/ms
Iteration   1: 8.368 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.368 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.207 ops/ms
Iteration   1: 3.720 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.720 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.373 ±(99.9%) 0.080 ms/op
Iteration   1: 3.428 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.428 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.620 ±(99.9%) 0.031 ms/op
Iteration   1: 1.920 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.920 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.262 ±(99.9%) 0.068 ms/op
Iteration   1: 3.259 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.259 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.386 ±(99.9%) 0.163 ms/op
Iteration   1: 10.157 ±(99.9%) 0.120 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  10.157 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.259 ±(99.9%) 0.121 ms/op
Iteration   1: 2.980 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   1.233 ms/op
                 createUser·p0.50:   2.781 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.111 ms/op
                 createUser·p0.999:  18.022 ms/op
                 createUser·p0.9999: 19.716 ms/op
                 createUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10801
  mean =      2.980 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1891 
    [ 2.500,  3.750) = 7922 
    [ 3.750,  5.000) = 857 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      2.781 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      5.111 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     19.716 ms/op
     p(99.9990) =     19.726 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.212 ±(99.9%) 0.078 ms/op
Iteration   1: 2.044 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.586 ms/op
                 existUser·p0.50:   1.958 ms/op
                 existUser·p0.90:   2.548 ms/op
                 existUser·p0.95:   2.830 ms/op
                 existUser·p0.99:   3.525 ms/op
                 existUser·p0.999:  4.768 ms/op
                 existUser·p0.9999: 5.419 ms/op
                 existUser·p1.00:   5.489 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15640
  mean =      2.044 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 38 
    [1.000, 1.500) = 588 
    [1.500, 2.000) = 8107 
    [2.000, 2.500) = 5069 
    [2.500, 3.000) = 1232 
    [3.000, 3.500) = 434 
    [3.500, 4.000) = 97 
    [4.000, 4.500) = 24 
    [4.500, 5.000) = 42 
    [5.000, 5.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      1.958 ms/op
     p(90.0000) =      2.548 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      3.525 ms/op
     p(99.9000) =      4.768 ms/op
     p(99.9900) =      5.419 ms/op
     p(99.9990) =      5.489 ms/op
     p(99.9999) =      5.489 ms/op
    p(100.0000) =      5.489 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.870 ±(99.9%) 0.142 ms/op
Iteration   1: 2.870 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   2.740 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  6.999 ms/op
                 getUser·p0.9999: 8.691 ms/op
                 getUser·p1.00:   8.765 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11337
  mean =      2.870 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 36 
    [1.500, 2.000) = 500 
    [2.000, 2.500) = 2826 
    [2.500, 3.000) = 4039 
    [3.000, 3.500) = 1993 
    [3.500, 4.000) = 1351 
    [4.000, 4.500) = 429 
    [4.500, 5.000) = 101 
    [5.000, 5.500) = 29 
    [5.500, 6.000) = 15 
    [6.000, 6.500) = 4 
    [6.500, 7.000) = 3 
    [7.000, 7.500) = 6 
    [7.500, 8.000) = 2 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      2.740 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      6.999 ms/op
     p(99.9900) =      8.691 ms/op
     p(99.9990) =      8.765 ms/op
     p(99.9999) =      8.765 ms/op
    p(100.0000) =      8.765 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 12.374 ±(99.9%) 0.452 ms/op
Iteration   1: 7.942 ±(99.9%) 0.129 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   7.520 ms/op
                 listUser·p0.90:   10.076 ms/op
                 listUser·p0.95:   11.125 ms/op
                 listUser·p0.99:   19.881 ms/op
                 listUser·p0.999:  26.374 ms/op
                 listUser·p0.9999: 29.524 ms/op
                 listUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4026
  mean =      7.942 ±(99.9%) 0.129 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 103 
    [ 5.000,  7.500) = 1889 
    [ 7.500, 10.000) = 1614 
    [10.000, 12.500) = 295 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.404 ms/op
     p(50.0000) =      7.520 ms/op
     p(90.0000) =     10.076 ms/op
     p(95.0000) =     11.125 ms/op
     p(99.0000) =     19.881 ms/op
     p(99.9000) =     26.374 ms/op
     p(99.9900) =     29.524 ms/op
     p(99.9990) =     29.524 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.606          ops/ms
Client.existUser                       thrpt         11.784          ops/ms
Client.getUser                         thrpt          8.368          ops/ms
Client.listUser                        thrpt          3.720          ops/ms
Client.createUser                       avgt          3.428           ms/op
Client.existUser                        avgt          1.920           ms/op
Client.getUser                          avgt          3.259           ms/op
Client.listUser                         avgt         10.157           ms/op
Client.createUser                     sample  10801   2.980 ± 0.032   ms/op
Client.createUser:createUser·p0.00    sample          1.233           ms/op
Client.createUser:createUser·p0.50    sample          2.781           ms/op
Client.createUser:createUser·p0.90    sample          3.678           ms/op
Client.createUser:createUser·p0.95    sample          4.043           ms/op
Client.createUser:createUser·p0.99    sample          5.111           ms/op
Client.createUser:createUser·p0.999   sample         18.022           ms/op
Client.createUser:createUser·p0.9999  sample         19.716           ms/op
Client.createUser:createUser·p1.00    sample         19.726           ms/op
Client.existUser                      sample  15640   2.044 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          0.586           ms/op
Client.existUser:existUser·p0.50      sample          1.958           ms/op
Client.existUser:existUser·p0.90      sample          2.548           ms/op
Client.existUser:existUser·p0.95      sample          2.830           ms/op
Client.existUser:existUser·p0.99      sample          3.525           ms/op
Client.existUser:existUser·p0.999     sample          4.768           ms/op
Client.existUser:existUser·p0.9999    sample          5.419           ms/op
Client.existUser:existUser·p1.00      sample          5.489           ms/op
Client.getUser                        sample  11337   2.870 ± 0.020   ms/op
Client.getUser:getUser·p0.00          sample          1.057           ms/op
Client.getUser:getUser·p0.50          sample          2.740           ms/op
Client.getUser:getUser·p0.90          sample          3.715           ms/op
Client.getUser:getUser·p0.95          sample          4.026           ms/op
Client.getUser:getUser·p0.99          sample          4.604           ms/op
Client.getUser:getUser·p0.999         sample          6.999           ms/op
Client.getUser:getUser·p0.9999        sample          8.691           ms/op
Client.getUser:getUser·p1.00          sample          8.765           ms/op
Client.listUser                       sample   4026   7.942 ± 0.129   ms/op
Client.listUser:listUser·p0.00        sample          2.404           ms/op
Client.listUser:listUser·p0.50        sample          7.520           ms/op
Client.listUser:listUser·p0.90        sample         10.076           ms/op
Client.listUser:listUser·p0.95        sample         11.125           ms/op
Client.listUser:listUser·p0.99        sample         19.881           ms/op
Client.listUser:listUser·p0.999       sample         26.374           ms/op
Client.listUser:listUser·p0.9999      sample         29.524           ms/op
Client.listUser:listUser·p1.00        sample         29.524           ms/op
