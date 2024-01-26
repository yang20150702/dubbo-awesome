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
# Warmup Iteration   1: 2.564 ops/ms
Iteration   1: 5.817 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.817 ops/ms


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
# Warmup Iteration   1: 5.730 ops/ms
Iteration   1: 12.449 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.449 ops/ms


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
# Warmup Iteration   1: 3.676 ops/ms
Iteration   1: 8.241 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.241 ops/ms


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
# Warmup Iteration   1: 2.041 ops/ms
Iteration   1: 3.746 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.746 ops/ms


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
# Warmup Iteration   1: 5.453 ±(99.9%) 0.080 ms/op
Iteration   1: 3.057 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.057 ms/op


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
# Warmup Iteration   1: 3.458 ±(99.9%) 0.040 ms/op
Iteration   1: 2.002 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.002 ms/op


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
# Warmup Iteration   1: 4.856 ±(99.9%) 0.047 ms/op
Iteration   1: 2.993 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.993 ms/op


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
# Warmup Iteration   1: 11.447 ±(99.9%) 0.148 ms/op
Iteration   1: 8.268 ±(99.9%) 0.077 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.268 ms/op


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
# Warmup Iteration   1: 5.192 ±(99.9%) 0.106 ms/op
Iteration   1: 3.016 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   1.456 ms/op
                 createUser·p0.50:   2.789 ms/op
                 createUser·p0.90:   3.575 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   7.022 ms/op
                 createUser·p0.999:  15.516 ms/op
                 createUser·p0.9999: 18.505 ms/op
                 createUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10592
  mean =      3.016 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1360 
    [ 2.500,  3.750) = 8532 
    [ 3.750,  5.000) = 437 
    [ 5.000,  6.250) = 125 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.456 ms/op
     p(50.0000) =      2.789 ms/op
     p(90.0000) =      3.575 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      7.022 ms/op
     p(99.9000) =     15.516 ms/op
     p(99.9900) =     18.505 ms/op
     p(99.9990) =     18.645 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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
# Warmup Iteration   1: 3.560 ±(99.9%) 0.082 ms/op
Iteration   1: 1.748 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.547 ms/op
                 existUser·p0.50:   1.663 ms/op
                 existUser·p0.90:   2.073 ms/op
                 existUser·p0.95:   2.286 ms/op
                 existUser·p0.99:   3.639 ms/op
                 existUser·p0.999:  27.352 ms/op
                 existUser·p0.9999: 27.842 ms/op
                 existUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18289
  mean =      1.748 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17816 
    [ 2.500,  5.000) = 402 
    [ 5.000,  7.500) = 39 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      1.663 ms/op
     p(90.0000) =      2.073 ms/op
     p(95.0000) =      2.286 ms/op
     p(99.0000) =      3.639 ms/op
     p(99.9000) =     27.352 ms/op
     p(99.9900) =     27.842 ms/op
     p(99.9990) =     27.951 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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
# Warmup Iteration   1: 5.129 ±(99.9%) 0.123 ms/op
Iteration   1: 3.235 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.556 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   4.067 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.229 ms/op
                 getUser·p0.999:  8.023 ms/op
                 getUser·p0.9999: 8.798 ms/op
                 getUser·p1.00:   8.798 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9867
  mean =      3.235 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 5 
    [1.000, 1.500) = 33 
    [1.500, 2.000) = 166 
    [2.000, 2.500) = 1419 
    [2.500, 3.000) = 2559 
    [3.000, 3.500) = 2104 
    [3.500, 4.000) = 2389 
    [4.000, 4.500) = 782 
    [4.500, 5.000) = 153 
    [5.000, 5.500) = 90 
    [5.500, 6.000) = 54 
    [6.000, 6.500) = 43 
    [6.500, 7.000) = 19 
    [7.000, 7.500) = 31 
    [7.500, 8.000) = 10 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.229 ms/op
     p(99.9000) =      8.023 ms/op
     p(99.9900) =      8.798 ms/op
     p(99.9990) =      8.798 ms/op
     p(99.9999) =      8.798 ms/op
    p(100.0000) =      8.798 ms/op


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
# Warmup Iteration   1: 12.373 ±(99.9%) 0.429 ms/op
Iteration   1: 9.661 ±(99.9%) 0.174 ms/op
                 listUser·p0.00:   2.089 ms/op
                 listUser·p0.50:   9.142 ms/op
                 listUser·p0.90:   13.309 ms/op
                 listUser·p0.95:   15.084 ms/op
                 listUser·p0.99:   18.347 ms/op
                 listUser·p0.999:  29.129 ms/op
                 listUser·p0.9999: 33.686 ms/op
                 listUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3326
  mean =      9.661 ±(99.9%) 0.174 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 59 
    [ 5.000,  7.500) = 728 
    [ 7.500, 10.000) = 1249 
    [10.000, 12.500) = 753 
    [12.500, 15.000) = 367 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.089 ms/op
     p(50.0000) =      9.142 ms/op
     p(90.0000) =     13.309 ms/op
     p(95.0000) =     15.084 ms/op
     p(99.0000) =     18.347 ms/op
     p(99.9000) =     29.129 ms/op
     p(99.9900) =     33.686 ms/op
     p(99.9990) =     33.686 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.817          ops/ms
