# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.032 ops/ms
Iteration   1: 2.410 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.410 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 2.285 ops/ms
Iteration   1: 7.675 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.675 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.081 ops/ms
Iteration   1: 4.862 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.862 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.915 ops/ms
Iteration   1: 1.286 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.286 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 18.320 ±(99.9%) 0.250 ms/op
Iteration   1: 8.079 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.079 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.316 ±(99.9%) 0.083 ms/op
Iteration   1: 3.959 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.959 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.306 ±(99.9%) 0.145 ms/op
Iteration   1: 4.326 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.326 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 25.681 ±(99.9%) 0.728 ms/op
Iteration   1: 17.730 ±(99.9%) 0.128 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.730 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.404 ±(99.9%) 0.438 ms/op
Iteration   1: 5.920 ±(99.9%) 0.084 ms/op
                 createUser·p0.00:   2.056 ms/op
                 createUser·p0.50:   5.472 ms/op
                 createUser·p0.90:   6.095 ms/op
                 createUser·p0.95:   8.238 ms/op
                 createUser·p0.99:   16.220 ms/op
                 createUser·p0.999:  16.663 ms/op
                 createUser·p0.9999: 17.170 ms/op
                 createUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5527
  mean =      5.920 ±(99.9%) 0.084 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 3 
    [ 2.500,  3.750) = 0 
    [ 3.750,  5.000) = 226 
    [ 5.000,  6.250) = 4837 
    [ 6.250,  7.500) = 166 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 94 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 51 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.056 ms/op
     p(50.0000) =      5.472 ms/op
     p(90.0000) =      6.095 ms/op
     p(95.0000) =      8.238 ms/op
     p(99.0000) =     16.220 ms/op
     p(99.9000) =     16.663 ms/op
     p(99.9900) =     17.170 ms/op
     p(99.9990) =     17.170 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.941 ±(99.9%) 0.182 ms/op
Iteration   1: 3.060 ±(99.9%) 0.044 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.803 ms/op
                 existUser·p0.99:   10.976 ms/op
                 existUser·p0.999:  13.173 ms/op
                 existUser·p0.9999: 13.238 ms/op
                 existUser·p1.00:   13.238 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 10506
  mean =      3.060 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 2228 
    [ 2.500,  3.750) = 7727 
    [ 3.750,  5.000) = 120 
    [ 5.000,  6.250) = 126 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 139 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.803 ms/op
     p(99.0000) =     10.976 ms/op
     p(99.9000) =     13.173 ms/op
     p(99.9900) =     13.238 ms/op
     p(99.9990) =     13.238 ms/op
     p(99.9999) =     13.238 ms/op
    p(100.0000) =     13.238 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 7.961 ±(99.9%) 0.233 ms/op
Iteration   1: 4.695 ±(99.9%) 0.049 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   4.669 ms/op
                 getUser·p0.90:   5.475 ms/op
                 getUser·p0.95:   6.291 ms/op
                 getUser·p0.99:   9.710 ms/op
                 getUser·p0.999:  13.943 ms/op
                 getUser·p0.9999: 14.221 ms/op
                 getUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6816
  mean =      4.695 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 117 
    [ 2.500,  3.750) = 1010 
    [ 3.750,  5.000) = 3518 
    [ 5.000,  6.250) = 1804 
    [ 6.250,  7.500) = 201 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      5.475 ms/op
     p(95.0000) =      6.291 ms/op
     p(99.0000) =      9.710 ms/op
     p(99.9000) =     13.943 ms/op
     p(99.9900) =     14.221 ms/op
     p(99.9990) =     14.221 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 26.279 ±(99.9%) 0.730 ms/op
Iteration   1: 15.515 ±(99.9%) 0.204 ms/op
                 listUser·p0.00:   7.733 ms/op
                 listUser·p0.50:   15.663 ms/op
                 listUser·p0.90:   17.760 ms/op
                 listUser·p0.95:   18.506 ms/op
                 listUser·p0.99:   29.000 ms/op
                 listUser·p0.999:  29.809 ms/op
                 listUser·p0.9999: 31.195 ms/op
                 listUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2092
  mean =     15.515 ±(99.9%) 0.204 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 694 
    [15.000, 17.500) = 1040 
    [17.500, 20.000) = 175 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      7.733 ms/op
     p(50.0000) =     15.663 ms/op
     p(90.0000) =     17.760 ms/op
     p(95.0000) =     18.506 ms/op
     p(99.0000) =     29.000 ms/op
     p(99.9000) =     29.809 ms/op
     p(99.9900) =     31.195 ms/op
     p(99.9990) =     31.195 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          2.410          ops/ms
Client.existUser                       thrpt          7.675          ops/ms
Client.getUser                         thrpt          4.862          ops/ms
Client.listUser                        thrpt          1.286          ops/ms
Client.createUser                       avgt          8.079           ms/op
Client.existUser                        avgt          3.959           ms/op
Client.getUser                          avgt          4.326           ms/op
Client.listUser                         avgt         17.730           ms/op
Client.createUser                     sample   5527   5.920 ± 0.084   ms/op
Client.createUser:createUser·p0.00    sample          2.056           ms/op
Client.createUser:createUser·p0.50    sample          5.472           ms/op
Client.createUser:createUser·p0.90    sample          6.095           ms/op
Client.createUser:createUser·p0.95    sample          8.238           ms/op
Client.createUser:createUser·p0.99    sample         16.220           ms/op
Client.createUser:createUser·p0.999   sample         16.663           ms/op
Client.createUser:createUser·p0.9999  sample         17.170           ms/op
Client.createUser:createUser·p1.00    sample         17.170           ms/op
Client.existUser                      sample  10506   3.060 ± 0.044   ms/op
Client.existUser:existUser·p0.00      sample          0.721           ms/op
Client.existUser:existUser·p0.50      sample          2.908           ms/op
Client.existUser:existUser·p0.90      sample          3.428           ms/op
Client.existUser:existUser·p0.95      sample          3.803           ms/op
Client.existUser:existUser·p0.99      sample         10.976           ms/op
Client.existUser:existUser·p0.999     sample         13.173           ms/op
Client.existUser:existUser·p0.9999    sample         13.238           ms/op
Client.existUser:existUser·p1.00      sample         13.238           ms/op
Client.getUser                        sample   6816   4.695 ± 0.049   ms/op
Client.getUser:getUser·p0.00          sample          0.748           ms/op
Client.getUser:getUser·p0.50          sample          4.669           ms/op
Client.getUser:getUser·p0.90          sample          5.475           ms/op
Client.getUser:getUser·p0.95          sample          6.291           ms/op
Client.getUser:getUser·p0.99          sample          9.710           ms/op
Client.getUser:getUser·p0.999         sample         13.943           ms/op
Client.getUser:getUser·p0.9999        sample         14.221           ms/op
Client.getUser:getUser·p1.00          sample         14.221           ms/op
Client.listUser                       sample   2092  15.515 ± 0.204   ms/op
Client.listUser:listUser·p0.00        sample          7.733           ms/op
Client.listUser:listUser·p0.50        sample         15.663           ms/op
Client.listUser:listUser·p0.90        sample         17.760           ms/op
Client.listUser:listUser·p0.95        sample         18.506           ms/op
Client.listUser:listUser·p0.99        sample         29.000           ms/op
Client.listUser:listUser·p0.999       sample         29.809           ms/op
Client.listUser:listUser·p0.9999      sample         31.195           ms/op
Client.listUser:listUser·p1.00        sample         31.195           ms/op
