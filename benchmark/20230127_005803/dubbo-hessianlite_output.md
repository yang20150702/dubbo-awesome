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
# Warmup Iteration   1: 1.106 ops/ms
Iteration   1: 2.540 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.540 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.545 ops/ms
Iteration   1: 6.813 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.813 ops/ms


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
# Warmup Iteration   1: 2.345 ops/ms
Iteration   1: 4.984 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.984 ops/ms


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
# Warmup Iteration   1: 0.830 ops/ms
Iteration   1: 1.415 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.415 ops/ms


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
# Warmup Iteration   1: 15.502 ±(99.9%) 0.294 ms/op
Iteration   1: 7.892 ±(99.9%) 0.045 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.892 ms/op


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
# Warmup Iteration   1: 7.127 ±(99.9%) 0.101 ms/op
Iteration   1: 4.101 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.101 ms/op


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
# Warmup Iteration   1: 10.813 ±(99.9%) 0.130 ms/op
Iteration   1: 4.516 ±(99.9%) 0.046 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.516 ms/op


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
# Warmup Iteration   1: 25.181 ±(99.9%) 0.360 ms/op
Iteration   1: 15.820 ±(99.9%) 0.068 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.820 ms/op


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
# Warmup Iteration   1: 11.246 ±(99.9%) 0.464 ms/op
Iteration   1: 6.595 ±(99.9%) 0.084 ms/op
                 createUser·p0.00:   3.604 ms/op
                 createUser·p0.50:   6.513 ms/op
                 createUser·p0.90:   7.242 ms/op
                 createUser·p0.95:   8.266 ms/op
                 createUser·p0.99:   17.697 ms/op
                 createUser·p0.999:  19.764 ms/op
                 createUser·p0.9999: 19.923 ms/op
                 createUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4846
  mean =      6.595 ±(99.9%) 0.084 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 11 
    [ 3.750,  5.000) = 503 
    [ 5.000,  6.250) = 834 
    [ 6.250,  7.500) = 3219 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      3.604 ms/op
     p(50.0000) =      6.513 ms/op
     p(90.0000) =      7.242 ms/op
     p(95.0000) =      8.266 ms/op
     p(99.0000) =     17.697 ms/op
     p(99.9000) =     19.764 ms/op
     p(99.9900) =     19.923 ms/op
     p(99.9990) =     19.923 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


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
# Warmup Iteration   1: 6.869 ±(99.9%) 0.182 ms/op
Iteration   1: 3.089 ±(99.9%) 0.039 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   9.634 ms/op
                 existUser·p0.999:  12.878 ms/op
                 existUser·p0.9999: 13.008 ms/op
                 existUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 10484
  mean =      3.089 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 2671 
    [ 2.500,  3.750) = 7291 
    [ 3.750,  5.000) = 205 
    [ 5.000,  6.250) = 67 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      9.634 ms/op
     p(99.9000) =     12.878 ms/op
     p(99.9900) =     13.008 ms/op
     p(99.9990) =     13.009 ms/op
     p(99.9999) =     13.009 ms/op
    p(100.0000) =     13.009 ms/op


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
# Warmup Iteration   1: 9.366 ±(99.9%) 0.388 ms/op
Iteration   1: 4.715 ±(99.9%) 0.065 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   4.588 ms/op
                 getUser·p0.90:   5.612 ms/op
                 getUser·p0.95:   6.210 ms/op
                 getUser·p0.99:   10.322 ms/op
                 getUser·p0.999:  25.690 ms/op
                 getUser·p0.9999: 25.919 ms/op
                 getUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6832
  mean =      4.715 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 223 
    [ 2.500,  5.000) = 5087 
    [ 5.000,  7.500) = 1405 
    [ 7.500, 10.000) = 44 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.612 ms/op
     p(95.0000) =      6.210 ms/op
     p(99.0000) =     10.322 ms/op
     p(99.9000) =     25.690 ms/op
     p(99.9900) =     25.919 ms/op
     p(99.9990) =     25.919 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 28.541 ±(99.9%) 0.829 ms/op