Client.existUser                       thrpt         12.449          ops/ms
Client.getUser                         thrpt          8.241          ops/ms
Client.listUser                        thrpt          3.746          ops/ms
Client.createUser                       avgt          3.057           ms/op
Client.existUser                        avgt          2.002           ms/op
Client.getUser                          avgt          2.993           ms/op
Client.listUser                         avgt          8.268           ms/op
Client.createUser                     sample  10592   3.016 ± 0.033   ms/op
Client.createUser:createUser·p0.00    sample          1.456           ms/op
Client.createUser:createUser·p0.50    sample          2.789           ms/op
Client.createUser:createUser·p0.90    sample          3.575           ms/op
Client.createUser:createUser·p0.95    sample          3.903           ms/op
Client.createUser:createUser·p0.99    sample          7.022           ms/op
Client.createUser:createUser·p0.999   sample         15.516           ms/op
Client.createUser:createUser·p0.9999  sample         18.505           ms/op
Client.createUser:createUser·p1.00    sample         18.645           ms/op
Client.existUser                      sample  18289   1.748 ± 0.028   ms/op
Client.existUser:existUser·p0.00      sample          0.547           ms/op
Client.existUser:existUser·p0.50      sample          1.663           ms/op
Client.existUser:existUser·p0.90      sample          2.073           ms/op
Client.existUser:existUser·p0.95      sample          2.286           ms/op
Client.existUser:existUser·p0.99      sample          3.639           ms/op
Client.existUser:existUser·p0.999     sample         27.352           ms/op
Client.existUser:existUser·p0.9999    sample         27.842           ms/op
Client.existUser:existUser·p1.00      sample         27.951           ms/op
Client.getUser                        sample   9867   3.235 ± 0.027   ms/op
Client.getUser:getUser·p0.00          sample          0.556           ms/op
Client.getUser:getUser·p0.50          sample          3.195           ms/op
Client.getUser:getUser·p0.90          sample          4.067           ms/op
Client.getUser:getUser·p0.95          sample          4.358           ms/op
Client.getUser:getUser·p0.99          sample          6.229           ms/op
Client.getUser:getUser·p0.999         sample          8.023           ms/op
Client.getUser:getUser·p0.9999        sample          8.798           ms/op
Client.getUser:getUser·p1.00          sample          8.798           ms/op
Client.listUser                       sample   3326   9.661 ± 0.174   ms/op
Client.listUser:listUser·p0.00        sample          2.089           ms/op
Client.listUser:listUser·p0.50        sample          9.142           ms/op
Client.listUser:listUser·p0.90        sample         13.309           ms/op
Client.listUser:listUser·p0.95        sample         15.084           ms/op
Client.listUser:listUser·p0.99        sample         18.347           ms/op
Client.listUser:listUser·p0.999       sample         29.129           ms/op
Client.listUser:listUser·p0.9999      sample         33.686           ms/op
Client.listUser:listUser·p1.00        sample         33.686           ms/op