Iteration   1: 15.855 ±(99.9%) 0.328 ms/op
                 listUser·p0.00:   6.636 ms/op
                 listUser·p0.50:   15.073 ms/op
                 listUser·p0.90:   21.201 ms/op
                 listUser·p0.95:   22.774 ms/op
                 listUser·p0.99:   27.787 ms/op
                 listUser·p0.999:  32.865 ms/op
                 listUser·p0.9999: 33.194 ms/op
                 listUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2003
  mean =     15.855 ±(99.9%) 0.328 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 14 
    [ 7.500, 10.000) = 202 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 549 
    [15.000, 17.500) = 403 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 397 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      6.636 ms/op
     p(50.0000) =     15.073 ms/op
     p(90.0000) =     21.201 ms/op
     p(95.0000) =     22.774 ms/op
     p(99.0000) =     27.787 ms/op
     p(99.9000) =     32.865 ms/op
     p(99.9900) =     33.194 ms/op
     p(99.9990) =     33.194 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          2.540          ops/ms
Client.existUser                       thrpt          6.813          ops/ms
Client.getUser                         thrpt          4.984          ops/ms
Client.listUser                        thrpt          1.415          ops/ms
Client.createUser                       avgt          7.892           ms/op
Client.existUser                        avgt          4.101           ms/op
Client.getUser                          avgt          4.516           ms/op
Client.listUser                         avgt         15.820           ms/op
Client.createUser                     sample   4846   6.595 ± 0.084   ms/op
Client.createUser:createUser·p0.00    sample          3.604           ms/op
Client.createUser:createUser·p0.50    sample          6.513           ms/op
Client.createUser:createUser·p0.90    sample          7.242           ms/op
Client.createUser:createUser·p0.95    sample          8.266           ms/op
Client.createUser:createUser·p0.99    sample         17.697           ms/op
Client.createUser:createUser·p0.999   sample         19.764           ms/op
Client.createUser:createUser·p0.9999  sample         19.923           ms/op
Client.createUser:createUser·p1.00    sample         19.923           ms/op
Client.existUser                      sample  10484   3.089 ± 0.039   ms/op
Client.existUser:existUser·p0.00      sample          0.771           ms/op
Client.existUser:existUser·p0.50      sample          3.011           ms/op
Client.existUser:existUser·p0.90      sample          3.564           ms/op
Client.existUser:existUser·p0.95      sample          3.736           ms/op
Client.existUser:existUser·p0.99      sample          9.634           ms/op
Client.existUser:existUser·p0.999     sample         12.878           ms/op
Client.existUser:existUser·p0.9999    sample         13.008           ms/op
Client.existUser:existUser·p1.00      sample         13.009           ms/op
Client.getUser                        sample   6832   4.715 ± 0.065   ms/op
Client.getUser:getUser·p0.00          sample          1.090           ms/op
Client.getUser:getUser·p0.50          sample          4.588           ms/op
Client.getUser:getUser·p0.90          sample          5.612           ms/op
Client.getUser:getUser·p0.95          sample          6.210           ms/op
Client.getUser:getUser·p0.99          sample         10.322           ms/op
Client.getUser:getUser·p0.999         sample         25.690           ms/op
Client.getUser:getUser·p0.9999        sample         25.919           ms/op
Client.getUser:getUser·p1.00          sample         25.919           ms/op
Client.listUser                       sample   2003  15.855 ± 0.328   ms/op
Client.listUser:listUser·p0.00        sample          6.636           ms/op
Client.listUser:listUser·p0.50        sample         15.073           ms/op
Client.listUser:listUser·p0.90        sample         21.201           ms/op
Client.listUser:listUser·p0.95        sample         22.774           ms/op
Client.listUser:listUser·p0.99        sample         27.787           ms/op
Client.listUser:listUser·p0.999       sample         32.865           ms/op
Client.listUser:listUser·p0.9999      sample         33.194           ms/op
Client.listUser:listUser·p1.00        sample         33.194           ms/op
